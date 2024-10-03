<template>
    <div class="bg-gray-800 h-screen flex justify-center items-center">
        <div class="bg-white rounded-lg p-4 pt-1 w-auto flex md:flex-row-reverse flex-col items-center" v-if="error.statusCode == 404">
            <div class="flex flex-col items-center justify-center">
                <span class="text-5xl font-semibold text-indigo-700">{{ error.statusCode }}</span>
                <h1 class="mt-5 text-4xl font-medium text-teal-600">{{ error.message }}</h1>
                <p class="mt-6 text-lg font-medium">متسفانه صفحه ای  مورد نظر پیدا نشد؟؟</p>
                <button @click="handlerNotFound" class="px-3 py-2 outline-none mt-7 text-white bg-purple-600 rounded-lg hover:translate-y-3 delay-300 duration-500">برگشت به صفحه اصلی</button>
            </div>
            <img class="md:w-96 w-52 h-auto rounded object-center object-cover" src="/image/NotFound.jpg" alt="NotFoundImage">
        </div>
        <div class="bg-white rounded-lg p-4 pt-1 w-auto flex md:flex-row-reverse flex-col items-center" v-else>
            <div class="flex flex-col items-center justify-center">
                <span class="text-7xl font-semibold text-indigo-700">{{ error.statusCode }}</span>
                <h1 class="mt-5 text-4xl font-medium text-teal-600">{{ error.message }}</h1>
                <p class="mt-6 text-lg font-medium">خطا از سمت سرور لطف مجدد تلاش کنید!</p>
                <button @click="handlerNotFound" class="px-3 py-2 outline-none mt-7 text-white bg-purple-600 rounded-lg hover:translate-y-3 delay-300 duration-500">برگشت به صفحه اصلی</button>
            </div>
            <img class="md:w-96 w-52 h-auto rounded object-center object-cover" src="/image/server-error.jpg" alt="Server Error">
        </div>
    </div>
</template>
<script setup lang="js">
defineProps(['error'])
const handlerNotFound = ()=>clearError({redirect:'/'})
</script>
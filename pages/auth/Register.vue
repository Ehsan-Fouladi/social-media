<template>
    <div class="bg-gray-800 h-screen flex justify-center items-center">
        <div class="bg-white rounded-md  w-full-screen shadow-2xl shadow-teal-600">
            <div class="flex justify-center mt-10">
                <span class="font-semibold text-3xl hover:text-yellow-300 hover:origin-top-left hover:rotate-12 delay-300 duration-200 ease-in">ثبت نام در سایت</span>
            </div>
            <form method="get" class="p-4 mt-36">
                <input type="text" placeholder="ایمیل خود را وارد کنید." class="border-b-2 border-black outline-none w-full rounded px-10 py-2 text-purple-700 placeholder:text-gray-400">
                <input type="password" placeholder="گذرواژه خود را وارد کنید." class="border-b-2 border-black outline-none w-full rounded px-10 py-2 text-purple-700 placeholder:text-gray-400 mt-10">
                <input type="password" placeholder="گذرواژه دوم خود را وارد کنید." class="border-b-2 border-black outline-none w-full rounded px-10 py-2 text-purple-700 placeholder:text-gray-400 mt-10">
                <div class="mt-6 flex flex-col md:flex-row md:justify-between">
                    <div class="flex items-center mr-7">
                        <input type="checkbox" class="w-4 h-4 rounded-full">
                        <span class="mr-2 font-medium text-base"> مرا بخاطر بسپار</span>
                    </div>
                </div>
                <div class="flex flex-col justify-center items-center mt-10">
                    <NuxtLink class="bg-violet-700 py-3 px-10 rounded text-white outline-none hover:scale-110 duration-500 ease-in">ثبت نام</NuxtLink>
                    <NuxtLink to="/auth/login/" class="bg-gray-800 py-3 px-10 rounded text-white outline-none hover:scale-110 duration-300 ease-in mt-3">ورود به سایت</NuxtLink>
                </div>
            </form>
        </div>
    </div>
</template>
<script setup>
definePageMeta({layout:false})
</script>
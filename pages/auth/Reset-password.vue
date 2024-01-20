<template>
    <div class="bg-gray-800 h-screen flex justify-center items-center">
        <div class="bg-white rounded-md w-full-screen shadow-2xl shadow-teal-600">
            <div class="flex justify-center mt-10">
                <span class="font-semibold text-3xl hover:text-yellow-300 hover:origin-top-left hover:rotate-12 delay-300 duration-200 ease-in">تغییر گذرواژه</span>
            </div>
            <form method="get" class="p-4 mt-36">
                <input type="text" placeholder="ایمیل خود را وارد کنید." class="border-b-2 border-black outline-none w-full rounded px-10 py-2 text-purple-700 placeholder:text-gray-400 mt-10">

                <div class="mt-20 flex justify-center items-center">
                    <NuxtLink class="bg-violet-700 py-3 px-10 rounded text-white outline-none hover:scale-110 duration-300 ease-in">تایید</NuxtLink>
                </div>
                <div class="flex flex-col md:flex-row items-center md:justify-evenly">
                    <NuxtLink to="/auth/login/" class="bg-gray-800 py-3 px-10 rounded text-white outline-none hover:scale-110 duration-500 ease-in mt-3 w-60 md:w-auto">ورود به سایت</NuxtLink>
                    <NuxtLink to="/" class="bg-gray-800 py-3 px-10 rounded text-white outline-none hover:scale-110 duration-500 ease-in mt-3 w-60 md:w-auto">بازگشت به سایت</NuxtLink>
                </div>
            </form>
        </div>
    </div>
</template>
<script>
definePageMeta({layout:false})
</script>
<template>
    <div class="flex justify-center items-center overflow-hidden h-screen">
        <img class="w-screen h-screen object-cover object-center" src="/image/subtle-prism.svg" alt="avatar">
        <div class="bg-gray-700/30 w-80 sm:w-96 xl:w-[30%] h-auto p-4 z-50 mx-auto rounded-md backdrop-blur-md absolute flex flex-col justify-center">
            <span class="text-black/70 capitalize italic font-medium text-2xl text-center">register</span>
            <form action="" method="post" class="p-2 mt-5 flex flex-col justify-center">
                <div class="flex flex-col">
                    <label for="username" class="text-gray-700 text-pretty mr-2">نام کاربری:</label>
                    <input type="text" name="username" placeholder="نام کاربری" class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-2">
                </div>
                <div class="flex flex-col">
                    <label for="email" class="text-gray-700 text-pretty mr-2">ایمیل:</label>
                    <input type="email" name="email" placeholder="ایمیل" class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-2">
                </div>
                <div class="flex flex-col mt-5">
                    <label for="password" class="text-gray-700 text-pretty mr-2">گذرواژه:</label>
                    <input type="password" name="password" placeholder="گذرواژه" class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-1">
                </div>
                <div class="flex flex-col mt-5">
                    <label for="password" class="text-gray-700 text-pretty mr-2">تایید گذرواژه:</label>
                    <input type="password" name="password" placeholder="گذرواژه" class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-1">
                </div>
                <div class="flex flex-row justify-between items-center">
                    <div class="mt-5 flex items-center gap-2">
                        <input type="checkbox" class="size-3 accent-rose-500 text-gray-700"><span class="select-none">مرابه خاطربسپار</span>
                    </div>
                </div>
                <button class="mt-5 px-2 py-3 bg-green-500 rounded-lg text-white outline-none transition-all hover:scale-105 duration-300 bg-gradient-to-r hover:from-cyan-500 hover:to-blue-500">ثبت نام</button>
                <NuxtLink to="/" class="mt-2 px-2 py-3 bg-gray-600 rounded-lg text-white outline-none transition-all hover:scale-105 duration-300 bg-gradient-to-r hover:from-purple-600 hover:to-indigo-500 text-center">ورود به سایت</NuxtLink>
            </form>
        </div>
    </div>
</template>
<script setup>
definePageMeta({layout: false})
</script>
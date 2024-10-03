<template>
  <div class="flex justify-center items-center overflow-hidden">
    <img class="w-dvw h-dvh object-cover object-center" src="/image/subtle-prism.svg" alt="image background"
         draggable="false">
    <div class="absolute flex flex-col justify-center z-50 w-full sm:w-96 xl:w-[25%] h-full p-2 md:p-0">
      <div
          class="bg-gray-700/30 w-full h-auto p-4 mx-auto rounded-md backdrop-blur-md flex flex-col">
        <span class="text-black/70 font-medium text-3xl text-center">ثبت نام</span>
        <form action="#" method="post" class="pt-5 px-2 flex flex-col justify-center space-y-5">
          <div class="flex flex-col">
            <label for="text" class="text-gray-700 text-pretty mr-2">نام کاربری:</label>
            <input type="email" name="email" placeholder="نام کاربری"
                   class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-2">
          </div>
          <div class="flex flex-col">
            <label for="email" class="text-gray-700 text-pretty mr-2">ایمیل:</label>
            <input type="email" name="email" placeholder="ایمیل"
                   class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-2">
          </div>
          <div class="flex flex-col">
            <label for="password" class="text-gray-700 text-pretty mr-2">گذرواژه:</label>
            <input type="password" name="password" placeholder="گذرواژه"
                   class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-1">
          </div>
          <div class="flex flex-col">
            <label for="password" class="text-gray-700 text-pretty mr-2">تکرار گذرواژه:</label>
            <input type="password" name="password" placeholder="تکرار گذرواژه"
                   class="bg-gray-600 rounded-lg px-3 py-3 outline-none text-white focus:placeholder:text-gray-300 hover:shadow-lg hover:shadow-teal-500 duration-300 mt-1">
          </div>
          <div class="flex flex-col w-full">
            <button
                class="mt-5 px-2 py-3 bg-green-500 rounded-lg text-white outline-none transition-all hover:scale-105 duration-300 bg-gradient-to-r hover:from-cyan-500 hover:to-blue-500">
              ثبت نام
            </button>
            <NuxtLink to="/"
                      class="mt-2 px-2 py-3 bg-gray-600 rounded-lg text-white outline-none transition-all hover:scale-105 duration-300 bg-gradient-to-r hover:from-purple-600 hover:to-indigo-500 text-center">
              ورود به سایت
            </NuxtLink>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
<script setup>
definePageMeta({layout: false})
</script>
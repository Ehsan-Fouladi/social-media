<template>
  <!-- carts -->
  <div class="flex justify-center items-center w-full h-full relative">
    <div class="w-full h-[500px] bg-cover bg-center bg-no-repeat md:h-[580px] background-image"></div>
    <div class="absolute w-full h-full p-3 md:p-4 lg:p-6 flex items-center justify-center">
      <div class="flex flex-col justify-center items-start gap-5 w-full lg:w-5/6 h-full">
        <div class="flex items-center pr-1 sm:pr-0">
          <svg class="w-8 text-yellow-300 opacity-50" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"
               fill="currentColor">
            <path fill-rule="evenodd"
                  d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z"
                  clip-rule="evenodd"/>
          </svg>
          <h3 class="text-lg font-normal text-yellow-400 mr-3 select-none">پیشنهاد ویژه</h3>
        </div>
        <div class="flex items-center md:p-4 w-full">
          <div class="flex gap-4 w-full overflow-auto">
            <!-- cart -->
            <Product v-for="item in 10" :key="item"/>
            <!-- cart -->
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- carts -->
</template>
<style scoped>
div .background-image {
  background-image: url('/image/background1.jpg');
}
</style>
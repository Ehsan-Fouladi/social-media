<template>
  <div class="bg-gray-900">
    <div class="flex flex-col justify-center items-center">
      <!-- card -->
      <div class="flex flex-col justify-center items-center gap-5 w-full lg:w-5/6 h-full">
        <div class="bg-gradient-to-r from-gray-800 via-gray-800 to-yellow-900 px-4 py-4 w-9/12 sm:w-8/12 lg:mr-14 mt-5 rounded">
          <span class="text-white font-medium text-xl">بایگانی‌ها: انیمه</span>
        </div>
        <div class="flex justify-center items-center md:p-4 w-full">
          <div class="grid grid-flow-row grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-4">
            <!-- cart -->
            <Product v-for="item in 15" :key="item"/>
            <!-- cart -->
          </div>
        </div>
      </div>
      <!-- card -->
      <!-- pagination -->
      <div class="flex items-center justify-center py-10 lg:px-0 sm:px-6 px-4">
        <div class=" w-full  flex items-center justify-between border-t border-gray-200">
          <div class="flex items-center pt-3 text-gray-600 hover:text-indigo-700 cursor-pointer">
            <svg class="text-white" width="14" height="8" viewBox="0 0 14 8" fill="none"
                 xmlns="http://www.w3.org/2000/svg">
              <path d="M1.1665 4H12.8332" stroke="currentColor" stroke-width="1.25" stroke-linecap="round"
                    stroke-linejoin="round"/>
              <path d="M1.1665 4L4.49984 7.33333" stroke="currentColor" stroke-width="1.25" stroke-linecap="round"
                    stroke-linejoin="round"/>
              <path d="M1.1665 4.00002L4.49984 0.666687" stroke="currentColor" stroke-width="1.25"
                    stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            <p class="text-sm ml-3 font-medium leading-none text-white">قبلی</p>
          </div>
          <div class="hidden sm:flex">
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              1
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              2
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              3
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-indigo-700 border-t border-indigo-400 pt-3 mr-4 px-2">
              4
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              5
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              6
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              7
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              8
            </p>
          </div>
          <div class="flex sm:hidden">
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              1
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              2
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-white hover:text-indigo-700 border-t border-transparent hover:border-indigo-400 pt-3 mr-4 px-2">
              ...
            </p>
            <p class="text-sm font-medium leading-none cursor-pointer text-indigo-700 border-t border-indigo-400 pt-3 mr-4 px-2">
              4
            </p>
          </div>
          <div class="flex items-center pt-3 text-gray-600 hover:text-indigo-700 cursor-pointer">
            <p class="text-sm font-medium leading-none mr-3 text-white">بعدی</p>
            <svg class="text-white" width="14" height="8" viewBox="0 0 14 8" fill="none"
                 xmlns="http://www.w3.org/2000/svg">
              <path d="M1.1665 4H12.8332" stroke="currentColor" stroke-width="1.25" stroke-linecap="round"
                    stroke-linejoin="round"/>
              <path d="M9.5 7.33333L12.8333 4" stroke="currentColor" stroke-width="1.25" stroke-linecap="round"
                    stroke-linejoin="round"/>
              <path d="M9.5 0.666687L12.8333 4.00002" stroke="currentColor" stroke-width="1.25" stroke-linecap="round"
                    stroke-linejoin="round"/>
            </svg>
          </div>
        </div>
      </div>
      <!-- end pagination -->
    </div>
  </div>
</template>
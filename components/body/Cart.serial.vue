<template>
    <div class="bg-stone-900 relative flex flex-col justify-center items-center">
        <!-- box video update -->
        <div class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex   items-center justify-between mt-4">
            <div class="flex items-center mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-6 text-gray-500" viewBox="0 0 96 96">
                    <path fill="currentColor" fill-rule="evenodd" d="M48 96c26.51 0 48-21.49 48-48S74.51 0 48 0S0 21.49 0 48s21.49 48 48 48zM15 48a33 33 0 1 0 66 .127v-.253a33.175 33.175 0 0 0-.903-7.541a3.54 3.54 0 1 0-6.886 1.64a25.934 25.934 0 1 1-19.197-19.186a3.54 3.54 0 0 0 1.64-6.886A32.996 32.996 0 0 0 15 48zm49.61-24.056a.66.66 0 0 1 .07-.08l.002.002a5.26 5.26 0 0 1 8.008 6.763a5.57 5.57 0 0 1-.561.684a5.223 5.223 0 0 1-3.224 1.517h-.048c-.1 0-.2.005-.299.011c-.1.006-.199.011-.298.011a1.006 1.006 0 0 0-.096.011a.73.73 0 0 1-.112.012a9.428 9.428 0 0 0-8.397 11.515c.003.012.008.024.013.036c.007.02.015.04.015.062c.053.224.11.443.18.664a12.205 12.205 0 0 1-1.868 9.813a11.954 11.954 0 0 1-1.368 1.666A12.21 12.21 0 1 1 39.36 39.362c.066-.066.138-.126.209-.185c.054-.045.109-.091.161-.14a12.14 12.14 0 0 1 11.148-2.91a9.422 9.422 0 0 0 12.235-8.052l.017-.13a1.68 1.68 0 0 0 .025-.254v-.561a5.218 5.218 0 0 1 1.402-3.12c.02-.022.037-.044.054-.066z" clip-rule="evenodd"/>
                </svg>
            <span class="text-white font-medium px-3">فیلم و سریال های کره ای</span>
            </div>
            <a href="#" target="_blank" class="bg-yellow-500 px-3 py-1 text-xs rounded-md rounded-bl-3xl">مشاهده بیشتر >
            </a>
        </div>
        
        <div class="md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="flex flex-row gap-3 overflow-auto">
                <Product v-for="item in 10" :key="item"/>
            </div>
        </div>
    <!-- box video update -->
    <!-- box video update -->
        <div class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex   items-center justify-between mt-4">
            <div class="flex items-center mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 text-gray-500">
                    <path fill-rule="evenodd" d="M12.963 2.286a.75.75 0 00-1.071-.136 9.742 9.742 0 00-3.539 6.177A7.547 7.547 0 016.648 6.61a.75.75 0 00-1.152-.082A9 9 0 1015.68 4.534a7.46 7.46 0 01-2.717-2.248zM15.75 14.25a3.75 3.75 0 11-7.313-1.172c.628.465 1.35.81 2.133 1a5.99 5.99 0 011.925-3.545 3.75 3.75 0 013.255 3.717z" clip-rule="evenodd" />
                </svg>
            <span class="text-white font-medium px-3">دوبله فارسی</span>
            </div>
            <a href="#" target="_blank" class="bg-yellow-500 px-3 py-1 text-xs rounded-md rounded-bl-3xl">مشاهده بیشتر >
            </a>
        </div>
        
        <div class="md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="flex flex-row gap-3 overflow-auto">
                <Product v-for="item in 10" :key="item"/>
            </div>
        </div>
    <!-- box video update -->
</div>
</template>
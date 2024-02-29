<template>
    <!-- content -->
    <div class="flex flex-col justify-center items-center w-full bg-slate-800 p-5 rounded-lg">
        <div class="w-full flex flex-col gap-2 mt-2 relative">
            <div class="flex flex-row justify-between items-center w-full">
                <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل اول کامل</span>
                <span class="text-white bg-gray-600 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس
                    فارسی چسبیده</span>
            </div>
            <div class="flex flex-row justify-between items-center w-full" v-if="false">
                <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود رایگان با لینک
                    مستقیم</span>
                <span class="text-white bg-gray-700 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس
                    فارسی چسبیده</span>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
        </div>
        <div class="w-full flex flex-col gap-2 mt-5 relative">
            <div class="flex flex-row justify-between items-center w-full">
                <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل دوم کامل</span>
                <span class="text-white bg-gray-600 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس
                    فارسی چسبیده</span>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
            <div
                class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                <NuxtLink to="/downloads/"
                    class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm cursor-pointer">
                    دانلود</NuxtLink>
            </div>
        </div>
    </div>
</template>
<template>
    <div class="mt-7">
        <!-- links -->
        <div class="cursor-pointer">
            <div class="text-center px-3 py-2 font-medium" :class="active_section == 1 ? 'rounded-r-lg bg-yellow-500' : 'rounded-r-lg bg-gray-600 text-white'" @click="active_section = 1">لینک های دانلود</div>
        </div>
    </div>
    <!-- content -->
    <div class="flex justify-center items-center absolute right-0 left-0 bg-slate-700" v-if="active_section === 1">
        <div class="mt-8 bg-gray-800 p-8 rounded-lg w-full sm:w-5/6 md:w-4/5 lg:w-3/4 min-w-80 flex flex-col justify-center items-center">
            <div class="w-full flex flex-col gap-2 mt-2 relative">
                <div class="flex flex-row justify-between items-center w-full">
                    <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل اول کامل</span>
                    <span class="text-white bg-gray-700 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس فارسی چسبیده</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
            </div>
            <div class="w-full flex flex-col gap-2 mt-5 relative">
                <div class="flex flex-row justify-between items-center w-full">
                    <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل اول کامل</span>
                    <span class="text-white bg-gray-700 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس فارسی چسبیده</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
            </div>
        </div>
    </div>
    <!-- <div class="flex justify-center items-center absolute right-0 left-0 bg-slate-700" v-if="active_section === 1">
        <div class="mt-8 bg-gray-800 p-8 rounded-lg w-full sm:w-5/6 md:w-4/5 lg:w-3/4 min-w-80 flex flex-col justify-center items-center">
            <div class="w-full flex flex-col gap-2 mt-2 relative">
                <div class="flex flex-row justify-between items-center w-full">
                    <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل اول کامل</span>
                    <span class="text-white bg-gray-700 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس فارسی چسبیده</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
            </div>
            <div class="w-full flex flex-col gap-2 mt-5 relative">
                <div class="flex flex-row justify-between items-center w-full">
                    <span class="text-white font-medium text-sm sm:text-base text-pretty">دانلود فصل اول کامل</span>
                    <span class="text-white bg-gray-700 px-2 py-2 font-medium rounded-lg text-xs sm:text-sm text-pretty">زیرنویس فارسی چسبیده</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 1080p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 720p x265</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود با کیفیت 480p</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
                <div class="bg-slate-900 flex flex-shrink justify-between items-center py-3 px-4 rounded-md border-2 border-slate-900 border-l-yellow-500 border-r-purple-500">
                    <span class="text-white text-sm text-pretty font-medium">دانلود زیرنویس</span>
                    <span class="px-6 py-2 bg-gray-950 hover:border-2 border-yellow-500 rounded-md font-medium text-pretty text-white text-sm">دانلود</span>
                </div>
            </div>
        </div>
    </div> -->
</template>
<script setup>
const active_section = ref(2)
</script>
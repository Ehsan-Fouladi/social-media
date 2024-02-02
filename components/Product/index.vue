<template>
    <NuxtLink to="/films/{{ slug }}" class="flex flex-col relative" v-if="true">
        <div
            class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg transition-all flex justify-center items-center overflow-hidden duration-150">
            <div class="-z-50 hover:z-50 flex flex-col items-center">
                <span class="text-white font-bold text-lg">walking</span>
                <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
            </div>
        </div>
        <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="~/public/The-Northman.jpg" alt="avatar">
        <div class="bg-white rounded-b absolute px-1 left-5 bg-opacity-60">
            <span class="text-sm font-normal">17+</span>
        </div>
        <div class="bg-white rounded-md px-1 absolute mt-2 right-2 bg-opacity-60">
            <span class="text-xs font-normal">S2 EP12</span>
        </div>
        <div class="bg-white rounded-md px-1 absolute bottom-2 right-2 bg-opacity-60">
            <span class="text-xs font-medium">سافت ساب</span>
        </div>
    </NuxtLink>
    <div class="flex flex-col" v-else>
        <div class="w-60 h-60 md:h-80 rounded-lg object-cover object-center bg-gray-900">
            <div class="w-full h-full bg-gray-700 rounded-lg animate-pulse z-50 flex justify-center items-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-12 text-white">
                    <path stroke-linecap="round" stroke-linejoin="round" d="m2.25 15.75 5.159-5.159a2.25 2.25 0 0 1 3.182 0l5.159 5.159m-1.5-1.5 1.409-1.409a2.25 2.25 0 0 1 3.182 0l2.909 2.909m-18 3.75h16.5a1.5 1.5 0 0 0 1.5-1.5V6a1.5 1.5 0 0 0-1.5-1.5H3.75A1.5 1.5 0 0 0 2.25 6v12a1.5 1.5 0 0 0 1.5 1.5Zm10.5-11.25h.008v.008h-.008V8.25Zm.375 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z" />
                </svg>
            </div>
        </div>
    </div>
</template>
<script setup>
const AlertStatus = ref(true)
const {slug} = useRoute().params
</script>
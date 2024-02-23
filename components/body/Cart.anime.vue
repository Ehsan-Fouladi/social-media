<template>
    <div class="bg-gray-800 relative flex flex-col justify-center items-center">
        <!-- box video update -->
        <div
            class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex items-center justify-between mt-4">
            <div class="flex items-center mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-7 text-gray-500" viewBox="0 0 24 24">
                    <path fill="currentColor"
                        d="M8.273 7.247v8.423l-2.103-.003v-5.216l-2.03 2.404l-1.989-2.458l-.02 5.285H.001L0 7.247h2.203l1.865 2.545l2.015-2.546l2.19.001zm8.628 2.069l.025 6.335h-2.365l-.008-2.871h-2.8c.07.499.21 1.266.417 1.779c.155.381.298.751.583 1.128l-1.705 1.125c-.349-.636-.622-1.337-.878-2.082a9.296 9.296 0 0 1-.507-2.179c-.085-.75-.097-1.471.107-2.212a3.908 3.908 0 0 1 1.161-1.866c.313-.293.749-.5 1.1-.687c.351-.187.743-.264 1.107-.359a7.405 7.405 0 0 1 1.191-.183c.398-.034 1.107-.066 2.39-.028l.545 1.749H14.51c-.593.008-.878.001-1.341.209a2.236 2.236 0 0 0-1.278 1.92l2.663.033l.038-1.81h2.309zm3.992-2.099v6.627l3.107.032l-.43 1.775h-4.807V7.187l2.13.03z" />
                </svg>
                <span class="text-white font-medium px-3">انیمه های بروز شده</span>
            </div>
            <NuxtLink to="/productlist/" target="_blank" class="bg-yellow-500 px-3 py-1 text-xs rounded-md rounded-bl-3xl">
                مشاهده بیشتر >
            </NuxtLink>
        </div>

        <div class="md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="flex flex-row gap-3 overflow-auto">
                <Product v-for="item in 10" :key="item"/>
            </div>
        </div>
        <!-- box video update -->
        <!-- box video update -->
        <div
            class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex   items-center justify-between mt-4">
            <div class="flex items-center mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-7 text-gray-500" viewBox="0 0 48 48">
                    <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                        d="m14.303 32.1l6.347-7.737l-8.16-10.638l6.27-.081l5.062 6.528L35.231 5.665m-22.816 36.75L23.974 27.91l5.364 6.608l6.195-.08l-8.386-10.477l6.573-7.979m1.51-10.317l-18.13-.16m-4.685 36.91l19.19.08" />
                    <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                        d="M17.099 5.504a20.335 20.335 0 0 0-6.713 2.994C5.09 12.456 4.74 18.47 6.336 23.35c1.647 5.032 5.583 8.884 7.967 8.75m17.301 10.396c7.03-2.09 9.602-6.172 10.516-10.13a14.3 14.3 0 0 0-8.4-16.385" />
                </svg>
                <span class="text-white font-medium px-3">انیمیشن های بروز شده</span>
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
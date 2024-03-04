<template>
    <div class="relative flex flex-col justify-center items-center">
        <!-- box video update -->
        <div
            class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex items-center justify-between mt-4">
            <div class="flex mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                    class="w-6 h-6 text-gray-600">
                    <path
                        d="M4.5 4.5a3 3 0 00-3 3v9a3 3 0 003 3h8.25a3 3 0 003-3v-9a3 3 0 00-3-3H4.5zM19.94 18.75l-2.69-2.69V7.94l2.69-2.69c.944-.945 2.56-.276 2.56 1.06v11.38c0 1.336-1.616 2.005-2.56 1.06z" />
                </svg>
                <span class="text-white font-medium px-3">فیلم های جدید</span>
            </div>
            <NuxtLink to="/productlist/" target="_blank" class="bg-yellow-500 px-3 py-1 text-xs rounded-md rounded-bl-3xl">مشاهده بیشتر >
            </NuxtLink>
        </div>

        <div class="lg:w-[157vh] md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="flex flex-row gap-3 overflow-auto">
                <Product v-for="item in 10" :key="item"/>
            </div>
        </div>
        <!-- box video update -->
        <!-- box video update -->
        <div
            class="max-w-7xl w-full bg-gradient-to-r from-black to-yellow-500/10 p-2 rounded-xl flex items-center justify-between mt-4">
            <div class="flex mr-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                    class="w-6 h-6 text-gray-600">
                    <path fill-rule="evenodd"
                        d="M2.25 6a3 3 0 013-3h13.5a3 3 0 013 3v12a3 3 0 01-3 3H5.25a3 3 0 01-3-3V6zm18 3H3.75v9a1.5 1.5 0 001.5 1.5h13.5a1.5 1.5 0 001.5-1.5V9zm-15-3.75A.75.75 0 004.5 6v.008c0 .414.336.75.75.75h.008a.75.75 0 00.75-.75V6a.75.75 0 00-.75-.75H5.25zm1.5.75a.75.75 0 01.75-.75h.008a.75.75 0 01.75.75v.008a.75.75 0 01-.75.75H7.5a.75.75 0 01-.75-.75V6zm3-.75A.75.75 0 009 6v.008c0 .414.336.75.75.75h.008a.75.75 0 00.75-.75V6a.75.75 0 00-.75-.75H9.75z"
                        clip-rule="evenodd" />
                </svg>
                <span class="text-white font-medium px-3">سریال های بروز شده</span>
            </div>
            <NuxtLink to="/productlist/" target="_blank" class="bg-yellow-500 px-3 py-1 text-xs rounded-md rounded-bl-3xl">مشاهده بیشتر >
            </NuxtLink>
        </div>

        <div class="lg:w-[157vh] md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="flex flex-row gap-3 overflow-auto">
                <Product v-for="item in 10" :key="item"/>
            </div>
        </div>
        <!-- box video update -->
    </div>
</template>
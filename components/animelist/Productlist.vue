<template>
    <div class="bg-gray-900">
        <div class="flex flex-col justify-center items-center">
            <div class="bg-gradient-to-r from-gray-800 via-gray-800 to-yellow-900 px-4 py-4 w-8/12 mr-20 mt-32 rounded">
                <span class="text-white font-medium text-xl">بایگانی‌ها: انیمه</span> 
            </div>
            <!-- card -->
            <div class="md:w-[162vh] w-96 h-fit p-4 mt-4 md:mr-8">
            <div class="grid grid-flow-row grid-cols-5 gap-4 overflow-auto">
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
                <NuxtLink to="#" class="flex flex-col relative">
                    <div
                        class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                        <div class="-z-50 hover:z-50 flex flex-col items-center">
                            <span class="text-white font-bold text-lg">walking</span>
                            <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-if="AlertStatus">درحال پخش</span>
                            <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white"
                                v-else>اتمام پخش</span>
                        </div>
                    </div>
                    <img class="max-w-sm h-60 md:h-80 rounded-lg object-cover object-center" src="../../public/The-Northman.jpg" alt="avatar">
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
            </div>
        </div>
        <!-- card -->
        </div>
    </div>
</template>
<script>
</script>
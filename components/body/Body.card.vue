<template>
    <!-- carts -->
    <section id="hero-section">
        <div class="flex flex-row justify-center items-center">
            <div class="w-screen h-screen bg-no-repeat bg-center back md:-mt-20"></div>
            <div class="absolute mt-16 md:mt-0">
                <div class="flex md:-mr-10">
                    <div class="flex justify-center items-center">
                        <svg class="w-8 text-yellow-300 opacity-75" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                        <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd"/>
                        </svg>                  
                        <h3 class="text-lg font-normal text-yellow-400 mr-3">پیشنهاد ویژه</h3>
                    </div>
                </div>
                    <!-- box -->
                    <div class="md:w-[162vh] w-96 h-fit p-4 md:mt-6 md:mr-8">
                        <div class="flex flex-row gap-3 overflow-auto">
                            <NuxtLink to="#" class="flex flex-col relative">
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                                <div class="hover:backdrop-blur-sm hover:bg-black/60 w-full h-full absolute rounded-lg flex justify-center items-center overflow-hidden">
                                    <div class="-z-50 hover:z-50 flex flex-col items-center">
                                        <span class="text-white font-bold text-lg">walking</span>
                                        <span class="mt-5 bg-red-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-if="AlertStatus">درحال پخش</span>
                                        <span class="mt-5 bg-green-600 px-2 py-1 outline-none text-xs font-medium rounded-md text-white" v-else>اتمام پخش</span>
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
                    <!-- box -->
                </div>
            </div>
    </section>
    <!-- carts -->
</template>
<script setup>
const AlertStatus = ref(true)
</script>
<style scoped>
div .back{
    background-image: url('~/public/background1.jpg');
}
</style>
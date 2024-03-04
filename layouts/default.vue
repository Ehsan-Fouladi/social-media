<script setup>
const menu = ref(true)
const menuMobile = ref(true)
const SearchBox = ref(true)
function clickMenu() {
    menu.value = !menu.value
}
function clickMenuMobile() {
    menuMobile.value = !menuMobile.value
}
function SearchInput() {
    SearchBox.value = !SearchBox.value
}

onMounted(() => {
    ScrollPosition()
    window.addEventListener("scroll", ScrollPosition)
})
function ScrollPosition() {
    const winScroll = document.body.scrollTop || document.documentElement.scrollTop;
    const height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
    const scrolled = (winScroll / height) * 100;
    document.getElementById("progressBar").style.width = scrolled + "%"

    const header = document.getElementById('header')
    const footer = document.getElementById('footer')

    if (winScroll > 15) {
        header.classList.add('backdrop-blur-lg')
        header.classList.add('bg-gray-800/70')
        header.classList.remove('bg-gray-900')
    }
    else {
        header.classList.remove('backdrop-blur-lg')
        header.classList.remove('bg-gray-800/70')
        header.classList.add('bg-gray-900')
    }

    if (scrolled <= 97.50) {
        footer.classList.add('backdrop-blur-lg')
        footer.classList.add('bg-gray-800/70')
        footer.classList.remove('bg-gray-900')
    }
    else {
        footer.classList.remove('backdrop-blur-lg')
        footer.classList.remove('bg-gray-800/70')
        footer.classList.add('bg-gray-900')
    }
}
</script>
<template>
    <header id="header" class="w-full h-auto flex flex-col p-3 z-50 sticky top-0 transition-all duration-200 bg-gray-900">
        <div class="container mx-auto px-3 py-3">
            <div class="flex items-center md:justify-evenly justify-between">
                <!-- menu -->
                <div class="flex items-center lg:ml-20 xl:ml-0 relative">
                    <img class="object-cover w-full h-full hover:scale-110 duration-500" draggable="false"
                        src="~/public/logo.png" alt="logo">
                    <div class="mr-7 hidden md:block" v-if="menu" @click="clickMenu">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-12 text-white cursor-pointer">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                    </div>
                    <div class="mr-7 hidden md:block" v-else @click="clickMenu"></div>
                </div>
                <transition enter-to-class="animate__animated animate__slideInRight"
                    leave-to-class="animate__animated animate__slideOutRight">
                    <div v-show="!menu" @click="clickMenu"
                        class="absolute right-0 h-dvh -top-0 w-96 p-4 z-50 bg-gray-800 overflow-auto rounded-l-lg max-w-md">
                        <div class="flex flex-row justify-between items-center mt-3">
                            <img class="object-cover hover:scale-110 duration-500" draggable="false"
                                src="~/public/logo.png" alt="logo">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-12 text-white cursor-pointer">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                            </svg>
                        </div>
                        <div
                            class="flex flex-col mt-6 text-white p-4 space-y-5 cursor-pointer font-medium w-full transition-all">
                            <NuxtLink to="/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">صفحه اصلی</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">فیلم</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">سریال</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">انیمه</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">کره
                                    ای</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">دوبله
                                    فارسی</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">خارجی</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">مانگا</span>
                            </NuxtLink>
                            <NuxtLink to="/productlist/"
                                class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700 duration-500">
                                <span
                                    class="text-gray-300 font-medium text-nowrap hover:text-purple-500 duration-500">مانهوا</span>
                            </NuxtLink>
                        </div>
                    </div>
                </transition>
                <!-- search -->
                <div class="flex items-center hidden md:block">
                    <form method="get" class="flex justify-end items-center">
                        <input type="search" name="q" placeholder="جستجوی سریع..."
                            class="py-3 px-3 rounded-md bg-gray-700 text-gray-300 focus:text-base outline-none lg:w-full-screen md:w-96 text-base font-medium">
                        <div class="absolute ml-2">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-gray-400">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                            </svg>
                        </div>
                    </form>
                    <div
                        class="bg-gray-900 lg:w-full-screen md:w-96 h-96 p-4 rounded-md overflow-auto mt-4 absolute hidden">
                        <NuxtLink to="#"
                            class="rounded-sm duration-300 flex flex-row items-center justify-between peer hover:pe-3 mt-6">
                            <img class="object-cover object-center size-20 rounded-md hover:size-40 duration-500 delay-100"
                                src="../../public/The-Northman.jpg" alt="image file">
                            <span class="text-lg text-white font-medium hover:text-gray-500">walking</span>
                        </NuxtLink>
                    </div>
                </div>
                <!-- box -->
                <div class="flex items-center sm:mr-1 lg:mr-3 xl:mr-0">
                    <div class="bg-blue-700 px-3 py-2 relative rounded-lg block">
                        <NuxtLink to="/auth/login/" class="text-white font-normal text-xs md:text-sm text-center">ورود / ثبت نام
                        </NuxtLink>
                    </div>
                </div>
                <!-- end -->
            </div>
        </div>
        <!-- scroll progress bar -->
        <div class="w-full h-2 absolute bottom-0 right-0 left-0 bg-gradient-to-r from-cyan-500 to-blue-500"
            id="progressBar"></div>
        <!-- scroll progress bar -->
    </header>
    <slot />
    <nav id="footer" class="w-full h-auto flex flex-col sticky z-50 p-3 md:hidden transition-all duration-200 bg-gray-800/70 bottom-0">
        <div class="px-5 flex flex-row justify-between items-center">
            <!-- home -->
            <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
                <NuxtLink to="/">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                        stroke="currentColor" class="w-8 text-white">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                    </svg>
                </NuxtLink>
            </div>
            <!-- menu -->
            <transition enter-to-class="animate__animated animate__slideInLeft"
                leave-to-class="animate__animated animate__slideOutLeft">
                <div v-show="!menuMobile"
                    class="absolute bg-black/90 backdrop-blur-lg  md:hidden -z-50 h-dvh w-dvw right-0 bottom-0 overflow-auto">
                    <div class="h-screen flex flex-col justify-center items-center -mt-5 space-y-6">
                        <NuxtLink to="/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">صفحه اصلی</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">فیلم</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">سریال</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">انیمه</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">کره ای</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">دوبله فارسی</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">خارجی</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">مانگا</span>
                        </NuxtLink>
                        <NuxtLink to="/productlist/" class="bg-gray-800 px-3 py-1 text-center rounded-md w-80 hover:bg-gray-700">
                            <span class="text-gray-300 font-medium text-nowrap hover:text-purple-500">مانهوا</span>
                        </NuxtLink>
                    </div>
                </div>
            </transition>
            <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
                <div v-if="menuMobile" @click="clickMenuMobile">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-8 text-white cursor-pointer">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>
            </div>
            <div v-else @click="clickMenuMobile">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-8 text-white cursor-pointer">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                </svg>
            </div>
        </div>
        <!-- search -->
        <div class="flex items-center justify-center bg-gray-700 px-2 py-1 rounded-lg relative">
            <div @click="SearchInput">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-8 text-white">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                </svg>
            </div>
        </div>
        <transition enter-to-class="animate__animated animate__slideInLeft"
            leave-to-class="animate__animated animate__slideOutLeft">
            <div class="bg-black/70 backdrop-blur w-screen min-h-lvh absolute bottom-0 right-0 left-0 -z-50 flex justify-center items-center"
                v-show="!SearchBox">
                <form method="get" class="inline-block">
                    <input type="search" name="q" placeholder="جستجوی سریع..."
                        class="py-3 px-3 rounded-md bg-gray-700 text-gray-300 focus:text-base outline-none text-base font-medium w-96">
                </form>
            </div>
        </transition>
        <!-- login -->
        <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
            <NuxtLink to="/auth/login/">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-8 text-white">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15m3 0l3-3m0 0l-3-3m3 3H9" />
                </svg>
            </NuxtLink>
        </div>
    </div>
</nav></template>
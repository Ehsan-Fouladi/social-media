<template>
    <!-- header -->
    <div class="w-full h-16 top-0 flex flex-row items-center bg-gray-800 overflow-hidden sticky z-30">
        <div class="mr-10 flex flex-row items-center justify-between w-full relative">
            <NuxtLink to="/" class="hidden lg:block">
                <img class="object-cover hover:scale-110 duration-500" draggable="false" src="~/public/logo.png" alt="logo">
            </NuxtLink>
            <div class="flex flex-row items-center gap-2 text-white lg:hidden" v-if="menu" @click="clickMenu">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"              stroke="currentColor" class="size-8" >
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>
                <span class="font-medium md:text-lg">منو</span>
            </div>
            <div class="flex flex-row items-center gap-2 text-white lg:hidden" v-else @click="clickMenu">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12"/>
                </svg>
            </div>
            <div class="ml-10 md:ml-20">
                <NuxtLink to="/" class="border-2 border-indigo-500 px-2 py-2 rounded-xl text-white text-pretty text-sm md:text-base">بازگشت به سایت</NuxtLink>
            </div>
            <div class="ml-10 hidden md:block">
                <span class="text-white text-pretty font-medium  tracking-tight">به پنل کاربری آیوفیلم خوش آمدید ...</span>
            </div>
        </div>
    </div>
    <slot/>
    <!-- navbar -->
    <div class="h-full md:h-screen w-72 flex flex-col items-center bg-gray-800 relative" v-show="menu">
        <div class="flex flex-col items-center justify-center w-full">
            <div class="mt-4 flex flex-col md:flex-row items-center gap-2">
                <img class="rounded-full size-12 sm:size-16 md:size-20 object-cover object-center bg-white" src="https://static.vecteezy.com/system/resources/previews/019/879/198/non_2x/user-icon-on-transparent-background-free-png.png" alt="image user" draggable="false">
                <span class="text-white font-medium text-sm md:text-base">سلام کاربر</span>
            </div>
            <div class="flex flex-row items-center justify-center gap-3 mt-6">
                <div class="border-2 border-indigo-600 rounded-xl size-14 flex justify-center items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-7 text-yellow-400">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                    </svg>
                </div>
                <div class="relative">
                    <div class="absolute rounded-full size-5 bg-yellow-400 flex justify-center items-center top-0 -left-2 -mt-2">1</div>
                    <div class="border-2 border-indigo-600 rounded-xl size-14 flex justify-center items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-7 text-yellow-400">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.76c0 1.6 1.123 2.994 2.707 3.227 1.087.16 2.185.283 3.293.369V21l4.076-4.076a1.526 1.526 0 0 1 1.037-.443 48.282 48.282 0 0 0 5.68-.494c1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0 0 12 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018Z" />
                        </svg>
                    </div>
                </div>
                <div class="relative">
                    <div class="absolute rounded-full size-5 bg-yellow-400 flex justify-center items-center top-0 -left-2 -mt-2">1</div>
                    <div class="border-2 border-indigo-600 rounded-xl size-14 flex justify-center items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-7 text-yellow-400">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0M3.124 7.5A8.969 8.969 0 0 1 5.292 3m13.416 0a8.969 8.969 0 0 1 2.168 4.5" />
                        </svg>
                    </div>
                </div>
            </div>
            <div class="flex flex-col justify-center items-center mt-8 w-full cursor-pointer space-y-4">
                <NuxtLink to="/admin/" class="flex flex-row items-center gap-2 w-full p-5 mt-4" :class="styled_active_page('admin')">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6A2.25 2.25 0 0 1 6 3.75h2.25A2.25 2.25 0 0 1 10.5 6v2.25a2.25 2.25 0 0 1-2.25 2.25H6a2.25 2.25 0 0 1-2.25-2.25V6ZM3.75 15.75A2.25 2.25 0 0 1 6 13.5h2.25a2.25 2.25 0 0 1 2.25 2.25V18a2.25 2.25 0 0 1-2.25 2.25H6A2.25 2.25 0 0 1 3.75 18v-2.25ZM13.5 6a2.25 2.25 0 0 1 2.25-2.25H18A2.25 2.25 0 0 1 20.25 6v2.25A2.25 2.25 0 0 1 18 10.5h-2.25a2.25 2.25 0 0 1-2.25-2.25V6ZM13.5 15.75a2.25 2.25 0 0 1 2.25-2.25H18a2.25 2.25 0 0 1 2.25 2.25V18A2.25 2.25 0 0 1 18 20.25h-2.25A2.25 2.25 0 0 1 13.5 18v-2.25Z" />
                    </svg>
                    <span>داشتبورد</span>
                </NuxtLink>
                <NuxtLink to="/admin/comments/" class="flex flex-row items-center gap-2 w-full p-5" :class="styled_active_page('comments')">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M8.625 9.75a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H8.25m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H12m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0h-.375m-13.5 3.01c0 1.6 1.123 2.994 2.707 3.227 1.087.16 2.185.283 3.293.369V21l4.184-4.183a1.14 1.14 0 0 1 .778-.332 48.294 48.294 0 0 0 5.83-.498c1.585-.233 2.708-1.626 2.708-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0 0 12 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018Z" />
                    </svg>
                    <span>آخرین نظرات</span>
                </NuxtLink>
                <NuxtLink to="/admin/watchlist/" class="flex flex-row items-center gap-2 w-full p-5" :class="styled_active_page('watchlist')">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z" />
                    </svg>
                    <span>لیست تماشا</span>
                </NuxtLink>
                <NuxtLink to="/admin/favoritetitles/" class="flex flex-row items-center gap-2 w-full p-5" :class="styled_active_page('favoritetitles')">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z" />
                    </svg>
                    <span>عناوین مورد علاقه</span>
                </NuxtLink>
                <NuxtLink to="/admin/reset-password/" class="flex flex-row items-center gap-2 w-full p-5" :class="styled_active_page('reset-password')">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 5.25a3 3 0 0 1 3 3m3 0a6 6 0 0 1-7.029 5.912c-.563-.097-1.159.026-1.563.43L10.5 17.25H8.25v2.25H6v2.25H2.25v-2.818c0-.597.237-1.17.659-1.591l6.499-6.499c.404-.404.527-1 .43-1.563A6 6 0 1 1 21.75 8.25Z" />
                    </svg>

                    <span>تغییر گذرواژه</span>
                </NuxtLink>
                <NuxtLink to="/" class="flex flex-row items-center bg-gra90  gap-2 w-full p-5 text-yellow-300">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 9V5.25A2.25 2.25 0 0 1 10.5 3h6a2.25 2.25 0 0 1 2.25 2.25v13.5A2.25 2.25 0 0 1 16.5 21h-6a2.25 2.25 0 0 1-2.25-2.25V15m-3 0-3-3m0 0 3-3m-3 3H15" />
                    </svg>
                    <span>خروج</span>
                </NuxtLink>
            </div>
        </div>
    </div>
</template>
<script setup>
const menu = ref(true)
function clickMenu() {
    menu.value = !menu.value
}
function currentPage() {
    let paths = useRoute().fullPath.split('/')
    
    if (paths.length === 3) {
        return 'admin'
    }

    let empty = paths.filter((path) => path.length > 0).length
    return paths[paths.length - (empty)]
}

const styled_active_page = (page) => {
    return page === currentPage() ? 'text-indigo-600 bg-gray-900' : 'text-yellow-300'
}
</script>
<template>
    <div class="bg-gray-800 flex flex-col items-center">
        <div class="md:h-screen w-full flex flex-col lg:flex-row items-center">
            <img class="object-cover object-center rounded-xl lg:mr-24 w-72 h-auto mt-3 md:-mt-10"
                src="~/public/The-Northman.jpg" alt="avatar" draggable="false">
            <div
                class="flex flex-col mr-3 space-y-2 lg:-mt-10 justify-center items-center lg:justify-normal lg:items-stretch">
                <div class="flex lg:flex-col flex-row-reverse items-center lg:items-stretch gap-3 lg:gap-0">
                    <span class="text-white font-medium text-xl capitalize">Reacher</span>
                    <span class="text-white font-medium text-sm text-start">ریچر</span>
                </div>
                <div class="flex flex-wrap gap-2 justify-center lg:justify-normal items-center">
                    <nuxt-link to="https://www.imdb.com/title/tt9288030"
                        class="bg-yellow-500 outline-none px-1 py-1 w-14 text-center uppercase rounded-md">
                        <span class="font-extrabold">imdb</span>
                    </nuxt-link>
                    <div>
                        <span class="text-white text-sm font-medium">10/<span class="text-xl font-bold">8.1</span></span>
                    </div>
                    <div class="border-2 border-white px-2 py-0 rounded-md text-center">
                        <span class="font-medium text-white text-xs">17</span>
                    </div>
                    <div class="border-2 border-white px-2 py-0 rounded-md text-center mr-1">
                        <span class="font-medium text-white text-sm">سافت ساب</span>
                    </div>
                    <div class="border-2 border-white px-2 py-0 rounded-md text-center mr-1">
                        <span class="font-medium text-white text-xs">8</span>
                    </div>
                    <NuxtLink to="/productlist/" class="border-2 border-white px-2 py-0 rounded-md text-center mr-1">
                        <span class="font-medium text-white text-base capitalize">Amazon</span>
                    </NuxtLink>
                </div>
                <div class="mt-2 flex flex-col justify-center items-center lg:justify-normal lg:items-stretch">
                    <div class="mt-3 flex flex-wrap justify-center md:justify-normal items-center gap-3">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="size-4 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                        </svg>
                        <span class="text-white font-medium text-xs text-pretty">مدت زمان : هر قسمت میانگین 45 دقیقه</span>|
                        <nuxt-link to="/productlist/"
                            class="duration-500 hover:text-yellow-400 text-xs text-white">اکشن</nuxt-link>
                        <nuxt-link to="/productlist/"
                            class="duration-500 hover:text-yellow-400 text-xs text-white">جنایی</nuxt-link>
                        <nuxt-link to="/productlist/"
                            class="duration-500 hover:text-yellow-400 text-xs text-white">درام</nuxt-link>|
                        <span class="text-white text-xs font-medium">محصول : <nuxt-link to="/productlist/"
                                class="duration-500 hover:text-yellow-400">آمریکا</nuxt-link></span>
                    </div>
                    <div class="mt-2 flex flex-row items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="size-4 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="m15.75 10.5 4.72-4.72a.75.75 0 0 1 1.28.53v11.38a.75.75 0 0 1-1.28.53l-4.72-4.72M4.5 18.75h9a2.25 2.25 0 0 0 2.25-2.25v-9a2.25 2.25 0 0 0-2.25-2.25h-9A2.25 2.25 0 0 0 2.25 7.5v9a2.25 2.25 0 0 0 2.25 2.25Z" />
                        </svg>
                        <span class="text-xs text-white font-medium mr-2">کیفیت نمایش : <span
                                class="uppercase">WEB-DL</span></span>
                    </div>
                    <div class="mt-2" v-if="true">
                        <div class="flex flex-row items-center bg-yellow-800 px-2 py-2 rounded-lg w-60">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                            </svg>
                            <div class="mr-2 flex flex-row items-center gap-1">
                                <span class="text-white font-medium text-sm">قسمت</span>
                                <div class="bg-yellow-400 rounded px-2 text-sm font-bold">8</div>
                                <span class="text-white font-medium text-sm">فصل</span>
                                <div class="bg-yellow-400 rounded px-2 text-sm font-bold">2</div>
                                <span class="text-white font-medium text-sm">قرار گرفت</span>
                            </div>
                        </div>
                    </div>
                    <div class="mt-5 flex flex-col items-center lg:items-stretch">
                        <div class="text-white text-sm">
                            <span>کارگردان :</span>
                            <span> Christopher Nolan</span>
                        </div>
                        <div
                            class="text-white text-sm mt-3 flex flex-wrap justify-center lg:justify-normal items-center gap-2">
                            <span>ستارگان :</span>
                            <span>Cillian Murphy</span>
                            <span>Cillian Murphy</span>
                            <span>Cillian Murphy</span>
                        </div>
                        <span class="mt-3 text-white font-medium text-xs">سال پخش : 2023</span>
                    </div>
                    <div class="mt-4 flex flex-row gap-2">
                        <div class="bg-green-500 px-3 py-3 rounded-lg hover:bg-green-700 duration-300" v-if="false">
                            <span class="text-sm text-white">درحال پخش</span>
                        </div>
                        <div class="bg-rose-600 px-3 py-3 rounded-lg hover:bg-rose-700 duration-300" v-else>
                            <span class="text-sm text-white">اتمام پخش</span>
                        </div>
                        <div class="bg-gray-700 px-2 py-2 rounded-md">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="size-8 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z" />
                            </svg>
                        </div>
                        <div class="bg-gray-700 px-2 py-2 rounded-md">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="size-8 text-white">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z" />
                            </svg>

                        </div>
                    </div>
                    <div class="mt-2">
                        <p class="text-base text-pretty text-white">جک ریچر به جرم قتل دستگیر شد و اکنون پلیس به کمک او نیاز
                            دارد. بر اساس کتاب های لی چایلد.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex flex-col gap-2 justify-center items-center bg-slate-700 w-full p-4">
            <!-- header -->
            <div class="flex items-center gap-1 text-sm md:text-base lg:text-lg w-full lg:w-1/2">
                <!-- download -->
                <div class="text-center px-3 cursor-pointer py-2 font-medium rounded-r-lg w-1/3"
                    :class="active_section === 1 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 1">
                    لینک های دانلود</div>
                <!-- related -->
                <div class="text-center px-3 cursor-pointer py-2 font-medium w-1/3"
                    :class="active_section === 2 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 2">
                    لینک های مرتبط</div>
                <!-- comments -->
                <div class="text-center px-3 cursor-pointer py-2 font-medium rounded-l-lg w-1/3"
                    :class="active_section === 3 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 3">
                    نظرات</div>
            </div>
            <!-- content -->
            <div class="w-full lg:w-1/2">
                <WidgetDownload v-if="active_section === 1" />
                <WidgetTitleRelated v-if="active_section === 2" />
                <WidgetComments v-if="active_section === 3" />
            </div>
        </div>
    </div>
</template>
<script setup>

// definePageMeta({
//     layout: false
// })
const active_section = ref(1)
</script>
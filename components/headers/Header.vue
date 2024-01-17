<script>
export default {
    data() {
        return {
            menu: true
        }
    },
    methods: {
        clickMenu(){
            if (this.menu == true){
                this.menu = false
            }else{
                this.menu = true
            }
        }
    },
}
</script>
<template>
    <header class="w-full h-auto flex flex-col fixed p-3 z-50 backdrop-blur bg-gray-800" id="header">
        <div class="container mx-auto px-3 py-3">
            <div class="flex items-center md:justify-evenly justify-between relative">
                <!-- menu -->
                <div class="flex items-center lg:ml-20 xl:ml-0">
                    <img class="object-cover w-full h-full hover:scale-110 duration-500 delay-300" src="https://aiofilm.click/wp-content/uploads/2023/08/logo.png" alt="avatar">
                    <div class="mr-7 hidden md:block" v-if="menu" @click="clickMenu">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-12 text-white cursor-pointer">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                    </div>                
                    <div class="mr-7 hidden md:block" v-else @click="clickMenu">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-12 text-white cursor-pointer">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                        <div class="absolute p-3 px-1 py-2 pl-2 w-52 top-16 mr-5 bg-gray-800 rounded-md">
                            <div class="flex">
                                <ul class="text-white p-4 space-y-5 cursor-pointer font-medium w-full">
                                    <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">انیمه</NuxtLink></li>
                                    <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">کره ای</NuxtLink></li>
                                    <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">ترکی</NuxtLink></li>
                                    <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">خارجی</NuxtLink></li>
                                </ul>
                                
                            </div>
                        </div> 
                    </div>           
                </div>
                <!-- search -->
                <div class="flex items-center hidden md:block">
                    <form method="get" class="flex justify-end items-center">
                        <input type="search" name="q" placeholder="جستجوی سریع..." class="py-3 px-3 rounded-md bg-gray-700 text-gray-300 focus:text-base outline-none lg:w-full-screen md:w-96 text-base font-medium">
                        <div class="absolute ml-2">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 text-gray-400">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                            </svg>                              
                        </div>
                    </form>
                    <div class="bg-gray-900 lg:w-full-screen md:w-96 h-96 p-4 rounded-md overflow-auto mt-4 absolute hidden">
                        <NuxtLink to="#" class="rounded-sm duration-300 flex flex-row items-center justify-between peer hover:pe-3 mt-6">
                            <img class="object-cover object-center size-20 rounded-md hover:size-40 duration-500 delay-100" src="../../public/The-Northman.jpg" alt="image file">
                            <span class="text-lg text-white font-medium hover:text-gray-500">walking</span>
                        </NuxtLink>
                    </div>
                </div>
                <!-- box -->
                <div class="flex items-center sm:mr-1 lg:mr-3 xl:mr-0">
                    <div class="bg-blue-700 px-3 py-2 relative rounded-lg block">
                        <NuxtLink to="/auth/login/" class="text-white font-normal text-sm text-center">ورود / ثبت نام</NuxtLink>
                    </div>
                </div>
                <!-- end -->
            </div>
        </div>
    </header>
</template>
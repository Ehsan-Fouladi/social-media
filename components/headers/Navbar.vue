<script>
export default {
    data() {
        return {
            menuMobile: true,
            SearchBox: true,
        }
    },
    methods: {
        clickMenuMobile(){
            if (this.menuMobile == true){
                this.menuMobile = false
            }else{
                this.menuMobile = true
            }
        },
        SearchInput(){
            if (this.SearchBox == true){
                this.SearchBox = false
            }else{
                this.SearchBox = true
            }
        }
    },
}
</script>
<template>
    <nav class="w-full h-auto flex flex-col fixed z-50 p-3 md:hidden backdrop-blur bg-gray-800 bottom-0">
        <div class="px-5 flex flex-row justify-between items-center">
            <!-- home -->
            <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
                <NuxtLink to="/">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-white">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                    </svg>
                </NuxtLink>  
            </div>
            <!-- menu -->
            <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
                <div v-show="!menuMobile" class="absolute m-0 -top-[280px] text-white bg-gray-800 rounded-lg p-4 w-56 h-auto ps-5">
                    <ul class="text-2xl font-medium space-y-9">
                        <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">انیمه</NuxtLink></li>
                        <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">کره ای</NuxtLink></li>
                        <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">ترکی</NuxtLink></li>
                        <li class="block hover:pr-4 hover:rounded-md hover:bg-indigo-600/40 backdrop-blur px-2 py-1 duration-500"><NuxtLink to="#">خارجی</NuxtLink></li>
                    </ul>
                </div>
                <div v-if="menuMobile" @click="clickMenuMobile">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-white cursor-pointer">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                    </svg>
                </div>                
                <div v-else @click="clickMenuMobile">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-white cursor-pointer">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </div> 
            </div>
            <!-- search -->
            <div class="flex items-center justify-center bg-gray-700 px-2 py-1 rounded-lg relative">
                <div @click="SearchInput">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"        stroke="currentColor" class="w-8 text-white">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                    </svg>
                </div>
            </div>
            <div class="bg-black/70 backdrop-blur w-screen min-h-lvh absolute bottom-0 right-0 left-0 -z-50 flex justify-center items-center" v-show="!SearchBox">
                <form method="get" class="inline-block">
                    <input type="search" name="q" placeholder="جستجوی سریع..." class="py-3 px-3 rounded-md bg-gray-700 text-gray-300 focus:text-base outline-none text-base font-medium w-96">
                </form>
            </div>
            <!-- login -->
            <div class="flex items-center bg-gray-700 px-2 py-1 rounded-lg">
                <NuxtLink to="/auth/login/">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-white">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15m3 0l3-3m0 0l-3-3m3 3H9" />
                    </svg>                                            
                </NuxtLink>  
            </div>
        </div>
    </nav>
</template>
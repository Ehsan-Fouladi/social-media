<template>
    <!-- content -->
    <div class="bg-slate-800 p-4 rounded-md">
        <div class="flex flex-row justify-between items-center mt-5">
            <span class="font-medium text-lg text-pretty text-white" v-if="false">نظری برای این عنوان وجود ندارد</span>
            <span class="font-medium text-lg text-pretty text-white">6 نظر</span>
            <div class="flex flex-row-reverse items-center">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                    class="size-6 text-yellow-500">
                    <path fill-rule="evenodd"
                        d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                        clip-rule="evenodd" />
                </svg>
                <span class="ml-2 py-1 px-2 text-sm bg-stone-800 text-white rounded-lg">55</span>
            </div>
        </div>
        <div class="mt-5 relative overflow-auto">
            <form action="#" class="flex flex-wrap gap-4 justify-center items-center" on-submit="">
                <div>
                    <input type="text" placeholder="نام"
                        class="px-3 py-2 rounded-lg outline-none bg-gray-600 text-gray-200 hover:placeholder:text-gray-100 duration-500 focus:ring-2 focus:ring-indigo-500 w-60 text-base font-medium">
                </div>
                <div>
                    <input type="email" placeholder="ایمیل"
                        class="px-3 py-2 rounded-lg outline-none bg-gray-600 text-gray-200 hover:placeholder:text-gray-100 duration-500 focus:ring-2 focus:ring-indigo-500 w-60 text-base font-medium">
                </div>
                <div>
                    <textarea name="object"
                        class="bg-gray-600 rounded-md w-72 resize-none outline-none px-2 text-gray-200 hover:text-gray-100 focus:resize-y focus:ring-2 focus:ring-indigo-500 duration-500"> موضوع</textarea>
                </div>
                <div>
                    <button
                        class="px-3 py-2 w-20 rounded-md text-white text-base hover:focus:bg-pink-600 duration-500">ارسال</button>
                </div>
            </form>
        </div>
        <div class="flex flex-col mt-4">
            <div class="flex flex-row items-center gap-4 cursor-pointer group">
                <span class="text-gray-100 font-medium text-pretty text-sm border-b-2">بهترین</span>
                <span class="text-gray-300 font-medium text-pretty text-sm">قدیمی ترین</span>
                <span class="text-gray-300 font-medium text-pretty text-sm">جدید ترین</span>
            </div>
            <div class="border mt-2 border-gray-400"></div>
            <div class="mt-5 border-2 border-indigo-500 rounded-md p-4" v-for="i in 4">
                <div class="flex flex-row gap-1">
                    <span class="text-gray-300 text-sm font-medium">ehsan .</span>
                    <span class="text-gray-300 text-sm font-medium">2 سال قبل</span>
                </div>
                <div class="mt-2">
                    <p class="leading-5 text-gray-300 font-medium text-pretty md:text-balance tracking-wide">Lorem ipsum
                        dolor sit amet consectetur adipisicing elit. Cumque quis dolore eos!</p>
                </div>
                <div class="mt-3 flex flex-row items-center gap-2">
                    <span class="block text-gray-300 font-medium cursor-pointer text-md">3<svg
                            xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M6.633 10.25c.806 0 1.533-.446 2.031-1.08a9.041 9.041 0 0 1 2.861-2.4c.723-.384 1.35-.956 1.653-1.715a4.498 4.498 0 0 0 .322-1.672V2.75a.75.75 0 0 1 .75-.75 2.25 2.25 0 0 1 2.25 2.25c0 1.152-.26 2.243-.723 3.218-.266.558.107 1.282.725 1.282m0 0h3.126c1.026 0 1.945.694 2.054 1.715.045.422.068.85.068 1.285a11.95 11.95 0 0 1-2.649 7.521c-.388.482-.987.729-1.605.729H13.48c-.483 0-.964-.078-1.423-.23l-3.114-1.04a4.501 4.501 0 0 0-1.423-.23H5.904m10.598-9.75H14.25M5.904 18.5c.083.205.173.405.27.602.197.4-.078.898-.523.898h-.908c-.889 0-1.713-.518-1.972-1.368a12 12 0 0 1-.521-3.507c0-1.553.295-3.036.831-4.398C3.387 9.953 4.167 9.5 5 9.5h1.053c.472 0 .745.556.5.96a8.958 8.958 0 0 0-1.302 4.665c0 1.194.232 2.333.654 3.375Z" />
                        </svg>
                    </span>
                    <span class="block text-gray-300 font-medium cursor-pointer text-md">2 <svg
                            xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M7.498 15.25H4.372c-1.026 0-1.945-.694-2.054-1.715a12.137 12.137 0 0 1-.068-1.285c0-2.848.992-5.464 2.649-7.521C5.287 4.247 5.886 4 6.504 4h4.016a4.5 4.5 0 0 1 1.423.23l3.114 1.04a4.5 4.5 0 0 0 1.423.23h1.294M7.498 15.25c.618 0 .991.724.725 1.282A7.471 7.471 0 0 0 7.5 19.75 2.25 2.25 0 0 0 9.75 22a.75.75 0 0 0 .75-.75v-.633c0-.573.11-1.14.322-1.672.304-.76.93-1.33 1.653-1.715a9.04 9.04 0 0 0 2.86-2.4c.498-.634 1.226-1.08 2.032-1.08h.384m-10.253 1.5H9.7m8.075-9.75c.01.05.027.1.05.148.593 1.2.925 2.55.925 3.977 0 1.487-.36 2.89-.999 4.125m.023-8.25c-.076-.365.183-.75.575-.75h.908c.889 0 1.713.518 1.972 1.368.339 1.11.521 2.287.521 3.507 0 1.553-.295 3.036-.831 4.398-.306.774-1.086 1.227-1.918 1.227h-1.053c-.472 0-.745-.556-.5-.96a8.95 8.95 0 0 0 .303-.54" />
                        </svg>
                    </span>|
                    <span class="block text-gray-300 font-medium cursor-pointer text-md">پاسخ</span>
                </div>
            </div>
        </div>
    </div>
</template>
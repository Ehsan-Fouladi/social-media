<template>
  <div class="bg-gray-800 flex flex-col items-center">
    <div class="md:h-dvh w-full flex flex-col lg:flex-row items-center">
      <img class="object-cover object-center rounded-xl lg:mr-24 w-72 h-auto mt-3 md:-mt-10"
           src="/image/The-Northman.jpg" alt="avatar" draggable="false">
      <div
          class="flex flex-col pr-3 space-y-2 lg:-mt-10 justify-center items-center lg:justify-normal lg:items-stretch">
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
                    d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
            </svg>
            <span class="text-white font-medium text-xs text-pretty">مدت زمان : هر قسمت میانگین 45 دقیقه</span>|
            <nuxt-link to="/productlist"
                       class="duration-500 hover:text-yellow-400 text-xs text-white">اکشن
            </nuxt-link>
            <nuxt-link to="/productlist"
                       class="duration-500 hover:text-yellow-400 text-xs text-white">جنایی
            </nuxt-link>
            <nuxt-link to="/productlist"
                       class="duration-500 hover:text-yellow-400 text-xs text-white">درام
            </nuxt-link>
            |
            <span class="text-white text-xs font-medium">محصول : <nuxt-link to="/productlist"
                                                                            class="duration-500 hover:text-yellow-400">آمریکا</nuxt-link></span>
          </div>
          <div class="mt-2 flex flex-row items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                 stroke="currentColor" class="size-4 text-white">
              <path stroke-linecap="round" stroke-linejoin="round"
                    d="m15.75 10.5 4.72-4.72a.75.75 0 0 1 1.28.53v11.38a.75.75 0 0 1-1.28.53l-4.72-4.72M4.5 18.75h9a2.25 2.25 0 0 0 2.25-2.25v-9a2.25 2.25 0 0 0-2.25-2.25h-9A2.25 2.25 0 0 0 2.25 7.5v9a2.25 2.25 0 0 0 2.25 2.25Z"/>
            </svg>
            <span class="text-xs text-white font-medium mr-2">کیفیت نمایش : <span
                class="uppercase">WEB-DL</span></span>
          </div>
          <div class="mt-2" v-if="true">
            <div class="flex flex-row items-center bg-yellow-800 px-2 py-2 rounded-lg w-60">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                   stroke="currentColor" class="w-6 h-6 text-white">
                <path stroke-linecap="round" stroke-linejoin="round"
                      d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z"/>
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
                      d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"/>
              </svg>
            </div>
            <div class="bg-gray-700 px-2 py-2 rounded-md">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                   stroke="currentColor" class="size-8 text-white">
                <path stroke-linecap="round" stroke-linejoin="round"
                      d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z"/>
              </svg>

            </div>
          </div>
          <div class="mt-2">
            <p class="text-base text-pretty text-white leading-snug">جک ریچر به جرم قتل دستگیر شد و اکنون پلیس به کمک او نیاز
              دارد. بر اساس کتاب های لی چایلد.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col gap-2 justify-center items-center bg-slate-700 w-full p-4 lg:-mt-24">
      <!-- header -->
      <div class="flex items-center text-sm md:text-base lg:text-lg w-full lg:w-3/4">
        <!-- download -->
        <div
            class="flex flex-row-reverse justify-center items-center gap-1 px-3 cursor-pointer py-2 font-medium rounded-r-lg w-1/3"
            :class="active_section === 1 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 1">
          <span>لینک های دانلود</span>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="size-5">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="m9 13.5 3 3m0 0 3-3m-3 3v-6m1.06-4.19-2.12-2.12a1.5 1.5 0 0 0-1.061-.44H4.5A2.25 2.25 0 0 0 2.25 6v12a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18V9a2.25 2.25 0 0 0-2.25-2.25h-5.379a1.5 1.5 0 0 1-1.06-.44Z"/>
          </svg>
        </div>
        <!-- related -->
        <div class="flex flex-row-reverse justify-center items-center gap-1 px-3 cursor-pointer py-2 font-medium w-1/3"
             :class="active_section === 2 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 2">
          <span>لینک های مرتبط</span>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="size-5">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M2.25 18.75a60.07 60.07 0 0 1 15.797 2.101c.727.198 1.453-.342 1.453-1.096V18.75M3.75 4.5v.75A.75.75 0 0 1 3 6h-.75m0 0v-.375c0-.621.504-1.125 1.125-1.125H20.25M2.25 6v9m18-10.5v.75c0 .414.336.75.75.75h.75m-1.5-1.5h.375c.621 0 1.125.504 1.125 1.125v9.75c0 .621-.504 1.125-1.125 1.125h-.375m1.5-1.5H21a.75.75 0 0 0-.75.75v.75m0 0H3.75m0 0h-.375a1.125 1.125 0 0 1-1.125-1.125V15m1.5 1.5v-.75A.75.75 0 0 0 3 15h-.75M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm3 0h.008v.008H18V10.5Zm-12 0h.008v.008H6V10.5Z"/>
          </svg>
        </div>
        <!-- comments -->
        <div
            class="flex flex-row-reverse justify-center items-center gap-1 px-3 cursor-pointer py-2 font-medium rounded-l-lg w-1/3"
            :class="active_section === 3 ? 'bg-yellow-500' : 'bg-gray-600 text-white'" @click="active_section = 3">
          <span>نظرات کاربران</span>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="size-5">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M8.625 12a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H8.25m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H12m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0h-.375M21 12c0 4.556-4.03 8.25-9 8.25a9.764 9.764 0 0 1-2.555-.337A5.972 5.972 0 0 1 5.41 20.97a5.969 5.969 0 0 1-.474-.065 4.48 4.48 0 0 0 .978-2.025c.09-.457-.133-.901-.467-1.226C3.93 16.178 3 14.189 3 12c0-4.556 4.03-8.25 9-8.25s9 3.694 9 8.25Z"/>
          </svg>
        </div>
      </div>
      <!-- content -->
      <div class="w-full lg:w-4/5">
        <WidgetDownload v-if="active_section === 1"/>
        <WidgetTitleRelated v-if="active_section === 2"/>
        <WidgetComments v-if="active_section === 3"/>
      </div>
    </div>
    <div class="w-full p-5 bg-slate-700 flex flex-col items-center justify-center">
      <div class="flex flex-row-reverse justify-end items-center gap-2 text-white w-4/5 ml-16 md:ml-0">
        <span>نکات قابل توجه قبل از دانلود</span>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
             class="size-5">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M12 9v3.75m0-10.036A11.959 11.959 0 0 1 3.598 6 11.99 11.99 0 0 0 3 9.75c0 5.592 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.31-.21-2.57-.598-3.75h-.152c-3.196 0-6.1-1.25-8.25-3.286Zm0 13.036h.008v.008H12v-.008Z"/>
        </svg>
      </div>
      <div class="bg-gray-800 p-4 rounded-md w-full lg:w-4/5 mt-2">
        <ul class="cursor-pointer text-gray-400 list-outside list-decimal mr-4 text-pretty font-medium text-sm leading-6">
          <li>تمامی عناوین سایت به صورت اصلی و بدون دستکاری می باشد.</li>
          <li>برای دانلود و اجرای فیلم ها حتما صفحه نرم افزارهای مورد نیاز را مشاهده کنید.
            <NuxtLink to="/" class="text-yellow-400"> نرم افزار موردنیاز</NuxtLink>
          </li>
          <li>برای دریافت آخرین اطلاع رسانی ها حتما صفحه
            <NuxtLink to="/" class="text-yellow-400">اینستاگرام</NuxtLink>
            و کانال
            <NuxtLink to="/" class="text-yellow-400">تلگرام</NuxtLink>
            ما را دنبال کنید.
          </li>
          <li>توجه داشته باشید بعضی از فیلم ها بصورت زیرنویس چسبیده هستند و برای بعضی فایل زیرنویس برای دانلود قرار
            گرفته اند و زیرنویس چسبیده نیستند. توضیحات هر پست را با دقت مطالعه فرمایید.
          </li>
          <li> در صورتی که فیلم مورد نظر شما حاوی فایل زیرنویس بصورت جداگانه بود و اگر با مشکل بهم ریختگی زیرنویس مواجه
            بودید
            <NuxtLink to="/" class="text-yellow-400">اینجا کلیک کنید</NuxtLink>
          </li>
          <li>جهت مشاهده آموزش هماهنگ کردن زیرنویس با فیلم
            <NuxtLink to="/" class="text-yellow-400">اینجا کلیک کنید</NuxtLink>
          </li>
          <li>در صورت وجود مشکل در لینکها و ... از طریق پنل کاربری تیکت ارسال نمایید</li>
        </ul>
      </div>
    </div>
    <div class="w-full bg-slate-700 flex flex-col md:items-center justify-center self-center">
      <div class="flex flex-row-reverse justify-end items-center gap-2 text-white w-4/5">
        <span>برچسب ها</span>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
             class="size-5">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M13.19 8.688a4.5 4.5 0 0 1 1.242 7.244l-4.5 4.5a4.5 4.5 0 0 1-6.364-6.364l1.757-1.757m13.35-.622 1.757-1.757a4.5 4.5 0 0 0-6.364-6.364l-4.5 4.5a4.5 4.5 0 0 0 1.242 7.244"/>
        </svg>
      </div>
      <div class="mt-2 flex flex-wrap gap-2 w-3/4 mr-4 md:mr-0">
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty">
                        دانلود سریال Reacher
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        زیرنویس فارسی سریال Reacher
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        زیرنویس فارسی فصل دوم سریال Reacher
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        سریال Reacher با زیرنویس
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        سریال Reacher فصل دوم بدون سانسور 
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        سریال ریچر Reacher 2022
                    </span>
        </div>
        <div
            class="px-2 py-1 flex justify-center items-center rounded-xl bg-gray-800 w-auto hover:bg-gray-700 duration-500 cursor-pointer">
                    <span class="text-gray-400 hover:text-yellow-400 duration-500 font-medium text-sm text-pretty"> 
                        فصل دوم سریال Reacher
                    </span>
        </div>
      </div>
    </div>
    <div class="w-full">
      <BodyFooter/>
    </div>
  </div>
</template>
<script setup>
const active_section = ref(1)
</script>
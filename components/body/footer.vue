<template>
    <div class="flex flex-col">
        <div class="bg-yellow-500 p-6 w-full flex justify-center items-center">
            <p class="font-medium leading-7 text-justify tracking-tight max-w-5xl">
                آیوفیلم یکی از متفاوت ترین رسانه های سرگرمی کشور در زمینه فیلم ، انیمه و سریال است که با ایده ای نوین و طیف وسیع موضوعات مطالب سعی در ارائه هر گونه محتوا برای مخاطبان خود دارد. انواع فیلم خارجی ، انیمه ژاپنی ، سریال کره ای و سریال ترکی به صورت اختصاصی ، لینک های دانلود رایگان با کیفیت عالی ، نسخه زبان اصلی و همچنین جستجوی زیر نویس فارسی هر فیلم ، سریال و انیمه را می توانید در آیوفیلم انجام دهید.
            </p>
        </div>
        <div class="p-4 mt-4 flex flex-col lg:flex-row">
            <ul class="text-gray-400 block lg:pr-20 space-y-4">
                <li class="hover:text-yellow-500 list-disc"><a href="#">درخواست فیلم سریال</a></li>
                <li class="hover:text-yellow-500 list-disc"><a href="#">انتقاد پیشنهاد</a></li>
                <li class="hover:text-yellow-500 list-disc"><a href="#">گزارش خرابی و مشکل</a></li>
            </ul>
            <ul class="text-gray-400 block lg:pr-32 space-y-4 mt-5 lg:mt-0">
                <li class="hover:text-yellow-500 list-disc"><a href="#">ایوترند</a></li>
                <li class="hover:text-yellow-500 list-disc"><a href="#">تبلیغات</a></li>
                <li class="hover:text-yellow-500 list-disc"><a href="#">DMCA</a></li>
            </ul>
        </div>
        <div class="bg-gray-800 p-3 w-full flex justify-around mt-4">
            <span class="text-gray-400 text-sm md:text-base">تمامی حقوق این سایت برای احسان فولادی است</span>
            <span class="text-sm md:text-base text-gray-400"><span>© {{ TimeDate }}</span> All Rights Reserved</span>
        </div>
    </div>
</template>
<script setup>
const TimeDate = ref()
onMounted(() => {
    TimeDate.value = new Date().getFullYear()
})
</script>
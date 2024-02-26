<template>
    <div class="mt-7">
        <!-- links -->
        <div class="cursor-pointer">
            <div class="text-center px-3 py-2 font-medium" :class="active_section == 3 ? 'bg-gray-600 text-white' : ' bg-yellow-500 text-black'" @click="active_section = 2">عناوین مرتبط</div>
        </div>
    </div>
    <!-- content -->
    <div class="flex justify-center items-center w-full absolute right-0 left-0 bg-slate-700" v-if="active_section === 2">
        <div class="mt-8 flex flex-wrap gap-2">
            <Product v-for="i in 5"/>
        </div>
    </div>
</template>
<script setup>
const active_section = ref(3)
</script>
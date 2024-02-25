<template>
    <div class="mt-7">
        <!-- links -->
        <div class="cursor-pointer">
            <div class="text-center px-3 py-2 font-medium" :class="active_section == 3 ? 'rounded-l-lg bg-yellow-500 text-black' : 'rounded-l-lg bg-gray-600 text-white'" @click="active_section = 3">نظرات</div>
        </div>

        <!-- content -->
        <div class="flex flex-col w-full">
            <div class="border px-16 text-center py-10 rounded-lg" v-if="active_section === 3">Active 3</div>
        </div>
    </div>
</template>
<script setup>
const active_section = ref(2)
</script>
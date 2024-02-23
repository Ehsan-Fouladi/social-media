<template>
    <div class="flex flex-col w-full gap-2 bg-gray-200">
        <!-- links -->
        <div class="flex items-center w-full justify-evenly py-6">
            <div class="border rounded-md py-3 px-8 shadow cursor-pointer" :class="active_section == 1 ? 'border-red-900' : 'text-center'" @click="active_section = 1">Active 1</div>
            <div class="border rounded-md py-3 px-8 shadow cursor-pointer" :class="active_section == 2 ? 'border-red-900' : 'text-center'" @click="active_section = 2">Active 2</div>
            <div class="border rounded-md py-3 px-8 shadow cursor-pointer" :class="active_section == 3 ? 'border-red-900' : 'text-center'" @click="active_section = 3">Active 3</div>
        </div>

        <!-- content -->
        <div class="flex flex-col w-full">
            <div class="border px-16 text-center py-10 rounded-lg" v-if="active_section === 1">Active 1</div>
            <div class="border px-16 text-center py-10 rounded-lg" v-if="active_section === 2">Active 2</div>
            <div class="border px-16 text-center py-10 rounded-lg" v-if="active_section === 3">Active 3</div>
        </div>
    </div>
</template>
<script setup>
const active_section = ref(1)
</script>
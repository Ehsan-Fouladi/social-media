<template>
    <div>
        {{ category  }}
    </div>
</template>
<script setup>
import { onMounted } from 'vue';

const category = ref('')

onMounted(() => {
    category.value = useRoute().params.category
})
definePageMeta({
  layout: false  
})
</script>

<template>
    <div>
        {{ category  }}
    </div>
</template>
<script setup>
const category = ref('video')

onMounted(() => {
    category.value = useRoute().params.category
})
definePageMeta({
  layout: false  
})
</script>

<template>
    Hello, World! 3
</template>

<script setup>
import { useRouter } from 'vue-router'
const router = useRouter()

router.push({ name: 'course' })
</script>
<style lang="sass" scoped>
</style>

<template lang="pug">
#left-update
    |   {{ date }}
</template>

<script setup>
import { ref } from 'vue'
// 取url寫法

const date = ref(new Date().toLocaleDateString())
</script>

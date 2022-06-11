<style lang="sass" scoped>
</style>

<template lang="pug">
#top-image
    img(src="../assets/logo2.png")
    img(:src="img")

</template>

<script setup>
import { ref } from 'vue'
// 取url寫法

const img = ref(new URL('../assets/logo2.png', import.meta.url).href)
console.log(img.value)
</script>

<script setup>
import TopPart from './components/TopPart.vue'
import LeftMenu from './components/LeftMenu.vue'
import LeftUpdate from './components/LeftUpdate.vue'
</script>

<template lang="pug">
TopPart
#center
    #left
        LeftMenu
        LeftUpdate
    #right
</template>

<style lang="sass">
</style>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheNavbarVue from './components/TheNavbar.vue'
import TheFooterVue from './components/TheFooter.vue'

</script>

<template>

  <body>

    <TheNavbarVue />

    <RouterView />

    <TheFooterVue />

  </body>
</template>
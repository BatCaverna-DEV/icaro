<script setup>

  import { RouterLink, RouterView } from 'vue-router'

  import 'bootstrap/dist/css/bootstrap.css'
  import 'bootstrap/dist/js/bootstrap.bundle.js'
  import Navbar from "@/components/Navbar.vue";

</script>

<template>
  <header>
    <Navbar/>
  </header>

  <RouterView />
</template>

<style scoped>

</style>

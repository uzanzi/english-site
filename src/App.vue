<script setup>
import { RouterView } from 'vue-router'
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

</script>

<template>
  <header>
    <Header />
  </header>
  <RouterView />
  <Footer />
</template>

<style scoped></style>
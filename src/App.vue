<script setup lang="ts">
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <Header/>
  <Main/>
  <Footer/>
</template>

<style lang="scss">
  @import "./assets/globalStyles.scss";
  body {
    margin: 0 45px;
  }
</style>
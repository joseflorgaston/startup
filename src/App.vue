<template>
  <div>
    <Header></Header>
    <HeroSection> </HeroSection>
    <MainVue></MainVue>
    <FooterVue></FooterVue>
  </div>
</template>

<script setup lang="ts">
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import MainVue from './components/Main.vue';
import FooterVue from './components/Footer.vue';
</script>

<style>
@import 'assets/css/style.css';
@import 'assets/vendor/aos/aos.css';
@import 'assets/vendor/bootstrap/css/bootstrap.min.css';
@import 'assets/vendor/bootstrap-icons/bootstrap-icons.css';
@import 'assets/vendor/boxicons/css/boxicons.min.css';
@import 'assets/vendor/glightbox/css/glightbox.min.css';
@import 'assets/vendor/remixicon/remixicon.css';
@import 'assets/vendor/swiper/swiper-bundle.min.css';

a {
  text-decoration: none;
}
</style>

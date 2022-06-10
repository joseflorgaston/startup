<template>
  <div>
    <Header></Header>
    <HeroSection> </HeroSection>
    <MainVue></MainVue>
    <FooterVue></FooterVue>
  </div>
</template>

<script lang="ts">
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import MainVue from './components/Main.vue';
import FooterVue from './components/Footer.vue';

export default {
  components: {Header, HeroSection, MainVue, FooterVue},
  mounted() {
    let aos = document.createElement('script');
    let bootstrap = document.createElement('script');
    let glightbox = document.createElement('script');
    let isotope = document.createElement('script');
    let swiper = document.createElement('script');
    let waypoints = document.createElement('script');
    let php = document.createElement('script');
    let main = document.createElement('script');
    aos.setAttribute('src', './src/assets/vendor/aos/aos.js');
    bootstrap.setAttribute('src', './src/assets/vendor/bootstrap/js/bootstrap.bundle.min.js');
    glightbox.setAttribute('src', './src/assets/vendor/glightbox/js/glightbox.min.js');
    isotope.setAttribute('src', './src/assets/vendor/isotope-layout/isotope.pkgd.min.js');
    swiper.setAttribute('src', './src/assets/vendor/swiper/swiper-bundle.min.js');
    waypoints.setAttribute('src', './src/assets/vendor/waypoints/noframework.waypoints.js');
    php.setAttribute('src', './src/assets/vendor/php-email-form/validate.js');
    main.setAttribute('src', './src/assets/js/main.js');
    
    document.head.appendChild(aos)
    document.head.appendChild(bootstrap)
    document.head.appendChild(glightbox)
    document.head.appendChild(isotope)
    document.head.appendChild(swiper)
    document.head.appendChild(waypoints)
    document.head.appendChild(php)
    document.head.appendChild(main)
  }
}

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

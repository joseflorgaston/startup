<template>
  <div v-for="(item, index) in services" :key="index" class="col-xl-3 col-md-6 d-flex align-items-stretch" data-aos="zoom-in" data-aos-delay="100">
    <div class="icon-box">
      <div class="icon"><i :class="`bx ${item.icon}`"></i></div>
      <h4><a href="#">{{ item.title }}</a></h4>
      <p>{{ item.description }}</p>
    </div>
  </div>

</template>

<script setup lang="ts">
const services = [
  {
    title: 'Ecommerce',
    icon: 'bx-store',
    description: 'Desarrollamos su Ecommerce a medida.'
  },
  {
    title: 'Development and Design Web',
    icon: 'bx-code-alt',
    description: 'Disenhamos y Desarrollamos tu página web para obtener un mayor alcance.'
  },
  {
    title: 'SEO',
    icon: 'bx-tachometer',
    description: 'Ejecutamos estrategias y técnicas de optimización que se hacen en una página web para que aparezca orgánicamente en buscadores de Internet.'
  }
]
</script>

<style scoped>
</style>
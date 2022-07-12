<template>
  <div v-for="(item, index) in services" :key="index" class="col-12 mt-3 mt-sm-0 col-xl-3 col-md-6 d-flex align-items-stretch" data-aos="zoom-in" data-aos-delay="100">
    <div class="icon-box" style="width: 100%;">
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
    title: 'Web Development',
    icon: 'bx-code-alt',
    description: 'Diseñamos y desarrollamos tu página web para obtener un mayor alcance.'
  },
  {
    title: 'Multiplatform apps',
    icon: 'bx-devices',
    description: 'Diseñamos y desarrollamos tus aplicaciones multiplataforma para IOS y Android.'
  },
  {
    title: 'SEO',
    icon: 'bx-tachometer',
    description: 'Ejecutamos estrategias y técnicas de optimización para mejorar el posicionamiento web en distintos buscadores de Internet.'
  }
]
</script>

<style scoped>
</style>
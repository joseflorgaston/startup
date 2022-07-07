<template>
  <div v-for="(item, index) in items" :key="index"  class="col-lg-6 mt-4">
    <div class="member d-flex align-items-start aos-init aos-animate" data-aos="zoom-in" data-aos-delay="100">
      <div class="pic"><img :src="item.image" class="img-fluid" alt=""></div>
      <div class="member-info">
        <h4>{{ item.name }}</h4>
        <span>{{ item.role }}</span>
        <p>{{ item.phrase }}</p>
        <div class="social">
          <a :href="`${item.socials['twitter']}`" aria-label="Twitter"><i class="ri-twitter-fill"></i></a>
          <a :href="`${item.socials['github']}`" aria-label="Github"><i class="ri-github-fill"></i></a>
          <a :href="`${item.socials['instagram']}`" aria-label="Instagram"><i class="ri-instagram-fill"></i></a>
          <a :href="`${item.socials['linkedin']}`" aria-label="LinkedIn"> <i class="ri-linkedin-box-fill"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const items = [
  {
    name: 'Mauricio Acosta',
    role: 'CEO',
    phrase: '"Aprender a programar no tiene más que ver con el diseño de software interactivo de aprender a tocar el tipo tiene que ver con la escritura de la poesía"',
    image: '/src/assets/img/team/mauri.jpg',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Jorge Santiago Penayo',
    role: 'CTO',
    phrase: '"Hablar es barato. Enséñame el código" - Linus Torvalds',
    image: '/src/assets/img/team/santi.jfif',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Marcos Escobar',
    role: 'Co-Founder',
    phrase: '"Clean code always looks like it was written by someone who cares" - Robert C. Martin',
    image: '/src/assets/img/team/marcos.jfif',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Jose Flor',
    role: 'Co-Founder',
    phrase: '"La creatividad es la inteligencia divirtiéndose" - Albert Einstein',
    image: '/src/assets/img/team/jose.jfif',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Renato Jara',
    role: 'Co-Founder',
    phrase: '"La creatividad es la inteligencia divirtiéndose" - Albert Einstein',
    image: '/src/assets/img/team/renato.jfif',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Josias Noguera',
    role: 'Co-Founder',
    phrase: '"Happiness comes from within" - Anders Hejlsberg',
    image: '/src/assets/img/team/josias.jfif',
    socials: [
      {
        twitter: '',
        github: '',
        instagram: 'https://www.instagram.com/macosta.19/',
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
]
</script>

<style scoped>

</style>
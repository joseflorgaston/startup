<template>
  <div v-for="(item, index) in items" :key="index"  class="col-lg-6 mt-4">
    <div class="member d-flex align-items-start aos-init aos-animate" data-aos="zoom-in" data-aos-delay="100">
      <div class="pic"><img :src="item.image" class="img-fluid" alt=""></div>
      <div class="member-info">
        <h4>{{ item.name }}</h4>
        <span>{{ item.role }}</span>
        <p>{{ item.phrase }}</p>
        <div class="social">
          <a v-if="item.socials[0]['instagram']" :href="`${item.socials[0]['instagram']}`" aria-label="Instagram"><i class="ri-instagram-fill"></i></a>
          <a v-if="item.socials[0]['github']" :href="`${item.socials[0]['github']}`" aria-label="Github"><i class="ri-github-fill"></i> </a>
          <a v-if="item.socials[0]['linkedin']" :href="`${item.socials[0]['linkedin']}`" aria-label="LinkedIn"> <i class="ri-linkedin-box-fill"></i></a>
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
    phrase: '"Innovation distinguishes between a leader and a follower" - Steve Jobs',
    image: '/src/assets/img/team/mauri.jpg',
    socials: [
      {
        instagram: 'https://www.instagram.com/macosta.19/',
        github: null,
        linkedin: 'https://www.linkedin.com/in/mauricio-sebastian-acosta-rojas-561921226/'
      }
    ]
  },
  {
    name: 'Jorge Santiago Penayo',
    role: 'CTO',
    phrase: '"Talk is cheap. Show me the code" - Linus Torvalds',
    image: '/src/assets/img/team/santi.jfif',
    socials: [
      {
        instagram: null,
        github: 'https://github.com/jorgestg',
        linkedin: 'https://www.linkedin.com/in/jorgestg/'
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
        instagram: 'https://www.instagram.com/_escmarcos/',
        github: 'https://github.com/MarcosEscobarR',
        linkedin: 'https://www.linkedin.com/in/marcos-escobar-3a86a41a0/'
      }
    ]
  },
  {
    name: 'Jose Flor',
    role: 'Co-Founder',
    phrase: '"Creativity is intelligence having fun" - Albert Einstein',
    image: '/src/assets/img/team/jose.jfif',
    socials: [
      {
        instagram: 'https://www.instagram.com/joseflorgaston/',
        github: 'https://github.com/joseflorgaston',
        linkedin: 'https://www.linkedin.com/in/joseflorgaston/'
      }
    ]
  },
  {
    name: 'Renato Jara',
    role: 'Co-Founder',
    phrase: '"I could either watch it happen, or be part of it" - Albert Einstein',
    image: '/src/assets/img/team/renato.jfif',
    socials: [
      {
        instagram: 'https://www.instagram.com/renato_jn/',
        github: null,
        linkedin: 'https://www.linkedin.com/in/renatojara/'
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
        github: 'https://github.com/jdnoguera',
        instagram: 'https://www.instagram.com/josiasnoguera.s/',
        linkedin: 'https://www.linkedin.com/in/josiasnoguera/'
      }
    ]
  },
]
</script>

<style scoped></style>
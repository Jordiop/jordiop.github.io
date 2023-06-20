<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <div class="h-screen flex flex-col">
    <Navbar />
    <div class="flex-grow">
      <div class="hero min-h-screen" style="background-image: url(https://vastphotos.com/files/uploads/photos/10252/mountains-in-autumn-landscape-l.jpg);">
        <div class="hero-overlay bg-opacity-60"></div>
        <div class="hero-content text-center text-neutral-content">
          <div class="max-w-md">
            <h1 class="mb-5 text-5xl font-bold">Hello there</h1>
            <p class="mb-5">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem
              quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
            <button class="btn btn-primary">Get Started</button>
          </div>
        </div>
      </div>
      <RouterView />
    </div>
    <Footer />
  </div>
</template>

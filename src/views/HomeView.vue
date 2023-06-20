<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
    <div class="h-screen flex flex-col">
        <Navbar />
        <div class="flex-grow">
            <RouterView />
        </div>
        <Footer />
    </div>
</template>

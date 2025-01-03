<script setup>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';
import { RouterView } from 'vue-router';
import { onMounted } from 'vue';
import { initFlowbite } from 'flowbite';

onMounted(() => {
    initFlowbite();
});

</script>

<template>
  <Navbar />
  <RouterView />
  <Footer />
</template>

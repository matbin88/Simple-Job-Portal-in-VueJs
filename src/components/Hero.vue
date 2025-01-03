<script setup>
import { defineProps } from 'vue';

defineProps({
  title: {
    type: String,
    default: 'Launch Your Career as a Vue Developer',
  },
  subtitle: {
    type: String,
    default: 'Discover Jobs that Match Your Skills and Ambitions',
  },
});
</script>

<template>
  <section class="bg-green-700 py-14">
    <div class="container-xl lg:container m-auto"><div class="grid grid-cols-1 px-8">
      <div class="text-start">
        <h1 class="text-2xl font-extrabold text-white sm:text-3xl md:text-4xl">
          {{ title }}
        </h1>
        <p class="my-4 text-xl text-white">
          {{ subtitle }}
        </p>
      </div>
    </div></div>
    <div
      class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col"
    >
      
    </div>
  </section>
</template>

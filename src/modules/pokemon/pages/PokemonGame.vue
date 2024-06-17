<template>
  <section v-if="false" class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="text-3xl animate-pulse">Loading...</h1>
  </section>

  <section class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="text-3xl m-5">Who's that Pokemon</h1>
    <!-- Pokemon picture -->
    <PokemonPicture />

    <!-- Pokemon options -->
    <PokemonOptions />
  </section>
</template>

<script setup lang="ts">
import PokemonOptions from '../components/PokemonOptions.vue';
import PokemonPicture from '../components/PokemonPicture.vue';
</script>

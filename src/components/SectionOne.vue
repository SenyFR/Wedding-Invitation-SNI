<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <div class="-mt-28 sm:mt-0 flex flex-col space-y-10 w-full">
    <h1 class="w-full text-center text-3xl sm:text-6xl text-judul">{{msg}}</h1>
    <img class="mx-auto transform scale-95" alt="Home logo" src="src/assets/home.png" />
  </div>
</template>

<style scoped>

</style>

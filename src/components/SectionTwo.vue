<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <div class="w-full flex flex-col space-y-5 sm:space-y-0 sm:flex-row justify-between">

    <div class="flex flex-col space-y-10 w-full sm:w-1/2 py-10">
      <h1 class="w-full text-left text-3xl sm:text-4xl text-judul">{{msg}}</h1>
      <p class="second-text text-lg">
        I'm a paragraph. Click here to add your own text and edit me, It’s easy. Just click “Edit Text” or double click me and you can start adding your own content and make changes to the font. I’m a great place for you to tell a story and let your users know a little more about you.
      </p>
    </div>

    <div class="hidden sm:flex relative flex-col w-full sm:w-1/2 h-screen height-screen-minimum">
      <img class="-mt-20 transform scale-75 absolute z-20 top-0" alt="Home logo" src="src/assets/1.png" />

      <video class="ml-28 -mt-20 transform scale-75 absolute z-30 top-52" autoplay="autoplay" loop="loop">
        <source src="src/assets/vid1.mp4" type="video/mp4" />
      </video>

<!--      <img class="ml-28 -mt-20 transform scale-75 absolute z-30 top-52" alt="Home logo" src="src/assets/2.png" />-->
      <img class="-mt-20 transform scale-75 absolute z-10 top-80" alt="Home logo" src="src/assets/3.png" />
    </div>

    <div class="flex sm:hidden relative flex-col w-full sm:w-1/2 h-screen height-screen-minimum">
      <img class="" alt="Home logo" src="src/assets/2.png" />
    </div>

  </div>
</template>

<style scoped>

</style>

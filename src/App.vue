<script setup lang="ts">

import SectionTwo from './components/SectionTwo.vue'
import SectionOne from "./components/SectionOne.vue";

</script>

<template>
  <div class="sm:space-y-10 px-10 sm:px-20 w-full max-w-screen-2xl mx-auto">
    <div class="w-full h-screen flex flex-wrap content-center height-screen-minimum">
      <SectionOne msg="Seny & Irfan" />
    </div>
    <div class="w-full h-screen height-screen-minimum">
      <SectionTwo msg="SHE SAID YES" />
    </div>
  </div>
</template>

<style>

</style>

<template>
  <div class="app">
    <index class="mx-5 mt-5" />
    <indexInput class="mx-5 mt-5" />
    <indexCarousel />
    <indexNotification class="mx-5 mt-5 mb-5" />
  </div>
</template>

<script setup>
import index from "@/components/buttons/index";
import indexInput from "@/components/input/index";
import indexCarousel from "@/components/carousel/index";
import indexNotification from "@/components/notification/index.vue";
</script>

<style lang="scss" scoped>
.app {
  width: 100%;
  font-family: sans-serif;
  display: flex;
  flex-direction: column;
}
</style>

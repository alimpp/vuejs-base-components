<template>
  <div class="app px-5 pt-2">
    <index />
    <indexInput />
  </div>
</template>

<script setup>
import index from "@/components/buttons/index";
import indexInput from "@/components/input/index";
</script>

<style lang="scss" scoped>
.app {
  width: 100%;
  font-family: sans-serif;
  display: flex;
  flex-direction: column;
}
</style>

<template>
  <div class="app">
    <h5>Application Buttons</h5>
    <hr>
    <baseButton/>
  </div>  
</template>

<script setup>
import baseButton from '@/components/baseButton'
</script>

<style lang="scss" scoped>
.app{
  width: 100%;
  font-family: sans-serif;
  display: flex;
  flex-direction: column;
}
</style>

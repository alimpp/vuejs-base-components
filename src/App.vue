<template>
  <div class="app px-5 pt-2">
    <h6>Normal Buttons</h6>
    <div class="d-flex">
      <baseButton color="primary" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="secondary" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="success" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="danger" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="warning" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="info" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="light" name="Hello World...!" :loading="false"/>
      <baseButton class="mx-1" color="dark" name="Hello World...!" :loading="false"/>
    </div>
    <h6 class="pt-5">Loading Buttons</h6>
    <div class="d-flex">
      <baseButton color="primary" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="secondary" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="success" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="danger" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="warning" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="info" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="light" name="Hello World...!" :loading="true"/>
      <baseButton class="mx-1" color="dark" name="Hello World...!" :loading="true"/>
    </div>
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

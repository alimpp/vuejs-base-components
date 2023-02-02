<template>
  <div class="mt-5">
    <span>Application Input</span>
    <baseInput placeholder="Username" icon="username" :hasError="false" />
    <span class="pt-2">Error Input</span>
    <baseInput placeholder="Email" icon="email" :hasError="true" />
    <span class="pt-2">Disable Input</span>
    <baseInput placeholder="Gender" icon="gender" :hasError="true" :disable="true" />
  </div>
</template>

<script setup>
import baseInput from "@/components/base/baseInput";
</script>

<style></style>

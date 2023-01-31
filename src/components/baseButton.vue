<template>
    <div class="base-button-container d-flex flex-column">
      <button
        class="btn-sm btn white_color"
        :class="{}"
      >

        <div v-if="loading">
        <div
          class="spinner-border spinner-border-sm text-light"
          role="status"
          v-if="loading"
        ></div>
        <span>Loading</span>
        </div>

        <div v-else>
        <i
          class="bi"
          :class="{}"
        ></i>
        {{ name }}
        </div>

      </button>
    </div>
  </template>
  
  <script setup>
  import { computed } from "vue";

  const props = defineProps({
    color: {
      type: String,
      default: "",
      required: true,
    },
    name: {
      type: String,
      default: "",
      required: true,
    },
    loading: {
      type: Boolean,
      default: false,
      required: false,
    },
    icon: {
      type: String,
      default: "",
      required: false,
    },
  });
  </script>

 <style lang="scss" scoped>
  
  </style>
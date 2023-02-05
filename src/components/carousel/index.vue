<template>
  <div>
    <baseCarousel class="mt-5 mb-5" :slides="slides" autoplayTime="3000" />
  </div>
</template>

<script setup>
import baseCarousel from "@/components/base/baseCarousel";
const slides = [
  {
    id: "1",
    title: "Vue 3 Introduction",
    content: "VueJS is a library",
    image:
      "https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/640px-Image_created_with_a_mobile_phone.png",
  },
  {
    id: "2",
    title: "Vue 3 Components",
    content: "Know the components",
    image: "https://imgv3.fotor.com/images/blog-cover-image/part-blurry-image.jpg",
  },
  {
    id: "3",
    title: "Vue 3 Conditional",
    content: "Rendering Conditionally",
    image:
      "https://media.macphun.com/img/uploads/customer/how-to/608/15542038745ca344e267fb80.28757312.jpg?q=85&w=1340",
  },
];
</script>

<style></style>

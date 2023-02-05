<template>
  <div class="d-flex flex-column">
    <h6>Application Notification</h6>
   <div class="d-flex">
    <baseButton icon="user" name="Success" color="success" @click="successNotification" />
    <baseButton icon="user" name="Warning" color="warning" class="mx-2" @click="warningNotification" />
    <baseButton icon="user" name="Info" color="info" class="mx-2" @click="infoNotification" />
    <baseButton icon="user" name="Error" color="danger" class="mx-2" @click="errorNotification" />
   </div>
  </div>
</template>

<script setup>
import baseButton from "@/components/base/baseButton";
import {
  SuccessNotification,
  InfoNotification,
  WarningNotification,
  ErrorNotification,
} from "../base/notification";

const errorNotification = () => {
  ErrorNotification("2000", "Hello World...!", "bottom-center");
};

const successNotification = () => {
  SuccessNotification("2000", "Hello World...!", "bottom-center");
};

const infoNotification = () => {
  InfoNotification("2000", "Hello World...!", "bottom-center");
};

const warningNotification = () => {
  WarningNotification("2000", "Hello World...!", "bottom-center");
};
</script>

<style></style>

<template>
  <div class="d-flex flex-column">
    <h6>Normal Buttons</h6>
    <div class="d-flex">
      <baseButton
        color="primary"
        name="Hello World...!"
        :loading="false"
        icon="chat"
      />
      <baseButton
        class="mx-1"
        color="secondary"
        name="Hello World...!"
        :loading="false"
        icon="email"
      />
      <baseButton
        class="mx-1"
        color="success"
        name="Hello World...!"
        :loading="false"
        icon="user"
      />
      <baseButton
        class="mx-1"
        color="danger"
        name="Hello World...!"
        :loading="false"
        icon="send"
      />
      <baseButton
        class="mx-1"
        color="warning"
        name="Hello World...!"
        :loading="false"
        icon="send"
      />
      <baseButton
        class="mx-1"
        color="info"
        name="Hello World...!"
        :loading="false"
        icon="send"
      />
      <baseButton
        class="mx-1"
        color="light"
        name="Hello World...!"
        :loading="false"
        icon="send"
      />
      <baseButton
        class="mx-1"
        color="dark"
        name="Hello World...!"
        :loading="false"
        icon="send"
      />
    </div>
    <h6 class="pt-5">Loading Buttons</h6>
    <div class="d-flex">
      <baseButton color="primary" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="secondary" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="success" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="danger" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="warning" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="info" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="light" name="Hello World...!" :loading="true" />
      <baseButton class="mx-1" color="dark" name="Hello World...!" :loading="true" />
    </div>
    <h6 class="pt-5">Disabled Buttons</h6>
    <div class="d-flex">
      <baseButton
        color="primary"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="secondary"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="success"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="danger"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="warning"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="info"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="light"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
      <baseButton
        class="mx-1"
        color="dark"
        name="Hello World...!"
        :loading="true"
        :disable="true"
      />
    </div>
  </div>
</template>

<script setup>
import baseButton from "@/components/base/baseButton";
</script>

<style></style>

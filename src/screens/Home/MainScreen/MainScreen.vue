<script setup lang="ts">
// @ts-ignore
import Button from "@components/Button/Button.vue";
</script>

<template lang="">
  <div class="content-container">
    <h1 class="mt-16">Welcome to my game</h1>
    <p class="mt-4">Press start button to start my game</p>
    <Button text="Start Game" />
  </div>
</template>
<script lang="ts">
export default {
  name: "MainScreen",
};
</script>
<style lang=""></style>

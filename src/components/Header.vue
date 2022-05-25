
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
});
</script>

<template>
  <div>
    <img alt="Vue logo" class="logo" src="src\assets\logo.svg" width="125" height="125" />
    <h1>{{ msg }}</h1>
    <h5>Test project for testing and learn Vue</h5>
  </div>
</template>

<style>
</style>

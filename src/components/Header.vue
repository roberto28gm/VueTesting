
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
});
</script>

<template>
  <div class="mainContainer">
    <img alt="Vue logo" class="logo" src="src\assets\logo.svg" width="125" height="125" />
    <h1>{{ msg }}</h1>
    <h5>Test project for testing and learn Vue</h5>
  </div>
</template>

<style>
.mainContainer{
  margin-bottom: 1rem;
  background-color: #eee;
  display: flex;
  flex-direction: row;
}
img{
  flex: 1;
  margin: 2rem;  
}
h1{
  text-align: center;
  flex: 2;
}
h5{
  flex: 1;
}
</style>

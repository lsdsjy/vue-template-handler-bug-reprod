<template>
  <div id="app" @click="
    $emit('update:a');
  ">
  </div>
</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
console.log(HelloWorld)
</script>

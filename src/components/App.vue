<template>
  <div>
    <header-component></header-component>
    <p class='blue'> this is app comp </p>
  </div>
</template>

<script>
 import Header from './Header.vue';

 export default {
  components: {
    'header-component': Header
  }
 }
</script>

<style>
.blue { color: blue; }
</style>

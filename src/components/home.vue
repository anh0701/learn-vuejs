<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script setup>
  import { defineProps } from 'vue';
  defineProps(['msg'])
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @import url(../styles/home.css);
</style>

<template>
  <home msg="hello world"></home>
</template>

<script>
import home from './components/home.vue';


export default {
  name: 'App',
  components: {
    home
}
}
</script>

<style>
  @import url('./styles/main.css');
</style>

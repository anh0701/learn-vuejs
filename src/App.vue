<template>
  <Menu></Menu>
  <Home msg="hello world"></Home>
</template>

<script>
import Home from './components/home.vue';
import Menu from './components/menu.vue';

export default {
  name: 'App',
  components: {
    Home,
    Menu
}
}
</script>

<style>
  @import url('./styles/main.css');
</style>

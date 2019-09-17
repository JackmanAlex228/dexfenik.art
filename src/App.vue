<template>
  <div id="app">
    <logo/>
    <temp/>
    <menu/>
  </div>
</template>
<script>
import logo from './components/logo.vue'
import temp from './components/temp.vue'
import menu from './components/menu.vue'

export default {
  name: 'app',
  components: {
    logo,
    temp,
    menu
  }
}
</script>

<style>
  img {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
</style>

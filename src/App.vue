<template>
  <div id="app">
    <logo/>
    <temp/>
  </div>
</template>
<script>
import logo from './components/logo.vue'
import temp from './components/temp.vue'

export default {
  name: 'app',
  components: {
    logo,
    temp,
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

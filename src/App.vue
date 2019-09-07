<template>
  <div id="app">
    <logo/>
    <temp/>
  </div>
</template>
<script>
import temp from './components/temp.vue'
import logo from './components/logo.vue'

export default {
  name: 'app',
  components: {
    logo,
    temp
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

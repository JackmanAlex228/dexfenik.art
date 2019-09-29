<template>
  <div id="app">
    <logo/>
    <h3 class="title">The Art Of DexFenik</h3>
    <b-container class="main-nav-btns">
      <b-row class="justify-content-md-center">
        <b-col md="auto"><b-button v-on:click="component='gallery'">Portfolio</b-button></b-col>
        <!-- <b-button v-on:click="component='characters'">Characters</b-button> -->
        <b-col md="auto"><b-button v-on:click="component='about'">About</b-button></b-col>
        <b-col md="auto"><b-button v-on:click="component='commissions'">Commissions</b-button></b-col>
        <b-col md="auto"><b-button v-on:click="component='contact'">Contact</b-button></b-col>
      </b-row>
      <b-row class="justify-content-md-center">
        <component v-bind:is="component"/>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import logo from './components/logo.vue'
import gallery from './components/gallery.vue'
// import characters from './components/characters.vue'
import about from './components/about.vue'
import commissions from './components/commissions.vue'
import contact from './components/contact.vue'

export default {
  name: 'app',
  components: {
    logo,
    gallery,
    // characters,
    about,
    commissions,
    contact
  },
  data() {
    return {
      component: 'gallery'
    }
  }
}
</script>

<style>
  .title {
    width: 100% !important;
  }
  img {
    display: inline-block;
  }
  #app {
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    text-align: center;
    color: #5D5D5D;
  }
  #app h3 {
    color: #FF6600;
  }
  #app p, h3, ol, ul {
    display: inline-block;
    text-align: center;
  }
  .main-nav-btns .btn {
    border: none;
    background: none;
    color: #5D5D5D;
  }
  .main-nav-btns .btn:hover {
    background: none;
    color: #FF6600;
  }
  .main-nav-btns .btn:active {
    background: none !important;
    color: #FF6600 !important;
  }
</style>
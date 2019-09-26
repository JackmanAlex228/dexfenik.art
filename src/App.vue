<template>
  <div id="app">
    <logo/>
    <div class="main-nav-btns">
      <b-button v-on:click="component='gallery'">Portfolio</b-button>
      <!-- <b-button v-on:click="component='characters'">Characters</b-button> -->
      <b-button v-on:click="component='about'">About</b-button>
      <b-button v-on:click="component='commissions'">Commissions</b-button>
      <b-button v-on:click="component='contact'">Contact</b-button>
    </div>
    <component v-bind:is="component"/>
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
  img {
    display: block;
    margin-left: auto;
    margin-right: auto;
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
    width: 70%;
    display: inline-block;
    text-align: center;
  }
  .main-nav-btns .btn {
    border: none;
    background: none;
    color: #5D5D5D;
    margin-left: 5px;
    margin-right: 5px;
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
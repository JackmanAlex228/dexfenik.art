<template>
  <div id="body">
    <!-- <img src="../assets/construct_dex.png" height="350px"> -->
    <h1>Oh...heh...hello there...</h1>
    <p>This is my official website. As you can see, there's a lot I need to work on.</p>
    <p>Let's go to my <a href="https://twitter.com/DexFenik">Twitter</a> or <a href="https://www.instagram.com/dexfenik/">Instagram</a> while we wait.</p>
  </div>
</template>

<script>
export default {
  name: 'temp',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #body {
    text-align: center;
    font-family: "Lucida Sans Unicode";
    color: #5d5d5d;
  }
</style>

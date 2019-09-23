<template>
    <div class="gallery-body">

        <div class="images">
            <img v-for="img in images" v-bind:src="img" :key="img"/>
        </div>

        <div class="links">
            <h5> Check out more at these places </h5>
            <a target="_blank" href="https://twitter.com/DexFenik"><img src="../assets/Old Icons/tw.jpg"></a>
            <a target="_blank" href="https://www.instagram.com/dexfenik/"><img src="../assets/Old Icons/in.jpg"></a>
            <a target="_blank" href="https://www.deviantart.com/dexfenik"><img src="../assets/Old Icons/da.jpg"></a>
            <a target="_blank" href="https://www.furaffinity.net/user/dexfenik/"><img src="../assets/Old Icons/fa.png"></a>
        </div>

        <!-- TURN THIS BACK ON LATER -->
        <!-- <div class="gallery-nav-btns">
            <b-button size="sm" v-on:click="component='artwork_gallery'">Artwork</b-button>
            <b-button size="sm" v-on:click="component='gifts_trades_gallery'">Gifts and Trades</b-button>
            <b-button size="sm" v-on:click="component='commissions_gallery'">Commissions</b-button>
            <b-button size="sm" v-on:click="component='sketches_gallery'">Sketches</b-button>
        </div>
        <component v-bind:is="component"/> -->
    </div>
</template>

<script>
// import artwork_gallery from './gallery-artwork.vue'
// import gifts_trades_gallery from './gallery-gifts-trades.vue'
// import commissions_gallery from './gallery-comms.vue'
// import sketches_gallery from './gallery-sketches.vue'

export default {
    name: 'gallery',
    // components: {
    //     artwork_gallery,
    //     gifts_trades_gallery,
    //     commissions_gallery,
    //     sketches_gallery
    // },
    data() {
        return {
            // component: 'artwork_gallery'
            images:[
                'https://d.facdn.net/art/dexfenik/1555297740/1555297740.dexfenik_dogbomb1.png',
                'https://d.facdn.net/art/dexfenik/1555297527/1555297527.dexfenik_shoba_ref.png',
                'https://d.facdn.net/art/dexfenik/1555297277/1555297277.dexfenik_woofy_ref.png',
                'https://d.facdn.net/art/dexfenik/1551733489/1551733489.dexfenik_fox_shapes.png',
                'https://d.facdn.net/art/dexfenik/1551733256/1551733256.dexfenik_willow_character_ref.png']
        }
    }
}
</script>

<style scoped>
    .gallery-body {
        text-align: center;
    }
    .gallery-body .links img {
        width: 100px;
        margin: 10px;
        display: inline;
        border-radius: 20px;
        transition: 0.10s linear;
        -webkit-transition: 0.10s linear;
        -moz-transition: 0.10s linear;
    }
    .gallery-body .links img:hover {
        filter: brightness(120%);
    }
    .gallery-body .images {
        display: auto;
        margin-left: auto;
        margin-right: auto;
        max-width: 75%;
    }
    .gallery-body .images img{
        width: 300px;
        margin: 10px;
        display: inline;
        border-radius: 10px;
    }
    .gallery-nav-btns {
        text-align: center;
    }
    .gallery-nav-btns .btn {
        border: none;
        background: none;
        color: #5D5D5D;
    }
    .gallery-nav-btns .btn:hover {
        background: none;
        color: #FF6600;
    }
    .gallery-nav-btns .btn:active {
        background: none !important;
        color: #FF6600 !important;
    }
</style>

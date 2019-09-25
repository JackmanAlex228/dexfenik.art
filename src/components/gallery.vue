<template>
    <div class="gallery-body">

        <div class="images">
            <img v-for="img in images" v-bind:src="img" :key="img"/>
        </div>

        <div class="links">
            <p> Check out more at these places </p>
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
                'https://d.facdn.net/art/dexfenik/1569278259/1569278259.dexfenik_tes_24__small_.png',
                'https://d.facdn.net/art/dexfenik/1569278134/1569278134.dexfenik_scarf_dex__small_.png',
                'https://d.facdn.net/art/dexfenik/1569278065/1569278065.dexfenik_bird_and_marten__small_.png',
                'https://d.facdn.net/art/dexfenik/1569277805/1569277805.dexfenik_rockness_dog__small_.png',
                'https://d.facdn.net/art/dexfenik/1569277682/1569277682.dexfenik_hexium__small_.png',
                'https://d.facdn.net/art/dexfenik/1569277594/1569277594.dexfenik_ringtail__small_.png',
                'https://d.facdn.net/art/dexfenik/1569276466/1569276466.dexfenik_woofy_and_lazy__small_.png',
                'https://d.facdn.net/art/dexfenik/1569276353/1569276353.dexfenik_bexis__small_.jpg',
                'https://d.facdn.net/art/dexfenik/1569276286/1569276286.dexfenik_crankycoon__small_.png',
                'https://d.facdn.net/art/dexfenik/1569276067/1569276067.dexfenik_aquiloark.png',
                'https://d.facdn.net/art/dexfenik/1569275891/1569275891.dexfenik_dex_sniffing_flower.png',
                'https://d.facdn.net/art/dexfenik/1569275319/1569275319.dexfenik_mattnyc816.png',
                'https://d.facdn.net/art/dexfenik/1569275241/1569275241.dexfenik_dax.png',
                'https://d.facdn.net/art/dexfenik/1555297740/1555297740.dexfenik_dogbomb1.png',
                'https://d.facdn.net/art/dexfenik/1555297527/1555297527.dexfenik_shoba_ref.png',
                'https://d.facdn.net/art/dexfenik/1555297277/1555297277.dexfenik_woofy_ref.png',
                'https://d.facdn.net/art/dexfenik/1551733489/1551733489.dexfenik_fox_shapes.png',
                'https://d.facdn.net/art/dexfenik/1551733256/1551733256.dexfenik_willow_character_ref.png',
                'https://d.facdn.net/art/dexfenik/1546544832/1546544832.dexfenik_shadowfang.png',
                'https://d.facdn.net/art/dexfenik/1546289128/1546289128.dexfenik_drunk_yeen.png',
                'https://d.facdn.net/art/dexfenik/1545606299/1545606299.dexfenik_pomorand19.png',
                'https://d.facdn.net/art/dexfenik/1545606139/1545606139.dexfenik_gator.png',
                'https://d.facdn.net/art/dexfenik/1544059579/1544059579.dexfenik_jibkodi.png',
                'https://d.facdn.net/art/dexfenik/1544059329/1544059329.dexfenik_fall_dex_icon_2018.png',
                'https://d.facdn.net/art/dexfenik/1544059182/1544059182.dexfenik_robert_roberting.png',
                'https://d.facdn.net/art/dexfenik/1544058945/1544058945.dexfenik_princes_of_the_universe.png',
                'https://d.facdn.net/art/dexfenik/1544058148/1544058148.dexfenik_bluesugar__edited_.png',
                'https://d.facdn.net/art/dexfenik/1544057685/1544057685.dexfenik_lawer_fox_1.png',
                'https://d.facdn.net/art/dexfenik/1544057087/1544057087.dexfenik_cute_dex.png',
                'https://d.facdn.net/art/dexfenik/1544056619/1544056619.dexfenik_goldie.png',
                'https://d.facdn.net/art/dexfenik/1544056491/1544056491.dexfenik_misfit.png',
                'https://d.facdn.net/art/dexfenik/1544056187/1544056187.dexfenik_foxes.png',
                'https://d.facdn.net/art/dexfenik/1528132789/1528132789.dexfenik_jaders_gonna_jate.png',
                'https://d.facdn.net/art/dexfenik/1528132704/1528132704.dexfenik_tyles.png',
                'https://d.facdn.net/art/dexfenik/1528132136/1528132136.dexfenik_strat.png',
                'https://d.facdn.net/art/dexfenik/1528132053/1528132053.dexfenik_myles.png',
                'https://d.facdn.net/art/dexfenik/1528131862/1528131862.dexfenik_dawson_and_seven.png',
                'https://d.facdn.net/art/dexfenik/1528131764/1528131764.dexfenik_hugging.png',
                'https://d.facdn.net/art/dexfenik/1514876393/1514876393.dexfenik_konnor.png',
                'https://d.facdn.net/art/dexfenik/1511038393/1511038393.dexfenik_blitz__background_.png',
                'https://d.facdn.net/art/dexfenik/1514875871/1514875871.dexfenik_rusell.png',
                'https://d.facdn.net/art/dexfenik/1514875674/1514875674.dexfenik_dattas_and_mika.png',
                'https://d.facdn.net/art/dexfenik/1510107367/1510107367.dexfenik_fall_dex_badge.png',
                'https://d.facdn.net/art/dexfenik/1500261040/1500261040.dexfenik_banditt.png',
                'https://d.facdn.net/art/dexfenik/1482797507/1482797507.dexfenik_charlie_tinn.png',
                'https://d.facdn.net/art/dexfenik/1490408963/1490408963.dexfenik_compose.png']
        }
    }
}
</script>

<style scoped>
    .gallery-body {
        text-align: center;
    }
    .gallery-body .links img {
        width: 75px;
        margin-left: 5px;
        margin-right: 5px;
        margin-bottom: 25px;
        display: inline;
        border-radius: 10px;
        transition: 0.10s linear;
        -webkit-transition: 0.10s linear;
        -moz-transition: 0.10s linear;
    }
    .gallery-body .links img:hover {
        filter: brightness(120%);
    }
    .gallery-body .images {
        margin-top: 25px;
        margin-bottom: 25px;
        display: auto;
        margin-left: auto;
        margin-right: auto;
        max-width: 75%;
    }
    .gallery-body .images img{
        height: 300px;
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

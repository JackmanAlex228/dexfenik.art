<template>
    <div class="gallery-body">
        <div class="gallery-nav-btns">
            <b-button size="sm" v-on:click="component='artwork_gallery'">Artwork</b-button>
            <b-button size="sm" v-on:click="component='gifts_trades_gallery'">Gifts and Trades</b-button>
            <b-button size="sm" v-on:click="component='commissions_gallery'">Commissions</b-button>
            <b-button size="sm" v-on:click="component='sketches_gallery'">Sketches</b-button>
        </div>
        <component v-bind:is="component"/>
    </div>
</template>

<script>
import artwork_gallery from './gallery-artwork.vue'
import gifts_trades_gallery from './gallery-gifts-trades.vue'
import commissions_gallery from './gallery-comms.vue'
import sketches_gallery from './gallery-sketches.vue'

export default {
    name: 'gallery',
    components: {
        artwork_gallery,
        gifts_trades_gallery,
        commissions_gallery,
        sketches_gallery
    },
    data() {
        return {
            component: 'artwork_gallery'
        }
    }
}
</script>

<style scoped>
    .gallery-body {
        text-align: center;
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

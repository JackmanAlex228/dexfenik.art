<template>
    <div class="body">
        <b-container class="prices">

            <h3>Flat Illustrations</h3>
            <p>$25 | Add Character +$15 | Add Background +$20</p>
            <b-container class="examples">
                <b-row class="justify-content-lg-center">
                    <b-col lg="8"><img v-for="img in flatIllustrations" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <h3>Shaded Illustrations</h3>
            <p>$30 | Add Character +$20 | Add Background +$25</p>
            <b-container class="examples">
                <b-row class="justify-content-lg-center">
                    <b-col lg="8"><img v-for="img in shadedIllustrations" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <h3>Flat Icons</h3>
            <p>$15 | Add Character +$10 | Add Background +$10</p>
            <b-container class="examples">
                <b-row class="justify-content-lg-center">
                    <b-col lg="8"><img v-for="img in flatIcons" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <h3>Shaded Icons</h3>
            <p>$20 | Add Character +$15 | Add Background +$15</p>
            
            <h3>Badges</h3>
            <p>Add Nameplate To Artwork +$5 | Con Pickup +$5 | Shipping +$7</p>
            <b-container class="examples">
                <b-row class="justify-content-lg-center">
                    <b-col lg="8"><img v-for="img in badges" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <h3>Medium Character References</h3>
            <p>Colored $40 | Linart-Only $30</p>
            
            <h3>Large Character References</h3>
            <p>Colored $60 | Linart-Only $45</p>
            <b-container class="examples">
                <b-row class="justify-content-lg-center">
                    <b-col lg="8"><img v-for="img in largeRefs" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
        </b-container>
    </div>
</template>

<script>
export default {
    name: 'comm_prices',
    data() {
        return {
            flatIllustrations:[
                'https://d.facdn.net/art/dexfenik/1569277594/1569277594.dexfenik_ringtail__small_.png',
                'https://d.facdn.net/art/dexfenik/1569276353/1569276353.dexfenik_bexis__small_.jpg',
                'https://d.facdn.net/art/dexfenik/1569275241/1569275241.dexfenik_dax.png',
                'https://d.facdn.net/art/dexfenik/1546544832/1546544832.dexfenik_shadowfang.png'
            ],
            shadedIllustrations:[
                'https://d.facdn.net/art/dexfenik/1569277805/1569277805.dexfenik_rockness_dog__small_.png',
                'https://d.facdn.net/art/dexfenik/1569277682/1569277682.dexfenik_hexium__small_.png',
                'https://d.facdn.net/art/dexfenik/1528132136/1528132136.dexfenik_strat.png',
                'https://d.facdn.net/art/dexfenik/1528131764/1528131764.dexfenik_hugging.png'
            ],
            flatIcons:[
                'https://d.facdn.net/art/dexfenik/1544059329/1544059329.dexfenik_fall_dex_icon_2018.png',
                'https://d.facdn.net/art/dexfenik/1551733367/1551733367.dexfenik_manora.png'
            ],
            shadedIcons:[
                '',
                ''
            ],
            badges:[
                'https://d.facdn.net/art/dexfenik/1511038393/1511038393.dexfenik_blitz__background_.png',
                'https://d.facdn.net/art/dexfenik/1514875781/1514875781.dexfenik_kahuna_badge.png',
                'https://d.facdn.net/art/dexfenik/1544057442/1544057442.dexfenik_frippo.png',
                'https://d.facdn.net/art/dexfenik/1510107367/1510107367.dexfenik_fall_dex_badge.png'
            ],
            mediumRefs:[
                '',
                ''
            ],
            largeRefs:[
                'https://d.facdn.net/art/dexfenik/1551733256/1551733256.dexfenik_willow_character_ref.png',
                'https://d.facdn.net/art/dexfenik/1555297277/1555297277.dexfenik_woofy_ref.png',
                'https://d.facdn.net/art/dexfenik/1555297527/1555297527.dexfenik_shoba_ref.png',
                'https://d.facdn.net/art/dexfenik/1569276286/1569276286.dexfenik_crankycoon__small_.png'
            ]
        }
    }
}
</script>

<style scoped>
    .body {
        margin-top: 25px;
        margin-bottom: 25px;
    }
    .body h3, p {
        text-align: center !important;

    }
    .body .examples {
        width: 100% !important;
    }
    .body .examples img {
        width: 300px;
        margin: 10px;
        display: inline-block;
        border-radius: 10px;
    }
</style>

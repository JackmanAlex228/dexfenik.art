<template>
    <div class="body">
        <b-container class="prices">

            <br><h3>Flat Illustrations</h3><br>
            <p>$25 | Add Character +$15 | Add Background +$20</p>
            <b-container class="examples">
                <b-row class="justify-content-center">
                    <b-col sx="12" sm="12" md="12" lg="8" xl="8"><img v-for="img in flatIllustrations" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <br><h3>Shaded Illustrations</h3><br>
            <p>$30 | Add Character +$20 | Add Background +$25</p>
            <b-container class="examples">
                <b-row class="justify-content-center">
                    <b-col sx="12" sm="12" md="12" lg="8" xl="8"><img v-for="img in shadedIllustrations" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <br><h3>Flat Icons</h3><br>
            <p>$15 | Add Character +$10 | Add Background +$10</p>
            <b-container class="examples">
                <b-row class="justify-content-center">
                    <b-col sx="12" sm="12" md="12" lg="8" xl="8"><img v-for="img in flatIcons" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <br><h3>Shaded Icons</h3><br>
            <p>$20 | Add Character +$15 | Add Background +$15</p>
            
            <br><h3>Badges</h3><br>
            <p>Add Nameplate To Artwork +$5 | Con Pickup +$5 | Shipping +$7</p>
            <b-container class="examples">
                <b-row class="justify-content-center">
                    <b-col sx="12" sm="12" md="12" lg="8" xl="8"><img v-for="img in badges" v-bind:src="img" :key="img"/></b-col>
                </b-row>
            </b-container>
            
            <br><h3>Medium Character References</h3><br>
            <p>Colored $40 | Linart-Only $30</p>
            
            <br><h3>Large Character References</h3><br>
            <p>Colored $60 | Linart-Only $45</p>
            <b-container class="examples">
                <b-row class="justify-content-center">
                    <b-col sx="12" sm="12" md="12" lg="8" xl="8"><img v-for="img in largeRefs" v-bind:src="img" :key="img"/></b-col>
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
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-ill-1.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-ill-2.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-ill-3.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-ill-4.jpg'
            ],
            shadedIllustrations:[
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/shaded-ill-1.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/shaded-ill-2.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/shaded-ill-3.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/shaded-ill-4.jpg'
            ],
            flatIcons:[
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-icon-1.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/flat-icon-2.jpg'
            ],
            shadedIcons:[
                '',
                ''
            ],
            badges:[
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/badge-1.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/badge-2.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/badge-3.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/badge-4.jpg'
            ],
            mediumRefs:[
                '',
                ''
            ],
            largeRefs:[
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/large-ref-1.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/large-ref-2.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/large-ref-3.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/comm-examples/large-ref-4.jpg'
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
        max-width: 100%;
    }
</style>

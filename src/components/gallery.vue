<template>
    <div class="gallery-body">

        <b-container class="images">
            <b-row>
                <b-col sm md="auto"><img v-for="img in images" v-bind:src="img" :key="img"/></b-col>
            </b-row>
        </b-container>

        <div class="links">
            <a target="_blank" href="https://twitter.com/DexFenik"><img src="../assets/Old Icons/tw.jpg"></a>
            <a target="_blank" href="https://www.instagram.com/dexfenik/"><img src="../assets/Old Icons/in.jpg"></a>
            <a target="_blank" href="https://www.deviantart.com/dexfenik"><img src="../assets/Old Icons/da.jpg"></a>
            <a target="_blank" href="https://www.furaffinity.net/user/dexfenik/"><img src="../assets/Old Icons/fa.png"></a>
        </div>
    </div>
</template>

<script>

export default {
    name: 'gallery',
    data() {
        return {
            // component: 'artwork_gallery'
            images:[
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/43.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/42.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/41.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/40.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/39.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/38.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/37.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/36.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/35.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/34.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/33.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/32.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/31.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/30.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/29.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/28.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/27.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/26.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/25.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/24.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/23.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/22.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/21.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/20.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/19.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/18.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/17.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/16.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/15.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/14.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/13.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/12.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/11.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/10.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/9.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/8.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/7.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/6.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/5.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/4.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/3.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/2.jpg',
                'https://raw.githubusercontent.com/JackmanAlex228/dexfenik.art/master/src/assets/portfolio-thumb/1.jpg',
                ]
        }
    }
}
</script>

<style scoped>
    .gallery-body {
        text-align: center;
        margin-bottom: 25px;
    }
    .gallery-body .links {
        width: 100%;
    }
    .gallery-body .links p {
        text-align: center !important;
        width: 100% !important;
    }
    .gallery-body .links img {
        width: 75px;
        margin-left: 5px;
        margin-right: 5px;
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
        width: 100% !important;
    }
    .gallery-body .images img {
        width: 300px;
        border-radius: 10px;
        margin: 10px;
    }
    .gallery-nav-btns {
        text-align: center;
    }
    .gallery-nav-btns .btn {
        border: none;
        background: none;
        color: #5D5D5D;
    }
    .gallery-nav-btns .btn:hover, .btn:active {
        background: none;
        color: #FF6600;
    }
</style>

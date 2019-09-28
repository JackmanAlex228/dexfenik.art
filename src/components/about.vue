<template>
    <b-container class="about-body">

        <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="10" lg="8" xl="8">
                <h3>Hello</h3>
                <p>My name is DexFenik (Dex-Fee-Nick), but you can just call me Dex.</p>
                <p>I am a digital artist by hobby and a software engineer by school and profession.
                    I started doing graphic design in high school in 2010, focusing on Adobe Photoshop and Illustrator. 
                    In my freshman year of college in 2014, I began to draw freehand, mainly animals and nature.</p>
                <p>After less than a year of practice, moving from sketchpad to digital, 
                    I began taking commissions in Fall 2014 from a local furry group on Facebook. While I've produced 
                    more art over the years, I've gained many friends in the furry community as well, traveling to 
                    many cons and experiencing countless memories.</p>
                <p>For my whole life, I've always had an affinity for anthropomorphic animals, from films and 
                    shows such as Lion King and Dragon Ball. After discovering the art in 2013, persuing the 
                    community in 2014, and getting a fursuit in 2017, I've been living in this community through art, 
                    costplays, friendships, and other adventures. To this day, I draw character-focused artwork, open for 
                    commissions on occasion, and travel to cons so I can goof around dressed as an anxious fox. </p>
            </b-col>
        </b-row>

        <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="10" lg="8" xl="8">
                <h3>How I Learn</h3>
                <p>Practice every day, or at least as much as I can, starting from a sketch book. I also learn 
                    from my inspirations, watching them progress, viewing their tutorials, viewing the art they love, 
                    and aspiring to be like them. And most importantly, I enjoy it.</p>
            </b-col>
        </b-row>

        <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="10" lg="8" xl="8">
                <h3>What I Used</h3>
                <p>In my graphic design days, I used a Wacom Intuos Pro 4, which was given to me for Christmas 
                    in 2010. My brother and I also shared a copy of the Adobe CS5 Production Premium. </p>
                <p>When I started drawing in 2014, I simply bought a sketch book and drew what I felt like drawing every day. 
                    Eventually I went back to Photoshop and my Intuos 4 once I got back to my computer one summer. 
                    Later in the fall, I used Paint Tool Sai (given by a friend) for the lineart and color 
                    and Photoshop for the effects and touch-ups.</p>
                <p>In Spring of 2016, for my junior college graduation I was given by my family a Surface Pro 4, which I
                    used with Clip Studio Paint until Summer 2019.</p>
                <p>Today I use an iPad Pro (11" 2018) with Apple Pencil and ProCreate.<p/>
            </b-col>
        </b-row>

        <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="10" lg="8" xl="8">
                <h3>My Inspirations</h3>
                <div class="inspirations-btns">
                    <b-button class="Thanshuhai"    a href="https://twitter.com/thanshuhai"         target=_blank>Thanshuhai</b-button>
                    <b-button class="Denucard"      a href="https://twitter.com/Denucard"           target=_blank>Denucard</b-button>
                    <b-button class="TaniDaReal"    a href="https://twitter.com/Schnolf"            target=_blank>TaniDaReal</b-button>
                    <b-button class="Kenket"        a href="https://twitter.com/tessgarman"         target=_blank>Kenket</b-button>
                    <b-button class="Tirrel"        a href="https://twitter.com/Tirrelous"          target=_blank>Tirrel</b-button>
                    <b-button class="Ritwells"      a href="https://twitter.com/ritwells"           target=_blank>Ritwells</b-button>
                    <b-button class="Tsebresos"     a href="https://www.instagram.com/tsebresos/"   target=_blank>Tsebresos</b-button>
                    <b-button class="Kour"          a href="https://twitter.com/ArtKour"            target=_blank>Kour</b-button>
                    <b-button class="JibKodi"       a href="https://twitter.com/JibKodi"            target=_blank>JibKodi</b-button>
                    <b-button class="Fuel"          a href="https://twitter.com/foxefuel"           target=_blank>Fuel</b-button>
                    <b-button class="NowAndLater"   a href="https://twitter.com/cinnamonsp0ts"      target=_blank>NowAndLater</b-button>
                </div>
            </b-col>
        </b-row>

    </b-container>
</template>

<script>
export default {
    name: 'about'
}
</script>

<style scoped>
    .about-body {
        margin-top: 25px;
        width: 100% !important;
    }
    .about-body p, h3 {
        width: 100% !important;
        display: inline-block;
    }
    .about-body .inspirations-btns {
        display: inline-block;
        margin-bottom: 25px;
    }
    .inspirations-btns .btn {
        border: none;
        background: none;
        color: #5D5D5D;
    }
    .inspirations-btns .btn:hover {
        background: none;
        color: #FF6600;
    }
    .inspirations-btns .btn:active {
        background: none !important;
        border: none !important;
        color: #FF6600 !important;
    }
    .inspirations-btns .Thanshuhai:hover    { color: rgb(46, 219, 219); }
    .inspirations-btns .Denucard:hover      { color: rgb(243, 187, 46); }
    .inspirations-btns .TaniDaReal:hover    { color: rgb(80, 148, 148); }
    .inspirations-btns .Kenket:hover        { color: rgb(142, 197, 48); }
    .inspirations-btns .Tirrel:hover        { color: rgb(209, 105, 8); }
    .inspirations-btns .Ritwells:hover      { color: orange; }
    .inspirations-btns .Tsebresos:hover     { color: plum; }
    .inspirations-btns .Kour:hover          { color: rgb(255, 0, 140); }
    .inspirations-btns .JibKodi:hover       { color: rgb(13, 150, 43); }
    .inspirations-btns .Fuel:hover          { color: rgb(4, 212, 132); }
    .inspirations-btns .NowAndLater:hover   { color: red; }
</style>
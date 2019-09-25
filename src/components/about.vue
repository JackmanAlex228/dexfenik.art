<template>
    <div class="body">

        <h3>Hello</h3>
        <p>My name is DexFenik (Dex-Fee-Nick), but you can just call me Dex.</p>
        <p>I am a digital artist by hobby and a software engineer by school and profession.
            I started doing graphic design in high school in 2010, focusing on Adobe Photoshop and Illustrator.
            At the time I focused mainly on photo editing and designs, however, it won't be until my college
            freshman year in 2014 that I began to draw freehand, mainly animals and nature.</p>
        <p>After less than a year of practice, as well as graduating from the sketch pad to digital, 
            I began taking commissions in Fall 2014 from a local furry group on Facebook. While I've produced 
            more art over the years, I've gained many friends in the furry community as well, traveling to 
            many cons and experiencing countless memories.</p>
        <p>For my whole life, I've always had an affinity for anthropomorphic animals, from films and 
            shows such as Lion King and Dragon Ball. After discovering the art in 2013, persuing the 
            community in 2014, and getting a fursuit in 2017, I've been an living in this community through art, 
            costplays, friendships, and other adventures. To this day, I draw character-focused artwork, open for 
            commissions on occasion, and travel to cons so I can dress as an anxious fox on the side. </p>

        <h3>How I Learned</h3>
        <p>I practiced every day, or at least as much as I can, starting from a sketch book. I also learned 
            from my inspirations, watching them progress, viewing their tutorials, viewing the art they love, 
            and so on. And most importantly, I enjoyed it, and I enjoyed others enjoying it.</p>

        <h3>What I Used</h3>
        <p>In my graphic design days, I used an Intuos Pro 4, which was given to me for Christmas 
            in 2010. My brother and I also shared a copy of the Adobe CS5 Production Premium. </p>
        <p>When I started drawing in 2014, I simply bought a sketch book and drew what I felt like every day. 
            Eventually I went back to Photoshop and my Intuos 4 once I got back to my computer one summer. 
            Later in the fall, I used Paint Tool Sai (given by a friend) for the lineart and color 
            and Photoshop for the effects and touch-ups.</p>
        <p>In Spring of 2016, for my junior college graduation I was given by my family a Surface Pro 4, which I
            used with Clip Studio Paint until Summer 2019.</p>
        <p>Today I use an iPad Pro (11" 2018) with Apple Pencil and ProCreate.<p/>

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
    </div>
</template>

<script>
export default {
    name: 'about'
}
</script>

<style scoped>
    .body {
        margin-top: 25px;
    }
    .body p {
        width: 70%;
        display: inline-block;
        text-align: left;
    }
    .body .inspirations-btns {
        width: 70%;
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
    .inspirations-btns .Thanshuhai:hover    { color: cyan; }
    .inspirations-btns .Denucard:hover      { color: darkgoldenrod; }
    .inspirations-btns .TaniDaReal:hover    { color: darkslategray; }
    .inspirations-btns .Kenket:hover        { color: darkolivegreen; }
    .inspirations-btns .Tirrel:hover        { color: brown; }
    .inspirations-btns .Ritwells:hover      { color: orange; }
    .inspirations-btns .Tsebresos:hover     { color: plum; }
    .inspirations-btns .Kour:hover          { color: blue; }
    .inspirations-btns .JibKodi:hover       { color: lawngreen; }
    .inspirations-btns .Fuel:hover          { color: orange; }
    .inspirations-btns .NowAndLater:hover   { color: red; }
</style>
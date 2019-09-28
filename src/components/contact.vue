<template>
    <b-container class="contact-body">
        <b-row class="justify-content-center">
            <b-col xm="12" sm="12" md="12" lg="8" xl="8">
                <h3>Email</h3>
                <p>dexfenikfox@gmail.com</p>
            </b-col>
        </b-row> 
        <b-row class="justify-content-center">
            <b-col xm="12" sm="12" md="12" lg="8" xl="8">
                <h3>Other ways you can contact me</h3>
                <p>Telegram, Twitter, Instagram, FurAffinity, and DeviantArt DMs. I'm @DexFenik on all of these.</p>
            </b-col>
        </b-row> 

        <b-row class="justify-content-center">
            <b-col xm="12" sm="12" md="12" lg="8" xl="8">
                <h3>There are no stupid questions</h3>
                <p>Please feel free ask me anything on <a href="https://curiouscat.me/DexFenik" target="_blank">CuriousCat</a>.</p>
            </b-col>
        </b-row> 

        <b-row class="justify-content-center">
            <b-col xm="12" sm="12" md="12" lg="8" xl="8">
                <h3>What NOT to do when contacting me</h3>
                <!-- <ul> -->
                    <p>Send spam.</p>
                    <p>Role play or ask to role play.</p>
                    <p>Send one-worded effortless messages such as "hey" or "hi".</p>
                    <p>Harass, threaten, or generally be creepy.</p>
                    <p>Send unsolicited explicit content.</p>
                    <p>Ask for validation through self-loathing or other forms of emotional manipulation.</p>
                    <p>Attempt to figure out my personal life.</p>
                    <p>Attempt to pursue friendships with me directly.</p>
                <!-- </ul> -->
            </b-col>
        </b-row> 
    </b-container>
</template>

<script>
export default {
    name: 'contact'
}
</script>

<style scoped>
    .contact-body {
        margin-top: 25px;
        margin-bottom: 25px;
        width: 100% !important;
    }
    .contact-body h3, p {
        text-align: left !important;
        width: 100% !important;
        display: inpne-block;
    }
    .contact-body a {
        text-decoration: underline;
        color: #5D5D5D;
    }
    .contact-body a:hover {
        color: #FF6600;
    }
</style>
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
                <p>Twitter, Instagram, FurAffinity, and DeviantArt. I'm DexFenik on all of these.</p>
            </b-col>
        </b-row> 

        <b-row class="justify-content-center">
            <b-col xm="12" sm="12" md="12" lg="8" xl="8">
                <h3>What NOT to do when contacting me</h3>
                <p>Be rude or overall immature.</p>
                <p>Fish for complements through self-loathing or other forms of emotional manipulation.</p>
                <p>Attempt to figure out my personal life.</p>
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
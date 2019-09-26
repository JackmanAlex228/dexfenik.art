<template>
    <div class="commissions-body">
        <div class="status">
            <h3>Commissions are currently <h3 class="closed"><b>CLOSED</b></h3></h3>
            <br>
            <p>I might do trades if you ask, I do not do requests,
                and if you would like to know when I open, watch out for 
                commission annoucements on my Twitter: @DexFenik.</p>
        </div>
        <div class="commissions-nav-btns">
            <b-button size="sm" v-on:click="component='comm_prices'">Prices</b-button>
            <b-button size="sm" v-on:click="component='comm_tos'">Terms of Service</b-button>
            <b-button size="sm" v-on:click="component='comm_queue'">Queue</b-button>
        </div>
        <component v-bind:is="component"/>
    </div>
</template>

<script>
import comm_prices from './comm-prices.vue'
import comm_tos from './comm-tos.vue'
import comm_queue from './comm-queue.vue'

export default {
    name: 'commissions',
    components: {
        comm_prices,
        comm_tos,
        comm_queue
    },
    data() {
        return {
            component: 'comm_prices'
        }
    }
}
</script>

<style scoped>
    .commissions-body {
        text-align: center;
    }
    .commissions-nav-btns {
        text-align: center;
    }
    .commissions-nav-btns .btn {
        border: none;
        background: none;
        color: #5D5D5D;
    }
    .commissions-nav-btns .btn:hover {
        background: none;
        color: #FF6600;
    }
    .commissions-nav-btns .btn:active {
        background: none !important;
        color: #FF6600 !important;
    }
    .commissions-body .status {
        width: 70%;
        display:inline-block;
        border-radius: 10px;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        margin: 25px;
    }
    .commissions-body .status p {
        width: 70%;
        display: inline-block;
        text-align: center !important;
    }
    .commissions-body .status h3 {
        text-align: center !important;
        color: #5D5D5D !important;
        display: inline-block;
        margin: 5px;
    }
    .commissions-body .status h3 .closed {
        color: red !important;
    }
    .commissions-body .status h3 .open {
        color: green !important;
    }
    .commissions-body .status h3 .inprogress {
        color: green !important;
        animation: blinker 1.5s linear infinite;
    }
    .commissions-body .status h3 .onhold {
        color: gold !important;
    }
    @keyframes blinker {
        50% { opacity: 0; } 
    }
</style>
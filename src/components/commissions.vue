<template>
    <div class="commissions-body">
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
</style>
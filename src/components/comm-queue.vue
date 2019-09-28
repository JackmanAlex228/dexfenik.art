<template>
    <b-container class="queue-body">
        <!-- <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="10" lg="8" xl="8"> -->
                <b-table class="table" :items="items" :fields="fields" caption-top borderless>
                    <template v-slot:table-caption>PayPal Address: dexfenikfox@gmail.com</template>
                </b-table>
            <!-- </b-col>
        </b-row> -->
    </b-container>
</template>

<script>
export default {
    name: 'comm_queue',
    data() {
      return {
        fields: ['queue_number', 'username', 'commission_type', 'payment_status'],
        items: [
          { queue_number: 1, username: '-', commission_type: '-', payment_status: '-' },
          { queue_number: 2, username: '-', commission_type: '-', payment_status: '-' },
          { queue_number: 3, username: '-', commission_type: '-', payment_status: '-' },
          { queue_number: 4, username: '-', commission_type: '-', payment_status: '-' },
          { queue_number: 5, username: '-', commission_type: '-', payment_status: '-' },
        ]
      }
    }
}
</script>

<style scoped>
    .queue-body {
        margin-top: 25px;
        margin-bottom: 25px;
        width: 100% !important;
    }
    .queue-body .table {
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        color: #5D5D5D;
        /* display: inline-block; */
        width: 100% !important;
    }
</style>

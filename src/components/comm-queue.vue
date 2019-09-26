<template>
    <div class="body">
        <div>
            <b-table class="table" :items="items" :fields="fields" caption-top borderless>
                <template v-slot:table-caption>PayPal Address: dexfenikfox@gmail.com</template>
            </b-table>
        </div>
    </div>
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
    .body {
        width: 70%;
        display: inline-block;
        margin-top: 25px;
        margin-bottom: 25px;
        text-align: center;
    }
    .body .table {
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        color: #5D5D5D;
    }
</style>

<template>
    <b-container class="queue-body">
        <b-row class="justify-content-center">
            <b-col sx="12" sm="12" md="12" lg="12" xl="12">
                <b-table :items="items" :fields="fields" caption-top borderless>
                    <template v-slot:table-caption>PayPal Address: dexfenikfox@gmail.com</template>
                </b-table>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    name: 'comm_queue',
    data() {
      return {
        fields: ['number', 'commission', 'progress'],
        items: [
          { number: 1, commission: '-', progress: '-' },
          { number: 2, commission: '-', progress: '-' },
          { number: 3, commission: '-', progress: '-' },
          { number: 4, commission: '-', progress: '-' },
          { number: 5, commission: '-', progress: '-' },
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
        display: inline-block;
        width: 100% !important;
    }
</style>

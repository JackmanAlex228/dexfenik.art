<template>
    <div id="body">
        <div>
            <b-button>Gallery</b-button>
            <b-button>Characters</b-button>
            <b-button>About</b-button>
            <b-button>Commissions</b-button>
            <b-button>Contact</b-button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'temp',
    props: {
        msg: String
    }
}
</script>

<style scoped>
    .btn {
        color: #5D5D5D;
        border: none;
        background: none;
        height: auto;
        margin-left: 5px;
        margin-right: 5px;
    }
    .btn:hover {
        background: none;
        color: #FF6600;
    }
    .btn:active {
        background: none !important;
        color: #FF6600 !important;
    }
    #body {
        text-align: center;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    }
</style>

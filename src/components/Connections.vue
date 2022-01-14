<template>
<div class="connections">
    <div class="container down">
        <ul>
            <ConnectionsType
                v-for="(connection_type, index) in connections_type"
                :key="index"
                :src="connection_type.surce"
                :alt="connection_type.alt"
                :title="connection_type.title" 
            />
        </ul>
    </div>
</div>
</template>

<script>
import ConnectionsType from "./ConnectionsType.vue"

export default {
    name: 'Connections',
    components: {
        ConnectionsType,
    },
     data () {  //funzione che restituisce object
        return {
            connections_type: [
                {
                    "surce": "../asset/img/buy-comics-digital-comics.png",
                    "alt": "buy-comics-digital-comics.png",
                    "title": "DIGITAL COMICS"
                },
                {
                    "surce": "../assets/img/buy-comics-merchandise.png",
                    "alt": "buy-comics-merchandise.png",
                    "title": "DC-MERCHANDISE" 
                },
                {
                    "surce": "../assets/img/buy-comics-subscriptions.png",
                    "alt": "buy-comics-subscriptions.png",
                    "title": "SUBSCRIPTION" 
                },
                {
                    "surce": "../assets/img/buy-comics-shop-locator.png",
                    "alt": "buy-comics-shop-locator.png",
                    "title": "COMIC SHOP LOCATOR" 
                },
                {
                    "surce": "../assets/img/buy-dc-power-visa.svg",
                    "alt": "buy-dc-power-visa.svg.png",
                    "title": "DC POWER-VISA" 
                }
            ]
        }
    },
    created () {
        console.log('created');
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_connections.scss";
.connections {
    width: 100%;
    background-color: blue;
    @include down (center, none);
}
</style>
<template>
<div class="connections">
    <div class="container down">
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital-comics">
                <span>DIGITAL COMICS</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="buy-comics-merchandise">
                <span>DC MERCHANDISE</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="buy-comics-subscriptions">
                <span>SUBSCIPTION</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="buy-comics-shop-locator">
                <span>COMIC SHOP LOCATOR</span>
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="buy-dc-power-vis">
                <span>DC POWER VISA</span>
            </li>
        </ul>
    </div>
</div>
</template>

<script>
export default {
    name: 'Connections',
     data () {  //funzione che restituisce object
        return {
    
        }
    },
    created () {
        console.log('created');
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
.connections {
    width: 100%;
    background-color: blue;
    .down {
        ul {
            display: flex;
            flex-direction: row;
            justify-content: center;
            width: 100%;
            list-style: none;
            padding: 3em;
            li {
                display: flex;
                align-items: center;
                img {
                    width: calc(100% / 5);
                }
                span {
                    color: white;
                    font-size: 0.8em;
                    font-weight: bold;
                    margin-left: 0.5em;
                }
            }
        }
    }
}
</style>
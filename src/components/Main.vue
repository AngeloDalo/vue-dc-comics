<template>
    <main>
        <div class="container up">
            <p>--> Content goes here </p>
        </div>
        <div class="container down">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCIPTION</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </li>
            </ul>
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main',
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
main {
    padding-top: 2em;
    background-color: black;
    .container {
        color: white;
        padding-bottom: 1em;
        p {
            font-size: 2em;
        }
    }
    .down {
        width: 100%;
        background-color: blue;
        ul {
            display: flex;
            width: 80%;
            margin: auto;
            list-style: none;
            padding: 3em;
            li {
                display: flex;
                align-items: center;
                img {
                    width: calc(100% / 5);
                }
                span {
                    font-size: 0.8em;
                    font-weight: bold;
                    margin-left: 0.5em;
                }
            }
        }
    }
}
</style>
<template>
    <header>
        <div class="container">
            <div class="image">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
     data () {  //funzione che restituisce object
        return {
            title: "Lorem Ipsum"
        }
    },
    created () {
        console.log('created');
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
.container {
    display: flex;
    align-items: center;
    height: 107px;
    .image {
        width: 20%;
    }
    ul {
        width: 80%;
        height: 100%;
        display: flex;
        justify-content: flex-end;
        flex-wrap: wrap;
        list-style: none;
            li {
                line-height: 5em;
                display: block;
                padding: 0.8em;
                height: 100%;
                a {
                    font-weight: bold;
                    font-size: 0.8em;
                    display: block;
                    text-decoration: none;
                    color: black;
                }
                &:hover,
                &:active {
                    border-bottom: 5px solid $heavenlyDC;
                }   
            }
    }   
}
</style>
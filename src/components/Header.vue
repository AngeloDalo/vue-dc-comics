<template>
    <header>
        <div class="container">
            <div class="image">
                <img src="../assets/img/dc-logo.png" alt="dc-logo">
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
    
        }
    },
    created () {
        console.log('created');
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
@import "../assets/scss/partials/_header.scss";
.container {
    @include base-scss (107px, 1143px, center);
    @include image (20%);
    @include list(flex-end, none, bold, none);   
}
</style>
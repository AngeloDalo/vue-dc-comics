<template>
    <div class="contact">
        <div class="container">
            <button>SIGN-UP NOW!</button>
            <ul>
                <li>FOLLOW US</li>
                <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook-logo"></a></li>
                <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter-logo"></a></li>
                <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube-logo"></a></li>
                <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest-logo"></a></li>
                <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope-logo"></a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Contact',
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
@import "../assets/scss/partials/_contact.scss";
.contact {
    width: 100%;
    background-color: $greyDC;
    padding-top: 2em;
    padding-bottom: 2em;
    @include container;
}
</style>

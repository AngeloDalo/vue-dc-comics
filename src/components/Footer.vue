<template>
    <footer>
        <img src="../assets/img/dc-logo-bg.png" alt="dc-logo">
        <div class="container">
            <div class="link-dc-shop">
                <ul>
                    <li>DC COMICS</li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <ul>
                    <li>SHOP</li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="link-dc">
                <ul>
                    <li>DC</li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Adversiting</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="link-sities">
                <ul>
                    <li>SITIES</li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Viza</a></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
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
@import "../assets/scss/partials/_footer.scss";
footer {
    position: relative;
    background-image: url("../assets/img/footer-bg.jpg");
    background-position: center;
    background-size: contain;
    @include image (200px, 100%);
    @include container (2em, 3em, 1.5em, 1em, 1em, 1em, 0.8em);
}
</style>
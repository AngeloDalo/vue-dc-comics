<template>
    <main>
        <div class="container up">
            <p>--> Content goes here </p>
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
}
</style>
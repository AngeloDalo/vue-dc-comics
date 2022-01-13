<template>
    <footer>
        <h1> {{ title }} </h1>
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

</style>
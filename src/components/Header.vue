<template>
    <header>
        <h1> {{ title }} </h1>
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

</style>
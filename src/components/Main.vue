<template>
    <main>
        <h1> {{ title }} </h1>
    </main>
</template>

<script>
export default {
    name: 'Main',
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
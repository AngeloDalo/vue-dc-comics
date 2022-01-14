<template>
  <div class="title">
        <img class="title-image"
        :src="src"
        :alt="alt">
        <h2> {{ title }} </h2>
  </div>
</template>

<script>
export default {
    name: "MainTitles",
    props: ['src', 'alt', 'title'],
    data() {
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
.title img {
  width: 100%;
}
.title h2 {
  width: 100%;
  font-size: 1em;
}
</style>
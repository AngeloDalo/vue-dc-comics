<template>
    <li>
        <img         
            :src="src"
            :alt="alt">
            <span> {{ title }} </span>
    </li>
</template>

<script>
export default {
    name: "ConnectionsType",
    props: ['src', 'alt', 'title'],
    data() {
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_connections.scss";
    li {
        display: flex;
        align-items: center;
        img {
            width: calc(100% / 5);
            }
            span {
                color: white;
                font-size: 0.8em;
                font-weight: bold;
                margin-left: 0.5em;
            }
        }
</style>
<template>
  <div id="app">
    <HelloWorld msg="" />
    <Header />
    <Main />
    <Footer />
    <Contact />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Contact from "./components/Contact.vue";
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
    Main,
    Footer,
    Contact,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <HelloWorld msg="" />
    <Header />
    <Main />
    <Connections />
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
import Connections from "./components/Connections.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
    Main,
    Footer,
    Contact,
    Connections,
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
  margin-top: 5px;
}
</style>

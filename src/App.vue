<template>
  <div id="app">
    <header>
      <HeaderComp/>
      <HeroComp/>
    </header>
    <main>
      <ContentComp/>
      <FeaturesComp/>
    </main>
    <footer>
      <FooterComp/>
    </footer>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import ContentComp from "./components/ContentComp.vue";
import FeaturesComp from "./components/FeaturesComp.vue";
import FooterComp from "./components/FooterComp.vue";
import HeroComp from "./components/HeroComp.vue";

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    FeaturesComp,
    FooterComp,
    HeroComp,
}
}
</script>

<style lang="scss">
*{padding: 0; margin: 0; box-sizing: border-box;}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
li{list-style-type: none;}
a{display: inline-block; text-decoration: none;}
</style>

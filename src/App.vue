<template>
  <div id="app">
    <header>
      <HeaderComp></HeaderComp>
    </header>
    <main>
      <ContentComp></ContentComp>
      <FeaturesComp></FeaturesComp>
    </main>
    <footer>
      <FooterComp></FooterComp>
    </footer>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import ContentComp from "./components/ContentComp.vue";
import FeaturesComp from "./components/FeaturesComp.vue";
import FooterComp from "./components/FooterComp.vue";

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    FeaturesComp,
    FooterComp
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

// 12 colonne
@for $i from 1 through 12{
  .col-#{$i}{max-width: 100%/10 * $i; flex-basis: 100%/10 * $i;}
}

// right offset
@for $i from 1 through 12{
  .right-offset-#{$i}{margin-right: 100%/10 * $i;}
}
</style>

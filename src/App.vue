<template>
  <div id="app">
    <HeaderComp></HeaderComp>
    <ContentComp></ContentComp>
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import ContentComp from "./components/ContentComp.vue";

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp
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
  .col-#{$i}{width: 100%/12 * $i}
}
</style>

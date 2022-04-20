<template>
  <div class="header">
    <a href="#"><img class="header__logo" src="../assets/img/dc-logo.png" alt="dc logo"></a>
    <nav class="header__nav">
      <ul>
        <a :href="elm.url" v-for="(elm, i) in mainNav" :key="i"><li>{{elm.name}}</li></a>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
name: 'HeaderComp',
data() {
  return {
    mainNav : [
      {
        name : "characters",
        url : "#",
      },
      {
        name : "comics",
        url : "#",
      },
      {
        name : "movies",
        url : "#",
      },
      {
        name : "tv",
        url : "#",
      },
      {
        name : "games",
        url : "#",
      },
      {
        name : "collectibles",
        url : "#",
      },
      {
        name : "videos",
        url : "#",
      },
      {
        name : "fans",
        url : "#",
      },
      {
        name : "news",
        url : "#",
      },
      {
        name : "shop",
        url : "#",
      },
    ]
  }
}
}
</script>

<style scoped lang='scss'>
.header{
  background-color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 70%;
  margin: 0 auto;

  &__logo{
    width: 70%;
    height: auto;
  }

  &__nav{
    ul{
      text-transform: uppercase;
    }

    li{
      margin-left: 1.5em;
      font-size: 0.9rem;
      color: #000;
      font-weight: 700;
      padding: 2.5em 0;
      border-bottom: 4px solid transparent;

      &:hover{
        color: #0282f9;
        border-bottom: 4px solid #0282f9;
      }
    }
  }
}
</style>
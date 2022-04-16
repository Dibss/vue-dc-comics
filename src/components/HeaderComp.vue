<template>
  <div class="header">
    <a href="#"><img class="header__logo" src="../assets/img/dc-logo.png" alt="dc logo"></a>
    <nav class="header__nav">
      <ul>
        <a href="#"><li>characters</li></a>
        <a href="#"><li>comics</li></a>
        <a href="#"><li>movies</li></a>
        <a href="#"><li>tv</li></a>
        <a href="#"><li>games</li></a>
        <a href="#"><li>collectibles</li></a>
        <a href="#"><li>videos</li></a>
        <a href="#"><li>fans</li></a>
        <a href="#"><li>news</li></a>
        <a href="#"><li>shop</li></a>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
name: 'HeaderComp',
// data: {
//   menu : [
//     "characters",
//     "comics",
//     "movies",
//     "tv",
//     "games",
//     "collectibles",
//     "videos",
//     "fans",
//     "news",
//     "shop"
//   ]
// }
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
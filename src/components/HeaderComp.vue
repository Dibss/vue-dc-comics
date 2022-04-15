<template>
  <div class="header">
    <img class="header__logo" src="../assets/img/dc-logo.png" alt="dc logo">
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
    width: 7%;
    height: auto;
    padding: 0.5em 0;
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
    }
  }
}
</style>
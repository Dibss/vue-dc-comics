<template>
  <div class="comic-book">
    <img :src="img" alt="serie">
    <span>{{series}}</span>
  </div>
</template>

<script>
export default {
name: 'ComicBook',
props : {
  img : String,
  price : String,
  series : String,
  type : String
}
}
</script>

<style scoped lang='scss'>
.comic-book{
  margin: 1em 0;
  width: calc(100% / 6);
  img{
    // clip-path: inset(0 0 35% 0);
    width: 180px;
    height: 180px;
    object-fit: cover;
    object-position: top;
    margin-bottom: 0.6em;
  }
  span{
    color: #fff;
    text-transform: uppercase;
    font-size: 0.9rem;
    width: 95%;
    display: inline-block;
  }
}

</style>
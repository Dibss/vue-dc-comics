<template>
  <div class="container">
    <div class="container__content">
      <div class="col-2" v-for="(elm, i) in buyImg" :key="i">
        <img class="col-2" :src="elm.img" :alt="elm.name + 'image'">
        <a :href="elm.url"><span class="col-8">{{elm.name}}</span></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'FeaturesComp',
data(){
  return{
    buyImg : [
      {
        name : "digital comics",
        img : require("../../public/img/buy-comics-digital-comics.png"),
        url : "#"
      },
      {
        name : "dc merchandise",
        img : require("../../public/img/buy-comics-merchandise.png"),
        url : "#"
      },
      {
        name : "subscription",
        img : require("../../public/img/buy-comics-subscriptions.png"),
        url : "#"
      },
      {
        name : "comic shop locator",
        img : require("../../public/img/buy-comics-shop-locator.png"),
        url : "#"
      },
      {
        name : "dc power visa",
        img : require("../../public/img/buy-dc-power-visa.svg"),
        url : "#"
      }
    ]
  }
}
}
</script>

<style scoped lang='scss'>
.container{
  background-color: #0282f9;
  &__content{
    width: 70%;
    margin: 0 auto;
    display: flex;
    flex-wrap: nowrap;

    div.col-2{
      text-transform: uppercase;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: nowrap;
      margin: 1.5em 0;
      padding: 0 0.5em;
      
      img{
        width: 100%;
        height: auto;
      }
      span{
        font-size: 0.75rem;
        padding-left: 0.8em;
        color: #fff;
      }
    }
  }
}

.container__content > div:nth-last-of-type(2) img{max-width: 15%;}
</style>
<template>
  <div class="container">
    <div class="container__content">
      <div class="col-2">
        <img class="col-2" src="../assets/img/buy-comics-digital-comics.png" alt="digital comics image">
        <span class="col-8">digital comics</span>
      </div>
      <div class="col-2">
        <img class="col-2" src="../assets/img/buy-comics-merchandise.png" alt="dc merchandise image">
        <span class="col-8">dc merchandise</span>
      </div>
      <div class="col-2">
        <img class="col-2" src="../assets/img/buy-comics-subscriptions.png" alt="subscription image">
        <span class="col-8">subscription</span>
      </div>
      <div class="col-2">
        <img class="col-2" src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator image">
        <span class="col-8">comic shop locator</span>
      </div>
      <div class="col-2">
        <img class="col-2" src="../assets/img/buy-dc-power-visa.svg" alt="dc power visa image">
        <span class="col-8">dc power visa</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'FeaturesComp',
}
</script>

<style scoped lang='scss'>
.container{
  background-color: #0282f9;
  &__content{
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    flex-wrap: nowrap;

    div.col-2{
      text-align: center;
      text-transform: uppercase;
      color: #fff;
      display: flex;
      align-items: center;
      flex-wrap: nowrap;
      margin: 1.5em 0;
      
      img{
        width: 100%;
        height: auto;
      }
      span{
        font-size: 0.9rem;
      }
    }
  }
}
</style>
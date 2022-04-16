<template>
  <div>
    <div class="container-top">
      <div>
        <div class="col-4 right-offset-2 container-top__left">
          <div class="col-3">
            <h2>dc comics</h2>
            <ul>
              <a href="#"><li>characters</li></a>
              <a href="#"><li>comics</li></a>
              <a href="#"><li>movies</li></a>
              <a href="#"><li>tv</li></a>
              <a href="#"><li>games</li></a>
              <a href="#"><li>videos</li></a>
              <a href="#"><li>news</li></a>
            </ul>
            <h2>shop</h2>
            <ul>
              <a href="#"><li>shop DC</li></a>
              <a href="#"><li>shop DC collectibles</li></a>
            </ul>
          </div>
          <div class="col-3">
            <h2>dc</h2>
            <ul>
              <a href="#"><li>terms of use</li></a>
              <a href="#"><li>privacy policy (New)</li></a>
              <a href="#"><li>ad choices</li></a>
              <a href="#"><li>advertising</li></a>
              <a href="#"><li>jobs</li></a>
              <a href="#"><li>subscription</li></a>
              <a href="#"><li>talent workshops</li></a>
              <a href="#"><li>CPSC certificates</li></a>
              <a href="#"><li>ratings</li></a>
              <a href="#"><li>shop help</li></a>
              <a href="#"><li>contacs us</li></a>
            </ul>
          </div>
          <div class="col-3">
            <h2>sites</h2>
            <ul>
              <a href="#"><li>DC</li></a>
              <a href="#"><li>MAD magazine</li></a>
              <a href="#"><li>DC kids</li></a>
              <a href="#"><li>DC universe</li></a>
              <a href="#"><li>DC power visa</li></a>
            </ul>
          </div>
        </div>
        <div class="col-4 logo">
        </div>
      </div>
    </div>
    <div class="container-bottom">
      <div>
        <div class="container-bottom__left">
          <a href="#"><span>sign-up now!</span></a>
        </div>
        <div class="container-bottom__right">
          <span>follow us</span>
          <div>
            <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook logo"></a>
          </div>
          <div>
            <a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter logo"></a>
          </div>
          <div>
            <a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube logo"></a>
          </div>
          <div>
            <a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest logo"></a>
          </div>
          <div>
            <a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope logo"></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'FooterComp',
}
</script>

<style scoped lang='scss'>
.container-top{
  background-image: url(../assets/img/footer-bg.jpg);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  &__left{
    display: flex;
    padding: 2em 0.5em 3em;
    h2{
      color: #fff;
      text-transform: uppercase;
      font-size: 1rem;
      font-weight: 700;
      margin: 0.5em 0;
    }
    a{
      color: #797c7c;
      text-transform: capitalize;
      font-size: 0.8rem;
      margin: 0.3em 0;
      display: block;
    }
  }
}

.container-top > div{
  width: 70%; 
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}

.col-4.logo{
  background-image: url(../assets/img/dc-logo-bg.png);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}

.container-bottom{
  background-color: #303030;
  &__left{
    span{
      text-transform: uppercase;
      color: #fff;
      border: 1px solid #0282f9;
      padding: 0.5em;
      font-size: 0.8rem;
      font-weight: 700;
      
      &:hover{
        background-color: #0282f9;
      }
    }
  }
  &__right{
    display: flex;
    align-items: center;
    margin: 1em 0;
    span{
      text-transform: uppercase;
      color: #0282f9;
      margin-right: 1em;
      font-weight: 700;
    }
    img{
      width: 60%;
      height: auto;
      margin: 0 0.5em;
    }
  }
}

.container-bottom > div{
  width: 70%; 
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
<template>
  <div class="container">
    <div class="content">
      <h2 class="content__title">--> Content goes here</h2>
    </div>
  </div>
</template>

<script>
export default {
name: 'ContentComp',
}
</script>

<style scoped lang='scss'>
.container{
  background-color: #1c1c1c;
}

.content{
  width: 70%;
  margin: 0 auto;
  display: flex;
  align-content: center;
  &__title{
    color: #fff;
    font-weight: 700;
    padding: 2em 0;
  }
}

</style>
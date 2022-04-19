<template>
  <div class="container">
    <div class="content">
      <ComicsComp/>
    </div>
  </div>
</template>

<script>
import ComicsComp from "./ComicsComp.vue";

export default {
name: 'ContentComp',
components : {
    ComicsComp
}
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
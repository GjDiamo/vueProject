<!--这是一个子组件-->
<template>
  <div class="row title">
    <div class="col-xs-12">
      <!--<router-link tag="div" v-if="needBack" class="div_back" to="/">&lt;返回</router-link>-->
      {{title}}
    </div>
  </div>
</template>
<script>
  export default {
    name: "title-bar",
    //通过props来向父组件传递消息
    props: {
      title: String,
    }
  }
</script>
<style scoped>
  .div_back{
    position: absolute;
    left: 15px;
  }
</style>

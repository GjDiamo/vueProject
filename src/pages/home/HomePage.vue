<!--这个就是根组件-->
<template>
  <div class="hello">
    <!--标题栏-->
    <title-bar :title="title" ></title-bar>
    <!--轮播图-->
    <Carousel></Carousel>
    <!--显示数据-->
    <!--底部栏-->
    <menu-bar></menu-bar>
  </div>
</template>
<script>
  import TitleBar from '@/pages/common/TitleBar'
  import Carousel from '@/pages/common/Carousel'
  import MenuBar  from '@/pages/common/MenuBar'
export default {
  name: 'home-page',
  //注册组件
  components:{
    TitleBar,
    Carousel,
    MenuBar
  },
  // 返回数据
  data () {
    return {
      title: '小黄车首页'
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >

</style>




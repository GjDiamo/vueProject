<!--这是一个子组件-->
<template>
  <!--5.底部菜单栏-->
  <div class="div-height">
    <div class="menu" >
      <div class="col-xs-4 menu-item" >
        <span class="glyphicon glyphicon-home"></span>
        <p>首页</p>
      </div>
      <div class="col-xs-4 menu-item" >
        <span class="glyphicon glyphicon-yen"></span>
        <p>我的资产</p>
      </div>
      <div class="col-xs-4 menu-item" >
        <span class="glyphicon glyphicon-user"></span>
        <p>我</p>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: "menu-bar",
    props:{
      index:{
        type:String,
         //default:"1"
      }
    },
 /*   methods:{
      handleClick(index){
        console.log(index)
        switch (index){
          case '1':
            //跳转去首页
            this.$router.push('/')
            break;
          case '2':
            this.$router.push('/select')
            //跳转去选号页面
            break;
          case '3':
            this.$router.push('/user')
            //跳转去用户页面
            break;
        }
      }
    }*/
  }
</script>

<style scoped>
  .div-height{
    height: 50px;
  }
</style>

<template>
  <div id="app">
    <mt-header fixed title="传智播客"></mt-header>
    <router-view></router-view>
    <mt-tabbar v-model="selected">
      <mt-tab-item id="外卖">
        <img slot="icon" src="./assets/images/menu1.png">
       外卖
    </mt-tab-item>
    <mt-tab-item id="订单">
      <img slot="icon" src="./assets/images/menu2.png">
      订单
    </mt-tab-item>
    <mt-tab-item id="发现">
      <img slot="icon" src="./assets/images/menu3.png">
      发现
    </mt-tab-item>
    <mt-tab-item id="我的">
      <img slot="icon" src="./assets/images/menu4.png">
      我的
    </mt-tab-item>
</mt-tabbar>
  </div>
</template>

<script>
import mintUi from 'mint-ui'
import 'bootstrap/dist/css/bootstrap.css'
import  '@/assets/dist/css/mui.css'
export default {
  name: 'App',
  methods:{
   
  }
}
</script>

<style >
#app{
  padding-top:40px ;
}
</style>

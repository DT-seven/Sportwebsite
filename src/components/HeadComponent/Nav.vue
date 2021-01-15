<template>
  <div class="Nav">
      <NavBar title='Muscle' :NavBarfont =true />
      <NavBar title='图片'/>
      <NavBar title='视频'/>
      <NavBar title='我的数据'/>
      <SignModel />
      
  </div>
</template>
<script>
import SignModel from './signModel.vue'
import NavBar from './NavBar.vue'
export default {
    name:'Nav',
    components:{
        NavBar,
        SignModel
    }
}
</script>
<style scoped lang='scss'>
 .Nav{
     display: flex;
     height: 100px;
 }

</style>
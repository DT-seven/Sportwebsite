<template>
  <div class='signModel'>
      <div class='seek'>
          <a-button shape="circle"><SearchOutlined /></a-button>
      </div>
      <div class='search'>
           <a-button type="primary">Sign Up</a-button>
      </div>
  </div>
</template>
<script>
import {SearchOutlined} from '@ant-design/icons-vue'
export default {
name:'signModel',
components:{
    SearchOutlined
}
}
</script>
<style scoped>
 .signModel{
     position: relative;
     line-height: 100px;
     height: 100px;  
 }
 .seek{
     position: absolute;
     left:950px
 }
 .search{
     position: absolute;
     left:1000px
 }
</style>
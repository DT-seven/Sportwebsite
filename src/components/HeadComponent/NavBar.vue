<template>
  <div class="NavBar" :class="{active:NavBarfont}">
      {{data.title}}
  </div>
    
</template>
<script>

import { reactive } from 'vue'
export default {
name:'NavBar',
props:{
    title:String,
    NavBarfont:Boolean
},
setup(props){
    const data = reactive({title:props.title,NavBarfont:props.NavBarfont})
    return{
        data
    }
}
}
</script>
<style scoped>
.NavBar{
    height: 50px;
    width: 100px;   
    font-size:20px;
    margin:25px 0;
    color:#30336b;
    text-align: center;
    line-height: 50px;
}
.active{
    font-family: hanyiwei;
    font-size:35px;
    color:#130f40;
}
</style>
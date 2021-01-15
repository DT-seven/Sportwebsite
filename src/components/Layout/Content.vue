<template>
  <div class="content">
      <div class="contentTitle">
        You Are The Best !
      </div>
      <div class="contentText">
          All life is a chance. The man who goes farthest 
        is generally the one who is willing to do and dare.
      </div>
  </div>
</template>
<script>
export default {
name: 'Content'
}
</script>
<style scoped>
  .content{
    position: relative;
    background-image:url("../../assets/image/sport.jpg");
    height: 550px;
  }
  .contentTitle{
    position: absolute;
    top: 50px;
    right: 200px;
    font-family: 'EnglishSport';
    font-size:40px;
    color: black;
  }
    .contentText{
    position: absolute;
    width: 400px;
    
    top: 100px;
    right: 150px;
    font-family: 'TypoPRODancingScriptRegular';
    font-size:28px;
    color: #1e272e;
  }
</style>
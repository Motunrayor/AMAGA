<template>
 <div class="source">
<img src="../assets/calendar.png"><a href="#">Traffic Sources</a>
        
 </div>
    
</template>

<script>
export default {
  name: 'Source',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.source{
  position:absolute;
  background:#413f59;
  width: 211px;
  height:39px;
  top:33.5%;
  border-bottom: #BBBACA 0.1px ridge;
   
}
.source img{
  color:#F5F5DC;
  padding:5px 0px 0px 15px;
  width:15px;
}
.source a{
  color:#F5F5DC;
  text-decoration:none;
  font-size:13px;
  padding:0px 0px 0px 10px;
}
</style>
<template>
 <div class="recom">

         <img src="../assets/anchor.png"><a href="#">Recommendation</a>
        
 </div>
    
</template>

<script>
export default {
  name: 'Recommendation',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.recom{
  position:absolute;
  background:#413f59;
  width: 211px;
  height:39px;
  top:51.7%;
  border-bottom: #BBBACA 0.1px ridge;
   
}
.recom img{
  color:#F5F5DC;
  padding:5px 0px 0px 15px;
  width:15px;
}
.recom a{
  color:#F5F5DC;
  text-decoration:none;
  font-size:13px;
  padding:0px 0px 0px 10px;
}
</style>
<template>
 <div class="convers">

         <img src="../assets/map.png"><a href="#">Conversation</a>
        
 </div>
    
</template>

<script>
export default {
  name: 'Conversation',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.convers{
  position:absolute;
  background:#413f59;
  width: 211px;
  height:39px;
  top:45.6%;
  border-bottom: #BBBACA 0.1px ridge;
   
}
.convers img{
  color:#F5F5DC;
  padding:5px 0px 0px 15px;
  width:15px;
}
.convers a{
  color:#F5F5DC;
  text-decoration:none;
  font-size:13px;
  padding:0px 0px 0px 10px;
}
</style>
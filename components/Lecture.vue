<template>
 <div class="lecture">

         <img src="../assets/user.png"><a href="#">Lecture Hall</a>
        
 </div>
    
</template>

<script>
export default {
  name: 'Lecture',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.lecture{
  position:absolute;
  background:#413f59;
  width: 211px;
  height:39px;
  top:27.3%;
  border-bottom: #BBBACA 0.1px ridge;
   
}
.lecture img{
  color:#F5F5DC;
  padding:5px 0px 0px 15px;
  width:15px;
}
.lecture a{
  color:#F5F5DC;
  text-decoration:none;
  font-size:13px;
  padding:0px 0px 0px 10px;
}
</style>
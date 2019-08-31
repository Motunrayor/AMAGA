<template>
 <div class="home">

         <img src="../assets/pink-house.png"><a href="#">Home</a>
         
    
 </div>
    
</template>

<script>
export default {
  name: 'Home',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home{
  position:absolute;
  background-color:#000;
  width: 207px;
  height:35px;
  top: 9.3%;
  border-left:#FF0078 5px ridge;
  border-bottom: #BBBACA 0.1px ridge;
   
}
.home img{
  color: #FF0078;
  padding:5px 0px 0px 10px;
  width:18px;
}
.home a{
  color:#FF0078;
  text-decoration:none;
  font-size:13px;
  padding:0px 0px 0px 10px;
}

</style>
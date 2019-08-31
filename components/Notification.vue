<template>
 <div class="notification">
    <div id="bell">&#x1f514;</div>
    <div id= num>1</div>
 </div>
    
</template>

<script>
export default {
  name: 'Notification',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.notification{
	position:absolute;
	width: 70px;
	height:52px;
    background:#413f59;
	left:77.0%;
    border: #BBBACA 0.1px ridge;
}
#bell{
    text-align:center;
    color:#fff;
    padding-top:15px;    
}
#num{
    border-radius:50%;
    background:red;
    width:10px;
    height:15px;
    margin:-20px 0px 0px 36px;
    
}
</style>
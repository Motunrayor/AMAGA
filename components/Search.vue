<template>
 <div class="search">
    <input type="text" placeholder= "search for anything...">
 </div>
    
</template>

<script>
export default {
  name: 'search',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
input{
    position:absolute;
	width: 320px;
	height:48px;
	background:#413f59;
    right:59.8%;
	border-color: transparent;
    text-indent:20px;
    border: #BBBACA 0.9px ridge;
    background:url(../assets/search.png);
    background-repeat:no-repeat;
    background-position:center right 20px;
}

</style>
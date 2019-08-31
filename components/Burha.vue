<template>
 <div class="burha">
    <img src="../assets/image.jpg">
	<select>
	<option>Akinrimisi Motunrayo</option>
	<option>Fatumo Joseph</option>
	</select>
 </div>
    
</template>

<script>
export default {
  name: 'Burha',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.burha{
	position:absolute;
	width: 232px;
	height:51px;
    background:#fff;
	left:82.2%;
	background:#413f59;
    border: #BBBACA 0.3px ridge;

}
.burha img{
	width:25px;
	height:25px;
	margin:13px 0px 0px 20px;
	border-radius:50%;
}
select{
	color:#F5F5DC;
	background:#413f59;
	border-color: transparent;
	margin:-10px 0px 0px 10px;
  
}
</style>
<template>
 <div class="review">
     <p>Reviews</P>
     <select>
     <option>Today</option>
     </select>
     <p id=number>1,238</p>
     <p id="notice">you got <span>+24,916</span> more reviews than last week</P>
     <span><img src="../assets/motun.jpg" width="32px" height="30px"></span>
     <span><img src="../assets/benita.jpg" width="32px" height="30px"></span>
     <span><img src="../assets/dorcas.jpg" width="32px" height="30px"></span>
     <span><img src="../assets/joe.jpg" width="32px" height="30px"></span>
     <span><img src="../assets/precious.jpg" width="32px" height="30px"></span>
      <span><img src="../assets/Path 2.png"></span>
     <label>View All</label>
     
     <button id="one">
     <p>1,238</p>
     <h6>Today</h6>
     </button>
     <button id="two">
     <p>765</p>
     <h6>Drlbbble</h6>
     </button>
    
     
 </div>
    
</template>

<script>
export default {
  name: 'Review',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.review{
    position:absolute;
	width: 350px;
	height:170px;
    left: 71%;
    top: 17%;
    background:#413f59;
    color:#F5F5DC;
    border-radius: 7px 7px 0px 0px;
}
span img{
    border-radius: 50px;
    padding:10px;
    margin-top: -10px;

}
p{
    padding-left:15px;
}
#number{
    padding-left:15px;
    font-size:40px;
    margin-top: -5px;
}
#notice{
    font-size:14px;
    margin-top: -29px;
    color:gray;
}
span{
    color:#FF0078;
}
label{
    float:right;
    padding: 15px 20px 0px 0px ;
    font-size:13px;
     margin-top: -6px;
}
select{
    position:absolute;
    top:10%;
    left:80%;
    color:#F5F5DC;
	background:#413f59;
	border-color: transparent;
    color:gray;
    
}
#one{
    background:#413f59;
    width:175px;
    height:60px;
    position: absolute;
    left: 0%;
    right: 0%;
    top: 101%;
    bottom: 0%;
    border:none;
    color:#F5F5DC;
    border-radius: 0px 0px 0px 10px;
    box-shadow:rgba(52, 52, 52, 0.5) 0px 5px 4px;
}
#one p{
    font-size:15px;
    margin:5px 20px 0px 0px;
}
#one h6{
    margin:8px 20px 0px 15px;
    color:gray;
}
#two{
    background:#413f59;
    width:175px;
    height:60px;
    position: absolute;
    color:#F5F5DC;
    left: 50%;
    right: 0%;
    top: 101%;
    bottom: 0%;
    border:none;
    border-radius: 0px 0px 10px 0px;
    box-shadow:rgba(52, 52, 52, 0.5) 0px 5px 4px;
}
#two p{
    font-size:15px;
    margin:5px 20px 0px 0px;
}
#two h6{
    margin:8px 20px 0px 15px;
    color:gray;
}
</style>
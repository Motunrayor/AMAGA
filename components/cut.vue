<p> Use Map</P>
     <div class="loader1"></div><label>426 people</label>
     <div class="loader2"></div><label>312 people</label>
     <div class="loader3"></div><label>289 people</label>
     <div class="loader4"></div><label>211 people</label>

 </div>

 /map/
 p{
    padding-left:15px;
}
.loader1 {
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid #00E8CB;
  width: 6px;
  height: 6px;
   margin-top:10px;
   margin-left:78%;
  -webkit-animation: spin 2s linear infinite; /* Safari */
  animation: spin  linear infinite;
}
span{
    float:left;
}
.loader2 {
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid #FFEF00;
  width: 6px;
  height: 6px;
  margin-top:10px;
  margin-left:78%;
  -webkit-animation: spin 2s linear infinite; /* Safari */
  animation: spin   linear infinite;
}
.loader3 {
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid #FF0078;
  width: 6px;
  height: 6px;
  margin-top:10px;
  margin-left:78%;
  -webkit-animation: spin 2s linear infinite; /* Safari */
  animation: spin  linear infinite;
}
.loader4 {
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid grey;
  width: 6px;
  height: 6px;
  margin-top:10px;
  margin-left:78%;
  -webkit-animation: spin 2s linear infinite; /* Safari */
  animation: spin  linear infinite;
}

/* Safari */
@-webkit-keyframes spin {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
label{
  float:right;
  margin-top:-30px;
  padding-right:20px;


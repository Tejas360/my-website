# 
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" width="device-width" />
<style type="text/css">

#web_name{
Color: Yellow;
height:45px;
width:392px;
border:2px solid red;
background:red;
font-size:40px;
position: absolute;
left:0px;
top:0px;
z-index:1;
overflow: hidden;
}
#text1{
position: absolute;
transform:translate(125px,-45px);
font-weight:900;


}
#img1{
transform:translate(-50px,-40px) rotate(20deg);
animation:pump 20s ease-in 0s  infinite  alternate;
}

@keyframes pump{

0%{
transform:translate(-50px,-40px) rotate(0deg);


}

100%{
transform:translate(400px,-40px) rotate(90deg);
}


}

#img2{
transform:translate(400px,-110px) rotate(20deg);
animation:cof 20s ease-in 0s  infinite  alternate;
}

@keyframes cof{

0%{
transform:translate(400px,-110px) rotate(0deg);


}

100%{
transform:translate(-80px,-110px) rotate(90deg);
}


}

#img3{
transform:translate(150px,-180px) rotate(20deg);
animation:straw 20s ease-in 0s  infinite  alternate;
}

@keyframes straw{

0%{
transform:translate(150px,-300px) rotate(0deg);


}

100%{
transform:translate(150px,-120px) rotate(360deg);
}


}


#offer_wind{

position: absolute;
top:100px;
left:0px;
height:300px;
width:390px;
border:2px solid red;
border-radius:10%;
box-shadow:10px 14px 27px grey;
background-image:url("https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.muxToCvgWbEPnH8RRiUjagHaEo%26pid%3DApi&f=1");
}
</style>
<title></title>
</head>
<body>
<div id="web_name">
<p ><center id="text1" >फूddy</center></p>
<img id="img1" src="https://img.icons8.com/small/50/000000/cute-pumpkin.png"/><br>
<img id="img2" src="https://img.icons8.com/small/64/000000/kawaii-soda.png"/><br>
<img id="img3"src="https://img.icons8.com/small/64/000000/strawberry.png"/>

</div>


<div id="offer_wind">




</div>
<script type="text/javascript">

array=[

"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.cnjiiPPJ5uo4h_8in-cDyAHaH_%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.srE4ux0pCteNVy857egKIwHaE7%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.mBjY2ET-uUILw_udEeDUtgHaFj%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.aL8FhlTSUXOq-w3h57t8AQHaEo%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.muxToCvgWbEPnH8RRiUjagHaEo%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.j8CuYJvk8OA9jcj_MijZLAHaFb%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.j8CuYJvk8OA9jcj_MijZLAHaFb%26pid%3DApi&f=1)",
"URL(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.j8CuYJvk8OA9jcj_MijZLAHaFb%26pid%3DApi&f=1)"


]

var chn=-1;
function change(){
chn=chn+1;
if(chn>=array.length){
chn=0

}
document.getElementById("offer_wind").style.backgroundImage=array[chn]

}
setInterval(change,2000)


</script>
</body>
</html>

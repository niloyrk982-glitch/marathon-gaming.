<!DOCTYPE html>
<html>
<head>
<title>Car Racing Game</title>

<style>
body{
margin:0;
overflow:hidden;
background:gray;
}

#road{
width:300px;
height:100vh;
background:#222;
margin:auto;
position:relative;
overflow:hidden;
border-left:5px solid white;
border-right:5px solid white;
}

#car{
width:50px;
height:90px;
background:red;
position:absolute;
bottom:20px;
left:125px;
border-radius:10px;
}

.enemy{
width:50px;
height:90px;
background:yellow;
position:absolute;
top:-100px;
border-radius:10px;
}

#line{
width:10px;
height:100vh;
background:repeating-linear-gradient(
white 0px,
white 40px,
transparent 40px,
transparent 80px
);
position:absolute;
left:145px;
}

#score{
position:absolute;
top:10px;
left:10px;
color:white;
font-size:25px;
font-family:Arial;
z-index:10;
}
</style>
</head>

<body>

<div id="score">Score: 0</div>

<div id="road">

<div id="line"></div>
<div id="car"></div>

</div>

<script>

let car=document.getElementById("car");
let road=document.getElementById("road");
let scoreText=document.getElementById("score");

let score=0;

document.addEventListener("touchmove",(e)=>{

let x=e.touches[0].clientX-road.offsetLeft-25;

if(x<0)x=0;
if(x>250)x=250;

car.style.left=x+"px";
});

function createEnemy(){

let enemy=document.createElement("div");
enemy.classList.add("enemy");

enemy.style.left=Math.random()*250+"px";

road.appendChild(enemy);

let move=setInterval(()=>{

enemy.style.top=enemy.offsetTop+5+"px";

if(enemy.offsetTop>700){

enemy.remove();
clearInterval(move);

score++;
scoreText.innerHTML="Score: "+score;
}

if(

enemy.offsetTop+90>car.offsetTop &&
enemy.offsetLeft<car.offsetLeft+50 &&
enemy.offsetLeft+50>car.offsetLeft

){

alert("Game Over! Score: "+score);
location.reload();

}

},30);

}

setInterval(createEnemy,1500);

</script>

</body>
</html>

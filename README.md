# Anamika-s-Birthdayy
Happy Birthday 
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Happy Birthday Anamika ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#ffd6e7,#ffeef5,#fff);
overflow-x:hidden;
color:white;
}

#loader{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:#ff4f91;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
z-index:9999;
}

.loader-text{
font-size:28px;
font-weight:bold;
animation:pulse 1.2s infinite;
text-align:center;
}

@keyframes pulse{
0%{transform:scale(1);}
50%{transform:scale(1.08);}
100%{transform:scale(1);}
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:
linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url("https://images.unsplash.com/photo-1492684223066-81342ee5ff30?w=1200") center/cover;
background-attachment:fixed;
}

.hero h1{
font-size:52px;
text-shadow:0 0 20px hotpink;
animation:fadeInScale 0.8s ease-out;
}

.hero p{
font-size:20px;
margin-top:15px;
animation:fadeIn 1s ease-out 0.3s both;
}

@keyframes fadeInScale{
from{
opacity:0;
transform:scale(0.9);
}
to{
opacity:1;
transform:scale(1);
}
}

@keyframes fadeIn{
from{opacity:0;}
to{opacity:1;}
}

button{
margin-top:40px;
padding:16px 42px;
border:none;
border-radius:50px;
font-size:18px;
background:#ff3d86;
color:white;
cursor:pointer;
box-shadow:0 0 25px hotpink;
transition:.3s;
animation:fadeIn 1s ease-out 0.6s both;
}

button:hover{
transform:scale(1.08);
box-shadow:0 0 35px hotpink;
}

section{
padding:70px 20px;
text-align:center;
animation:slideUp 0.8s ease-out;
}

@keyframes slideUp{
from{
opacity:0;
transform:translateY(30px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.glass{
width:90%;
max-width:800px;
margin:auto;
background:rgba(255,255,255,.18);
backdrop-filter:blur(14px);
border-radius:30px;
padding:35px;
color:white;
box-shadow:0 0 30px rgba(255,255,255,.2);
}

.glass h2{
font-size:28px;
margin-bottom:20px;
color:#ff3d86;
}

#message{
font-size:23px;
line-height:1.8;
min-height:230px;
}

.hidden{
display:none;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:18px;
padding:20px;
}

.gallery img{
width:100%;
height:220px;
object-fit:cover;
border-radius:20px;
transition:.4s;
box-shadow:0 10px 25px rgba(0,0,0,.25);
}

.gallery img:hover{
transform:scale(1.07);
box-shadow:0 15px 35px rgba(255,61,134,.4);
}

.heart{
position:fixed;
bottom:-30px;
font-size:25px;
animation:float 6s linear infinite;
pointer-events:none;
z-index:10;
}

@keyframes float{
0%{
transform:translateY(0);
opacity:1;
}
100%{
transform:translateY(-110vh);
opacity:0;
}
}

@media(max-width:768px){
.hero h1{font-size:36px;}
.hero p{font-size:16px;}
button{padding:14px 28px;font-size:16px;}
.glass{padding:25px;}
#message{font-size:18px;}
}

</style>

</head>

<body>

<div id="loader">
<div class="loader-text">
Preparing a Special Surprise... 💖
</div>
</div>

<div class="hero">
<h1>Happy Birthday 🎂</h1>
<h1>Anamika ❤️</h1>
<p>A Surprise Made With Love By Raushan</p>
<button onclick="startSurprise()">
🎁 Open Your Gift
</button>
</div>

<section id="letter" class="hidden">
<div class="glass">
<h2>💌 A Letter For You</h2>
<br>
<p id="message"></p>
</div>
</section>

<section id="gallery" class="hidden">
<h2 style="color:#ff3d86;font-size:34px;margin-bottom:30px;">
📸 Beautiful Memories
</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1492684223066-81342ee5ff30?w=400" alt="Memory 1">
<img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?w=400" alt="Memory 2">
<img src="https://images.unsplash.com/photo-1516874150951-faeb2853a146?w=400" alt="Memory 3">
<img src="https://images.unsplash.com/photo-1519904981063-b0cf448d479e?w=400" alt="Memory 4">
<img src="https://images.unsplash.com/photo-1511379938547-c1f69b13d835?w=400" alt="Memory 5">
<img src="https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?w=400" alt="Memory 6">
<img src="https://images.unsplash.com/photo-1487180144351-b8472da7d491?w=400" alt="Memory 7">
<img src="https://images.unsplash.com/photo-1514320291840-2e0a9bf2a9ae?w=400" alt="Memory 8">
<img src="https://images.unsplash.com/photo-1514632923736-6d29dd01d977?w=400" alt="Memory 9">
</div>
</section>

<section id="final" class="hidden">
<div class="glass">
<h2>💖 A Special Wish 💖</h2>
<br>
<p style="font-size:22px;line-height:1.8;">
May every smile you share return to you a thousand times.
May your dreams come true, your heart stay happy,
and your life be filled with endless joy.
<br><br>
🎂 Happy Birthday Anamika 🎂
<br><br>
❤️ With Love,<br>
<b>Raushan</b>
</p>
</div>
</section>

<audio id="music" loop>
<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<script>

const text=
`Thank you! 💗

For being a part of my life.

I wish all your dreams come true and I pray for your good health because that's the most important thing. ❤️

Happy Birthday! 🎂🎈

— Raushan`;

function startSurprise(){
document.querySelector(".hero").style.display="none";
document.getElementById("letter").classList.remove("hidden");
document.getElementById("gallery").classList.remove("hidden");
document.getElementById("final").classList.remove("hidden");
try{
document.getElementById("music").play();
}catch(e){
console.log("Audio autoplay prevented by browser");
}
typeWriter();
createConfetti();
}

window.onload=function(){
setTimeout(()=>{
document.getElementById("loader").style.display="none";
},2500);
}

let i=0;

function typeWriter(){
if(i<text.length){
document.getElementById("message").innerHTML+=text.charAt(i);
i++;
setTimeout(typeWriter,45);
}
}

function createConfetti(){
for(let j=0;j<20;j++){
setTimeout(()=>{
const h=document.createElement("div");
h.className="heart";
h.innerHTML="💖";
h.style.left=Math.random()*100+"vw";
h.style.fontSize=(20+Math.random()*20)+"px";
document.body.appendChild(h);
setTimeout(()=>h.remove(),6000);
},j*100);
}
}

setInterval(()=>{
const h=document.createElement("div");
h.className="heart";
h.innerHTML="💖";
h.style.left=Math.random()*100+"vw";
h.style.fontSize=(20+Math.random()*20)+"px";
document.body.appendChild(h);
setTimeout(()=>h.remove(),6000);
},350);

</script>

</body>
</html>

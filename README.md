<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QuickGG</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial,sans-serif;
background:black;
overflow-x:hidden;
color:white;
}

/* BACKGROUND */

body::before{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background-image:url("https://picsum.photos/1920/1080");
background-size:cover;
background-position:center;
filter:brightness(0.35);
z-index:-2;
}

body::after{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:
radial-gradient(circle at top,#7e22ce55,transparent 40%),
radial-gradient(circle at bottom,#2563eb55,transparent 40%);
z-index:-1;
}

/* NAVBAR */

.navbar{
display:flex;
justify-content:center;
align-items:center;
padding:25px;
backdrop-filter:blur(10px);
background:rgba(0,0,0,0.3);
border-bottom:1px solid rgba(255,255,255,0.1);
position:sticky;
top:0;
}

.logo{
font-size:48px;
font-weight:900;
letter-spacing:3px;
background:linear-gradient(to right,#c084fc,#60a5fa);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
text-shadow:0 0 20px purple;
}

/* HERO */

.hero{
text-align:center;
padding:90px 20px;
}

.hero h1{
font-size:70px;
margin-bottom:20px;
text-shadow:0 0 25px purple;
}

.hero p{
font-size:24px;
color:#ddd;
}

/* GAME GRID */

.games{
max-width:1400px;
margin:auto;
padding:30px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
}

.card{
background:rgba(255,255,255,0.08);
border:1px solid rgba(255,255,255,0.15);
border-radius:25px;
overflow:hidden;
cursor:pointer;
transition:0.3s;
backdrop-filter:blur(10px);
}

.card:hover{
transform:translateY(-10px) scale(1.03);
box-shadow:0 0 35px #9333ea;
border-color:#c084fc;
}

.card:active{
transform:scale(0.95);
}

.card img{
width:100%;
height:170px;
object-fit:cover;
transition:0.4s;
}

.card:hover img{
transform:scale(1.08);
}

.card p{
padding:15px;
font-size:24px;
font-weight:bold;
text-align:center;
}

/* FOOTER */

.footer{
text-align:center;
padding:40px;
color:#aaa;
}

</style>
</head>

<body>

<div class="navbar">
<div class="logo">QUICKGG</div>
</div>

<div class="hero">
<h1>WELCOME TO QUICKGG</h1>
<p>Play awesome unblocked games at school.</p>
</div>

<div class="games">

<div class="card">
<img src="https://picsum.photos/400/300?1">
<p>Slope</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?2">
<p>Run 3</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?3">
<p>1v1.LOL</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?4">
<p>Retro Bowl</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?5">
<p>Basketball Stars</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?6">
<p>Drift Hunters</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?7">
<p>Cookie Clicker</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/300?8">
<p>Monkey Mart</p>
</div>

</div>

<div class="footer">
© 2026 QUICKGG
</div>

</body>
</html>


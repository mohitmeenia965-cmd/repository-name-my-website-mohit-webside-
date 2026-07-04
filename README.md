<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>InstaBoost</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0f172a;
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#111827;
}

.logo{
font-size:28px;
font-weight:bold;
color:#00d4ff;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
text-align:center;
padding:80px 20px;
}

.hero h1{
font-size:45px;
margin-bottom:15px;
}

.hero p{
color:#cbd5e1;
margin-bottom:30px;
}

input{
width:320px;
padding:14px;
border:none;
border-radius:8px;
font-size:16px;
}

button{
padding:14px 25px;
border:none;
background:#00d4ff;
color:white;
border-radius:8px;
cursor:pointer;
font-size:16px;
margin-left:10px;
}

.cards{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:20px;
padding:50px 20px;
}

.card{
width:280px;
background:#1e293b;
padding:20px;
border-radius:12px;
text-align:center;
}

.card h2{
margin-bottom:10px;
color:#00d4ff;
}

footer{
text-align:center;
padding:20px;
background:#111827;
margin-top:40px;
}
</style>

</head>
<body>

<header>
<div class="logo">InstaBoost</div>

<nav>
<a href="#">Home</a>
<a href="#">Services</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Grow Your Instagram Smarter</h1>

<p>Analyze your profile, generate hashtags and improve your content.</p>

<input id="username" placeholder="Enter Instagram Username">

<button onclick="analyze()">Analyze</button>

<p id="result" style="margin-top:20px;"></p>

</section>

<section class="cards">

<div class="card">
<h2>Profile Analyzer</h2>
<p>Get basic profile insights.</p>
</div>

<div class="card">
<h2>Hashtag Generator</h2>
<p>Find useful hashtags for your posts.</p>
</div>

<div class="card">
<h2>Caption Ideas</h2>
<p>Create engaging captions instantly.</p>
</div>

</section>

<footer>
© 2026 InstaBoost. All Rights Reserved.
</footer>

<script>
function analyze(){

let user=document.getElementById("username").value;

if(user==""){
document.getElementById("result").innerHTML="Please enter a username.";
return;
}

document.getElementById("result").innerHTML=
"Analysis complete for <b>@"+user+"</b><br><br>Estimated Engagement: Good ✅";
}
</script>

<body>
<h1 style="color:red;">TEST</h1>

<header>
...
</html>

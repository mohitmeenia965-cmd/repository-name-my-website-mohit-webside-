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

<h1>Grow Your Instagram Followers</h1>

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

let shayari = [

"😂 Sorry! Ye sirf ek prank tha.<br><br>🌹 Muskaan se khoobsurat koi gehna nahi hota, dil se hasne wala kabhi tanha nahi hota. ❤️",

"😅 Sorry! Followers nahi badhe.<br><br>✨ Haste raho, muskurate raho, zindagi ka har pal jeete raho. 😊",

"🤣 Oops! Prank successful.<br><br>🌸 Phool khilte hain baharon ke liye, muskaan zaroori hai jeene ke liye. 💐",

"😂 Sorry yaar! Bas thoda hasaana tha.<br><br>🔥 Sapne woh hote hain jo mehnat se poore hote hain. 💯",

"😜 Caught you! Ye sirf mazaak tha.<br><br>❤️ Dil bada rakho, followers to aate jaate rehte hain. 😄",

"😂 Sorry! Fake followers nahi mile.<br><br>🌹 Asli pehchaan mehnat se banti hai, shortcut se nahi. ✨",

"😅 Arre gussa mat hona!<br><br>😊 Muskurahat har dard ki sabse achhi dawa hai. ❤️",

"🤣 Bas ek chhota sa prank tha.<br><br>🌟 Zindagi mein haste raho, kyunki hasi hi asli daulat hai.",

"<br><br>💪 Mehnat itni khamoshi se karo ki kamyabi shor macha de.",

"😎 Sorry! Tum prank mein fas gaye.<br><br>🌹 Khush rehna hi sabse badi jeet hai, muskuraate raho hamesha. ❤️"

];

let random = Math.floor(Math.random() * shayari.length);

document.getElementById("result").innerHTML =
"😂 Sorry! Ye sirf ek prank tha.<br><br>" +
"<b>@" + user + "</b><br><br>" +
shayari[random];
}
</script>

<body>
<h1 style="color:skyblue;">MOHIT FIRST FILE</h1>

<header>
...
</html>

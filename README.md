<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mohit's Website</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}

header{
    background:#0077ff;
    color:white;
    text-align:center;
    padding:30px;
}

section{
    max-width:800px;
    margin:20px auto;
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,.1);
}

button{
    background:#0077ff;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:6px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#005ad1;
}

footer{
    text-align:center;
    padding:20px;
    background:#222;
    color:white;
    margin-top:30px;
}
</style>

</head>
<body>

<header>
<h1>Welcome to Mohit's Website</h1>
<p>My First Website</p>
</header>

<section>
<h2>About Me</h2>
<p>Hello! Mera naam Mohit hai. Yeh meri pehli website hai jo HTML, CSS aur JavaScript se bani hai.</p>

<button onclick="hello()">Click Me</button>

<p id="msg"></p>
</section>

<footer>
© 2026 Mohit's Website
</footer>

<script>
function hello(){
document.getElementById("msg").innerHTML="🎉 Welcome Mohit! Button Successfully Clicked.";
}
</script>

</body>
</html># repository-name-my-website-mohit-webside-
Description : My first website ()

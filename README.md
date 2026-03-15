<!DOCTYPE html>
<html>
<head>

<title>Smart Online Tips</title>

<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="stylesheet" href="style.css">

</head>

<body><body{
font-family:Arial;
margin:0;
background:#f4f4f4;

<header><header{
background:#111;
color:white;
padding:20px;
text-align:center;

<h1>Smart Online Tips</h1>
<p>Technology • Apps • Online Earning</p>

</header>

<nav><nav{
background:#333;
padding:10px;
text-align:center;

<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
<a href="privacy.html">Privacy</a>

</nav><
nav a{
color:white;
margin:10px;
text-decoration:none;
font-weight:bold;

<input id="search" placeholder="Search articles...">

<div class="container" id="articles">

<div class="card">

<h2>
<a href="article1.html">
Top 5 Apps to Make Money Online
</a>
</h2>

<p>
Discover apps that help you earn money using only your phone.
</p>

</div>

<div class="card">

<h2>
<a href="article2.html">
Best Free AI Tools in 2026
</a>
</h2>

<p>
Powerful AI tools anyone can use for productivity.
</p>

</div>

<div class="card">

<h2>
<a href="article3.html">
How Beginners Start Blogging
</a>
</h2>

<p>
Learn how to build your first website easily.
</p>

</div>

</div>

<footer>

<p>© 2026 Smart Online Tips</p>

</footer>

<script src="script.js"></script><const search = document.getElementById("search")

#search.addEventListener("keyup", function(){

let filter = search.value.toLowerCase()

let articles = document.querySelectorAll(".card")

articles.forEach(function(card){

let text = card.innerText.toLowerCase()

card.style.display = text.includes(filter) ? "" : "none"

})

})

</body>
</html>

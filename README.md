<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IsmaelOmar</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f4f4f4;
}

header{
background:#0d6efd;
color:white;
padding:20px;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
max-width:1200px;
margin:auto;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
}

.hero{
height:80vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1200');
background-size:cover;
background-position:center;
color:white;
}

.hero h1{
font-size:55px;
}

.hero p{
font-size:20px;
margin:15px 0;
}

.btn{
background:#0d6efd;
padding:12px 25px;
color:white;
text-decoration:none;
border-radius:5px;
}

.section{
padding:60px 20px;
max-width:1200px;
margin:auto;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:30px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 2px 10px rgba(0,0,0,.1);
}

form{
display:flex;
flex-direction:column;
gap:10px;
}

input,textarea{
padding:12px;
border:1px solid #ccc;
border-radius:5px;
}

button{
padding:12px;
background:#0d6efd;
color:white;
border:none;
border-radius:5px;
cursor:pointer;
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
</style>

</head>
<body>

<header>
<nav>
<h2>IsmaelOmar</h2>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section class="hero" id="home">
<h1>Welcome to IsmaelOmar</h1>
<p>Professional Business & Digital Platform</p>
<a href="#contact" class="btn">Get Started</a>
</section>

<section class="section" id="services">
<h2>Our Services</h2>

<div class="cards">

<div class="card">
<h3>Website Development</h3>
<p>Modern websites for businesses and brands.</p>
</div>

<div class="card">
<h3>Mobile Apps</h3>
<p>Android and web application development.</p>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Social media and online promotion services.</p>
</div>

</div>
</section>

<section class="section" id="about">
<h2>About Us</h2>
<p>
IsmaelOmar is a modern digital brand focused on
website development, online business solutions,
and technology services.
</p>
</section>

<section class="section" id="contact">
<h2>Contact Us</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

</section>

<footer>
<p>© 2026 IsmaelOmar. All Rights Reserved.</p>
</footer>

</body>
</html>

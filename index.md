<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HANZ STORE</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:linear-gradient(135deg,#000,#111,#1a1a1a);
color:white;
}

header{
text-align:center;
padding:25px;
font-size:32px;
font-weight:bold;
color:#00ffee;
text-shadow:0 0 15px #00ffee;
}

.sub{
text-align:center;
color:#aaa;
margin-bottom:20px;
}

.music-box{
text-align:center;
padding:15px;
}

.music-box button{
margin:5px;
padding:10px 18px;
border:none;
border-radius:10px;
background:#00ffee;
font-weight:bold;
cursor:pointer;
box-shadow:0 0 10px rgba(0,255,255,0.4);
}

.container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:18px;
padding:20px;
}

.card{
background:rgba(255,255,255,0.05);
border-radius:18px;
padding:15px;
text-align:center;
box-shadow:0 0 15px rgba(0,255,255,0.12);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 0 20px rgba(0,255,255,0.3);
}

.card img{
width:100%;
height:160px;
object-fit:cover;
border-radius:14px;
margin-bottom:12px;
}

.nama{
font-size:22px;
font-weight:bold;
color:#00ffee;
margin-bottom:8px;
}

.harga{
font-size:24px;
font-weight:bold;
color:#00ff88;
margin-bottom:12px;
}

.btn{
display:inline-block;
padding:10px 18px;
background:#00ffee;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:10px;
}

footer{
text-align:center;
padding:20px;
color:#888;
}
</style>
</head>
<body>

<header>🔥 HANZ STORE 🔥</header>
<div class="sub">Produk Digital Murah & Trusted</div>

<div class="music-box">
<button onclick="playSong('Strongest_spotdown.org.mp3')">🎵 Lagu 1</button>
<button onclick="playSong('Cupid_spotdown.org.mp3')">🎶 Lagu 2</button>
<button onclick="playSong('blue_spotdown.org.mp3')">🎧 Lagu 3</button>
</div>

<div class="container">

<div class="card">
<img src="foto1.jpg">
<div class="nama">PANEL PTERO</div>
<div class="harga">Rp5K</div>
<a href="https://wa.me/628531183853" class="btn">Beli</a>
</div>

<div class="card">
<img src="foto2.jpg">
<div class="nama">BOOST FOLLOWERS</div>
<div class="harga">Rp10K</div>
<a href="https://wa.me/628531183853" class="btn">Beli</a>
</div>

<div class="card">
<img src="foto3.jpg">
<div class="nama">PREMIUM APP</div>
<div class="harga">Rp15K</div>
<a href="https://wa.me/628531183853" class="btn">Beli</a>
</div>

<div class="card">
<img src="foto4.jpg">
<div class="nama">AKUN SULTAN</div>
<div class="harga">Rp25K</div>
<a href="https://wa.me/628531183853" class="btn">Beli</a>
</div>

</div>

<footer>© 2026 HANZ STORE</footer>

<audio id="player"></audio>

<script>
function playSong(file){
let audio = document.getElementById("player");
audio.src = file;
audio.play();
}
</script>

</body>
</html>

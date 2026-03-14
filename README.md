<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>GameZone - Магазин игр</title>

<style>

body{
margin:0;
font-family:Arial;
background:#0f172a;
color:white;
}

header{
background:#020617;
padding:20px;
text-align:center;
font-size:28px;
font-weight:bold;
}

nav{
background:#111827;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
color:#22c55e;
}

.container{
padding:40px;
}

.games{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:20px;
border-radius:10px;
text-align:center;
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
border-radius:10px;
}

.price{
color:#22c55e;
font-size:20px;
margin:10px 0;
}

button{
background:#22c55e;
border:none;
padding:10px 20px;
color:white;
font-size:16px;
border-radius:6px;
cursor:pointer;
}

button:hover{
background:#16a34a;
}

footer{
margin-top:40px;
background:#020617;
padding:20px;
text-align:center;
}

</style>
</head>

<body>

<header>
🎮 GameZone — Магазин игр
</header>

<nav>
<a href="#">Главная</a>
<a href="#">Игры</a>
<a href="#">Скидки</a>
<a href="#">Контакты</a>
</nav>

<div class="container">

<h2>Популярные игры</h2>

<div class="games">

<div class="card">
<img src="https://images.igdb.com/igdb/image/upload/t_cover_big/co2lbd.jpg">
<h3>Cyberpunk 2077</h3>
<div class="price">$39</div>
<button onclick="buy()">Купить</button>
</div>

<div class="card">
<img src="https://images.igdb.com/igdb/image/upload/t_cover_big/co1tmu.jpg">
<h3>GTA V</h3>
<div class="price">$19</div>
<button onclick="buy()">Купить</button>
</div>

<div class="card">
<img src="https://images.igdb.com/igdb/image/upload/t_cover_big/co1rs4.jpg">
<h3>Elden Ring</h3>
<div class="price">$49</div>
<button onclick="buy()">Купить</button>
</div>

<div class="card">
<img src="https://images.igdb.com/igdb/image/upload/t_cover_big/co2l7z.jpg">
<h3>Call of Duty</h3>
<div class="price">$59</div>
<button onclick="buy()">Купить</button>
</div>

</div>

</div>

<footer>
© 2026 GameZone Store
</footer>

<script>

function buy(){
alert("Игра добавлена в корзину!");
}

</script>

</body>
</html># levelupgameshop

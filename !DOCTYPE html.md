<!DOCTYPE html>  
<html lang="es">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Bariloche Freeride</title>  
  
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600;900&display=swap" rel="stylesheet">  
  
<style>  
* {  
  margin: 0;  
  padding: 0;  
  box-sizing: border-box;  
}  
  
body {  
  font-family: 'Montserrat', sans-serif;  
  background: #0a0a0a;  
  color: white;  
}  
  
/* NAV */  
nav {  
  position: fixed;  
  width: 100%;  
  padding: 15px 20px;  
  display: flex;  
  justify-content: space-between;  
  z-index: 1000;  
  background: rgba(0,0,0,0.4);  
  backdrop-filter: blur(10px);  
}  
  
nav h1 {  
  font-size: 1.2em;  
}  
  
nav a {  
  color: white;  
  text-decoration: none;  
  font-size: 0.9em;  
}  
  
/* HERO */  
.hero {  
  height: 100vh;  
  background: url('https://images.unsplash.com/photo-1519681393784-d120267933ba') center/cover no-repeat;  
  display: flex;  
  align-items: flex-end;  
  padding: 40px 20px;  
}  
  
.hero-content {  
  max-width: 600px;  
}  
  
.hero h2 {  
  font-size: 2.8em;  
  font-weight: 900;  
}  
  
.hero p {  
  margin: 15px 0;  
  opacity: 0.8;  
}  
  
.btn {  
  display: inline-block;  
  background: #ff3c00;  
  padding: 12px 22px;  
  border-radius: 30px;  
  color: white;  
  text-decoration: none;  
  font-weight: 600;  
}  
  
/* SECTIONS */  
section {  
  padding: 60px 20px;  
}  
  
/* CARDS */  
.cards {  
  display: grid;  
  grid-template-columns: 1fr;  
  gap: 20px;  
}  
  
.card {  
  background: #111;  
  padding: 25px;  
  border-radius: 15px;  
  transition: 0.3s;  
}  
  
.card:hover {  
  transform: translateY(-5px);  
}  
  
/* VIDEO */  
.video iframe {  
  width: 100%;  
  height: 250px;  
  border-radius: 10px;  
}  
  
/* CTA */  
.cta {  
  text-align: center;  
}  
  
.cta h2 {  
  font-size: 2em;  
  margin-bottom: 20px;  
}  
  
/* FOOTER */  
footer {  
  padding: 30px;  
  text-align: center;  
  font-size: 0.8em;  
  opacity: 0.6;  
}  
  
/* DESKTOP */  
@media (min-width: 768px) {  
  
.hero {  
  align-items: center;  
}  
  
.hero h2 {  
  font-size: 4em;  
}  
  
.cards {  
  grid-template-columns: repeat(3, 1fr);  
}  
  
.video iframe {  
  height: 400px;  
}  
  
}  
</style>  
  
</head>  
  
<body>  
  
<nav>  
  <h1>FREERIDE BRC</h1>  
  <a href="https://instagram.com/TUUSUARIO">Instagram</a>  
</nav>  
  
<div class="hero">  
  <div class="hero-content">  
    <h2>NO VENGAS A MIRAR</h2>  
    <h2>VENÍ A VIVIRLO</h2>  
    <p>Experiencias reales en Bariloche. Bike, snow y aventura.</p>  
    <a class="btn" href="https://wa.me/TUNUMERO">Reservar ahora</a>  
  </div>  
</div>  
  
<section>  
  <h2>Experiencias</h2>  
  <div class="cards">  
    <div class="card">  
      <h3>Bike</h3>  
      <p>Senderos escondidos, bajadas técnicas y vistas únicas.</p>  
    </div>  
    <div class="card">  
      <h3>Snow</h3>  
      <p>Freeride en nieve polvo lejos de las pistas.</p>  
    </div>  
    <div class="card">  
      <h3>Sunsets</h3>  
      <p>Atardeceres que no vas a olvidar nunca.</p>  
    </div>  
  </div>  
</section>  
  
<section class="video">  
  <h2>Sentilo</h2>  
  <iframe src="https://www.youtube.com/embed/Scxs7L0vhZ4" allowfullscreen></iframe>  
</section>  
  
<section class="cta">  
  <h2>¿Listo para vivir Bariloche?</h2>  
  <a class="btn" href="https://wa.me/TUNUMERO">Escribinos</a>  
</section>  
  
<footer>  
  © 2026 Freeride Bariloche  
</footer>  
  
</body>  
</html>  

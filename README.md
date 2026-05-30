<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Bistro Obiadowo | Domowe Obiady w Żorach</title>
<meta name="description" content="Domowe obiady w Żorach. Świeże składniki, duże porcje, danie dnia, na miejscu i na wynos.">
<meta name="keywords" content="obiady Żory, domowe obiady Żory, jedzenie na wynos Żory, restauracja Żory">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Poppins,sans-serif;color:#222;background:#fafafa}
header{position:fixed;top:0;width:100%;background:#fff;box-shadow:0 2px 12px rgba(0,0,0,.08);z-index:1000}
.container{width:min(1200px,92%);margin:auto}
nav{display:flex;justify-content:space-between;align-items:center;padding:18px 0}
.logo{font-size:28px;font-weight:800;color:#b22222}
nav a{text-decoration:none;color:#333;margin-left:20px}
.btn{background:#b22222;color:#fff;padding:14px 22px;border-radius:10px;text-decoration:none;font-weight:600}
.hero{min-height:100vh;background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),url('https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=1600&q=80') center/cover;display:flex;align-items:center;text-align:center;color:#fff}
.hero h1{font-size:clamp(2.5rem,5vw,4.8rem);margin-bottom:15px}
.hero p{font-size:1.2rem;max-width:800px;margin:auto}
.hero .cta{margin-top:30px}
section{padding:90px 0}
h2{text-align:center;font-size:2.3rem;margin-bottom:40px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:24px}
.card,.review,.dish{background:#fff;border-radius:16px;overflow:hidden;box-shadow:0 8px 24px rgba(0,0,0,.08)}
.card{padding:24px}
.dish img{width:100%;height:220px;object-fit:cover}
.dish div{padding:20px}
.reviews{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:24px}
.review{padding:24px}
.cta-band{background:#b22222;color:#fff;text-align:center}
.contact{display:grid;grid-template-columns:1fr 1fr;gap:30px}
footer{background:#111;color:#fff;text-align:center;padding:30px}
.badge{display:inline-block;background:#ffd54f;color:#222;padding:8px 14px;border-radius:999px;margin-bottom:20px;font-weight:700}
@media(max-width:768px){.contact{grid-template-columns:1fr} nav .links{display:none}}
</style>
</head>
<body>

<header>
<div class="container">
<nav>
<div class="logo">Bistro Obiadowo</div>
<div class="links">
<a href="#menu">Menu</a>
<a href="#opinie">Opinie</a>
<a href="#kontakt">Kontakt</a>
</div>
<a class="btn" href="tel:785486107">📞 Zamów</a>
</nav>
</div>
</header>

<section class="hero">
<div class="container">
<div class="badge">⭐ 4,7/5 • 345 opinii</div>
<h1>Domowe Obiady Jak U Mamy</h1>
<p>Świeże składniki, duże porcje i tradycyjne smaki. Na miejscu i na wynos. Idealne dla rodzin, pracowników i każdego, kto chce dobrze zjeść.</p>
<div class="cta">
<a class="btn" href="tel:785486107">Zadzwoń: 785 486 107</a>
</div>
</div>
</section>

<section>
<div class="container">
<h2>Dlaczego Klienci Wracają?</h2>
<div class="grid">
<div class="card"><h3>🍲 Domowa kuchnia</h3><p>Codziennie świeże zupy, schabowe, rolady i dania dnia.</p></div>
<div class="card"><h3>💰 Świetne ceny</h3><p>Obiady już od 20 zł.</p></div>
<div class="card"><h3>🚀 Szybka obsługa</h3><p>Na miejscu i na wynos bez długiego oczekiwania.</p></div>
<div class="card"><h3>⭐ Zaufanie klientów</h3><p>Setki pozytywnych opinii mieszkańców regionu.</p></div>
</div>
</div>
</section>

<section id="menu">
<div class="container">
<h2>Najpopularniejsze Dania</h2>
<div class="grid">
<div class="dish">
<img src="https://images.unsplash.com/photo-1514516345957-556ca7b4f83e?auto=format&fit=crop&w=900&q=80">
<div><h3>Kotlet Schabowy</h3><p>Frytki i świeża surówka.</p></div>
</div>
<div class="dish">
<img src="https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=900&q=80">
<div><h3>Rosół Domowy</h3><p>Klasyczny smak polskiej kuchni.</p></div>
</div>
<div class="dish">
<img src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=900&q=80">
<div><h3>Rolada Wieprzowa</h3><p>Śląski klasyk uwielbiany przez klientów.</p></div>
</div>
</div>
</div>
</section>

<section id="opinie">
<div class="container">
<h2>Opinie Klientów</h2>
<div class="reviews">
<div class="review">⭐⭐⭐⭐⭐<br><br>„Fest dobre jedzenie w dobrej cenie. Pyszne jedzonko.”</div>
<div class="review">⭐⭐⭐⭐⭐<br><br>„Obiad był przepyszny. Wszystko świeże i smaczne.”</div>
<div class="review">⭐⭐⭐⭐⭐<br><br>„Duże porcje, miła obsługa i bardzo dobre ceny.”</div>
</div>
</div>
</section>

<section class="cta-band">
<div class="container">
<h2>Masz Ochotę na Domowy Obiad?</h2>
<p>Przyjmujemy zamówienia telefoniczne i na wynos.</p><br>
<a class="btn" href="tel:785486107">📞 Zamów Teraz</a>
</div>
</section>

<section id="kontakt">
<div class="container">
<h2>Kontakt</h2>
<div class="contact">
<div>
<h3>Bistro Obiadowo</h3>
<p>Żołnierzy Września 42<br>44-247 Żory</p><br>
<p><strong>Telefon:</strong> 785 486 107</p><br>
<p><strong>Usługi:</strong> Na miejscu • Na wynos</p>
</div>
<div>
<iframe src="https://maps.google.com/maps?q=%C5%BBo%C5%82nierzy%20Wrze%C5%9Bnia%2042%20%C5%BBory&t=&z=15&ie=UTF8&iwloc=&output=embed" width="100%" height="320" style="border:0;border-radius:16px"></iframe>
</div>
</div>
</div>
</section>

<footer>
© 2026 Bistro Obiadowo • Strona przygotowana pod SEO i kampanie reklamowe
</footer>

</body>
</html>

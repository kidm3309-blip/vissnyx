<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Viss' Fav Skins </title>
  <style>
    :root{
      --bg:#ffffff; --text:#111; --muted:#777; --line:#eee; --accent:#000;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,Arial,sans-serif;background:var(--bg);color:var(--text)}
    a{text-decoration:none;color:inherit}
    header{position:sticky;top:0;background:#fff;border-bottom:1px solid var(--line);z-index:10}
    .nav{max-width:1200px;margin:auto;display:flex;align-items:center;gap:20px;padding:14px 16px}
    .brand{font-weight:800;letter-spacing:2px}
    .nav a{font-size:14px;color:#333}
    .spacer{flex:1}
    .hero{max-width:1200px;margin:40px auto;padding:0 16px;display:grid;grid-template-columns:1.2fr .8fr;gap:30px}
    .hero-card{border-radius:18px;overflow:hidden;box-shadow:0 20px 60px rgba(0,0,0,.08)}
    .hero img{width:100%;height:100%;object-fit:cover}
    .hero-copy{padding:36px}
    .hero h1{font-size:42px;margin:0 0 10px}
    .hero p{color:var(--muted);margin:0 0 20px}
    .btn{display:inline-block;padding:12px 18px;border-radius:12px;background:#000;color:#fff;font-size:14px}
    .section{max-width:1200px;margin:60px auto;padding:0 16px}
    .section h2{font-size:24px;margin:0 0 20px}
    .grid{display:grid;grid-template-columns:repeat(4,1fr);gap:20px}
    .card{border:1px solid var(--line);border-radius:16px;overflow:hidden}
    .card img{width:100%;height:260px;object-fit:cover;background:#f5f5f5}
    .card .info{padding:12px}
    .name{font-size:14px;margin:0 0 6px}
    .price{font-weight:700}
    footer{border-top:1px solid var(--line);margin-top:80px}
    .foot{max-width:1200px;margin:auto;padding:24px 16px;color:#666;font-size:13px}
    @media(max-width:900px){.hero{grid-template-columns:1fr}.grid{grid-template-columns:repeat(2,1fr)}}
    @media(max-width:500px){.grid{grid-template-columns:1fr}.hero h1{font-size:32px}}
  </style>
</head>
<body>
  <header>
    <div class="nav">
      <div class="brand">U CAN CALL ME VISS</div>
      <a href="#">ИЙМ</a><a href="#">БАЙХАД</a><a href="#">БОЛОХ УУ</a><a href="#">БАГШАА?</a>
      <div class="spacer"></div>
      <a href="#">Search</a><a href="#">Cart</a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="hero-card">
        <img src="C:\Users\User\Downloads\arima.jpg" alt="hero" />
      </div>
      <div class="hero-card hero-copy">
        <h1>VISS EFFECTS</h1>
        <p>KENJIZX. EVELYNN. REIKO. DM.</p>
        <a class="btn" href="#products">А. Гарьд-Эрдэнэ</a>
      </div>
    </section>

    <section id="products" class="section">
      <h2>My Favourite Skins</h2>
      <div class="grid">
        <article class="card">
          <img src="C:\Users\User\Downloads\wild lotus.png"/>
          <div class="info"><p class="name">Wild Lotus</p><div class="price">$16,643.59</div></div>
        </article>
        <article class="card">
          <img src="C:\Users\User\Downloads\dragon lore.png"/>
          <div class="info"><p class="name">Dragon Lore</p><div class="price">$496,614</div></div>
        </article>
        <article class="card">
          <img src="C:\Users\User\Downloads\ruby butterfly.png" />
          <div class="info"><p class="name">Ruby</p><div class="price">$13000</div></div>
        </article>
        <article class="card">
          <img src="C:\Users\User\Downloads\hadge maze.png" />
          <div class="info"><p class="name">Hedge maze</p><div class="price">$29,906.80</div></div>
        </article>
      </div>
    </section>
  </main>

  <footer>
    <div class="foot">© 2025 Viss from "EVEVERSE" · Static demo (HTML/CSS)</div>
  </footer>
</body>
</html>

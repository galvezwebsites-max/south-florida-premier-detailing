<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>South Florida Premier Detailing</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --dark:#05060a;
      --blue:#1fd6ff;
      --pink:#ff3fb4;
      --white:#ffffff;
      --soft:#111318;
    }

    * { box-sizing:border-box; margin:0; padding:0; font-family:'Inter', sans-serif; }

    body {
      background:var(--dark);
      color:var(--white);
      line-height:1.6;
    }

    header {
      background:rgba(0,0,0,0.85);
      padding:14px 24px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .logo { height:60px; }

    nav a {
      color:var(--white);
      margin-left:22px;
      text-decoration:none;
    }

    .btn {
      background:linear-gradient(135deg,var(--blue),var(--pink));
      color:black;
      padding:13px 24px;
      border-radius:40px;
      text-decoration:none;
      font-weight:700;
      display:inline-block;
      margin:6px;
    }

    .hero {
      padding:120px 20px;
      text-align:center;
      background: radial-gradient(circle at top, rgba(31,214,255,0.15), transparent 50%),
                  radial-gradient(circle at bottom, rgba(255,63,180,0.15), transparent 50%),
                  var(--dark);
    }

    .hero h1 {
      font-size:46px;
      margin-bottom:16px;
      background:linear-gradient(90deg,var(--blue),var(--pink));
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
    }

    section { padding:80px 20px; max-width:1100px; margin:auto; }

    .grid {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
      gap:24px;
    }

    .card {
      background:var(--soft);
      padding:28px;
      border-radius:20px;
    }

    .price {
      font-size:26px;
      font-weight:800;
      margin:12px 0;
      color:var(--blue);
    }

    footer {
      background:#000;
      color:#aaa;
      padding:30px;
      text-align:center;
    }

    .sticky-buttons {
      position:fixed;
      bottom:15px;
      right:15px;
      display:flex;
      flex-direction:column;
      gap:10px;
    }

    .sticky-buttons a {
      background:linear-gradient(135deg,var(--blue),var(--pink));
      padding:14px 18px;
      border-radius:40px;
      font-weight:700;
      color:black;
      text-decoration:none;
    }
  </style>
</head>

<body>

<header>
  <img src="logo.png" class="logo">
  <nav>
    <a href="#services">Services</a>
    <a href="#pricing">Pricing</a>
    <a href="#areas">Areas</a>
  </nav>
</header>

<section class="hero">
  <h1>Luxury Mobile Auto Detailing</h1>
  <p>We come to you. Premium results. Showroom shine.</p>

  <a class="btn" href="tel:1234567890">Call Now</a>
  <a class="btn" href="sms:1234567890">Text Us</a>
</section>

<section id="services">
  <h2>Services</h2>
  <div class="grid">
    <div class="card">Interior Deep Cleaning</div>
    <div class="card">Exterior Wash & Wax</div>
    <div class="card">Paint Correction</div>
    <div class="card">Ceramic Coating</div>
  </div>
</section>

<section id="pricing">
  <h2>Pricing</h2>
  <div class="grid">
    <div class="card">
      <h3>Basic</h3>
      <div class="price">$99+</div>
    </div>
    <div class="card">
      <h3>Premium</h3>
      <div class="price">$199+</div>
    </div>
    <div class="card">
      <h3>Elite</h3>
      <div class="price">$299+</div>
    </div>
  </div>
</section>

<section id="areas">
  <h2>Service Areas</h2>
  <p>Miami • Fort Lauderdale • Boca Raton • West Palm Beach</p>
</section>

<footer>
  © 2026 South Florida Premier Detailing
</footer>

<div class="sticky-buttons">
  <a href="tel:1234567890">Call</a>
  <a href="sms:1234567890">Text</a>
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>South Florida Premier Detailing</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --dark:#05060a;
      --blue:#1fd6ff;
      --pink:#ff3fb4;
      --white:#ffffff;
      --soft:#111318;
    }

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Inter',sans-serif;
      scroll-behavior:smooth;
    }

    body{
      background:var(--dark);
      color:var(--white);
      line-height:1.6;
    }

    header{
      position:sticky;
      top:0;
      background:#000;


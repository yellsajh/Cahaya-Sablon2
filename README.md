<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Cahaya Sablon - Toko sablon baju kekinian dengan layanan sablon manual, digital, dan DTG satuan. Bisa custom desain kaos sendiri!">
  <meta name="author" content="Cahaya Sablon">
  <meta name="keywords" content="sablon kaos, toko sablon, custom baju, sablon dtg, sablon digital, sablon manual">
  <title>Cahaya Sablon - Toko Sablon Kekinian</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    :root {
      --primary: #6366f1;
      --secondary: #ec4899;
      --bg: #f9f9ff;
      --text: #333;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: var(--bg);
      color: var(--text);
      scroll-behavior: smooth;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    nav {
      background: white;
      position: sticky;
      top: 0;
      z-index: 999;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 14px 24px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    nav h1 {
      color: var(--primary);
      font-size: 1.5rem;
    }

    nav .sosmed a {
      margin-left: 15px;
      color: var(--primary);
      font-size: 1.2rem;
      transition: 0.3s;
    }

    nav .sosmed a:hover {
      color: var(--secondary);
    }

    header {
      background: linear-gradient(135deg, var(--secondary), var(--primary));
      color: white;
      text-align: center;
      padding: 100px 20px 80px;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      background: white;
      color: var(--primary);
      padding: 12px 24px;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: var(--secondary);
      color: white;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 30px;
      color: var(--primary);
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.06);
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card i {
      font-size: 2rem;
      margin-bottom: 12px;
      color: var(--secondary);
    }

    .cta {
      background: var(--primary);
      color: white;
      text-align: center;
      padding: 60px 20px;
      border-radius: 12px;
    }

    .cta h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <h1>Cahaya Sablon</h1>
    <div class="sosmed">
      <a href="https://instagram.com/cahayasablon" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://wa.me/6281234567890" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>
  </nav>

  <!-- Hero Section -->
  <header>
    <h1>Bikin Kaos, Bebas Ekspresi!</h1>
    <p>Desain sesukamu, sablon dengan kualitas tinggi & harga bersahabat.</p>
    <a href="#layanan" class="btn">Lihat Layanan Kami</a>
  </header>

  <!-- Layanan -->
  <section id="layanan">
    <h2 class="section-title">Layanan Cahaya Sablon</h2>
    <div class="card-grid">
      <div class="card">
        <i class="fas fa-paint-brush"></i>
        <h3>Sablon Manual</h3>
        <p>Cocok untuk komunitas dan produksi massal, warna solid & awet.</p>
      </div>
      <div class="card">
        <i class="fas fa-print"></i>
        <h3>Digital Printing</h3>
        <p>Cetak cepat, hasil tajam, cocok untuk desain full color.</p>
      </div>
      <div class="card">
        <i class="fas fa-tshirt"></i>
        <h3>DTG Satuan</h3>
        <p>Tanpa minimum order, langsung print ke baju dengan hasil premium.</p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta">
    <h2>Yuk, Mulai Desain Kaosmu Hari Ini!</h2>
    <a href="https://wa.me/6281234567890" class="btn">Hubungi via WhatsApp</a>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Cahaya Sablon. All rights reserved. <br>
    IG: <a href="https://instagram.com/cahayasablon" target="_blank">@cahayasablon</a>
  </footer>

</body>
</html>

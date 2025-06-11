<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TK Latifah</title>
  <link href="https://fonts.googleapis.com/css2?family=Baloo+2&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Baloo 2', cursive;
      background: #fff8f0;
      margin: 0;
      padding: 0;
    }
    header {
      background: linear-gradient(90deg, #ffb703, #f77f00);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
    }
    h1, h2 {
      margin: 0 0 10px;
    }
    .visi-misi {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }
    .box {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      flex: 1 1 250px;
      padding: 20px;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .box:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }
    .gallery {
      display: flex;
      overflow-x: auto;
      gap: 10px;
      margin-top: 20px;
    }
    .gallery img {
      height: 200px;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #023047;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .button {
      display: inline-block;
      background: #fb8500;
      color: white;
      padding: 10px 20px;
      margin-top: 20px;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .button:hover {
      background: #ff6d00;
    }
  </style>
</head>
<body>
  <header>
    <h1>TK Latifah</h1>
    <p>"Cerdas, Ceria, Berakhlak Mulia"</p>
    <a href="#kontak" class="button">Hubungi Kami</a>
  </header>

  <section>
    <h2>Visi</h2>
    <p>Membentuk anak yang cerdas, ceria, dan berakhlak mulia.</p>

    <h2>Misi</h2>
    <div class="visi-misi">
      <div class="box">Pembelajaran aktif dan menyenangkan.</div>
      <div class="box">Penanaman nilai-nilai agama dan karakter.</div>
      <div class="box">Pengembangan potensi melalui permainan edukatif.</div>
    </div>
  </section>

  <section>
    <h2>Galeri Kegiatan</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Kegiatan+1" alt="Kegiatan 1">
      <img src="https://via.placeholder.com/300x200?text=Kegiatan+2" alt="Kegiatan 2">
      <img src="https://via.placeholder.com/300x200?text=Kegiatan+3" alt="Kegiatan 3">
    </div>
  </section>

  <section id="kontak">
    <h2>Kontak Kami</h2>
    <p>📍 Jl. Rokan, Desa Buluapo, Kec. Pinggir</p>
    <p>📞 0813‑6510‑5029 | ✉️ tk.latifah01@gmail.com</p>
    <iframe src="https://www.google.com/maps?q=Pinggir,+Riau&output=embed" width="100%" height="250" style="border:0; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" allowfullscreen="" loading="lazy"></iframe>
  </section>

  <footer>
    <p>&copy; 2025 TK Latifah. All rights reserved.</p>
  </footer>
</body>
</html>

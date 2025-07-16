# genzia-website
website genzia academy
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Genzia Learn & Play</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Fredoka One', cursive;
      margin: 0;
      background: #F0F8FF;
      color: #333;
    }
    header {
      background-color: #FFB703;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #8ECAE6;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
     #C3E8F2;
      color: white;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }
    .feature-box {
      background: white;
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .kelas-section {
      background: #ffffff;
      padding: 40px;
    }
    .kelas-section h2 {
      text-align: center;
      color: #023047;
    }
    .kelas-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .kelas-box {
      background-color: #FFD166;
      border-radius: 16px;
      padding: 20px;
      text-align: center;
      color: #333;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }
    .footer {
      background: #023047;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <img src="https://cdn-icons-png.flaticon.com/512/1077/1077042.png" alt="Logo Genzia" style="width: 100px; display: block; margin: 0 auto 10px auto;">
    <h1>Genzia Learn & Play</h1>
    <p>Belajar jadi seru untuk anak-anak generasi Alpha & Beta!</p>
  </header>

  <nav>
    <a href="#kelas">Kelas</a>
    <a href="#fitur">Fitur</a>
    <a href="#orangtua">Parent Zone</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <section class="hero">
    <img src="https://cdn-icons-png.flaticon.com/512/4264/4264746.png" alt="Karakter Genzia Lucu" style="width: 150px; margin-bottom: 20px;">
    <h2>Gabung dan mulai petualangan belajarmu hari ini!</h2>
    <p>Temukan kelas interaktif, mini games edukatif, dan banyak fitur seru lainnya 🎉</p>
  </section>

  <section class="kelas-section" id="kelas">
    <h2>Program Kelas di Genzia</h2>
    <div class="kelas-list">
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/5231/5231019.png" alt="Karakter Mentari" style="width: 80px; margin-bottom: 10px;">
        <h3>Kelas Mentari</h3>
        <p>Untuk SD kelas 1-3. Fokus pada literasi dasar, matematika, dan kreativitas.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/5231/5231066.png" alt="Karakter Gemilang" style="width: 80px; margin-bottom: 10px;">
        <h3>Kelas Gemilang</h3>
        <p>Untuk SD kelas 4-6. Fokus pada penguatan logika, penalaran, dan pemecahan masalah.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/4184/4184460.png" alt="Karakter Mengaji" style="width: 80px; margin-bottom: 10px;">
        <h3>Program Mengaji & Tata Krama</h3>
        <p>Belajar membaca Al-Qur'an dan menanamkan nilai adab serta etika sehari-hari.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/4481/4481247.png" alt="Karakter Penalaran" style="width: 80px; margin-bottom: 10px;">
        <h3>Kelas Penalaran</h3>
        <p>Melatih kemampuan berpikir kritis, logika, dan pemahaman analitis sejak dini.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/6513/6513028.png" alt="Karakter Bahasa" style="width: 80px; margin-bottom: 10px;">
        <h3>Kelas Belajar Bahasa</h3>
        <p>Belajar bahasa Indonesia, Inggris, Korea, dan China dasar dengan cara menyenangkan.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/5900/5900204.png" alt="Karakter Privat" style="width: 80px; margin-bottom: 10px;">
        <h3>Kelas Privat</h3>
        <p>Bimbingan belajar eksklusif 1-on-1 sesuai kebutuhan anak. Bisa online atau offline.</p>
      </div>
      <div class="kelas-box">
        <img src="https://cdn-icons-png.flaticon.com/512/5900/5900201.png" alt="Karakter Soft Skill" style="width: 80px; margin-bottom: 10px;">
        <h3>Asah Soft Skill</h3>
        <p>Latihan komunikasi, kerja tim, percaya diri, dan public speaking untuk anak SD.</p>
      </div>
    </div>
  </section>

  <section class="features" id="fitur">
    <div class="feature-box">
      <h3>Mini Games Edukatif</h3>
      <p>Belajar lewat permainan seru yang mendidik sesuai jenjang usia anak-anak.</p>
    </div>
    <div class="feature-box">
      <h3>Kelas Interaktif</h3>
      <p>Ikuti kelas daring atau luring dengan tutor yang menyenangkan dan profesional.</p>
    </div>
    <div class="feature-box">
      <h3>Progress Anak</h3>
      <p>Orang tua dapat memantau perkembangan akademik dan minat anak secara real-time.</p>
    </div>
    <div class="feature-box">
      <h3>Reward & Avatar</h3>
      <p>Berikan semangat pada anak dengan sistem penghargaan dan personalisasi karakter.</p>
    </div>
  </section>

  <section class="footer" id="kontak">
    <p>&copy; 2025 Genzia | Rumah Belajar Anak Cerdas</p>
    <p>Kontak: info@genzia.id | IG: @genzia.learn | Email : genziaclasskids25@gmail.com</p>
  </section>
</body>
</html>


<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Link Sosial Saya</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #f5f7fa, #e4ecf7);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.card {
  background: #ffffff;
  padding: 30px 25px;
  border-radius: 20px;
  width: 320px;
  text-align: center;
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  transition: 0.3s;
}
.card:hover {
  transform: translateY(-5px);
}
.profile {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin: 0 auto 15px;
  background: #ddd;
  background-size: cover;
  background-position: center;
}
h2 {
  margin: 10px 0 5px;
  font-weight: 600;
}
p {
  margin: 0 0 20px;
  font-size: 14px;
  color: #666;
}
.link {
  display: block;
  margin: 10px 0;
  padding: 12px;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 500;
  color: white;
  transition: 0.2s;
}
.link:hover {
  opacity: 0.85;
}
.wa { background: #25D366; }
.shopee { background: #FF5722; }
footer {
  margin-top: 15px;
  font-size: 12px;
  color: #aaa;
}
.profile-container {
  display: flex;
  justify-content: center;
}
.profile-img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid white;
  box-shadow: 0 5px 15px rgba(0,0,0,0.15);
  transition: 0.3s;
}
.profile-img:hover {
  transform: scale(1.05);
 }
  </style>
</head>
<body>
  <div class="card"><!-- Ganti URL foto di bawah -->
    <div class="profile-container">
  <img src="Sajam.jpg" alt="Foto Profil" class="profile-img">
</div>
<h2>RUANG SAJAM</h2>
<p>Selamat datang di website kita</p>

<!-- Ganti link di bawah -->
<a class="link wa" href="https://wa.me/6287823546360" target="_blank">WhatsApp</a>
<a class="link shopee" href="https://s.shopee.co.id/1LbV8fGDlR" target="_blank">Shopee</a>

<footer>© 2026</footer>

  </div>
</body>


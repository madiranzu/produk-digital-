# produk-digital-
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PRODUK DIGITAL BY MADI</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #dbeafe, #f5f3ff);
      animation: fadeIn 1s ease-in-out;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 30px;
      color: #1e3a8a;
    }

    .product-card {
      background: #ffffff;
      margin: 20px auto;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      max-width: 600px;
      opacity: 0;
      transform: translateY(30px);
      animation: slideUp 0.8s ease forwards;
    }

    .product-card:nth-child(2) { animation-delay: 0.2s; }
    .product-card:nth-child(3) { animation-delay: 0.4s; }
    .product-card:nth-child(4) { animation-delay: 0.6s; }

    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
    }

    .product-card h2 {
      color: #1e40af;
      margin-top: 0;
    }

    .product-card p {
      color: #555;
    }

    .buy-button, .wa-button {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 25px;
      background: #1e40af;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: 600;
      transition: background 0.3s ease;
    }

    .buy-button:hover, .wa-button:hover {
      background: #1e3a8a;
    }

    .wa-support {
      margin-top: 50px;
    }

    @keyframes slideUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>PRODUK DIGITAL BY MADI</h1>

    <div class="product-card">
      <h2>Jago Telegram Dalam 1 Hari</h2>
      <p>Pelajari cara maksimalkan Telegram untuk bisnis dan komunikasi hanya dalam 1 hari.</p>
      <a class="buy-button" href="http://lynk.id/produklengkap999/37moj17498k9/checkout" target="_blank">Beli Sekarang</a>
    </div>

    <div class="product-card">
      <h2>E-BOOK Jago Jualan di WhatsApp</h2>
      <p>Cara jualan laris manis di WhatsApp dengan strategi terbukti. Cocok untuk pemula!</p>
      <a class="buy-button" href="http://lynk.id/produklengkap999/48mql2r3xg07/checkout" target="_blank">Beli Sekarang</a>
    </div>

    <div class="product-card">
      <h2>Jago Edukasi dan Promosi</h2>
      <p>Strategi edukasi & promosi yang powerful untuk tingkatkan penjualan dan trust audience.</p>
      <a class="buy-button" href="http://lynk.id/produklengkap999/4g35o9onxm6y/checkout" target="_blank">Beli Sekarang</a>
    </div>

    <div class="wa-support">
      <p>Jika ada kendala dalam membeli, silakan hubungi kami lewat WhatsApp:</p>
      <a class="wa-button" href="https://wa.me/6285752647611" target="_blank">Hubungi via WhatsApp</a>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>İndirme Sayfası</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 50px;
      background-color: #f0f0f0;
    }
    .box {
      background: white;
      padding: 30px;
      border-radius: 15px;
      display: inline-block;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    button, a.button {
      background-color: #ff0000;
      color: white;
      padding: 15px 25px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-size: 18px;
      text-decoration: none;
      margin: 10px;
    }
    #indir {
      display: none;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="box">
    <h2>📢 Dosyayı indirmek için YouTube kanalıma abone ol!</h2>
    <a class="button" href="https://www.youtube.com/@SeninKanalAdin" target="_blank">➤ Kanala Abone Ol</a>
    <br>
    <button onclick="document.getElementById('indir').style.display='block'">✅ Abone Oldum</button>
    <div id="indir">
      <h3>🔓 Dosya Açıldı!</h3>
      <a class="button" href="https://drive.google.com/dosya-linkin" target="_blank">📥 Dosyayı İndir</a>
    </div>
  </div>
</body>
</html>

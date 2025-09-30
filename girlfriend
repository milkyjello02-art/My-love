<?php
date_default_timezone_set('Asia/Jakarta');
?>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Girlfriend Day ❤️</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Comic Sans MS", cursive, sans-serif;
      background: linear-gradient(120deg, #ffdde1, #ee9ca7);
      overflow: hidden;
      color: #fff;
      text-align: center;
    }
    h1 {
      margin-top: 40px;
      font-size: 2.5em;
      animation: fadeIn 2s ease-in-out;
    }
    .message {
      margin: 20px auto;
      max-width: 600px;
      padding: 20px;
      background: rgba(255,255,255,0.2);
      border-radius: 20px;
      font-size: 1.2em;
      line-height: 1.6em;
      animation: fadeInUp 2s ease-in-out;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #ff4e50;
      border-radius: 30px;
      color: #fff;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover {
      background: #fc913a;
      transform: scale(1.1);
    }
    /* Animasi love */
    .heart {
      position: fixed;
      width: 30px;
      height: 30px;
      background: url('love.png') no-repeat center/contain;
      animation: float 6s linear infinite;
    }
    @keyframes float {
      0% { transform: translateY(100vh) scale(0.5); opacity: 1; }
      100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(50px);}
      to {opacity: 1; transform: translateY(0);}
    }
    /* Efek typing */
    .typing {
      display: inline-block;
      border-right: 2px solid #fff;
      white-space: nowrap;
      overflow: hidden;
      animation: typing 4s steps(40,end), blink 0.75s step-end infinite;
    }
    @keyframes typing {
      from {width: 0;}
      to {width: 100%;}
    }
    @keyframes blink {
      50% {border-color: transparent;}
    }
  </style>
</head>
<body>

  <h1>Happy Girlfriend Day ❤️</h1>

  <div class="message">
    <p class="typing">Hai Sayang, aku punya pesan spesial buat kamu...</p>
    <p>Terima kasih sudah selalu ada, menjadi bagian terindah dalam hidupku 💕</p>
    <p>Aku sayang kamu, hari ini dan selamanya 🥰</p>
  </div>

  <a href="https://wa.me/6285xxxx" class="btn">Balas ke WhatsApp 💌</a>

  <!-- Musik otomatis -->
  <audio autoplay loop>
    <source src="musik.mp3" type="audio/mpeg">
  </audio>

  <!-- Script animasi love random -->
  <script>
    function createHeart() {
      const heart = document.createElement("div");
      heart.className = "heart";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (4 + Math.random() * 3) + "s";
      document.body.appendChild(heart);
      setTimeout(() => { heart.remove(); }, 7000);
    }
    setInterval(createHeart, 500);
  </script>

</body>
</html>

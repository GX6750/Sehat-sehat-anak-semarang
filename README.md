<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Goodluck di Semarang!</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      font-family: 'Pacifico', cursive;
      color: #fff;
      text-align: center;
      overflow: hidden;
      position: relative;
    }
    .text-container {
      position: relative;
      z-index: 3; /* Teks di layer paling atas */
      background: rgba(255, 255, 255, 0.3); /* Latar belakang semi-transparan untuk teks */
      padding: 20px;
      border-radius: 10px;
    }
    h1 {
      font-size: 4rem;
      animation: fadeIn 2s ease-in-out;
      margin: 0;
    }
    h2 {
      font-size: 2.5rem;
      animation: fadeIn 3s ease-in-out;
      margin-top: 20px;
    }
    .floating-photo {
      position: absolute;
      width: 100px; /* Ukuran foto */
      height: auto;
      animation: float 2s infinite ease-in-out, bounce 3.33s infinite linear; /* 3x lebih cepat */
      z-index: 1; /* Foto di layer bawah */
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
    @keyframes bounce {
      0%, 100% { transform: translateX(0); }
      50% { transform: translateX(20px); }
    }
  </style>
</head>
<body>
  <div class="text-container">
    <h1>Semangat dan Goodluck di Semarang! 🌸</h1>
    <h2>Stay safe, bel! 💖</h2>
  </div>

  <!-- Foto-foto Anda -->
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/IMG_9650-removebg-preview.png" class="floating-photo" style="top: 10%; left: 5%; animation-delay: 0s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/IMG_9325-removebg-preview.png" class="floating-photo" style="top: 20%; right: 10%; animation-delay: 1s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/F10AD7FE-CC2B-4530-8776-FE60812EEFF3-removebg-preview.png" class="floating-photo" style="bottom: 15%; left: 20%; animation-delay: 2s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/692A6920-3A88-44C4-A6C2-E99EE220BF79-removebg-preview.png" class="floating-photo" style="bottom: 5%; right: 5%; animation-delay: 3s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/553159e8-b9e2-45ac-9008-c9ae6c420f54-removebg-preview.png" class="floating-photo" style="top: 30%; left: 15%; animation-delay: 4s;">
  <!-- Duplikat foto-foto di atas hingga total 10 foto -->
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/IMG_9650-removebg-preview.png" class="floating-photo" style="top: 40%; right: 20%; animation-delay: 5s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/IMG_9325-removebg-preview.png" class="floating-photo" style="bottom: 30%; left: 10%; animation-delay: 6s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/F10AD7FE-CC2B-4530-8776-FE60812EEFF3-removebg-preview.png" class="floating-photo" style="top: 50%; right: 5%; animation-delay: 7s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/692A6920-3A88-44C4-A6C2-E99EE220BF79-removebg-preview.png" class="floating-photo" style="bottom: 40%; left: 25%; animation-delay: 8s;">
  <img src="https://github.com/GX6750/Sehat-sehat-anak-semarang/raw/8064bd9ccf05d9f328f39b0c14f7a7a370dded70/553159e8-b9e2-45ac-9008-c9ae6c420f54-removebg-preview.png" class="floating-photo" style="top: 60%; right: 15%; animation-delay: 9s;">

  <!-- Audio untuk efek suara -->
  <audio id="sound-effect" src="https://assets.mixkit.co/active_storage/sfx/3007/3007-preview.mp3" preload="auto"></audio>

  <script>
    // Memainkan efek suara saat teks muncul
    document.addEventListener('DOMContentLoaded', function() {
      const soundEffect = document.getElementById('sound-effect');
      soundEffect.play();
    });
  </script>
</body>
</html>

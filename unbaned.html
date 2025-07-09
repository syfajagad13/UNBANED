<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ARWAB 😈 - Banding WhatsApp</title>
  <style>
    body {
      margin: 0;
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 20px;
      text-align: center;
    }
    h1 {
      background: linear-gradient(45deg, red, black);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    input, button {
      padding: 10px;
      margin: 10px 0;
      width: 260px;
      border-radius: 5px;
      border: 1px solid #444;
      background-color: #111;
      color: #fff;
      font-size: 1rem;
    }
    button {
      background-color: red;
      cursor: pointer;
    }
    #formBanding, #processText, #loadingBar, #riwayatContainer {
      display: none;
    }
    #loadingBar {
      width: 80%;
      height: 20px;
      background-color: #222;
      border-radius: 10px;
      overflow: hidden;
      margin-top: 10px;
    }
    #progress {
      height: 100%;
      width: 0%;
      background-color: limegreen;
      transition: width 1s;
    }
    .img-top {
      width: 200px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 0 15px red;
    }
    .riwayat-title {
      margin-top: 40px;
      color: #ff5555;
      font-weight: bold;
      font-size: 1.3rem;
    }
    .riwayat-list {
      margin-top: 10px;
      color: #ccc;
      font-size: 1rem;
    }
    .riwayat-item {
      margin-bottom: 5px;
      background-color: #111;
      padding: 5px 10px;
      border-radius: 5px;
      border-left: 3px solid red;
    }
  </style>
</head>
<body>

  <!-- Halaman Login -->
  <div id="loginPage">
    <img src="https://i.postimg.cc/HWPcgkxJ/images-1.jpg" alt="Gambar Login" class="img-top">
    <h1>ARWAB 😈</h1>
    <input type="text" id="username" placeholder="Username">
    <input type="password" id="password" placeholder="Password">
    <button onclick="login()">Login</button>
  </div>

  <!-- Halaman Banding -->
  <div id="mainPage" style="display:none;">
    <h1>Form Banding WhatsApp</h1>
    <form id="formBanding" action="https://formspree.io/f/mnnvgrrj" method="POST">
      <input type="text" id="phoneInput" name="Nomor WhatsApp" placeholder="Masukkan nomor WhatsApp diawali +62" required maxlength="16">
      <button type="button" onclick="mulaiBanding()">Kirim Banding</button>
    </form>

    <div id="processText">MOHON DI TUNGGU, MASIH DALAM PROSES BANDING OLEH PIHAK WHATSAPP...</div>
    <div id="loadingBar">
      <div id="progress"></div>
    </div>

    <!-- Riwayat Banding -->
    <div id="riwayatContainer">
      <div class="riwayat-title">📜 Riwayat Banding</div>
      <div id="riwayatList" class="riwayat-list"></div>
    </div>
  </div>

  <script>
    function login() {
      const user = document.getElementById('username').value.trim();
      const pass = document.getElementById('password').value.trim();
      if (user && pass) {
        document.getElementById('loginPage').style.display = 'none';
        document.getElementById('mainPage').style.display = 'block';
        document.getElementById('formBanding').style.display = 'block';
        tampilkanRiwayat();
      } else {
        alert('Isi username SAMA password NYA ANJING 🤬!');
      }
    }

    function mulaiBanding() {
      const phone = document.getElementById('phoneInput').value.trim();
      if (!phone.startsWith('+62') || phone.length < 13) {
        alert('Nomor harus dimulai dengan +62 dan minimal 13 karakter anjir 🙂.');
        return;
      }

      // Simpan ke localStorage sebagai riwayat
      simpanRiwayat(phone);

      // Sembunyikan form, tampilkan loading
      document.getElementById('formBanding').style.display = 'none';
      document.getElementById('processText').style.display = 'block';
      document.getElementById('loadingBar').style.display = 'block';
      document.getElementById('riwayatContainer').style.display = 'none';

      let percent = 0;
      const interval = setInterval(() => {
        percent++;
        document.getElementById('progress').style.width = percent + '%';
        if (percent >= 100) {
          clearInterval(interval);
          document.getElementById('processText').textContent = '✅ Banding telah selesai dikirim!';
          setTimeout(() => {
            document.getElementById('formBanding').submit();
          }, 1000);
        }
      }, 600); // 60 detik
    }

    function simpanRiwayat(phone) {
      let data = JSON.parse(localStorage.getItem('riwayatBanding')) || [];
      data.unshift(phone);
      localStorage.setItem('riwayatBanding', JSON.stringify(data));
    }

    function tampilkanRiwayat() {
      const data = JSON.parse(localStorage.getItem('riwayatBanding')) || [];
      const list = document.getElementById('riwayatList');
      list.innerHTML = '';
      if (data.length > 0) {
        document.getElementById('riwayatContainer').style.display = 'block';
        data.forEach((item, index) => {
          const div = document.createElement('div');
          div.className = 'riwayat-item';
          div.textContent = `${index + 1}. ${item}`;
          list.appendChild(div);
        });
      }
    }
  </script>

</body>
</html>

<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>💌 Happy Birthday พี่สาว 💌</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Prompt:wght@400;600&display=swap');

    body {
      font-family: 'Prompt', sans-serif;
      background: linear-gradient(135deg, #ffe6f2, #e6ccff);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      text-align: center;
      padding: 20px;
      flex-direction: column;
    }

    .envelope {
      background: #fff0f6;
      border-radius: 20px;
      padding: 30px;
      max-width: 400px;
      box-shadow: 0 6px 15px rgba(255, 105, 180, 0.3);
    }

    h2 {
      color: #d63384;
      margin-bottom: 15px;
    }

    textarea {
      width: 100%;
      height: 150px;
      font-size: 16px;
      border-radius: 12px;
      border: 2px solid #ffb3d9;
      padding: 10px;
      resize: none;
      outline: none;
      background: #fff0f6;
      color: #d63384;
      text-align: center;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="envelope">
    <h2>💌 Happy Birthday พี่สาวที่น่ารัก 💌</h2>
    <textarea readonly>สุขสันต์วันเกิดนะคะ 🎂🎈
ขอให้มีความสุขมาก ๆ สุขภาพแข็งแรง
และสมหวังทุกประการ!</textarea>
    <p style="color:#d63384; font-size:14px; margin-top:10px;">*แตะหน้าจอเพื่อเปิดเพลง 🎶</p>
  </div>

  <iframe id="yt-player"
    width="0" height="0"
    src="https://www.youtube.com/embed/EjtxTX_VjxE?autoplay=1&loop=1&playlist=EjtxTX_VjxE&mute=1&playsinline=1"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen>
  </iframe>

  <script>
    // เปิดเพลงเต็มเสียงเมื่อผู้ใช้แตะหน้าจอครั้งแรก
    document.body.addEventListener("click", function() {
      var yt = document.getElementById("yt-player");
      yt.src = "https://www.youtube.com/embed/EjtxTX_VjxE?autoplay=1&loop=1&playlist=EjtxTX_VjxE&playsinline=1";
    }, { once: true });
  </script>

</body>
</html>

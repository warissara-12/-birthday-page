# birthday-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🎂 Happy Birthday to Pon 🎉</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(to right, #ffecd2, #fcb69f);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding-top: 100px;
    }
    .birthday-box {
      background-color: #fff0f6;
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      animation: fadeIn 2s ease-in-out;
    }
    h1 {
      font-size: 3rem;
      color: #e91e63;
    }
    h2 {
      color: #880e4f;
      margin-top: 20px;
    }
    .cake {
      font-size: 5rem;
      animation: float 2s infinite ease-in-out;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>

<div class="container">
  <div class="birthday-box mx-auto">
    <img src="S__8626179.jpg"  width="150">
    <div class="cake">🎂</div>
    <h1>Happy Birthday!</h1>
    <h2>Have a wonderful day, <span id="name">Preyarat</span>🎉</h2>
    <p class="mt-3 text-muted">เบิร์ดเดย์นะไอ้อ้วน ปีนี้ก็25แล้วแก่ละๆ5555555555 ดรีมขอให้ป้อนมีความสุขมากๆ ยิ้มเยอะๆ ขอให้โลกใจดีกับป้อนนะ ตั้งใจทำให้เลยนะเนี่ยยยย5555ครั้งแรกๆมันอาจจะไม่ค่อยสวยแต่ก็นะ🎁🤍🤏🏼</p>
  </div>
</div>

</body>
</html>

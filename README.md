# UpulMinerBot
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UpulMinerBot</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: linear-gradient(135deg, #1e1e2f, #2c3e50);
      color: white;
      padding: 20px;
    }
    .container {
      max-width: 500px;
      margin: auto;
      background: #292942;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
    }
    h1 {
      text-align: center;
      color: #00f2ff;
    }
    input, select, button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 10px;
      font-size: 16px;
    }
    button {
      background-color: #00f2ff;
      color: #000;
      font-weight: bold;
      cursor: pointer;
    }
    .miners {
      margin-top: 30px;
    }
    .miner {
      background-color: #1e1e2f;
      padding: 10px;
      border-radius: 10px;
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>UpulFX Mining</h1>
    <p>Start earning daily profits with as low as <strong>$100</strong>!</p>

    <input type="text" placeholder="Your Name" />
    <input type="email" placeholder="Your Email" />

    <select>
      <option disabled selected>Select Mining Plan</option>
      <option>Basic Plan - $100 - Daily ROI 3%</option>
      <option>Pro Plan - $300 - Daily ROI 5%</option>
      <option>VIP Plan - $500+ - Daily ROI 7%</option>
    </select>

    <button>Deposit & Start Mining</button>
    <button>Withdraw Earnings</button>

    <div class="miners">
      <h3>Active Miners:</h3>
      <div class="miner">Ali_Hash - VIP Plan</div>
      <div class="miner">CryptoQueen - Pro Plan</div>
      <div class="miner">BTC_Miner88 - Basic Plan</div>
      <div class="miner">Zainah_Pro - VIP Plan</div>
      <div class="miner">FutureBoss - Pro Plan</div>
    </div>
  </div>
</body>
</html>

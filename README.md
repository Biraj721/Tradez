<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trading Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #1e1e2f;
      color: white;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.2s ease-in-out;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card p {
      padding: 15px;
      font-size: 16px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1e1e2f;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>Trading Image Gallery</h1>
    <p>Explore market trends, charts, and trading setups</p>
  </header>

  <div class="gallery">
    <div class="card">
      <img src="https://via.placeholder.com/400x200?text=Stock+Chart+1" alt="Trading Chart 1" />
      <p>Technical analysis of stock trends using candlestick patterns.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x200?text=Forex+Trading" alt="Forex Trading" />
      <p>Forex currency pairs movement and analysis snapshot.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x200?text=Crypto+Market" alt="Crypto Market" />
      <p>Cryptocurrency market volatility and news impact.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x200?text=Stock+Screening" alt="Stock Screener" />
      <p>Screening stocks for investment opportunities using tools.</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Trading Insights. All rights reserved.
  </footer>
</body>
</html>

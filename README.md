<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>EVENT STARS</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: radial-gradient(circle at top, #0a0a0a, #000);
      color: #FFD700;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      overflow: hidden;
    }

    /* glowing background */
    .glow {
      position: absolute;
      width: 500px;
      height: 500px;
      background: #FFD700;
      filter: blur(200px);
      opacity: 0.12;
      animation: pulse 6s infinite alternate ease-in-out;
    }

    @keyframes pulse {
      0% { transform: scale(1); opacity: 0.1; }
      100% { transform: scale(1.3); opacity: 0.25; }
    }

    .container {
      z-index: 2;
    }

    .logo {
      width: 150px;
      height: 150px;
      margin: auto;
      border-radius: 50%;
      overflow: hidden;
      border: 2px solid #FFD700;
      box-shadow: 0 0 25px #FFD700;
    }

    .logo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .brand {
      margin-top: 20px;
      font-size: 34px;
      font-weight: 900;
      letter-spacing: 3px;
      text-shadow: 0 0 15px #FFD700;
    }

    .coming {
      margin-top: 10px;
      font-size: 18px;
      color: #ffffff;
      opacity: 0.9;
    }
  </style>
</head>

<body>

  <div class="glow"></div>

  <div class="container">

    <div class="logo">
      <img src="logo.png" alt="EVENT STARS">
    </div>

    <div class="brand">EVENT STARS</div>

    <div class="coming">Coming Soon</div>
    <div class="coming">We are working on completing the website</div>

  </div>

</body>
</html>

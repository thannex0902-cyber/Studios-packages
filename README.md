<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Packages | Nathan Studios</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #f7f7f7;
      color: #222;
      margin: 0;
      padding: 0;
    }

    header {
      background: url('https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?auto=format&fit=crop&w=1950&q=80') center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.3em;
      font-weight: 300;
    }

    section {
      max-width: 1200px;
      margin: 60px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
    }

    .package {
      background: white;
      border-radius: 15px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
      padding: 30px;
      text-align: center;
      transition: all 0.3s ease;
    }

    .package:hover {
      transform: translateY(-8px);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
    }

    .package h2 {
      font-size: 1.8em;
      color: #111;
      margin-bottom: 10px;
    }

    .price {
      font-size: 1.5em;
      color: #c19a6b;
      font-weight: bold;
      margin: 10px 0 20px;
    }

    .package ul {
      list-style: none;
      padding: 0;
      line-height: 1.8;
    }

    .package ul li {
      margin: 8px 0;
    }

    .btn {
      display: inline-block;
      background-color: #c19a6b;
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      margin-top: 20px;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: #a67b4f;
    }

    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 40px 20px;
      margin-top: 60px;
    }

    footer a {
      color: #c19a6b;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Our Packages</h1>
    <p>Choose the perfect experience for your story.</p>
  </header>

  <section>
    <div class="package">
      <h2>💍 Wedding Package</h2>
      <p class="price">₱25,000+</p>
      <ul>
        <li>8 hours coverage</li>
        <li>2 professional photographers</li>
        <li>Edited digital album (150+ photos)</li>
        <li>1 highlight video (3–5 mins)</li>
        <li>USB copy & online gallery</li>
      </ul>
      <a href="mailto:nathanstudiosphoto@gmail.com" class="btn">Book Now</a>
    </div>

    <div class="package">
      <h2>🎞️ Portrait Package</h2>
      <p class="price">₱5,000+</p>
      <ul>
        <li>2-hour session</li>
        <li>10 fully edited photos</li>
        <li>1 outfit change</li>
        <li>Studio or outdoor location</li>
        <li>High-resolution downloads</li>
      </ul>
      <a href="mailto:nathanstudiosphoto@gmail.com" class="btn">Book Now</a>
    </div>

    <div class="package">
      <h2>🌄 Landscape & Travel</h2>
      <p class="price">Custom</p>
      <ul>
        <li>On-location photography</li>
        <li>Professional color grading</li>
        <li>Drone shots (optional)</li>
        <li>Flexible scheduling</li>
        <li>Perfect for tourism & real estate</li>
      </ul>
      <a href="mailto:nathanstudiosphoto@gmail.com" class="btn">Get Quote</a>
    </div>

    <div class="package">
      <h2>📦 Product & Branding</h2>
      <p class="price">₱8,000+</p>
      <ul>
        <li>High-end product photography</li>
        <li>White or creative backgrounds</li>
        <li>Up to 15 edited shots</li>
        <li>Studio lighting setup</li>
        <li>Brand-consistent visuals</li>
      </ul>
      <a href="mailto:nathanstudiosphoto@gmail.com" class="btn">Book Now</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Nathan Studios | <a href="https://nathanstudios.github.io/about.html">About Us</a></p>
  </footer>
</body>
</html>

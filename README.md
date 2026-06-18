<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rayos del Sol Piñatas</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #fff8f0;
      color: #333;
    }

    header {
      text-align: center;
      padding: 30px 20px;
      background: white;
    }

    header img {
      max-width: 300px;
    }

    nav {
      background: #ffb347;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 12px;
      flex-wrap: wrap;
    }

    nav a {
     <nav>
  <a href="#about">About</a>
  <a href="#gallery">Gallery</a>
  <a href="#pricing">Pricing</a>
  <a href="#design">Choose Design</a>
  <a href="#contact">Order</a>
</nav>

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    h2 {
      color: #ff6f61;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .gallery img {
      width: 250px;
      border-radius: 12px;
    }

    .pricing p {
      font-size: 18px;
      margin: 10px 0;
    }

    .highlight {
      font-weight: bold;
      color: #ff6f61;
    }

    .btn {
      display: inline-block;
      margin-top: 15px;
      background: #ff6f61;
      color: white;
      padding: 12px 20px;
      text-decoration: none;
      border-radius: 8px;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  <!-- Replace logo.png with your actual file name -->
  <img src="logo.png" alt="Rayos del Sol Piñatas Logo">
</header>

<nav>
  <a href="#about">About</a>
  <a href="#gallery">Gallery</a>
  <a href="#pricing">Pricing</a>
  <a href="#contact">Order</a>
</nav>

<section id="about">
  <h2>About Us</h2>
  <p>
    At <span class="highlight">Rayos del Sol Piñatas</span>, we create handmade, custom piñatas 
    for birthdays, baby showers, and special celebrations. Each design is made with love and color to make your event unforgettable.
  </p>
</section>

<section id="gallery">
  <h2>Our Work</h2>
  <div class="gallery">
    <img src="pinata1.jpg" alt="Piñata example">
    <img src="pinata2.jpg" alt="Piñata example">
    <img src="pinata3.jpg" alt="Piñata example">
  </div>
</section>

<section id="pricing" class="pricing">
  <h2>Pricing</h2>
  <p><span class="highlight">Small:</span> $15</p>
  <p><span class="highlight">Medium:</span> $35</p>
  <p><span class="highlight">Large:</span> $60</p>
  <p><span class="highlight">XL:</span> $115</p>
  <p>Custom designs may vary depending on detail.</p>
</section>

<section id="contact">
  <h2>Order Your Piñata</h2>
  <p>Message us to place your custom order!</p>

  <!-- Replace with your info -->
  <p>Phone: (your number)</p>
  <p>Email: your@email.com</p>

  <a class="btn" href="mailto:your@email.com">Order Now</a>
</section>

<footer>
  <p>© 2026 Rayos del Sol Piñatas</p>
</footer>

</body>
</html>

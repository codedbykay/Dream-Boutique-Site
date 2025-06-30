<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kay's Dream Boutique</title>
  <style>
    /* ✨ Global Styles */
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: #fff0f5;
      color: #333;
    }

    header {
      background-color: #d63384;
      color: white;
      text-align: center;
      padding: 1.2rem;
      font-size: 2rem;
      font-weight: bold;
    }

    /* 🎀 Promo Banner */
    .promo-banner {
      background: linear-gradient(to right, #ffe6f0, #fff0f5);
      color: #d63384;
      font-weight: bold;
      text-align: center;
      padding: 15px 20px;
      font-size: 1.2em;
      border-bottom: 2px solid #d63384;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    /* 👑 Hero Section */
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: #fff;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      color: #d63384;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto 1.5rem;
    }

    .cta-button {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background-color: #d63384;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }

    .cta-button:hover {
      background-color: #c1276f;
    }

    /* 🛍️ Shop Preview */
    .shop-preview {
      padding: 3rem 1rem;
      background-color: #fff0f5;
      text-align: center;
    }

    .shop-preview h2 {
      font-size: 2rem;
      color: #d63384;
      margin-bottom: 2rem;
    }

    .product-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
    }

    .product-card {
      background-color: white;
      padding: 1rem;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
      width: 200px;
    }

    .product-card img {
      width: 100%;
      border-radius: 10px;
    }

    .product-card h3 {
      font-size: 1.1rem;
      margin: 10px 0 5px;
      color: #d63384;
    }

    .product-card p {
      font-size: 1rem;
      color: #555;
    }

    /* 💬 Testimonial */
    .testimonial {
      background-color: #fff;
      padding: 3rem 1rem;
      text-align: center;
    }

    .testimonial blockquote {
      font-style: italic;
      font-size: 1.2rem;
      color: #666;
      max-width: 600px;
      margin: auto;
    }

    .testimonial cite {
      display: block;
      margin-top: 1rem;
      color: #d63384;
      font-weight: bold;
    }

    /* 💌 Newsletter Signup */
    .newsletter {
      padding: 3rem 1rem;
      background-color: #ffe6f0;
      text-align: center;
    }

    .newsletter h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #d63384;
    }

    .newsletter input[type="email"] {
      padding: 10px;
      width: 250px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    .newsletter button {
      padding: 10px 20px;
      margin-left: 10px;
      background-color: #d63384;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    /* 📦 Footer */
    footer {
      background-color: #d63384;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- 🎀 Promo Banner -->
  <div class="promo-banner">
    💖 Summer Sale: Up to 30% Off Selected Items! 💖
  </div>

  <!-- 🧁 Header -->
  <header>Kay's Dream Boutique</header>

  <!-- 👑 Hero Section -->
  <section class="hero">
    <h1>Welcome to Your Dream Boutique</h1>
    <p>Where modern elegance meets timeless style. Shop our curated collection today.</p>
    <a href="#" class="cta-button">Shop Now</a>
  </section>

  <!-- 🛍️ Shop Preview -->
  <section class="shop-preview">
    <h2>🛍️ Featured Pieces</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Elegant Dress">
        <h3>Elegant Dress</h3>
        <p>$89.00</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Chic Blazer">
        <h3>Chic Blazer</h3>
        <p>$120.00</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Classic Heels">
        <h3>Classic Heels</h3>
        <p>$75.00</p>
      </div>
    </div>
  </section>

  <!-- 💬 Testimonial -->
  <section class="testimonial">
    <blockquote>
      “I absolutely love everything from this boutique — the quality, the style, the service! My new go-to shop.”
    </blockquote>
    <cite>— A Happy Customer</cite>
  </section>

  <!-- 💌 Newsletter Signup -->
  <section class="newsletter">
    <h3>Get style updates & exclusive offers 💌</h3>
    <input type="email" placeholder="Your email address">
    <button>Subscribe</button>
  </section>

  <!-- 📦 Footer -->
  <footer>
    &copy; 2025 Kay’s Dream Boutique. All rights reserved.
  </footer>

</body>
</html>

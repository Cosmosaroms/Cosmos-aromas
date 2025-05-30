# Cosmos-aromas
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>COSMOS AROMAS</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fff9f5;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #3a1c71, #d76d77, #ffaf7b);
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header img {
      max-height: 80px;
      margin-bottom: 1rem;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0.5rem 0;
    }

    header p {
      font-size: 1.2rem;
      font-style: italic;
    }

    nav {
      background-color: #eee;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      flex-wrap: wrap;
    }

    nav a {
      color: #3a1c71;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 3rem 2rem;
      background: url('https://images.unsplash.com/photo-1597007519802-df69a77c3ccf') no-repeat center;
      background-size: cover;
      color: white;
    }

    .hero h2 {
      background: rgba(0,0,0,0.6);
      display: inline-block;
      padding: 1rem 2rem;
      border-radius: 10px;
      font-size: 2rem;
    }

    .products {
      padding: 3rem 2rem;
      text-align: center;
      background-color: #faf0ec;
    }

    .products h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #3a1c71;
    }

    .product-grid {
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
    }

    .product {
      background: white;
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 5px 10px rgba(0,0,0,0.1);
      width: 250px;
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    .product h3 {
      margin-top: 1rem;
      color: #6a2f70;
    }

    .product p {
      font-size: 0.95rem;
      margin-bottom: 0.5rem;
    }

    .product .price {
      font-weight: bold;
      color: #333;
      margin-bottom: 1rem;
    }

    .btn {
      background: #3a1c71;
      color: white;
      padding: 0.6rem 1.2rem;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      display: inline-block;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #5f2d91;
    }

    .contact {
      padding: 2rem;
      background-color: #e5d3e8;
      text-align: center;
    }

    .contact h2 {
      margin-bottom: 1rem;
      color: #3a1c71;
    }

    footer {
      background-color: #3a1c71;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 768px) {
      .product-grid {
        flex-direction: column;
        align-items: center;
      }

      header h1 {
        font-size: 2rem;
      }

      .hero h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="your-logo.png" alt="Cosmos Aromas Logo" />
    <h1>COSMOS AROMAS</h1>
    <p>"The Universal Essence"</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Signature Scents That Transcend Time</h2>
  </section>

  <section class="products" id="products">
    <h2>Our Signature Scents</h2>
    <div class="product-grid">

      <div class="product">
        <img src="legacy.jpg" alt="LEGACY Perfume" />
        <h3>LEGACY</h3>
        <p>Bold, timeless, and elegant. For those who leave their mark.</p>
        <p class="price">₹249 + Delivery</p>
        <a href="https://rzp.io/l/legacy" class="btn">Shop Now</a>
      </div>

      <div class="product">
        <img src="afterlife.jpg" alt="AFTERLIFE Perfume" />
        <h3>AFTERLIFE</h3>
        <p>Mystic and alluring. A scent that lingers beyond presence.</p>
        <p class="price">₹249 + Delivery</p>
        <a href="https://rzp.io/l/afterlife" class="btn">Shop Now</a>
      </div>

      <div class="product">
        <img src="infinity.jpg" alt="INFINITY Perfume" />
        <h3>INFINITY</h3>
        <p>Endlessly fresh and boundless. The scent of endless potential.</p>
        <p class="price">₹249 + Delivery</p>
        <a href="https://rzp.io/l/infinity" class="btn">Shop Now</a>
      </div>

    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:cosmos.aromas@gmail.com">cosmos.aromas@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/cosmos.aromas" target="_blank">@cosmos.aromas</a></p>
  </section>

  <footer>
    &copy; 2025 COSMOS AROMAS | All rights reserved.
  </footer>

</body>
</html>

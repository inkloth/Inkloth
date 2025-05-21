<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Inkloth - Custom & Trendy Fashion</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet"/>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffffff;
      color: #000;
      line-height: 1.6;
    }
    header {
      background-color: #1b1b1b;
      color: white;
      text-align: center;
      padding: 20px 0;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 999;
    }
    header h1 { color: #E67E22; font-size: 2.5rem; font-weight: 700; }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover { color: #E67E22; }
    .main {
      padding: 120px 20px 40px;
      text-align: center;
    }
    .main h2 { font-size: 2.5rem; font-weight: 600; }
    .main p { font-size: 1.1rem; color: #333; margin-top: 15px; }

    #about {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }
    #about h2 {
      font-size: 2.5rem;
      color: #2C3E50;
      margin-bottom: 20px;
    }
    #about p {
      font-size: 1.1rem;
      color: #333;
      line-height: 1.8;
      margin-bottom: 20px;
    }

    .section-title {
      text-align: center;
      font-size: 2.2rem;
      color: #2c3e50;
      margin-top: 50px;
    }
    .offers {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 30px 20px;
    }
    .offer-card {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      width: 260px;
      margin: 15px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .offer-card:hover { transform: translateY(-5px); }
    .offer-card h3 { color: #2c3e50; font-size: 1.5rem; margin-bottom: 10px; }
    .offer-card p { color: #555; font-size: 1rem; }
    .cta-btn {
      display: inline-block;
      margin-top: 15px;
      background: #E67E22;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 600;
    }
    .cta-btn:hover { background: #d35400; }

    footer {
      background: #1b1b1b;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    footer a {
      color: #E67E22;
      text-decoration: none;
    }
    .whatsapp-btn {
      display: inline-block;
      background: #25D366;
      color: white;
      padding: 8px 15px;
      border-radius: 5px;
      text-decoration: none;
      margin: 5px;
      font-weight: 600;
    }
    .whatsapp-btn:hover { background: #128C7E; }

    @media (max-width: 768px) {
      .offers { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>

  <header>
    <h1><strong>Inkloth</strong></h1>
    <nav>
      <a href="#main">Home</a>
      <a href="#about">About</a>
      <a href="#offers">What We Offer</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="main" class="main">
    <h2>Your Fashion, Your Way</h2>
    <p>Explore our custom clothing, from trendy streetwear to basics. Launch your fashion journey with <strong>Inkloth</strong>.</p>
  </section>

  <section id="about">
    <h2>About <strong>Inkloth</strong></h2>
    <p><strong>Inkloth</strong> is a dynamic fashion and apparel brand founded on <strong>March 8, 2024</strong>, by entrepreneur <strong>Nishant Kumar</strong> with a vision to revolutionize custom clothing in India. At Inkloth, we blend style, quality, and innovation to provide a seamless experience for customers, resellers, and brand creators.</p>
    <p>What started as a simple idea to offer affordable, stylish clothing has now evolved into a full-fledged platform offering <strong>retail, wholesale, white labeling, print-on-demand (POD), and dropshipping</strong> solutions under one roof.</p>
    <p>Whether you're a fashion-forward shopper, a budding entrepreneur, or a large-scale business, <strong>Inkloth</strong> gives you the power to customize, brand, and sell apparel effortlessly. With multiple platforms like <a href="https://inkloth.in" target="_blank">Inkloth.in</a>, we are committed to making fashion more accessible, scalable, and profitable.</p>
    <p>At our core, we believe fashion should reflect individuality — and with <strong>Inkloth</strong>, anyone can become a fashionpreneur.</p>
  </section>

  <section id="offers">
    <h2 class="section-title">What We Offer</h2>
    <div class="offers">
      <div class="offer-card">
        <h3>Retail Fashion</h3>
        <p>Shop our exclusive graphic tees, oversized fits, and streetwear collections.</p>
        <a href="#shop" class="cta-btn">Shop Now</a>
      </div>
      <div class="offer-card">
        <h3>Wholesale</h3>
        <p>Get premium products in bulk with competitive pricing and reseller support.</p>
        <a href="#wholesale" class="cta-btn">View Deals</a>
      </div>
      <div class="offer-card">
        <h3>White Label</h3>
        <p>Launch your own brand. We apply your custom labels and ship under your name.</p>
        <a href="#white-label" class="cta-btn">Start Branding</a>
      </div>
      <div class="offer-card">
        <h3>Print-on-Demand</h3>
        <p>Upload your designs. We print, pack, and ship — zero inventory needed.</p>
        <a href="#pod" class="cta-btn">Start POD</a>
      </div>
      <div class="offer-card">
        <h3>Dropshipping</h3>
        <p>You sell, we fulfill. No stock, no hassle — just focus on marketing and growth.</p>
        <a href="#dropshipping" class="cta-btn">Start Now</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <footer>
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:inkloth.in@gmail.com">inkloth.in@gmail.com</a>, <a href="mailto:inklothhelp@gmail.com">inklothhelp@gmail.com</a></p>
      <p>Phone: <a href="tel:+919267981157">+91 92679 81157</a>, <a href="tel:+919608826736">96088 26736</a>, <a href="tel:+919128706648">91287 06648</a></p>
      <a class="whatsapp-btn" href="https://wa.me/919267981157" target="_blank">WhatsApp 1</a>
      <a class="whatsapp-btn" href="https://wa.me/919608826736" target="_blank">WhatsApp 2</a>
      <a class="whatsapp-btn" href="https://wa.me/919128706648" target="_blank">WhatsApp 3</a>
      <p>&copy; 2025 <strong>Inkloth</strong>. All rights reserved.</p>
    </footer>
  </section>

</body>
</html>


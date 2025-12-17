# GodIdolsEcomm
E-commerce platform for God Idols, offering all modern features and functionalities.
hardik-handy-craft/
├── index.html
├── products.html
├── style.css<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hardik Handy Craft | Wooden God Idols</title>
  <meta name="description" content="Handcrafted wooden god idols made by skilled Indian artisans.">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Hardik Handy Craft</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="products.html">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Handcrafted Wooden God Idols</h1>
  <p>Pure wood • Traditional carving • Made in India</p>
  <a class="btn" href="products.html">View Products</a>
</section>

<section id="about" class="section">
  <h2>About Us</h2>
  <p>
    Hardik Handy Craft creates premium wooden god idols crafted by experienced artisans.
    Every piece reflects devotion, tradition, and quality workmanship.
  </p>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>
  <p>📞 WhatsApp: <strong>+91XXXXXXXXXX</strong></p>
  <a class="btn" href="https://wa.me/91XXXXXXXXXX">Chat on WhatsApp</a>
</section>

<footer>
  <p>© 2025 Hardik Handy Craft. All rights reserved.</p>
</footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Products | Hardik Handy Craft</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Hardik Handy Craft</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="products.html">Products</a>
  </nav>
</header>

<section class="section">
  <h2>Our Wooden Idols</h2>

  <div class="products">

    <div class="product-card">
      <img src="https://via.placeholder.com/300" alt="Wooden Krishna Idol">
      <h3>Wooden Krishna Idol – 12 Inch</h3>
      <p>Hand-carved from premium quality wood.</p>
      <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=Interested%20in%20Wooden%20Krishna%20Idol">
        Enquire on WhatsApp
      </a>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/300" alt="Wooden Ganesh Idol">
      <h3>Wooden Ganesh Idol – 10 Inch</h3>
      <p>Traditional design with smooth finish.</p>
      <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=Interested%20in%20Wooden%20Ganesh%20Idol">
        Enquire on WhatsApp
      </a>
    </div>

  </div>
</section>

<footer>
  <p>© 2025 Hardik Handy Craft</p>
</footer>

</body>
</html>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #faf7f2;
  color: #333;
}

header {
  background: #fff;
  padding: 15px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #ddd;
}

.logo {
  font-size: 22px;
  font-weight: bold;
  color: #6b3e26;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

.hero {
  text-align: center;
  padding: 80px 20px;
  background: #e9ddcf;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 25px;
}

.section {
  padding: 60px 40px;
  text-align: center;
}

.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  margin-top: 40px;
}

.product-card {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.product-card img {
  width: 100%;
  border-radius: 6px;
}

.product-card h3 {
  margin: 15px 0 10px;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background: #6b3e26;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
}

.btn:hover {
  background: #54301d;
}

footer {
  background: #fff;
  padding: 15px;
  text-align: center;
  border-top: 1px solid #ddd;
}
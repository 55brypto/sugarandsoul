# sugarandsoul
Website for bakery
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sugar and Soul - A Heartfelt Cinnamon Roll Bakery">
  <title>Sugar and Soul | Handcrafted Cinnamon Rolls</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Lato:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <nav>
      <h1 class="logo">Sugar <span>&</span> Soul</h1>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#order">Order</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="hero">
      <h2>Where Sweetness Meets the Heart</h2>
      <p>Handcrafted cinnamon rolls for every occasion.</p>
      <a href="#menu" class="cta-button">Explore Flavors</a>
    </div>
  </header>

  <main>
    <section id="about" class="about">
      <h2>About Us</h2>
      <p>Sugar and Soul is a cottage bakery born out of a passion for creating homemade, heartfelt cinnamon rolls. Every bite is made with love and the finest ingredients.</p>
      <img src="images/about.jpg" alt="Baking cinnamon rolls" />
    </section>

    <section id="menu" class="menu">
      <h2>Our Menu</h2>
      <div class="menu-items">
        <div class="menu-item">
          <h3>Classic Cinnamon Roll</h3>
          <p>The perfect blend of cinnamon and sugar, topped with creamy frosting.</p>
        </div>
        <div class="menu-item">
          <h3>Caramel Pecan</h3>
          <p>A delightful twist with creamy caramel and crunchy pecans.</p>
        </div>
        <div class="menu-item">
          <h3>Seasonal Special</h3>
          <p>Ask about our limited-edition rolls, available fresh for the season!</p>
        </div>
      </div>
    </section>

    <section id="order" class="order">
      <h2>Order Now</h2>
      <p>Choose your favorite flavors and place your order easily.</p>
      <a href="#contact" class="cta-button">Contact Us to Order</a>
    </section>

    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>© 2026 Sugar and Soul Bakery. All Rights Reserved.</p>
    <div class="social-links">
      <a href="https://www.instagram.com" target="_blank">Instagram</a> | 
      <a href="https://www.facebook.com" target="_blank">Facebook</a>
    </div>
  </footer>
</body>
</html>
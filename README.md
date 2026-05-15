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
      <div class="hero-text">
        <h2>Where Sweetness Meets the Heart</h2>
        <p>Indulge in handcrafted cinnamon rolls made with love and the finest ingredients.</p>
        <a href="#menu" class="cta-button">Explore Flavors</a>
      </div>
    </div>
  </header>

  <main>
    <!-- About Section -->
    <section id="about" class="about">
      <h2>About Us</h2>
      <div class="about-content">
        <p>At Sugar & Soul, we bring the warm, homemade flavors of cinnamon rolls to your table. From classic varieties to creative seasonal pairings, our rolls are baked with the utmost care. Every cinnamon roll tells a delicious story!</p>
        <img src="images/about-bakery.jpg" alt="Rustic cinnamon rolls on a table">
      </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="menu">
      <h2>Our Menu</h2>
      <div class="menu-items">
        <div class="menu-item">
          <img src="images/classic-roll.jpg" alt="Classic Cinnamon Roll">
          <h3>Classic Cinnamon Roll</h3>
          <p>A sweet harmony of cinnamon and creamy frosting.</p>
        </div>
        <div class="menu-item">
          <img src="images/caramel-pecan.jpg" alt="Caramel Pecan Cinnamon Roll">
          <h3>Caramel Pecan</h3>
          <p>The delicate sweetness of caramel paired with crunchy pecans.</p>
        </div>
        <div class="menu-item">
          <img src="images/seasonal-roll.jpg" alt="Seasonal Specialty Roll">
          <h3>Seasonal Special</h3>
          <p>Celebrate the season with our rotating special flavors!</p>
        </div>
      </div>
    </section>

    <!-- Order Section -->
    <section id="order" class="order">
      <h2>Order Now</h2>
      <p>Ready to experience the warmth of our cinnamon rolls? Place your order today and elevate your dessert game.</p>
      <a href="#contact" class="cta-button">Contact Us to Order</a>
    </section>

    <!-- Contact Section -->
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
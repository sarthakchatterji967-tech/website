# website
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ShopEase — Modern eCommerce</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <h1 class="logo">ShopEase</h1>
      <nav class="nav">
        <a href="#products">Products</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
        <button class="btn btn-primary" id="cta-top">Shop Now</button>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-copy">
          <h2>Everything you love. Delivered fast.</h2>
          <p>Curated products, great prices, and lightning-fast shipping. Discover picks we know you'll love.</p>
          <div class="hero-ctas">
            <button class="btn btn-primary" id="cta-hero">Shop Featured</button>
            <a class="btn btn-ghost" href="#features">Why ShopEase</a>
          </div>
        </div>
        <div class="hero-image" aria-hidden="true">
          <img src="https://images.unsplash.com/photo-1526178614375-43f6b6f0c1d8?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Products on display"/>
        </div>
      </div>
    </section>

    <section id="features" class="features container">
      <h3>Why shop with us</h3>
      <div class="features-grid">
        <div class="feature">
          <h4>Free shipping</h4>
          <p>On orders over $50 — always fast and tracked.</p>
        </div>
        <div class="feature">
          <h4>Curated collections</h4>
          <p>Hand-picked items from trusted brands.</p>
        </div>
        <div class="feature">
          <h4>Hassle-free returns</h4>
          <p>30-day returns and friendly support.</p>
        </div>
      </div>
    </section>

    <section id="products" class="products container">
      <h3>Featured products</h3>
      <div class="product-grid" id="product-grid">
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=600&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Product 1"/>
          <h4>Minimalist Headphones</h4>
          <p class="price">$79</p>
          <button class="btn btn-primary add-to-cart">Add to cart</button>
        </article>
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?q=80&w=600&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Product 2"/>
          <h4>Everyday Backpack</h4>
          <p class="price">$59</p>
          <button class="btn btn-primary add-to-cart">Add to cart</button>
        </article>
        <article class="product-card">
          <img src="https://images.unsplash.com/photo-1503602642458-232111445657?q=80&w=600&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Product 3"/>
          <h4>Smart Bottle</h4>
          <p class="price">$29</p>
          <button class="btn btn-primary add-to-cart">Add to cart</button>
        </article>
      </div>
    </section>

    <section class="testimonials container">
      <h3>What customers say</h3>
      <blockquote>
        "Fast delivery and excellent packaging — will buy again!" — Priya
      </blockquote>
    </section>

    <section id="contact" class="contact container">
      <h3>Stay in the loop</h3>
      <form id="signup-form">
        <label for="email">Email</label>
        <input id="email" type="email" placeholder="you@example.com" required />
        <button class="btn btn-primary" type="submit">Subscribe</button>
      </form>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>© 2026 ShopEase. All rights reserved.</p>
      <small>Made with care.</small>
    </div>
  </footer>

  <div id="toast" role="status" aria-live="polite" class="toast" hidden></div>

  <script src="script.js"></script>
</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>AQUADET CORPORATION — Industrial & Water Treatment Chemicals</title>
  <meta name="description" content="AQUADET CORPORATION — Manufacturers & suppliers of boiler antiscalant & corrosion inhibitors, cooling tower chemicals, RO antiscalant, ETP/STP chemicals, construction chemicals, liquid soaps, dust suppression chemicals in Jabalpur, India." />
  <meta name="keywords" content="boiler antiscalant, corrosion inhibitor, cooling tower chemicals, RO antiscalant, ETP chemicals, STP chemicals, construction chemicals, liquid soap, dust suppression chemicals, Jabalpur" />
  <link rel="icon" href="assets/favicon.svg" type="image/svg+xml" />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="#">
        <img src="assets/logo.svg" alt="AQUADET CORPORATION logo" />
        <span>AQUADET CORPORATION</span>
      </a>

      <nav class="nav" id="main-nav">
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#industries">Industries</a>
        <a href="#contact">Contact</a>
      </nav>

      <button id="nav-toggle" class="nav-toggle" aria-label="Toggle navigation">☰</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-copy">
          <h1>Chemicals for Cleaner, Safer Industrial Water</h1>
          <p>Manufacturers & suppliers of boiler antiscalant & corrosion inhibitors, cooling tower chemicals, RO antiscalants, ETP/STP chemicals, construction chemicals, liquid soap, and dust suppression solutions.</p>
          <div class="hero-cta">
            <a class="btn" href="#products">Our Products</a>
            <a class="btn btn-outline" href="#contact">Get a Quote</a>
          </div>
        </div>
        <div class="hero-image" aria-hidden="true">
          <!-- Placeholder illustration -->
          <svg width="360" height="220" viewBox="0 0 360 220" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="360" height="220" rx="12" fill="#E8F7F3"/>
            <g fill="#057A6E">
              <circle cx="300" cy="60" r="24" />
              <rect x="40" y="40" width="140" height="120" rx="8" />
            </g>
          </svg>
        </div>
      </div>
    </section>

    <section id="about" class="container about">
      <h2>About AQUADET CORPORATION</h2>
      <p>AQUADET CORPORATION is a chemical manufacturer based in Jabalpur focused on industrial water treatment and specialty chemicals. We provide tailored solutions for boilers, cooling towers, RO pre-treatment, effluent treatment plants (ETP), sewage treatment plants (STP), construction, and dust suppression.</p>
      <ul class="contact-card">
        <li><strong>Address:</strong> 23 Tapti Nagar, Adhartal, Jabalpur 482004</li>
        <li><strong>Phone:</strong> +91-XXXXXXXXXX (update)</li>
        <li><strong>Email:</strong> info@aquadet.com (update)</li>
      </ul>
    </section>

    <section id="products" class="container products">
      <h2>Our Products & Solutions</h2>
      <div class="grid">
        <article class="card">
          <h3>Boiler Antiscalant & Corrosion Inhibitors</h3>
          <p>Scale & corrosion control formulations to extend boiler life and improve heat transfer.</p>
        </article>

        <article class="card">
          <h3>Cooling Tower Chemicals</h3>
          <p>Biocides, scale inhibitors, and dispersants for efficient cooling water management.</p>
        </article>

        <article class="card">
          <h3>RO Antiscalant</h3>
          <p>High-performance antiscalants for reverse osmosis membranes to reduce fouling.</p>
        </article>

        <article class="card">
          <h3>ETP & STP Chemicals</h3>
          <p>Coagulants, flocculants, and biological treatment aids for wastewater treatment systems.</p>
        </article>

        <article class="card">
          <h3>Construction Chemicals</h3>
          <p>Admixtures and additives for concrete, curing compounds, and surface treatments.</p>
        </article>

        <article class="card">
          <h3>Liquid Soaps & Cleaning Agents</h3>
          <p>Industrial and institutional cleaning formulations available in bulk.</p>
        </article>

        <article class="card">
          <h3>Dust Suppression Chemicals</h3>
          <p>Environment-friendly solutions to control airborne dust at sites and stockpiles.</p>
        </article>
      </div>
    </section>

    <section id="industries" class="container industries">
      <h2>Industries We Serve</h2>
      <p>Power plants, manufacturing, textiles, pharmaceuticals, food & beverage, municipal bodies, construction sites, and more.</p>
    </section>

    <section id="contact" class="container contact">
      <h2>Contact & Get a Quote</h2>

      <div class="contact-grid">
        <div>
          <h3>Send us a message</h3>
          <form id="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
            <label>
              Name
              <input type="text" name="name" required />
            </label>
            <label>
              Email
              <input type="email" name="email" required />
            </label>
            <label>
              Company / Industry
              <input type="text" name="company" />
            </label>
            <label>
              Message / Requirement
              <textarea name="message" rows="5" required></textarea>
            </label>
            <button class="btn" type="submit">Send Message</button>
            <p class="note">Or email us at <a href="mailto:info@aquadet.com">info@aquadet.com</a></p>
          </form>
        </div>

        <div>
          <h3>Office</h3>
          <p>23 Tapti Nagar, Adhartal, Jabalpur 482004</p>
          <h4>Map</h4>
          <div class="map-wrap">
            <iframe
              title="AQUADET CORPORATION location"
              src="https://www.google.com/maps?q=23%20Tapti%20Nagar%20Adhartal%20Jabalpur%20482004&output=embed"
              allowfullscreen
              loading="lazy"></iframe>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>&copy; <span id="year"></span> AQUADET CORPORATION — All rights reserved.</p>
      <p>Designed & maintained by AQUADET CORPORATION</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

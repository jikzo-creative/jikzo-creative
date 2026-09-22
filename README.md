<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>JIKZO Creative | Digital Services</title>

  <meta name="description" content="JIKZO Creative provides affordable digital, creative, gaming and online services.">
  <meta name="theme-color" content="#111827">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: #ffffff;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    header {
      background: #111827;
      padding: 18px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 1px solid #263247;
    }

    nav {
      max-width: 1100px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #38bdf8;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 60px 20px;
      background:
        radial-gradient(circle at top, #183b5b 0%, #0b1020 55%);
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h1 {
      font-size: clamp(42px, 8vw, 76px);
      margin-bottom: 15px;
    }

    .hero h1 span {
      color: #38bdf8;
    }

    .hero p {
      font-size: 20px;
      color: #cbd5e1;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .btn {
      display: inline-block;
      padding: 13px 24px;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.2s;
    }

    .btn-primary {
      background: #38bdf8;
      color: #06111c;
    }

    .btn-secondary {
      border: 1px solid #38bdf8;
      color: #38bdf8;
    }

    .btn:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    section {
      padding: 70px 20px;
    }

    .container {
      max-width: 1100px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      font-size: 36px;
      margin-bottom: 40px;
    }

    .section-title span {
      color: #38bdf8;
    }

    .about {
      text-align: center;
      max-width: 800px;
      margin: auto;
      color: #cbd5e1;
      font-size: 18px;
    }

    .services {
      background: #0f172a;
    }

    .service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .card {
      background: #111827;
      border: 1px solid #263247;
      border-radius: 14px;
      padding: 28px;
      text-align: center;
      transition: 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #38bdf8;
    }

    .card-icon {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .card p {
      color: #cbd5e1;
    }

    .contact-box {
      max-width: 700px;
      margin: auto;
      background: #111827;
      border: 1px solid #263247;
      border-radius: 15px;
      padding: 35px;
      text-align: center;
    }

    .contact-box p {
      color: #cbd5e1;
      margin: 10px 0;
    }

    .contact-link {
      display: block;
      margin: 15px 0;
      color: #38bdf8;
      font-size: 18px;
      word-break: break-word;
    }

    footer {
      background: #070b14;
      text-align: center;
      padding: 25px 20px;
      color: #94a3b8;
    }

    @media (max-width: 650px) {
      nav {
        flex-direction: column;
      }

      nav ul {
        gap: 12px;
        flex-wrap: wrap;
        justify-content: center;
      }

      .hero {
        min-height: 75vh;
      }

      .hero p {
        font-size: 17px;
      }
    }
  </style>
</head>

<body>

  <header>
    <nav>
      <div class="logo">JIKZO Creative</div>

      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>

    <section class="hero" id="home">
      <div class="hero-content">
        <h1>JIKZO <span>Creative</span></h1>

        <p>
          Digital creativity, online services, gaming and creative solutions
          designed to help you build and grow online.
        </p>

        <div class="buttons">
          <a class="btn btn-primary" href="#services">View Services</a>

          <a
            class="btn btn-secondary"
            href="https://wa.me/27810030559"
            target="_blank"
            rel="noopener"
          >
            WhatsApp Me
          </a>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="container">
        <h2 class="section-title">About <span>JIKZO Creative</span></h2>

        <p class="about">
          JIKZO Creative is an independent digital creative business focused
          on helping people and small businesses with online, creative,
          gaming and digital projects.
        </p>
      </div>
    </section>

    <section class="services" id="services">
      <div class="container">

        <h2 class="section-title">Our <span>Services</span></h2>

        <div class="service-grid">

          <div class="card">
            <div class="card-icon">🎨</div>
            <h3>Graphic Design</h3>
            <p>
              Creative designs for social media, brands, posters and online projects.
            </p>
          </div>

          <div class="card">
            <div class="card-icon">🎬</div>
            <h3>Video & Content</h3>
            <p>
              Creative video and content ideas for YouTube, TikTok and other platforms.
            </p>
          </div>

          <div class="card">
            <div class="card-icon">🎮</div>
            <h3>Gaming Content</h3>
            <p>
              Gaming-focused creative content, ideas and digital support.
            </p>
          </div>

          <div class="card">
            <div class="card-icon">💻</div>
            <h3>Digital Services</h3>
            <p>
              Simple digital solutions for individuals, creators and small businesses.
            </p>
          </div>

        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container">

        <h2 class="section-title">Get In <span>Touch</span></h2>

        <div class="contact-box">

          <p>Ready to work together?</p>
          <p>Contact JIKZO Creative directly.</p>

          <a
            class="contact-link"
            href="mailto:jikzob@gmail.com"
          >
            📧 jikzob@gmail.com
          </a>

          <a
            class="contact-link"
            href="https://wa.me/27810030559"
            target="_blank"
            rel="noopener"
          >
            📱 WhatsApp: 0810030559
          </a>

          <div class="buttons">
            <a
              class="btn btn-primary"
              href="mailto:jikzob@gmail.com"
            >
              Send Email
            </a>

            <a
              class="btn btn-secondary"
              href="https://wa.me/27810030559"
              target="_blank"
              rel="noopener"
            >
              Open WhatsApp
            </a>
          </div>

        </div>
      </div>
    </section>

  </main>

  <footer>
    <p>© 2026 JIKZO Creative. All rights reserved.</p>
  </footer>

</body>
</html>

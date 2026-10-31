
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Joy Mohon — Digital Marketing, SEO, Web Development and AI Automation.">
  <meta name="theme-color" content="#ffffff">
  <title>Joy Mohon | Digital Marketing Professional</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #ffffff;
      color: #172b4d;
      line-height: 1.7;
    }

    a {
      text-decoration: none;
    }

    .container {
      width: min(1100px, 90%);
      margin: auto;
    }

    header {
      background: #ffffff;
      border-bottom: 1px solid #e8eef7;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav {
      min-height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      font-size: 23px;
      font-weight: 800;
      color: #173d75;
      letter-spacing: -1px;
    }

    .nav-links {
      display: flex;
      gap: 24px;
      flex-wrap: wrap;
    }

    .nav-links a {
      color: #52647a;
      font-size: 14px;
      font-weight: 600;
    }

    .nav-links a:hover {
      color: #2563eb;
    }

    .hero {
      padding: 100px 0 85px;
      background: linear-gradient(135deg, #f8fbff, #edf5ff);
    }

    .hero-content {
      max-width: 760px;
    }

    .eyebrow {
      color: #2563eb;
      font-size: 13px;
      font-weight: 800;
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 18px;
    }

    h1 {
      font-size: clamp(40px, 7vw, 68px);
      line-height: 1.12;
      letter-spacing: -2px;
      margin-bottom: 22px;
    }

    h1 span {
      color: #2563eb;
    }

    .hero p {
      max-width: 620px;
      color: #52647a;
      font-size: 18px;
      margin-bottom: 30px;
    }

    .button {
      display: inline-block;
      background: #2563eb;
      color: #ffffff;
      padding: 13px 23px;
      border-radius: 8px;
      font-weight: 700;
      transition: 0.2s;
    }

    .button:hover {
      background: #173dba;
      transform: translateY(-2px);
    }

    .button-outline {
      background: #ffffff;
      color: #2563eb;
      border: 1px solid #bfdbfe;
      margin-left: 10px;
    }

    .button-outline:hover {
      background: #eff6ff;
      color: #173d75;
    }

    section {
      padding: 78px 0;
      scroll-margin-top: 75px;
    }

    .section-title {
      text-align: center;
      font-size: 34px;
      margin-bottom: 12px;
      letter-spacing: -1px;
    }

    .section-intro {
      text-align: center;
      color: #64748b;
      max-width: 620px;
      margin: 0 auto 38px;
    }

    .about {
      max-width: 760px;
      margin: auto;
      text-align: center;
      color: #52647a;
      font-size: 17px;
    }

    .skills-grid,
    .services-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      padding: 27px 23px;
      background: #ffffff;
      border: 1px solid #e2eaf5;
      border-radius: 14px;
      box-shadow: 0 8px 28px rgba(29, 78, 150, 0.05);
      transition: 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #93c5fd;
      box-shadow: 0 12px 32px rgba(37, 99, 235, 0.10);
    }

    .card-icon {
      font-size: 27px;
      margin-bottom: 12px;
    }

    .card h3 {
      font-size: 19px;
      margin-bottom: 9px;
    }

    .card p {
      color: #64748b;
      font-size: 14px;
    }

    #skills {
      background: #f8fbff;
    }

    #contact {
      background: #edf5ff;
      text-align: center;
    }

    #contact p {
      color: #52647a;
      max-width: 570px;
      margin: 0 auto 25px;
    }

    footer {
      padding: 25px 0;
      text-align: center;
      color: #64748b;
      font-size: 13px;
      border-top: 1px solid #e8eef7;
    }

    @media (max-width: 700px) {
      nav {
        padding: 15px 0;
        align-items: flex-start;
        flex-direction: column;
      }

      .nav-links {
        gap: 15px;
      }

      .hero {
        padding: 72px 0 65px;
      }

      h1 {
        letter-spacing: -1px;
      }

      .hero p {
        font-size: 16px;
      }

      section {
        padding: 58px 0;
      }

      .skills-grid,
      .services-grid {
        grid-template-columns: 1fr;
      }

      .button {
        margin: 5px 5px 5px 0;
      }
    }
  </style>
</head>

<body>
  <header>
    <nav class="container">
      <a href="#home" class="logo">JOY MOHON.</a>

      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-content">
        <div class="eyebrow">Digital Marketing & Web Development</div>

        <h1>Hello, I'm <span>Joy Mohon.</span></h1>

        <p>
          I help businesses build their digital presence through
          digital marketing, SEO, online advertising and modern
          web solutions.
        </p>

        <a href="#services" class="button">Explore My Services ↗</a>
        <a href="#about" class="button button-outline">About Me</a>
      </div>
    </section>

    <section id="about">
      <div class="container">
        <h2 class="section-title">About Me</h2>
        <p class="section-intro">
          Passionate about digital growth and technology.
        </p>

        <div class="about">
          I'm Joy Mohon, a digital marketing and web development
          learner focused on helping businesses improve their
          online visibility, reach their audiences and grow.
          I also have an interest in AI automation and practical
          digital solutions.
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2 class="section-title">My Skills</h2>
        <p class="section-intro">
          Digital skills I'm learning and developing.
        </p>

        <div class="skills-grid">
          <article class="card">
            <div class="card-icon">🔎</div>
            <h3>SEO</h3>
            <p>Keyword research, on-page SEO and website optimization.</p>
          </article>

          <article class="card">
            <div class="card-icon">📈</div>
            <h3>Digital Marketing</h3>
            <p>Content strategy, social media and audience research.</p>
          </article>

          <article class="card">
            <div class="card-icon">🎯</div>
            <h3>Meta & Google Ads</h3>
            <p>Online advertising and campaign optimization.</p>
          </article>

          <article class="card">
            <div class="card-icon">💻</div>
            <h3>Web Development</h3>
            <p>Building responsive websites with HTML and CSS.</p>
          </article>

          <article class="card">
            <div class="card-icon">🤖</div>
            <h3>AI Automation</h3>
            <p>Exploring AI-powered workflows and automation tools.</p>
          </article>

          <article class="card">
            <div class="card-icon">📱</div>
            <h3>Social Media</h3>
            <p>Social media marketing and content planning.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="services">
      <div class="container">
        <h2 class="section-title">My Services</h2>
        <p class="section-intro">
          Digital solutions to help businesses grow online.
        </p>

        <div class="services-grid">
          <article class="card">
            <div class="card-icon">🌐</div>
            <h3>SEO Services</h3>
            <p>Improve website structure, content and search visibility.</p>
          </article>

          <article class="card">
            <div class="card-icon">📢</div>
            <h3>Digital Advertising</h3>
            <p>Plan and manage advertising campaigns for businesses.</p>
          </article>

          <article class="card">
            <div class="card-icon">🛠️</div>
            <h3>Website Creation</h3>
            <p>Create simple, responsive websites for an online presence.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container">
        <h2 class="section-title">Let's Connect</h2>
        <p>
          Have a project or want to discuss a digital solution?
          Get in touch with me.
        </p>

        <a class="button" href="mailto:your-email@example.com">
          Contact Me ✉
        </a>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © 2026 Joy Mohon. All rights reserved.
    </div>
  </footer>
</body>
</html>

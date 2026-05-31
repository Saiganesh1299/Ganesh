<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Sai Ganesh Bandikattu | Finance Professional</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=DM+Sans:wght@300;400;500;600&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet"/>
<style>
  :root {
    --gold: #C9A84C;
    --gold-light: #E8C97A;
    --gold-dark: #8B6914;
    --navy: #0A1628;
    --navy-mid: #122040;
    --navy-light: #1C305C;
    --cream: #F5F0E8;
    --cream-dark: #E8E0D0;
    --text-light: #C8D4E8;
    --text-muted: #8899BB;
    --white: #FFFFFF;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--navy);
    color: var(--text-light);
    overflow-x: hidden;
  }

  /* ── NOISE TEXTURE OVERLAY ── */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none; z-index: 0; opacity: 0.4;
  }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    display: flex; justify-content: space-between; align-items: center;
    padding: 1.2rem 3rem;
    background: rgba(10,22,40,0.85);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid rgba(201,168,76,0.15);
  }

  .nav-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.1rem;
    color: var(--gold);
    letter-spacing: 0.05em;
  }

  .nav-links {
    display: flex; gap: 2rem; list-style: none;
  }

  .nav-links a {
    font-size: 0.8rem;
    font-weight: 500;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--text-muted);
    text-decoration: none;
    transition: color 0.3s;
  }

  .nav-links a:hover { color: var(--gold); }

  /* ── HERO ── */
  #hero {
    min-height: 100vh;
    display: flex; align-items: center;
    padding: 6rem 3rem 4rem;
    position: relative;
    overflow: hidden;
  }

  .hero-bg-lines {
    position: absolute; inset: 0; pointer-events: none;
  }

  .hero-bg-lines::before {
    content: '';
    position: absolute;
    top: -20%; right: -10%;
    width: 700px; height: 700px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(201,168,76,0.08) 0%, transparent 70%);
  }

  .hero-bg-lines::after {
    content: '';
    position: absolute;
    bottom: -10%; left: -5%;
    width: 500px; height: 500px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(28,48,92,0.6) 0%, transparent 70%);
  }

  .hero-inner {
    max-width: 1200px; margin: 0 auto; width: 100%;
    display: grid; grid-template-columns: 1fr auto;
    gap: 4rem; align-items: center;
    position: relative; z-index: 1;
  }

  .hero-tag {
    display: inline-block;
    font-family: 'DM Mono', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    border: 1px solid rgba(201,168,76,0.3);
    padding: 0.35rem 0.9rem;
    margin-bottom: 1.5rem;
    border-radius: 2px;
    animation: fadeUp 0.8s ease both;
  }

  h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(3rem, 6vw, 5.5rem);
    font-weight: 900;
    line-height: 1.05;
    color: var(--white);
    animation: fadeUp 0.8s 0.1s ease both;
  }

  h1 span { color: var(--gold); }

  .hero-subtitle {
    font-size: 1.05rem;
    color: var(--text-muted);
    margin-top: 1.2rem;
    line-height: 1.7;
    max-width: 520px;
    animation: fadeUp 0.8s 0.2s ease both;
  }

  .hero-cta {
    display: flex; gap: 1rem; margin-top: 2.5rem;
    animation: fadeUp 0.8s 0.3s ease both;
  }

  .btn-primary {
    display: inline-block;
    padding: 0.85rem 2rem;
    background: linear-gradient(135deg, var(--gold), var(--gold-dark));
    color: var(--navy);
    font-weight: 600;
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    text-decoration: none;
    border-radius: 2px;
    transition: transform 0.2s, box-shadow 0.2s;
    box-shadow: 0 4px 20px rgba(201,168,76,0.3);
  }

  .btn-primary:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 30px rgba(201,168,76,0.4);
  }

  .btn-outline {
    display: inline-block;
    padding: 0.85rem 2rem;
    border: 1px solid rgba(201,168,76,0.4);
    color: var(--gold);
    font-weight: 600;
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    text-decoration: none;
    border-radius: 2px;
    transition: background 0.2s, transform 0.2s;
  }

  .btn-outline:hover {
    background: rgba(201,168,76,0.08);
    transform: translateY(-2px);
  }

  .hero-card {
    background: linear-gradient(135deg, var(--navy-mid), var(--navy-light));
    border: 1px solid rgba(201,168,76,0.2);
    border-radius: 8px;
    padding: 2rem;
    min-width: 220px;
    animation: fadeUp 0.8s 0.4s ease both;
    box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  }

  .hero-card-item {
    text-align: center;
    padding: 1rem 0;
    border-bottom: 1px solid rgba(201,168,76,0.1);
  }

  .hero-card-item:last-child { border-bottom: none; }

  .hero-card-num {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    color: var(--gold);
    font-weight: 700;
  }

  .hero-card-label {
    font-size: 0.72rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text-muted);
    margin-top: 0.25rem;
  }

  /* ── SECTION SHARED ── */
  section { padding: 6rem 3rem; position: relative; }

  .section-inner { max-width: 1100px; margin: 0 auto; }

  .section-eyebrow {
    font-family: 'DM Mono', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.75rem;
  }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 700;
    color: var(--white);
    margin-bottom: 3rem;
    line-height: 1.2;
  }

  .gold-line {
    display: inline-block;
    width: 50px; height: 3px;
    background: linear-gradient(90deg, var(--gold), transparent);
    margin-left: 1rem;
    vertical-align: middle;
  }

  /* ── ABOUT ── */
  #about { background: var(--navy-mid); }

  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: start;
  }

  .about-text p {
    font-size: 1rem;
    line-height: 1.9;
    color: var(--text-light);
    margin-bottom: 1.2rem;
  }

  .about-details {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-top: 2rem;
  }

  .detail-item {
    padding: 1rem 1.2rem;
    background: rgba(10,22,40,0.6);
    border: 1px solid rgba(201,168,76,0.12);
    border-radius: 4px;
  }

  .detail-label {
    font-size: 0.68rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.3rem;
  }

  .detail-value {
    font-size: 0.9rem;
    color: var(--text-light);
    font-weight: 500;
  }

  /* ── EXPERIENCE ── */
  #experience { background: var(--navy); }

  .exp-card {
    background: linear-gradient(135deg, var(--navy-mid), rgba(28,48,92,0.4));
    border: 1px solid rgba(201,168,76,0.15);
    border-left: 3px solid var(--gold);
    border-radius: 6px;
    padding: 2.5rem;
    position: relative;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .exp-card:hover {
    transform: translateX(6px);
    box-shadow: -6px 0 30px rgba(201,168,76,0.1);
  }

  .exp-header {
    display: flex; justify-content: space-between; align-items: flex-start;
    flex-wrap: wrap; gap: 1rem;
    margin-bottom: 1.5rem;
  }

  .exp-role {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    color: var(--white);
    font-weight: 700;
  }

  .exp-company {
    font-size: 0.9rem;
    color: var(--gold);
    font-weight: 500;
    margin-top: 0.3rem;
  }

  .exp-date {
    font-family: 'DM Mono', monospace;
    font-size: 0.75rem;
    color: var(--text-muted);
    letter-spacing: 0.1em;
    background: rgba(201,168,76,0.08);
    padding: 0.35rem 0.8rem;
    border-radius: 2px;
    border: 1px solid rgba(201,168,76,0.15);
    white-space: nowrap;
  }

  .exp-list {
    list-style: none;
    display: flex; flex-direction: column; gap: 0.8rem;
  }

  .exp-list li {
    display: flex; gap: 0.75rem;
    font-size: 0.92rem;
    line-height: 1.7;
    color: var(--text-light);
  }

  .exp-list li::before {
    content: '▸';
    color: var(--gold);
    flex-shrink: 0;
    margin-top: 0.05rem;
    font-size: 0.8rem;
  }

  /* ── SKILLS ── */
  #skills { background: var(--navy-mid); }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
  }

  .skill-card {
    background: rgba(10,22,40,0.7);
    border: 1px solid rgba(201,168,76,0.12);
    border-radius: 6px;
    padding: 1.8rem;
    transition: border-color 0.3s, transform 0.3s;
  }

  .skill-card:hover {
    border-color: rgba(201,168,76,0.35);
    transform: translateY(-4px);
  }

  .skill-icon {
    font-size: 1.5rem;
    margin-bottom: 0.8rem;
  }

  .skill-card h3 {
    font-family: 'Playfair Display', serif;
    font-size: 1.05rem;
    color: var(--white);
    margin-bottom: 1rem;
  }

  .skill-tags {
    display: flex; flex-wrap: wrap; gap: 0.5rem;
  }

  .skill-tag {
    font-size: 0.72rem;
    letter-spacing: 0.05em;
    color: var(--gold-light);
    background: rgba(201,168,76,0.08);
    border: 1px solid rgba(201,168,76,0.2);
    padding: 0.3rem 0.7rem;
    border-radius: 2px;
  }

  /* ── EDUCATION ── */
  #education { background: var(--navy); }

  .edu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1.5rem;
  }

  .edu-card {
    background: linear-gradient(160deg, var(--navy-mid), var(--navy));
    border: 1px solid rgba(201,168,76,0.15);
    border-radius: 6px;
    padding: 1.8rem;
    position: relative;
    overflow: hidden;
    transition: transform 0.3s;
  }

  .edu-card::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, var(--gold), transparent);
  }

  .edu-card:hover { transform: translateY(-4px); }

  .edu-degree {
    font-family: 'Playfair Display', serif;
    font-size: 1.1rem;
    font-weight: 700;
    color: var(--white);
    margin-bottom: 0.4rem;
  }

  .edu-institution {
    font-size: 0.82rem;
    color: var(--text-muted);
    margin-bottom: 0.8rem;
    line-height: 1.4;
  }

  .edu-meta {
    display: flex; justify-content: space-between;
    font-family: 'DM Mono', monospace;
    font-size: 0.72rem;
  }

  .edu-year { color: var(--gold); }
  .edu-score { color: var(--text-muted); }

  /* ── FINANCE KNOWLEDGE ── */
  #finance { background: var(--navy-mid); }

  .finance-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.2rem;
  }

  .finance-item {
    display: flex; align-items: center; gap: 0.8rem;
    padding: 1rem 1.2rem;
    background: rgba(10,22,40,0.5);
    border: 1px solid rgba(201,168,76,0.1);
    border-radius: 4px;
    transition: border-color 0.3s, background 0.3s;
    font-size: 0.88rem;
    color: var(--text-light);
  }

  .finance-item:hover {
    border-color: rgba(201,168,76,0.3);
    background: rgba(201,168,76,0.05);
  }

  .finance-item::before {
    content: '◆';
    color: var(--gold);
    font-size: 0.5rem;
    flex-shrink: 0;
  }

  /* ── ACHIEVEMENTS ── */
  #achievements { background: var(--navy); }

  .ach-list {
    display: flex; flex-direction: column; gap: 1rem;
  }

  .ach-item {
    display: flex; align-items: center; gap: 1.5rem;
    padding: 1.5rem 2rem;
    background: linear-gradient(135deg, var(--navy-mid), rgba(28,48,92,0.3));
    border: 1px solid rgba(201,168,76,0.15);
    border-radius: 6px;
    transition: transform 0.2s;
  }

  .ach-item:hover { transform: translateX(6px); }

  .ach-badge {
    font-size: 1.8rem;
    flex-shrink: 0;
  }

  .ach-title {
    font-size: 1rem;
    font-weight: 600;
    color: var(--white);
    margin-bottom: 0.2rem;
  }

  .ach-body {
    font-size: 0.85rem;
    color: var(--text-muted);
  }

  /* ── CONTACT ── */
  #contact {
    background: linear-gradient(135deg, var(--navy-mid), var(--navy-light));
    text-align: center;
  }

  .contact-links {
    display: flex; justify-content: center; flex-wrap: wrap; gap: 1.5rem;
    margin-top: 2rem;
  }

  .contact-link {
    display: flex; align-items: center; gap: 0.6rem;
    padding: 0.9rem 1.8rem;
    border: 1px solid rgba(201,168,76,0.25);
    border-radius: 4px;
    color: var(--text-light);
    text-decoration: none;
    font-size: 0.88rem;
    transition: all 0.3s;
  }

  .contact-link:hover {
    border-color: var(--gold);
    color: var(--gold);
    background: rgba(201,168,76,0.05);
    transform: translateY(-3px);
  }

  .contact-link svg {
    width: 16px; height: 16px;
    stroke: currentColor; fill: none;
    stroke-width: 2; stroke-linecap: round; stroke-linejoin: round;
  }

  /* ── FOOTER ── */
  footer {
    text-align: center;
    padding: 2rem;
    background: var(--navy);
    border-top: 1px solid rgba(201,168,76,0.1);
    font-size: 0.78rem;
    color: var(--text-muted);
    letter-spacing: 0.05em;
  }

  footer span { color: var(--gold); }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .reveal {
    opacity: 0; transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }

  .reveal.visible {
    opacity: 1; transform: translateY(0);
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 768px) {
    nav { padding: 1rem 1.5rem; }
    .nav-links { display: none; }
    section { padding: 4rem 1.5rem; }
    #hero { padding: 6rem 1.5rem 4rem; }
    .hero-inner { grid-template-columns: 1fr; }
    .hero-card { display: none; }
    .about-grid { grid-template-columns: 1fr; gap: 2rem; }
    .about-details { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">SG · Finance</div>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#finance">Finance</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-bg-lines"></div>
  <div class="hero-inner">
    <div class="hero-content">
      <div class="hero-tag">Fund Accounting &amp; Investment Banking</div>
      <h1>Sai Ganesh<br/><span>Bandikattu</span></h1>
      <p class="hero-subtitle">
        Finance professional with hands-on accounting expertise and deep knowledge in financial markets, derivatives, private equity, and fund operations — ready to deliver precision in every transaction.
      </p>
      <div class="hero-cta">
        <a href="#contact" class="btn-primary">Get In Touch</a>
        <a href="#experience" class="btn-outline">View Experience</a>
      </div>
    </div>
    <div class="hero-card">
      <div class="hero-card-item">
        <div class="hero-card-num">MBA</div>
        <div class="hero-card-label">Finance &amp; Business</div>
      </div>
      <div class="hero-card-item">
        <div class="hero-card-num">2+</div>
        <div class="hero-card-label">Years Experience</div>
      </div>
      <div class="hero-card-item">
        <div class="hero-card-num">CFI</div>
        <div class="hero-card-label">Certified</div>
      </div>
      <div class="hero-card-item">
        <div class="hero-card-num">AP·AR</div>
        <div class="hero-card-label">Core Expertise</div>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-inner">
    <div class="section-eyebrow">About Me</div>
    <h2 class="section-title">Who I Am <span class="gold-line"></span></h2>
    <div class="about-grid reveal">
      <div class="about-text">
        <p>
          I am a finance and accounting professional from Nellore, Andhra Pradesh, currently based in Hyderabad. With an MBA and a B.Com background, I bring a solid academic foundation combined with real-world accounts executive experience at Cloudray.
        </p>
        <p>
          My goal is to contribute to an organization in fund accounting or investment banking — roles where precision, market knowledge, and analytical discipline make the difference. I have trained extensively in financial markets, derivatives, private equity structures, mutual funds, NAV calculation, and AML/KYC compliance.
        </p>
        <p>
          I am a self-motivated learner who has earned certifications from NPTEL and the Corporate Finance Institute, and I am committed to continuous professional development in the finance industry.
        </p>
      </div>
      <div>
        <div class="about-details">
          <div class="detail-item">
            <div class="detail-label">Location</div>
            <div class="detail-value">Hyderabad, India</div>
          </div>
          <div class="detail-item">
            <div class="detail-label">Date of Birth</div>
            <div class="detail-value">16 February 1999</div>
          </div>
          <div class="detail-item">
            <div class="detail-label">Languages</div>
            <div class="detail-value">English, Telugu</div>
          </div>
          <div class="detail-item">
            <div class="detail-label">Target Roles</div>
            <div class="detail-value">Fund Accounting · IB</div>
          </div>
          <div class="detail-item">
            <div class="detail-label">Email</div>
            <div class="detail-value" style="font-size:0.78rem">bandikattusaiganesh<br/>1926@gmail.com</div>
          </div>
          <div class="detail-item">
            <div class="detail-label">MS Excel</div>
            <div class="detail-value">Advanced</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="section-inner">
    <div class="section-eyebrow">Work History</div>
    <h2 class="section-title">Experience <span class="gold-line"></span></h2>
    <div class="exp-card reveal">
      <div class="exp-header">
        <div>
          <div class="exp-role">Accounts Executive</div>
          <div class="exp-company">Cloudray</div>
        </div>
        <div class="exp-date">Prior to 2024</div>
      </div>
      <ul class="exp-list">
        <li>Proficiently managed client invoicing processes using Akken Cloud, ensuring accurate and timely billing aligned with consultant time sheets.</li>
        <li>Implemented effective payment follow-up procedures that optimised cash flow and minimised outstanding balances.</li>
        <li>Conducted regular reviews of accounts payable aging reports, proactively addressing overdue payments and generating weekly due reports for timely collections.</li>
        <li>Performed bank reconciliation activities with precision, compiling data for US payroll processing with accuracy.</li>
        <li>Maintained comprehensive databases of sub-vendors, candidates, and clients — ensuring data integrity and accessibility for streamlined operations.</li>
      </ul>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-inner">
    <div class="section-eyebrow">Capabilities</div>
    <h2 class="section-title">Technical &amp; Soft Skills <span class="gold-line"></span></h2>
    <div class="skills-grid">
      <div class="skill-card reveal">
        <div class="skill-icon">📊</div>
        <h3>Accounting &amp; Finance</h3>
        <div class="skill-tags">
          <span class="skill-tag">Accounts Payable</span>
          <span class="skill-tag">Accounts Receivable</span>
          <span class="skill-tag">Bank Reconciliation</span>
          <span class="skill-tag">Invoicing</span>
          <span class="skill-tag">Payroll Processing</span>
          <span class="skill-tag">Cash Flow Management</span>
        </div>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">💹</div>
        <h3>Financial Markets</h3>
        <div class="skill-tags">
          <span class="skill-tag">Primary Market</span>
          <span class="skill-tag">Secondary Market</span>
          <span class="skill-tag">Money Market</span>
          <span class="skill-tag">Market Products</span>
          <span class="skill-tag">NAV Calculation</span>
        </div>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">🖥️</div>
        <h3>Technology</h3>
        <div class="skill-tags">
          <span class="skill-tag">MS Excel (Advanced)</span>
          <span class="skill-tag">MS Office Suite</span>
          <span class="skill-tag">Akken Cloud</span>
          <span class="skill-tag">Data Management</span>
        </div>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">🤝</div>
        <h3>Professional Skills</h3>
        <div class="skill-tags">
          <span class="skill-tag">Positive Attitude</span>
          <span class="skill-tag">High Flexibility</span>
          <span class="skill-tag">Formal Accounting</span>
          <span class="skill-tag">Team Collaboration</span>
          <span class="skill-tag">Attention to Detail</span>
        </div>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">🔒</div>
        <h3>Compliance &amp; Risk</h3>
        <div class="skill-tags">
          <span class="skill-tag">AML</span>
          <span class="skill-tag">KYC</span>
          <span class="skill-tag">CDD / EDD</span>
          <span class="skill-tag">PEPs</span>
          <span class="skill-tag">Red Flags</span>
          <span class="skill-tag">Corporate Actions</span>
        </div>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">📈</div>
        <h3>Derivatives &amp; Funds</h3>
        <div class="skill-tags">
          <span class="skill-tag">Forwards</span>
          <span class="skill-tag">Futures</span>
          <span class="skill-tag">Options</span>
          <span class="skill-tag">Swaps</span>
          <span class="skill-tag">Mutual Funds</span>
          <span class="skill-tag">Hedge Funds</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="section-inner">
    <div class="section-eyebrow">Academic Background</div>
    <h2 class="section-title">Education <span class="gold-line"></span></h2>
    <div class="edu-grid">
      <div class="edu-card reveal">
        <div class="edu-degree">MBA</div>
        <div class="edu-institution">Narayana Engineering College</div>
        <div class="edu-meta">
          <span class="edu-year">2022</span>
          <span class="edu-score">65%</span>
        </div>
      </div>
      <div class="edu-card reveal">
        <div class="edu-degree">B.COM</div>
        <div class="edu-institution">Vikrama Simhapuri University</div>
        <div class="edu-meta">
          <span class="edu-year">2019</span>
          <span class="edu-score">69%</span>
        </div>
      </div>
      <div class="edu-card reveal">
        <div class="edu-degree">Intermediate / 12th</div>
        <div class="edu-institution">Chandra Reddy Jr College</div>
        <div class="edu-meta">
          <span class="edu-year">2016</span>
          <span class="edu-score">65%</span>
        </div>
      </div>
      <div class="edu-card reveal">
        <div class="edu-degree">SSC / 10th</div>
        <div class="edu-institution">Saint Nobel School</div>
        <div class="edu-meta">
          <span class="edu-year">2014</span>
          <span class="edu-score">60%</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FINANCE KNOWLEDGE -->
<section id="finance">
  <div class="section-inner">
    <div class="section-eyebrow">Domain Knowledge</div>
    <h2 class="section-title">Finance Courseware <span class="gold-line"></span></h2>
    <div class="finance-grid">
      <div class="finance-item reveal">Financial Markets — Primary &amp; Secondary</div>
      <div class="finance-item reveal">Money Market &amp; Market Products</div>
      <div class="finance-item reveal">Derivatives — Forwards, Futures &amp; Options</div>
      <div class="finance-item reveal">Swap Instruments</div>
      <div class="finance-item reveal">Private Equity — Structure &amp; Management Fees</div>
      <div class="finance-item reveal">Waterfall Provisions &amp; PE Strategies</div>
      <div class="finance-item reveal">Mutual Funds — Structure &amp; Types</div>
      <div class="finance-item reveal">NAV Calculation</div>
      <div class="finance-item reveal">Hedge Funds</div>
      <div class="finance-item reveal">Corporate Actions</div>
      <div class="finance-item reveal">AML / KYC — Stages &amp; Red Flags</div>
      <div class="finance-item reveal">CDD, EDD &amp; PEPs Compliance</div>
    </div>
  </div>
</section>

<!-- ACHIEVEMENTS -->
<section id="achievements">
  <div class="section-inner">
    <div class="section-eyebrow">Certifications &amp; Awards</div>
    <h2 class="section-title">Achievements <span class="gold-line"></span></h2>
    <div class="ach-list">
      <div class="ach-item reveal">
        <div class="ach-badge">🏅</div>
        <div>
          <div class="ach-title">NPTEL Elite Certificate</div>
          <div class="ach-body">Consumer Behavior — Awarded Elite status by the National Programme on Technology Enhanced Learning (NPTEL), IIT.</div>
        </div>
      </div>
      <div class="ach-item reveal">
        <div class="ach-badge">📜</div>
        <div>
          <div class="ach-title">CFI Certificate — Accounting Fundamentals</div>
          <div class="ach-body">Certified by the Corporate Finance Institute (CFI), globally recognized in finance and investment banking education.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-inner">
    <div class="section-eyebrow">Let's Connect</div>
    <h2 class="section-title">Contact <span class="gold-line"></span></h2>
    <p style="color:var(--text-muted);max-width:500px;margin:0 auto 1rem;font-size:0.95rem;line-height:1.7;">
      Open to opportunities in fund accounting, investment banking, and finance operations. Feel free to reach out.
    </p>
    <div class="contact-links">
      <a href="mailto:bandikattusaiganesh1926@gmail.com" class="contact-link">
        <svg viewBox="0 0 24 24"><rect x="2" y="4" width="20" height="16" rx="2"/><polyline points="2,4 12,13 22,4"/></svg>
        bandikattusaiganesh1926@gmail.com
      </a>
      <a href="https://github.com/" target="_blank" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>
        GitHub Profile
      </a>
      <a href="https://www.linkedin.com/in/sai-ganesh-bandikattu" target="_blank" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
        LinkedIn
      </a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2025 <span>Sai Ganesh Bandikattu</span> · Fund Accounting &amp; Finance Professional · Hyderabad, India</p>
</footer>

<script>
  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        setTimeout(() => entry.target.classList.add('visible'), i * 60);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  // Nav active link highlight
  const sections = document.querySelectorAll('section[id]');
  const navLinks = document.querySelectorAll('.nav-links a');
  window.addEventListener('scroll', () => {
    let current = '';
    sections.forEach(s => {
      if (window.scrollY >= s.offsetTop - 120) current = s.id;
    });
    navLinks.forEach(a => {
      a.style.color = a.getAttribute('href') === '#' + current
        ? 'var(--gold)' : '';
    });
  });
</script>
</body>
</html>

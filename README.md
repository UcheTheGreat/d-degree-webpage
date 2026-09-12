<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#E4232B">
<title>D-Degree Digital Hub — Digital Growth, Branding &amp; Compliance from Lagos</title>
<meta name="description" content="D-Degree Digital Hub is a Lagos-based digital innovation, marketing and project facilitation agency helping SMEs, brands and institutions grow, get visible, and stay compliant.">
<link rel="icon" type="image/png" href="logo.png">
<link rel="shortcut icon" type="image/png" href="logo.png">
<style>
/* ==================================================================
   D-Degree Digital Hub — Enhanced with Nexus Studio Features
   ================================================================== */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');

:root{
  --bg:            #FFFFFF;
  --ink:           #1D1D1F;
  --ink-soft:      #6E6E73;
  --white:         #ffffff;
  --dark-bg:       #0F0F0F;

  --teal:          #E4232B;
  --amber:         #FF4D6D;
  --violet:        #FF6B6B;

  --glass-fill:    rgba(255,255,255,0.50);
  --glass-fill-2:  rgba(255,255,255,0.68);
  --glass-border:  rgba(255,255,255,0.75);
  --glass-shadow:  0 8px 32px rgba(29,29,31,0.08), 0 1px 1px rgba(255,255,255,0.6) inset;

  --dark-glass-fill:   rgba(20,20,30,0.38);
  --dark-glass-border: rgba(255,255,255,0.18);

  --radius-lg: 32px;
  --radius-md: 22px;
  --radius-sm: 14px;

  --font: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  --max: 1180px;
}

/* Dark Mode Theme */
[data-theme="dark"] {
  --bg:            #0F0F0F;
  --ink:           #F5F5F7;
  --ink-soft:      #A0A0A0;
  --white:         #1D1D1F;
  --glass-fill:    rgba(255,255,255,0.08);
  --glass-fill-2:  rgba(255,255,255,0.12);
  --glass-border:  rgba(255,255,255,0.15);
  --glass-shadow:  0 8px 32px rgba(0,0,0,0.4), 0 1px 1px rgba(255,255,255,0.1) inset;
}

[data-theme="dark"] .bg-field {
  background: #0F0F0F;
}

[data-theme="dark"] .blob-1 { background:radial-gradient(circle, rgba(228,35,43,0.15), transparent 70%); }
[data-theme="dark"] .blob-2 { background:radial-gradient(circle, rgba(255,107,107,0.12), transparent 70%); }
[data-theme="dark"] .blob-3 { background:radial-gradient(circle, rgba(255,77,109,0.1), transparent 70%); }

*{ box-sizing:border-box; }
html{ scroll-behavior:smooth; transition:background-color 0.3s ease, color 0.3s ease; }
body{
  margin:0;
  font-family:var(--font);
  color:var(--ink);
  background:var(--bg);
  -webkit-font-smoothing:antialiased;
  overflow-x:hidden;
  transition:background-color 0.3s ease, color 0.3s ease;
}

img,svg{ display:block; max-width:100%; }
a{ color:inherit; text-decoration:none; }

:focus-visible{ outline:2px solid var(--violet); outline-offset:3px; border-radius:4px; }

h1,h2,h3,h4{ margin:0 0 0.4em; font-weight:600; letter-spacing:-0.02em; line-height:1.08; }
p{ margin:0 0 1em; color:var(--ink-soft); line-height:1.6; }

.container{ max-width:var(--max); margin:0 auto; padding:0 32px; position:relative; z-index:2; }

/* Background Field */
.bg-field{
  position:fixed; inset:0; z-index:0; overflow:hidden; pointer-events:none;
  background:#FFFFFF;
}
.blob{
  position:absolute; border-radius:50%; filter:blur(70px); opacity:0.55;
}
.blob-1{ width:520px; height:520px; top:-140px; left:-120px; background:radial-gradient(circle, var(--teal), transparent 70%); }
.blob-2{ width:480px; height:480px; top:280px; right:-160px; background:radial-gradient(circle, var(--violet), transparent 70%); }
.blob-3{ width:420px; height:420px; bottom:-160px; left:20%; background:radial-gradient(circle, var(--amber), transparent 70%); }

@media (prefers-reduced-motion:no-preference){
  .blob{ animation:drift 22s ease-in-out infinite alternate; }
  .blob-2{ animation-duration:26s; }
  .blob-3{ animation-duration:30s; }
  @keyframes drift{
    from{ transform:translate(0,0) scale(1); }
    to{ transform:translate(30px,40px) scale(1.08); }
  }
}

/* Glass Utility */
.glass{
  background:var(--glass-fill);
  backdrop-filter:blur(24px) saturate(160%);
  -webkit-backdrop-filter:blur(24px) saturate(160%);
  border:1px solid var(--glass-border);
  border-radius:var(--radius-lg);
  box-shadow:var(--glass-shadow);
}
.glass-dark{
  background:var(--dark-glass-fill);
  backdrop-filter:blur(24px) saturate(160%);
  -webkit-backdrop-filter:blur(24px) saturate(160%);
  border:1px solid var(--dark-glass-border);
  border-radius:var(--radius-lg);
  box-shadow:0 8px 40px rgba(0,0,0,0.25);
  color:#fff;
}
.glass-dark p{ color:rgba(255,255,255,0.72); }
.glass-dark h1,.glass-dark h2,.glass-dark h3,.glass-dark h4{ color:#fff; }

/* Navigation */
.nav-wrap{ position:sticky; top:18px; z-index:50; padding:0 20px; }
.nav{
  max-width:var(--max); margin:0 auto;
  display:flex; align-items:center; justify-content:space-between;
  padding:12px 14px 12px 22px;
}
.brand{ display:flex; align-items:center; gap:12px; font-weight:700; font-size:1.1rem; }
.brand-logo{ width:50px; height:50px; object-fit:contain; display:flex; align-items:center; justify-content:center; }
.nav-links{ display:flex; gap:8px; list-style:none; margin:0; padding:0; }
.nav-links a{
  font-size:0.92rem; font-weight:500; padding:9px 16px; border-radius:999px;
  color:var(--ink);
}
.nav-links a:hover{ background:rgba(29,29,31,0.06); }
.nav-links a[aria-current="page"]{ background:rgba(29,29,31,0.08); }
.nav-actions{ display:flex; gap:8px; align-items:center; }
.theme-toggle{
  background:transparent; border:1px solid rgba(29,29,31,0.2); color:var(--ink);
  padding:9px 12px; border-radius:999px; cursor:pointer; font-size:1.1rem;
  display:flex; align-items:center; justify-content:center; width:38px; height:38px;
  transition:all 0.3s ease;
}
.theme-toggle:hover{ background:rgba(29,29,31,0.08); }
[data-theme="dark"] .theme-toggle{
  border-color:rgba(255,255,255,0.2);
}
[data-theme="dark"] .theme-toggle:hover{ background:rgba(255,255,255,0.1); }
.nav-cta{
  background:var(--ink); color:#fff !important; padding:10px 20px; border-radius:999px;
  font-weight:600; font-size:0.88rem;
}
.nav-cta:hover{ background:#000; }

.nav.glass{
  background:var(--teal);
  border:1px solid rgba(255,255,255,0.35);
  box-shadow:0 8px 32px rgba(228,35,43,0.28), 0 1px 1px rgba(255,255,255,0.25) inset;
}
.nav.glass .brand{ color:#fff; }
.nav.glass .nav-links a{ color:#fff; }
.nav.glass .nav-links a:hover{ background:rgba(255,255,255,0.16); }
.nav.glass .nav-links a[aria-current="page"]{ background:rgba(255,255,255,0.26); }
.nav.glass .theme-toggle{
  background:rgba(255,255,255,0.14); border-color:rgba(255,255,255,0.3); color:#fff;
}
.nav.glass .theme-toggle:hover{ background:rgba(255,255,255,0.22); }
.nav.glass .nav-cta{ background:#fff; color:#E4232B !important; }
.nav.glass .nav-cta:hover{ background:#f2f2f2; }

/* Buttons */
.btn{
  display:inline-flex; align-items:center; gap:8px; font-weight:600; font-size:0.95rem;
  padding:14px 28px; border-radius:999px; cursor:pointer; border:1px solid transparent;
}
.btn-primary{ background:var(--ink); color:#fff; }
.btn-primary:hover{ background:#000; }
.btn-glass{
  background:var(--glass-fill-2); border:1px solid var(--glass-border);
  backdrop-filter:blur(16px); color:var(--ink);
}
.btn-glass:hover{ background:rgba(255,255,255,0.85); }
.btn-glass-dark{
  background:rgba(255,255,255,0.14); border:1px solid rgba(255,255,255,0.3);
  backdrop-filter:blur(16px); color:#fff;
}
.btn-glass-dark:hover{ background:rgba(255,255,255,0.22); }

/* Hero Section */
.hero{ padding:96px 0 40px; text-align:center; }
.hero-kicker{
  display:inline-block; font-size:0.85rem; font-weight:600; color:var(--ink-soft);
  background:var(--glass-fill-2); border:1px solid var(--glass-border);
  padding:8px 18px; border-radius:999px; margin-bottom:28px; backdrop-filter:blur(10px);
}
.hero h1{
  font-size:clamp(2.6rem, 6vw, 4.6rem); font-weight:700; letter-spacing:-0.03em;
  max-width:16ch; margin:0 auto 22px;
}
.hero p.lead{ font-size:1.2rem; max-width:46ch; margin:0 auto 36px; color:var(--ink-soft); }
.hero-actions{ display:flex; gap:14px; justify-content:center; flex-wrap:wrap; margin-bottom:56px; }

.hero-visual{
  max-width:920px; margin:0 auto; padding:36px; text-align:left;
}
.hero-visual .visual-inner{ display:grid; grid-template-columns:1fr 1fr; gap:28px; align-items:center; }

@media (prefers-reduced-motion:no-preference){
  .fade-up{ animation:fadeUp 0.8s cubic-bezier(.2,.7,.2,1) both; }
  .fade-up.d1{ animation-delay:0.05s; }
  .fade-up.d2{ animation-delay:0.16s; }
  .fade-up.d3{ animation-delay:0.27s; }
  .fade-up.d4{ animation-delay:0.38s; }
  @keyframes fadeUp{ from{ opacity:0; transform:translateY(18px);} to{ opacity:1; transform:translateY(0);} }
}

/* Sections */
section{ padding:64px 0; }
.section-head{ max-width:640px; margin:0 auto 44px; text-align:center; }
.section-head h2{ font-size:clamp(1.8rem, 3vw, 2.5rem); }
.section-head.left{ text-align:left; margin-left:0; }

/* Tile Grid */
.tile-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:20px; }
.tile{ padding:32px; }
.tile .icon-wrap{
  width:52px; height:52px; border-radius:16px; display:flex; align-items:center; justify-content:center;
  margin-bottom:20px; background:rgba(255,255,255,0.6); border:1px solid var(--glass-border);
}
.tile h3{ font-size:1.1rem; margin-bottom:8px; }
.tile p{ font-size:0.95rem; margin:0; }

/* Stats Grid */
.stats-grid{ display:grid; grid-template-columns:repeat(4,1fr); gap:20px; }
.stat-card{ padding:32px; text-align:center; }
.stat-number{ font-size:2.8rem; font-weight:700; color:var(--teal); margin:0 0 8px; }
.stat-label{ font-size:0.95rem; color:var(--ink-soft); margin:0; }

/* Process Timeline */
.timeline{ display:grid; grid-template-columns:repeat(4,1fr); gap:20px; position:relative; }
.timeline::before{
  content:''; position:absolute; top:50px; left:0; right:0; height:2px;
  background:linear-gradient(to right, var(--teal), transparent); z-index:0;
}
.timeline-item{ padding:32px 20px; text-align:center; position:relative; z-index:1; }
.timeline-dot{
  width:40px; height:40px; border-radius:50%; background:var(--teal);
  color:#fff; display:flex; align-items:center; justify-content:center;
  margin:0 auto 20px; font-weight:700; border:3px solid #fff;
}
.timeline-item h3{ font-size:1rem; margin-bottom:8px; }
.timeline-item p{ font-size:0.9rem; margin:0; }

/* Pills Row */
.pill-row{ display:flex; gap:16px; flex-wrap:wrap; justify-content:center; }
.pill{
  padding:10px 20px; border-radius:999px; font-size:0.9rem; font-weight:500;
  background:var(--glass-fill-2); border:1px solid var(--glass-border);
}

/* Service Panel */
.service-panel{ padding:8px; }
.service-item{
  display:grid; grid-template-columns:64px 1fr 1fr; gap:28px; align-items:center;
  padding:28px 24px; border-radius:var(--radius-md);
}
.service-item + .service-item{ margin-top:8px; }
.service-item:hover{ background:rgba(255,255,255,0.35); }
.service-icon{
  width:56px; height:56px; border-radius:16px; display:flex; align-items:center; justify-content:center;
  background:linear-gradient(135deg, rgba(228,35,43,0.18), rgba(255,107,107,0.14));
}
.service-item h3{ font-size:1.15rem; margin-bottom:4px; }
.service-detail{ list-style:none; margin:0; padding:0; font-size:0.9rem; color:var(--ink-soft); }
.service-detail li{ padding:3px 0; }

@media (max-width: 860px){
  .service-item{ grid-template-columns:1fr; text-align:left; }
  .tile-grid{ grid-template-columns:1fr; }
  .stats-grid{ grid-template-columns:1fr 1fr; }
  .timeline{ grid-template-columns:1fr 1fr; }
  .timeline::before{ display:none; }
}

/* Quote Grid */
.quote-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:20px; }
.quote-card{ padding:30px; }
.quote-card p.quote-text{ font-size:1.02rem; color:var(--ink); margin-bottom:18px; }
.quote-attr{ font-size:0.85rem; color:var(--ink-soft); }
.quote-attr strong{ color:var(--ink); display:block; margin-bottom:2px; }

/* Work Grid */
.work-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:20px; }
.work-card{ padding:30px; }
.work-tag{
  display:inline-block; font-size:0.78rem; font-weight:600; color:var(--teal);
  background:rgba(228,35,43,0.12); padding:5px 12px; border-radius:999px; margin-bottom:14px;
}
.work-card h3{ font-size:1.1rem; }

/* FAQ Grid */
.faq-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:20px; }
.faq-item{ padding:32px; }
.faq-item h3{ font-size:1.1rem; margin-bottom:12px; cursor:pointer; }
.faq-item p{ font-size:0.95rem; margin:0; }

/* Pricing Grid */
.pricing-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:20px; }
.pricing-card{ padding:40px 32px; text-align:center; }
.pricing-card.featured{
  transform:scale(1.05); border-color:var(--teal);
}
.price{ font-size:3rem; font-weight:700; color:var(--teal); margin:20px 0 8px; }
.price-period{ font-size:0.9rem; color:var(--ink-soft); }
.pricing-features{ list-style:none; margin:28px 0; padding:0; text-align:left; }
.pricing-features li{
  padding:12px 0; border-bottom:1px solid rgba(29,29,31,0.1);
  font-size:0.95rem;
}
.pricing-features li:last-child{ border-bottom:none; }

/* CTA Banner */
.cta-section{ padding:40px 0 96px; }
.cta-glass{
  padding:64px 48px; text-align:center;
  background:linear-gradient(135deg, rgba(228,35,43,0.85), rgba(255,107,107,0.85));
  border:1px solid rgba(255,255,255,0.35);
}
.cta-glass h2{ color:#fff; max-width:22ch; margin:0 auto 14px; }
.cta-glass p{ color:rgba(255,255,255,0.85); max-width:44ch; margin:0 auto 30px; }

/* Footer */
footer{ padding:20px 20px 40px; }
.footer-glass{ padding:44px 40px; }
.footer-grid{ display:grid; grid-template-columns:1.4fr 1fr 1fr 1fr; gap:28px; margin-bottom:32px; }
.footer-grid h4{ font-size:0.9rem; margin-bottom:12px; }
.footer-grid a, .footer-grid p{ display:block; font-size:0.88rem; color:var(--ink-soft); padding:4px 0; margin:0; }
.footer-grid a:hover{ color:var(--ink); }
.footer-bottom{
  border-top:1px solid rgba(29,29,31,0.1); padding-top:20px; font-size:0.82rem; color:var(--ink-soft);
  display:flex; justify-content:space-between; flex-wrap:wrap; gap:8px;
}

/* Form */
.contact-grid{ display:grid; grid-template-columns:0.85fr 1.15fr; gap:24px; align-items:start; }
.info-glass{ padding:36px; }
.info-row{ padding:16px 0; border-bottom:1px solid rgba(29,29,31,0.08); }
.info-row:last-child{ border-bottom:none; }
.info-row h4{ font-size:0.82rem; font-weight:600; color:var(--ink-soft); margin-bottom:4px; }
.info-row p{ margin:0; color:var(--ink); font-weight:500; }

.form-glass{ padding:36px; }
.field{ margin-bottom:18px; }
.field label{ display:block; font-size:0.88rem; font-weight:600; margin-bottom:8px; }
.field input, .field select, .field textarea{
  width:100%; padding:13px 16px; border-radius:14px; border:1px solid rgba(29,29,31,0.14);
  background:rgba(255,255,255,0.6); font-family:var(--font); font-size:0.95rem; color:var(--ink);
  transition:all 0.3s ease;
}
.field input:focus, .field select:focus, .field textarea:focus{
  outline:none; border-color:var(--violet); background:rgba(255,255,255,0.9);
  box-shadow:0 0 0 3px rgba(255,107,107,0.15);
}
.field textarea{ min-height:120px; resize:vertical; }

[data-theme="dark"] .field input,
[data-theme="dark"] .field select,
[data-theme="dark"] .field textarea {
  background:rgba(255,255,255,0.08);
  border-color:rgba(255,255,255,0.15);
  color:var(--ink);
}

[data-theme="dark"] .field input:focus,
[data-theme="dark"] .field select:focus,
[data-theme="dark"] .field textarea:focus {
  background:rgba(255,255,255,0.12);
  border-color:var(--violet);
  box-shadow:0 0 0 3px rgba(255,107,107,0.25);
}

@media (max-width: 900px){
  .contact-grid{ grid-template-columns:1fr; }
  .quote-grid{ grid-template-columns:1fr; }
  .work-grid{ grid-template-columns:1fr; }
  .pricing-grid{ grid-template-columns:1fr; }
  .faq-grid{ grid-template-columns:1fr; }
  .footer-grid{ grid-template-columns:1fr 1fr; }
  .hero-visual .visual-inner{ grid-template-columns:1fr; }
  .nav-links{ display:none; }
}

/* Blog Preview */
.blog-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:20px; }
.blog-card{ padding:20px; }
.blog-date{ font-size:0.82rem; color:var(--ink-soft); margin-bottom:8px; display:block; }
.blog-card h3{ font-size:1rem; margin-bottom:8px; }
.blog-excerpt{ font-size:0.9rem; margin-bottom:16px; }
.read-more{ color:var(--teal); font-weight:600; font-size:0.9rem; }
</style>
</head>
<body>
<div class="bg-field"><span class="blob blob-1"></span><span class="blob blob-2"></span><span class="blob blob-3"></span></div>

<div class="nav-wrap">
  <div class="nav glass">
    <a href="#hero" class="brand">
      <img class="brand-logo" src="logo.png" alt="D-Degree Digital Hub Logo" title="D-Degree Digital Hub">
      <span style="display:none;">D-Degree</span>
    </a>
    <ul class="nav-links">
      <li><a href="#hero">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#process">Process</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="nav-actions">
      <button class="theme-toggle" id="theme-toggle" title="Toggle dark mode" aria-label="Toggle dark mode">
        <span id="theme-icon">🌙</span>
      </button>
      <a href="#contact" class="nav-cta">Partner With Us</a>
    </div>
  </div>
</div>

<!-- HERO -->
<section class="hero" id="hero">
  <div class="container">
    <span class="hero-kicker fade-up d1">Lagos-Built · Market-Ready</span>
    <h1 class="fade-up d2">Growth and visibility, made effortless</h1>
    <p class="lead fade-up d3">D-Degree Digital Hub designs the marketing, technology and compliance systems that take SMEs, brands and institutions from unseen to unmissable.</p>
    <div class="hero-actions fade-up d4">
      <a href="#contact" class="btn btn-primary">Partner With Us</a>
      <a href="#services" class="btn btn-glass">See what we build</a>
    </div>

    <div class="hero-visual glass fade-up d4">
      <div class="visual-inner">
        <div>
          <div class="icon-wrap" style="background:linear-gradient(135deg, rgba(228,35,43,0.25), rgba(255,107,107,0.2)); margin-bottom:16px;">
            <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M3 17L9 11L13 15L21 5" stroke="#E4232B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          </div>
          <h3 style="font-size:1.1rem; margin-bottom:6px;">Growth, visualised</h3>
          <p style="font-size:0.92rem;">Live campaign performance, audience growth and revenue impact — tracked from day one.</p>
        </div>
        <div style="display:flex; align-items:flex-end; gap:10px; height:120px;">
          <div style="flex:1; height:40%; border-radius:10px 10px 0 0; background:linear-gradient(180deg, rgba(228,35,43,0.7), rgba(228,35,43,0.25));"></div>
          <div style="flex:1; height:65%; border-radius:10px 10px 0 0; background:linear-gradient(180deg, rgba(255,107,107,0.7), rgba(255,107,107,0.25));"></div>
          <div style="flex:1; height:52%; border-radius:10px 10px 0 0; background:linear-gradient(180deg, rgba(255,77,109,0.75), rgba(255,77,109,0.25));"></div>
          <div style="flex:1; height:90%; border-radius:10px 10px 0 0; background:linear-gradient(180deg, rgba(228,35,43,0.9), rgba(228,35,43,0.35));"></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- WHY D-DEGREE -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Why brands choose D-Degree</h2>
      <p>A single partner covering the ground between a good idea and a governed, growing business.</p>
    </div>
    <div class="pill-row">
      <span class="pill">🇳🇬 Built in Ogba, Lagos</span>
      <span class="pill">📊 Data-driven strategy</span>
      <span class="pill">🔐 Compliance built in</span>
      <span class="pill">🌍 Emerging-market ready</span>
    </div>
  </div>
</section>

<!-- STATS SECTION -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Our Impact</h2>
      <p>Measurable results that drive real business growth.</p>
    </div>
    <div class="stats-grid">
      <div class="glass stat-card">
        <div class="stat-number">250+</div>
        <p class="stat-label">Active partnerships</p>
      </div>
      <div class="glass stat-card">
        <div class="stat-number">3x</div>
        <p class="stat-label">Average lead growth</p>
      </div>
      <div class="glass stat-card">
        <div class="stat-number">98%</div>
        <p class="stat-label">Client satisfaction</p>
      </div>
      <div class="glass stat-card">
        <div class="stat-number">6y+</div>
        <p class="stat-label">Industry experience</p>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container">
    <span class="hero-kicker" style="display:inline-block; margin-bottom:20px;">About D-Degree Digital Hub</span>
    <div class="section-head" style="text-align:left; margin-left:0;">
      <h2>A growth and compliance partner, built for how business happens in Lagos</h2>
      <p>We started as a marketing shop. We became something closer to an operations partner — because the brands we worked with kept asking for the same thing: help us grow without creating a mess we'll regret later. Founded to close a specific gap, D-Degree operates from Ogba, Ikeja, and pairs marketing talent with compliance expertise under one roof.</p>
    </div>
    <div class="tile-grid">
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M12 2v20M2 12h20" stroke="#E4232B" stroke-width="2" stroke-linecap="round"/></svg></div>
        <h3>Embedded, not outsourced</h3>
        <p>We sit close enough to your team to understand the business, not just the brief — structured onboarding, shared dashboards, weekly check-ins.</p>
      </div>
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="8" r="4" stroke="#FF6B6B" stroke-width="2"/><path d="M4 20c0-4 4-7 8-7s8 3 8 7" stroke="#FF6B6B" stroke-width="2" stroke-linecap="round"/></svg></div>
        <h3>SMEs, brands and institutions</h3>
        <p>From owner-run businesses scaling their first marketing function, to public and private institutions needing compliant digital infrastructure.</p>
      </div>
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M12 2l8 4v6c0 5-3.4 8.7-8 10-4.6-1.3-8-5-8-10V6l8-4z" stroke="#FF4D6D" stroke-width="2" stroke-linejoin="round"/></svg></div>
        <h3>Growth that survives scrutiny</h3>
        <p>We build campaigns and platforms that hold up under regulatory, investor and board-level review — not just short-term traffic spikes.</p>
      </div>
    </div>
  </div>
</section>

<!-- PROCESS TIMELINE -->
<section id="process">
  <div class="container">
    <div class="section-head">
      <h2>Our Process</h2>
      <p>From discovery to delivery, a structured approach that ensures results.</p>
    </div>
    <div class="timeline">
      <div class="glass timeline-item">
        <div class="timeline-dot">1</div>
        <h3>Discovery</h3>
        <p>We listen to understand your business, market, and goals.</p>
      </div>
      <div class="glass timeline-item">
        <div class="timeline-dot">2</div>
        <h3>Strategy</h3>
        <p>We develop a data-driven roadmap aligned with your vision.</p>
      </div>
      <div class="glass timeline-item">
        <div class="timeline-dot">3</div>
        <h3>Execution</h3>
        <p>We build and launch campaigns with precision and accountability.</p>
      </div>
      <div class="glass timeline-item">
        <div class="timeline-dot">4</div>
        <h3>Scale</h3>
        <p>We optimize and scale what works into sustainable growth.</p>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="container">
    <span class="hero-kicker" style="display:inline-block; margin-bottom:20px;">What we do</span>
    <div class="section-head" style="text-align:left; margin-left:0;">
      <h2>Five capabilities. One accountable partner.</h2>
      <p>Every service below can be engaged on its own or bundled into a single retainer, run by the same strategy lead.</p>
    </div>

    <div class="glass service-panel">
      <div class="service-item">
        <div class="service-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="#E4232B" stroke-width="2"/><circle cx="12" cy="12" r="4" stroke="#E4232B" stroke-width="2"/></svg></div>
        <div>
          <h3>Digital Marketing &amp; Strategy</h3>
          <p style="font-size:0.92rem; margin:0;">Acquisition systems, not one-off campaigns — wired together and reported against revenue.</p>
        </div>
        <ul class="service-detail">
          <li>SEO for local and national visibility</li>
          <li>Pay-per-click across Google &amp; social</li>
          <li>Growth hacking &amp; experimentation</li>
          <li>Weekly performance reporting</li>
        </ul>
      </div>

      <div class="service-item">
        <div class="service-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M4 20L8 8L12 16L16 4L20 20" stroke="#FF6B6B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
        <div>
          <h3>Content Creation &amp; Branding</h3>
          <p style="font-size:0.92rem; margin:0;">Your brand is the story a customer tells someone else. We build it deliberately.</p>
        </div>
        <ul class="service-detail">
          <li>Corporate identity &amp; brand guidelines</li>
          <li>Brand strategy &amp; storytelling</li>
          <li>Logo &amp; visual asset systems</li>
          <li>Photography, video &amp; multimedia</li>
        </ul>
      </div>

      <div class="service-item">
        <div class="service-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none"><circle cx="8" cy="9" r="3" stroke="#FF4D6D" stroke-width="2"/><circle cx="17" cy="9" r="3" stroke="#FF4D6D" stroke-width="2"/><path d="M2 20c0-3 3-5 6-5s6 2 6 5M12 20c0-3 3-5 6-5" stroke="#FF4D6D" stroke-width="2" stroke-linecap="round"/></svg></div>
        <div>
          <h3>Social Media Management</h3>
          <p style="font-size:0.92rem; margin:0;">Communities that convert, with a reporting cycle your team can question anytime.</p>
        </div>
        <ul class="service-detail">
          <li>Community building &amp; engagement</li>
          <li>Editorial &amp; content calendars</li>
          <li>Platform-specific content production</li>
          <li>Analytics tied to leads &amp; conversions</li>
        </ul>
      </div>

      <div class="service-item">
        <div class="service-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M12 3L2 8l10 5 10-5-10-5z" stroke="#E4232B" stroke-width="2" stroke-linejoin="round"/><path d="M6 12v5c0 1.5 3 3 6 3s6-1.5 6-3v-5" stroke="#E4232B" stroke-width="2"/></svg></div>
        <div>
          <h3>Training &amp; Capacity Building</h3>
          <p style="font-size:0.92rem; margin:0;">Hands-on programmes that leave your staff able to operate independently.</p>
        </div>
        <ul class="service-detail">
          <li>Digital literacy for non-technical teams</li>
          <li>Corporate skill-development workshops</li>
          <li>CRM &amp; analytics tools training</li>
          <li>Custom curricula for public &amp; private sector</li>
        </ul>
      </div>

      <div class="service-item">
        <div class="service-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M12 2L4 5v6c0 5 3.4 8.7 8 10 4.6-1.3 8-5 8-10V5l-8-3z" stroke="#FF6B6B" stroke-width="2" stroke-linejoin="round"/><path d="M9 12l2 2 4-4" stroke="#FF6B6B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
        <div>
          <h3>Ecosystem Projects — DDComply</h3>
          <p style="font-size:0.92rem; margin:0;">Data protection, corporate compliance and financial-inclusion infrastructure.</p>
        </div>
        <ul class="service-detail">
          <li>NDPR &amp; data protection audits</li>
          <li>Corporate governance readiness</li>
          <li>Financial inclusion tooling</li>
          <li><a href="#ecosystem" style="color:#AE1B23; font-weight:600;">Full DDComply overview →</a></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>What partners say</h2>
      <p>Placeholder testimonials — swap in verified client quotes before launch.</p>
    </div>
    <div class="quote-grid">
      <div class="glass quote-card">
        <p class="quote-text">"D-Degree rebuilt our entire online presence in under two months. Inbound leads tripled the following quarter."</p>
        <p class="quote-attr"><strong>Operations Director</strong>Mid-size FMCG distributor, Lagos</p>
      </div>
      <div class="glass quote-card">
        <p class="quote-text">"The compliance work through DDComply gave our board the confidence to approve our fintech partnership."</p>
        <p class="quote-attr"><strong>Chief Compliance Officer</strong>Regional microfinance institution</p>
      </div>
      <div class="glass quote-card">
        <p class="quote-text">"Our staff went from avoiding our CRM to running weekly reports themselves after the training programme."</p>
        <p class="quote-attr"><strong>HR Lead</strong>Public sector agency, Ikeja</p>
      </div>
    </div>
  </div>
</section>

<!-- PORTFOLIO -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Selected work</h2>
      <p>Illustrative placeholders — swap in verified project details and client-approved figures before publishing.</p>
    </div>
    <div class="work-grid">
      <div class="glass work-card">
        <span class="work-tag">Digital Marketing</span>
        <h3>Regional retail chain, Lagos &amp; Ogun</h3>
        <p style="margin:8px 0 0; font-size:0.92rem;">Rebuilt paid and organic acquisition for a 14-outlet retail chain, targeting campaigns around footfall data rather than platform defaults.</p>
      </div>
      <div class="glass work-card">
        <span class="work-tag" style="color:#FF6B6B; background:rgba(255,107,107,0.12);">Branding</span>
        <h3>Corporate identity refresh, logistics sector</h3>
        <p style="margin:8px 0 0; font-size:0.92rem;">Full identity system — naming, logo suite, brand guidelines and driver-facing materials — for a mid-size haulage operator.</p>
      </div>
      <div class="glass work-card">
        <span class="work-tag" style="color:#FF4D6D; background:rgba(255,77,109,0.14);">Compliance · DDComply</span>
        <h3>Data protection audit, microfinance institution</h3>
        <p style="margin:8px 0 0; font-size:0.92rem;">End-to-end NDPR compliance review and remediation plan ahead of a regulatory inspection, with staff training sign-off.</p>
      </div>
      <div class="glass work-card">
        <span class="work-tag">Training</span>
        <h3>Digital literacy programme, public sector agency</h3>
        <p style="margin:8px 0 0; font-size:0.92rem;">A six-week capacity-building programme covering digital tools, data handling and basic cyber hygiene.</p>
      </div>
    </div>
  </div>
</section>

<!-- BLOG PREVIEW -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Latest insights</h2>
      <p>Stay updated with trends in digital growth and compliance.</p>
    </div>
    <div class="blog-grid">
      <div class="glass blog-card">
        <span class="blog-date">September 12, 2026</span>
        <h3>Building compliant growth systems</h3>
        <p class="blog-excerpt">How to scale your business without leaving compliance behind.</p>
        <a href="#" class="read-more">Read article →</a>
      </div>
      <div class="glass blog-card">
        <span class="blog-date">September 5, 2026</span>
        <h3>NDPR compliance for SMEs</h3>
        <p class="blog-excerpt">A practical guide to data protection in Nigeria.</p>
        <a href="#" class="read-more">Read article →</a>
      </div>
      <div class="glass blog-card">
        <span class="blog-date">August 29, 2026</span>
        <h3>Customer acquisition in emerging markets</h3>
        <p class="blog-excerpt">Strategies that work when conventional metrics don't.</p>
        <a href="#" class="read-more">Read article →</a>
      </div>
    </div>
  </div>
</section>

<!-- FAQ SECTION -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Frequently asked</h2>
      <p>Quick answers to common questions about our services.</p>
    </div>
    <div class="faq-grid">
      <div class="glass faq-item">
        <h3>What's your typical engagement model?</h3>
        <p>We work on retainers (monthly/quarterly), project bases, or hybrid models. The scope always depends on your specific needs and stage of growth.</p>
      </div>
      <div class="glass faq-item">
        <h3>How long before we see results?</h3>
        <p>Digital marketing results typically show within 4-8 weeks. Compliance work is usually completed within 2-4 weeks depending on your current state.</p>
      </div>
      <div class="glass faq-item">
        <h3>Do you work with small businesses?</h3>
        <p>Yes. Many of our strongest partnerships are with SMEs scaling their first marketing function. We scale our approach to fit your budget.</p>
      </div>
      <div class="glass faq-item">
        <h3>What's your compliance expertise based on?</h3>
        <p>Our DDComply team has deep expertise in NDPR, corporate governance, and emerging-market fintech regulations.</p>
      </div>
    </div>
  </div>
</section>

<!-- ECOSYSTEM -->
<section id="ecosystem">
  <div class="container">
    <span class="hero-kicker" style="display:inline-block; margin-bottom:20px;">Our Ecosystem</span>
    <div class="section-head" style="text-align:left; margin-left:0;">
      <h2>DDComply — compliance and financial inclusion infrastructure</h2>
      <p>A dedicated platform for organisations that need to grow and stay defensible at the same time — built for the regulatory realities of Nigeria and other emerging markets.</p>
    </div>

    <div class="glass eco-glass" style="margin-bottom:44px;">
      <h3 style="margin-bottom:14px;">Why DDComply exists</h3>
      <p style="max-width:70ch; margin-bottom:0;">Marketing can get a business noticed. It can't get that business through a data-protection audit, a lending license review, or a board asking whether customer data is actually safe. DDComply closes that gap — as a standalone workstream that plugs directly into everything else we do.</p>
    </div>

    <div class="tile-grid" style="margin-bottom:44px;">
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><rect x="4" y="10" width="16" height="10" rx="2" stroke="#E4232B" stroke-width="2"/><path d="M8 10V7a4 4 0 018 0v3" stroke="#E4232B" stroke-width="2"/></svg></div>
        <h3>Data protection</h3>
        <p>Audits, policy documentation and remediation plans aligned with Nigerian data protection regulation (NDPR).</p>
      </div>
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M9 12l2 2 4-4" stroke="#FF6B6B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><circle cx="12" cy="12" r="9" stroke="#FF6B6B" stroke-width="2"/></svg></div>
        <h3>Corporate compliance</h3>
        <p>Governance structures, reporting frameworks and documentation that hold up under regulator or investor review.</p>
      </div>
      <div class="glass tile">
        <div class="icon-wrap"><svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M3 12h18M3 6h18M3 18h18" stroke="#FF4D6D" stroke-width="2" stroke-linecap="round"/></svg></div>
        <h3>Financial inclusion</h3>
        <p>Tools and process design that extend services to underserved populations without breaching compliance.</p>
      </div>
    </div>

    <div class="tile-grid">
      <div class="glass tile">
        <h3 style="font-size:1rem;">Fintechs &amp; microfinance</h3>
        <p>Licensing and audit readiness ahead of CBN or state-level regulatory review, or due diligence for a funding round.</p>
      </div>
      <div class="glass tile">
        <h3 style="font-size:1rem;">SMEs scaling fast</h3>
        <p>Putting basic data protection and compliance structures in place before growth outpaces the systems supporting it.</p>
      </div>
      <div class="glass tile">
        <h3 style="font-size:1rem;">Public sector &amp; NGOs</h3>
        <p>Structured, auditable documentation and training that stand up to public scrutiny and funder reporting.</p>
      </div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section>
  <div class="container">
    <div class="section-head">
      <h2>Service packages</h2>
      <p>Flexible pricing tailored to your scope and stage.</p>
    </div>
    <div class="pricing-grid">
      <div class="glass pricing-card">
        <h3>Starter</h3>
        <div class="price">₦150k</div>
        <p class="price-period">per month</p>
        <p style="font-size:0.9rem; margin:16px 0;">Perfect for SMEs testing the market.</p>
        <ul class="pricing-features">
          <li>✓ Strategic consulting (2 hrs/wk)</li>
          <li>✓ Social media management (2 posts/day)</li>
          <li>✓ Weekly reporting</li>
          <li>✗ Full campaign management</li>
        </ul>
        <a href="#contact" class="btn btn-primary">Get started</a>
      </div>
      <div class="glass pricing-card featured">
        <span style="display:inline-block; background:var(--teal); color:#fff; padding:6px 16px; border-radius:999px; font-size:0.8rem; font-weight:600; margin-bottom:16px;">Most Popular</span>
        <h3>Growth</h3>
        <div class="price">₦500k</div>
        <p class="price-period">per month</p>
        <p style="font-size:0.9rem; margin:16px 0;">For scaling brands needing full support.</p>
        <ul class="pricing-features">
          <li>✓ Full digital marketing strategy</li>
          <li>✓ Paid &amp; organic campaigns</li>
          <li>✓ Content &amp; social management</li>
          <li>✓ Weekly reporting &amp; optimization</li>
        </ul>
        <a href="#contact" class="btn btn-primary">Get started</a>
      </div>
      <div class="glass pricing-card">
        <h3>Enterprise</h3>
        <div class="price">Custom</div>
        <p class="price-period">based on scope</p>
        <p style="font-size:0.9rem; margin:16px 0;">Complete transformation for institutions.</p>
        <ul class="pricing-features">
          <li>✓ Dedicated account team</li>
          <li>✓ Custom strategy &amp; execution</li>
          <li>✓ DDComply compliance work</li>
          <li>✓ Training &amp; capacity building</li>
        </ul>
        <a href="#contact" class="btn btn-primary">Contact sales</a>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <div class="container">
    <div class="glass cta-glass">
      <h2>Ready to make your brand impossible to miss?</h2>
      <p>Tell us where you're stuck — growth, branding, or compliance — and we'll show you the fastest way through it.</p>
      <a href="#contact" class="btn btn-glass-dark">Grow Your Brand</a>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">
    <span class="hero-kicker" style="display:inline-block; margin-bottom:20px;">Get in touch</span>
    <div class="section-head" style="text-align:left; margin-left:0;">
      <h2>Tell us what you're building</h2>
      <p>Whether it's a full growth retainer, a single campaign, or a DDComply compliance review — send us the brief and we'll respond within two business days.</p>
    </div>

    <div class="contact-grid">
      <div class="glass info-glass">
        <div class="info-row">
          <h4>Visit us</h4>
          <p>16B Akintan Street, Dideolu Estate, Ogba, Ikeja, Lagos, Nigeria</p>
        </div>
        <div class="info-row">
          <h4>Email</h4>
          <p>info@ddegreedigital.com</p>
        </div>
        <div class="info-row">
          <h4>Phone</h4>
          <p>+234 (0) 000 000 0000</p>
        </div>
        <div class="info-row">
          <h4>Office hours</h4>
          <p>Monday – Friday, 9:00 AM – 5:00 PM (WAT)</p>
        </div>
      </div>

      <form class="glass form-glass" onsubmit="return handleSubmit(event)">
        <div class="field">
          <label for="name">Full name</label>
          <input type="text" id="name" name="name" placeholder="e.g. Adaeze Okoye" required>
        </div>
        <div class="field">
          <label for="company">Company / organisation</label>
          <input type="text" id="company" name="company" placeholder="e.g. Sahara Retail Group">
        </div>
        <div class="field">
          <label for="email">Email address</label>
          <input type="email" id="email" name="email" placeholder="you@company.com" required>
        </div>
        <div class="field">
          <label for="phone">Phone number</label>
          <input type="tel" id="phone" name="phone" placeholder="+234 800 000 0000">
        </div>
        <div class="field">
          <label for="service">Service you're interested in</label>
          <select id="service" name="service">
            <option>Digital Marketing &amp; Strategy</option>
            <option>Content Creation &amp; Branding</option>
            <option>Social Media Management</option>
            <option>Training &amp; Capacity Building</option>
            <option>DDComply — Compliance &amp; Financial Inclusion</option>
            <option>Not sure yet</option>
          </select>
        </div>
        <div class="field">
          <label for="message">Tell us about your project</label>
          <textarea id="message" name="message" placeholder="What are you trying to achieve, and by when?" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Send message</button>
        <p id="form-status" style="margin-top:14px; font-size:0.88rem; display:none; color:#AE1B23;">Thanks — this is a static demo, so nothing was actually sent. Wire this form up to your CMS or a form service to go live.</p>
      </form>
    </div>
  </div>
</section>

<footer>
  <div class="container footer-glass glass">
    <div class="footer-grid">
      <div>
        <h4>D-Degree Digital Hub</h4>
        <p>16B Akintan Street, Dideolu Estate, Ogba, Ikeja, Lagos, Nigeria.</p>
      </div>
      <div>
        <h4>Navigate</h4>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#ecosystem">Ecosystem</a>
      </div>
      <div>
        <h4>Get in touch</h4>
        <a href="#contact">Contact form</a>
        <a href="mailto:info@ddegreedigital.com">info@ddegreedigital.com</a>
        <a href="tel:+2340000000000">+234 (0) 000 000 0000</a>
      </div>
      <div>
        <h4>Follow</h4>
        <a href="#">LinkedIn</a>
        <a href="#">Instagram</a>
        <a href="#">X (Twitter)</a>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 D-Degree Digital Hub. All rights reserved.</span>
      <span>Ogba, Ikeja, Lagos, Nigeria</span>
    </div>
  </div>
</footer>

<script>
  // Theme Toggle Functionality
  function initTheme() {
    const savedTheme = localStorage.getItem('theme') || 'light';
    const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
    const theme = savedTheme === 'auto' ? (prefersDark ? 'dark' : 'light') : savedTheme;
    
    if (theme === 'dark') {
      document.documentElement.setAttribute('data-theme', 'dark');
      document.getElementById('theme-icon').textContent = '☀️';
    } else {
      document.documentElement.removeAttribute('data-theme');
      document.getElementById('theme-icon').textContent = '🌙';
    }
  }

  // Initialize theme on page load
  initTheme();

  // Theme toggle button handler
  document.getElementById('theme-toggle').addEventListener('click', () => {
    const html = document.documentElement;
    const isDark = html.getAttribute('data-theme') === 'dark';
    
    if (isDark) {
      html.removeAttribute('data-theme');
      localStorage.setItem('theme', 'light');
      document.getElementById('theme-icon').textContent = '🌙';
    } else {
      html.setAttribute('data-theme', 'dark');
      localStorage.setItem('theme', 'dark');
      document.getElementById('theme-icon').textContent = '☀️';
    }
  });

  // Form submission handler
  function handleSubmit(e){
    e.preventDefault();
    document.getElementById('form-status').style.display = 'block';
    return false;
  }
</script>
</body>
</html>

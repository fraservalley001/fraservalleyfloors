<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fraser Valley Floors | Flooring Contractor in Fraser Valley, BC</title>
<meta name="description" content="Fraser Valley Floors is a trusted flooring contractor offering residential & commercial flooring, epoxy coatings, and concrete resurfacing in Fraser Valley, BC.">
<link rel="icon" href="assets/logo.png">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    --charcoal:#1b1d1f;
    --concrete:#3d4147;
    --concrete-light:#6b7178;
    --epoxy:#c8722e;
    --epoxy-light:#e08f45;
    --cream:#f6f4f0;
    --white:#ffffff;
    --line:#e4e1da;
  }
  *{box-sizing:border-box;margin:0;padding:0;}
  html{scroll-behavior:smooth;}
  body{
    font-family:'Manrope',sans-serif;
    color:var(--charcoal);
    background:var(--cream);
    line-height:1.6;
  }
  h1,h2,h3,h4{
    font-family:'Bebas Neue',sans-serif;
    letter-spacing:0.5px;
    line-height:1.05;
    color:var(--charcoal);
  }
  a{color:inherit;text-decoration:none;}
  img{max-width:100%;display:block;}
  .container{max-width:1180px;margin:0 auto;padding:0 24px;}
  .eyebrow{
    text-transform:uppercase;
    font-size:0.78rem;
    font-weight:800;
    letter-spacing:2px;
    color:var(--epoxy);
    margin-bottom:10px;
    display:block;
  }
  .btn{
    display:inline-flex;align-items:center;gap:8px;
    padding:14px 28px;
    border-radius:3px;
    font-weight:700;
    font-size:0.95rem;
    text-transform:uppercase;
    letter-spacing:0.5px;
    transition:transform .15s ease, box-shadow .15s ease;
  }
  .btn-primary{background:var(--epoxy);color:var(--white);}
  .btn-primary:hover{background:var(--epoxy-light);transform:translateY(-2px);}
  .btn-outline{border:2px solid var(--charcoal);color:var(--charcoal);}
  .btn-outline:hover{background:var(--charcoal);color:var(--white);transform:translateY(-2px);}

  /* Header */
  header{
    position:sticky;top:0;z-index:100;
    background:var(--charcoal);
    border-bottom:1px solid rgba(255,255,255,.08);
  }
  .nav-wrap{
    display:flex;align-items:center;justify-content:space-between;
    padding:14px 0;
  }
  .logo{display:flex;align-items:center;padding:8px 12px;background:#fff;border-radius:8px;box-shadow:0 2px 8px rgba(0,0,0,.12);display:inline-flex;}
  .logo img{display:block;max-width:220px;height:auto;object-fit:contain;}
  header .logo img{max-height:60px;}
  footer .logo img{max-height:55px;}
  nav.main-nav{display:flex;align-items:center;gap:28px;}
  nav.main-nav a{
    color:#e8e6e1;font-weight:600;font-size:0.92rem;
  }
  nav.main-nav a:hover{color:var(--epoxy-light);}
  .header-cta{display:flex;align-items:center;gap:18px;}
  .header-phone{color:var(--white);font-weight:700;font-size:0.95rem;white-space:nowrap;}
  .header-phone span{color:var(--epoxy-light);}
  @media(max-width:860px){
    nav.main-nav{display:none;}
  }

  /* Hero */
  .hero{
    position:relative;color:var(--white);
    min-height:640px;
    display:flex;align-items:center;
    background:linear-gradient(rgba(20,21,22,.72),rgba(20,21,22,.55)), url('https://www.fraservalleyfloors.com/assets/hero-epoxy-DW8Iq3bZ.jpg') center/cover no-repeat;
  }
  .hero-inner{max-width:680px;padding:100px 0;}
  .hero h1{font-size:clamp(2.6rem,6vw,4.2rem);margin:14px 0 20px;color:#fff !important;}
  .hero p{font-size:1.15rem;color:#e9e7e2;max-width:560px;margin-bottom:32px;}
  .hero-ctas{display:flex;gap:16px;flex-wrap:wrap;margin-bottom:48px;}
  .hero-stats{
    display:flex;gap:36px;flex-wrap:wrap;
    border-top:1px solid rgba(255,255,255,.25);
    padding-top:24px;
  }
  .hero-stats div{font-size:0.85rem;font-weight:700;text-transform:uppercase;letter-spacing:0.5px;color:#f0ede7;}

  section{padding:90px 0;}
  .section-head{max-width:680px;margin-bottom:52px;}
  .section-head h2{font-size:clamp(2rem,4vw,2.9rem);}
  .section-head p{color:var(--concrete-light);margin-top:12px;font-size:1.05rem;}

  /* Services */
  .division{margin-bottom:64px;}
  .division-head{
    display:flex;justify-content:space-between;align-items:flex-end;
    flex-wrap:wrap;gap:16px;margin-bottom:28px;
    border-bottom:2px solid var(--charcoal);
    padding-bottom:14px;
  }
  .division-head h3{font-size:1.9rem;}
  .division-head p{color:var(--concrete-light);font-size:0.95rem;max-width:420px;}
  .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:22px;}
  @media(max-width:900px){.cards{grid-template-columns:1fr;}}
  .card{
    background:var(--white);
    border:1px solid var(--line);
    border-radius:6px;
    padding:28px 26px;
    display:flex;flex-direction:column;
    transition:box-shadow .2s ease, transform .2s ease;
  }
  .card:hover{box-shadow:0 14px 30px rgba(27,29,31,.08);transform:translateY(-4px);}
  .card .mark{
    width:44px;height:44px;border-radius:4px;
    background:var(--epoxy);color:var(--white);
    display:flex;align-items:center;justify-content:center;
    font-family:'Bebas Neue',sans-serif;font-size:1.3rem;
    margin-bottom:18px;
  }
  .card h4{font-size:1.35rem;margin-bottom:8px;}
  .card p{color:var(--concrete-light);font-size:0.95rem;flex-grow:1;margin-bottom:18px;}
  .card .learn-more{
    font-weight:700;font-size:0.88rem;text-transform:uppercase;letter-spacing:0.5px;
    color:var(--epoxy);display:inline-flex;align-items:center;gap:6px;
  }
  .card .learn-more:hover{color:var(--charcoal);}
  .view-all{margin-top:24px;text-align:right;}
  .view-all a{font-weight:700;border-bottom:2px solid var(--epoxy);padding-bottom:2px;}

  /* Why choose */
  .why{background:var(--charcoal);color:var(--white);}
  .why .section-head p{color:#c8c6c1;}
  .why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:24px;}
  @media(max-width:900px){.why-grid{grid-template-columns:repeat(2,1fr);}}
  @media(max-width:560px){.why-grid{grid-template-columns:1fr;}}
  .why-item{border-top:3px solid var(--epoxy);padding-top:18px;}
  .why-item h4{font-size:1.3rem;color:var(--white);margin-bottom:8px;}
  .why-item p{color:#c8c6c1;font-size:0.92rem;}

  /* Areas */
  .areas-list{display:flex;flex-wrap:wrap;gap:12px;margin-top:20px;}
  .areas-list a{
    background:var(--white);border:1px solid var(--line);
    padding:10px 20px;border-radius:30px;font-weight:600;font-size:0.9rem;
  }
  .areas-list a:hover{background:var(--charcoal);color:var(--white);border-color:var(--charcoal);}
  .map-link{margin-top:24px;display:inline-block;font-weight:700;color:var(--epoxy);}

  /* Gallery */
  .gallery-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;}
  @media(max-width:760px){.gallery-grid{grid-template-columns:repeat(2,1fr);}}
  .gallery-grid img{border-radius:6px;height:220px;width:100%;object-fit:cover;}

  /* Process */
  .process{background:var(--white);}
  .steps{counter-reset:step;display:grid;grid-template-columns:repeat(4,1fr);gap:22px;}
  @media(max-width:900px){.steps{grid-template-columns:repeat(2,1fr);}}
  @media(max-width:560px){.steps{grid-template-columns:1fr;}}
  .step{padding:26px;border:1px solid var(--line);border-radius:6px;position:relative;}
  .step .num{
    font-family:'Bebas Neue',sans-serif;font-size:2.6rem;color:var(--epoxy);line-height:1;margin-bottom:10px;
  }
  .step h4{font-size:1.15rem;margin-bottom:8px;}
  .step p{color:var(--concrete-light);font-size:0.92rem;}

  /* Testimonials */
  .testi-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;}
  @media(max-width:900px){.testi-grid{grid-template-columns:1fr;}}
  .testi{
    background:var(--white);border:1px solid var(--line);border-radius:6px;padding:26px;
  }
  .testi p.quote{font-size:0.98rem;margin-bottom:18px;color:var(--concrete);}
  .testi .who{font-weight:700;font-size:0.92rem;}
  .testi .loc{color:var(--concrete-light);font-size:0.85rem;}
  .stars{color:var(--epoxy);letter-spacing:2px;margin-bottom:10px;}

  /* FAQ */
  .faq-item{border-bottom:1px solid var(--line);padding:20px 0;}
  .faq-item h4{font-size:1.1rem;font-family:'Manrope',sans-serif;font-weight:700;}

  /* CTA + Contact */
  .cta-section{
    background:var(--epoxy);color:var(--white);text-align:center;
  }
  .cta-section h2{font-size:clamp(2rem,4vw,2.8rem);color:var(--white);margin-bottom:16px;}
  .cta-section p{max-width:560px;margin:0 auto 28px;color:#fbe9db;}
  .cta-section .btn-outline{border-color:var(--white);color:var(--white);}
  .cta-section .btn-outline:hover{background:var(--white);color:var(--epoxy);}

  /* Footer */
  footer{background:var(--charcoal);color:#c8c6c1;padding:70px 0 30px;}
  .footer-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr 1fr;gap:32px;margin-bottom:50px;}
  @media(max-width:900px){.footer-grid{grid-template-columns:repeat(2,1fr);}}
  @media(max-width:560px){.footer-grid{grid-template-columns:1fr;}}
  footer .logo img{height:42px;margin-bottom:16px;}
  footer p.about{font-size:0.9rem;max-width:280px;}
  footer h4{color:var(--white);font-family:'Manrope',sans-serif;font-size:0.95rem;text-transform:uppercase;letter-spacing:1px;margin-bottom:16px;}
  footer ul{list-style:none;}
  footer ul li{margin-bottom:10px;font-size:0.9rem;}
  footer ul li a:hover{color:var(--epoxy-light);}
  .footer-bottom{
    border-top:1px solid rgba(255,255,255,.1);
    padding-top:24px;font-size:0.85rem;
    display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px;
  }
  .sticky-call{
    position:fixed;bottom:0;left:0;right:0;
    background:var(--charcoal);
    display:none;
    justify-content:space-between;
    padding:14px 20px;z-index:200;
  }
  .sticky-call a{color:var(--white);font-weight:700;font-size:0.9rem;}
  @media(max-width:640px){.sticky-call{display:flex;}body{padding-bottom:60px;}}
</style>
</head>
<body>

<header>
  <div class="container nav-wrap">
    <a href="https://www.fraservalleyfloors.com/" class="logo">
      <img src="https://www.fraservalleyfloors.com/Fraser-Valley-Floors.png" alt="Fraser Valley Floors Logo">
    </a>
    <nav class="main-nav">
      <a href="https://www.fraservalleyfloors.com/about">About</a>
      <a href="https://www.fraservalleyfloors.com/services">Services</a>
      <a href="https://www.fraservalleyfloors.com/projects">Projects</a>
      <a href="https://www.fraservalleyfloors.com/blog">Blog</a>
      <a href="https://www.fraservalleyfloors.com/locations">Locations</a>
      <a href="https://www.fraservalleyfloors.com/contact">Contact</a>
    </nav>
    <div class="header-cta">
      <a href="tel:7785625420" class="header-phone">📞 <span>(778) 562-5420</span></a>
      <a href="https://www.fraservalleyfloors.com/contact" class="btn btn-primary">Get a Free Quote</a>
    </div>
  </div>
</header>

<section class="hero" style="padding:0;">
  <div class="container hero-inner">
    <span class="eyebrow">Fraser Valley, BC</span>
    <h1>Best Flooring Contractor in Fraser Valley — Epoxy Coatings &amp; Concrete Experts</h1>
    <p>Residential &amp; commercial flooring installation, epoxy floor coatings, and concrete resurfacing — built to last, finished to impress.</p>
    <div class="hero-ctas">
      <a href="https://www.fraservalleyfloors.com/contact" class="btn btn-primary">Get a Free Quote</a>
      <a href="https://www.fraservalleyfloors.com/services" class="btn btn-outline" style="border-color:#fff;color:#fff;">View Our Services</a>
    </div>
    <div class="hero-stats">
      <div>10+ Years Experience</div>
      <div>Licensed &amp; Insured</div>
      <div>Free Estimates</div>
      <div>100% Satisfaction Guaranteed</div>
    </div>
  </div>
</section>

<!-- WHAT WE DO -->
<section id="services">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">What We Do</span>
      <h2>Hardwood, Vinyl, and Complete Flooring Solutions</h2>
      <p>Two specialised divisions, one trusted team. From a one-day garage epoxy to a whole-home hardwood install — we do it all, and we do it right.</p>
    </div>

    <div class="division">
      <div class="division-head">
        <div>
          <h3>Epoxy &amp; Concrete Coating Services</h3>
          <p>Tough, beautiful coatings for garage floors, warehouses, shops, patios &amp; commercial spaces.</p>
        </div>
      </div>
      <div class="cards">
        <div class="card">
          <div class="mark">✦</div>
          <h4>Epoxy Coatings</h4>
          <p>Durable, glossy epoxy systems for garages, shops &amp; commercial floors.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/epoxy-coatings">Learn more →</a>
        </div>
        <div class="card">
          <div class="mark">▣</div>
          <h4>Garage Coatings</h4>
          <p>Premium polyaspartic and epoxy systems built for daily abuse.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/garage-coatings">Learn more →</a>
        </div>
        <div class="card">
          <div class="mark">◫</div>
          <h4>Warehouse Coatings</h4>
          <p>Heavy-duty industrial flooring for warehouses &amp; distribution centres.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/warehouse-coatings">Learn more →</a>
        </div>
      </div>
      <div class="view-all"><a href="https://www.fraservalleyfloors.com/services">View All Epoxy &amp; Concrete Coating Services →</a></div>
    </div>

    <div class="division">
      <div class="division-head">
        <div>
          <h3>Flooring Services</h3>
          <p>Premium installation of vinyl, laminate, hardwood, stairs &amp; more.</p>
        </div>
      </div>
      <div class="cards">
        <div class="card">
          <div class="mark">▦</div>
          <h4>Vinyl Flooring</h4>
          <p>Waterproof luxury vinyl plank for kitchens, basements &amp; whole homes.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/vinyl-flooring">Learn more →</a>
        </div>
        <div class="card">
          <div class="mark">▧</div>
          <h4>Laminate Flooring</h4>
          <p>Premium AC-rated laminate that looks like hardwood for less.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/laminate-flooring">Learn more →</a>
        </div>
        <div class="card">
          <div class="mark">▩</div>
          <h4>Hardwood Flooring</h4>
          <p>Engineered and solid hardwood installation with expert finishing.</p>
          <a class="learn-more" href="https://www.fraservalleyfloors.com/services/hardwood-flooring">Learn more →</a>
        </div>
      </div>
      <div class="view-all"><a href="https://www.fraservalleyfloors.com/services">View All Flooring Services →</a></div>
    </div>
  </div>
</section>

<!-- WHY CHOOSE US -->
<section class="why">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Why Choose Us</span>
      <h2>Built on Craftsmanship, Trusted by Locals</h2>
    </div>
    <div class="why-grid">
      <div class="why-item">
        <h4>Quality Materials</h4>
        <p>Premium epoxies, polyaspartics, and brand-name flooring — never bargain product.</p>
      </div>
      <div class="why-item">
        <h4>Expert Installers</h4>
        <p>Trained, in-house crews — not subcontractors. Same team, every project.</p>
      </div>
      <div class="why-item">
        <h4>Competitive Pricing</h4>
        <p>Honest, itemised quotes. No surprises, no upsells, no hidden fees.</p>
      </div>
      <div class="why-item">
        <h4>Fast Turnaround</h4>
        <p>Most coatings done in a day. Floor installs scheduled around your life.</p>
      </div>
    </div>
  </div>
</section>

<!-- SERVICE AREAS -->
<section id="areas">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Service Areas</span>
      <h2>Proudly Serving the Entire Fraser Valley</h2>
      <p>From Tsawwassen to Chilliwack and everything in between, our crews work throughout the Lower Mainland and Fraser Valley.</p>
    </div>
    <div class="areas-list">
      <a href="https://www.fraservalleyfloors.com/locations/abbotsford">Abbotsford</a>
      <a href="https://www.fraservalleyfloors.com/locations/surrey">Surrey</a>
      <a href="https://www.fraservalleyfloors.com/locations/delta">Delta</a>
      <a href="https://www.fraservalleyfloors.com/locations/langley">Langley</a>
      <a href="https://www.fraservalleyfloors.com/locations/chilliwack">Chilliwack</a>
      <a href="https://www.fraservalleyfloors.com/locations/maple-ridge">Maple Ridge</a>
      <a href="https://www.fraservalleyfloors.com/locations/mission">Mission</a>
    </div>
    <a class="map-link" href="https://www.google.com/maps/search/Fraser+Valley,+BC/@49.1500,-122.5600,10z" target="_blank" rel="noopener">Open service area map →</a>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery" style="background:var(--white);">
  <div class="container">
    <div class="section-head" style="display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:16px;">
      <div>
        <span class="eyebrow">Project Gallery</span>
        <h2>Recent Work Across the Valley</h2>
      </div>
      <a href="https://www.fraservalleyfloors.com/projects" class="btn btn-outline">View Full Portfolio</a>
    </div>
    <div class="gallery-grid">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-1-66wGlJvB.jpg" alt="Project 1">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-2-ByTOSeCk.jpg" alt="Project 2">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-3-w-g-xxNg.jpg" alt="Project 3">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-4-ZgoM19f2.jpg" alt="Project 4">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-5-Bcz1gqt1.jpg" alt="Project 5">
      <img src="https://www.fraservalleyfloors.com/assets/gallery-6-CRDXHIa1.jpg" alt="Project 6">
    </div>
  </div>
</section>

<!-- PROCESS -->
<section class="process">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">How We Work</span>
      <h2>Clear Advice. Careful Installation. Lasting Results.</h2>
      <p>Every successful flooring or coating project begins with an honest look at the space — we check the subfloor, identify moisture concerns, and recommend materials that fit how you use the room.</p>
    </div>
    <div class="steps">
      <div class="step"><div class="num">1</div><h4>Plan the project</h4><p>We learn about your goals, room conditions, schedule, and budget before suggesting a system.</p></div>
      <div class="step"><div class="num">2</div><h4>Prepare the surface</h4><p>Grinding, repairs, leveling, and clean edges give the new floor the foundation it needs.</p></div>
      <div class="step"><div class="num">3</div><h4>Install with care</h4><p>In-house crews follow the product requirements and pay attention to transitions and finish quality.</p></div>
      <div class="step"><div class="num">4</div><h4>Leave it ready</h4><p>We review care instructions, remove installation debris, and make sure you know what's next.</p></div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section id="reviews">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">5-Star Reviews</span>
      <h2>What Fraser Valley Customers Say</h2>
      <p>Real reviews from real homeowners and business owners across the Fraser Valley.</p>
    </div>
    <div class="testi-grid">
      <div class="testi">
        <div class="stars">★★★★★</div>
        <p class="quote">"These guys transformed our garage in a single day. The polyaspartic finish looks like glass and the prep work was incredibly thorough."</p>
        <div class="who">Mike R.</div>
        <div class="loc">Abbotsford, BC</div>
      </div>
      <div class="testi">
        <div class="stars">★★★★★</div>
        <p class="quote">"Hardwood install across our main floor was flawless. Crew showed up on time and the transitions are perfect."</p>
        <div class="who">Jennifer L.</div>
        <div class="loc">Surrey, BC</div>
      </div>
      <div class="testi">
        <div class="stars">★★★★★</div>
        <p class="quote">"We had our warehouse coated with a heavy-duty epoxy system. Zero downtime issues and the safety striping is exactly what we needed."</p>
        <div class="who">David T.</div>
        <div class="loc">Langley, BC</div>
      </div>
    </div>
  </div>
</section>

<!-- FAQ -->
<section id="faq" style="background:var(--white);">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Questions &amp; Answers</span>
      <h2>Answers Before You Start</h2>
      <p>Learn what to expect from a Fraser Valley flooring or concrete coating project.</p>
    </div>
    <div class="faq-list">
      <div class="faq-item"><h4>What flooring and coating services do you provide?</h4></div>
      <div class="faq-item"><h4>Do you serve my Fraser Valley community?</h4></div>
      <div class="faq-item"><h4>How do I get a flooring or coating estimate?</h4></div>
      <div class="faq-item"><h4>How long does a garage coating project take?</h4></div>
      <div class="faq-item"><h4>Are your installers licensed and insured?</h4></div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section" id="quote">
  <div class="container">
    <h2>Ready to Transform Your Floor?</h2>
    <p>Get a Free Quote Today — no obligation, no pressure. Just honest pricing from Fraser Valley locals.</p>
    <a href="https://www.fraservalleyfloors.com/contact" class="btn btn-outline">Get a Free Quote</a>
  </div>
</section>

<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <a href="https://www.fraservalleyfloors.com/" class="logo">
          <img src="https://www.fraservalleyfloors.com/Fraser-Valley-Floors.png" alt="Fraser Valley Floors Logo">
        </a>
        <p class="about">Fraser Valley's trusted source for premium flooring and concrete coatings. Licensed, insured, and guaranteed.</p>
      </div>
      <div>
        <h4>Concrete Coatings</h4>
        <ul>
          <li><a href="https://www.fraservalleyfloors.com/services/epoxy-coatings">Epoxy Coatings</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/garage-coatings">Garage Coatings</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/warehouse-coatings">Warehouse Coatings</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/patio-coatings">Patio Coatings</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/polyaspartic-coatings">Polyaspartic Coatings</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/polyurethane-coatings">Polyurethane Coatings</a></li>
        </ul>
      </div>
      <div>
        <h4>Flooring</h4>
        <ul>
          <li><a href="https://www.fraservalleyfloors.com/services/vinyl-flooring">Vinyl Flooring</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/laminate-flooring">Laminate Flooring</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/hardwood-flooring">Hardwood Flooring</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/carpet-tiles">Carpet Tiles</a></li>
          <li><a href="https://www.fraservalleyfloors.com/services/custom-stairs">Custom Stairs</a></li>
        </ul>
      </div>
      <div>
        <h4>Contact</h4>
        <ul>
          <li><a href="tel:7785625420">(778) 562-5420</a></li>
          <li><a href="mailto:info@fraservalleyfloors.com">info@fraservalleyfloors.com</a></li>
          <li>Fraser Valley, British Columbia, Canada</li>
          <li>Available 24 Hours, 7 Days a Week</li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 Fraser Valley Floors. All rights reserved.</span>
      <span>Proudly serving the Fraser Valley, British Columbia.</span>
    </div>
  </div>
</footer>

<div class="sticky-call">
  <a href="tel:7785625420">📞 Call Now</a>
  <a href="https://www.fraservalleyfloors.com/contact">Get a Free Quote</a>
</div>

</body>
</html>

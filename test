<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>[Marka Adı] | [Kısa Tanım]</title>
  <meta name="description" content="[Marka Adı] - [1 cümlelik kısa açıklama]. [Hizmet/odak alanı] hakkında bilgi ve iletişim." />
  <meta name="robots" content="index,follow" />
  <link rel="canonical" href="https://[domainin.com]/" />

  <!-- Open Graph -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="[Marka Adı] | [Kısa Tanım]" />
  <meta property="og:description" content="[1 cümlelik kısa açıklama]" />
  <meta property="og:url" content="https://[domainin.com]/" />
  <meta property="og:locale" content="tr_TR" />

  <style>
    :root{
      --bg: #0b0f17;
      --card: rgba(255,255,255,.06);
      --text: rgba(255,255,255,.92);
      --muted: rgba(255,255,255,.72);
      --line: rgba(255,255,255,.10);
      --accent: #7c5cff;
      --accent2:#00d3a7;
      --shadow: 0 12px 30px rgba(0,0,0,.35);
      --radius: 18px;
      --max: 1100px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--text);
      background:
        radial-gradient(1000px 600px at 10% -10%, rgba(124,92,255,.35), transparent 55%),
        radial-gradient(900px 600px at 90% 0%, rgba(0,211,167,.25), transparent 60%),
        linear-gradient(180deg, #070a11 0%, #0b0f17 35%, #0b0f17 100%);
      line-height:1.55;
    }
    a{color:inherit;text-decoration:none}
    .wrap{max-width:var(--max); margin:0 auto; padding:20px}
    .nav{
      position:sticky; top:0; z-index:50;
      backdrop-filter: blur(10px);
      background: rgba(11,15,23,.55);
      border-bottom:1px solid var(--line);
    }
    .nav-inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px;
      max-width:var(--max); margin:0 auto; padding:12px 20px;
    }
    .brand{
      display:flex; align-items:center; gap:10px; font-weight:700; letter-spacing:.2px;
    }
    .logo{
      width:36px;height:36px;border-radius:12px;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      box-shadow: var(--shadow);
    }
    .nav a.link{
      padding:10px 12px;
      color:var(--muted);
      border-radius:12px;
      transition: background .2s ease, color .2s ease;
      display:inline-block;
    }
    .nav a.link:hover{background:rgba(255,255,255,.06); color:var(--text)}
    .nav-right{display:flex; align-items:center; gap:8px; flex-wrap:wrap; justify-content:flex-end}

    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:10px;
      padding:12px 14px;
      border-radius:14px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.06);
      color:var(--text);
      transition: transform .15s ease, background .2s ease, border-color .2s ease;
      white-space:nowrap;
    }
    .btn:hover{transform: translateY(-1px); background: rgba(255,255,255,.09); border-color: rgba(255,255,255,.18)}
    .btn.primary{
      background: linear-gradient(135deg, rgba(124,92,255,.95), rgba(0,211,167,.85));
      border-color: transparent;
      color:#061018;
      font-weight:700;
    }
    .btn.primary:hover{filter: brightness(1.02)}
    .btn.small{padding:10px 12px; border-radius:12px}

    .hero{
      padding:48px 0 18px;
    }
    .hero-grid{
      display:grid; gap:18px;
      grid-template-columns: 1.2fr .8fr;
      align-items:stretch;
    }
    .card{
      border:1px solid var(--line);
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }
    .hero-main{padding:28px}
    .kicker{
      display:inline-flex; align-items:center; gap:10px;
      font-size:14px; color:var(--muted);
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      padding:8px 12px;
      border-radius:999px;
    }
    .dot{
      width:9px;height:9px;border-radius:99px;
      background: var(--accent2);
      box-shadow: 0 0 0 4px rgba(0,211,167,.12);
    }
    h1{
      margin:14px 0 10px;
      font-size: clamp(28px, 4.2vw, 44px);
      line-height:1.12;
      letter-spacing:-.6px;
    }
    .lead{color:var(--muted); font-size: clamp(15px, 1.5vw, 18px); margin: 0 0 18px}
    .hero-actions{display:flex; gap:10px; flex-wrap:wrap; margin-top:16px}
    .hero-side{
      padding:22px;
      display:flex;
      flex-direction:column;
      gap:12px;
      justify-content:space-between;
    }
    .mini{
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      border-radius: 16px;
      padding:14px;
    }
    .mini strong{display:block; margin-bottom:6px}
    .mini span{color:var(--muted); font-size:14px}

    .section{
      padding:22px 0;
    }
    .section h2{
      font-size: 22px;
      margin: 0 0 10px;
      letter-spacing:-.2px;
    }
    .section p{color:var(--muted); margin:0}
    .grid-3{
      margin-top:14px;
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:12px;
    }
    .feature{
      padding:18px;
      border-radius: 18px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      min-height: 132px;
    }
    .feature .icon{
      width:40px;height:40px;border-radius:14px;
      background: rgba(124,92,255,.18);
      border:1px solid rgba(124,92,255,.30);
      display:grid; place-items:center;
      margin-bottom:10px;
      font-size:18px;
    }
    .feature h3{margin:0 0 6px; font-size:16px}
    .feature p{margin:0; color:var(--muted); font-size:14px}

    .split{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:12px;
      margin-top:14px;
    }
    .box{padding:18px}
    .list{
      margin:10px 0 0; padding:0; list-style:none;
      display:grid; gap:10px;
    }
    .list li{
      display:flex; gap:10px; align-items:flex-start;
      color:var(--muted);
    }
    .check{
      width:22px;height:22px;border-radius:8px;
      background: rgba(0,211,167,.15);
      border:1px solid rgba(0,211,167,.30);
      display:grid; place-items:center; flex: 0 0 22px;
      color: var(--accent2);
      font-weight:900;
      margin-top:1px;
    }

    .contact{
      padding:22px;
      display:flex;
      flex-direction:column;
      gap:12px;
    }
    .contact-row{
      display:flex; gap:10px; flex-wrap:wrap;
    }
    .muted{color:var(--muted)}
    footer{
      padding:26px 0 36px;
      color:rgba(255,255,255,.55);
      font-size:13px;
      border-top:1px solid var(--line);
      margin-top:18px;
    }
    .foot{
      display:flex; justify-content:space-between; gap:12px; flex-wrap:wrap;
      align-items:center;
    }

    /* Responsive */
    @media (max-width: 860px){
      .hero-grid{grid-template-columns: 1fr}
      .grid-3{grid-template-columns: 1fr}
      .split{grid-template-columns: 1fr}
      .nav-right{gap:6px}
    }
    /* Reduce motion */
    @media (prefers-reduced-motion: reduce){
      .btn{transition:none}
    }
  </style>

  <!-- Structured data (SEO) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "[Marka Adı]",
    "url": "https://[domainin.com]/",
    "email": "mailto:[mail@domainin.com]",
    "sameAs": ["[varsa-linkedin-url]", "[varsa-instagram-url]"]
  }
  </script>
</head>

<body>
  <header class="nav" role="banner">
    <div class="nav-inner">
      <a class="brand" href="#top" aria-label="Ana sayfa">
        <div class="logo" aria-hidden="true"></div>
        <span>[Marka Adı]</span>
      </a>
      <nav class="nav-right" aria-label="Site menüsü">
        <a class="link" href="#hakkinda">Hakkında</a>
        <a class="link" href="#hizmetler">Hizmetler</a>
        <a class="link" href="#iletisim">İletişim</a>
        <a class="btn small" href="mailto:[mail@domainin.com]">E-posta</a>
        <a class="btn primary small" href="#iletisim">Teklif Al</a>
      </nav>
    </div>
  </header>

  <main id="top" class="wrap">
    <!-- HERO -->
    <section class="hero" aria-label="Giriş">
      <div class="hero-grid">
        <div class="card hero-main">
          <div class="kicker"><span class="dot" aria-hidden="true"></span> [İş / Proje / Kişisel Site]</div>
          <h1>[Kısa, güçlü bir başlık]<br/>[Değer önerisi: neyi, kime, nasıl?]</h1>
          <p class="lead">
            [1–2 cümlelik kısa açıklama. Örn: “Markanız için modern ve hızlı web çözümleri sunuyorum.
            Basit, şık ve dönüşüm odaklı tasarım.”]
          </p>
          <div class="hero-actions">
            <a class="btn primary" href="mailto:[mail@domainin.com]?subject=Teklif%20Talebi%20-%20[Marka%20Ad%C4%B1]">📩 Teklif iste</a>
            <a class="btn" href="#hizmetler">✨ Hizmetleri gör</a>
            <a class="btn" href="https://wa.me/[90XXXXXXXXXX]?text=Merhaba%2C%20[Marka%20Ad%C4%B1]%20hakk%C4%B1nda%20bilgi%20almak%20istiyorum." target="_blank" rel="noopener">💬 WhatsApp</a>
          </div>
        </div>

        <aside class="card hero-side" aria-label="Özet bilgiler">
          <div class="mini">
            <strong>Hızlı & Mobil Uyumlu</strong>
            <span>Tek sayfa, hızlı açılan, modern bir deneyim.</span>
          </div>
          <div class="mini">
            <strong>Net Mesaj</strong>
            <span>Ziyaretçi 5 saniyede ne yaptığınızı anlar.</span>
          </div>
          <div class="mini">
            <strong>İletişim Kolay</strong>
            <span>E-posta ve WhatsApp ile tek tıkla ulaşım.</span>
          </div>
        </aside>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="hakkinda" class="section" aria-label="Hakkında">
      <div class="card box">
        <h2>Hakkında</h2>
        <p>
          [Kendiniz/ekibiniz/markanız hakkında 3–5 cümle. Örn: “Ben [Ad Soyad]. [X] yıldır
          [alan] üzerinde çalışıyorum. Amacım, karmaşıklığı azaltıp hızlı ve ölçülebilir sonuç üretmek.”]
        </p>

        <div class="split">
          <div class="feature">
            <div class="icon" aria-hidden="true">🎯</div>
            <h3>Odak</h3>
            <p>[Hedef kitleniz ve odak alanınız. Örn: KOBİ’ler, bireysel danışmanlar, creator’lar.]</p>
          </div>
          <div class="feature">
            <div class="icon" aria-hidden="true">⚡</div>
            <h3>Yaklaşım</h3>
            <p>[Nasıl çalışırsınız? Örn: hızlı prototip, iterasyon, sade tasarım, SEO temeli.]</p>
          </div>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="hizmetler" class="section" aria-label="Hizmetler">
      <div class="card box">
        <h2>Hizmetler / İçerik</h2>
        <p>[Sunduğunuz hizmetleri/başlıkları kısa bir cümleyle özetleyin.]</p>

        <div class="grid-3" role="list">
          <div class="feature" role="listitem">
            <div class="icon" aria-hidden="true">🧩</div>
            <h3>[Hizmet 1]</h3>
            <p>[1 cümle açıklama. Örn: Tek sayfa tanıtım sitesi, hızlı teslim.]</p>
          </div>
          <div class="feature" role="listitem">
            <div class="icon" aria-hidden="true">📈</div>
            <h3>[Hizmet 2]</h3>
            <p>[Örn: SEO temeli + performans optimizasyonu.]</p>
          </div>
          <div class="feature" role="listitem">
            <div class="icon" aria-hidden="true">🛠️</div>
            <h3>[Hizmet 3]</h3>
            <p>[Örn: Güncelleme, bakım, içerik düzenleme.]</p>
          </div>
        </div>

        <ul class="list" aria-label="Ek maddeler">
          <li><span class="check" aria-hidden="true">✓</span> [Öne çıkan fayda: hızlı kurulum / sade tasarım / net mesaj]</li>
          <li><span class="check" aria-hidden="true">✓</span> [Öne çıkan fayda: mobil uyum / erişilebilirlik]</li>
          <li><span class="check" aria-hidden="true">✓</span> [Öne çıkan fayda: iletişim ve dönüşüm odaklı CTA]</li>
        </ul>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="iletisim" class="section" aria-label="İletişim">
      <div class="card contact">
        <div>
          <h2>İletişim</h2>
          <p class="muted">Kısa bir mesaj bırakın; genelde aynı gün dönüş yaparım.</p>
        </div>

        <div class="contact-row">
          <a class="btn primary" href="mailto:[mail@domainin.com]?subject=İletişim%20-%20[Marka%20Ad%C4%B1]">📩 [mail@domainin.com]</a>
          <a class="btn" href="https://wa.me/[90XXXXXXXXXX]?text=Merhaba%2C%20[Marka%20Ad%C4%B1]%20ile%20ileti%C5%9Fime%20ge%C3%A7mek%20istiyorum." target="_blank" rel="noopener">💬 WhatsApp</a>
          <a class="btn" href="tel:+[90XXXXXXXXXX]">📞 +[90XXXXXXXXXX]</a>
        </div>

        <div class="mini">
          <strong>Çalışma Saatleri</strong>
          <span>[Örn: Hafta içi 09:00–18:00] • <span class="muted">Konum:</span> [İl / Ülke]</span>
        </div>
      </div>
    </section>

    <footer>
      <div class="foot">
        <div>© <span id="yil"></span> [Marka Adı]. Tüm hakları saklıdır.</div>
        <div class="muted">
          <a class="link" href="#top">Yukarı çık ↑</a>
        </div>
      </div>
    </footer>
  </main>

  <script>
    // küçük dokunuş: yıl otomatik
    document.getElementById("yil").textContent = new Date().getFullYear();

    // anchor smooth scroll (native destek yoksa)
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener("click", (e)=>{
        const id = a.getAttribute("href");
        if(!id || id === "#") return;
        const el = document.querySelector(id);
        if(!el) return;
        e.preventDefault();
        el.scrollIntoView({behavior:"smooth", block:"start"});
      });
    });
  </script>
</body>
</html>

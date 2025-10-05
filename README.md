<!doctype html>
<html lang="ro">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>HRT — Servicii Drone</title>
  <meta name="description" content="HRT: Sitecard, Fermă Lite / Construcții Lite, Reel Outdoor, Livrare surpriză. Foto & video aerian, simplu și sigur.">
  <link rel="icon" href="img/logo.png">
  <style>
    :root{ --bg:#07080b; --cyan:#00e6ff; --magenta:#ff3bff; --text:#e6f7ff; }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--text);font:16px/1.5 system-ui,Segoe UI,Roboto,Arial}
    header{text-align:center;padding:40px 20px}
    header img{width:220px;filter:drop-shadow(0 0 12px rgba(0,230,255,.6))}
    header .motto{margin:12px 0 0;color:var(--cyan);letter-spacing:.08em;text-shadow:0 0 8px rgba(0,230,255,.4)}
    main{max-width:980px;margin:0 auto;padding:20px}
    h2{margin:26px 0 14px;color:var(--cyan);text-align:center;text-shadow:0 0 8px rgba(0,230,255,.35)}
    .services{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));margin:22px 0 34px}
    .card{background:rgba(255,255,255,.02);border:1px solid rgba(0,230,255,.3);border-radius:12px;padding:18px;box-shadow:0 0 18px rgba(0,230,255,.08);text-align:center}
    .card h3{color:var(--cyan);margin:0 0 8px}
    .card p{margin:6px 0;color:#cfe9e2}
    .price{color:var(--magenta);font-weight:700;margin-top:8px}
    .btn{display:inline-block;margin-top:10px;padding:10px 16px;border-radius:6px;border:1px solid var(--cyan);color:var(--cyan);text-decoration:none;font-weight:600}
    .btn:hover{background:var(--cyan);color:#000}
    .panel{margin:34px 0;padding:20px;background:rgba(255,255,255,.02);border:1px solid rgba(0,230,255,.25);border-radius:12px}
    .panel p{margin:10px 0}
    .contact p{font-size:18px}
    footer{text-align:center;padding:20px 12px;font-size:13px;opacity:.75}
  </style>
</head>
<body>

<header>
  <img src="img/logo.png" alt="HRT Logo">
  <div class="motto">SEE BEYOND · THE FUTURE IS AERIAL</div>
</header>

<main>
  <h2>Servicii</h2>
  <div class="services">
    <div class="card">
      <h3>Sitecard</h3>
      <p>12 fotografii + video 45–60s + ortofotoplan (terenuri rurale).</p>
      <p class="price">499 RON</p>
      <a class="btn" href="#contact">Solicită ofertă</a>
    </div>
    <div class="card">
      <h3>Fermă Lite / Construcții Lite</h3>
      <p>20+ fotografii + raport PDF + clip scurt (monitorizare câmp/ferme sau șantiere).</p>
      <p class="price">699 RON</p>
      <a class="btn" href="#contact">Solicită ofertă</a>
    </div>
    <div class="card">
      <h3>Reel Outdoor</h3>
      <p>Reel vertical 30s + 6 fotografii editate (pensiuni / turism).</p>
      <p class="price">450 RON</p>
      <a class="btn" href="#contact">Solicită ofertă</a>
    </div>
    <div class="card">
      <h3>Livrare surpriză</h3>
      <p>Scrisori / invitații / inele — livrare discretă cu filmare scurtă a momentului.</p>
      <p class="price">la cerere</p>
      <a class="btn" href="#contact">Solicită ofertă</a>
    </div>
  </div>

  <section id="contact" class="panel contact">
    <h2>Contact</h2>
    <p><strong>Email:</strong> contact@hrt.ro</p>
    <p><strong>Telefon:</strong> +40 742 511 239</p>
  </section>

  <section class="panel legal">
    <h2>Legal Disclaimer</h2>
    <p>Operăm în conformitate cu reglementările UE și AACR România.</p>
    <p>Pilot certificat <strong>A1/A3</strong> și <strong>A2</strong>.</p>
    <p>Categorii de operare: <strong>Open A3</strong> și <strong>A2</strong>.</p>
    <p>Companie înregistrată: <strong>HRT SRL</strong> (CUI 32433428).</p>
    <p>Respectăm confidențialitatea și nu desfășurăm activități neautorizate.</p>
  </section>
</main>

<footer>© <span id="y"></span> HRT</footer>
<script>document.getElementById('y').textContent=new Date().getFullYear();</script>

</body>
</html>

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Lucas Salvo — README</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#98a0b3;
      --accent:#6ee7b7;
      --glass: rgba(255,255,255,0.04);
      --maxw:900px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,Arial,Helvetica,sans-serif;
      background: radial-gradient(1200px 600px at 10% 10%, rgba(99,102,241,0.12), transparent 6%),
                  radial-gradient(1000px 500px at 90% 90%, rgba(16,185,129,0.06), transparent 6%),
                  var(--bg);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px 16px;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .container{
      width:100%;
      max-width:var(--maxw);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:16px;
      padding:28px;
      box-shadow: 0 10px 30px rgba(2,6,23,0.6), inset 0 1px 0 rgba(255,255,255,0.02);
      border:1px solid rgba(255,255,255,0.03);
      backdrop-filter: blur(6px) saturate(120%);
    }

    header{
      display:flex;
      gap:20px;
      align-items:center;
    }

    .avatar{
      width:96px;height:96px;border-radius:14px;flex:0 0 96px;
      background:linear-gradient(135deg,#111827,#0b1220);
      display:flex;align-items:center;justify-content:center;
      font-weight:800;font-size:28px;color:var(--accent);
      box-shadow:0 6px 18px rgba(16,24,40,0.6);
      border:1px solid rgba(255,255,255,0.03);
    }

    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}

    .grid{
      display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px;
    }

    .card{background:var(--card);border-radius:12px;padding:18px;border:1px solid rgba(255,255,255,0.02)}

    .about h2{margin-top:0;font-size:16px}
    ul{padding-left:18px;margin:8px 0}
    li{margin:6px 0;color:var(--muted)}

    a.link{color:var(--accent);text-decoration:none;font-weight:600}

    .sidebar{display:flex;flex-direction:column;gap:12px}

    .btn{
      display:inline-flex;gap:8px;align-items:center;padding:10px 12px;border-radius:10px;
      background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.03);text-decoration:none;color:var(--accent);
      font-weight:600;font-size:14px
    }

    .badges{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
    .badge{padding:6px 10px;border-radius:999px;background:var(--glass);font-size:12px;color:var(--muted)}

    .fun{display:grid;grid-template-columns:1fr 1fr;gap:10px}
    .fact{padding:10px;border-radius:8px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.02);font-size:13px;color:var(--muted)}

    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    /* responsive */
    @media (max-width:880px){
      .grid{grid-template-columns:1fr;}
      .sidebar{order:2}
    }

  </style>
</head>
<body>
  <main class="container">
    <header>
      <div class="avatar">LS</div>
      <div>
        <h1>Hi, I'm <strong>Lucas</strong>!</h1>
        <p class="lead">Student passionate about web development and technology — learning HTML, CSS and starting JavaScript.</p>
      </div>
    </header>

    <div class="grid">
      <section class="card about">
        <h2>About Me</h2>
        <ul>
          <li>Atualmente estudando e aumentando meus conhecimentos em front-end.</li>
          <li>Aprendendo <strong>HTML</strong> e <strong>CSS</strong>, explorando o mundo do <strong>JavaScript</strong>.</li>
          <li>Tenho um <a class="link" href="https://github.com/Lucas-Salvo/Glossario-Tecnico.git" target="_blank">Glossário</a> onde documento conceitos e termos enquanto aprendo.</li>
          <li>Amo jogos, esportes e sou fã de ficção científica.</li>
          <li>Objetivo: me tornar um desenvolvedor especialista e construir uma carreira de sucesso em tecnologia.</li>
        </ul>

        <h2>Fun Facts</h2>
        <div class="fun">
          <div class="fact">Sempre ansioso para aprender algo novo.</div>
          <div class="fact">Ficção científica me inspira a imaginar e construir novas coisas.</div>
          <div class="fact">Acredito no <em>learning by doing</em> — meus projetos evoluem ao longo do tempo.</div>
          <div class="fact">Gosto de explorar ideias com código e protótipos pequenos.</div>
        </div>

      </section>

      <aside class="sidebar">
        <div class="card">
          <h3 style="margin:0 0 8px 0">Conecte-se comigo</h3>
          <a class="btn" href="https://www.linkedin.com/in/lucas-corrêia-salvo-a9a490333" target="_blank">LinkedIn</a>
          <div class="badges" style="margin-top:12px">
            <div class="badge">HTML</div>
            <div class="badge">CSS</div>
            <div class="badge">JavaScript (iniciando)</div>
            <div class="badge">Front-end</div>
          </div>
        </div>

        <div class="card">
          <h3 style="margin:0 0 8px 0">Projetos</h3>
          <p style="margin:0 0 8px 0;color:var(--muted)">Confira meu repositório de glossário com termos e explicações enquanto eu aprendo.</p>
          <a class="btn" href="https://github.com/Lucas-Salvo/Glossario-Tecnico.git" target="_blank">Abrir Glossário</a>
        </div>

        <div class="card">
          <h3 style="margin:0 0 8px 0">Contato</h3>
          <p style="margin:0;color:var(--muted)">Sinta-se à vontade para me seguir e mandar uma mensagem no LinkedIn.</p>
        </div>
      </aside>
    </div>

    <footer>
      Thanks for visiting my profile! — Feel free to check my projects and follow my journey.
    </footer>
  </main>
</body>
</html>

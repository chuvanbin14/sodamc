<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>sodamc — Official</title>
  <meta name="description" content="sodamc - server Minecraft VN | Addons, Plugin, Hướng dẫn">
  <style>
    :root{
      --bg:#070707;
      --card:#0f0f11;
      --muted:#9aa3af;
      --accent:#38d39f;
      --glass: rgba(255,255,255,0.03);
      --glass-2: rgba(255,255,255,0.02);
      --radius:14px;
      --max-width:1100px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; padding:24px; background:linear-gradient(180deg,#050506 0%, #0b0b0c 100%); color:#e6eef3; -webkit-font-smoothing:antialiased;
      display:flex; justify-content:center; font-size:16px;
    }
    .wrap{width:100%; max-width:var(--max-width)}

    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:22px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,#3b3b3b,#111);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);font-size:20px;box-shadow:0 6px 18px rgba(0,0,0,0.6)}
    .title{line-height:1}
    .title h1{margin:0;font-size:18px}
    .title p{margin:0;color:var(--muted);font-size:13px}

    .cta{display:flex;gap:8px;align-items:center}
    .btn{background:linear-gradient(90deg,var(--accent),#25b98f);border:none;padding:10px 14px;border-radius:10px;color:#02110b;font-weight:700;cursor:pointer}
    .ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:10px;color:var(--muted);cursor:pointer}

    .hero{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-bottom:24px}
    .hero-card{background:linear-gradient(180deg,var(--card),#0b0b0c);padding:20px;border-radius:18px;box-shadow:0 8px 30px rgba(2,6,10,0.6);border:1px solid rgba(255,255,255,0.03)}
    .hero h2{margin:0 0 8px 0}
    .ip{display:flex;align-items:center;gap:8px;background:var(--glass);padding:10px;border-radius:10px}
    .ip strong{font-family:monospace}
    .copy{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:6px 8px;border-radius:8px;color:var(--muted);cursor:pointer}

    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:18px}
    .section-title{display:flex;align-items:center;justify-content:space-between;margin-bottom:12px}
    .cards{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .card h3{margin:0 0 6px 0}
    .card p{margin:0;color:var(--muted);font-size:14px}
    .small{font-size:13px;color:var(--muted)}

    .plugin-list{display:flex;flex-direction:column;gap:10px}
    .plugin{display:flex;align-items:center;gap:12px}
    .plugin .icon{width:56px;height:56px;border-radius:8px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:700}
    .plugin .meta{flex:1}
    .plugin .meta h4{margin:0;font-size:15px}
    .plugin .meta p{margin:4px 0 0 0;font-size:13px;color:var(--muted)}
    .plugin .actions{display:flex;gap:8px}
    .link{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:8px 10px;border-radius:8px;color:var(--muted);cursor:pointer}

    .guides .guide{padding:12px;border-radius:10px;background:var(--glass-2);border:1px solid rgba(255,255,255,0.02)}
    .guide h4{margin:0 0 6px}
    .guide ol{margin:6px 0 0 18px;color:var(--muted)}

    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}

    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      .grid{grid-template-columns:1fr}
      .cards{grid-template-columns:1fr}
    }

  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">SO</div>
        <div class="title">
          <h1>sodamc</h1>
          <p>Server Minecraft VN — Addons, Plugin & Hướng dẫn</p>
        </div>
      </div>
      <div class="cta">
        <button class="ghost" id="discordBtn">Join Discord</button>
        <button class="btn" id="playBtn">Copy IP & Play</button>
      </div>
    </header>

    <section class="hero">
      <div class="hero-card">
        <h2>Chào mừng đến với <strong>sodamc</strong></h2>
        <p class="small">Server chạy ổn định, nhiều addon & plugin custom — phù hợp cho cộng đồng VN.</p>

        <div style="height:12px"></div>

        <div class="section-title">
          <h3>Giới thiệu nhanh</h3>
          <span class="small">Cập nhật: <strong id="updated">2 Dec 2025</strong></span>
        </div>
        <p class="small">Phiên bản: <strong>1.20.x</strong> · Loại: <strong>SMP / Addon</strong></p>
        <div style="height:10px"></div>

        <div class="ip">
          <div style="flex:1">
            <div class="small">IP Server</div>
            <div style="display:flex;align-items:center;gap:8px;margin-top:6px">
              <strong id="serverIp">sodamc.example:25565</strong>
              <button class="copy" id="copyIp">Copy</button>
            </div>
          </div>
          <div style="text-align:right">
            <div class="small">Players</div>
            <div style="font-weight:700;font-size:18px">0/200</div>
          </div>
        </div>

        <div style="height:12px"></div>
        <p class="small">Bạn có thể thay IP trong file <code>index.html</code> hoặc trong phần cấu hình GitHub Pages.</p>
      </div>

      <aside class="hero-card">
        <h3>Quick Links</h3>
        <div style="height:10px"></div>
        <div style="display:flex;flex-direction:column;gap:10px">
          <button class="link" onclick="location.hash='addons'">Addons & Plugin</button>
          <button class="link" onclick="location.hash='guides'">Hướng dẫn chơi</button>
          <button class="link" id="downloadBtn">Tải launcher</button>
          <button class="link" id="voteBtn">Vote server</button>
        </div>
      </aside>
    </section>

    <main class="grid">
      <section class="hero-card" id="addons">
        <div class="section-title">
          <h3>Addons & Plugin</h3>
          <span class="small">Miễn phí / Tải trực tiếp</span>
        </div>

        <div class="plugin-list">
          <!-- Example plugin items -->
          <div class="plugin card">
            <div class="icon">P1</div>
            <div class="meta">
              <h4>ExamplePluginCore</h4>
              <p>Plugin core custom: tính năng admin, economy, shop.</p>
            </div>
            <div class="actions">
              <button class="link" onclick="downloadSample('ExamplePluginCore.jar')">Tải</button>
              <button class="link" onclick="showDetails('ExamplePluginCore','1.0.2','Tác dụng: quản lý, economy')">Chi tiết</button>
            </div>
          </div>

          <div class="plugin card">
            <div class="icon">P2</div>
            <div class="meta">
              <h4>SkyAddon</h4>
              <p>Addon skyblock: island, shop, challenges.</p>
            </div>
            <div class="actions">
              <button class="link" onclick="downloadSample('SkyAddon.jar')">Tải</button>
              <button class="link" onclick="showDetails('SkyAddon','2.3.0','Addon Skyblock đầy đủ')">Chi tiết</button>
            </div>
          </div>

        </div>

      </section>

      <section class="hero-card guides" id="guides">
        <div class="section-title">
          <h3>Hướng dẫn chơi</h3>
          <span class="small">Bắt đầu nhanh</span>
        </div>

        <div class="guide">
          <h4>1. Cách kết nối (Java)</h4>
          <ol>
            <li>Khởi động Minecraft phiên bản <strong>1.20.x</strong>.</li>
            <li>Vào Multiplayer → Add Server.</li>
            <li>Copy IP: <code id="guideIp">sodamc.example:25565</code> và dán vào.</li>
            <li>Join và đọc luật trong chat.</li>
          </ol>
        </div>

        <div style="height:10px"></div>

        <div class="guide">
          <h4>2. Cài addon/plugin (Admin)</h4>
          <ol>
            <li>Tải file .jar từ mục Addons.</li>
            <li>Đặt vào folder <code>plugins/</code> trên server Spigot/Paper.</li>
            <li>Restart server để plugin load.</li>
            <li>Kiểm tra console để cấu hình tiếp.</li>
          </ol>
        </div>

        <div style="height:10px"></div>

        <div class="guide">
          <h4>3. Cách báo lỗi / hỗ trợ</h4>
          <ol>
            <li>Vào Discord (button bên trên) và tạo ticket.</li>
            <li>Đính kèm console log hoặc ảnh chụp lỗi.</li>
          </ol>
        </div>

      </section>

    </main>

    <footer>
      © <span id="year">2025</span> sodamc — Built with ♥ · Template for GitHub Pages
    </footer>
  </div>

  <!-- Simple modal / helpers -->
  <script>
    // small helpers to simulate download links (replace with real URLs on your repo)
    function downloadSample(filename){
      // If you host files in repo (e.g. /files/ExamplePluginCore.jar) replace below path
      const base = 'files/' + filename;
      const a = document.createElement('a');
      a.href = base;
      a.download = filename;
      document.body.appendChild(a);
      a.click();
      a.remove();
    }

    function showDetails(name,ver,desc){
      alert(name + ' ('+ver+')\n\n' + desc);
    }

    document.getElementById('copyIp').addEventListener('click', ()=>{
      const ip = document.getElementById('serverIp').innerText;
      navigator.clipboard.writeText(ip).then(()=>{
        alert('Đã copy: ' + ip);
      }).catch(()=>alert('Trình duyệt không hỗ trợ copy'));
    });

    document.getElementById('playBtn').addEventListener('click', ()=>{
      document.getElementById('copyIp').click();
    });

    document.getElementById('discordBtn').addEventListener('click', ()=>{
      // replace with your discord invite link
      window.open('https://discord.gg/your-invite','_blank');
    });

    document.getElementById('downloadBtn').addEventListener('click', ()=>{
      // optionally link to a launcher or resource
      alert('Chưa có launcher. Bạn có thể upload file trong thư mục /files và chỉnh link trong mã nguồn.');
    });

    document.getElementById('voteBtn').addEventListener('click', ()=>{
      alert('Chức năng vote chưa cấu hình. Thêm link vote ở đây.');
    });

    // auto set year and sample ip values
    document.getElementById('year').innerText = new Date().getFullYear();
    // TODO: replace example IP with your real IP
    const defaultIp = 'play.sodamc.vn:25565';
    document.getElementById('serverIp').innerText = defaultIp;
    document.getElementById('guideIp').innerText = defaultIp;

  </script>
</body>
</html>

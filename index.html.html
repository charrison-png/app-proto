<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UrbanSketch — App Prototype</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=DM+Sans:wght@300;400;500&family=Special+Elite&display=swap');
  * { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --ink: #1a1410; --paper: #f5f0e8; --paper2: #ede7d9; --paper3: #e4ddd0;
    --accent: #c45c2a; --accent2: #4a7c6f; --muted: #8a7f72; --border: rgba(26,20,16,0.12);
    --passport-cover: #1a3a5c; --passport-inner: #f7f3ec;
    --gold: #c9963a; --gold-light: #f0d080; --gold-bg: #fdf6e3;
    --asia-red: #b33a2a; --asia-gold: #d4a020; --asia-bg: #fdf0e8;
  }
  body { font-family:'DM Sans',sans-serif; background:#e8e2d8; display:flex; flex-direction:column; align-items:center; justify-content:center; min-height:100vh; padding:2rem 1rem 3rem; }
  h1 { font-family:'Playfair Display',serif; font-size:15px; color:#8a7f72; letter-spacing:0.12em; text-transform:uppercase; margin-bottom:8px; text-align:center; }
  .tagline { font-size:12px; color:#aaa; letter-spacing:0.06em; margin-bottom:20px; text-align:center; }
  .phone { width:340px; background:var(--paper); border-radius:36px; overflow:hidden; box-shadow:0 24px 64px rgba(0,0,0,0.22),0 2px 8px rgba(0,0,0,0.1); border:1px solid rgba(0,0,0,0.08); }
  .status-bar { background:var(--ink); color:var(--paper); font-size:11px; padding:10px 20px 8px; display:flex; justify-content:space-between; }
  .screen { display:none; animation:fadeIn 0.25s ease; }
  .screen.active { display:block; }
  @keyframes fadeIn { from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)} }
  .nav { display:flex; background:var(--ink); }
  .nav-btn { flex:1; background:none; border:none; color:var(--muted); padding:9px 2px 11px; font-family:'DM Sans',sans-serif; font-size:9px; font-weight:500; letter-spacing:0.04em; text-transform:uppercase; cursor:pointer; display:flex; flex-direction:column; align-items:center; gap:3px; transition:color 0.15s; min-width:0; }
  .nav-btn.active { color:var(--paper); }
  .nav-btn svg { width:16px; height:16px; flex-shrink:0; }
  .section-title { font-size:11px; font-weight:500; letter-spacing:0.1em; text-transform:uppercase; color:var(--muted); padding:16px 20px 10px; }
  .home-header { background:var(--ink); color:var(--paper); padding:20px 20px 28px; }
  .app-name { font-family:'Playfair Display',serif; font-size:26px; letter-spacing:-0.01em; margin-bottom:2px; }
  .app-sub { font-size:12px; color:#9a9080; letter-spacing:0.08em; text-transform:uppercase; }
  .next-event-card { background:var(--paper); margin:-14px 16px 0; border-radius:14px; padding:14px 16px; border:1px solid var(--border); position:relative; z-index:2; }
  .event-tag { display:inline-block; font-size:10px; font-weight:500; letter-spacing:0.1em; text-transform:uppercase; color:var(--accent); margin-bottom:6px; }
  .event-title { font-family:'Playfair Display',serif; font-size:17px; color:var(--ink); margin-bottom:4px; }
  .event-meta { font-size:12px; color:var(--muted); display:flex; gap:12px; }
  .check-in-btn { width:100%; margin-top:12px; background:var(--accent); color:white; border:none; border-radius:8px; padding:10px; font-family:'DM Sans',sans-serif; font-size:13px; font-weight:500; cursor:pointer; }
  .stats-row { display:grid; grid-template-columns:1fr 1fr 1fr; gap:8px; padding:0 16px 4px; }
  .stat-pill { background:var(--paper2); border-radius:10px; padding:10px 8px; text-align:center; border:1px solid var(--border); }
  .stat-num { font-family:'Playfair Display',serif; font-size:22px; color:var(--ink); line-height:1; }
  .stat-lbl { font-size:10px; color:var(--muted); margin-top:3px; letter-spacing:0.04em; }
  .milestone-banner { margin:14px 16px; background:linear-gradient(135deg,#4a7c6f,#3a6460); border-radius:12px; padding:14px 16px; display:flex; align-items:center; gap:12px; cursor:pointer; }
  .milestone-icon { width:38px; height:38px; background:rgba(255,255,255,0.15); border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:18px; flex-shrink:0; }
  .milestone-text { color:white; }
  .milestone-text strong { font-size:14px; font-weight:500; display:block; }
  .milestone-text span { font-size:11px; opacity:0.75; }
  .recent-list { padding:0 16px 16px; display:flex; flex-direction:column; gap:8px; }
  .recent-item { display:flex; align-items:center; gap:12px; padding:10px 12px; background:var(--paper2); border-radius:10px; }
  .sketch-thumb { width:38px; height:38px; border-radius:6px; background:var(--ink); display:flex; align-items:center; justify-content:center; font-size:16px; flex-shrink:0; }
  .recent-info { flex:1; }
  .recent-info .r-title { font-size:13px; font-weight:500; color:var(--ink); }
  .recent-info .r-date { font-size:11px; color:var(--muted); }
  .recent-pts { font-size:13px; }
  .events-header { background:var(--ink); color:var(--paper); padding:20px; }
  .events-header h2 { font-family:'Playfair Display',serif; font-size:22px; margin-bottom:10px; }
  .filter-row { display:flex; gap:6px; flex-wrap:wrap; }
  .filter-chip { font-size:10px; font-weight:500; letter-spacing:0.04em; padding:4px 10px; border-radius:20px; border:1px solid rgba(255,255,255,0.2); color:rgba(255,255,255,0.6); background:none; cursor:pointer; font-family:'DM Sans',sans-serif; }
  .filter-chip.on { background:var(--accent); border-color:var(--accent); color:white; }
  .event-list { padding:12px 16px; display:flex; flex-direction:column; gap:10px; }
  .event-row { background:white; border-radius:12px; padding:14px; border:1px solid var(--border); display:flex; gap:12px; align-items:flex-start; cursor:pointer; }
  .event-date-box { border-radius:8px; width:40px; text-align:center; padding:6px 4px; flex-shrink:0; }
  .event-date-box.std { background:var(--ink); color:var(--paper); }
  .event-date-box.symp { background:linear-gradient(160deg,#b8860b,#daa520,#c9963a); color:#fff8e0; }
  .event-date-box.asia { background:var(--asia-red); color:#fff0e0; }
  .event-date-box .day { font-family:'Playfair Display',serif; font-size:18px; line-height:1; }
  .event-date-box .mon { font-size:9px; letter-spacing:0.08em; text-transform:uppercase; opacity:0.7; margin-top:2px; }
  .event-info { flex:1; }
  .event-info .title { font-size:14px; font-weight:500; color:var(--ink); margin-bottom:3px; }
  .event-info .loc { font-size:12px; color:var(--muted); margin-bottom:6px; }
  .event-badge { display:inline-block; font-size:10px; padding:2px 8px; border-radius:20px; font-weight:500; letter-spacing:0.04em; }
  .badge-usk { background:#e8eef5; color:#1a3a5c; }
  .badge-symp { background:var(--gold-bg); color:#7a5800; border:1px solid #d4a020; }
  .badge-asia { background:var(--asia-bg); color:var(--asia-red); border:1px solid #e0a060; }
  .badge-solo { background:#f5ece6; color:var(--accent); }
  .attendees { font-size:11px; color:var(--muted); align-self:flex-start; white-space:nowrap; }
  .passport-book { margin:16px 16px 0; border-radius:12px; overflow:hidden; box-shadow:0 4px 20px rgba(0,0,0,0.18); }
  .passport-cover { background:var(--passport-cover); padding:16px 20px; text-align:center; position:relative; overflow:hidden; }
  .passport-cover::before { content:''; position:absolute; inset:0; background:repeating-linear-gradient(45deg,transparent,transparent 8px,rgba(255,255,255,0.02) 8px,rgba(255,255,255,0.02) 9px); }
  .passport-emblem { font-size:28px; margin-bottom:4px; position:relative; z-index:1; }
  .passport-title { font-family:'Special Elite',monospace; font-size:12px; color:#c9b882; letter-spacing:0.18em; text-transform:uppercase; position:relative; z-index:1; }
  .passport-subtitle { font-family:'Special Elite',monospace; font-size:9px; color:rgba(201,184,130,0.6); letter-spacing:0.12em; margin-top:2px; position:relative; z-index:1; }
  .passport-inner { background:var(--passport-inner); }
  .owner-strip { padding:10px 14px; border-bottom:1px solid rgba(26,20,16,0.1); display:flex; align-items:center; gap:12px; }
  .owner-photo { width:40px; height:40px; background:var(--passport-cover); border-radius:4px; display:flex; align-items:center; justify-content:center; font-family:'Playfair Display',serif; font-size:15px; color:#c9b882; flex-shrink:0; }
  .owner-details { flex:1; }
  .owner-name { font-family:'Special Elite',monospace; font-size:12px; color:var(--ink); letter-spacing:0.04em; }
  .owner-id { font-size:10px; color:var(--muted); margin-top:2px; font-family:'Special Elite',monospace; }
  .country-count { text-align:right; }
  .country-count .big { font-family:'Playfair Display',serif; font-size:24px; color:var(--passport-cover); line-height:1; }
  .country-count .lbl { font-size:9px; color:var(--muted); letter-spacing:0.06em; text-transform:uppercase; }
  .page-tabs { display:flex; border-bottom:1px solid rgba(26,20,16,0.1); background:var(--passport-inner); }
  .page-tab { flex:1; padding:8px 4px; font-family:'Special Elite',monospace; font-size:10px; letter-spacing:0.06em; text-transform:uppercase; color:var(--muted); text-align:center; cursor:pointer; border-bottom:2px solid transparent; transition:all 0.15s; }
  .page-tab.active { color:var(--passport-cover); border-bottom-color:var(--passport-cover); }
  .passport-page { display:none; }
  .passport-page.active { display:block; }
  .stamps-grid { padding:12px; display:grid; grid-template-columns:repeat(3,1fr); gap:8px; }
  .stamp { aspect-ratio:1; border-radius:4px; display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; position:relative; overflow:hidden; cursor:pointer; }
  .stamp.earned { background:var(--passport-inner); border:1.5px solid rgba(26,20,16,0.15); }
  .stamp.earned::after { content:''; position:absolute; inset:3px; border:1px solid rgba(26,20,16,0.08); border-radius:2px; pointer-events:none; }
  .stamp.locked { background:repeating-linear-gradient(45deg,#ede7d9,#ede7d9 4px,#e8e2d4 4px,#e8e2d4 8px); border:1.5px dashed rgba(26,20,16,0.15); opacity:0.45; }
  .stamp-flag { font-size:24px; margin-bottom:2px; }
  .stamp-country { font-family:'Special Elite',monospace; font-size:7.5px; color:var(--ink); letter-spacing:0.05em; text-transform:uppercase; line-height:1.2; }
  .stamp-date { font-size:7.5px; color:var(--muted); margin-top:2px; font-family:'Special Elite',monospace; }
  .stamp-ink { position:absolute; inset:0; border-radius:3px; pointer-events:none; }
  .s-au .stamp-ink{background:rgba(0,90,180,0.05)} .s-uk .stamp-ink{background:rgba(180,0,0,0.05)} .s-jp .stamp-ink{background:rgba(188,0,45,0.05)} .s-fr .stamp-ink{background:rgba(0,35,149,0.05)}
  .awards-page { padding:12px 14px 16px; display:flex; flex-direction:column; gap:14px; }
  .shield-item { display:flex; gap:12px; align-items:flex-start; }
  .shield-wrap { flex-shrink:0; display:flex; flex-direction:column; align-items:center; gap:6px; }
  .shield-count { font-family:'Special Elite',monospace; font-size:9px; color:var(--gold); letter-spacing:0.08em; text-align:center; }
  .award-info { flex:1; padding-top:2px; }
  .award-name { font-family:'Special Elite',monospace; font-size:12px; color:var(--ink); letter-spacing:0.06em; text-transform:uppercase; margin-bottom:3px; }
  .award-desc { font-size:11px; color:var(--muted); line-height:1.45; }
  .award-years { display:flex; gap:5px; margin-top:6px; flex-wrap:wrap; }
  .year-pip { font-family:'Special Elite',monospace; font-size:9px; padding:2px 7px; border-radius:3px; letter-spacing:0.06em; }
  .year-pip.symp { background:var(--gold-bg); color:#7a5800; border:1px solid #d4b840; }
  .year-pip.asia { background:var(--asia-bg); color:var(--asia-red); border:1px solid #e0a060; }
  .year-pip.locked { background:var(--paper2); color:var(--muted); border:1px dashed var(--border); opacity:0.6; }
  .hex-wrap { flex-shrink:0; display:flex; flex-direction:column; align-items:center; gap:6px; }
  .divider { height:1px; background:rgba(26,20,16,0.08); }
  .mrz-strip { background:#f0ead8; padding:6px 14px; border-top:1px solid rgba(26,20,16,0.08); }
  .mrz-line { font-family:'Special Elite',monospace; font-size:7.5px; color:rgba(26,20,16,0.28); letter-spacing:0.1em; white-space:nowrap; overflow:hidden; }
  .how-to-earn { margin:12px 16px 0; background:#f0ead8; border-radius:10px; padding:12px 14px; border-left:3px solid var(--passport-cover); }
  .how-to-earn .ht-title { font-size:11px; font-weight:500; letter-spacing:0.06em; text-transform:uppercase; color:var(--passport-cover); margin-bottom:5px; }
  .how-to-earn p { font-size:12px; color:var(--muted); line-height:1.5; }
  .progress-row { margin:10px 16px 16px; display:flex; gap:8px; }
  .prog-pill { flex:1; background:var(--paper2); border-radius:8px; padding:10px; text-align:center; border:1px solid var(--border); }
  .prog-pill .pn { font-family:'Playfair Display',serif; font-size:18px; color:var(--ink); }
  .prog-pill .pl { font-size:9px; color:var(--muted); letter-spacing:0.04em; }
  .profile-header { background:var(--ink); color:var(--paper); padding:20px 20px 32px; position:relative; overflow:hidden; }
  .profile-header::before { content:''; position:absolute; right:-20px; top:-20px; width:120px; height:120px; border-radius:50%; border:1px solid rgba(255,255,255,0.06); }
  .avatar { width:52px; height:52px; background:var(--accent); border-radius:50%; display:flex; align-items:center; justify-content:center; font-family:'Playfair Display',serif; font-size:20px; color:white; margin-bottom:10px; }
  .profile-name { font-family:'Playfair Display',serif; font-size:20px; margin-bottom:2px; }
  .profile-since { font-size:11px; color:#9a9080; }
  .big-stats { display:grid; grid-template-columns:1fr 1fr; gap:10px; margin:-18px 16px 0; position:relative; z-index:2; }
  .big-stat { background:var(--paper); border-radius:12px; padding:14px; border:1px solid var(--border); text-align:center; }
  .big-stat .num { font-family:'Playfair Display',serif; font-size:32px; color:var(--ink); line-height:1; }
  .big-stat .unit { font-size:10px; color:var(--muted); letter-spacing:0.08em; text-transform:uppercase; margin-top:4px; }
  .badges-section { padding:0 16px; }
  .badge-grid { display:flex; gap:8px; flex-wrap:wrap; padding-bottom:8px; }
  .badge-item { display:flex; flex-direction:column; align-items:center; width:58px; }
  .badge-circle { width:44px; height:44px; border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:18px; margin-bottom:4px; }
  .badge-circle.earned { background:var(--ink); }
  .badge-circle.gold { background:linear-gradient(145deg,#b8860b,#daa520,#f0d060); }
  .badge-circle.asia-earned { background:linear-gradient(145deg,var(--asia-red),#d4501a); }
  .badge-circle.locked { background:var(--paper2); border:1.5px dashed var(--border); }
  .badge-item .b-lbl { font-size:9px; color:var(--muted); text-align:center; }
  .log-header { background:var(--ink); color:var(--paper); padding:20px; }
  .log-header h2 { font-family:'Playfair Display',serif; font-size:22px; }
  .log-header p { font-size:12px; color:#9a9080; margin-top:4px; }
  .log-form { padding:16px; display:flex; flex-direction:column; gap:12px; }
  .form-group label { display:block; font-size:11px; font-weight:500; letter-spacing:0.08em; text-transform:uppercase; color:var(--muted); margin-bottom:5px; }
  .form-group input,.form-group select,.form-group textarea { width:100%; background:var(--paper2); border:1px solid var(--border); border-radius:8px; padding:10px 12px; font-family:'DM Sans',sans-serif; font-size:13px; color:var(--ink); outline:none; }
  .form-group textarea { resize:none; height:60px; }
  .upload-box { background:var(--paper2); border:1.5px dashed var(--border); border-radius:10px; padding:16px; text-align:center; cursor:pointer; }
  .upload-box .u-icon { font-size:22px; margin-bottom:4px; }
  .upload-box p { font-size:12px; color:var(--muted); }
  .upload-box span { font-size:11px; color:var(--accent); font-weight:500; }
  .submit-btn { width:100%; background:var(--ink); color:var(--paper); border:none; border-radius:10px; padding:13px; font-family:'Playfair Display',serif; font-size:16px; cursor:pointer; }
  .screen-label { text-align:center; font-size:10px; letter-spacing:0.14em; text-transform:uppercase; color:#999; margin-bottom:8px; font-family:'DM Sans',sans-serif; }
</style>
</head>
<body>

<h1>UrbanSketch</h1>
<p class="tagline">App prototype — click through the screens below</p>
<div class="screen-label" id="screen-label">Home</div>

<div class="phone">
  <div class="status-bar"><span>9:41</span><span>●●●●  WiFi  100%</span></div>

  <!-- HOME -->
  <div class="screen active" id="s-home">
    <div class="home-header">
      <div class="app-name">UrbanSketch</div>
      <div class="app-sub">Your sketching community</div>
    </div>
    <div class="next-event-card">
      <div class="event-tag">▶ Next USk Sketchmeet</div>
      <div class="event-title">Flinders Lane Laneways</div>
      <div class="event-meta"><span>Sat 29 Mar · 9:00 am</span><span>14 going</span></div>
      <button class="check-in-btn" onclick="showScreen('s-events')">View & Check In →</button>
    </div>
    <div class="section-title">Your Stats</div>
    <div class="stats-row">
      <div class="stat-pill"><div class="stat-num">47</div><div class="stat-lbl">Sketches</div></div>
      <div class="stat-pill"><div class="stat-num">23</div><div class="stat-lbl">Locations</div></div>
      <div class="stat-pill"><div class="stat-num">4</div><div class="stat-lbl">Countries</div></div>
    </div>
    <div class="milestone-banner" onclick="showScreen('s-passport')">
      <div class="milestone-icon">🛂</div>
      <div class="milestone-text">
        <strong>Passport: 4 stamps + 2 awards</strong>
        <span>Tap to view your sketch passport →</span>
      </div>
    </div>
    <div class="section-title">Recent Activity</div>
    <div class="recent-list">
      <div class="recent-item">
        <div class="sketch-thumb">🏛</div>
        <div class="recent-info"><div class="r-title">State Library forecourt</div><div class="r-date">Solo · 14 Mar</div></div>
        <div class="recent-pts">+1 loc</div>
      </div>
      <div class="recent-item">
        <div class="sketch-thumb" style="background:linear-gradient(145deg,#b8860b,#daa520);">🏆</div>
        <div class="recent-info"><div class="r-title">USk Symposium — Porto</div><div class="r-date">Official Symposium · Jul 2025</div></div>
        <div class="recent-pts">🥇</div>
      </div>
      <div class="recent-item">
        <div class="sketch-thumb" style="background:var(--asia-red);">🌏</div>
        <div class="recent-info"><div class="r-title">Asialink — Kuala Lumpur</div><div class="r-date">Asialink Event · Oct 2024</div></div>
        <div class="recent-pts">🔴</div>
      </div>
    </div>
  </div>

  <!-- EVENTS -->
  <div class="screen" id="s-events">
    <div class="events-header">
      <h2>Sessions</h2>
      <div class="filter-row">
        <button class="filter-chip on">All</button>
        <button class="filter-chip">USk Official</button>
        <button class="filter-chip">Symposium</button>
        <button class="filter-chip">Asialink</button>
      </div>
    </div>
    <div class="event-list">
      <div class="event-row">
        <div class="event-date-box symp"><div class="day">18</div><div class="mon">Jul</div></div>
        <div class="event-info">
          <div class="title">USk Symposium 2026</div>
          <div class="loc">📍 Lisbon, Portugal 🇵🇹</div>
          <span class="event-badge badge-symp">★ USk Symposium</span>
        </div>
        <div class="attendees">642 going</div>
      </div>
      <div class="event-row">
        <div class="event-date-box asia"><div class="day">09</div><div class="mon">Oct</div></div>
        <div class="event-info">
          <div class="title">Asialink 2026 — Seoul</div>
          <div class="loc">📍 Seoul, Korea 🇰🇷</div>
          <span class="event-badge badge-asia">◆ Asialink Event</span>
        </div>
        <div class="attendees">188 going</div>
      </div>
      <div class="event-row">
        <div class="event-date-box std"><div class="day">29</div><div class="mon">Mar</div></div>
        <div class="event-info">
          <div class="title">USk Melbourne — Flinders Lane</div>
          <div class="loc">📍 Flinders Lane, Melbourne 🇦🇺</div>
          <span class="event-badge badge-usk">🎨 USk Official</span>
        </div>
        <div class="attendees">14 going</div>
      </div>
      <div class="event-row" style="border-style:dashed;opacity:0.75;" onclick="showScreen('s-log')">
        <div class="event-date-box std" style="background:var(--paper2);color:var(--muted);">
          <div style="font-size:22px;line-height:1;">+</div>
        </div>
        <div class="event-info">
          <div class="title" style="color:var(--muted);">Log a solo session</div>
          <div class="loc">Sketch anywhere, anytime</div>
          <span class="event-badge badge-solo">Solo</span>
        </div>
      </div>
    </div>
  </div>

  <!-- PASSPORT -->
  <div class="screen" id="s-passport">
    <div style="background:var(--ink);padding:18px 20px 14px;">
      <div style="font-family:'Playfair Display',serif;font-size:22px;color:var(--paper);">Sketch Passport</div>
      <div style="font-size:12px;color:#9a9080;margin-top:3px;">Country stamps · Special awards</div>
    </div>
    <div class="passport-book">
      <div class="passport-cover">
        <div class="passport-emblem">✏️</div>
        <div class="passport-title">Urban Sketchers</div>
        <div class="passport-subtitle">Sketch Passport</div>
      </div>
      <div class="passport-inner">
        <div class="owner-strip">
          <div class="owner-photo">SJ</div>
          <div class="owner-details">
            <div class="owner-name">JENSEN &lt;&lt; SARAH</div>
            <div class="owner-id">USK · AUS · MEMBER 00847</div>
          </div>
          <div class="country-count">
            <div class="big">4</div>
            <div class="lbl">Countries</div>
          </div>
        </div>
        <div class="page-tabs">
          <div class="page-tab active" onclick="switchPage('pg-stamps',this)">Country Stamps</div>
          <div class="page-tab" onclick="switchPage('pg-awards',this)">Special Awards</div>
        </div>
        <div class="passport-page active" id="pg-stamps">
          <div class="stamps-grid">
            <div class="stamp earned s-au"><div class="stamp-ink"></div><div class="stamp-flag">🇦🇺</div><div class="stamp-country">Australia</div><div class="stamp-date">Mar 2024</div></div>
            <div class="stamp earned s-uk"><div class="stamp-ink"></div><div class="stamp-flag">🇬🇧</div><div class="stamp-country">United Kingdom</div><div class="stamp-date">Jul 2024</div></div>
            <div class="stamp earned s-fr"><div class="stamp-ink"></div><div class="stamp-flag">🇫🇷</div><div class="stamp-country">France</div><div class="stamp-date">Sep 2024</div></div>
            <div class="stamp earned s-jp"><div class="stamp-ink"></div><div class="stamp-flag">🇯🇵</div><div class="stamp-country">Japan</div><div class="stamp-date">Feb 2026</div></div>
            <div class="stamp locked"><div class="stamp-flag" style="opacity:0.3;">🌍</div><div class="stamp-country" style="color:var(--muted);">Unvisited</div></div>
            <div class="stamp locked"><div class="stamp-flag" style="opacity:0.3;">🌍</div><div class="stamp-country" style="color:var(--muted);">Unvisited</div></div>
          </div>
          <div class="mrz-strip">
            <div class="mrz-line">P&lt;AUSJENSENK&lt;&lt;SARAH&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;</div>
            <div class="mrz-line">USK00847AUS8501014F&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;4</div>
          </div>
        </div>
        <div class="passport-page" id="pg-awards">
          <div class="awards-page">
            <div class="shield-item">
              <div class="shield-wrap">
                <svg width="52" height="60" viewBox="0 0 52 60" style="filter:drop-shadow(0 2px 6px rgba(180,130,0,0.35))">
                  <defs>
                    <linearGradient id="goldShield" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#f0d060"/><stop offset="40%" stop-color="#daa520"/><stop offset="100%" stop-color="#a07010"/></linearGradient>
                    <linearGradient id="goldShine" x1="0%" y1="0%" x2="60%" y2="100%"><stop offset="0%" stop-color="rgba(255,248,180,0.7)"/><stop offset="100%" stop-color="rgba(255,248,180,0)"/></linearGradient>
                  </defs>
                  <path d="M26 2 L50 12 L50 30 C50 44 38 55 26 58 C14 55 2 44 2 30 L2 12 Z" fill="url(#goldShield)" stroke="#c9963a" stroke-width="1"/>
                  <path d="M26 2 L50 12 L50 30 C50 44 38 55 26 58 C14 55 2 44 2 30 L2 12 Z" fill="url(#goldShine)"/>
                  <text x="26" y="28" text-anchor="middle" font-family="Special Elite,monospace" font-size="18" fill="#7a5000">✦</text>
                  <text x="26" y="42" text-anchor="middle" font-family="Special Elite,monospace" font-size="7" fill="#7a5000" letter-spacing="1">SYMP</text>
                </svg>
                <div class="shield-count">2× earned</div>
              </div>
              <div class="award-info">
                <div class="award-name">USk Symposium</div>
                <div class="award-desc">One gold shield per Symposium attended. The rarest award in the passport.</div>
                <div class="award-years">
                  <span class="year-pip symp">Porto 2025</span>
                  <span class="year-pip symp">Chicago 2023</span>
                  <span class="year-pip locked">Next?</span>
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <div class="shield-item">
              <div class="hex-wrap">
                <svg width="52" height="58" viewBox="0 0 52 58" style="filter:drop-shadow(0 2px 5px rgba(160,40,20,0.3))">
                  <defs>
                    <linearGradient id="asiaGrad" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#d45030"/><stop offset="50%" stop-color="#b33020"/><stop offset="100%" stop-color="#8a2010"/></linearGradient>
                    <linearGradient id="asiaShine" x1="0%" y1="0%" x2="50%" y2="100%"><stop offset="0%" stop-color="rgba(255,200,150,0.4)"/><stop offset="100%" stop-color="rgba(255,200,150,0)"/></linearGradient>
                  </defs>
                  <polygon points="26,2 50,15 50,43 26,56 2,43 2,15" fill="url(#asiaGrad)" stroke="#e08040" stroke-width="1"/>
                  <polygon points="26,2 50,15 50,43 26,56 2,43 2,15" fill="url(#asiaShine)"/>
                  <text x="26" y="30" text-anchor="middle" font-family="Special Elite,monospace" font-size="16" fill="#ffd080">✦</text>
                  <text x="26" y="44" text-anchor="middle" font-family="Special Elite,monospace" font-size="6.5" fill="#ffd080" letter-spacing="0.5">ASIA</text>
                </svg>
                <div class="shield-count" style="color:var(--asia-red);">1× earned</div>
              </div>
              <div class="award-info">
                <div class="award-name">Asialink Event</div>
                <div class="award-desc">One red hexagon per Asialink yearly event attended.</div>
                <div class="award-years">
                  <span class="year-pip asia">KL 2024</span>
                  <span class="year-pip locked">Seoul 2026?</span>
                </div>
              </div>
            </div>
          </div>
          <div class="mrz-strip">
            <div class="mrz-line">AWARDS&lt;&lt;SYMPOSIUM&lt;&lt;PORTO2025&lt;&lt;CHI2023</div>
            <div class="mrz-line">ASIALINK&lt;&lt;KUALALUMPUR2024&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;&lt;</div>
          </div>
        </div>
      </div>
    </div>
    <div class="how-to-earn">
      <div class="ht-title">How to earn special awards</div>
      <p><strong style="color:var(--gold);font-weight:500;">Gold shield</strong> — attend any USk International Symposium. &nbsp;<strong style="color:var(--asia-red);font-weight:500;">Red hexagon</strong> — attend any USk Asialink yearly event.</p>
    </div>
    <div class="progress-row">
      <div class="prog-pill"><div class="pn">4</div><div class="pl">Countries</div></div>
      <div class="prog-pill"><div class="pn">2</div><div class="pl">Symposiums</div></div>
      <div class="prog-pill"><div class="pn">1</div><div class="pl">Asialink</div></div>
    </div>
  </div>

  <!-- PROFILE -->
  <div class="screen" id="s-profile">
    <div class="profile-header">
      <div class="avatar">SJ</div>
      <div class="profile-name">Sarah Jensen</div>
      <div class="profile-since">Member since Jan 2024 · Melbourne</div>
    </div>
    <div class="big-stats">
      <div class="big-stat"><div class="num">47</div><div class="unit">Total Sketches</div></div>
      <div class="big-stat"><div class="num">23</div><div class="unit">Unique Locations</div></div>
    </div>
    <div class="section-title">Badges & Awards</div>
    <div class="badges-section">
      <div class="badge-grid">
        <div class="badge-item"><div class="badge-circle earned">✏️</div><div class="b-lbl">First Sketch</div></div>
        <div class="badge-item"><div class="badge-circle earned">🗺</div><div class="b-lbl">10 Locations</div></div>
        <div class="badge-item"><div class="badge-circle earned">🔟</div><div class="b-lbl">10 Sketches</div></div>
        <div class="badge-item"><div class="badge-circle earned">🛂</div><div class="b-lbl">4 Countries</div></div>
        <div class="badge-item"><div class="badge-circle gold">🏆</div><div class="b-lbl">Symposium ×2</div></div>
        <div class="badge-item"><div class="badge-circle asia-earned">🌏</div><div class="b-lbl">Asialink ×1</div></div>
        <div class="badge-item"><div class="badge-circle locked">🏅</div><div class="b-lbl">50 Sketches</div></div>
        <div class="badge-item"><div class="badge-circle locked">💯</div><div class="b-lbl">100 Sketches</div></div>
      </div>
    </div>
    <div class="section-title">Recent Sketches</div>
    <div class="recent-list">
      <div class="recent-item">
        <div class="sketch-thumb">🏛</div>
        <div class="recent-info"><div class="r-title">State Library forecourt</div><div class="r-date">Solo · 14 Mar 2026</div></div>
      </div>
      <div class="recent-item">
        <div class="sketch-thumb" style="background:linear-gradient(145deg,#b8860b,#daa520);">🏆</div>
        <div class="recent-info"><div class="r-title">USk Symposium — Porto</div><div class="r-date">Symposium · Jul 2025</div></div>
      </div>
    </div>
  </div>

  <!-- LOG -->
  <div class="screen" id="s-log">
    <div class="log-header">
      <h2>Log a Solo Session</h2>
      <p>Sketch anywhere, anytime</p>
    </div>
    <div class="log-form">
      <div class="form-group"><label>Location</label><input type="text" placeholder="Search or use current location…"></div>
      <div class="form-group"><label>Date</label><input type="text" value="Today — Mon 16 Mar 2026"></div>
      <div class="form-group"><label>Medium</label>
        <select><option>Pen & ink</option><option>Watercolour</option><option>Pencil</option><option>Mixed media</option></select>
      </div>
      <div class="form-group"><label>Notes (optional)</label><textarea placeholder="What did you sketch?"></textarea></div>
      <div class="form-group"><label>Photo (optional)</label>
        <div class="upload-box"><div class="u-icon">📷</div><p>Add a photo of your sketch</p><span>Tap to upload</span></div>
      </div>
      <button class="submit-btn">Log this sketch</button>
    </div>
  </div>

  <!-- NAV -->
  <div class="nav">
    <button class="nav-btn active" id="nav-home" onclick="showScreen('s-home')">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>Home
    </button>
    <button class="nav-btn" id="nav-events" onclick="showScreen('s-events')">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>Sessions
    </button>
    <button class="nav-btn" id="nav-log" onclick="showScreen('s-log')">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="9"/><line x1="12" y1="8" x2="12" y2="16"/><line x1="8" y1="12" x2="16" y2="12"/></svg>Log
    </button>
    <button class="nav-btn" id="nav-passport" onclick="showScreen('s-passport')">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="4" y="2" width="16" height="20" rx="2"/><line x1="9" y1="7" x2="15" y2="7"/><line x1="9" y1="11" x2="15" y2="11"/><line x1="9" y1="15" x2="12" y2="15"/></svg>Passport
    </button>
    <button class="nav-btn" id="nav-profile" onclick="showScreen('s-profile')">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>Profile
    </button>
  </div>
</div>

<script>
const labels={'s-home':'Home','s-events':'Sessions','s-passport':'Passport','s-profile':'Profile','s-log':'Log Solo'};
const navMap={'s-home':'nav-home','s-events':'nav-events','s-passport':'nav-passport','s-profile':'nav-profile','s-log':'nav-log'};
function showScreen(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  document.getElementById(navMap[id]).classList.add('active');
  document.getElementById('screen-label').textContent=labels[id];
}
function switchPage(pageId,tab){
  document.querySelectorAll('.passport-page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.page-tab').forEach(t=>t.classList.remove('active'));
  document.getElementById(pageId).classList.add('active');
  tab.classList.add('active');
}
</script>
</body>
</html>

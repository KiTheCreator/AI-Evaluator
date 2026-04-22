<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YourWay Storage — Call QA</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#06090f;
  --surface:#0d1220;
  --surface2:#131b2e;
  --surface3:#1a253d;
  --border:#1e2d48;
  --border2:#28406b;
  --text:#f0f4ff;
  --muted:#6b82a8;
  --orange:#f97316;
  --orange2:#fb923c;
  --orange3:#fed7aa;
  --orange-dim:rgba(249,115,22,0.13);
  --orange-dim2:rgba(249,115,22,0.06);
  --green:#22c55e;
  --green-dim:rgba(34,197,94,0.1);
  --red:#ef4444;
  --red-dim:rgba(239,68,68,0.1);
  --yellow:#f59e0b;
  --yellow-dim:rgba(245,158,11,0.1);
  --blue:#3b82f6;
  --blue-dim:rgba(59,130,246,0.1);
  --r:8px;--r2:14px;--r3:20px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{font-size:14px}
body{
  font-family:'Plus Jakarta Sans',sans-serif;
  background:var(--bg);color:var(--text);
  min-height:100vh;overflow-x:hidden;
}

/* ══ ANIMATED BACKGROUND ══ */
.bg-wrap{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.bg-grid{
  position:absolute;inset:0;
  background-image:linear-gradient(rgba(249,115,22,0.04) 1px,transparent 1px),
    linear-gradient(90deg,rgba(249,115,22,0.04) 1px,transparent 1px);
  background-size:52px 52px;
  animation:gridMove 20s linear infinite;
}
@keyframes gridMove{0%{background-position:0 0}100%{background-position:52px 52px}}
.orb{position:absolute;border-radius:50%;filter:blur(100px);animation:orbFloat ease-in-out infinite alternate}
.orb1{width:700px;height:700px;background:rgba(249,115,22,0.07);top:-250px;right:-200px;animation-duration:12s;animation-delay:0s}
.orb2{width:500px;height:500px;background:rgba(59,130,246,0.05);bottom:-150px;left:-150px;animation-duration:16s;animation-delay:-5s}
.orb3{width:350px;height:350px;background:rgba(249,115,22,0.04);top:40%;left:30%;animation-duration:10s;animation-delay:-8s}
@keyframes orbFloat{0%{transform:translate(0,0) scale(1)}100%{transform:translate(30px,20px) scale(1.08)}}

/* floating particles */
.particles{position:absolute;inset:0}
.p{position:absolute;width:3px;height:3px;border-radius:50%;background:var(--orange);opacity:0;animation:pFloat linear infinite}
@keyframes pFloat{0%{transform:translateY(100vh) rotate(0deg);opacity:0}10%{opacity:0.6}90%{opacity:0.2}100%{transform:translateY(-100px) rotate(360deg);opacity:0}}

/* ══ HEADER ══ */
.header{
  position:sticky;top:0;z-index:50;
  background:rgba(6,9,15,0.9);backdrop-filter:blur(24px);
  border-bottom:1px solid var(--border);
  height:60px;display:flex;align-items:center;justify-content:space-between;
  padding:0 28px;
}
.logo{display:flex;align-items:center;gap:12px}
.logo-img{
  height:36px;width:auto;
  filter:brightness(1.1);
  animation:logoBob 3s ease-in-out infinite;
}
@keyframes logoBob{0%,100%{transform:translateY(0)}50%{transform:translateY(-2px)}}
.logo-divider{width:1px;height:24px;background:var(--border2)}
.logo-tag{
  font-size:12px;font-weight:700;color:var(--orange);
  letter-spacing:.08em;text-transform:uppercase;
  background:var(--orange-dim);border:1px solid rgba(249,115,22,0.2);
  padding:3px 10px;border-radius:100px;
  animation:tagPulse 2s ease-in-out infinite;
}
@keyframes tagPulse{0%,100%{box-shadow:0 0 0 0 rgba(249,115,22,0.3)}50%{box-shadow:0 0 0 5px rgba(249,115,22,0)}}
.hdr-right{display:flex;align-items:center;gap:10px}
.live-badge{
  display:flex;align-items:center;gap:5px;
  font-size:11px;color:var(--green);font-family:'DM Mono',monospace;
  background:var(--green-dim);border:1px solid rgba(34,197,94,0.2);
  padding:3px 10px;border-radius:100px;
}
.live-dot{width:6px;height:6px;border-radius:50%;background:var(--green);animation:blink 1.5s ease-in-out infinite}
@keyframes blink{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(.8)}}
.co-badge{font-size:11px;color:var(--muted);font-family:'DM Mono',monospace;background:var(--surface2);border:1px solid var(--border);padding:3px 10px;border-radius:100px}

/* ══ LAYOUT ══ */
.layout{display:flex;min-height:calc(100vh - 60px);position:relative;z-index:1}

/* ══ SIDEBAR ══ */
.sidebar{
  width:232px;min-width:232px;
  background:rgba(13,18,32,0.95);
  border-right:1px solid var(--border);
  display:flex;flex-direction:column;padding:20px 0;
  backdrop-filter:blur(10px);
}
.sb-lbl{font-size:10px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);padding:10px 18px 5px;opacity:.5}
.nav-item{
  display:flex;align-items:center;gap:11px;
  padding:10px 18px;cursor:pointer;
  font-size:13px;font-weight:500;color:var(--muted);
  border-left:2px solid transparent;transition:all .18s;
  position:relative;overflow:hidden;
}
.nav-item::before{
  content:'';position:absolute;inset:0;
  background:linear-gradient(90deg,var(--orange-dim),transparent);
  opacity:0;transition:opacity .18s;
}
.nav-item:hover{color:var(--text);border-left-color:var(--border2)}
.nav-item:hover::before{opacity:1}
.nav-item.active{color:var(--orange);border-left-color:var(--orange)}
.nav-item.active::before{opacity:1}
.nav-ico{
  width:30px;height:30px;border-radius:8px;
  display:flex;align-items:center;justify-content:center;
  font-size:15px;flex-shrink:0;background:var(--surface3);
  transition:all .2s;position:relative;z-index:1;
}
.nav-item.active .nav-ico{background:var(--orange-dim);box-shadow:0 0 14px rgba(249,115,22,0.25);transform:scale(1.05)}
.nav-item:hover:not(.active) .nav-ico{transform:scale(1.08) rotate(-3deg)}
.sb-foot{margin-top:auto;padding:14px 18px;border-top:1px solid var(--border)}
.sb-foot-txt{font-size:11px;color:var(--muted);line-height:1.7;font-family:'DM Mono',monospace;opacity:.35}

/* ══ MAIN ══ */
.main{flex:1;overflow-x:hidden;display:flex;flex-direction:column}
.topbar{
  background:rgba(13,18,32,0.7);backdrop-filter:blur(12px);
  border-bottom:1px solid var(--border);
  padding:14px 28px;display:flex;align-items:center;justify-content:space-between;
}
.page-title{font-size:18px;font-weight:800;color:var(--text);letter-spacing:-.4px}
.page-sub{font-size:11px;color:var(--muted);margin-top:2px;font-family:'DM Mono',monospace}
.topbar-btns{display:flex;gap:8px}
.content{padding:24px 28px;flex:1}

/* ══ SCREENS ══ */
.screen{display:none}
.screen.active{display:block;animation:fadeUp .22s ease both}
@keyframes fadeUp{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}

/* ══ CARDS ══ */
.card{
  background:rgba(13,18,32,0.8);
  border:1px solid var(--border);border-radius:var(--r2);
  padding:20px 22px;position:relative;overflow:hidden;
  backdrop-filter:blur(8px);transition:border-color .2s,transform .2s;
}
.card::after{
  content:'';position:absolute;top:0;left:0;right:0;height:1px;
  background:linear-gradient(90deg,transparent,rgba(249,115,22,0.5),transparent);
  transform:translateX(-100%);transition:transform .5s;
}
.card:hover::after{transform:translateX(100%)}
.card:hover{border-color:var(--border2)}
.card+.card{margin-top:14px}
.card-title{font-size:14px;font-weight:700;margin-bottom:4px}
.card-sub{font-size:12px;color:var(--muted);margin-bottom:16px;line-height:1.6;font-family:'DM Mono',monospace}

/* ══ FORMS ══ */
label{font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--muted);display:block;margin-bottom:5px}
input[type=text],input[type=password],select,textarea{
  width:100%;background:var(--surface2);border:1px solid var(--border);
  border-radius:var(--r);color:var(--text);
  font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;
  padding:9px 12px;outline:none;
  transition:border-color .15s,box-shadow .15s;
}
input:focus,select:focus,textarea:focus{
  border-color:var(--orange);
  box-shadow:0 0 0 3px rgba(249,115,22,0.12);
}
textarea{resize:vertical;min-height:190px;font-family:'DM Mono',monospace;font-size:12px;line-height:1.7}
select option{background:var(--surface2)}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px}
.form-group{margin-bottom:12px}

/* ══ BUTTONS ══ */
.btn{
  display:inline-flex;align-items:center;gap:6px;
  padding:8px 16px;border-radius:var(--r);
  border:1px solid var(--border2);background:var(--surface2);
  color:var(--text);font-family:'Plus Jakarta Sans',sans-serif;
  font-size:13px;font-weight:500;cursor:pointer;transition:all .15s;white-space:nowrap;
}
.btn:hover{background:var(--surface3);transform:translateY(-1px);box-shadow:0 4px 12px rgba(0,0,0,0.3)}
.btn:active{transform:scale(.97)}
.btn-primary{background:var(--orange);border-color:var(--orange);color:#fff;font-weight:700}
.btn-primary:hover{background:var(--orange2);border-color:var(--orange2);box-shadow:0 4px 20px rgba(249,115,22,0.4)}
.btn-sm{padding:5px 12px;font-size:12px}
.btn-ghost{background:transparent;border-color:transparent;color:var(--muted)}
.btn-ghost:hover{background:var(--surface2);border-color:var(--border);color:var(--text)}
.btn-danger{border-color:rgba(239,68,68,.3);color:var(--red)}
.btn-danger:hover{background:var(--red-dim)}

/* ══ EVALUATE BUTTON ══ */
.btn-evaluate{
  position:relative;overflow:hidden;
  background:var(--orange);border:none;color:#fff;
  font-size:14px;font-weight:700;padding:13px 36px;border-radius:var(--r);
  cursor:pointer;font-family:'Plus Jakarta Sans',sans-serif;
  display:inline-flex;align-items:center;gap:9px;
  letter-spacing:.01em;
  box-shadow:0 4px 24px rgba(249,115,22,0.4);
  transition:all .2s;
}
.btn-evaluate::before{
  content:'';position:absolute;inset:0;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,0.15),transparent);
  transform:translateX(-100%);
  animation:btnShine 2.5s ease-in-out infinite;
}
@keyframes btnShine{0%{transform:translateX(-100%)}50%,100%{transform:translateX(200%)}}
.btn-evaluate:hover{background:var(--orange2);transform:translateY(-2px);box-shadow:0 8px 32px rgba(249,115,22,0.55)}
.btn-evaluate:active{transform:scale(.97)}
.btn-evaluate .arr{transition:transform .2s}
.btn-evaluate:hover .arr{transform:translateX(4px)}

/* ══ BADGES ══ */
.badge{display:inline-flex;align-items:center;font-size:11px;font-weight:600;padding:2px 8px;border-radius:100px}
.b-orange{background:var(--orange-dim);color:var(--orange)}
.b-green{background:var(--green-dim);color:var(--green)}
.b-red{background:var(--red-dim);color:var(--red)}
.b-yellow{background:var(--yellow-dim);color:var(--yellow)}
.b-blue{background:var(--blue-dim);color:var(--blue)}
.b-gray{background:var(--surface3);color:var(--muted)}

/* ══ STATS ══ */
.stat{
  background:var(--surface2);border:1px solid var(--border);
  border-radius:var(--r2);padding:14px 16px;
  transition:all .2s;cursor:default;
}
.stat:hover{border-color:var(--border2);transform:translateY(-3px);box-shadow:0 8px 24px rgba(0,0,0,0.3)}
.stat-n{font-size:28px;font-weight:800;line-height:1;margin-bottom:4px;font-family:'Plus Jakarta Sans',sans-serif}
.stat-l{font-size:10px;font-weight:700;letter-spacing:.07em;text-transform:uppercase;color:var(--muted)}

/* ══ RUBRIC ══ */
.rub-section{margin-bottom:8px;border:1px solid var(--border);border-radius:var(--r2);overflow:hidden;transition:all .2s}
.rub-section:hover{border-color:var(--border2);box-shadow:0 4px 16px rgba(0,0,0,0.2)}
.rub-head{display:flex;align-items:center;justify-content:space-between;padding:11px 16px;background:var(--surface2);cursor:pointer;transition:background .12s;gap:12px}
.rub-head:hover{background:var(--surface3)}
.rub-head.open{background:var(--surface);border-bottom:1px solid var(--border)}
.rub-name{font-size:13px;font-weight:600}
.rub-meta{display:flex;align-items:center;gap:10px;flex-shrink:0}
.rub-body{display:none;background:var(--surface)}
.rub-body.open{display:block}
.crit-row{display:grid;grid-template-columns:1fr auto;gap:14px;align-items:center;padding:9px 16px;border-bottom:1px solid var(--border);transition:background .1s}
.crit-row:last-child{border-bottom:none}
.crit-row:hover{background:rgba(249,115,22,0.03)}
.crit-text{color:var(--muted);line-height:1.5;font-size:12px}
.crit-pills{display:flex;gap:3px}
.pill{
  width:28px;height:28px;border-radius:var(--r);
  border:1px solid var(--border2);background:transparent;
  color:var(--muted);font-size:12px;font-weight:600;
  cursor:pointer;display:flex;align-items:center;justify-content:center;
  transition:all .12s;font-family:'DM Mono',monospace;
}
.pill:hover{border-color:var(--text);color:var(--text);transform:scale(1.15)}
.pill:active{transform:scale(.9)}
.pill.s0{background:var(--red-dim);border-color:var(--red);color:var(--red)}
.pill.s1{background:var(--orange-dim);border-color:var(--orange);color:var(--orange)}
.pill.s2{background:var(--yellow-dim);border-color:var(--yellow);color:var(--yellow)}
.pill.s3{background:var(--blue-dim);border-color:var(--blue);color:var(--blue)}
.pill.s4{background:var(--green-dim);border-color:var(--green);color:var(--green)}
.pill.sna{background:var(--surface3);border-color:var(--border2);color:var(--muted);font-size:8px}

/* ══ BAR ══ */
.bar{height:4px;background:var(--surface3);border-radius:100px;overflow:hidden}
.bar-f{height:100%;border-radius:100px;transition:width .6s cubic-bezier(.34,1.56,.64,1)}

/* ══ OBS ══ */
.obs{padding:12px 15px;border-radius:var(--r);margin-bottom:8px;border-left:3px solid;transition:transform .15s}
.obs:hover{transform:translateX(3px)}
.obs.good{background:rgba(34,197,94,0.05);border-color:var(--green)}
.obs.fair{background:rgba(245,158,11,0.05);border-color:var(--yellow)}
.obs.bad{background:rgba(239,68,68,0.05);border-color:var(--red)}
.obs-lbl{font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;margin-bottom:6px}
.obs.good .obs-lbl{color:var(--green)}
.obs.fair .obs-lbl{color:var(--yellow)}
.obs.bad .obs-lbl{color:var(--red)}
.obs-item{font-size:12px;padding:2px 0;line-height:1.5}

/* ══ QUOTE ══ */
.qblock{background:var(--surface2);border-left:3px solid var(--border2);padding:10px 14px;border-radius:0 var(--r) var(--r) 0;font-family:'DM Mono',monospace;font-size:11px;color:var(--muted);margin:8px 0;line-height:1.7}
.qsuggest{background:var(--orange-dim2);border-left:3px solid var(--orange);padding:10px 14px;border-radius:0 var(--r) var(--r) 0;font-size:12px;color:var(--orange2);margin:6px 0;line-height:1.6;font-style:italic}

/* ══ TABLE ══ */
table{width:100%;border-collapse:collapse;font-size:12px}
th{padding:8px 12px;text-align:left;font-size:10px;font-weight:700;letter-spacing:.07em;text-transform:uppercase;color:var(--muted);border-bottom:1px solid var(--border);background:var(--surface2)}
td{padding:9px 12px;border-bottom:1px solid var(--border);color:var(--muted)}
tr:last-child td{border-bottom:none}
tr:hover td{background:rgba(249,115,22,0.02)}
td.tdm{color:var(--text);font-weight:600}

/* ══ HIST ══ */
.hist-row{
  display:flex;align-items:center;gap:12px;padding:13px 16px;
  background:var(--surface);border:1px solid var(--border);
  border-radius:var(--r2);margin-bottom:8px;cursor:pointer;
  transition:all .18s;
}
.hist-row:hover{border-color:var(--orange);transform:translateX(4px);background:var(--surface2);box-shadow:0 4px 16px rgba(249,115,22,0.1)}
.hist-name{font-size:13px;font-weight:700;flex:1}
.hist-meta{font-size:11px;color:var(--muted);font-family:'DM Mono',monospace;margin-top:2px}

/* ══ CALLOUT ══ */
.callout{padding:12px 16px;border-radius:var(--r);font-size:12px;line-height:1.7;margin-bottom:14px;border:1px solid}
.c-orange{background:var(--orange-dim2);border-color:rgba(249,115,22,.2);color:var(--orange2)}
.c-green{background:rgba(34,197,94,.05);border-color:rgba(34,197,94,.2);color:var(--green)}
.c-blue{background:var(--blue-dim);border-color:rgba(59,130,246,.2);color:var(--blue)}

/* ══ RING ══ */
.ring-wrap{position:relative;width:96px;height:96px;flex-shrink:0}
.ring-wrap svg{width:96px;height:96px}
.ring-center{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}
.ring-n{font-size:28px;font-weight:800;line-height:1}
.ring-d{font-size:10px;color:var(--muted);font-family:'DM Mono',monospace}

/* ══ OVERLAY ══ */
.overlay{
  display:none;position:fixed;inset:0;
  background:rgba(6,9,15,0.94);backdrop-filter:blur(20px);
  z-index:200;flex-direction:column;align-items:center;justify-content:center;gap:20px;
}
.overlay.show{display:flex}
.ov-spinner{
  width:60px;height:60px;
  border:3px solid var(--surface3);
  border-top-color:var(--orange);
  border-right-color:rgba(249,115,22,0.4);
  border-radius:50%;animation:spin .8s linear infinite;
}
@keyframes spin{to{transform:rotate(360deg)}}
.ov-txt{font-size:17px;font-weight:700;color:var(--text)}
.ov-sub{font-size:12px;color:var(--muted);font-family:'DM Mono',monospace}
.ov-dots{display:flex;gap:6px;margin-top:6px}
.ov-dot{width:8px;height:8px;border-radius:50%;background:var(--orange);animation:dotB 1.2s ease-in-out infinite}
.ov-dot:nth-child(2){animation-delay:.15s;background:var(--orange2)}
.ov-dot:nth-child(3){animation-delay:.3s;background:var(--yellow)}
@keyframes dotB{0%,80%,100%{transform:scale(.5);opacity:.3}40%{transform:scale(1.3);opacity:1}}

/* ══ NOTIF ══ */
.notif{
  display:none;position:fixed;bottom:22px;right:22px;
  padding:11px 20px;background:var(--surface2);
  border:1px solid var(--border2);border-radius:var(--r);
  font-size:13px;font-weight:600;color:var(--text);z-index:300;
  animation:notifIn .22s cubic-bezier(.34,1.56,.64,1) both;
  backdrop-filter:blur(12px);
}
@keyframes notifIn{from{opacity:0;transform:translateY(10px) scale(.9)}to{opacity:1;transform:translateY(0) scale(1)}}
.notif.good{border-color:rgba(34,197,94,.4);color:var(--green)}
.notif.bad{border-color:rgba(239,68,68,.4);color:var(--red)}

/* ══ CONFETTI ══ */
.cp{position:fixed;top:-20px;pointer-events:none;z-index:400;animation:cf linear forwards;border-radius:2px}
@keyframes cf{0%{transform:translateY(0) rotate(0deg);opacity:1}100%{transform:translateY(100vh) rotate(720deg);opacity:0}}

/* ══ EMPTY ══ */
.empty{text-align:center;padding:60px 20px;color:var(--muted)}
.empty-ico{font-size:40px;margin-bottom:14px;display:block;animation:bob 2s ease-in-out infinite}
@keyframes bob{0%,100%{transform:translateY(0)}50%{transform:translateY(-10px)}}
.empty-t{font-size:15px;font-weight:700;color:var(--text);margin-bottom:5px}

hr{border:none;border-top:1px solid var(--border);margin:18px 0}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
.flex{display:flex}.ic{align-items:center}.jb{justify-content:space-between}
.gap6{gap:6px}.gap10{gap:10px}.gap14{gap:14px}
.mb6{margin-bottom:6px}.mb10{margin-bottom:10px}.mb14{margin-bottom:14px}.mb20{margin-bottom:20px}
.mt8{margin-top:8px}.mt12{margin-top:12px}
.tx-m{color:var(--muted)}.tx-s{font-size:12px}.tx-xs{font-size:11px}
.tx-mono{font-family:'DM Mono',monospace}.fw7{font-weight:700}
@keyframes pillPop{0%{transform:scale(1)}50%{transform:scale(1.3)}100%{transform:scale(1)}}
.pill-popping{animation:pillPop .18s ease}
@keyframes scoreAnim{from{transform:scale(1.4);opacity:0}to{transform:scale(1);opacity:1}}
.score-pop{animation:scoreAnim .5s cubic-bezier(.34,1.56,.64,1) both}

@media print{
  .bg-wrap,.sidebar,.header,.topbar,button,.btn,.overlay,.notif,.cp{display:none!important}
  .layout{display:block}body{background:#fff;color:#000}
  .screen{display:block!important}#screen-evaluate,#screen-manual,#screen-history,#screen-phrases{display:none!important}
}
</style>
</head>
<body>

<!-- BG -->
<div class="bg-wrap">
  <div class="bg-grid"></div>
  <div class="orb orb1"></div>
  <div class="orb orb2"></div>
  <div class="orb orb3"></div>
  <div class="particles" id="particles"></div>
</div>

<!-- HEADER -->
<header class="header">
  <div class="logo">
    <img class="logo-img" src="https://storagely-prod-public-assets.s3.us-east-2.amazonaws.com/logos/yourway-storage/logo_white492694011f99e16d.webp" alt="YourWay Storage" onerror="this.style.display='none';document.getElementById('logo-fallback').style.display='flex'">
    <div id="logo-fallback" style="display:none;align-items:center;gap:8px">
      <div style="width:36px;height:36px;border-radius:10px;background:linear-gradient(135deg,var(--orange),#ea580c);display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:800;color:#fff;box-shadow:0 0 20px rgba(249,115,22,0.4)">YW</div>
      <span style="font-size:15px;font-weight:800;color:var(--text)">YourWay <span style="color:var(--orange)">Storage</span></span>
    </div>
    <div class="logo-divider"></div>
    <div class="logo-tag">Call QA</div>
  </div>
  <div class="hdr-right">
    <div class="live-badge"><div class="live-dot"></div>live</div>
    <div class="co-badge">company use only</div>
  </div>
</header>

<div class="layout">

<!-- SIDEBAR -->
<nav class="sidebar">
  <div>
    <div class="sb-lbl">Evaluate</div>
    <div class="nav-item active" onclick="go('evaluate')"><div class="nav-ico">🎙️</div>AI Evaluation</div>
    <div class="nav-item" onclick="go('manual')"><div class="nav-ico">✏️</div>Manual Scoring</div>
  </div>
  <div>
    <div class="sb-lbl">Reports</div>
    <div class="nav-item" onclick="go('report')"><div class="nav-ico">📊</div>Last Report</div>
    <div class="nav-item" onclick="go('history')"><div class="nav-ico">🕐</div>History</div>
  </div>
  <div>
    <div class="sb-lbl">Admin</div>
    <div class="nav-item" onclick="go('phrases')"><div class="nav-ico">📌</div>Custom Phrases</div>
  </div>
  <div class="sb-foot">
    <div class="sb-foot-txt">YourWay Storage<br>Internal QA Tool · 2026</div>
  </div>
</nav>

<!-- MAIN -->
<div class="main">
  <div class="topbar">
    <div>
      <div class="page-title" id="ptitle">AI Evaluation</div>
      <div class="page-sub" id="psub">paste a transcript → instant score + coaching report</div>
    </div>
    <div class="topbar-btns" id="topbar-btns"></div>
  </div>
  <div class="content">

    <!-- ══ EVALUATE ══ -->
    <div class="screen active" id="screen-evaluate">
      <div class="callout c-orange mb20">
        📋 Paste your Otter.ai transcript below. AI will detect the call type, score every criterion, and write coaching notes directly to the agent.
      </div>
      <div class="card">
        <div class="form-row">
          <div><label>Agent Name</label><input type="text" id="e-agent" placeholder="e.g. Sarah Chen"></div>
          <div><label>Location</label>
            <select id="e-loc">
              <option value="">— select location —</option>
              <option value="walton">🏢 Walton Way — Augusta, GA</option>
              <option value="berkshire">🏢 Berkshire Drive — Columbia, SC</option>
              <option value="mckinley">🏢 McKinley Ave — Pocatello, ID</option>
            </select>
          </div>
        </div>
        <div class="form-row">
          <div><label>Call Date</label><input type="text" id="e-date" placeholder="2026-04-22"></div>
          <div><label>Call Type (optional)</label>
            <select id="e-type">
              <option value="">🤖 Auto-detect</option>
              <option value="New Rental Inquiry">New Rental Inquiry</option>
              <option value="Billing & Payments">Billing &amp; Payments</option>
              <option value="Move-Out / Cancellation">Move-Out / Cancellation</option>
              <option value="Complaint / Dispute">Complaint / Dispute</option>
              <option value="General Info / Lead Capture">General Info / Lead Capture</option>
              <option value="Lien / Delinquency">Lien / Delinquency</option>
              <option value="Move-In Processing">Move-In Processing</option>
            </select>
          </div>
        </div>
        <div class="form-group">
          <div class="flex jb ic mb6">
            <label style="margin:0">Transcript (from Otter.ai)</label>
            <div class="flex gap6">
              <button class="btn btn-sm btn-ghost" onclick="loadSample()">📋 sample</button>
              <button class="btn btn-sm btn-ghost" onclick="document.getElementById('e-transcript').value=''">🗑 clear</button>
            </div>
          </div>
          <textarea id="e-transcript" placeholder="[00:00] Agent: Thank you for calling YourWay Storage...&#10;[00:04] Caller: Hi, I need a storage unit..."></textarea>
        </div>
        <div class="flex ic gap10">
          <button class="btn-evaluate" onclick="runEval()">
            Evaluate Call <span class="arr">→</span>
          </button>
          <span class="tx-xs tx-m tx-mono">~15–30 sec · powered by OpenAI</span>
        </div>
      </div>
    </div>

    <!-- ══ MANUAL ══ -->
    <div class="screen" id="screen-manual">
      <div class="card mb14">
        <div class="form-row" style="margin:0">
          <div><label>Agent Name</label><input type="text" id="m-agent" placeholder="e.g. Mike Reyes"></div>
          <div><label>Call Type</label>
            <select id="m-type" onchange="buildManual()">
              <option value="">— select —</option>
              <option value="0">📞 New Rental Inquiry</option>
              <option value="1">💳 Billing &amp; Payments</option>
              <option value="2">📦 Move-Out / Cancellation</option>
              <option value="3">😤 Complaint / Dispute</option>
              <option value="4">📝 General Info / Lead Capture</option>
              <option value="5">⚠️ Lien / Delinquency</option>
              <option value="6">🔑 Move-In Processing</option>
            </select>
          </div>
        </div>
      </div>
      <div id="m-rubric">
        <div class="empty"><span class="empty-ico">🎯</span><div class="empty-t">Select a call type to score</div></div>
      </div>
      <div id="m-foot" style="display:none">
        <hr>
        <div class="flex ic jb">
          <div>
            <div class="tx-xs tx-m mb6">calculated score</div>
            <div style="font-size:42px;font-weight:800;color:var(--orange)" id="m-score-out">—</div>
          </div>
          <div class="flex gap10">
            <button class="btn btn-ghost" onclick="resetManual()">🔄 reset</button>
            <button class="btn btn-primary" onclick="saveManual()">💾 save report</button>
          </div>
        </div>
      </div>
    </div>

    <!-- ══ REPORT ══ -->
    <div class="screen" id="screen-report">
      <div id="report-out">
        <div class="empty"><span class="empty-ico">🏆</span><div class="empty-t">No report yet</div><div class="tx-s tx-m">run an evaluation to see results here</div></div>
      </div>
    </div>

    <!-- ══ HISTORY ══ -->
    <div class="screen" id="screen-history"><div id="hist-out"></div></div>

    <!-- ══ PHRASES ══ -->
    <div class="screen" id="screen-phrases">
      <div class="card mb14">
        <div class="card-title">📌 Custom Must-Say Phrases</div>
        <div class="card-sub">AI checks for these on every evaluation and flags if missed.</div>
        <div id="phrases-out" class="mb14"></div>
        <div class="flex gap10">
          <input type="text" id="s-phrase" placeholder='e.g. "No contracts, month-to-month"' style="flex:1">
          <button class="btn btn-primary" onclick="addPhrase()">Add</button>
        </div>
      </div>
      <div class="card">
        <div class="card-title">ℹ️ About</div>
        <div class="tx-s tx-m tx-mono" style="line-height:2.2">
          YourWay Storage Call Evaluator · v3.0<br>
          Powered by OpenAI GPT-4o-mini<br>
          7 call types · 0–4 per criterion · 1–100 score<br>
          For company use only · YourWay Storage 2026
        </div>
      </div>
    </div>

  </div>
</div>
</div>

<!-- OVERLAY -->
<div class="overlay" id="overlay">
  <div class="ov-spinner"></div>
  <div class="ov-txt" id="ov-txt">Evaluating call…</div>
  <div class="ov-sub" id="ov-sub">reading transcript</div>
  <div class="ov-dots"><div class="ov-dot"></div><div class="ov-dot"></div><div class="ov-dot"></div></div>
</div>
<div class="notif" id="notif"></div>

<script>
// ══════════════════════════════════════════
// RUBRICS
// ══════════════════════════════════════════
const RUBRICS=[
{name:'New Rental Inquiry',canReview:true,canMoveIn:true,sections:[
  {id:'s01',name:'Opening & Name Capture',weight:10,criteria:['Asked for customer\'s name at the very start of the call','Used the customer\'s name throughout the conversation','Greeted warmly with full name and "YourWay Storage"']},
  {id:'s02',name:'Needs Discovery',weight:15,criteria:['Asked why they need storage (moving, downsizing, remodel, business, etc.)','Asked what they need to store (furniture, boxes, vehicle, business inventory)','Asked when they need the unit (move-in timeline / urgency)']},
  {id:'s03',name:'Unit Size Recommendation',weight:10,criteria:['Recommended the right unit size based on items described — OR — accepted customer\'s stated size without pushing if they already knew what they wanted','Gave dimensions AND a real-world comparison (e.g. "fits a 1-bedroom apartment")','Explained the right unit type for the location (climate, smart, drive-up)']},
  {id:'s04',name:'Protection Plan',weight:15,criteria:['Offered the protection plan proactively — did not wait to be asked','Started with the $17/mo ($3,500 coverage) tier as the default offer','Explained zero deductible and coverage benefits clearly','Only stepped down to $13/mo ($2,500) if tenant objected that items aren\'t worth that much — never opened with the lowest tier','Held firm through at least one objection before considering own-insurance — never offered own insurance casually or as a first alternative','Own insurance mentioned only after multiple objections as absolute last resort']},
  {id:'s05',name:'Pricing, Promo & Admin Fee',weight:15,criteria:['Explained the promotional rate clearly (50% off first month, ends April 30)','Explained the standard rate (what they pay after promo ends)','Clearly communicated the admin fee','Move-in cost was clearly explained (promo rate + admin fee + PP if applicable)']},
  {id:'s06',name:'Facility Features & Access',weight:10,criteria:['Mentioned access hours and office hours','Highlighted facility features relevant to the customer','Walton: highlighted fully climate-controlled + Nokē smart facility access','Berkshire: highlighted fully smart units + drive-up + climate-controlled','McKinley: clarified mix of regular and smart units, smart = climate-controlled, 24-hr access area']},
  {id:'s07',name:'Objection Handling & Close',weight:15,criteria:['If customer was shopping around — pushed for reservation and explained price/promo not guaranteed next time','Explained reservation requires no credit card and takes 3 minutes','Asked to book or reserve on the call','Confirmed next step before ending the call']},
  {id:'s08',name:'Phone & Email Capture',weight:10,criteria:['Verified/captured phone number — early in call','Captured email address — acceptable if collected toward latter part of call','Info collected naturally without being robotic']},
]},
{name:'Billing & Payments',canReview:true,canMoveIn:false,sections:[
  {id:'s01',name:'Greeting & Verification',weight:20,criteria:['Asked for customer\'s name at the start','Verified customer identity before accessing account','Used customer name throughout']},
  {id:'s02',name:'Empathy',weight:20,criteria:['Acknowledged customer frustration without defensiveness','Did not interrupt while customer explained','Maintained calm, warm tone even if customer was upset']},
  {id:'s03',name:'Policy Knowledge',weight:25,criteria:['Explained billing policy accurately','Stated late fee policy correctly','Did not make promises that contradict policy','Explained rate increase process correctly if applicable']},
  {id:'s04',name:'Resolution',weight:25,criteria:['Resolved the issue or escalated appropriately','Confirmed action being taken','Gave clear timeline for any follow-up']},
  {id:'s05',name:'Wrap-Up',weight:10,criteria:['Summarized outcome before ending','Asked if anything else needed','Ended professionally']},
]},
{name:'Move-Out / Cancellation',canReview:true,canMoveIn:false,sections:[
  {id:'s01',name:'Greeting & Empathy',weight:15,criteria:['Asked for name at start, used it throughout','Acknowledged move-out without making customer feel guilty']},
  {id:'s02',name:'Reason Discovery',weight:20,criteria:['Asked why the customer is moving out','Listened without interrupting','Identified if reason is fixable']},
  {id:'s03',name:'Retention Attempt',weight:25,criteria:['Made a genuine retention attempt','Offered relevant solution','Did not pressure or guilt the customer','Respected decision if customer was firm']},
  {id:'s04',name:'Move-Out Procedure',weight:30,criteria:['Explained move-out process clearly','Confirmed move-out date','Explained unit must be emptied and lock left open','Confirmed final bill process']},
  {id:'s05',name:'Goodwill Close',weight:10,criteria:['Thanked customer for their business','Left door open for future rentals','Ended warmly']},
]},
{name:'Complaint / Dispute',canReview:false,canMoveIn:false,sections:[
  {id:'s01',name:'Greeting & Listening',weight:20,criteria:['Asked for name and used it','Let customer fully explain without interrupting','Did not get defensive']},
  {id:'s02',name:'Empathy',weight:25,criteria:['Validated frustration explicitly','Apologized appropriately','Maintained calm, caring tone throughout']},
  {id:'s03',name:'Fact-Finding',weight:25,criteria:['Asked clarifying questions','Did not make assumptions','Confirmed details back to customer']},
  {id:'s04',name:'Resolution / Escalation',weight:20,criteria:['Offered solution or clear escalation path','Explained what happens next and by when','Did not make unauthorized promises']},
  {id:'s05',name:'Close',weight:10,criteria:['Confirmed next steps before ending','Ended professionally']},
]},
{name:'General Info / Lead Capture',canReview:true,canMoveIn:false,sections:[
  {id:'s01',name:'Opening & Name Capture',weight:15,criteria:['Asked for customer\'s name right away','Used it throughout the call','Greeted with name and YourWay Storage']},
  {id:'s02',name:'Info Sharing',weight:20,criteria:['Answered questions accurately','Proactively mentioned 50% off promo and deadline','Mentioned key differentiators (no contracts, smart access, climate control)']},
  {id:'s03',name:'Soft Discovery',weight:20,criteria:['Asked what they need to store and why','Asked about their timeline','Asked which location is nearest']},
  {id:'s04',name:'Phone & Email Capture',weight:20,criteria:['Captured phone number early in the call','Captured email toward end of call naturally']},
  {id:'s05',name:'Lead Push & Close',weight:25,criteria:['Pushed for reservation if customer was shopping around','Explained price/promo not guaranteed next time','Offered to hold unit with no credit card needed','Set clear next step before ending the call']},
]},
{name:'Lien / Delinquency',canReview:false,canMoveIn:false,sections:[
  {id:'s01',name:'Greeting & Verification',weight:15,criteria:['Asked for name, verified identity','Professional tone from the first word']},
  {id:'s02',name:'Compliance & Disclosures',weight:35,criteria:['Stated lien/delinquency policy accurately','No unauthorized promises about waiving fees','All required disclosures communicated','No threatening or inappropriate language']},
  {id:'s03',name:'Empathy',weight:20,criteria:['Acknowledged situation with compassion','Did not lecture or shame','Stayed calm under stress']},
  {id:'s04',name:'Resolution Path',weight:20,criteria:['Explained options clearly','Gave specific payment deadlines','Confirmed next steps']},
  {id:'s05',name:'Close',weight:10,criteria:['Summarized outcome clearly','Ended professionally']},
]},
{name:'Move-In Processing',canReview:true,canMoveIn:false,sections:[
  {id:'s01',name:'Greeting & Confirmation',weight:15,criteria:['Asked for name, confirmed reservation and unit','Used customer name throughout']},
  {id:'s02',name:'Agreement Walk-Through',weight:25,criteria:['Walked through rental agreement key points','Confirmed billing date and amount','Explained access hours and how to enter','Explained Nokē smart access','Confirmed month-to-month terms']},
  {id:'s03',name:'Move-In Data Capture',weight:30,criteria:['Captured DL state','Captured DL number','Captured date of birth','Captured alternate contact first + last name','Captured alternate contact phone number']},
  {id:'s04',name:'Protection Plan & Payment',weight:20,criteria:['Offered protection plan proactively with zero deductible benefit explained','Started with $17/mo ($3,500) as the default — not the lowest tier','Only stepped down to $13/mo ($2,500) if tenant objected that items aren\'t worth more','Own insurance raised only after multiple objections as absolute last resort — never as a casual alternative','Confirmed payment method on file','Confirmed first payment processed']},
  {id:'s05',name:'Close',weight:10,criteria:['Confirmed move-in date and access','Asked if any final questions','Ended warmly and professionally']},
]},
];

const LOC_INFO={
  walton:'Walton Way Ext, Augusta GA — Fully climate-controlled · Nokē smart facility access · Interior units',
  berkshire:'Berkshire Drive, Columbia SC — All smart units · Drive-up access · Climate-controlled',
  mckinley:'McKinley Avenue, Pocatello ID — Mix of regular and smart units · Smart units = climate-controlled · 24-hr access area available',
};

// ══════════════════════════════════════════
// STATE
// ══════════════════════════════════════════
let mScores={},mType=null,lastReport=null;
let history=JSON.parse(localStorage.getItem('yw_hist')||'[]');
let phrases=JSON.parse(localStorage.getItem('yw_phrases')||'[]');

// ══════════════════════════════════════════
// PARTICLES
// ══════════════════════════════════════════
function initParticles(){
  const wrap=document.getElementById('particles');
  for(let i=0;i<18;i++){
    const p=document.createElement('div');
    p.className='p';
    p.style.left=Math.random()*100+'vw';
    p.style.width=p.style.height=(Math.random()*3+1)+'px';
    p.style.animationDuration=(Math.random()*20+15)+'s';
    p.style.animationDelay=Math.random()*20+'s';
    p.style.opacity=Math.random()*0.4+0.1;
    wrap.appendChild(p);
  }
}
initParticles();

// ══════════════════════════════════════════
// NAV
// ══════════════════════════════════════════
const PAGE_META={
  evaluate:['AI Evaluation','paste a transcript → instant score + coaching report'],
  manual:['Manual Scoring','click 0–4 per criterion, score calculates live'],
  report:['Last Report','most recent evaluation scorecard'],
  history:['History','all saved evaluations'],
  phrases:['Custom Phrases','must-say phrases AI checks on every call'],
};
function go(name){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  document.getElementById('screen-'+name).classList.add('active');
  document.querySelectorAll('.nav-item').forEach(n=>{
    if(n.getAttribute('onclick')?.includes("'"+name+"'")) n.classList.add('active');
  });
  const m=PAGE_META[name]||[name,''];
  document.getElementById('ptitle').textContent=m[0];
  document.getElementById('psub').textContent=m[1];
  const tbb=document.getElementById('topbar-btns');tbb.innerHTML='';
  if(name==='report'&&lastReport){
    const b=document.createElement('button');b.className='btn btn-sm';b.innerHTML='🖨 PDF';b.onclick=()=>window.print();
    const b2=document.createElement('button');b2.className='btn btn-sm btn-ghost';b2.innerHTML='📋 Copy';b2.onclick=copyReport;
    tbb.append(b,b2);
  }
  if(name==='history') renderHistory();
  if(name==='phrases') renderPhrases();
}

// ══════════════════════════════════════════
// AI EVAL — OPENAI
// ══════════════════════════════════════════
async function runEval(){
  const agent=document.getElementById('e-agent').value.trim()||'Unknown Agent';
  const loc=document.getElementById('e-loc').value;
  const date=document.getElementById('e-date').value.trim()||new Date().toISOString().split('T')[0];
  const typeHint=document.getElementById('e-type').value;
  const tx=document.getElementById('e-transcript').value.trim();
  if(!tx){showNotif('📋 Paste a transcript first','bad');return;}

  showOv('Reading transcript…','classifying call type');
  const msgs=[
    ['Classifying call type…','matching to one of 7 rubrics'],
    ['Scoring each criterion…','going through all sections'],
    ['Checking protection plan…','offer, pricing, firmness'],
    ['Checking promo & pricing…','admin fee, promo, post-promo rate'],
    ['Checking facility features…','access hours, unit types, smart access'],
    ['Writing coaching notes…','drafting observations & suggestions'],
  ];
  let mi=0;
  const iv=setInterval(()=>{mi=(mi+1)%msgs.length;document.getElementById('ov-txt').textContent=msgs[mi][0];document.getElementById('ov-sub').textContent=msgs[mi][1];},3000);

  const locNote=loc?`\n\nLOCATION: ${LOC_INFO[loc]}`:'';
  const phraseNote=phrases.length?`\n\nCUSTOM MUST-SAY PHRASES:\n${phrases.map((p,i)=>`${i+1}. "${p}"`).join('\n')}`:'';
  const typeNote=typeHint?`\n\nCALL TYPE HINT: ${typeHint}`:'';

  const sys=`You are a strict but fair call quality evaluator for YourWay Storage. Write coaching directly to the agent.

YOURWAY FACTS:
Locations:
• Walton Way Ext, Augusta GA — fully climate-controlled, Nokē smart facility access
• Berkshire Drive, Columbia SC — all smart units, drive-up access, climate-controlled
• McKinley Avenue, Pocatello ID — mix of regular + smart units; smart = climate-controlled; 24-hr access area

Promo rates (50% off first month, ends April 30):
5x5: $20/mo | 5x10: $28/mo | 10x10: $60-73/mo | 10x15: $89-105/mo | 10x20: $132/mo | 10x30: $195/mo

Protection Plans (ZERO deductible — agent must offer firmly):
• $13/mo = $2,500 coverage
• $17/mo = $3,500 coverage
• $25/mo = $5,000 coverage
Own insurance = last resort only.

Access hours: 6am–10pm daily | Office: Mon-Sat 9am–8pm, Sun 9am–5pm
No contracts, month-to-month | Online reservation: no credit card, 3 min

SCORING: 0=missed | 1=poor attempt | 2=fair/partial | 3=good | 4=excellent | null=N/A

CALL TYPES: 1.New Rental Inquiry 2.Billing&Payments 3.Move-Out/Cancellation 4.Complaint/Dispute(NO review) 5.General Info/Lead Capture 6.Lien/Delinquency(NO review) 7.Move-In Processing

§06 Review: positive calls only, weight 10%
§07 Move-In Compliance: Rubric 1 only when rented on call, weight 15%

MATH: avg section scores → pct=(avg/4)*100 → weighted=pct*weight% → sum all = final (min 1)

PP STANDARD:
• Agent MUST open with $17/mo ($3,500) as default — never start with lowest tier
• Step down to $13/mo only if tenant says items aren't worth that much
• Own insurance: ONLY after MULTIPLE objections, absolute last resort. Offering it casually = score 0.
• Scoring: 4=opened $17 held firm stepped down correctly. 3=opened $17 reasonable. 2=wrong tier OR caved fast. 1=barely tried. 0=skipped PP or opened with own insurance.

PROMO: Must explain promo rate + deadline + post-promo rate. Missing any = docked.
ADMIN FEE: Must be explicitly mentioned.
NAME: Ask early, use throughout.
PHONE: Capture early. EMAIL: Can be later.
SHOPPING: Must push reservation + explain prices change.
SIZE: If customer knows size, give credit for accepting it.

PII: Never include full DL, DOB, SSN, financial data.
VOICE: Write to agent directly (you/your). Warm, direct, specific. No fluff.${locNote}${phraseNote}${typeNote}

Respond ONLY with valid JSON, no markdown fences:
{"call_type":"string","call_type_num":1,"location_used":"walton|berkshire|mckinley|unknown","classification_confidence":"high|medium|low","overall_score":85,"grade":"A","grade_label":"string","section_scores":[{"id":"s01","name":"string","weight":10,"avg_score":3.5,"pct":87.5,"weighted":8.75,"criteria_scores":[{"text":"string","score":4,"note":"string"}]}],"review_applied":false,"movein_applied":false,"review_section":null,"movein_section":null,"did_well":["string"],"fairly_well":["string"],"needs_work":["string"],"pp_note":"string","promo_note":"string","key_quote_good":"string","key_quote_improve":"string","better_phrase":"string","summary":"string","custom_phrases_check":[{"phrase":"string","found":true,"note":"string"}],"qa_contact_captured":"all|partial|none","qa_pp_offered":"yes-firm|yes-weak|no","qa_promo_explained":"full|partial|no","qa_closed":"booked|reserved|follow-up|no-close"}`;

  try{
    const res=await fetch('/.netlify/functions/evaluate',{
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body:JSON.stringify({transcript:`${sys}\n\nAgent: ${agent}\nDate: ${date}\n\nTRANSCRIPT:\n${tx}`})
    });
    clearInterval(iv);
    if(!res.ok){
      const e=await res.json();
      hideOv();
      showNotif('❌ Error: '+(e.error||res.status),'bad');
      console.error(e);return;
    }
    const d=await res.json();
    const raw=(d.text||d.content||'').replace(/```json|```/g,'').trim();
    let r;
    try{r=JSON.parse(raw);}
    catch(pe){hideOv();showNotif('❌ Parse error — try again','bad');console.error('Raw:',raw);return;}
    r.agent=agent;r.date=date;r.loc=loc;r.id=Date.now();
    lastReport=r;
    history.unshift(r);if(history.length>50)history=history.slice(0,50);
    localStorage.setItem('yw_hist',JSON.stringify(history));
    hideOv();renderReport(r);go('report');
    if(r.overall_score>=80) launchConfetti();
    showNotif((r.overall_score>=80?'🎉 ':'📊 ')+'Done — '+r.overall_score+'/100 ('+r.grade+')',r.overall_score>=80?'good':'');
  }catch(e){clearInterval(iv);hideOv();showNotif('❌ '+e.message,'bad');console.error(e);}
}

// ══════════════════════════════════════════
// REPORT
// ══════════════════════════════════════════
function barC(p){return p>=80?'#22c55e':p>=60?'#f97316':p>=40?'#f59e0b':'#ef4444'}
function gradeC(g){return{A:'#22c55e',B:'#86efac',C:'#f59e0b',D:'#f97316',F:'#ef4444'}[g]||'var(--text)'}

function renderReport(r){
  const allSecs=[...r.section_scores];
  if(r.review_applied&&r.review_section) allSecs.push(r.review_section);
  if(r.movein_applied&&r.movein_section) allSecs.push(r.movein_section);
  const locLabel={walton:'Walton Way · Augusta GA',berkshire:'Berkshire · Columbia SC',mckinley:'McKinley · Pocatello ID'}[r.loc||r.location_used]||r.location_used||'—';

  const secHTML=allSecs.map(s=>{
    const p=Math.round(s.pct||0);
    return `<div class="rub-section">
      <div class="rub-head" onclick="toggleRub(this)">
        <div class="rub-name">${s.name} <span class="tx-xs tx-m">(${s.weight}%)</span></div>
        <div class="rub-meta">
          <div class="bar" style="width:80px"><div class="bar-f" style="width:${p}%;background:${barC(p)}"></div></div>
          <span style="font-size:13px;font-weight:700;color:${barC(p)};min-width:38px;text-align:right">${p}%</span>
        </div>
      </div>
      <div class="rub-body">
        ${(s.criteria_scores||[]).map(c=>{
          const sc=c.score,na=sc===null||sc===undefined;
          const bc=na?'b-gray':sc>=3?'b-green':sc>=2?'b-yellow':sc>=1?'b-orange':'b-red';
          const pill=`<span class="badge ${bc}">${na?'N/A':sc+'/4'}</span>`;
          return `<div class="crit-row">
            <div>
              <div class="crit-text">${c.text}</div>
              ${c.note?`<div class="tx-xs tx-m mt8" style="font-style:italic;font-family:'DM Mono',monospace">${c.note}</div>`:''}
            </div>
            <div>${pill}</div>
          </div>`;
        }).join('')}
      </div>
    </div>`;
  }).join('');

  const obsHTML=(items,cls,lbl,ico)=>items&&items.length?`<div class="obs ${cls}"><div class="obs-lbl">${ico} ${lbl}</div>${items.map(i=>`<div class="obs-item">→ ${i}</div>`).join('')}</div>`:'';

  const ppB=r.qa_pp_offered==='yes-firm'?'b-green':r.qa_pp_offered==='yes-weak'?'b-yellow':'b-red';
  const promoB=r.qa_promo_explained==='full'?'b-green':r.qa_promo_explained==='partial'?'b-yellow':'b-red';
  const contB=r.qa_contact_captured==='all'?'b-green':r.qa_contact_captured==='partial'?'b-yellow':'b-red';
  const closeB=(r.qa_closed==='booked'||r.qa_closed==='reserved')?'b-green':r.qa_closed==='follow-up'?'b-yellow':'b-red';

  const circ=251.2;
  const offset=(circ-(r.overall_score/100)*circ).toFixed(1);
  const gc=gradeC(r.grade);

  const customHTML=r.custom_phrases_check&&r.custom_phrases_check.length?`
    <div class="card mb14">
      <div class="card-title mb10">📌 Custom Phrase Check</div>
      ${r.custom_phrases_check.map(p=>`
        <div class="flex ic gap10" style="padding:8px 0;border-bottom:1px solid var(--border)">
          <span class="badge ${p.found?'b-green':'b-red'}">${p.found?'✓ found':'✗ missed'}</span>
          <span class="tx-s" style="flex:1">"${p.phrase}"</span>
          <span class="tx-xs tx-m tx-mono">${p.note||''}</span>
        </div>`).join('')}
    </div>`:'';

  document.getElementById('report-out').innerHTML=`
    <div class="flex ic jb mb20">
      <div>
        <div style="font-size:20px;font-weight:800">${r.agent}</div>
        <div class="tx-s tx-m tx-mono">${r.date} · ${r.call_type} · ${locLabel}</div>
      </div>
      <span class="badge b-gray">${r.classification_confidence} confidence</span>
    </div>

    <div style="display:flex;align-items:center;gap:22px;margin-bottom:18px;background:var(--surface);border:1px solid var(--border);border-radius:var(--r2);padding:20px">
      <div class="ring-wrap">
        <svg viewBox="0 0 100 100">
          <circle cx="50" cy="50" r="40" fill="none" stroke="var(--surface3)" stroke-width="8"/>
          <circle cx="50" cy="50" r="40" fill="none" stroke="${gc}" stroke-width="8"
            stroke-linecap="round" stroke-dasharray="${circ}" stroke-dashoffset="${offset}"
            transform="rotate(-90 50 50)" style="transition:stroke-dashoffset .8s cubic-bezier(.34,1.56,.64,1)"/>
        </svg>
        <div class="ring-center">
          <span class="ring-n score-pop" style="color:${gc}">${r.overall_score}</span>
          <span class="ring-d">/100</span>
        </div>
      </div>
      <div>
        <div style="font-size:40px;font-weight:800;color:${gc};line-height:1">${r.grade}</div>
        <div style="font-size:15px;font-weight:600;margin-top:5px">${r.grade_label}</div>
        ${r.review_applied?'<div class="badge b-green" style="margin-top:8px">⭐ Review Request scored</div>':''}
      </div>
    </div>

    <div class="g4 mb14">
      <div class="stat"><div class="badge ${ppB}" style="margin-bottom:5px">${r.qa_pp_offered||'—'}</div><div class="stat-l">PP Offer</div></div>
      <div class="stat"><div class="badge ${promoB}" style="margin-bottom:5px">${r.qa_promo_explained||'—'}</div><div class="stat-l">Promo Explained</div></div>
      <div class="stat"><div class="badge ${contB}" style="margin-bottom:5px">${r.qa_contact_captured||'—'}</div><div class="stat-l">Contact Captured</div></div>
      <div class="stat"><div class="badge ${closeB}" style="margin-bottom:5px">${r.qa_closed||'—'}</div><div class="stat-l">Close Result</div></div>
    </div>

    <div class="card mb14">
      <div class="card-title mb10">💬 Coaching Summary</div>
      <p class="tx-s" style="line-height:1.9;color:var(--text)">${r.summary}</p>
      ${r.pp_note?`<hr><div class="tx-xs tx-m mb6" style="font-weight:700;text-transform:uppercase;letter-spacing:.07em">🛡 Protection Plan</div><p class="tx-s">${r.pp_note}</p>`:''}
      ${r.promo_note?`<hr><div class="tx-xs tx-m mb6" style="font-weight:700;text-transform:uppercase;letter-spacing:.07em">🏷 Promo & Pricing</div><p class="tx-s">${r.promo_note}</p>`:''}
    </div>

    <div class="card mb14">
      <div class="card-title mb10">🔍 Observations</div>
      ${obsHTML(r.did_well,'good','Did Well (3–4)','🟢')}
      ${obsHTML(r.fairly_well,'fair','Fairly Well (2)','🟡')}
      ${obsHTML(r.needs_work,'bad','Needs Work (0–1)','🔴')}
      ${r.key_quote_good?`<div class="tx-xs tx-m mt12 mb6" style="font-weight:700">✨ Moment that worked:</div><div class="qblock">"${r.key_quote_good}"</div>`:''}
      ${r.key_quote_improve?`<div class="tx-xs tx-m mb6 mt12" style="font-weight:700">⚡ Moment to improve:</div><div class="qblock">"${r.key_quote_improve}"</div>${r.better_phrase?`<div class="tx-xs tx-m mb6">💡 Try instead:</div><div class="qsuggest">"${r.better_phrase}"</div>`:''}`:''}
    </div>

    <div class="card mb14">
      <div class="card-title mb10">📋 Section Breakdown</div>
      ${secHTML}
    </div>

    ${customHTML}

    <div class="card">
      <div class="card-title mb10">📌 QA Tracking</div>
      <table>
        <tr><th>Field</th><th>Value</th></tr>
        <tr><td class="tdm">Agent</td><td>${r.agent}</td></tr>
        <tr><td class="tdm">Date</td><td>${r.date}</td></tr>
        <tr><td class="tdm">Location</td><td>${locLabel}</td></tr>
        <tr><td class="tdm">Call Type</td><td>${r.call_type}</td></tr>
        <tr><td class="tdm">Score</td><td>${r.overall_score}/100 (${r.grade}) — ${r.grade_label}</td></tr>
        <tr><td class="tdm">PP Offer</td><td>${r.qa_pp_offered||'—'}</td></tr>
        <tr><td class="tdm">Promo Explained</td><td>${r.qa_promo_explained||'—'}</td></tr>
        <tr><td class="tdm">Contact Captured</td><td>${r.qa_contact_captured||'—'}</td></tr>
        <tr><td class="tdm">Close Result</td><td>${r.qa_closed||'—'}</td></tr>
        <tr><td class="tdm">Review Request</td><td>${r.review_applied?'Yes':'No'}</td></tr>
        <tr><td class="tdm">Move-In Compliance</td><td>${r.movein_applied?'Yes':'No'}</td></tr>
      </table>
    </div>`;
}

function toggleRub(h){h.classList.toggle('open');h.nextElementSibling.classList.toggle('open')}

// ══════════════════════════════════════════
// MANUAL SCORING
// ══════════════════════════════════════════
function buildManual(){
  const idx=parseInt(document.getElementById('m-type').value);
  if(isNaN(idx))return;
  mType=idx;mScores={};
  const rub=RUBRICS[idx];
  let html='';
  rub.sections.forEach(s=>{
    html+=`<div class="rub-section">
      <div class="rub-head open" onclick="toggleRub(this)">
        <div class="rub-name">${s.name} <span class="tx-xs tx-m">(${s.weight}%)</span></div>
        <div class="rub-meta"><span class="tx-xs tx-mono" id="ms-${s.id}">—</span></div>
      </div>
      <div class="rub-body open">
        ${s.criteria.map((c,ci)=>`<div class="crit-row">
          <div class="crit-text">${c}</div>
          <div class="crit-pills">
            ${[0,1,2,3,4].map(n=>`<button class="pill" data-s="${s.id}" data-i="${ci}" data-v="${n}" onclick="setPill(this)">${n}</button>`).join('')}
            <button class="pill" data-s="${s.id}" data-i="${ci}" data-v="na" onclick="setPill(this)" style="font-size:8px">N/A</button>
          </div>
        </div>`).join('')}
      </div>
    </div>`;
  });
  document.getElementById('m-rubric').innerHTML=html;
  document.getElementById('m-foot').style.display='block';
  calcManual();
}

function setPill(b){
  const s=b.dataset.s,i=b.dataset.i,v=b.dataset.v;
  document.querySelectorAll(`[data-s="${s}"][data-i="${i}"]`).forEach(x=>{x.className='pill';});
  mScores[s+'_'+i]=v==='na'?'na':parseInt(v);
  b.classList.add(v==='na'?'sna':'s'+v);
  b.classList.add('pill-popping');setTimeout(()=>b.classList.remove('pill-popping'),200);
  calcManual();
}

function calcManual(){
  if(mType===null)return;
  const rub=RUBRICS[mType];let total=0;
  rub.sections.forEach(s=>{
    const scored=[];
    s.criteria.forEach((_,ci)=>{const k=s.id+'_'+ci;const v=mScores[k];if(v!=='na'&&v!==undefined)scored.push(v);});
    const avg=scored.length?scored.reduce((a,b)=>a+b,0)/scored.length:0;
    const pct=(avg/4)*100;total+=pct*(s.weight/100);
    const el=document.getElementById('ms-'+s.id);
    if(el)el.textContent=scored.length?Math.round(pct)+'%':'—';
  });
  document.getElementById('m-score-out').textContent=Math.max(1,Math.round(total))+'/100';
}

function resetManual(){
  mScores={};
  document.querySelectorAll('.pill').forEach(p=>p.className='pill');
  document.getElementById('m-score-out').textContent='—';
  document.querySelectorAll('[id^="ms-"]').forEach(e=>e.textContent='—');
}

function saveManual(){
  const agent=document.getElementById('m-agent').value.trim()||'Unknown Agent';
  const txt=document.getElementById('m-score-out').textContent;
  const score=parseInt(txt);
  if(isNaN(score)){showNotif('Score some criteria first','bad');return;}
  const grade=score>=90?'A':score>=80?'B':score>=65?'C':score>=50?'D':'F';
  const r={id:Date.now(),agent,date:new Date().toISOString().split('T')[0],
    call_type:RUBRICS[mType].name,call_type_num:mType+1,
    overall_score:score,grade,
    grade_label:score>=90?'Outstanding':score>=80?'Good':score>=65?'Fair':score>=50?'Poor':'Needs Coaching',
    summary:`Manual evaluation. ${agent} scored ${score}/100 (Grade ${grade}).`,
    did_well:[],fairly_well:[],needs_work:[],section_scores:[],
    review_applied:false,movein_applied:false,review_section:null,movein_section:null,
    custom_phrases_check:[],classification_confidence:'manual',
    qa_pp_offered:'—',qa_promo_explained:'—',qa_contact_captured:'—',qa_closed:'—',
    loc:'',pp_note:'',promo_note:'',key_quote_good:'',key_quote_improve:'',better_phrase:''
  };
  lastReport=r;history.unshift(r);if(history.length>50)history=history.slice(0,50);
  localStorage.setItem('yw_hist',JSON.stringify(history));
  renderReport(r);go('report');
  if(score>=80)launchConfetti();
  showNotif((score>=80?'🎉 ':'💾 ')+'Saved — '+score+'/100',score>=80?'good':'');
}

// ══════════════════════════════════════════
// HISTORY
// ══════════════════════════════════════════
function renderHistory(){
  const el=document.getElementById('hist-out');
  if(!history.length){el.innerHTML='<div class="empty"><span class="empty-ico">📂</span><div class="empty-t">No evaluations yet</div></div>';return;}
  const gc={A:'b-green',B:'b-green',C:'b-yellow',D:'b-orange',F:'b-red'};
  el.innerHTML=`<div class="flex ic jb mb14">
    <span class="tx-s tx-m">${history.length} evaluation${history.length!==1?'s':''}</span>
    <button class="btn btn-sm btn-danger" onclick="clearHist()">🗑 clear all</button>
  </div>`+history.map(r=>`
    <div class="hist-row" onclick="viewHist(${r.id})">
      <div style="flex:1">
        <div class="hist-name">${r.agent}</div>
        <div class="hist-meta">${r.date} · ${r.call_type}</div>
      </div>
      <span class="badge ${gc[r.grade]||'b-gray'}">${r.overall_score}/100</span>
      <span class="badge b-gray">${r.grade}</span>
      ${r.classification_confidence==='manual'?'<span class="badge b-gray" style="font-size:10px">manual</span>':''}
    </div>`).join('');
}
function viewHist(id){const r=history.find(h=>h.id===id);if(!r)return;lastReport=r;renderReport(r);go('report');}
function clearHist(){if(!confirm('Clear all history?'))return;history=[];localStorage.setItem('yw_hist','[]');renderHistory();}

// ══════════════════════════════════════════
// PHRASES
// ══════════════════════════════════════════
function renderPhrases(){
  const el=document.getElementById('phrases-out');
  if(!phrases.length){el.innerHTML='<div class="tx-xs tx-m mb10 tx-mono">No custom phrases yet.</div>';return;}
  el.innerHTML=phrases.map((p,i)=>`
    <div class="flex ic gap10 mb6">
      <span class="badge b-orange" style="flex:1;justify-content:flex-start;padding:6px 12px">${p}</span>
      <button class="btn btn-sm btn-ghost" onclick="removePhrase(${i})">remove</button>
    </div>`).join('');
}
function addPhrase(){const inp=document.getElementById('s-phrase');const v=inp.value.trim();if(!v)return;phrases.push(v);localStorage.setItem('yw_phrases',JSON.stringify(phrases));inp.value='';renderPhrases();showNotif('📌 Phrase added','good');}
function removePhrase(i){phrases.splice(i,1);localStorage.setItem('yw_phrases',JSON.stringify(phrases));renderPhrases();}

// ══════════════════════════════════════════
// CONFETTI
// ══════════════════════════════════════════
function launchConfetti(){
  const cols=['#f97316','#fb923c','#fed7aa','#ffffff','#fbbf24','#fdba74','#f97316','#ea580c'];
  for(let i=0;i<65;i++){
    const el=document.createElement('div');
    el.className='cp';
    el.style.left=Math.random()*100+'vw';
    el.style.background=cols[Math.floor(Math.random()*cols.length)];
    el.style.width=(Math.random()*10+4)+'px';
    el.style.height=(Math.random()*10+4)+'px';
    el.style.borderRadius=Math.random()>.4?'50%':'2px';
    el.style.animationDuration=(Math.random()*2+1.5)+'s';
    el.style.animationDelay=Math.random()*.8+'s';
    document.body.appendChild(el);
    setTimeout(()=>el.remove(),(Math.random()*2+2)*1000);
  }
}

// ══════════════════════════════════════════
// HELPERS
// ══════════════════════════════════════════
function showOv(t,s){document.getElementById('ov-txt').textContent=t;document.getElementById('ov-sub').textContent=s;document.getElementById('overlay').classList.add('show')}
function hideOv(){document.getElementById('overlay').classList.remove('show')}
let ntimer;
function showNotif(m,type){
  const el=document.getElementById('notif');
  el.textContent=m;el.className='notif'+(type==='good'?' good':type==='bad'?' bad':'');
  el.style.display='block';clearTimeout(ntimer);ntimer=setTimeout(()=>el.style.display='none',3200);
}
function copyReport(){
  if(!lastReport)return;
  const r=lastReport;
  let t=`YOURWAY STORAGE — CALL QA REPORT\n\nAgent: ${r.agent} | Date: ${r.date} | Type: ${r.call_type}\nScore: ${r.overall_score}/100 (${r.grade}) — ${r.grade_label}\n\n${r.summary}\n\n`;
  if(r.pp_note)t+='PROTECTION PLAN:\n'+r.pp_note+'\n\n';
  if(r.promo_note)t+='PROMO & PRICING:\n'+r.promo_note+'\n\n';
  if(r.did_well?.length)t+='DID WELL:\n'+r.did_well.map(x=>'• '+x).join('\n')+'\n\n';
  if(r.fairly_well?.length)t+='FAIRLY WELL:\n'+r.fairly_well.map(x=>'• '+x).join('\n')+'\n\n';
  if(r.needs_work?.length)t+='NEEDS WORK:\n'+r.needs_work.map(x=>'• '+x).join('\n')+'\n\n';
  navigator.clipboard.writeText(t).then(()=>showNotif('📋 Copied!','good'));
}

function loadSample(){
  document.getElementById('e-agent').value='Sarah Chen';
  document.getElementById('e-loc').value='walton';
  document.getElementById('e-date').value=new Date().toISOString().split('T')[0];
  document.getElementById('e-transcript').value=`[00:00] Agent: Thank you for calling YourWay Storage, this is Sarah, how can I help you today?
[00:04] Caller: Hi yeah, I need a storage unit. I'm moving out of my apartment next month.
[00:09] Agent: Of course! Can I get your name real quick?
[00:11] Caller: Yeah it's Marcus Williams.
[00:13] Agent: Great, Marcus! So you're moving — can you tell me a little about what you need to store? Like furniture, boxes, or both?
[00:19] Caller: Yeah it's like a full bedroom, couch, TV, and probably 30 boxes or so.
[00:24] Agent: Perfect, that sounds like a 10x10 is your best bet Marcus — it's about the size of a small bedroom, so your couch, bed frame, dresser and all those boxes will fit comfortably. At our Walton Way location here in Augusta we're fully climate controlled which is great for your furniture and electronics especially in this heat.
[00:42] Caller: Nice. What does it cost?
[00:44] Agent: So right now we have a great promotion — it's 50% off your first month, so the 10x10 would be $73 for your first month instead of $145. That promo does end April 30th so the timing is perfect. After the first month it goes to the standard rate of $145. There's also a one-time admin fee of $25 when you move in.
[01:06] Agent: We also offer a protection plan — it's zero deductible, and I'd recommend our $17 a month plan which gives you $3,500 in coverage.
[01:22] Caller: I have renters insurance actually.
[01:24] Agent: That's good to know Marcus, though a lot of renters policies don't cover off-site storage. I'd still really recommend the protection plan — $17 a month for zero deductible peace of mind is hard to beat.
[01:36] Caller: Hmm, my stuff isn't really worth $3,500 though.
[01:39] Agent: No problem — we also have a $13 a month option that covers up to $2,500. Given what you described that should cover you well.
[01:48] Agent: Our access hours are 6am to 10pm every day, and customer care is available weekdays and Saturday 9 to 8, Sunday 9 to 5. Our facility uses Nokē smart access so you get in right from your phone.
[02:05] Agent: Just want to let you know our pricing and promo rate aren't guaranteed — they change based on availability. I can reserve the 10x10 for you right now with no credit card required, takes 3 minutes.
[02:19] Caller: Yeah okay let's do that.
[02:24] Caller: 706-555-0147.
[02:31] Caller: marcus.w92@gmail.com
[02:34] Agent: Perfect Marcus, you're all set! Anything else I can help you with?
[02:40] Agent: My pleasure, talk soon!`;
  showNotif('📋 Sample loaded!','good');
}

// init
renderPhrases();
</script>
</body>
</html>

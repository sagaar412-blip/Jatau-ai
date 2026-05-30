<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Recruit AI OS</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Geist:wght@300;400;500;600;700&family=Geist+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#09090b;--bg1:#111113;--bg2:#18181b;--bg3:#1f1f23;--bg4:#27272a;
  --border:#2a2a2f;--border2:#3a3a40;
  --text:#fafafa;--text2:#a1a1aa;--text3:#71717a;--text4:#52525b;
  --accent:#f97316;--accent2:#fb923c;--accentdim:rgba(249,115,22,.12);--accentglow:rgba(249,115,22,.3);
  --green:#22c55e;--greendim:rgba(34,197,94,.12);
  --blue:#3b82f6;--bluedim:rgba(59,130,246,.12);
  --purple:#a855f7;--purpledim:rgba(168,85,247,.12);
  --red:#ef4444;--reddim:rgba(239,68,68,.12);
  --yellow:#eab308;--yellowdim:rgba(234,179,8,.12);
  --r:8px;--r2:12px;--r3:16px;
  --shadow:0 4px 32px rgba(0,0,0,.5);
  --shadow2:0 2px 8px rgba(0,0,0,.3);
}
html,body{height:100%;background:var(--bg);color:var(--text);font-family:'Geist',sans-serif;font-size:14px;line-height:1.6;overflow:hidden}
::-webkit-scrollbar{width:3px;height:3px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--border2);border-radius:3px}

/* ── Layout ── */
#app{display:flex;height:100vh;position:relative}

/* ── Sidebar ── */
.sidebar{
  width:240px;min-width:240px;background:var(--bg1);
  border-right:1px solid var(--border);
  display:flex;flex-direction:column;
  transition:width .2s ease;
  position:relative;z-index:20;
}
.sidebar.collapsed{width:56px;min-width:56px}
.sidebar-header{
  padding:16px 16px 12px;
  border-bottom:1px solid var(--border);
  display:flex;align-items:center;gap:10px;
}
.logo{
  display:flex;align-items:center;gap:10px;
  font-family:'Instrument Serif',serif;font-size:18px;color:var(--text);
  white-space:nowrap;overflow:hidden;
}
.logo-icon{
  width:30px;height:30px;min-width:30px;
  background:var(--accent);border-radius:7px;
  display:flex;align-items:center;justify-content:center;
  font-size:14px;font-family:'Geist',sans-serif;font-weight:700;color:white;
  flex-shrink:0;
}
.logo-text{font-family:'Instrument Serif',serif;font-size:16px;font-style:italic}
.logo-sub{font-size:9px;font-family:'Geist',sans-serif;color:var(--text4);font-style:normal;letter-spacing:1.5px;text-transform:uppercase;margin-left:1px}

.sidebar-toggle{
  margin-left:auto;width:24px;height:24px;min-width:24px;
  background:transparent;border:1px solid var(--border);
  border-radius:6px;color:var(--text3);cursor:pointer;
  display:flex;align-items:center;justify-content:center;font-size:11px;
  transition:all .15s;flex-shrink:0;
}
.sidebar-toggle:hover{background:var(--bg3);color:var(--text)}

.sidebar-nav{flex:1;padding:10px 8px;overflow-y:auto}
.nav-group-label{
  font-size:9px;font-weight:600;color:var(--text4);
  letter-spacing:1.2px;text-transform:uppercase;
  padding:8px 8px 4px;
  white-space:nowrap;overflow:hidden;
}
.sidebar.collapsed .nav-group-label{opacity:0}
.nav-item{
  display:flex;align-items:center;gap:10px;
  padding:8px 8px;border-radius:var(--r);
  color:var(--text2);font-size:13px;font-weight:500;
  cursor:pointer;transition:all .12s;margin-bottom:1px;
  white-space:nowrap;overflow:hidden;position:relative;
}
.nav-item:hover{background:var(--bg3);color:var(--text)}
.nav-item.active{background:var(--accentdim);color:var(--accent)}
.nav-item .ni{font-size:15px;min-width:20px;text-align:center;flex-shrink:0}
.nav-item .nl{flex:1;overflow:hidden;text-overflow:ellipsis}
.nav-badge{
  margin-left:auto;background:var(--accent);color:white;
  font-size:9px;font-weight:700;padding:1px 5px;border-radius:10px;
  min-width:18px;text-align:center;flex-shrink:0;
}

.sidebar-footer{
  padding:10px 8px 12px;border-top:1px solid var(--border);
}
.user-block{
  display:flex;align-items:center;gap:10px;
  padding:8px;border-radius:var(--r);cursor:pointer;
  transition:background .12s;overflow:hidden;
}
.user-block:hover{background:var(--bg3)}
.user-avatar{
  width:28px;height:28px;min-width:28px;border-radius:7px;
  background:var(--accentdim);border:1px solid var(--accent);
  display:flex;align-items:center;justify-content:center;
  font-size:11px;font-weight:700;color:var(--accent);flex-shrink:0;
}
.user-info{flex:1;overflow:hidden}
.user-name{font-size:12px;font-weight:600;color:var(--text);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.user-role{font-size:10px;color:var(--text3);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}

/* ── Main ── */
.main{flex:1;display:flex;flex-direction:column;overflow:hidden;min-width:0}

/* ── Topbar ── */
.topbar{
  height:52px;min-height:52px;
  background:var(--bg1);border-bottom:1px solid var(--border);
  display:flex;align-items:center;padding:0 20px;gap:12px;
}
.topbar-title{font-family:'Instrument Serif',serif;font-size:18px;color:var(--text);font-style:italic;flex:1}
.topbar-actions{display:flex;align-items:center;gap:8px}

/* Search */
.search-bar{
  display:flex;align-items:center;gap:8px;
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r);padding:6px 12px;
  width:240px;transition:all .15s;
}
.search-bar:focus-within{border-color:var(--accent);width:280px}
.search-bar input{
  background:transparent;border:none;outline:none;
  color:var(--text);font-family:'Geist',sans-serif;font-size:13px;
  flex:1;
}
.search-bar input::placeholder{color:var(--text4)}
.search-icon{color:var(--text4);font-size:13px}

/* Buttons */
.btn{
  display:inline-flex;align-items:center;gap:6px;
  padding:7px 14px;border-radius:var(--r);border:none;
  font-family:'Geist',sans-serif;font-size:13px;font-weight:500;
  cursor:pointer;transition:all .12s;white-space:nowrap;
}
.btn-primary{background:var(--accent);color:white}
.btn-primary:hover{background:var(--accent2);box-shadow:0 0 16px var(--accentglow)}
.btn-secondary{background:var(--bg3);color:var(--text);border:1px solid var(--border)}
.btn-secondary:hover{border-color:var(--border2);background:var(--bg4)}
.btn-ghost{background:transparent;color:var(--text2)}
.btn-ghost:hover{background:var(--bg3);color:var(--text)}
.btn-danger{background:var(--reddim);color:var(--red);border:1px solid rgba(239,68,68,.2)}
.btn-sm{padding:5px 10px;font-size:12px;border-radius:6px}
.btn-xs{padding:3px 8px;font-size:11px;border-radius:5px}
.btn:disabled{opacity:0.45;cursor:not-allowed}

/* ── Content ── */
.content{flex:1;overflow-y:auto;padding:24px}

/* ── Cards ── */
.card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r2)}
.card-header{
  display:flex;align-items:center;justify-content:space-between;
  padding:14px 18px;border-bottom:1px solid var(--border);
}
.card-title{font-weight:600;font-size:13px;color:var(--text)}

/* ── Stats ── */
.stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-bottom:20px}
.stat{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r2);padding:18px;position:relative;overflow:hidden;
}
.stat::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:var(--c,var(--accent))}
.stat.green{--c:var(--green)}
.stat.blue{--c:var(--blue)}
.stat.purple{--c:var(--purple)}
.stat-label{font-size:11px;color:var(--text3);margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px}
.stat-val{font-family:'Instrument Serif',serif;font-size:36px;color:var(--text);line-height:1}
.stat-sub{font-size:11px;color:var(--text3);margin-top:6px}
.stat-icon{position:absolute;top:14px;right:14px;font-size:18px;opacity:.3}

/* ── Table ── */
.table-wrap{overflow-x:auto}
table{width:100%;border-collapse:collapse}
thead th{
  text-align:left;padding:9px 16px;
  font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;
  color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border);
}
tbody tr{border-bottom:1px solid var(--border);transition:background .1s;cursor:pointer}
tbody tr:hover{background:var(--bg3)}
tbody tr:last-child{border:none}
td{padding:11px 16px;vertical-align:middle}
.td-name{font-weight:600;font-size:13px;color:var(--text)}
.td-sub{font-size:11px;color:var(--text3);margin-top:1px}
.td-mono{font-family:'Geist Mono',monospace;font-size:11px;color:var(--text2)}

/* ── Chips ── */
.chip{
  display:inline-flex;align-items:center;gap:3px;
  padding:2px 8px;border-radius:20px;font-size:11px;font-weight:500;
  white-space:nowrap;
}
.chip-orange{background:var(--accentdim);color:var(--accent);border:1px solid rgba(249,115,22,.2)}
.chip-green{background:var(--greendim);color:var(--green);border:1px solid rgba(34,197,94,.2)}
.chip-blue{background:var(--bluedim);color:var(--blue);border:1px solid rgba(59,130,246,.2)}
.chip-purple{background:var(--purpledim);color:var(--purple);border:1px solid rgba(168,85,247,.2)}
.chip-gray{background:var(--bg4);color:var(--text2);border:1px solid var(--border)}
.chip-red{background:var(--reddim);color:var(--red);border:1px solid rgba(239,68,68,.2)}
.chip-yellow{background:var(--yellowdim);color:var(--yellow);border:1px solid rgba(234,179,8,.2)}

/* ── Empty ── */
.empty{text-align:center;padding:60px 20px}
.empty-icon{font-size:36px;margin-bottom:12px;opacity:.3}
.empty-title{font-weight:600;font-size:15px;color:var(--text2)}
.empty-sub{font-size:13px;color:var(--text4);margin-top:6px}

/* ── Skeleton ── */
.skel{
  background:linear-gradient(90deg,var(--bg3) 25%,var(--bg4) 50%,var(--bg3) 75%);
  background-size:200% 100%;animation:shimmer 1.4s infinite;border-radius:4px;
}
@keyframes shimmer{0%{background-position:-200% 0}100%{background-position:200% 0}}

/* ── Modal ── */
.overlay{
  position:fixed;inset:0;background:rgba(0,0,0,.75);
  z-index:1000;display:flex;align-items:center;justify-content:center;
  backdrop-filter:blur(4px);animation:fadeIn .15s ease;
}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
.modal{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r3);width:720px;max-width:94vw;max-height:88vh;
  display:flex;flex-direction:column;box-shadow:var(--shadow);
  animation:slideUp .18s ease;
}
@keyframes slideUp{from{transform:translateY(16px);opacity:0}to{transform:translateY(0);opacity:1}}
.modal-sm{width:480px}
.modal-header{
  padding:18px 22px 14px;border-bottom:1px solid var(--border);
  display:flex;align-items:center;justify-content:space-between;flex-shrink:0;
}
.modal-title{font-family:'Instrument Serif',serif;font-size:18px;font-style:italic}
.modal-body{padding:22px;overflow-y:auto;flex:1}
.modal-footer{padding:14px 22px;border-top:1px solid var(--border);display:flex;justify-content:flex-end;gap:8px;flex-shrink:0}
.close-btn{
  width:26px;height:26px;background:var(--bg3);border:1px solid var(--border);
  border-radius:6px;color:var(--text3);cursor:pointer;
  display:flex;align-items:center;justify-content:center;font-size:14px;
}
.close-btn:hover{color:var(--text);border-color:var(--border2)}

/* ── Forms ── */
.form-group{margin-bottom:14px}
.form-label{display:block;font-size:11px;font-weight:600;color:var(--text2);margin-bottom:5px;text-transform:uppercase;letter-spacing:.5px}
.form-input,.form-select,.form-textarea{
  width:100%;padding:8px 11px;
  background:var(--bg3);border:1px solid var(--border);
  border-radius:var(--r);color:var(--text);
  font-family:'Geist',sans-serif;font-size:13px;
  outline:none;transition:border-color .12s;
}
.form-input:focus,.form-select:focus,.form-textarea:focus{border-color:var(--accent)}
.form-textarea{resize:vertical;min-height:80px}
.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}

/* ── Candidate Profile ── */
.profile-hero{display:flex;gap:16px;align-items:flex-start;margin-bottom:20px}
.profile-av{
  width:56px;height:56px;border-radius:var(--r2);
  background:var(--accentdim);border:2px solid var(--accent);
  display:flex;align-items:center;justify-content:center;
  font-family:'Instrument Serif',serif;font-size:22px;color:var(--accent);flex-shrink:0;
}
.profile-name{font-family:'Instrument Serif',serif;font-size:22px;color:var(--text);font-style:italic}
.profile-role{font-size:13px;color:var(--text2);margin-top:2px}
.profile-meta{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
.pmeta{display:flex;align-items:center;gap:4px;font-size:12px;color:var(--text2)}

/* Tabs */
.tabs{display:flex;gap:4px;border-bottom:1px solid var(--border);padding:0 22px;flex-shrink:0}
.tab{
  padding:10px 14px;font-size:12px;font-weight:500;color:var(--text3);
  cursor:pointer;border-bottom:2px solid transparent;transition:all .12s;
  margin-bottom:-1px;white-space:nowrap;
}
.tab:hover{color:var(--text2)}
.tab.active{color:var(--accent);border-bottom-color:var(--accent)}
.tab-content{padding:20px 22px;overflow-y:auto;flex:1}

/* Info grid */
.info-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:16px}
.info-item{background:var(--bg3);border:1px solid var(--border);border-radius:var(--r);padding:10px 12px}
.info-l{font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.5px;margin-bottom:2px}
.info-v{font-size:13px;color:var(--text);font-weight:500}

/* Work history */
.work-item{display:flex;gap:12px;margin-bottom:14px}
.work-dot{width:8px;height:8px;border-radius:50%;background:var(--accent);flex-shrink:0;margin-top:5px}
.work-title{font-weight:600;font-size:13px;color:var(--text)}
.work-co{font-size:12px;color:var(--text2)}
.work-dates{font-size:11px;color:var(--text3);font-family:'Geist Mono',monospace;margin-top:2px}
.work-desc{font-size:12px;color:var(--text2);margin-top:4px;line-height:1.55}

/* AI summary */
.ai-box{
  background:linear-gradient(135deg,var(--purpledim),rgba(168,85,247,.06));
  border:1px solid rgba(168,85,247,.2);border-radius:var(--r2);
  padding:14px 16px;margin-bottom:16px;
}
.ai-label{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--purple);margin-bottom:8px;display:flex;align-items:center;gap:5px}
.ai-text{font-size:13px;color:var(--text);line-height:1.65}

/* Pipeline Kanban */
.kanban{display:flex;gap:12px;overflow-x:auto;padding-bottom:8px}
.k-col{min-width:210px;flex-shrink:0}
.k-header{
  padding:10px 12px;border-radius:var(--r) var(--r) 0 0;
  border:1px solid var(--border);border-bottom:none;
  background:var(--bg2);
  display:flex;align-items:center;justify-content:space-between;
}
.k-title{font-size:12px;font-weight:600;color:var(--text2)}
.k-count{font-size:10px;color:var(--text4);background:var(--bg4);padding:1px 7px;border-radius:10px;border:1px solid var(--border)}
.k-body{
  background:var(--bg);border:1px solid var(--border);
  border-radius:0 0 var(--r) var(--r);
  min-height:180px;padding:8px;
}
.k-card{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r);padding:10px 12px;margin-bottom:8px;
  cursor:pointer;transition:border-color .12s;
}
.k-card:hover{border-color:var(--accent)}
.k-name{font-size:12px;font-weight:600;color:var(--text)}
.k-sub{font-size:11px;color:var(--text3);margin-top:2px}

/* Analytics charts placeholder */
.chart-box{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r2);padding:18px;
}
.bar-chart{display:flex;align-items:flex-end;gap:6px;height:120px;margin-top:12px}
.bar{
  flex:1;border-radius:4px 4px 0 0;background:var(--accent);opacity:.7;
  transition:opacity .15s;min-width:0;
}
.bar:hover{opacity:1}

/* Toast */
.toast-wrap{position:fixed;bottom:20px;right:20px;z-index:9999;display:flex;flex-direction:column;gap:8px}
.toast{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r2);padding:11px 15px;
  display:flex;align-items:center;gap:10px;
  min-width:260px;max-width:360px;
  box-shadow:var(--shadow);animation:slideIn .2s ease;
  font-size:13px;
}
@keyframes slideIn{from{transform:translateX(16px);opacity:0}to{transform:translateX(0);opacity:1}}
.toast.ok{border-left:3px solid var(--green)}
.toast.err{border-left:3px solid var(--red)}
.toast.inf{border-left:3px solid var(--blue)}

/* Pagination */
.pagination{display:flex;align-items:center;justify-content:space-between;padding:11px 16px;border-top:1px solid var(--border)}
.page-info{font-size:12px;color:var(--text3)}
.page-btns{display:flex;gap:4px}
.page-btn{
  width:28px;height:28px;border-radius:6px;
  display:flex;align-items:center;justify-content:center;
  font-size:12px;cursor:pointer;
  border:1px solid var(--border);background:var(--bg3);color:var(--text2);
  transition:all .1s;
}
.page-btn:hover,.page-btn.on{background:var(--accentdim);color:var(--accent);border-color:var(--accent)}
.page-btn:disabled{opacity:.35;cursor:not-allowed}

/* Filter bar */
.filter-bar{display:flex;gap:8px;padding:12px 16px;border-bottom:1px solid var(--border);align-items:center;flex-wrap:wrap}
.fb-search{position:relative;flex:1;min-width:180px}
.fb-search input{width:100%;padding:7px 12px 7px 30px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r);color:var(--text);font-family:'Geist',sans-serif;font-size:13px;outline:none}
.fb-search input:focus{border-color:var(--accent)}
.fb-icon{position:absolute;left:9px;top:50%;transform:translateY(-50%);color:var(--text4);font-size:13px;pointer-events:none}
.fb-select{padding:7px 11px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r);color:var(--text2);font-family:'Geist',sans-serif;font-size:13px;outline:none;cursor:pointer}
.fb-select:focus{border-color:var(--accent)}

/* Login */
.login-screen{display:flex;align-items:center;justify-content:center;height:100vh;background:var(--bg)}
.login-box{width:400px;background:var(--bg2);border:1px solid var(--border);border-radius:20px;padding:36px}
.login-logo{font-family:'Instrument Serif',serif;font-size:26px;font-style:italic;margin-bottom:4px}
.login-sub{font-size:13px;color:var(--text3);margin-bottom:28px}
.login-err{font-size:12px;color:var(--red);margin-top:8px;display:none}

/* Settings */
.settings-section{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r2);padding:20px;margin-bottom:16px}
.settings-title{font-weight:600;font-size:14px;margin-bottom:14px}
.code-block{background:var(--bg);border:1px solid var(--border);border-radius:var(--r);padding:11px 14px;font-family:'Geist Mono',monospace;font-size:12px;color:var(--text2);position:relative;word-break:break-all}
.copy-btn{position:absolute;top:6px;right:6px;background:var(--bg3);border:1px solid var(--border);border-radius:5px;color:var(--text3);font-size:11px;padding:3px 8px;cursor:pointer;font-family:'Geist',sans-serif}
.copy-btn:hover{color:var(--text)}

/* Notes */
.note-item{background:var(--bg3);border:1px solid var(--border);border-radius:var(--r);padding:12px;margin-bottom:8px}
.note-text{font-size:13px;color:var(--text);line-height:1.55}
.note-meta{font-size:11px;color:var(--text4);margin-top:6px;font-family:'Geist Mono',monospace}

/* Activity */
.activity-item{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid var(--border)}
.activity-item:last-child{border:none}
.activity-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;margin-top:5px;background:var(--accent)}
.activity-text{font-size:13px;color:var(--text);flex:1}
.activity-time{font-size:11px;color:var(--text4);font-family:'Geist Mono',monospace;white-space:nowrap}

/* Section header */
.section-lbl{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--text4);margin-bottom:10px;margin-top:18px}

/* Jobs grid */
.jobs-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.job-card{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r2);padding:18px;cursor:pointer;
  transition:all .12s;position:relative;overflow:hidden;
}
.job-card:hover{border-color:var(--border2);transform:translateY(-1px);box-shadow:var(--shadow2)}
.job-card.selected{border-color:var(--accent);background:var(--accentdim)}
.job-title{font-family:'Instrument Serif',serif;font-size:15px;font-style:italic;color:var(--text);margin-bottom:4px}
.job-loc{font-size:12px;color:var(--text3);margin-bottom:10px;display:flex;align-items:center;gap:4px}
.job-stats{display:flex;gap:16px}
.js-n{font-family:'Instrument Serif',serif;font-size:22px;color:var(--accent)}
.js-l{font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.5px}

/* New job modal */
.nj-form .form-grid{grid-template-columns:1fr 1fr}

/* Tooltip */
[title]{cursor:help}
</style>
</head>
<body>
<div id="app"></div>
<div class="toast-wrap" id="toastWrap"></div>

<script>
const API = "https://blessed-salamander-994.convex.site";
const PAGE_SZ = 30;

// ── State ──────────────────────────────────────────────────────────────────
const S = {
  token: localStorage.getItem("rk_token") || "",
  grokKey: localStorage.getItem("rk_grok") || "",
  page: "dashboard",
  candidates: [], jobs: [],
  loading: false,
  cPage: 1, search: "", jobFilter: "", statusFilter: "",
  selectedCand: null, selectedJob: null,
  candTab: "overview",
  showNewJob: false,
  showScreen: false,
  screenStep: 0,     // 0=config, 1=scoring, 2=results
  screenJobId: "",
  screenCriteria: { minExp:0, skills:"", maxSalary:"", location:"", notes:"" },
  screenQueue: [], screenResults: [], screenDone: 0, screenProgress: 0, screenCurrent: "",
  toasts: [],
  stats: { total:0, today:0, week:0, jobs:0 },
  notes: {},
};

// ── API ────────────────────────────────────────────────────────────────────
function clean(t){ return (t||"").replace(/[^\x20-\x7E]/g,"").trim() }
async function api(path, opts={}){
  const tok = clean(S.token);
  const res = await fetch(API+path,{
    ...opts,
    headers:{"Content-Type":"application/json",...(tok?{"Authorization":"Bearer "+tok}:{}), ...(opts.headers||{})},
  });
  if(!res.ok){ const e=await res.json().catch(()=>({})); throw new Error(e.error||"HTTP "+res.status) }
  return res.json();
}
async function loadJobs(){
  try{ const d=await api("/ext/jobs"); S.jobs=d.jobs||[]; } catch(e){ toast("Jobs: "+e.message,"err") }
}
async function loadCandidates(){
  S.loading=true; render();
  try{
    const qs = S.jobFilter ? "?jobId="+S.jobFilter : "";
    const d = await api("/ext/candidates"+qs);
    S.candidates = d.candidates||d.data||[];
    const now=Date.now(), day=86400000;
    S.stats = {
      total: S.candidates.length,
      today: S.candidates.filter(c=>now-new Date(c._creationTime||c.createdAt||0)<day).length,
      week: S.candidates.filter(c=>now-new Date(c._creationTime||c.createdAt||0)<7*day).length,
      jobs: S.jobs.length,
    };
  } catch(e){ S.candidates=[]; }
  S.loading=false; render();
}
async function createJob(data){
  await api("/ext/jobs",{method:"POST",body:JSON.stringify(data)});
  await loadJobs(); toast("Job created!","ok");
}

// ── Helpers ────────────────────────────────────────────────────────────────
function ago(ts){
  if(!ts) return "—";
  const d=Date.now()-new Date(ts).getTime(), m=Math.floor(d/60000);
  if(m<1) return "just now"; if(m<60) return m+"m ago";
  const h=Math.floor(m/60); if(h<24) return h+"h ago";
  return Math.floor(h/24)+"d ago";
}
function fmt(v,fb="—"){ return v||fb }
function initials(n){ return (n||"?").split(" ").filter(Boolean).slice(0,2).map(w=>w[0]).join("").toUpperCase() }
function raw(c){ try{return c._rawData?JSON.parse(c._rawData):(c.rawData?JSON.parse(c.rawData):{})}catch{return{}} }
function exp(c){ const e=c.experienceYears; return e!=null?e+"y":"—" }

function filtered(){
  let l = S.candidates;
  if(S.search){ const q=S.search.toLowerCase(); l=l.filter(c=>(c.name||"").toLowerCase().includes(q)||(c.email||"").toLowerCase().includes(q)||(c.currentTitle||"").toLowerCase().includes(q)||(c.currentCompany||"").toLowerCase().includes(q)||(c.skills||[]).some(s=>s.toLowerCase().includes(q))) }
  if(S.jobFilter) l=l.filter(c=>c.jobId===S.jobFilter);
  if(S.statusFilter) l=l.filter(c=>(c.status||"sourced")===S.statusFilter);
  return l;
}
function paged(){ const l=filtered(),s=(S.cPage-1)*PAGE_SZ; return {list:l.slice(s,s+PAGE_SZ),total:l.length} }
function jobName(id){ return S.jobs.find(j=>j._id===id)?.title||"" }
function statusColor(s){ return {sourced:"chip-blue",screening:"chip-yellow",shortlisted:"chip-green",rejected:"chip-red",contacted:"chip-orange"}[s]||"chip-gray" }

function toast(msg,type="inf",dur=4000){
  const id=Date.now(); S.toasts.push({id,msg,type});
  renderToasts();
  setTimeout(()=>{S.toasts=S.toasts.filter(t=>t.id!==id);renderToasts()},dur);
}
function renderToasts(){
  const icons={ok:"✓",err:"✕",inf:"i"};
  document.getElementById("toastWrap").innerHTML=S.toasts.map(t=>`
    <div class="toast ${t.type}"><span style="font-weight:700">${icons[t.type]||"i"}</span> ${t.msg}</div>
  `).join("");
}

// ── RENDER ─────────────────────────────────────────────────────────────────
function render(){
  const app=document.getElementById("app");
  if(!S.token){ app.innerHTML=loginHTML(); bindLogin(); return; }
  app.innerHTML=`
    <div class="sidebar" id="sidebar">${sidebarHTML()}</div>
    <div class="main">
      <div class="topbar">${topbarHTML()}</div>
      <div class="content" id="mc">${pageHTML()}</div>
    </div>
    ${S.selectedCand?candModalHTML():""}
    ${S.showNewJob?newJobModalHTML():""}
    ${S.showScreen?aiScreenModalHTML():""}
  `;
  bindShell();
}

// ── LOGIN ──────────────────────────────────────────────────────────────────
function loginHTML(){ return `
<div class="login-screen">
  <div class="login-box">
    <div class="login-logo">Recruit AI OS</div>
    <div style="font-size:12px;color:var(--text3);font-style:italic;margin-bottom:20px">The AI-Powered Recruitment Operating System</div>
    <div class="login-sub">Enter your auth token to connect your workspace.</div>
    <div class="form-group">
      <label class="form-label">Auth Token</label>
      <input class="form-input" id="tokIn" type="password" placeholder="Paste token from your recruiter app…"/>
    </div>
    <button class="btn btn-primary" id="tokBtn" style="width:100%;justify-content:center">Connect Workspace →</button>
    <div id="tokErr" class="login-err"></div>
    <div style="margin-top:16px;padding:12px;background:var(--bg3);border-radius:var(--r);font-size:11px;color:var(--text4);line-height:1.6">
      <strong style="color:var(--text2)">Where is my token?</strong><br>
      Your token comes from the Convex Recruiter App backend. Go to your app → Settings → Extension Setup. It's a short string of random characters, NOT a paragraph.
    </div>
  </div>
</div>`; }

function bindLogin(){
  const btn=document.getElementById("tokBtn");
  const inp=document.getElementById("tokIn");
  const err=document.getElementById("tokErr");
  btn.onclick=async()=>{
    const v=inp.value.trim();
    err.style.display="none";
    if(!v){err.textContent="Please enter a token.";err.style.display="block";return}
    if(v.length>500){err.textContent="That looks too long — a token is a short string, not a paragraph.";err.style.display="block";return}
    btn.disabled=true;btn.textContent="Connecting…";
    S.token=clean(v); localStorage.setItem("rk_token",S.token);
    try{ await loadJobs(); await loadCandidates(); render(); }
    catch(e){ S.token=""; localStorage.removeItem("rk_token"); err.textContent="Failed: "+e.message; err.style.display="block"; btn.disabled=false; btn.textContent="Connect Workspace →"; }
  };
  inp.onkeydown=e=>{ if(e.key==="Enter") btn.click(); };
}

// ── SIDEBAR ────────────────────────────────────────────────────────────────
function sidebarHTML(){
  const nav=(id,icon,lbl,badge)=>`<div class="nav-item ${S.page===id?'active':''}" data-nav="${id}"><span class="ni">${icon}</span><span class="nl">${lbl}</span>${badge?`<span class="nav-badge">${badge}</span>`:""}</div>`;
  return `
  <div class="sidebar-header">
    <div class="logo">
      <div class="logo-icon">R</div>
      <div>
        <div class="logo-text">Recruit AI OS</div>
      </div>
    </div>
    <button class="sidebar-toggle" id="sidebarToggle">◀</button>
  </div>
  <div class="sidebar-nav">
    <div class="nav-group-label">Overview</div>
    ${nav("dashboard","⚡","Dashboard")}
    ${nav("analytics","📊","Analytics")}
    <div class="nav-group-label">Recruiting</div>
    ${nav("jobs","💼","Jobs",S.jobs.length||"")}
    ${nav("candidates","👥","Candidates",S.stats.total||"")}
    ${nav("pipeline","🔄","Pipeline")}
    ${nav("talent","⭐","Talent Pool")}
    <div class="nav-group-label">Tools</div>
    ${nav("ai","✨","AI Copilot")}
    ${nav("settings","⚙️","Settings")}
  </div>
  <div class="sidebar-footer">
    <div class="user-block">
      <div class="user-avatar">${initials(S.token?S.jobs[0]?.title||"R":"?")}</div>
      <div class="user-info">
        <div class="user-name">Recruiter</div>
        <div class="user-role">hrd@ketto.org</div>
      </div>
    </div>
  </div>`;
}

// ── TOPBAR ────────────────────────────────────────────────────────────────
function topbarHTML(){
  const titles={dashboard:"Dashboard",analytics:"Analytics",jobs:"Jobs",candidates:"Candidates",pipeline:"Pipeline",talent:"Talent Pool",ai:"AI Copilot",settings:"Settings"};
  return `
  <div class="topbar-title">${titles[S.page]||""}</div>
  <div class="topbar-actions">
    <div class="search-bar"><span class="search-icon">🔍</span><input placeholder="Search candidates, jobs…" id="globalSearch" value="${S.page==='candidates'?S.search:''}"/></div>
    ${S.page==="candidates"?`<button class="btn btn-secondary btn-sm" id="aiScreenBtn">✨ AI Shortlist</button><button class="btn btn-ghost btn-sm" id="refreshBtn">↻</button>`:""}
    ${S.page==="jobs"?`<button class="btn btn-primary btn-sm" id="newJobBtn">+ New Job</button>`:""}
    <button class="btn btn-ghost btn-sm" id="logoutBtn" title="Sign out">⏏</button>
  </div>`;
}

// ── PAGE ROUTING ──────────────────────────────────────────────────────────
function pageHTML(){
  switch(S.page){
    case "dashboard": return dashboardHTML();
    case "candidates": return candidatesHTML();
    case "jobs": return jobsHTML();
    case "pipeline": return pipelineHTML();
    case "talent": return talentHTML();
    case "analytics": return analyticsHTML();
    case "ai": return aiHTML();
    case "settings": return settingsHTML();
    default: return dashboardHTML();
  }
}

// ── DASHBOARD ─────────────────────────────────────────────────────────────
function dashboardHTML(){
  const recent=[...S.candidates].sort((a,b)=>new Date(b._creationTime||b.createdAt||0)-new Date(a._creationTime||a.createdAt||0)).slice(0,8);
  const stages=["sourced","screening","shortlisted","contacted","rejected"];
  const stageCounts=stages.reduce((a,s)=>{a[s]=S.candidates.filter(c=>(c.status||"sourced")===s).length;return a},{});

  return `
  <div class="stats-row">
    ${statCard("","👥",S.stats.total,"Total Candidates","All time")}
    ${statCard("green","📅",S.stats.today,"Added Today","Last 24h")}
    ${statCard("blue","📈",S.stats.week,"This Week","Last 7 days")}
    ${statCard("purple","💼",S.stats.jobs,"Active Jobs","Open positions")}
  </div>

  <div style="display:grid;grid-template-columns:1fr 340px;gap:16px">
    <div class="card">
      <div class="card-header">
        <div class="card-title">Recent Candidates</div>
        <button class="btn btn-ghost btn-sm" data-nav="candidates">View all →</button>
      </div>
      ${recent.length===0?`<div class="empty"><div class="empty-icon">👥</div><div class="empty-title">No candidates yet</div><div class="empty-sub">Import from Naukri using the Chrome extension</div></div>`:`
      <div class="table-wrap"><table>
        <thead><tr><th>Name</th><th>Role</th><th>Location</th><th>Status</th><th>Added</th></tr></thead>
        <tbody>
          ${recent.map(c=>`
          <tr class="cand-row" data-id="${c._id}">
            <td><div class="td-name">${fmt(c.name)}</div><div class="td-sub td-mono">${fmt(c.email)}</div></td>
            <td><div style="font-size:12px">${fmt(c.currentTitle)}</div><div class="td-sub">${fmt(c.currentCompany)}</div></td>
            <td><span style="font-size:12px;color:var(--text2)">${fmt(c.location)}</span></td>
            <td><span class="chip ${statusColor(c.status||'sourced')}">${c.status||"sourced"}</span></td>
            <td><span style="font-size:11px;color:var(--text4)">${ago(c._creationTime||c.createdAt)}</span></td>
          </tr>`).join("")}
        </tbody>
      </table></div>`}
    </div>

    <div style="display:flex;flex-direction:column;gap:14px">
      <div class="card">
        <div class="card-header"><div class="card-title">Pipeline Health</div></div>
        <div style="padding:14px">
          ${stages.map(s=>`
          <div style="display:flex;align-items:center;gap:8px;margin-bottom:8px">
            <div style="font-size:11px;color:var(--text2);width:70px;text-transform:capitalize">${s}</div>
            <div style="flex:1;height:6px;background:var(--bg4);border-radius:3px;overflow:hidden">
              <div style="height:100%;background:var(--accent);border-radius:3px;width:${S.stats.total?Math.round(stageCounts[s]/S.stats.total*100):0}%;opacity:.8"></div>
            </div>
            <div style="font-size:11px;color:var(--text3);width:20px;text-align:right">${stageCounts[s]}</div>
          </div>`).join("")}
        </div>
      </div>

      <div class="card">
        <div class="card-header"><div class="card-title">Jobs</div></div>
        ${S.jobs.length===0?`<div class="empty" style="padding:24px"><div class="empty-icon" style="font-size:24px">💼</div><div class="empty-title" style="font-size:13px">No jobs</div></div>`:`
        <div style="padding:8px">
          ${S.jobs.map(j=>`
          <div class="activity-item" style="padding:8px">
            <div class="activity-dot"></div>
            <div class="activity-text">${j.title}<div style="font-size:11px;color:var(--text4)">${j.location||"Remote"}</div></div>
            <span class="chip chip-orange" style="font-size:10px">${S.candidates.filter(c=>c.jobId===j._id).length}</span>
          </div>`).join("")}
        </div>`}
      </div>
    </div>
  </div>`;
}
function statCard(color,icon,val,label,sub){
  return `<div class="stat ${color}"><div class="stat-icon">${icon}</div><div class="stat-label">${label}</div><div class="stat-val">${val??0}</div><div class="stat-sub">${sub}</div></div>`;
}

// ── CANDIDATES ────────────────────────────────────────────────────────────
function candidatesHTML(){
  const {list,total}=paged();
  const pages=Math.max(1,Math.ceil(total/PAGE_SZ));
  return `
  <div class="card">
    <div class="filter-bar">
      <div class="fb-search"><span class="fb-icon">🔍</span><input id="candSearch" placeholder="Search name, skills, company…" value="${S.search}"/></div>
      <select class="fb-select" id="candJob">
        <option value="">All Jobs</option>
        ${S.jobs.map(j=>`<option value="${j._id}" ${S.jobFilter===j._id?"selected":""}>${j.title}</option>`).join("")}
      </select>
      <select class="fb-select" id="candStatus">
        <option value="">All Status</option>
        ${["sourced","screening","shortlisted","contacted","rejected"].map(s=>`<option value="${s}" ${S.statusFilter===s?"selected":""}>${s}</option>`).join("")}
      </select>
      <span style="font-size:12px;color:var(--text4);white-space:nowrap">${total} result${total!==1?"s":""}</span>
    </div>
    ${S.loading?skelRows():`
    <div class="table-wrap"><table>
      <thead><tr><th><input type="checkbox" id="checkAll"/></th><th>Candidate</th><th>Role & Company</th><th>Contact</th><th>Exp</th><th>Location</th><th>Status</th><th>Skills</th><th>Added</th></tr></thead>
      <tbody>
        ${list.length===0?`<tr><td colspan="9"><div class="empty"><div class="empty-icon">🔍</div><div class="empty-title">${S.search?"No matches":"No candidates yet"}</div><div class="empty-sub">${S.search?"Try a different search":"Import from Naukri using the Chrome extension"}</div></div></td></tr>`:
          list.map(c=>candRow(c)).join("")}
      </tbody>
    </table></div>
    <div class="pagination">
      <div class="page-info">Showing ${Math.min((S.cPage-1)*PAGE_SZ+1,total)}–${Math.min(S.cPage*PAGE_SZ,total)} of ${total}</div>
      <div class="page-btns">
        <button class="page-btn" id="prevPage" ${S.cPage<=1?"disabled":""}>‹</button>
        ${Array.from({length:Math.min(pages,7)},(_,i)=>`<button class="page-btn ${i+1===S.cPage?"on":""}" data-pg="${i+1}">${i+1}</button>`).join("")}
        <button class="page-btn" id="nextPage" ${S.cPage>=pages?"disabled":""}>›</button>
      </div>
    </div>`}
  </div>`;
}
function candRow(c){
  const r=raw(c);
  const skills=(c.skills||r.keySkills||[]).slice(0,2);
  return `
  <tr class="cand-row" data-id="${c._id}">
    <td onclick="event.stopPropagation()"><input type="checkbox" class="cand-chk" data-id="${c._id}"/></td>
    <td>
      <div style="display:flex;align-items:center;gap:9px">
        <div style="width:30px;height:30px;border-radius:7px;background:var(--accentdim);border:1px solid var(--accent);display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:var(--accent);flex-shrink:0">${initials(c.name)}</div>
        <div><div class="td-name">${fmt(c.name)}</div><div style="font-size:10px;color:var(--text4)">${ago(c._creationTime||c.createdAt)}</div></div>
      </div>
    </td>
    <td><div style="font-size:12px">${fmt(c.currentTitle)}</div><div class="td-sub">${fmt(c.currentCompany)}</div></td>
    <td><div class="td-mono">${fmt(c.email,"—")}</div><div class="td-mono">${fmt(c.phone,"—")}</div></td>
    <td><span class="chip chip-blue" style="font-size:10px">${exp(c)}</span></td>
    <td><span style="font-size:12px;color:var(--text2)">${fmt(c.location)}</span></td>
    <td><span class="chip ${statusColor(c.status||'sourced')}">${c.status||"sourced"}</span></td>
    <td>
      <div style="display:flex;gap:3px;flex-wrap:wrap">
        ${skills.map(s=>`<span class="chip chip-gray" style="font-size:10px">${s}</span>`).join("")}
        ${(c.skills||[]).length>2?`<span class="chip chip-gray" style="font-size:10px">+${(c.skills||[]).length-2}</span>`:""}
      </div>
    </td>
    <td>${jobName(c.jobId)?`<span class="chip chip-orange" style="font-size:10px">${jobName(c.jobId).slice(0,18)}</span>`:""}</td>
  </tr>`;
}
function skelRows(){
  return `<div class="table-wrap"><table><tbody>
    ${Array.from({length:8}).map(()=>`<tr>
      ${Array.from({length:9}).map(()=>`<td><div class="skel" style="height:12px;width:80px"></div></td>`).join("")}
    </tr>`).join("")}
  </tbody></table></div>`;
}

// ── CANDIDATE MODAL ───────────────────────────────────────────────────────
function candModalHTML(){
  const c=S.selectedCand; if(!c) return "";
  const r=raw(c);
  const wh=r.workHistory||c.workHistory||[];
  const edu=r.education||c.education||[];
  const langs=r.languages||c.languages||[];
  const skills=[...(c.skills||[]),...(r.keySkills||[])].filter((s,i,a)=>a.indexOf(s)===i);
  const ai=c.aiSummary||r.aiSummary||c.resdexAiSummary||"";
  const salary=r.salary||c.salary||"";
  const notice=r.noticePeriod||c.noticePeriod||"";
  const prefLoc=r.preferredLocations||c.preferredLocations||"";
  const jn=jobName(c.jobId);

  const tabs=["overview","experience","education","skills","ai","notes"];
  const tabLabels={overview:"Overview",experience:"Experience",education:"Education",skills:"Skills & Keywords",ai:"AI Analysis",notes:"Notes"};

  return `<div class="overlay" id="candOverlay">
  <div class="modal">
    <div class="modal-header">
      <div>
        <div class="modal-title">${fmt(c.name)}</div>
        <div style="font-size:12px;color:var(--text3);margin-top:2px">${fmt(c.currentTitle)} ${c.currentCompany?'· '+c.currentCompany:''}</div>
      </div>
      <div style="display:flex;gap:8px;align-items:center">
        ${c.profileUrl?`<a href="${c.profileUrl}" target="_blank" class="btn btn-secondary btn-sm">↗ Naukri</a>`:""}
        <button class="close-btn" id="closeCand">✕</button>
      </div>
    </div>
    <div class="tabs">
      ${tabs.map(t=>`<div class="tab ${S.candTab===t?"active":""}" data-tab="${t}">${tabLabels[t]}</div>`).join("")}
    </div>
    <div class="tab-content">
      ${S.candTab==="overview"?`
        <div class="profile-hero">
          <div class="profile-av">${initials(c.name)}</div>
          <div style="flex:1">
            <div class="profile-name">${fmt(c.name)}</div>
            <div class="profile-role">${fmt(c.currentTitle)}${c.currentCompany?" · "+c.currentCompany:""}</div>
            <div class="profile-meta">
              ${c.location?`<span class="pmeta">📍 ${c.location}</span>`:""}
              ${c.experienceYears!=null?`<span class="pmeta">💼 ${c.experienceYears}y exp</span>`:""}
              ${notice?`<span class="pmeta">⏱ ${notice}</span>`:""}
              ${salary?`<span class="pmeta">💰 ${salary}</span>`:""}
            </div>
            <div style="margin-top:8px">
              <select class="fb-select" id="statusSelect" style="font-size:12px;padding:4px 8px">
                ${["sourced","screening","shortlisted","contacted","rejected"].map(s=>`<option value="${s}" ${(c.status||"sourced")===s?"selected":""}>${s}</option>`).join("")}
              </select>
              ${jn?`<span class="chip chip-orange" style="margin-left:6px">${jn}</span>`:""}
            </div>
          </div>
        </div>
        ${ai?`<div class="ai-box"><div class="ai-label">✨ AI Summary</div><div class="ai-text">${ai.replace(/\*\*(.*?)\*\*/g,"<strong>$1</strong>").replace(/\n/g,"<br>")}</div></div>`:""}
        ${c.summary||r.workSummary?`<div class="section-lbl">Profile Summary</div><div style="font-size:13px;color:var(--text2);line-height:1.65;background:var(--bg3);border-radius:var(--r);padding:12px">${c.summary||r.workSummary||""}</div>`:""}
        <div class="section-lbl">Contact & Details</div>
        <div class="info-grid">
          <div class="info-item"><div class="info-l">Email</div><div class="info-v" style="font-family:'Geist Mono',monospace;font-size:12px">${fmt(c.email)}</div></div>
          <div class="info-item"><div class="info-l">Phone</div><div class="info-v" style="font-family:'Geist Mono',monospace;font-size:12px">${fmt(c.phone)}</div></div>
          <div class="info-item"><div class="info-l">Current Salary</div><div class="info-v">${fmt(salary)}</div></div>
          <div class="info-item"><div class="info-l">Notice Period</div><div class="info-v">${fmt(notice)}</div></div>
          <div class="info-item"><div class="info-l">Preferred Location</div><div class="info-v">${fmt(prefLoc)}</div></div>
          ${r.gender?`<div class="info-item"><div class="info-l">Gender</div><div class="info-v">${r.gender}</div></div>`:""}
          ${r.industry?`<div class="info-item"><div class="info-l">Industry</div><div class="info-v">${r.industry}</div></div>`:""}
          ${r.maritalStatus?`<div class="info-item"><div class="info-l">Marital Status</div><div class="info-v">${r.maritalStatus}</div></div>`:""}
        </div>
        ${langs.length?`<div class="section-lbl">Languages</div><div style="display:flex;gap:5px;flex-wrap:wrap">${langs.map(l=>`<span class="chip chip-blue">${l}</span>`).join("")}</div>`:""}
      `:""}
      ${S.candTab==="experience"?`
        ${wh.length===0?`<div class="empty"><div class="empty-icon">💼</div><div class="empty-title">No work history</div></div>`:""}
        ${wh.map(w=>`
        <div class="work-item">
          <div class="work-dot"></div>
          <div>
            <div class="work-title">${fmt(w.title)}</div>
            <div class="work-co">${fmt(w.company)}</div>
            <div class="work-dates">${w.tenure||(w.startDate?w.startDate+" – "+(w.endDate||"Present"):"")}</div>
            ${w.description?`<div class="work-desc">${String(w.description).slice(0,400)}</div>`:""}
          </div>
        </div>`).join("")}
      `:""}
      ${S.candTab==="education"?`
        ${edu.length===0?`<div class="empty"><div class="empty-icon">🎓</div><div class="empty-title">No education data</div></div>`:""}
        ${edu.map(e=>`
        <div class="work-item">
          <div class="work-dot" style="background:var(--blue)"></div>
          <div>
            <div class="work-title">${fmt(e.degree)}${e.specialization?" · "+e.specialization:""}</div>
            <div class="work-co">${fmt(e.college)}</div>
            <div class="work-dates">${fmt(e.year)}</div>
          </div>
        </div>`).join("")}
      `:""}
      ${S.candTab==="skills"?`
        ${skills.length===0?`<div class="empty"><div class="empty-icon">🛠</div><div class="empty-title">No skills data</div></div>`:`
        <div class="section-lbl">Skills</div>
        <div style="display:flex;flex-wrap:wrap;gap:6px">${skills.map(s=>`<span class="chip chip-orange">${s}</span>`).join("")}</div>
        ${r.keywords?`<div class="section-lbl" style="margin-top:16px">Keywords</div><div style="font-size:13px;color:var(--text2)">${r.keywords}</div>`:""}
        `}
      `:""}
      ${S.candTab==="ai"?`
        ${ai?`
        <div class="ai-box" style="margin-bottom:16px">
          <div class="ai-label">✨ AI Insights from CV (Naukri)</div>
          <div class="ai-text">${ai.replace(/\*\*(.*?)\*\*/g,"<strong>$1</strong>").replace(/\n/g,"<br>")}</div>
        </div>`:`<div class="empty"><div class="empty-icon">✨</div><div class="empty-title">No AI summary</div><div class="empty-sub">AI summary is captured automatically when profile is imported with jsprofile</div></div>`}
        ${c.summary||r.workSummary?`
        <div class="section-lbl">Candidate Summary</div>
        <div style="font-size:13px;color:var(--text2);line-height:1.65;background:var(--bg3);border-radius:var(--r);padding:12px">${c.summary||r.workSummary}</div>
        `:""}
      `:""}
      ${S.candTab==="notes"?`
        <div style="display:flex;gap:8px;margin-bottom:14px">
          <textarea class="form-textarea" id="noteInput" placeholder="Add a note…" style="flex:1;min-height:60px"></textarea>
          <button class="btn btn-primary btn-sm" id="addNoteBtn">Add</button>
        </div>
        ${(S.notes[c._id]||[]).length===0?`<div class="empty" style="padding:24px"><div class="empty-icon" style="font-size:24px">📝</div><div class="empty-title" style="font-size:13px">No notes yet</div></div>`:""}
        ${(S.notes[c._id]||[]).map(n=>`
        <div class="note-item">
          <div class="note-text">${n.text}</div>
          <div class="note-meta">${ago(n.ts)}</div>
        </div>`).join("")}
      `:""}
    </div>
    <div class="modal-footer">
      <button class="btn btn-danger btn-xs" id="delCandBtn">🗑 Remove</button>
      <button class="btn btn-secondary btn-sm" id="closeCand2">Close</button>
    </div>
  </div>
</div>`;
}

// ── JOBS ──────────────────────────────────────────────────────────────────
function jobsHTML(){ return `
  ${S.jobs.length===0?`
  <div class="empty" style="margin-top:80px">
    <div class="empty-icon">💼</div>
    <div class="empty-title">No jobs yet</div>
    <div class="empty-sub">Create your first job to start organising candidates</div>
    <button class="btn btn-primary" style="margin-top:16px" id="newJobBtn2">+ Create First Job</button>
  </div>`:`
  <div class="jobs-grid" id="jobsGrid">
    ${S.jobs.map(j=>{
      const cnt=S.candidates.filter(c=>c.jobId===j._id).length;
      return `<div class="job-card ${S.selectedJob?._id===j._id?"selected":""}" data-jid="${j._id}">
        <div style="display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:4px">
          <div class="job-title">${j.title}</div>
          <span class="chip chip-green" style="font-size:10px">Active</span>
        </div>
        <div class="job-loc">📍 ${j.location||"Not specified"}</div>
        <div class="job-stats">
          <div><div class="js-n">${cnt}</div><div class="js-l">Candidates</div></div>
        </div>
        <div style="margin-top:12px;display:flex;gap:6px">
          <button class="btn btn-secondary btn-xs" data-filterjob="${j._id}">View Candidates</button>
        </div>
      </div>`;
    }).join("")}
  </div>`}`; }

// ── NEW JOB MODAL ─────────────────────────────────────────────────────────
function newJobModalHTML(){ return `
<div class="overlay" id="newJobOverlay">
  <div class="modal modal-sm">
    <div class="modal-header">
      <div class="modal-title">Create New Job</div>
      <button class="close-btn" id="closeNJ">✕</button>
    </div>
    <div class="modal-body">
      <div class="form-group"><label class="form-label">Job Title *</label><input class="form-input" id="nj_title" placeholder="e.g. Inside Sales Executive"/></div>
      <div class="form-grid">
        <div class="form-group"><label class="form-label">Location</label><input class="form-input" id="nj_loc" placeholder="Mumbai, Remote…"/></div>
        <div class="form-group"><label class="form-label">Department</label><input class="form-input" id="nj_dept" placeholder="Sales, Tech…"/></div>
      </div>
      <div class="form-group"><label class="form-label">Description</label><textarea class="form-textarea" id="nj_desc" placeholder="Describe the role…"></textarea></div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-secondary btn-sm" id="closeNJ2">Cancel</button>
      <button class="btn btn-primary btn-sm" id="submitNJ">Create Job →</button>
    </div>
  </div>
</div>`; }

// ── PIPELINE ──────────────────────────────────────────────────────────────
function pipelineHTML(){
  const stages=[
    {id:"sourced",label:"Sourced",color:"var(--blue)"},
    {id:"screening",label:"Screening",color:"var(--yellow)"},
    {id:"shortlisted",label:"Shortlisted",color:"var(--purple)"},
    {id:"contacted",label:"Contacted",color:"var(--accent)"},
    {id:"rejected",label:"Rejected",color:"var(--red)"},
  ];
  return `
  <div style="margin-bottom:14px;display:flex;align-items:center;gap:10px">
    <select class="fb-select" id="pipelineJob">
      <option value="">All Jobs</option>
      ${S.jobs.map(j=>`<option value="${j._id}" ${S.jobFilter===j._id?"selected":""}>${j.title}</option>`).join("")}
    </select>
    <span style="font-size:12px;color:var(--text4)">${S.candidates.length} candidates total</span>
  </div>
  <div class="kanban">
    ${stages.map(({id,label,color})=>{
      const cands=filtered().filter(c=>(c.status||"sourced")===id);
      return `<div class="k-col">
        <div class="k-header" style="border-top:2px solid ${color}">
          <span class="k-title">${label}</span>
          <span class="k-count">${cands.length}</span>
        </div>
        <div class="k-body">
          ${cands.slice(0,15).map(c=>`
          <div class="k-card cand-row" data-id="${c._id}">
            <div class="k-name">${fmt(c.name)}</div>
            <div class="k-sub">${fmt(c.currentTitle,"—")} · ${exp(c)}</div>
            <div style="margin-top:5px;display:flex;gap:3px;flex-wrap:wrap">
              ${(c.skills||[]).slice(0,2).map(s=>`<span class="chip chip-gray" style="font-size:9px">${s}</span>`).join("")}
            </div>
          </div>`).join("")}
          ${cands.length===0?`<div style="text-align:center;padding:20px;font-size:12px;color:var(--text4)">Empty</div>`:""}
        </div>
      </div>`;
    }).join("")}
  </div>`;
}

// ── TALENT POOL ───────────────────────────────────────────────────────────
function talentHTML(){
  const shortlisted=S.candidates.filter(c=>(c.status||"sourced")==="shortlisted");
  const highExp=S.candidates.filter(c=>c.experienceYears>=5);
  const fresh=S.candidates.filter(c=>Date.now()-new Date(c._creationTime||c.createdAt||0)<7*86400000);
  const pools=[
    {name:"Shortlisted Talent",icon:"⭐",cands:shortlisted,color:"var(--accent)"},
    {name:"Senior Professionals",icon:"🏆",cands:highExp,color:"var(--purple)"},
    {name:"Recent Imports",icon:"🆕",cands:fresh,color:"var(--green)"},
  ];
  return `
  <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-bottom:20px">
    ${pools.map(p=>`
    <div class="card" style="padding:18px;cursor:pointer">
      <div style="font-size:24px;margin-bottom:8px">${p.icon}</div>
      <div style="font-family:'Instrument Serif',serif;font-size:16px;font-style:italic;color:var(--text);margin-bottom:4px">${p.name}</div>
      <div style="font-family:'Instrument Serif',serif;font-size:28px;color:${p.color}">${p.cands.length}</div>
      <div style="font-size:11px;color:var(--text4);margin-top:2px">candidates</div>
    </div>`).join("")}
  </div>
  <div class="card">
    <div class="card-header"><div class="card-title">Shortlisted Candidates</div></div>
    ${shortlisted.length===0?`<div class="empty"><div class="empty-icon">⭐</div><div class="empty-title">No shortlisted candidates</div><div class="empty-sub">Move candidates to 'Shortlisted' status in the pipeline</div></div>`:`
    <div class="table-wrap"><table>
      <thead><tr><th>Name</th><th>Role</th><th>Experience</th><th>Location</th><th>Skills</th></tr></thead>
      <tbody>
        ${shortlisted.map(c=>`
        <tr class="cand-row" data-id="${c._id}">
          <td><div class="td-name">${fmt(c.name)}</div><div class="td-sub td-mono">${fmt(c.email)}</div></td>
          <td><div style="font-size:12px">${fmt(c.currentTitle)}</div><div class="td-sub">${fmt(c.currentCompany)}</div></td>
          <td><span class="chip chip-blue">${exp(c)}</span></td>
          <td><span style="font-size:12px;color:var(--text2)">${fmt(c.location)}</span></td>
          <td><div style="display:flex;gap:3px">${(c.skills||[]).slice(0,3).map(s=>`<span class="chip chip-orange" style="font-size:10px">${s}</span>`).join("")}</div></td>
        </tr>`).join("")}
      </tbody>
    </table></div>`}
  </div>`;
}

// ── ANALYTICS ─────────────────────────────────────────────────────────────
function analyticsHTML(){
  const stages=["sourced","screening","shortlisted","contacted","rejected"];
  const counts=stages.map(s=>S.candidates.filter(c=>(c.status||"sourced")===s).length);
  const maxC=Math.max(...counts,1);
  const jobData=S.jobs.map(j=>({name:j.title,count:S.candidates.filter(c=>c.jobId===j._id).length})).sort((a,b)=>b.count-a.count).slice(0,5);

  const now=Date.now(); const day=86400000;
  const trend=Array.from({length:7},(_,i)=>{
    const d=new Date(now-(6-i)*day); const ds=d.toDateString();
    return {d:d.toLocaleDateString("en",{weekday:"short"}),n:S.candidates.filter(c=>new Date(c._creationTime||c.createdAt||0).toDateString()===ds).length};
  });
  const maxT=Math.max(...trend.map(t=>t.n),1);

  return `
  <div class="stats-row">
    ${statCard("","📊",S.stats.total,"Total Candidates","")}
    ${statCard("green","✅",counts[2],"Shortlisted",Math.round(counts[2]/Math.max(S.stats.total,1)*100)+"% rate")}
    ${statCard("blue","📧",counts[3],"Contacted","")}
    ${statCard("purple","💼",S.stats.jobs,"Active Jobs","")}
  </div>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
    <div class="chart-box">
      <div class="card-title">Hiring Funnel</div>
      <div class="bar-chart">
        ${stages.map((s,i)=>`<div style="display:flex;flex-direction:column;align-items:center;flex:1;gap:4px">
          <div style="font-size:10px;color:var(--text3)">${counts[i]}</div>
          <div class="bar" style="height:${Math.round(counts[i]/maxC*100)}%;background:var(--accent);opacity:${0.4+0.6*(1-i/stages.length)}"></div>
          <div style="font-size:9px;color:var(--text4);text-transform:capitalize">${s.slice(0,5)}</div>
        </div>`).join("")}
      </div>
    </div>
    <div class="chart-box">
      <div class="card-title">Imports — Last 7 Days</div>
      <div class="bar-chart">
        ${trend.map(t=>`<div style="display:flex;flex-direction:column;align-items:center;flex:1;gap:4px">
          <div style="font-size:10px;color:var(--text3)">${t.n}</div>
          <div class="bar" style="height:${Math.round(t.n/maxT*100)}%;background:var(--blue)"></div>
          <div style="font-size:9px;color:var(--text4)">${t.d}</div>
        </div>`).join("")}
      </div>
    </div>
    <div class="chart-box">
      <div class="card-title" style="margin-bottom:12px">Candidates by Job</div>
      ${jobData.length===0?`<div style="color:var(--text4);font-size:12px">No data</div>`:""}
      ${jobData.map(j=>`
      <div style="display:flex;align-items:center;gap:10px;margin-bottom:8px">
        <div style="font-size:12px;color:var(--text2);flex:1;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${j.name}</div>
        <div style="flex:0 0 120px;height:6px;background:var(--bg4);border-radius:3px;overflow:hidden">
          <div style="height:100%;background:var(--purple);width:${Math.round(j.count/Math.max(...jobData.map(x=>x.count),1)*100)}%"></div>
        </div>
        <div style="font-size:11px;color:var(--text3);width:24px;text-align:right">${j.count}</div>
      </div>`).join("")}
    </div>
    <div class="chart-box">
      <div class="card-title" style="margin-bottom:12px">Source Breakdown</div>
      <div style="display:flex;flex-direction:column;gap:8px">
        ${[["Naukri Extension","var(--accent)",S.candidates.filter(c=>c.source==="naukri"||!c.source).length],
           ["LinkedIn","var(--blue)",S.candidates.filter(c=>c.source==="linkedin").length],
           ["Manual","var(--green)",S.candidates.filter(c=>c.source==="manual").length]
          ].map(([src,col,n])=>`
        <div style="display:flex;align-items:center;gap:8px">
          <div style="width:10px;height:10px;border-radius:50%;background:${col};flex-shrink:0"></div>
          <div style="font-size:12px;color:var(--text2);flex:1">${src}</div>
          <span class="chip chip-gray" style="font-size:10px">${n}</span>
        </div>`).join("")}
      </div>
    </div>
  </div>`;
}

// ── AI COPILOT ────────────────────────────────────────────────────────────
function aiHTML(){
  return `
  <div style="max-width:700px">
    <div class="ai-box" style="margin-bottom:20px">
      <div class="ai-label">✨ AI Copilot</div>
      <div class="ai-text">AI Copilot connects to your candidate data and helps you make better hiring decisions. Ask about candidates, compare profiles, or get recommendations.</div>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:20px">
      ${[["Who are the most experienced candidates?","👥"],["Summarise all shortlisted candidates","⭐"],["Which candidates have the shortest notice period?","⏱"],["Which job has the most candidates?","💼"]].map(([q,i])=>`
      <button class="card" style="padding:14px;text-align:left;cursor:pointer;transition:border-color .12s" id="aiQ" data-q="${q}">
        <div style="font-size:16px;margin-bottom:5px">${i}</div>
        <div style="font-size:12px;color:var(--text2)">${q}</div>
      </button>`).join("")}
    </div>
    <div class="card" style="margin-bottom:16px">
      <div style="padding:14px;display:flex;gap:8px">
        <input class="form-input" id="aiInput" placeholder="Ask anything about your candidates or jobs…" style="flex:1"/>
        <button class="btn btn-primary" id="aiSend">Ask AI</button>
      </div>
      <div id="aiResponse" style="padding:0 14px 14px;font-size:13px;color:var(--text2);line-height:1.65;display:none"></div>
    </div>
  </div>`;
}

// ── SETTINGS ──────────────────────────────────────────────────────────────
function settingsHTML(){ return `
  <div style="max-width:540px">
    <div class="settings-section">
      <div class="settings-title">🔑 Auth Token</div>
      <input class="form-input" id="settingsTok" type="password" value="${S.token}" style="margin-bottom:10px"/>
      <button class="btn btn-primary btn-sm" id="saveTok">Save Token</button>
    </div>
    <div class="settings-section">
      <div class="settings-title">✨ Grok AI Key <span style="font-size:11px;color:var(--green);margin-left:6px">${S.grokKey?"● Connected":"○ Not set"}</span></div>
      <div style="font-size:12px;color:var(--text3);margin-bottom:10px">Used for AI candidate scoring. Get your key from <a href="https://console.x.ai" target="_blank" style="color:var(--accent)">console.x.ai</a></div>
      <input class="form-input" id="grokKeyInput" type="password" placeholder="gsk_…" value="${S.grokKey}" style="margin-bottom:10px"/>
      <div style="display:flex;gap:8px">
        <button class="btn btn-primary btn-sm" id="saveGrok">Save Grok Key</button>
        <button class="btn btn-ghost btn-sm" id="testGrok">Test Connection</button>
      </div>
      <div id="grokTestRes" style="font-size:12px;margin-top:8px"></div>
    </div>
    <div class="settings-section">
      <div class="settings-title">⚡ Connection Test</div>
      <button class="btn btn-secondary btn-sm" id="testConn" style="margin-bottom:10px">Run Test</button>
      <div id="testRes" style="font-size:13px"></div>
    </div>
    <div class="settings-section">
      <div class="settings-title">📡 API Endpoints</div>
      <div style="font-size:11px;color:var(--text4);margin-bottom:6px">Backend URL</div>
      <div class="code-block">${API}<button class="copy-btn" onclick="navigator.clipboard.writeText('${API}').then(()=>toast('Copied!','ok'))">Copy</button></div>
    </div>
    <div class="settings-section">
      <div class="settings-title">⚙️ Extension Setup</div>
      <div style="font-size:13px;color:var(--text2);line-height:1.7;margin-bottom:10px">
        1. Install the Chrome extension from your project folder<br>
        2. Click the extension icon → paste your token → Verify → select a job → Save<br>
        3. Go to resdex.naukri.com → search → check candidates → Import Selected<br>
        4. Candidates appear here automatically
      </div>
    </div>
    <div class="settings-section">
      <div class="settings-title" style="color:var(--red)">⚠ Danger Zone</div>
      <button class="btn btn-danger btn-sm" id="logoutBtn2">Sign Out</button>
    </div>
  </div>`; }

// ── BIND ───────────────────────────────────────────────────────────────────
function bindShell(){
  // Nav
  document.querySelectorAll("[data-nav]").forEach(el=>el.onclick=()=>{S.page=el.dataset.nav;render()});

  // Sidebar toggle
  const tog=document.getElementById("sidebarToggle");
  const sb=document.getElementById("sidebar");
  if(tog) tog.onclick=()=>{ sb.classList.toggle("collapsed"); tog.textContent=sb.classList.contains("collapsed")?"▶":"◀"; };

  // Topbar
  const gb=document.getElementById("globalSearch");
  if(gb){ gb.oninput=e=>{S.search=e.target.value;S.cPage=1;render()}; gb.onfocus=()=>{if(S.page!=="candidates"){S.page="candidates";render()}} }
  const rb=document.getElementById("refreshBtn");
  if(rb) rb.onclick=()=>loadCandidates();
  const njb=document.getElementById("newJobBtn")||document.getElementById("newJobBtn2");
  if(njb) njb.onclick=()=>{S.showNewJob=true;render()};
  const lo=document.getElementById("logoutBtn");
  if(lo) lo.onclick=logout;

  // Candidate rows
  document.querySelectorAll(".cand-row[data-id]").forEach(r=>r.onclick=()=>{S.selectedCand=S.candidates.find(c=>c._id===r.dataset.id)||null;S.candTab="overview";render()});

  // Candidate modal
  ["closeCand","closeCand2"].forEach(id=>{const el=document.getElementById(id);if(el)el.onclick=()=>{S.selectedCand=null;render()}});
  const co=document.getElementById("candOverlay");
  if(co) co.onclick=e=>{if(e.target===co){S.selectedCand=null;render()}};

  // Tabs
  document.querySelectorAll("[data-tab]").forEach(t=>t.onclick=()=>{S.candTab=t.dataset.tab;render()});

  // Status change
  const ss=document.getElementById("statusSelect");
  if(ss) ss.onchange=async e=>{
    S.selectedCand={...S.selectedCand,status:e.target.value};
    S.candidates=S.candidates.map(c=>c._id===S.selectedCand._id?{...c,status:e.target.value}:c);
    toast("Status updated","ok"); render();
  };

  // Delete candidate
  const dc=document.getElementById("delCandBtn");
  if(dc) dc.onclick=()=>{if(confirm("Remove "+S.selectedCand?.name+"?")){const id=S.selectedCand._id;S.candidates=S.candidates.filter(c=>c._id!==id);S.selectedCand=null;toast("Removed","inf");render()}};

  // Notes
  const an=document.getElementById("addNoteBtn");
  if(an) an.onclick=()=>{
    const txt=document.getElementById("noteInput").value.trim();
    if(!txt) return;
    const cid=S.selectedCand._id;
    if(!S.notes[cid]) S.notes[cid]=[];
    S.notes[cid].unshift({text:txt,ts:Date.now()});
    render();
  };

  // Filters
  const cs=document.getElementById("candSearch");
  if(cs){ cs.oninput=e=>{S.search=e.target.value;S.cPage=1;render()};  setTimeout(()=>{if(cs) cs.focus()},50); }
  const cj=document.getElementById("candJob");
  if(cj){ cj.value=S.jobFilter;cj.onchange=e=>{S.jobFilter=e.target.value;S.cPage=1;render()} }
  const cst=document.getElementById("candStatus");
  if(cst){ cst.value=S.statusFilter;cst.onchange=e=>{S.statusFilter=e.target.value;S.cPage=1;render()} }

  // Pipeline job filter
  const pj=document.getElementById("pipelineJob");
  if(pj){ pj.value=S.jobFilter;pj.onchange=e=>{S.jobFilter=e.target.value;render()} }

  // Pagination
  const pp=document.getElementById("prevPage");
  if(pp) pp.onclick=()=>{S.cPage--;render()};
  const np=document.getElementById("nextPage");
  if(np) np.onclick=()=>{S.cPage++;render()};
  document.querySelectorAll("[data-pg]").forEach(b=>b.onclick=()=>{S.cPage=parseInt(b.dataset.pg);render()});

  // Jobs
  document.querySelectorAll("[data-jid]").forEach(el=>el.onclick=()=>{S.selectedJob=S.jobs.find(j=>j._id===el.dataset.jid)||null;render()});
  document.querySelectorAll("[data-filterjob]").forEach(b=>b.onclick=e=>{e.stopPropagation();S.jobFilter=b.dataset.filterjob;S.page="candidates";render()});

  // New job modal
  ["closeNJ","closeNJ2"].forEach(id=>{const el=document.getElementById(id);if(el)el.onclick=()=>{S.showNewJob=false;render()}});
  const njo=document.getElementById("newJobOverlay");
  if(njo) njo.onclick=e=>{if(e.target===njo){S.showNewJob=false;render()}};
  const snj=document.getElementById("submitNJ");
  if(snj) snj.onclick=async()=>{
    const t=document.getElementById("nj_title").value.trim();
    if(!t){toast("Title required","err");return}
    snj.disabled=true;snj.textContent="Creating…";
    try{await createJob({title:t,location:document.getElementById("nj_loc").value.trim(),department:document.getElementById("nj_dept").value.trim(),description:document.getElementById("nj_desc").value.trim()});S.showNewJob=false;render();}
    catch(e){toast("Failed: "+e.message,"err");snj.disabled=false;snj.textContent="Create Job →"}
  };

  // AI Shortlist button
  const aisb=document.getElementById("aiScreenBtn");
  if(aisb) aisb.onclick=()=>{S.showScreen=true;S.screenStep=0;S.screenJobId=S.jobFilter||"";render()};

  // Screen modal bindings
  ["closeScreen","closeScreen2","closeScreen3"].forEach(id=>{const el=document.getElementById(id);if(el)el.onclick=()=>{S.showScreen=false;render()}});
  const sco=document.getElementById("screenOverlay");
  if(sco) sco.onclick=e=>{if(e.target===sco&&S.screenStep!==1){S.showScreen=false;render()}};

  const startBtn=document.getElementById("startScreen");
  if(startBtn) startBtn.onclick=async()=>{
    const jobId=document.getElementById("sc_job")?.value||"";
    if(!jobId){toast("Please select a job","err");return}
    S.screenJobId=jobId;
    S.screenCriteria={
      minExp: parseFloat(document.getElementById("sc_exp")?.value)||0,
      skills: document.getElementById("sc_skills")?.value||"",
      maxSalary: parseFloat(document.getElementById("sc_sal")?.value)||"",
      location: document.getElementById("sc_loc")?.value||"",
      notes: document.getElementById("sc_notes")?.value||"",
    };
    // Get candidates for this job
    S.screenQueue = S.candidates.filter(c=>c.jobId===jobId||!jobId);
    if(S.screenQueue.length===0){toast("No candidates to score for this job","err");return}
    S.screenStep=1; S.screenResults=[]; S.screenDone=0; S.screenProgress=0; S.screenCurrent="";
    render();
    // Score candidates in batches (non-blocking)
    for(let i=0;i<S.screenQueue.length;i++){
      const c=S.screenQueue[i];
      S.screenCurrent=c.name;
      await new Promise(res=>setTimeout(res,30)); // small delay for UI update
      const result=scoreCandidate(c,S.screenCriteria);
      S.screenResults.push(result);
      S.screenDone=i+1;
      S.screenProgress=Math.round((i+1)/S.screenQueue.length*100);
      // Update progress bar without full re-render
      const bar=document.getElementById("scoreBar");
      if(bar) bar.style.width=S.screenProgress+"%";
      const prog=document.querySelector("#screenOverlay [style*='scored']");
      if(prog) prog.textContent=S.screenDone+" / "+S.screenQueue.length+" scored";
    }
    S.screenStep=2; render();
  };

  // Approve all recommended
  const appAll=document.getElementById("approveAll");
  if(appAll) appAll.onclick=()=>{
    S.screenResults=S.screenResults.map(r=>({...r,approved:r.score>=60}));
    render();
  };
  const appAllChk=document.getElementById("approveAllChk");
  if(appAllChk) appAllChk.onchange=e=>{
    S.screenResults=S.screenResults.map(r=>({...r,approved:e.target.checked}));
    render();
  };

  // Individual approve checkboxes
  document.querySelectorAll(".approve-chk").forEach(chk=>{
    chk.onchange=e=>{
      const id=e.target.dataset.id;
      S.screenResults=S.screenResults.map(r=>r.id===id?{...r,approved:e.target.checked}:r);
    };
  });

  // Apply selections — move approved to shortlisted
  const applyBtn=document.getElementById("applyScreen");
  if(applyBtn) applyBtn.onclick=()=>{
    const approved=S.screenResults.filter(r=>r.approved).map(r=>r.id);
    S.candidates=S.candidates.map(c=>
      approved.includes(c._id)?{...c,status:"shortlisted"}:c
    );
    toast(`✓ ${approved.length} candidates shortlisted`,"ok");
    S.showScreen=false; render();
  };

  // Settings
  const st=document.getElementById("saveTok");
  if(st) st.onclick=()=>{const v=document.getElementById("settingsTok").value.trim();if(!v)return;S.token=clean(v);localStorage.setItem("rk_token",S.token);toast("Token saved","ok")};

  const sg=document.getElementById("saveGrok");
  if(sg) sg.onclick=()=>{
    const v=document.getElementById("grokKeyInput").value.trim();
    S.grokKey=v; localStorage.setItem("rk_grok",v);
    toast(v?"Grok key saved ✓":"Grok key cleared","ok"); render();
  };

  const tg=document.getElementById("testGrok");
  if(tg) tg.onclick=async()=>{
    const key=document.getElementById("grokKeyInput").value.trim()||S.grokKey;
    const res=document.getElementById("grokTestRes");
    if(!key){res.innerHTML=`<span style="color:var(--red)">No key entered</span>`;return}
    tg.disabled=true;tg.textContent="Testing…";
    try{
      const r=await fetch("https://api.x.ai/v1/chat/completions",{
        method:"POST",
        headers:{"Content-Type":"application/json","Authorization":"Bearer "+key},
        body:JSON.stringify({model:"grok-3-mini",messages:[{role:"user",content:"Say OK"}],max_tokens:5}),
      });
      if(r.ok){res.innerHTML=`<span style="color:var(--green)">✓ Grok connected! Key is valid.</span>`;}
      else{const e=await r.json().catch(()=>({}));res.innerHTML=`<span style="color:var(--red)">✕ ${e.error?.message||"HTTP "+r.status}</span>`;}
    }catch(e){res.innerHTML=`<span style="color:var(--red)">✕ ${e.message}</span>`;}
    tg.disabled=false;tg.textContent="Test Connection";
  };
  const tc=document.getElementById("testConn");
  if(tc) tc.onclick=async()=>{
    tc.disabled=true;tc.textContent="Testing…";
    const res=document.getElementById("testRes");
    try{const d=await api("/ext/jobs");res.innerHTML=`<span style="color:var(--green)">✓ Connected! ${(d.jobs||[]).length} jobs found.</span>`}
    catch(e){res.innerHTML=`<span style="color:var(--red)">✕ ${e.message}</span>`}
    tc.disabled=false;tc.textContent="Run Test";
  };
  const lo2=document.getElementById("logoutBtn2");
  if(lo2) lo2.onclick=logout;

  // AI
  document.querySelectorAll("[id=aiQ]").forEach(b=>b.onclick=()=>{
    document.getElementById("aiInput").value=b.dataset.q;
    document.getElementById("aiSend")?.click();
  });
  const ais=document.getElementById("aiSend");
  if(ais) ais.onclick=async()=>{
    const q=document.getElementById("aiInput").value.trim();
    if(!q) return;
    const res=document.getElementById("aiResponse");
    res.style.display="block";
    res.innerHTML="<em>Thinking…</em>";
    ais.disabled=true;
    try{
      // Simple local AI using candidate data — no external API needed
      const answer=localAI(q);
      res.innerHTML=answer;
    } catch(e){ res.innerHTML="<span style='color:var(--red)'>Error: "+e.message+"</span>"; }
    ais.disabled=false;
  };
}

function localAI(q){
  const ql=q.toLowerCase();
  const cands=S.candidates;
  if(ql.includes("experi")){
    const top=[...cands].sort((a,b)=>(b.experienceYears||0)-(a.experienceYears||0)).slice(0,5);
    return "<strong>Top candidates by experience:</strong><br>"+top.map(c=>`• ${c.name} — ${c.experienceYears||"?"}y (${c.currentTitle||"—"})`).join("<br>");
  }
  if(ql.includes("notice")||ql.includes("availab")){
    const np=cands.filter(c=>raw(c).noticePeriod).map(c=>({name:c.name,np:raw(c).noticePeriod}));
    if(!np.length) return "No notice period data found for current candidates.";
    return "<strong>Notice periods:</strong><br>"+np.slice(0,10).map(x=>`• ${x.name} — ${x.np}`).join("<br>");
  }
  if(ql.includes("shortlist")){
    const sl=cands.filter(c=>(c.status||"sourced")==="shortlisted");
    if(!sl.length) return "No shortlisted candidates yet.";
    return `<strong>${sl.length} shortlisted candidates:</strong><br>`+sl.map(c=>`• ${c.name} — ${c.currentTitle||"—"} (${c.experienceYears||"?"}y exp)`).join("<br>");
  }
  if(ql.includes("job")||ql.includes("which job")){
    const jd=S.jobs.map(j=>({title:j.title,count:cands.filter(c=>c.jobId===j._id).length})).sort((a,b)=>b.count-a.count);
    return "<strong>Jobs by candidate count:</strong><br>"+jd.map(j=>`• ${j.title} — ${j.count} candidates`).join("<br>");
  }
  // Generic summary
  const sl=cands.filter(c=>c.status==="shortlisted").length;
  return `<strong>Workspace Summary:</strong><br>• ${cands.length} total candidates<br>• ${S.jobs.length} active jobs<br>• ${sl} shortlisted<br>• ${S.stats.today} added today<br><br>Try asking: "Who has the most experience?" or "Show shortlisted candidates"`;
}

function logout(){
  localStorage.removeItem("rk_token"); S.token=""; S.candidates=[]; S.jobs=[]; render();
}

// ── AI SCREENING ──────────────────────────────────────────────────────────
function aiScreenModalHTML(){
  const job = S.jobs.find(j=>j._id===S.screenJobId);
  return `<div class="overlay" id="screenOverlay">
  <div class="modal" style="width:860px">
    <div class="modal-header">
      <div>
        <div class="modal-title">✨ AI Shortlisting</div>
        <div style="font-size:12px;color:var(--text3);margin-top:2px">AI scores candidates · You approve</div>
      </div>
      <button class="close-btn" id="closeScreen">✕</button>
    </div>
    <div class="modal-body" style="padding:0">

      ${S.screenStep===0?`
      <!-- Step 0: Configure criteria -->
      <div style="padding:22px">
        <div style="font-size:13px;color:var(--text2);margin-bottom:16px">
          Tell the AI what you're looking for. It will score all candidates and suggest who to shortlist.
        </div>
        <div class="form-grid" style="margin-bottom:12px">
          <div class="form-group">
            <label class="form-label">Job *</label>
            <select class="form-select" id="sc_job">
              <option value="">Select job…</option>
              ${S.jobs.map(j=>`<option value="${j._id}" ${S.screenJobId===j._id?"selected":""}>${j.title}</option>`).join("")}
            </select>
          </div>
          <div class="form-group">
            <label class="form-label">Min Experience (years)</label>
            <input class="form-input" id="sc_exp" type="number" min="0" max="30" value="${S.screenCriteria.minExp||0}" placeholder="0"/>
          </div>
        </div>
        <div class="form-group">
          <label class="form-label">Required Skills (comma separated)</label>
          <input class="form-input" id="sc_skills" value="${S.screenCriteria.skills||""}" placeholder="e.g. Inside Sales, CRM, B2B, Lead Generation"/>
        </div>
        <div class="form-grid">
          <div class="form-group">
            <label class="form-label">Max Salary (Lacs)</label>
            <input class="form-input" id="sc_sal" type="number" min="0" value="${S.screenCriteria.maxSalary||""}" placeholder="e.g. 8"/>
          </div>
          <div class="form-group">
            <label class="form-label">Preferred Locations</label>
            <input class="form-input" id="sc_loc" value="${S.screenCriteria.location||""}" placeholder="Mumbai, Navi Mumbai…"/>
          </div>
        </div>
        <div class="form-group">
          <label class="form-label">Additional Instructions</label>
          <textarea class="form-textarea" id="sc_notes" placeholder="e.g. Prefer candidates from pharma industry, must have B2B experience…" style="min-height:60px">${S.screenCriteria.notes||""}</textarea>
        </div>
      </div>
      `:``}

      ${S.screenStep===1?`
      <!-- Step 1: Scoring in progress -->
      <div style="padding:40px;text-align:center">
        <div style="font-size:36px;margin-bottom:14px">✨</div>
        <div style="font-family:'Instrument Serif',sans-serif;font-size:18px;font-style:italic;color:var(--text);margin-bottom:8px">Scoring ${S.screenQueue.length} candidates…</div>
        <div style="font-size:13px;color:var(--text3);margin-bottom:20px">Analysing skills, experience, salary, and location fit</div>
        <div style="background:var(--bg4);border-radius:4px;height:6px;overflow:hidden;max-width:300px;margin:0 auto 12px">
          <div id="scoreBar" style="height:100%;background:var(--accent);border-radius:4px;transition:width .3s;width:${S.screenProgress}%"></div>
        </div>
        <div style="font-size:12px;color:var(--text4)">${S.screenDone} / ${S.screenQueue.length} scored</div>
        ${S.screenCurrent?`<div style="font-size:12px;color:var(--text2);margin-top:6px">Scoring: ${S.screenCurrent}</div>`:""}
      </div>
      `:``}

      ${S.screenStep===2?`
      <!-- Step 2: Results — approve/reject -->
      <div style="padding:14px 18px;border-bottom:1px solid var(--border);display:flex;align-items:center;gap:10px;flex-wrap:wrap">
        <div style="font-size:13px;color:var(--text2)"><strong style="color:var(--text)">${S.screenResults.filter(r=>r.score>=60).length}</strong> recommended · <strong style="color:var(--text)">${S.screenResults.length}</strong> total scored</div>
        <div style="margin-left:auto;display:flex;gap:8px">
          <button class="btn btn-ghost btn-sm" id="approveAll">✓ Approve All Recommended</button>
          <button class="btn btn-primary btn-sm" id="applyScreen">Apply Selections</button>
        </div>
      </div>
      <div style="overflow-y:auto;max-height:420px">
        <table style="width:100%;border-collapse:collapse">
          <thead><tr>
            <th style="text-align:left;padding:8px 16px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border)">
              <input type="checkbox" id="approveAllChk"/>
            </th>
            <th style="text-align:left;padding:8px 16px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border)">Candidate</th>
            <th style="text-align:left;padding:8px 16px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border)">AI Score</th>
            <th style="text-align:left;padding:8px 16px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border)">Fit Analysis</th>
            <th style="text-align:left;padding:8px 16px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.7px;color:var(--text4);background:var(--bg);border-bottom:1px solid var(--border)">Verdict</th>
          </tr></thead>
          <tbody>
            ${[...S.screenResults].sort((a,b)=>b.score-a.score).map(r=>`
            <tr style="border-bottom:1px solid var(--border)">
              <td style="padding:10px 16px">
                <input type="checkbox" class="approve-chk" data-id="${r.id}" ${r.approved?"checked":""}/>
              </td>
              <td style="padding:10px 16px">
                <div style="font-weight:600;font-size:13px;color:var(--text)">${r.name}</div>
                <div style="font-size:11px;color:var(--text3)">${r.title||"—"} · ${r.exp!==null?r.exp+"y":""}</div>
              </td>
              <td style="padding:10px 16px">
                <div style="display:flex;align-items:center;gap:8px">
                  <div style="width:44px;height:44px;border-radius:50%;background:${r.score>=70?"var(--greendim)":r.score>=50?"var(--yellowdim)":"var(--reddim)"};border:2px solid ${r.score>=70?"var(--green)":r.score>=50?"var(--yellow)":"var(--red)"};display:flex;align-items:center;justify-content:center;font-family:'Instrument Serif',serif;font-size:16px;font-weight:700;color:${r.score>=70?"var(--green)":r.score>=50?"var(--yellow)":"var(--red)"}">${r.score}</div>
                  <div>
                    <div style="font-size:10px;color:var(--text4)">Skills</div>
                    <div style="width:60px;height:3px;background:var(--bg4);border-radius:2px;overflow:hidden;margin-top:2px"><div style="height:100%;background:var(--accent);width:${r.skillScore||0}%"></div></div>
                    <div style="font-size:10px;color:var(--text4);margin-top:3px">Exp</div>
                    <div style="width:60px;height:3px;background:var(--bg4);border-radius:2px;overflow:hidden;margin-top:2px"><div style="height:100%;background:var(--blue);width:${r.expScore||0}%"></div></div>
                  </div>
                </div>
              </td>
              <td style="padding:10px 16px;max-width:240px">
                <div style="font-size:11px;color:var(--text2);line-height:1.5">${r.reason}</div>
                ${r.missing?`<div style="font-size:10px;color:var(--red);margin-top:3px">Missing: ${r.missing}</div>`:""}
              </td>
              <td style="padding:10px 16px">
                <span class="chip ${r.score>=70?"chip-green":r.score>=50?"chip-yellow":"chip-red"}">${r.score>=70?"✓ Recommend":r.score>=50?"Maybe":"Skip"}</span>
              </td>
            </tr>`).join("")}
          </tbody>
        </table>
      </div>
      `:``}

    </div>
    <div class="modal-footer">
      ${S.screenStep===0?`
        <button class="btn btn-secondary btn-sm" id="closeScreen2">Cancel</button>
        <button class="btn btn-primary btn-sm" id="startScreen">Score Candidates →</button>
      `:``}
      ${S.screenStep===2?`
        <div style="font-size:12px;color:var(--text3);margin-right:auto">${S.screenResults.filter(r=>r.approved).length} selected for shortlisting</div>
        <button class="btn btn-secondary btn-sm" id="closeScreen3">Close</button>
      `:``}
    </div>
  </div>
</div>`;
}

// ── AI SCORING ENGINE — powered by Grok ────────────────────────────────────
// Falls back to rule-based scoring if Grok key not set or call fails
function scoreCandidateLocal(c, criteria){
  const r = raw(c);
  const skills = [...(c.skills||[]), ...(r.keySkills||[])].map(s=>s.toLowerCase());
  const reqSkills = (criteria.skills||"").split(",").map(s=>s.trim().toLowerCase()).filter(Boolean);
  const candExp = c.experienceYears ?? 0;
  const minExp = parseFloat(criteria.minExp)||0;
  const maxSal = parseFloat(criteria.maxSalary)||999;
  const prefLocs = (criteria.location||"").split(",").map(s=>s.trim().toLowerCase()).filter(Boolean);
  const candLoc = (c.location||"").toLowerCase();
  const salaryStr = r.salary||c.salary||"";
  const salNum = parseFloat((salaryStr.match(/\d+\.?\d*/)||[])[0])||0;

  let skillScore = reqSkills.length===0?70:Math.round((reqSkills.filter(rs=>skills.some(cs=>cs.includes(rs)||rs.includes(cs))).length/reqSkills.length)*100);
  let expScore = minExp===0?80:candExp>=minExp?100:candExp>=minExp-1?70:candExp>=minExp*0.7?40:10;
  let salScore = (maxSal<999&&salNum>0)?(salNum<=maxSal?100:salNum<=maxSal*1.2?60:20):100;
  let locScore = prefLocs.length===0?60:prefLocs.some(pl=>candLoc.includes(pl)||pl.includes(candLoc.split(",")[0]))?100:20;
  const overall = Math.round(skillScore*0.45+expScore*0.3+salScore*0.15+locScore*0.1);
  const missing = reqSkills.filter(rs=>!skills.some(cs=>cs.includes(rs)||rs.includes(cs))).slice(0,3).join(", ");
  const parts=[];
  if(skillScore>=80)parts.push("Strong skill match");else if(skillScore>=50)parts.push("Partial skill match");else parts.push("Weak skill match");
  if(minExp>0){if(candExp>=minExp)parts.push(candExp+"y exp meets requirement");else parts.push("Only "+candExp+"y exp (need "+minExp+"y)");}
  if(salScore<60&&maxSal<999)parts.push("Salary above budget");
  if(locScore===100)parts.push("Location matches");else if(locScore<40&&prefLocs.length>0)parts.push("Location mismatch");
  return {id:c._id,name:c.name,title:c.currentTitle,exp:candExp,score:overall,skillScore,expScore,salScore,locScore,reason:parts.join(" · "),missing,approved:overall>=60};
}

async function scoreCandidateGrok(c, criteria, apiKey){
  const r = raw(c);
  const profile = {
    name: c.name,
    currentTitle: c.currentTitle||"",
    currentCompany: c.currentCompany||"",
    experienceYears: c.experienceYears??0,
    skills: [...(c.skills||[]),...(r.keySkills||[])],
    location: c.location||"",
    salary: r.salary||c.salary||"",
    noticePeriod: r.noticePeriod||c.noticePeriod||"",
    summary: c.summary||r.workSummary||"",
    aiSummary: c.aiSummary||r.aiSummary||"",
  };
  const prompt = `You are a recruitment AI. Score this candidate for the job opening.

JOB REQUIREMENTS:
- Min Experience: ${criteria.minExp||0} years
- Required Skills: ${criteria.skills||"Not specified"}
- Max Salary Budget: ${criteria.maxSalary?criteria.maxSalary+" Lacs":"Not specified"}
- Preferred Location: ${criteria.location||"Not specified"}
- Additional Notes: ${criteria.notes||"None"}

CANDIDATE PROFILE:
${JSON.stringify(profile, null, 2)}

Respond ONLY with a valid JSON object (no markdown, no explanation) in this exact format:
{"score":85,"skillScore":90,"expScore":80,"salScore":100,"locScore":70,"reason":"Strong B2B sales background with CRM experience · Meets experience requirement","missing":"Lead Generation","verdict":"Recommend","strengths":"3 years B2B sales, strong communication","concerns":"No pharma industry experience"}

Score 0-100. Be strict and honest.`;

  const res = await fetch("https://api.x.ai/v1/chat/completions", {
    method: "POST",
    headers: {
      "Content-Type": "application/json",
      "Authorization": "Bearer " + apiKey,
    },
    body: JSON.stringify({
      model: "grok-3-mini",
      messages: [{ role: "user", content: prompt }],
      temperature: 0.1,
      max_tokens: 300,
    }),
  });

  if(!res.ok){
    const err = await res.text().catch(()=>"");
    throw new Error("Grok API "+res.status+": "+err.slice(0,100));
  }

  const data = await res.json();
  const text = data.choices?.[0]?.message?.content || "";

  // Parse JSON response
  const clean = text.replace(/```json?/g,"").replace(/```/g,"").trim();
  const parsed = JSON.parse(clean);

  return {
    id: c._id,
    name: c.name,
    title: c.currentTitle,
    exp: c.experienceYears??0,
    score: Math.min(100,Math.max(0,parseInt(parsed.score)||0)),
    skillScore: Math.min(100,Math.max(0,parseInt(parsed.skillScore)||0)),
    expScore: Math.min(100,Math.max(0,parseInt(parsed.expScore)||0)),
    salScore: Math.min(100,Math.max(0,parseInt(parsed.salScore)||0)),
    locScore: Math.min(100,Math.max(0,parseInt(parsed.locScore)||0)),
    reason: parsed.reason||"",
    missing: parsed.missing||"",
    strengths: parsed.strengths||"",
    concerns: parsed.concerns||"",
    approved: (parseInt(parsed.score)||0) >= 60,
  };
}

async function scoreCandidate(c, criteria){
  if(S.grokKey){
    try{ return await scoreCandidateGrok(c, criteria, S.grokKey); }
    catch(e){ console.warn("[AI] Grok failed, falling back:", e.message); }
  }
  return scoreCandidateLocal(c, criteria);
}

// ── INIT ───────────────────────────────────────────────────────────────────
async function init(){
  // Pre-load saved Grok key
  const savedGrok = localStorage.getItem("rk_grok")||"";
  if(savedGrok) S.grokKey = savedGrok;
  render();
  if(S.token){ await loadJobs(); await loadCandidates(); render(); }
}
init();
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blue Ocean Steels — Daily Rate Broadcast | ZoTok Journey</title>
<style>
:root{--brand:#1B3A6B;--brand-dark:#152f58;--accent:#589981;}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#f0f2f5;display:flex;min-height:100vh;}

/* ── Sidebar ── */
.sidebar{width:260px;background:#fff;border-right:1px solid #e0e0e0;display:flex;flex-direction:column;height:100vh;position:sticky;top:0;flex-shrink:0;}
.sb-head{padding:18px 16px 14px;border-bottom:1px solid #f0f0f0;}
.brand-row{display:flex;align-items:center;gap:10px;margin-bottom:10px;}
.brand-logo{width:38px;height:38px;border-radius:10px;background:var(--brand);display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:900;color:#fff;flex-shrink:0;letter-spacing:-.5px;}
.brand-name{font-size:15px;font-weight:700;color:#111;line-height:1.2;}
.brand-industry{font-size:11px;color:#888;}
.journey-lbl{font-size:11px;font-weight:700;color:var(--brand);text-transform:uppercase;letter-spacing:.5px;}
.step-list{flex:1;overflow-y:auto;padding:8px 0;}
.step-item{display:flex;align-items:flex-start;gap:9px;padding:9px 14px;cursor:pointer;border-left:3px solid transparent;transition:all .15s;}
.step-item:hover{background:#f0f4ff;}
.step-item.active{background:#eef2fb;border-left-color:var(--brand);}
.step-num{width:20px;height:20px;border-radius:50%;background:#e8e8e8;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#666;flex-shrink:0;margin-top:2px;}
.step-item.active .step-num{background:var(--brand);color:#fff;}
.step-lbl{font-size:12px;font-weight:600;color:#333;line-height:1.35;}
.step-item.active .step-lbl{color:var(--brand);}
.step-meta{font-size:10px;color:#aaa;margin-top:1px;}

/* ── Main ── */
.main{flex:1;display:flex;flex-direction:column;min-height:100vh;overflow:hidden;}
.main-head{background:#fff;border-bottom:1px solid #e8e8e8;padding:13px 28px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;}
.step-title{font-size:16px;font-weight:700;color:#111;}
.step-counter{font-size:12px;color:#888;background:#f5f5f5;border-radius:20px;padding:4px 12px;}
.step-desc-bar{background:#fff;border-bottom:1px solid #f0f0f0;padding:7px 28px;display:flex;align-items:center;gap:8px;font-size:12px;color:#555;flex-shrink:0;flex-wrap:wrap;}
.tag{display:inline-flex;align-items:center;padding:2px 8px;border-radius:10px;font-size:10px;font-weight:700;white-space:nowrap;}
.tag-sheet{background:#e8f5e9;color:#2E7D32;}
.tag-admin{background:#fff3e0;color:#E65100;}
.tag-ai{background:#ede7f6;color:#4527A0;}
.tag-waba{background:#e3f2fd;color:#1565C0;}
.tag-broadcast{background:#fff8e1;color:#F57F17;}
.tag-intro{background:#f3e5f5;color:#6A1B9A;}
.screens-area{flex:1;overflow-y:auto;overflow-x:auto;padding:24px 16px;background:#f0f2f5;}

/* ── Step sections ── */
.step-section{display:none;width:100%;justify-content:center;gap:20px;align-items:flex-start;}
.step-section.active{display:flex;flex-wrap:nowrap;}
/* Desktop steps (intro/sheet/menu/success) — wide centered layout */
#step-1.active,#step-2.active,#step-3.active,#step-4.active{display:block;}
#step-1 .screen-wrap,#step-2 .screen-wrap,#step-3 .screen-wrap,#step-4 .screen-wrap{width:100%;max-width:1080px;margin:0 auto;}
#step-1 .screen-desc,#step-2 .screen-desc,#step-3 .screen-desc,#step-4 .screen-desc{width:100%;max-width:1080px;}

/* ── Phone wrap layout ── */
.phone-wrap{display:flex;flex-direction:column;align-items:center;gap:6px;}
.phones-row{display:flex;flex-wrap:nowrap;gap:22px;align-items:flex-start;}
.screen-lbl{font-size:10.5px;color:#888;text-transform:uppercase;letter-spacing:.5px;font-weight:600;}
.screen-type-lbl{font-size:10px;color:#aaa;margin-bottom:2px;}
.screen-desc{width:375px;border-radius:12px;padding:10px 14px;font-size:13px;line-height:1.5;color:#2a2a2a;}
.screen-desc strong{font-size:13.5px;font-weight:700;color:#111;display:block;margin-bottom:3px;}

/* ── Phone frame (DM) ── */
.pf{width:375px;border-radius:40px;border:8px solid #1a1a1a;box-shadow:0 20px 60px rgba(0,0,0,.3);overflow:hidden;display:flex;flex-direction:column;height:680px;position:relative;flex-shrink:0;}

/* DM phone (dark teal) */
.dm-sb{background:#075E54;padding:9px 16px 5px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;}
.dm-time{font-size:13px;font-weight:600;color:#fff;}
.dm-icons{display:flex;align-items:center;gap:5px;}
.dm-bat-wrap{display:flex;align-items:center;gap:1px;}
.dm-bat-body{width:19px;height:10px;border:1.5px solid rgba(255,255,255,.7);border-radius:2.5px;padding:1.5px;display:flex;align-items:center;}
.dm-bat-fill{height:100%;width:70%;background:rgba(255,255,255,.7);border-radius:1px;}
.dm-bat-tip{width:2px;height:5px;background:rgba(255,255,255,.5);border-radius:0 1px 1px 0;margin-left:1px;}
.dm-tb{background:#075E54;padding:6px 10px 8px;display:flex;align-items:center;gap:8px;flex-shrink:0;border-bottom:1px solid rgba(0,0,0,.08);}
.dm-back{display:flex;align-items:center;flex-shrink:0;padding-right:2px;}
.dm-ava{width:36px;height:36px;border-radius:50%;background:#1B3A6B;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:800;color:#fff;flex-shrink:0;letter-spacing:-.3px;}
.dm-info{flex:1;}
.dm-name{font-size:14px;font-weight:600;color:#fff;}
.dm-status{font-size:11px;color:rgba(255,255,255,.75);}
.dm-acts{display:flex;align-items:center;gap:14px;}

/* Chat area */
.chat-area{flex:1;overflow-y:auto;padding:10px 10px 8px;background-color:#ECE5DD;background-image:url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23b2a99a' fill-opacity='0.13'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");display:flex;flex-direction:column;gap:5px;}
.sys-evt{align-self:center;background:rgba(255,255,255,.8);border-radius:8px;padding:4px 12px;font-size:10.5px;color:#667781;margin:3px 0;}

/* Bubbles */
.mb-r-w{display:flex;flex-direction:column;align-items:flex-start;margin-bottom:3px;}
.mb-s-w{display:flex;flex-direction:column;align-items:flex-end;margin-bottom:3px;}
.dm-receiver{background:#fff;border-radius:0 10px 10px 10px;padding:7px 11px 5px;max-width:268px;box-shadow:0 1px 2px rgba(0,0,0,.09);position:relative;}
.dm-receiver::before{content:'';position:absolute;top:0;left:-7px;border-width:0 8px 8px 0;border-style:solid;border-color:transparent #fff transparent transparent;}
.dm-sender{background:#DCF8C6;border-radius:10px 0 10px 10px;padding:7px 11px 5px;max-width:268px;box-shadow:0 1px 2px rgba(0,0,0,.09);position:relative;}
.dm-sender::after{content:'';position:absolute;top:0;right:-7px;border-width:0 0 8px 8px;border-style:solid;border-color:transparent transparent transparent #DCF8C6;}
.mb-body{font-size:13px;color:#111B21;line-height:1.45;}
.mb-time{font-size:10.5px;color:#667781;text-align:right;margin-top:3px;display:block;}
.mb-tick{color:#53bdeb;}

/* WhatsApp Business Template card */
.wa-tmpl{background:#fff;border-radius:8px 0 8px 8px;max-width:268px;overflow:hidden;box-shadow:0 1px 3px rgba(0,0,0,.13);}
.wa-tmpl-hdr-text{padding:8px 12px 4px;font-size:13.5px;font-weight:700;color:#111B21;background:#f5f5f5;}
.wa-tmpl-body{padding:10px 12px 5px;font-size:12.5px;color:#111B21;line-height:1.55;}
.wa-tmpl-footer{padding:0 12px 4px;font-size:11px;color:#667781;}
.wa-tmpl-time{font-size:10.5px;color:#667781;text-align:right;padding:2px 10px 7px;}
.wa-tmpl-btns{border-top:1px solid #f0f0f0;}
.wa-cta-btn{display:flex;align-items:center;justify-content:center;gap:6px;width:100%;padding:10px 12px;font-size:13.5px;font-weight:500;color:#00A884;background:none;border:none;border-bottom:1px solid #f0f0f0;cursor:pointer;}
.wa-cta-btn:last-child{border-bottom:none;}
.wa-cta-btn::before{content:'';width:14px;height:14px;flex-shrink:0;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none'%3E%3Cpath d='M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6' stroke='%2300A884' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M15 3h6v6M10 14L21 3' stroke='%2300A884' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E") center/contain no-repeat;}
.wa-qr-btn{display:flex;align-items:center;justify-content:center;gap:6px;width:100%;padding:10px 12px;font-size:13.5px;font-weight:500;color:#00A884;background:none;border:none;border-bottom:1px solid #f0f0f0;cursor:pointer;}
.wa-qr-btn:last-child{border-bottom:none;}
.wa-qr-btn::before{content:'';width:14px;height:14px;flex-shrink:0;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none'%3E%3Cpath d='M9 14L4 9l5-5' stroke='%2300A884' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M20 20v-5a6 6 0 00-6-6H4' stroke='%2300A884' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E") center/contain no-repeat;}

/* Input bar */
.input-bar{background:#f0f0f0;padding:6px 8px;display:flex;align-items:center;gap:8px;flex-shrink:0;}
.input-field{flex:1;background:#fff;border-radius:22px;padding:7px 14px;font-size:13px;color:#8696a0;}

/* ═══════════════════════ INTRO SLIDE ═══════════════════════ */
.intro-card{background:#fff;border-radius:18px;box-shadow:0 8px 36px rgba(0,0,0,.08);padding:38px 44px;border:1px solid #e8e8e8;}
.intro-eyebrow{font-size:11px;font-weight:700;color:var(--accent);text-transform:uppercase;letter-spacing:1.5px;margin-bottom:8px;}
.intro-title{font-size:30px;font-weight:800;color:#111;letter-spacing:-.5px;line-height:1.2;margin-bottom:10px;}
.intro-sub{font-size:14.5px;color:#555;line-height:1.6;margin-bottom:28px;max-width:780px;}
.intro-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:24px;}
.intro-col{padding:22px 22px 18px;border-radius:14px;}
.intro-col.problem{background:#fff5f5;border:1px solid #ffd3d3;}
.intro-col.sol{background:#e8f5e9;border:1px solid #b7dfb9;}
.intro-col-lbl{font-size:11px;font-weight:800;text-transform:uppercase;letter-spacing:1.2px;margin-bottom:8px;}
.intro-col.problem .intro-col-lbl{color:#C62828;}
.intro-col.sol .intro-col-lbl{color:#2E7D32;}
.intro-col-h{font-size:18px;font-weight:700;color:#111;margin-bottom:12px;line-height:1.3;}
.intro-list{list-style:none;display:flex;flex-direction:column;gap:9px;}
.intro-list li{font-size:13.5px;color:#333;line-height:1.5;display:flex;gap:10px;align-items:flex-start;}
.intro-list li::before{content:'';flex-shrink:0;margin-top:6px;width:7px;height:7px;border-radius:50%;}
.intro-col.problem .intro-list li::before{background:#E53935;}
.intro-col.sol .intro-list li::before{background:#2E7D32;}
.intro-stats{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:8px;}
.intro-stat{background:#f8f9fa;border:1px solid #e8eaed;border-radius:12px;padding:16px 14px;text-align:center;}
.intro-stat-num{font-size:24px;font-weight:800;color:var(--brand);letter-spacing:-.5px;}
.intro-stat-lbl{font-size:11px;color:#5f6368;margin-top:3px;line-height:1.3;}
.intro-flow{margin-top:26px;background:#f8fafc;border:1px solid #e1e8ee;border-radius:12px;padding:16px 18px;display:flex;align-items:center;gap:10px;flex-wrap:wrap;font-size:12.5px;color:#444;}
.intro-flow-pill{background:#fff;border:1px solid #d8e0e8;border-radius:20px;padding:6px 12px;font-weight:600;color:#1B3A6B;display:inline-flex;align-items:center;gap:6px;}
.intro-flow-arr{color:#999;font-weight:700;}

/* ═══════════════════════ GOOGLE SHEETS DESKTOP ═══════════════════════ */
.gs-frame{background:#fff;border-radius:10px;border:1px solid #dadce0;box-shadow:0 6px 30px rgba(0,0,0,.12);overflow:hidden;width:100%;display:flex;flex-direction:column;position:relative;}
.gs-tlbar{background:#f6f8fa;border-bottom:1px solid #e0e0e0;padding:6px 12px;display:flex;align-items:center;gap:9px;}
.gs-traffic{display:flex;gap:6px;}
.gs-traffic span{width:11px;height:11px;border-radius:50%;}
.gs-url{flex:1;background:#fff;border:1px solid #dadce0;border-radius:14px;padding:4px 12px;font-size:11px;color:#555;display:flex;align-items:center;gap:5px;max-width:540px;}
.gs-url .lock{font-size:9px;color:#5f6368;}
.gs-doc-row{padding:8px 14px;display:flex;align-items:center;gap:10px;border-bottom:1px solid #f0f0f0;background:#fff;}
.gs-doc-icon{width:28px;height:28px;border-radius:5px;background:#0f9d58;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.gs-doc-icon::after{content:'';width:14px;height:18px;background:#fff;clip-path:polygon(0 0,75% 0,100% 25%,100% 100%,0 100%);}
.gs-doc-info{flex:1;}
.gs-doc-title{font-size:15px;font-weight:500;color:#222;}
.gs-history{margin-left:auto;color:#5f6368;}
.gs-menubar{padding:0 14px 4px;display:flex;align-items:center;gap:0;border-bottom:1px solid #f0f0f0;background:#fff;font-size:12.5px;color:#444;position:relative;}
.gs-menu-item{padding:5px 9px;border-radius:4px;cursor:pointer;}
.gs-menu-item:hover{background:#f1f3f4;}
.gs-menu-item.open{background:#e8f0fe;color:#1a73e8;}
.gs-toolbar{background:#f6f8fa;border-bottom:1px solid #e0e0e0;padding:5px 14px;display:flex;align-items:center;gap:6px;flex-wrap:wrap;}
.gs-tb-btn{padding:5px 7px;border-radius:4px;color:#5f6368;font-size:12px;cursor:pointer;display:inline-flex;align-items:center;gap:3px;}
.gs-tb-btn:hover{background:#fff;}
.gs-tb-sep{width:1px;height:18px;background:#e0e0e0;margin:0 3px;}
.gs-search{display:flex;align-items:center;gap:5px;background:#fff;border:1px solid #e0e0e0;border-radius:18px;padding:3px 10px;font-size:11.5px;color:#5f6368;}
.gs-namebar{padding:4px 14px;display:flex;align-items:center;gap:10px;border-bottom:1px solid #e0e0e0;background:#fff;font-size:11.5px;color:#444;}
.gs-namebox{background:#fff;border:1px solid #e0e0e0;border-radius:3px;padding:3px 8px;width:60px;font-size:11px;}
.gs-formula{flex:1;font-family:'Courier New',monospace;font-size:11px;color:#222;}
.gs-grid-wrap{flex:1;overflow:auto;background:#fff;max-height:430px;}
.gs-grid{border-collapse:collapse;width:100%;table-layout:fixed;}
.gs-grid .ch{background:#f8f9fa;color:#5f6368;font-size:10.5px;padding:3px 4px;border:1px solid #e0e0e0;text-align:center;font-weight:400;height:18px;}
.gs-grid .rh{background:#f8f9fa;color:#5f6368;font-size:10.5px;padding:2px 6px;border:1px solid #e0e0e0;text-align:center;font-weight:400;width:34px;}
.gs-grid .gc{padding:4px 7px;border:1px solid #e8e8e8;font-size:11.5px;color:#222;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;background:#fff;}
.gs-grid .gh{background:#f1f3f4;font-weight:600;color:#222;border:1px solid #c5c8e8;}
.gs-grid .sel{outline:2px solid #1a73e8;outline-offset:-2px;background:#e8f0fe!important;}
.gs-grid .new-row{background:#fff8e1!important;animation:rowFlash 1.4s ease-out;}
@keyframes rowFlash{0%{background:#fff59d!important;}100%{background:#fff8e1!important;}}
.gs-bottom{background:#f6f8fa;border-top:1px solid #e0e0e0;padding:5px 12px;display:flex;align-items:center;gap:8px;font-size:11.5px;}
.gs-tab{padding:4px 12px;border-radius:4px 4px 0 0;color:#444;cursor:pointer;}
.gs-tab.active{background:#fff;color:#0f9d58;font-weight:600;border:1px solid #e0e0e0;border-bottom:2px solid #0f9d58;}
.gs-tab-add{font-size:14px;color:#5f6368;cursor:pointer;padding:0 8px;}

/* Cascading menus */
.gs-dropdown{position:absolute;background:#fff;border:1px solid #dadce0;border-radius:4px;box-shadow:0 6px 24px rgba(0,0,0,.18);min-width:280px;padding:6px 0;z-index:10;font-size:12.5px;color:#222;}
.gs-dd-item{padding:7px 16px 7px 38px;display:flex;align-items:center;gap:10px;cursor:pointer;position:relative;}
.gs-dd-item .icn{position:absolute;left:12px;top:50%;transform:translateY(-50%);width:18px;height:18px;display:flex;align-items:center;justify-content:center;font-size:13px;}
.gs-dd-item .arr{margin-left:auto;color:#5f6368;font-size:11px;}
.gs-dd-item:hover{background:#f1f3f4;}
.gs-dd-item.hl{background:#e8f0fe;}
.gs-dd-sep{height:1px;background:#e0e0e0;margin:5px 0;}

/* Success card */
.gs-success-card{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);background:#fff;border-radius:14px;width:400px;padding:30px 26px;box-shadow:0 18px 60px rgba(0,0,0,.32);text-align:center;z-index:45;}
.gsuc-ico{width:64px;height:64px;border-radius:50%;background:#e8f5e9;display:flex;align-items:center;justify-content:center;margin:0 auto 14px;}
.gsuc-ico::before{content:'';width:26px;height:14px;border-left:4px solid #0f9d58;border-bottom:4px solid #0f9d58;transform:rotate(-45deg) translateY(-3px);}
.gsuc-title{font-size:19px;font-weight:700;color:#111;margin-bottom:6px;}
.gsuc-sub{font-size:12.5px;color:#555;line-height:1.55;margin-bottom:16px;}
.gsuc-stats{display:flex;gap:10px;justify-content:center;margin-bottom:18px;}
.gsuc-stat{flex:1;background:#f8f9fa;border-radius:8px;padding:11px 6px;}
.gsuc-stat-num{font-size:19px;font-weight:800;color:#1B3A6B;}
.gsuc-stat-lbl{font-size:10px;color:#5f6368;text-transform:uppercase;letter-spacing:.4px;margin-top:2px;}
.gsuc-seg-row{display:flex;justify-content:space-between;align-items:center;padding:8px 12px;border-radius:6px;margin-bottom:5px;background:#f8f9fa;}
.gsuc-seg-name{font-size:12.5px;font-weight:600;color:#222;}
.gsuc-seg-cnt{font-size:11px;color:#1B3A6B;font-weight:700;background:#e8f0fe;border-radius:10px;padding:2px 9px;}
.gsuc-btn{background:#1B3A6B;color:#fff;border:none;border-radius:6px;padding:10px 22px;font-size:13px;font-weight:600;cursor:pointer;margin-top:6px;}

/* Nav bar */
.nav-bar{background:#fff;border-top:1px solid #e8e8e8;padding:12px 28px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;}
.nav-btn{padding:8px 18px;border-radius:8px;border:1.5px solid #e0e0e0;background:#fff;font-size:13px;font-weight:600;color:#333;cursor:pointer;transition:all .15s;display:flex;align-items:center;gap:6px;}
.nav-btn:hover:not(:disabled){border-color:var(--brand);color:var(--brand);background:#eef2fb;}
.nav-btn:disabled{opacity:.3;cursor:not-allowed;}
.nav-btn.primary{background:var(--brand);border-color:var(--brand);color:#fff;}
.nav-btn.primary:hover:not(:disabled){background:var(--brand-dark);border-color:var(--brand-dark);}

/* ══════ MOBILE ══════ */
@media (min-width:769px){
  .mob-swipe-hint{display:none !important;}
  .mob-hamburger{display:none !important;}
  .mob-sb-close{display:none !important;}
  .mob-overlay{display:none !important;}
}
@media (max-width:768px){
.sidebar{position:fixed;left:0;top:0;bottom:0;z-index:1000;transform:translateX(-100%);transition:transform .26s cubic-bezier(.4,0,.2,1);box-shadow:4px 0 28px rgba(0,0,0,.22);height:100%;overflow-y:auto;}
.sidebar.mob-open{transform:translateX(0);}
.mob-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.42);z-index:999;-webkit-tap-highlight-color:transparent;}
.mob-overlay.mob-open{display:block;}
.mob-sb-close{position:absolute;top:10px;right:10px;width:28px;height:28px;border:none;background:none;font-size:20px;cursor:pointer;color:#888;}
.mob-hamburger{display:flex;flex-direction:column;justify-content:center;gap:5px;cursor:pointer;padding:5px;flex-shrink:0;}
.mob-hamburger span{display:block;width:22px;height:2.5px;background:#555;border-radius:2px;}
.main{overflow:hidden;}
.main-head{padding:8px 14px;gap:10px;}
.step-title{font-size:13px;flex:1;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.step-desc-bar{display:none !important;}
.step-counter{display:none !important;}
.screen-lbl{display:none !important;}
.screens-area{display:flex !important;flex-direction:row;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;-webkit-overflow-scrolling:touch;scrollbar-width:none;padding:0;gap:0;flex:1;}
.screens-area::-webkit-scrollbar{display:none;}
.step-section{display:contents !important;}
.screen-wrap{width:100vw !important;min-width:100vw !important;max-width:100vw !important;flex-shrink:0;scroll-snap-align:start;display:flex !important;flex-direction:column;align-items:center;justify-content:flex-start;padding:14px 12px 80px;overflow-y:auto;overflow-x:hidden;gap:10px;}
.nav-bar{display:none !important;}
.pf{width:calc(100vw - 24px);max-width:375px;}
.gs-frame{width:calc(100vw - 24px);max-width:600px;font-size:10px;transform:scale(.92);transform-origin:top center;}
.intro-card{padding:24px 18px;}
.intro-grid{grid-template-columns:1fr;}
.intro-stats{grid-template-columns:1fr 1fr;}
.intro-title{font-size:22px;}
.mob-swipe-hint{position:fixed;bottom:0;left:0;right:0;background:rgba(255,255,255,.95);border-top:1px solid #e8e8e8;padding:7px 16px;display:flex;align-items:center;justify-content:space-between;z-index:100;}
.mob-swipe-dots{display:flex;gap:5px;align-items:center;}
.mob-dot{width:6px;height:6px;border-radius:50%;background:#ddd;transition:background .2s,width .2s;}
.mob-dot.active{background:var(--brand);width:16px;border-radius:3px;}
.mob-prev-btn,.mob-next-btn{background:var(--brand);color:#fff;border:none;border-radius:8px;padding:6px 14px;font-size:12px;font-weight:600;cursor:pointer;}
.mob-prev-btn:disabled,.mob-next-btn:disabled{background:#ccc;cursor:not-allowed;}
.chat-area{overscroll-behavior:contain;}
.screen-desc{position:fixed !important;left:16px !important;right:16px !important;bottom:58px !important;width:auto !important;max-width:none !important;z-index:200;opacity:0;pointer-events:none;transition:opacity 0.5s ease;backdrop-filter:blur(4px);border-radius:14px !important;box-shadow:0 8px 28px rgba(0,0,0,0.18) !important;font-size:13px !important;}
.screen-desc.desc-visible{opacity:0.93;pointer-events:auto;}
}
</style>
</head>
<body>

<div class="mob-overlay" id="mob-overlay" onclick="closeSidebar()"></div>

<!-- ══════ SIDEBAR ══════ -->
<nav class="sidebar">
  <button class="mob-sb-close" onclick="closeSidebar()">✕</button>

  <div class="sb-head" style="padding-right:36px;">
    <div class="brand-row">
      <div class="brand-logo">ZT</div>
      <div>
        <div class="brand-name">Recykal Marketplace</div>
      </div>
    </div>

    <div class="journey-lbl">Buyer Requirement → Listing Creation</div>
  </div>

  <div class="step-list">

    <div class="step-item active" onclick="scrollToStep(1)">
      <div class="step-num">1</div>
      <div>
        <div class="step-lbl">Problem & Solution</div>
        <div class="step-meta">Send Campaign in one-click</div>
      </div>
    </div>

    <div class="step-item" onclick="scrollToStep(2)">
      <div class="step-num">2</div>
      <div>
        <div class="step-lbl">Campaign Data Sheet</div>
        <div class="step-meta">Buyer requirements uploaded in Google Sheets against Sellers</div>
      </div>
    </div>

    <div class="step-item" onclick="scrollToStep(3)">
      <div class="step-num">3</div>
      <div>
        <div class="step-lbl">Open ZoTok Add-on Menu</div>
        <div class="step-meta">Extensions › Zotok › Campaign › Send Messages</div>
      </div>
    </div>

    <div class="step-item" onclick="scrollToStep(4)">
      <div class="step-num">4</div>
      <div>
        <div class="step-lbl">Broadcast Sent</div>
        <div class="step-meta">Material, quantity and price submitted</div>
      </div>
    </div>

    <div class="step-item" onclick="scrollToStep(5)">
      <div class="step-num">5</div>
      <div>
        <div class="step-lbl">Seller Receives Requirement</div>
        <div class="step-meta">WhatsApp notification for stock listing</div>
      </div>
    </div>


  </div>

  <a href="index.html"
     class="sb-foot"
     style="display:block;text-decoration:none;color:#1B3A6B;font-weight:600;font-size:11px;padding:10px 14px;border-top:1px solid #f0f0f0;text-align:center;">
     ← Main Menu
  </a>
</nav>

<!-- ══════ MAIN ══════ -->
<main class="main">
  <div class="main-head">
    <div style="display:flex;align-items:center;gap:12px;">
      <div class="mob-hamburger" onclick="openSidebar()"><span></span><span></span><span></span></div>
      <div class="step-title" id="step-title">Step 1 — Problem &amp; Solution</div>
    </div>
    <div class="step-counter" id="step-counter">Step 1 of 6</div>
  </div>
  <div class="step-desc-bar" id="step-desc-bar"></div>

  <div class="screens-area">

<!-- ════════ STEP 1 — INTRO: Problem & Solution ════════ -->
<div id="step-1" class="step-section active">
  <div class="screen-wrap">

    <div class="intro-card">

      <div class="intro-eyebrow">
        ZOTOK × GOOGLE SHEETS · BUY RECYKAL MARKETPLACE
      </div>

      <div class="intro-title">
        Buyer Requirements — broadcast from a Google Sheet to every seller in one click
      </div>

      <div class="intro-sub">
        Buyers on Recykal post their material requirements every day. The right seller, with the right stock, at the right terms decides who gets the order. ZoTok turns your buyer requirement sheet into a one-click WhatsApp broadcast.
      </div>

      <div class="intro-grid">

        <!-- Problem Card -->
        <div class="intro-col problem">

          <div class="intro-col-lbl">
            ⚠ THE PROBLEM TODAY
          </div>

          <div class="intro-col-h">
            Delayed responses. Missed opportunities.
          </div>

          <ul class="intro-list">

            <li>
              Recykal team manually shares buyer requirements with sellers over WhatsApp — one by one
            </li>

            <li>
              Sellers ask the same questions repeatedly (quantity,material grade, location, pickup terms, target price, payment terms)
            </li>

            <li>
              Hard to reach the right sellers fast — many relevant sellers never see the requirement
            </li>

            <li>
              Different buyer requirements (material, grade, quantity, location) need different messages — easy to send wrong details
            </li>

            <li>
              No clear record of what was sent, to whom, when, and who responded
            </li>

          </ul>

        </div>

        <!-- Solution Card -->
        <div class="intro-col sol">

          <div class="intro-col-lbl">
            ✓ ZOTOK SOLUTION
          </div>

          <div class="intro-col-h">
            One sheet • One click • Hundreds of seller notifications
          </div>

          <ul class="intro-list">

            <li>
              Recykal team updates buyer requirements in the Recykal Requirements google sheets
              (the same one they already use)
            </li>

            <li>
              Opens
              Extensions›ZoTok ›Campaign ›Send Messages — the ZoTok Workspace add-on
            </li>

            <li>
              Each campaign_id maps to a Meta-approved WhatsApp template for broadcasting buyer requirements to relevant sellers
            </li>

            <li>
              Variables auto-fill directly from the Recykal Google Sheet including
              Customer Name,
              Item Name,
              Quantity,
            </li>

            <li>
              Messages are sent only to relevant and opted-in sellers matched from the Recykal seller network
            </li>

          </ul>

        </div>

      </div>

      <!-- Flow -->
      <div class="intro-flow">

        <strong style="color:#1B3A6B;">Flow:</strong>

        <span class="intro-flow-pill">
          📊 Update Buyer Requirements Sheet
        </span>

        <span class="intro-flow-arr">→</span>

        <span class="intro-flow-pill">
          🧩 Extensions › ZoTok › Campaign › Send Messages
        </span>

        <span class="intro-flow-arr">→</span>

        <span class="intro-flow-pill">
          📣 Broadcast to Relevant Sellers
        </span>

        <span class="intro-flow-arr">→</span>

        <span class="intro-flow-pill">
          💬 Seller Shares Stock Details
        </span>

        <span class="intro-flow-arr">→</span>

        <span class="intro-flow-pill">
          📦 Listing Draft Created
        </span>

        <span class="intro-flow-arr">→</span>

        <span class="intro-flow-pill">
          ✅ Listing Published
        </span>

      </div>

    </div>

  </div>
</div>
<!-- /step-1 -->

    <!-- ════════ STEP 2 — Update Sheet ════════ -->
    <div id="step-2" class="step-section">
      <div class="screen-wrap">
       <div class="screen-lbl" style="text-align:center;display:block;">Step 2 · Buyer Requirement Campaign Sheet</div>
<div class="screen-type-lbl" style="text-align:center;">Coordinator updates buyer details, item requirements &amp; quantity in Google Sheets</div>

        <div class="gs-frame">
          <div class="gs-tlbar">
            <div class="gs-traffic"><span style="background:#ff5f57"></span><span style="background:#febc2e"></span><span style="background:#28c840"></span></div>
            <div class="gs-url"><span class="lock">🔒</span> docs.google.com/spreadsheets/d/1bO-rate-broadcast/edit</div>
          </div>
          <div class="gs-doc-row">
            <div class="gs-doc-icon"></div>
            <div class="gs-doc-info">
             <div class="gs-doc-title">Recykal — Buyer Requirement Campaign ⭐</div>
            </div>
            <div class="gs-history">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M3 12a9 9 0 109-9 9.75 9.75 0 00-6.74 2.74L3 8M3 3v5h5M12 7v5l4 2" stroke="#5f6368" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </div>
          </div>
          <div class="gs-menubar">
            <span class="gs-menu-item">File</span>
            <span class="gs-menu-item">Edit</span>
            <span class="gs-menu-item">View</span>
            <span class="gs-menu-item">Insert</span>
            <span class="gs-menu-item">Format</span>
            <span class="gs-menu-item">Data</span>
            <span class="gs-menu-item">Tools</span>
            <span class="gs-menu-item">Extensions</span>
            <span class="gs-menu-item">Help</span>
          </div>
          <div class="gs-toolbar">
            <div class="gs-search"><span>🔍</span> Menus</div>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">↶</span>
            <span class="gs-tb-btn">↷</span>
            <span class="gs-tb-btn">🖨</span>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">100% ▾</span>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">₹</span>
            <span class="gs-tb-btn">%</span>
            <span class="gs-tb-btn">.0</span>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">B</span>
            <span class="gs-tb-btn">I</span>
            <span class="gs-tb-btn">A▾</span>
            <span class="gs-tb-btn">Fill</span>
          </div>
          <div class="gs-namebar">
            <div class="gs-namebox">A12</div>
            <div style="font-size:14px;color:#5f6368;">𝑓<sub>x</sub></div>
            <div class="gs-formula">DRB-2026-05-14-AGENT</div>
          </div>
        <table class="gs-grid">
  <colgroup>
    <col style="width:34px">
    <col style="width:180px">
    <col style="width:220px">
    <col style="width:160px">
    <col style="width:220px">
    <col style="width:100px">
  </colgroup>

  <!-- Column Letters -->
  <tr>
    <td class="ch"></td>
    <td class="ch">A</td>
    <td class="ch">B</td>
    <td class="ch">C</td>
    <td class="ch">D</td>
    <td class="ch">E</td>
  </tr>

  <!-- Header Row -->
  <tr>
    <td class="rh">1</td>
    <td class="gc gh">campaign_code</td>
    <td class="gc gh">customer_name</td>
    <td class="gc gh">mobile_number</td>
    <td class="gc gh">item_name</td>
    <td class="gc gh">qty</td>
  </tr>

  <!-- Data Rows -->
  <tr>
    <td class="rh">2</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Ramesh Traders</td>
    <td class="gc">9876543210</td>
    <td class="gc">PET Bottle Scrap Baled - Clear, First Grade</td>
    <td class="gc">25 MT</td>
  </tr>

  <tr>
    <td class="rh">3</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Shree Steel</td>
    <td class="gc">9123456780</td>
    <td class="gc">Melting Scrap</td>
    <td class="gc">18 MT</td>
  </tr>

  <tr>
    <td class="rh">4</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Sai Metals</td>
    <td class="gc">9988776655</td>
    <td class="gc">Hot washe PET flakes</td>
    <td class="gc">40 MT</td>
  </tr>

  <tr>
    <td class="rh">5</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Blue Star Steel</td>
    <td class="gc">9012345678</td>
    <td class="gc">MS scrap</td>
    <td class="gc">30 MT</td>
  </tr>

  <tr>
    <td class="rh">6</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Maheshwari Steel</td>
    <td class="gc">9090909090</td>
    <td class="gc">Mix scrap </td>
    <td class="gc">22 MT</td>
  </tr>
</table>
          </div>
          <div class="gs-bottom">
            <span style="color:#5f6368;">≡</span>
            <span class="gs-tab active">Daily Rates</span>
            <span class="gs-tab" style="color:#5f6368;">Customers</span>
            <span class="gs-tab" style="color:#5f6368;">Templates</span>
            <span class="gs-tab-add">+</span>
          </div>
        </div>

        <div class="screen-desc" style="background:#fff8e1;border:1px solid #ffe082;margin-top:14px;">
  <strong>Campaign setup — 30 seconds, zero manual effort</strong>
  Coordinator updates the Recykal buyer requirement sheet with campaign data, buyer details, item name, and quantity. ZoTok automatically reads the sheet, maps the campaign to WhatsApp templates, and sends personalized messages to all seller instantly.
</div>
    </div><!-- /step-2 -->

    <!-- ════════ STEP 3 — Extensions > Zotok > Campaign > Send Messages ════════ -->
    <div id="step-3" class="step-section">
      <div class="screen-wrap">
        <div class="screen-lbl" style="text-align:center;display:block;">Step 3 · ZoTok Add-on Menu</div>
        <div class="screen-type-lbl" style="text-align:center;">Extensions › Zotok › Campaign › Send Messages</div>

        <div class="gs-frame" style="min-height:780px;">
          <div class="gs-tlbar">
            <div class="gs-traffic"><span style="background:#ff5f57"></span><span style="background:#febc2e"></span><span style="background:#28c840"></span></div>
            <div class="gs-url"><span class="lock">🔒</span> docs.google.com/spreadsheets/d/1bO-rate-broadcast/edit</div>
          </div>
          <div class="gs-doc-row">
            <div class="gs-doc-icon"></div>
            <div class="gs-doc-info">
              <div class="gs-doc-title">Recykal — Buyer Requirement Campaign ⭐
</div>
            </div>
          </div>
          <!-- Menu bar with Extensions OPEN -->
          <div class="gs-menubar" style="position:relative;padding-bottom:4px;">
            <span class="gs-menu-item">File</span>
            <span class="gs-menu-item">Edit</span>
            <span class="gs-menu-item">View</span>
            <span class="gs-menu-item">Insert</span>
            <span class="gs-menu-item">Format</span>
            <span class="gs-menu-item">Data</span>
            <span class="gs-menu-item">Tools</span>
            <span class="gs-menu-item open">Extensions</span>
            <span class="gs-menu-item">Help</span>

            <!-- Extensions dropdown -->
            <div class="gs-dropdown" style="left:295px;top:30px;">
              <div class="gs-dd-item"><span class="icn">🧩</span>Add-ons<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">▶</span>Macros<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">📜</span>Apps Script</div>
              <div class="gs-dd-sep"></div>
              <div class="gs-dd-item"><span class="icn">🅰</span>AppSheet<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">📊</span>Data Studio<span class="arr">▸</span></div>
              <div class="gs-dd-sep"></div>
              <div class="gs-dd-item"><span class="icn">🤖</span>AI for Work: Gemini GPT Claude<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">📤</span>Export Sheet Data<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">🗑</span>Remove Duplicates<span class="arr">▸</span></div>
              <div class="gs-dd-item hl"><span class="icn">📦</span>Zotok<span class="arr">▸</span></div>
            </div>

            <!-- Zotok submenu — aligned with the highlighted Zotok row in Extensions dropdown -->
            <div class="gs-dropdown" style="left:580px;top:332px;min-width:230px;">
              <div class="gs-dd-item"><span class="icn">💰</span>Price List<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">👥</span>Customers<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">📦</span>Products<span class="arr">▸</span></div>
              <div class="gs-dd-item"><span class="icn">📋</span>Orders<span class="arr">▸</span></div>
              <div class="gs-dd-item hl"><span class="icn">📣</span>Campaign<span class="arr">▸</span></div>
              <div class="gs-dd-sep"></div>
              <div class="gs-dd-item"><span class="icn">🎁</span>All Entities</div>
              <div class="gs-dd-item"><span class="icn">🔐</span>Manage Credentials</div>
              <div class="gs-dd-sep"></div>
              <div class="gs-dd-item"><span class="icn">❓</span>Help</div>
            </div>

            <!-- Campaign submenu -->
            <div class="gs-dropdown" style="left:810px;top:464px;min-width:200px;">
              <div class="gs-dd-item hl" style="position:relative;">
                <span class="icn">💬</span>Send Messages
                <span style="position:absolute;right:12px;top:50%;transform:translateY(-50%);width:10px;height:10px;border:2px solid #1a73e8;border-radius:50%;background:#fff;"></span>
              </div>
            </div>
          </div>
          <div class="gs-toolbar" style="opacity:.55;">
            <div class="gs-search"><span>🔍</span> Menus</div>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">↶</span>
            <span class="gs-tb-btn">↷</span>
            <div class="gs-tb-sep"></div>
            <span class="gs-tb-btn">100% ▾</span>
          </div>
          <div class="gs-grid-wrap" style="opacity:.45;min-height:330px;">
            <table class="gs-grid">
              <colgroup><col style="width:34px"><col style="width:200px"><col style="width:90px"><col style="width:140px"><col style="width:110px"><col style="width:110px"><col style="width:110px"><col style="width:240px"></colgroup>
              <tr>
                <td class="ch"></td>
                <td class="ch">A</td><td class="ch">B</td><td class="ch">C</td><td class="ch">D</td><td class="ch">E</td><td class="ch">F</td><td class="ch">G</td>
              </tr>
              <tr>
                <td class="rh">1</td>
                <td class="gc gh">campaign_code</td><td class="gc gh">customer_name</td><td class="gc gh">mobile_number</td><td class="gc gh">item_name</td><td class="gc gh">Qty</td>
              </tr>
              <tr>
    <td class="rh">2</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Ramesh Traders</td>
    <td class="gc">9876543210</td>
    <td class="gc">PET Bottle Scrap Baled - Clear, First Grade</td>
    <td class="gc">25 MT</td>
  </tr>

  <tr>
    <td class="rh">3</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Shree Steel</td>
    <td class="gc">9123456780</td>
    <td class="gc">Melting Scrap</td>
    <td class="gc">18 MT</td>
  </tr>

  <tr>
    <td class="rh">4</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Sai Metals</td>
    <td class="gc">9988776655</td>
    <td class="gc">Hot washe PET flakes</td>
    <td class="gc">40 MT</td>
  </tr>

  <tr>
    <td class="rh">5</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Blue Star Steel</td>
    <td class="gc">9012345678</td>
    <td class="gc">MS scrap</td>
    <td class="gc">30 MT</td>
  </tr>

  <tr>
    <td class="rh">6</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Maheshwari Steel</td>
    <td class="gc">9090909090</td>
    <td class="gc">Mix scrap </td>
    <td class="gc">22 MT</td>
  </tr>
            </table>
          </div>
        </div>

        <div class="screen-desc" style="background:#e3f2fd;border:1px solid #90caf9;margin-top:14px;">
          <strong>ZoTok Workspace Add-on — installed once, lives in every sheet</strong>
          The ZoTok add-on is published in Google Workspace Marketplace (free). Once installed by the org admin, it appears under <code>Extensions › Zotok</code> for every sheet user with no per-user setup. The full add-on surface — <em>Price List, Customers, Products, Orders, Campaign, All Entities, Manage Credentials</em> — is one click away. For broadcast: <strong>Extensions → Zotok → Campaign → Send Messages</strong>.
        </div>
      </div>
    </div><!-- /step-3 -->

    <!-- ════════ STEP 4 — Broadcast Sent (success only, no confirm modal) ════════ -->
    <div id="step-4" class="step-section">
      <div class="screen-wrap">
        <div class="screen-lbl" style="text-align:center;display:block;">Step 4 · Broadcast Sent</div>
        <div class="screen-type-lbl" style="text-align:center;">Per-segment templates queued · live delivery in CRM</div>

        <div class="gs-frame" style="position:relative;min-height:580px;">
          <div class="gs-tlbar">
            <div class="gs-traffic"><span style="background:#ff5f57"></span><span style="background:#febc2e"></span><span style="background:#28c840"></span></div>
            <div class="gs-url"><span class="lock">🔒</span> docs.google.com/spreadsheets/d/1bO-rate-broadcast/edit</div>
          </div>
          <div class="gs-doc-row">
            <div class="gs-doc-icon"></div>
            <div class="gs-doc-info">
              <div class="gs-doc-title">Recykal — Buyer Requirement Campaign ⭐
</div>
            </div>
          </div>
          <div class="gs-menubar">
            <span class="gs-menu-item">File</span><span class="gs-menu-item">Edit</span><span class="gs-menu-item">View</span><span class="gs-menu-item">Insert</span><span class="gs-menu-item">Format</span><span class="gs-menu-item">Data</span><span class="gs-menu-item">Tools</span><span class="gs-menu-item">Extensions</span><span class="gs-menu-item">Help</span>
          </div>
          <div class="gs-grid-wrap" style="opacity:.4;max-height:380px;">
            <table class="gs-grid">
              <colgroup><col style="width:34px"><col style="width:200px"><col style="width:90px"><col style="width:90px"><col style="width:90px"><col style="width:90px"><col style="width:90px"><col style="width:200px"></colgroup>
              <tr><td class="ch"></td><td class="ch">A</td><td class="ch">B</td><td class="ch">C</td><td class="ch">D</td><td class="ch">E</td><td class="ch">F</td><td class="ch">G</td></tr>
              <tr>
                <td class="rh">1</td>
                <td class="gc gh">campaign_code</td><td class="gc gh">customer_name</td><td class="gc gh">mobile_number</td><td class="gc gh">item_name</td><td class="gc gh">Qty</td>
              </tr>
              <tr>
    <td class="rh">2</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Ramesh Traders</td>
    <td class="gc">9876543210</td>
    <td class="gc">PET Bottle Scrap Baled - Clear, First Grade</td>
    <td class="gc">25 MT</td>
  </tr>

  <tr>
    <td class="rh">3</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Shree Steel</td>
    <td class="gc">9123456780</td>
    <td class="gc">Melting Scrap</td>
    <td class="gc">18 MT</td>
  </tr>

  <tr>
    <td class="rh">4</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Sai Metals</td>
    <td class="gc">9988776655</td>
    <td class="gc">Hot washe PET flakes</td>
    <td class="gc">40 MT</td>
  </tr>

  <tr>
    <td class="rh">5</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Blue Star Steel</td>
    <td class="gc">9012345678</td>
    <td class="gc">MS scrap</td>
    <td class="gc">30 MT</td>
  </tr>

  <tr>
    <td class="rh">6</td>
    <td class="gc">DRB-2026-05-14</td>
    <td class="gc">Maheshwari Steel</td>
    <td class="gc">9090909090</td>
    <td class="gc">Mix scrap </td>
    <td class="gc">22 MT</td>
  </tr>
            </table>
          </div>

          <!-- Success card overlay -->
          <div class="gs-success-card">
            <div class="gsuc-ico"></div>
            <div class="gsuc-title">Broadcast Queued Successfully</div>
            <div class="gsuc-sub"><strong>42 messages</strong> being delivered using different buyer requirements. Per-segment variants applied automatically from the sheet.</div>
            <div class="gsuc-stats">
              <div class="gsuc-stat"><div class="gsuc-stat-num">42</div><div class="gsuc-stat-lbl">Queued</div></div>
              <div class="gsuc-stat"><div class="gsuc-stat-num">1</div><div class="gsuc-stat-lbl">Variants</div></div>
              <div class="gsuc-stat"><div class="gsuc-stat-num">~2m</div><div class="gsuc-stat-lbl">ETA</div></div>
            </div>
            <div style="text-align:left;margin-bottom:14px;">
              <div class="gsuc-seg-row"><span class="gsuc-seg-name">📦 DRB-2026-05-14</span><span class="gsuc-seg-cnt">42 agents</span></div>
            </div>
            <button class="gsuc-btn">View Live Status →</button>
          </div>
        </div>

        <div class="screen-desc" style="background:#e8f5e9;border:1px solid #a5d6a7;margin-top:14px;">
          <strong>One click → 42 messages out the door</strong>
          ZoTok queues the broadcast via WhatsApp Business API using pre-approved templates, with placeholders dynamically filled from the sheet rows.

Campaign codes are automatically detected from the sheet, ensuring the correct template is triggered every time.
        </div>
      </div>
    </div><!-- /step-4 -->

    <!-- ════════ STEP 5 — Recipients (Agent + Party side-by-side) ════════ -->
    <div id="step-5" class="step-section">

      <!-- Screen 1: Agent -->
      <div class="phone-wrap screen-wrap">
        <div class="screen-lbl">Screen 3 · WhatsApp Message Received by Seller</div>
  <div class="screen-type-lbl">WABA Utility + Engagement Message — Stock Listing Prompt</div>

  <div class="pf">
    <div class="dm-sb">
      <span class="dm-time">09:34</span>
      <div class="dm-icons">
        <svg width="16" height="12" viewBox="0 0 16 12" fill="none">
          <rect x="0" y="8" width="3" height="4" rx=".5" fill="#fff"/>
          <rect x="4" y="5" width="3" height="7" rx=".5" fill="#fff"/>
          <rect x="8" y="2" width="3" height="10" rx=".5" fill="#fff"/>
          <rect x="12" y="0" width="3" height="12" rx=".5" fill="#fff"/>
        </svg>

        <svg width="16" height="12" viewBox="0 0 24 18" fill="none">
          <path d="M12 14a2 2 0 110 4 2 2 0 010-4z" fill="#fff"/>
          <path d="M5.6 9.4a9 9 0 0112.8 0" stroke="#fff" stroke-width="2" stroke-linecap="round"/>
          <path d="M2 5.8A14 14 0 0122 5.8" stroke="#fff" stroke-width="2" stroke-linecap="round"/>
        </svg>

        <div class="dm-bat-wrap">
          <div class="dm-bat-body"><div class="dm-bat-fill"></div></div>
          <div class="dm-bat-tip"></div>
        </div>
      </div>
    </div>

    <div class="dm-tb">
      <div class="dm-back">
        <svg width="9" height="16" viewBox="0 0 10 17" fill="none">
          <path d="M9 1L1 8.5L9 16" stroke="#fff" stroke-width="2.2" stroke-linecap="round"/>
        </svg>
      </div>

      <div class="dm-ava">RM</div>

      <div class="dm-info">
        <div class="dm-name">Recykal Marketplace</div>
        <div class="dm-status">Business Account</div>
      </div>

      <div class="dm-acts">
        <svg width="18" height="14" viewBox="0 0 24 17" fill="none">
          <rect x="1" y="1" width="15" height="15" rx="2" stroke="#fff" stroke-width="2"/>
          <path d="M16 6l7-4v13l-7-4V6z" stroke="#fff" stroke-width="2"/>
        </svg>

        <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
          <path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 11a19.79 19.79 0 01-3-8.57A2 2 0 012.06 0h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.09 7.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"
                stroke="#fff" stroke-width="2" stroke-linecap="round"/>
        </svg>
      </div>
    </div>

    <div class="chat-area">
      <div class="sys-evt">14 May 2026</div>

      <div class="mb-r-w">
        <div class="wa-tmpl">
              <div class="wa-hdr-img" style="height:90px;background:linear-gradient(150deg,#FFA000,#E65100);">
                <svg width="34" height="34" viewBox="0 0 24 24" fill="none">
      <path d="M6 7V6a6 6 0 0112 0v1" stroke="white" stroke-width="2" stroke-linecap="round"/>
      <path d="M4 7h16l-1 14H5L4 7z" stroke="white" stroke-width="2" stroke-linejoin="round"/>
    </svg>
                 <div class="cta-text">
    LIST YOUR STOCK
  </div>
              </div>
              <div class="wa-tmpl-body">
                <b><strong>Hello Rahul </strong>.</b><br><br>
                 
                Apna stock list kariye 📦<br><br>
                Aaj 500 KG Plastic Bottles dhoondh rahe hain<br><br>
                Aaj 5 steel mills HMS 1&amp;2 dhoondh rahe hain. Fresh stock list karne ke <b>3 simple steps:</b><br><br>
                • 📸 <b>Photo + voice note</b> bhejiye — sabse fast<br>
                • 📝 Ya text me likhiye: material, MT, rate<br>
                • 💬 Ya seedha team ko message kariye<br><br>
                <span style="color:#7a5b00;">Listing draft 30 second me taiyaar ho jaayega.</span>
              </div>
              <div class="wa-tmpl-footer">Fresh listings get matched first</div>
              <div class="wa-tmpl-time">9:32 AM</div>
              <div class="wa-tmpl-btns">
                <button class="wa-cta-btn accept">List New Stock</button>
              </div>
              </div>
            </div>
          </div>
          <div class="input-bar">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="10" stroke="#54656f" stroke-width="1.8"/><path d="M12 8v8M8 12h8" stroke="#54656f" stroke-width="1.8" stroke-linecap="round"/></svg>
            <div class="input-field">Type a message</div>
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 1a3 3 0 00-3 3v8a3 3 0 006 0V4a3 3 0 00-3-3z" stroke="#54656f" stroke-width="1.8"/><path d="M19 10v2a7 7 0 01-14 0v-2M12 19v4M8 23h8" stroke="#54656f" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
          </div>
        </div>
        <div class="screen-desc" style="background:#fff8e1;border:1px solid #ffe082;">
          Rahul receives campaign messages asking whether stock is available.

If stock is available, he is prompted to list the stock immediately enabling fast matching and quicker buyer connect.
        </div>
      </div>

  </div><!-- /screens-area -->

  <!-- Desktop Nav bar -->
  <div class="nav-bar">
    <button class="nav-btn" id="desk-prev" onclick="desktopNavigate(-1)" disabled>← Prev</button>
    <div style="display:flex;align-items:center;gap:16px;">
      <a href="index.html" style="font-size:12px;color:#888;text-decoration:none;font-weight:600;">← Main Menu</a>
      <span style="font-size:13px;color:#888;" id="desk-counter">Step 1 of 6</span>
    </div>
    <button class="nav-btn primary" id="desk-next" onclick="desktopNavigate(1)">Next →</button>
  </div>

</main><!-- /main -->

<!-- Mobile nav -->
<div class="mob-swipe-hint" id="mob-nav-bar">
  <div style="display:flex;flex-direction:column;align-items:flex-start;gap:4px;">
    <button class="mob-prev-btn" id="mob-prev" onclick="mobNavigate(-1)" disabled>← Prev</button>
    <a href="index.html" style="font-size:10px;color:#1B3A6B;font-weight:600;text-decoration:none;padding-left:2px;">⌂ Menu</a>
  </div>
  <div class="mob-swipe-dots" id="mob-dots"></div>
  <button class="mob-next-btn" id="mob-next" onclick="mobNavigate(1)">Next →</button>
</div>

<script>
const steps = [
  { title:'Step 1 — Problem &amp; Solution', desc:'<span style="color:#555;font-size:12px;">ZoTok replaces this fragmented process with a single controlled workflow..</span><span class="tag tag-intro">Intro</span>' },
  { title:'Step 2 — Campaign Data Sheet', desc:'<span style="color:#555;font-size:12px;">When buyer demand is identified, ZoTok initiates a stock sourcing request to relevant sellers.</span><span class="tag tag-sheet">Google Sheets</span><span class="tag tag-admin">Coordinator</span>' },
  { title:'Step 3 — Open ZoTok Add-on', desc:'<span style="color:#555;font-size:12px;">Extensions › Zotok › Campaign › Send Messages — the ZoTok Workspace add-on lives in the menu, no app to switch to.</span><span class="tag tag-broadcast">Workspace Add-on</span>' },
  { title:'Step 4 — Broadcast Sent', desc:'<span style="color:#555;font-size:12px;">42 messages queued · 1 template variants · delivered in under 2 minutes.</span><span class="tag tag-broadcast">638 Recipients</span>' },
  { title:'Step 5 — Recipients Receive Rate', desc:'<span style="color:#555;font-size:12px;"> Rahul receives WhatsApp messages asking if the required buyer demand is available. </span><span class="tag tag-waba">2 Variants</span>' },
  
];
const MOBILE_BP = 768;
function isMobile(){ return window.innerWidth <= MOBILE_BP; }

const sa = document.querySelector('.screens-area');
const stepSections = Array.from(document.querySelectorAll('.step-section'));

const allSlides = [];
const slideToStep = {};
const stepFirstSlide = {};

stepSections.forEach((section, idx) => {
  const stepNum = idx + 1;
  stepFirstSlide[stepNum] = allSlides.length;
  Array.from(section.querySelectorAll('.screen-wrap')).forEach(sw => {
    allSlides.push(sw);
    slideToStep[allSlides.length - 1] = stepNum;
  });
});
const totalSlides = allSlides.length;

function getSlideInfo(slideIdx){
  const stepNum = slideToStep[slideIdx];
  const firstIdx = stepFirstSlide[stepNum];
  const nextFirst = stepFirstSlide[stepNum + 1] ?? totalSlides;
  return { stepNum, slideInStep: slideIdx - firstIdx + 1, countInStep: nextFirst - firstIdx };
}

const dotsContainer = document.getElementById('mob-dots');
steps.forEach((_, i) => {
  const d = document.createElement('div');
  d.className = 'mob-dot' + (i === 0 ? ' active' : '');
  dotsContainer.appendChild(d);
});

let curSlide = 0, curStep = 1, descTimer = null;

function updateMobileHeader(slideIdx){
  const { stepNum } = getSlideInfo(slideIdx);
  const slide = allSlides[slideIdx];
  const baseTitle = steps[stepNum-1].title;
  document.getElementById('step-title').innerHTML = baseTitle;
  document.querySelectorAll('.step-item').forEach((el,i) => el.classList.toggle('active', i === stepNum-1));
  document.querySelectorAll('.mob-dot').forEach((d,i) => d.classList.toggle('active', i === stepNum-1));
  document.getElementById('mob-prev').disabled = slideIdx === 0;
  const isLast = slideIdx === totalSlides - 1;
  const mobNext = document.getElementById('mob-next');
  if(mobNext){ mobNext.disabled = isLast; }
  curSlide = slideIdx; curStep = stepNum;
  clearTimeout(descTimer);
  document.querySelectorAll('.screen-desc').forEach(el => el.classList.remove('desc-visible'));
  const currentDesc = slide ? slide.querySelector('.screen-desc') : null;
  if(currentDesc){ descTimer = setTimeout(() => currentDesc.classList.add('desc-visible'), 1500); }
}

function scrollToSlide(idx){
  idx = Math.max(0, Math.min(idx, totalSlides - 1));
  sa.scrollTo({ left: idx * sa.clientWidth, behavior:'smooth' });
  updateMobileHeader(idx);
}
function mobNavigate(d){ scrollToSlide(curSlide + d); }

let scrollDebounce;
sa.addEventListener('scroll', () => {
  clearTimeout(scrollDebounce);
  scrollDebounce = setTimeout(() => {
    const w = sa.clientWidth; if(!w) return;
    const idx = Math.min(Math.round(sa.scrollLeft / w), totalSlides - 1);
    if(idx !== curSlide) updateMobileHeader(idx);
  }, 80);
}, { passive:true });

let desktopStep = 1;

function showDesktopStep(n){
  const total = steps.length;
  n = Math.max(1, Math.min(total, n));
  stepSections.forEach(s => s.classList.remove('active'));
  const sec = document.getElementById('step-' + n);
  if(sec) sec.classList.add('active');
  desktopStep = n;
  document.getElementById('step-title').innerHTML = steps[n-1].title;
  document.getElementById('step-counter').textContent = `Step ${n} of ${total}`;
  document.getElementById('step-desc-bar').innerHTML = steps[n-1].desc;
  document.querySelectorAll('.step-item').forEach((el,i) => el.classList.toggle('active', i === n-1));
  const dp = document.getElementById('desk-prev');
  const dn = document.getElementById('desk-next');
  if(dp) dp.disabled = n === 1;
  const atEnd = n === total;
  if(dn){ dn.disabled = atEnd; dn.style.display = atEnd ? 'none' : ''; }
  let nextMod = document.getElementById('desk-next-module');
  if(!nextMod){
    nextMod = document.createElement('a');
    nextMod.id = 'desk-next-module';
    nextMod.href = 'index.html';
    nextMod.className = 'nav-btn primary';
    nextMod.style.textDecoration = 'none';
    nextMod.textContent = '← Back to Menu';
    dn.parentNode.insertBefore(nextMod, dn.nextSibling);
  }
  nextMod.style.display = atEnd ? '' : 'none';
  document.getElementById('desk-counter').textContent = `Step ${n} of ${total}`;
  if(n === 6) setTimeout(function(){ var c=document.getElementById('s6s1-chat'); if(c) c.scrollTop=c.scrollHeight; }, 80);
}

function desktopNavigate(d){ showDesktopStep(desktopStep + d); }

function scrollToStep(stepNum){
  closeSidebar();
  if(isMobile()) scrollToSlide(stepFirstSlide[stepNum] ?? 0);
  else showDesktopStep(stepNum);
}
function openSidebar(){
  document.querySelector('.sidebar').classList.add('mob-open');
  document.getElementById('mob-overlay').classList.add('mob-open');
}
function closeSidebar(){
  document.querySelector('.sidebar').classList.remove('mob-open');
  document.getElementById('mob-overlay').classList.remove('mob-open');
}
document.addEventListener('keydown', e => {
  if(isMobile()){
    if(e.key==='ArrowRight'||e.key==='ArrowDown') mobNavigate(1);
    if(e.key==='ArrowLeft'||e.key==='ArrowUp') mobNavigate(-1);
  } else {
    if(e.key==='ArrowRight'||e.key==='ArrowDown') desktopNavigate(1);
    if(e.key==='ArrowLeft'||e.key==='ArrowUp') desktopNavigate(-1);
  }
});
window.addEventListener('resize', () => {
  if(!isMobile()){
    showDesktopStep(desktopStep);
  }
});
showDesktopStep(1);
</script>
</body>
</html>

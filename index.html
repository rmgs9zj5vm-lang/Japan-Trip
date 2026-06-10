<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🗾 Japan Travel Planner</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@300;400;600;700&family=Shippori+Mincho:wght@400;700&family=Cormorant+Garamond:wght@600;700&display=swap" rel="stylesheet">
<style>
:root{
  /* ── Earth Tone Palette ── */
  --ink:    #2c1f0f;
  --paper:  #f4ede0;
  --card:   #faf6ef;
  --border: #d6c9b0;
  --border2:#c4b49a;
  --muted:  #8a7560;
  --accent: #8b5e3c;
  --accent2:#a87050;
  --accentbg:rgba(139,94,60,.09);

  /* functional */
  --red:    #8a3a2a;
  --gold:   #b08030;
  --green:  #4a7040;
  --blue:   #3a5a7a;
  --orange: #a06020;
  --warm:   #c8a87a;
}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--paper);font-family:'Noto Sans Thai',sans-serif;color:var(--ink);overflow-x:hidden;}
.page{display:none;min-height:100vh;}
.page.active{display:block;}

/* ── TOP NAV ── */
.top-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;box-shadow:0 2px 8px rgba(44,31,15,.25);}
.top-nav .logo{font-family:'Cormorant Garamond',serif;font-size:20px;color:#f4ede0;letter-spacing:3px;white-space:nowrap;font-weight:700;}
.top-nav .logo span{color:var(--warm);}
.top-nav .spacer{flex:1;}
.nav-btn{padding:5px 13px;border-radius:16px;border:1px solid rgba(244,237,224,.2);background:transparent;color:#c8b89a;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:11px;transition:all .2s;white-space:nowrap;}
.nav-btn:hover,.nav-btn.on{background:var(--accent);color:#f4ede0;border-color:var(--accent);}
.breadcrumb{font-size:11px;color:#a89070;display:flex;align-items:center;gap:5px;flex-wrap:wrap;}
.breadcrumb span{color:var(--warm);cursor:pointer;}
.breadcrumb span:hover{text-decoration:underline;}

/* ════ HOME ════ */
.hero{background:linear-gradient(160deg,var(--ink) 0%,#3d2510 60%,#5a3520 100%);padding:36px 20px 28px;text-align:center;}
.hero h2{font-family:'Cormorant Garamond',serif;font-size:clamp(26px,5vw,58px);color:#f4ede0;letter-spacing:4px;font-weight:700;}
.hero h2 span{color:var(--warm);}
.hero p{color:#a89070;font-size:12px;margin-top:5px;}

.home-wrap{display:grid;grid-template-columns:1fr 290px;gap:0;max-width:1080px;margin:0 auto;padding:24px 18px;}
@media(max-width:720px){.home-wrap{grid-template-columns:1fr;}}

/* MAP */
.map-box{background:var(--card);border-radius:14px;border:1px solid var(--border);padding:18px;}
.box-title{font-family:'Shippori Mincho',serif;font-size:15px;border-bottom:2px solid var(--accent);padding-bottom:7px;margin-bottom:10px;color:var(--ink);}
.map-hint{font-size:10px;color:var(--muted);margin-bottom:8px;}
svg#jmap{width:100%;max-height:450px;display:block;margin:0 auto;}
.mr{fill:#e8dbc0;stroke:#c4a87a;stroke-width:1.5;cursor:pointer;transition:all .2s;}
.mr:hover,.mr.hi{fill:var(--warm);stroke:var(--accent);stroke-width:2;}
.ml{font-size:8px;fill:#3a2510;font-family:'Noto Sans Thai',sans-serif;pointer-events:none;font-weight:700;text-anchor:middle;}

/* REGION LIST */
.region-list{padding-left:18px;}
@media(max-width:720px){.region-list{padding-left:0;padding-top:18px;}}
.region-list .box-title{margin-bottom:10px;}
.rbtn{display:flex;align-items:center;gap:9px;width:100%;padding:10px 13px;background:var(--card);border:1px solid var(--border);border-radius:10px;margin-bottom:7px;cursor:pointer;text-align:left;transition:all .2s;}
.rbtn:hover{background:var(--ink);color:#f4ede0;transform:translateX(3px);}
.rbtn:hover .rsub{color:#a89070;}
.ricon{font-size:19px;}
.rinfo{flex:1;}
.rname{font-weight:700;font-size:13px;}
.rsub{font-size:10px;color:var(--muted);margin-top:1px;}
.rbadge{font-size:9px;padding:2px 7px;border-radius:10px;background:var(--accent);color:#f4ede0;white-space:nowrap;}

/* HOME TABS */
.htabs{display:flex;gap:6px;flex-wrap:wrap;}
.htab-btn{padding:7px 16px;border-radius:18px;border:1.5px solid var(--border);background:var(--card);cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.htab-btn:hover,.htab-btn.on{background:var(--ink);color:#f4ede0;border-color:var(--ink);}
.sec{max-width:1080px;margin:0 auto;padding:0 18px 44px;}
.sec-title{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--accent);padding-left:10px;margin-bottom:16px;color:var(--ink);}

/* RAIL PASS */
.rail-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:12px;}
.rcard{background:var(--card);border-radius:12px;border:1px solid var(--border);padding:14px;transition:box-shadow .2s;}
.rcard:hover{box-shadow:0 5px 18px rgba(44,31,15,.12);}
.rcard-h{display:flex;align-items:center;gap:9px;margin-bottom:9px;}
.rice{font-size:26px;}.rn{font-weight:700;font-size:12px;color:var(--ink);}.rs{font-size:10px;color:var(--muted);}
.rcov{font-size:11px;color:var(--muted);line-height:1.7;margin-bottom:8px;}
.rprice{font-size:11px;font-weight:700;color:var(--accent);margin-bottom:7px;}
.rtags{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:8px;}
.rtag{font-size:9px;padding:2px 7px;border-radius:10px;background:var(--paper);color:var(--muted);border:1px solid var(--border);}
.rlink{display:inline-flex;align-items:center;gap:3px;font-size:10px;color:var(--blue);text-decoration:none;font-weight:600;}
.rlink:hover{text-decoration:underline;}
.tip{background:#fdf6ec;border:1px solid #d6c090;border-radius:10px;padding:12px;font-size:11px;line-height:1.9;color:var(--muted);}
.tip strong{color:var(--orange);}
.tip a{color:var(--blue);}

/* CALENDAR */
.cal-wrap{overflow-x:auto;border-radius:11px;border:1px solid var(--border);}
table.cal{width:100%;border-collapse:collapse;min-width:680px;background:var(--card);}
table.cal thead th{background:var(--ink);color:#f4ede0;font-size:10px;padding:9px 4px;text-align:center;}
table.cal thead th:first-child{text-align:left;padding-left:12px;min-width:155px;}
table.cal tbody tr{border-bottom:1px solid var(--border);}
table.cal tbody tr:last-child{border:none;}
table.cal tbody tr:hover{background:#faf4e8;}
.ccity{padding:11px 12px;font-weight:700;font-size:11px;border-right:1px solid var(--border);color:var(--ink);}
.ccity span{display:block;font-size:9px;color:var(--muted);font-weight:400;}
td.cc{text-align:center;padding:7px 2px;font-size:13px;position:relative;cursor:default;}
td.cc:hover::after{content:attr(data-tip);position:absolute;bottom:calc(100%+3px);left:50%;transform:translateX(-50%);background:var(--ink);color:#f4ede0;font-size:9px;padding:3px 7px;border-radius:5px;white-space:nowrap;z-index:99;pointer-events:none;}
.cb{background:rgba(74,112,64,.13);}.cs{background:rgba(180,80,100,.13);}.ck{background:rgba(176,128,48,.16);}
.cn{background:rgba(58,90,122,.12);}.ca{background:rgba(138,58,42,.1);}.co{background:rgba(44,31,15,.04);}.cr{background:rgba(58,80,120,.1);}
.leg-row{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:14px;}
.leg{display:flex;align-items:center;gap:4px;font-size:10px;background:var(--card);border:1px solid var(--border);border-radius:18px;padding:3px 9px;color:var(--ink);}

/* ════ REGION PAGE ════ */
.region-hero{position:relative;overflow:hidden;height:180px;display:flex;align-items:flex-end;background:linear-gradient(135deg,var(--ink),#3d2510);}
.region-hero-img{position:absolute;inset:0;background-size:cover;background-position:center;opacity:.35;}
.region-hero-content{position:relative;z-index:2;padding:18px 24px;color:#f4ede0;width:100%;}
.region-hero-content h1{font-family:'Cormorant Garamond',serif;font-size:clamp(24px,4vw,46px);letter-spacing:3px;font-weight:700;}
.region-hero-content p{color:#c8b89a;font-size:11px;margin-top:3px;}
.best-bar{background:var(--ink);color:#f4ede0;padding:8px 22px;font-size:11px;display:flex;align-items:center;gap:5px;flex-wrap:wrap;border-bottom:1px solid rgba(200,168,122,.2);}
.best-bar strong{color:var(--warm);}

.region-content{max-width:940px;margin:0 auto;padding:22px 18px 50px;}
.sec-label{font-family:'Shippori Mincho',serif;font-size:16px;color:var(--ink);border-left:3px solid var(--accent);padding-left:10px;margin-bottom:14px;}

/* Sub-city CARDS */
.city-cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:14px;margin-bottom:28px;}
.city-card{background:var(--card);border-radius:12px;border:1.5px solid var(--border);overflow:hidden;cursor:pointer;transition:transform .2s,box-shadow .2s,border-color .2s;}
.city-card:hover{transform:translateY(-4px);box-shadow:0 8px 24px rgba(44,31,15,.14);border-color:var(--accent);}
.city-card-img{width:100%;height:110px;background:#e0d0b8 center/cover no-repeat;}
.city-card-body{padding:12px;}
.city-card-name{font-weight:700;font-size:14px;margin-bottom:3px;color:var(--ink);}
.city-card-sub{font-size:10px;color:var(--muted);line-height:1.5;}
.city-card-arrow{display:flex;align-items:center;justify-content:space-between;margin-top:8px;}
.city-card-count{font-size:10px;color:var(--blue);}
.city-card-go{font-size:18px;color:var(--accent);}

/* ════ CITY PAGE ════ */
.city-hero{position:relative;overflow:hidden;height:160px;display:flex;align-items:flex-end;background:linear-gradient(135deg,var(--ink),#3d2510);}
.city-hero-img{position:absolute;inset:0;background-size:cover;background-position:center;opacity:.38;}
.city-hero-content{position:relative;z-index:2;padding:16px 22px;color:#f4ede0;width:100%;}
.city-hero-content h1{font-family:'Cormorant Garamond',serif;font-size:clamp(22px,4vw,42px);letter-spacing:3px;font-weight:700;}
.city-hero-content p{color:#c8b89a;font-size:11px;margin-top:2px;}

.city-content{max-width:940px;margin:0 auto;padding:20px 18px 50px;}

/* Progress */
.prog-wrap{margin-bottom:16px;}
.prog-label{font-size:11px;color:var(--muted);margin-bottom:4px;}
.prog-bar{height:5px;background:var(--border);border-radius:3px;overflow:hidden;}
.prog-fill{height:100%;background:var(--green);border-radius:3px;transition:width .4s;}

/* Inner tabs */
.itabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:16px;}
.itab{padding:7px 14px;border-radius:16px;border:1.5px solid var(--border);background:var(--card);cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.itab.on{background:var(--accent);color:#f4ede0;border-color:var(--accent);}
.ipane{display:none;}
.ipane.on{display:block;}

/* Place cards */
.pg{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:13px;}
.pc{background:var(--card);border-radius:11px;border:1px solid var(--border);overflow:hidden;transition:transform .2s,box-shadow .2s;}
.pc:hover{transform:translateY(-3px);box-shadow:0 7px 20px rgba(44,31,15,.12);}
.pimg{width:100%;height:125px;background:#e0d0b8 center/cover no-repeat;position:relative;}
.pbadge{position:absolute;top:6px;right:6px;font-size:9px;padding:2px 6px;border-radius:9px;font-weight:700;}
.bm{background:var(--red);color:#f4ede0;}
.bl{background:var(--green);color:#f4ede0;}
.bf{background:var(--gold);color:#f4ede0;}
.bc{background:#7a5a8a;color:#f4ede0;}
.pbody{padding:11px;}
.pname{font-weight:700;font-size:13px;margin-bottom:2px;color:var(--ink);}
.pjp{font-size:10px;color:var(--muted);margin-bottom:5px;font-family:'Shippori Mincho',serif;}
.pdesc{font-size:11px;color:var(--muted);line-height:1.6;margin-bottom:9px;}
.pact{display:flex;gap:6px;align-items:center;flex-wrap:wrap;}
.chk{width:25px;height:25px;border-radius:50%;border:2px solid var(--border);background:var(--card);cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:12px;transition:all .2s;flex-shrink:0;}
.chk.on{background:var(--green);border-color:var(--green);color:#fff;}
.del-btn{position:absolute;top:6px;left:6px;width:22px;height:22px;border-radius:50%;background:rgba(138,58,42,.85);border:none;color:#fff;font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center;opacity:0;transition:opacity .2s;line-height:1;font-weight:700;z-index:5;}
.pc:hover .del-btn{opacity:1;}
.del-badge{font-size:9px;padding:2px 6px;border-radius:8px;background:rgba(74,112,64,.15);color:var(--green);border:1px solid rgba(74,112,64,.3);font-weight:600;margin-left:4px;}
.mapbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;background:var(--blue);color:#f4ede0;border-radius:14px;font-size:10px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;border:none;cursor:pointer;}
.mapbtn:hover{opacity:.85;}
.extbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;background:var(--muted);color:#f4ede0;border-radius:14px;font-size:10px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.extbtn:hover{opacity:.85;}

/* Trail cards */
.tg{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:13px;}
.tc{background:var(--card);border-radius:11px;border:1px solid var(--border);padding:13px;display:flex;flex-direction:column;gap:7px;transition:transform .2s,box-shadow .2s;}
.tc:hover{transform:translateY(-3px);box-shadow:0 7px 20px rgba(44,31,15,.12);}
.tc-h{display:flex;align-items:center;gap:8px;}
.tc-icon{font-size:22px;}
.tc-name{font-weight:700;font-size:13px;color:var(--ink);}
.tc-jp{font-size:10px;color:var(--muted);}
.tc-meta{display:flex;gap:6px;flex-wrap:wrap;}
.ttag{font-size:9px;padding:2px 8px;border-radius:9px;background:var(--paper);border:1px solid var(--border);color:var(--muted);}
.t-easy{background:rgba(74,112,64,.12);color:var(--green);border-color:rgba(74,112,64,.3);}
.t-med{background:rgba(160,96,32,.12);color:var(--orange);border-color:rgba(160,96,32,.3);}
.t-hard{background:rgba(138,58,42,.12);color:var(--red);border-color:rgba(138,58,42,.3);}
.tc-desc{font-size:11px;color:var(--muted);line-height:1.6;}
.tc-links{display:flex;gap:6px;flex-wrap:wrap;}

/* Add form */
.add-sec{margin-top:24px;}
.add-sec h3{font-size:13px;font-weight:700;margin-bottom:11px;color:var(--ink);}
.addform{display:grid;grid-template-columns:1fr 1fr;gap:7px;}
@media(max-width:480px){.addform{grid-template-columns:1fr;}}
.addform input,.addform select,.addform textarea{padding:8px 11px;border:1.5px solid var(--border);border-radius:7px;font-family:'Noto Sans Thai',sans-serif;font-size:12px;background:var(--card);color:var(--ink);}
.addform input:focus,.addform select:focus,.addform textarea:focus{outline:none;border-color:var(--accent);}
.addform textarea{grid-column:1/-1;resize:vertical;min-height:56px;}
.addbtn{grid-column:1/-1;padding:9px;background:var(--ink);color:#f4ede0;border:none;border-radius:7px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:13px;font-weight:700;transition:background .2s;}
.addbtn:hover{background:var(--accent);}
.full{grid-column:1/-1;}
hr.div{border:none;border-top:1px solid var(--border);margin:22px 0;}
.empty{color:var(--muted);font-size:12px;padding:10px 0;}

/* ════ RAIL PASS PAGE (pgRail) ════ */
.rp-nav,.tp-nav,.ap-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;}
.rp-nav .logo,.tp-nav .logo,.ap-nav .logo{font-family:'Cormorant Garamond',serif;font-size:20px;color:#f4ede0;letter-spacing:3px;font-weight:700;}
.rp-nav .logo span,.tp-nav .logo span,.ap-nav .logo span{color:var(--warm);}
.rp-hero,.tp-hero,.ap-hero{background:linear-gradient(135deg,var(--ink),#3d2510);padding:30px 20px;text-align:center;}
.rp-hero h1,.tp-hero h1,.ap-hero h1{font-family:'Cormorant Garamond',serif;font-size:clamp(24px,5vw,50px);color:#f4ede0;letter-spacing:4px;font-weight:700;}
.rp-hero h1 span,.tp-hero h1 span,.ap-hero h1 span{color:var(--warm);}
.rp-hero p,.tp-hero p,.ap-hero p{color:#a89070;font-size:12px;margin-top:5px;}
.rp-tabbar{display:flex;gap:0;border-bottom:2px solid var(--border);background:var(--card);position:sticky;top:57px;z-index:90;overflow-x:auto;}
.rp-tab{padding:11px 18px;font-family:'Noto Sans Thai',sans-serif;font-size:12px;background:none;border:none;cursor:pointer;color:var(--muted);border-bottom:3px solid transparent;margin-bottom:-2px;transition:all .2s;white-space:nowrap;}
.rp-tab.on{color:var(--accent);border-bottom-color:var(--accent);font-weight:700;}
.rp-pane{display:none;max-width:1040px;margin:0 auto;padding:26px 18px 60px;}
.rp-pane.on{display:block;}
.rp-stitle{font-family:'Shippori Mincho',serif;font-size:19px;border-left:4px solid var(--accent);padding-left:11px;margin-bottom:18px;color:var(--ink);}
.rp-tip{background:#fdf6ec;border:1px solid #d6c090;border-radius:11px;padding:13px;margin-bottom:22px;font-size:12px;line-height:1.9;color:var(--muted);}
.rp-tip strong{color:var(--orange);}
.rp-tip a{color:var(--blue);}
.rp-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(265px,1fr));gap:15px;}
.rp-card{background:var(--card);border-radius:13px;border:2px solid var(--border);padding:17px;cursor:pointer;transition:all .2s;position:relative;overflow:hidden;}
.rp-card::before{content:'';position:absolute;top:0;left:0;right:0;height:4px;background:var(--rpc,var(--blue));}
.rp-card:hover{transform:translateY(-4px);box-shadow:0 10px 28px rgba(44,31,15,.14);border-color:var(--rpc,var(--blue));}
.rp-card-head{display:flex;align-items:center;gap:11px;margin-bottom:11px;}
.rp-icon{font-size:30px;}.rp-title{font-weight:700;font-size:14px;line-height:1.3;color:var(--ink);}.rp-sub{font-size:11px;color:var(--muted);margin-top:2px;}
.rp-badge{display:inline-block;color:#f4ede0;font-size:10px;font-weight:700;padding:3px 9px;border-radius:18px;margin-bottom:9px;}
.rp-ctags{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:11px;}
.rp-ctag{font-size:9px;padding:2px 7px;border-radius:9px;background:var(--paper);border:1px solid var(--border);color:var(--muted);}
.rp-desc{font-size:11px;color:var(--muted);line-height:1.7;margin-bottom:11px;}
.rp-cta{display:flex;align-items:center;justify-content:space-between;}
.rp-detail{font-size:11px;font-weight:700;cursor:pointer;background:none;border:none;font-family:'Noto Sans Thai',sans-serif;}
.rp-overlay{display:none;position:fixed;inset:0;background:rgba(44,31,15,.6);z-index:500;overflow-y:auto;padding:18px;}
.rp-overlay.on{display:flex;align-items:flex-start;justify-content:center;}
.rp-modal{background:var(--card);border-radius:17px;max-width:800px;width:100%;margin:auto;overflow:hidden;border:1px solid var(--border);}
.rp-mhero{padding:22px 26px 18px;position:relative;}
.rp-mhero h2{font-family:'Cormorant Garamond',serif;font-size:clamp(22px,4vw,38px);letter-spacing:3px;color:#f4ede0;font-weight:700;}
.rp-mhero p{color:rgba(244,237,224,.75);font-size:11px;margin-top:3px;}
.rp-mclose{position:absolute;top:14px;right:14px;width:32px;height:32px;border-radius:50%;background:rgba(244,237,224,.2);border:none;color:#f4ede0;font-size:17px;cursor:pointer;display:flex;align-items:center;justify-content:center;}
.rp-mbody{padding:22px 26px 28px;}
.rp-msecs{display:grid;grid-template-columns:1fr 1fr;gap:18px;}
@media(max-width:560px){.rp-msecs{grid-template-columns:1fr;}}
.rp-msec h3{font-size:12px;font-weight:700;margin-bottom:9px;display:flex;align-items:center;gap:5px;color:var(--ink);}
.rp-ptable{width:100%;border-collapse:collapse;font-size:11px;}
.rp-ptable th{background:var(--paper);padding:6px 9px;text-align:left;font-weight:700;border-bottom:1px solid var(--border);color:var(--ink);}
.rp-ptable td{padding:6px 9px;border-bottom:1px solid var(--border);color:var(--muted);}
.rp-ptable tr:last-child td{border:none;}
.rp-ilist{list-style:none;}
.rp-ilist li{font-size:11px;color:var(--muted);padding:5px 0;border-bottom:1px solid var(--border);display:flex;gap:7px;line-height:1.6;}
.rp-ilist li:last-child{border:none;}
.rp-ilist li::before{content:'·';color:var(--accent);flex-shrink:0;}
.rp-mapwrap{margin:18px 0;}
.rp-mapwrap h3{font-size:12px;font-weight:700;margin-bottom:9px;color:var(--ink);}
.rp-mapimg{width:100%;max-height:300px;object-fit:contain;border-radius:9px;border:1px solid var(--border);background:var(--paper);display:block;}
.rp-mapsrc{font-size:9px;color:var(--muted);margin-top:4px;text-align:right;}
.rp-mapsrc a{color:var(--blue);text-decoration:none;}
.rp-mapfb{display:none;flex-direction:column;align-items:center;gap:9px;padding:26px;background:var(--paper);border-radius:9px;border:1px solid var(--border);}
.rp-schref{background:var(--paper);border-radius:9px;padding:12px;margin-top:14px;font-size:11px;color:var(--muted);line-height:1.8;}
.rp-schref strong{color:var(--ink);}
.rp-schref a{color:var(--blue);text-decoration:none;}
.rp-lgrid{display:grid;grid-template-columns:1fr 1fr;gap:7px;margin-top:14px;}
@media(max-width:460px){.rp-lgrid{grid-template-columns:1fr;}}
.rp-lbtn{display:flex;align-items:center;gap:7px;padding:9px 12px;border-radius:9px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;font-size:11px;font-weight:700;transition:opacity .2s;}
.rp-lbtn:hover{opacity:.85;}
.rp-lbtn.primary{background:var(--accent);color:#f4ede0;}
.rp-lbtn.secondary{background:var(--ink);color:#f4ede0;}
.rp-lbtn.ext{background:var(--paper);color:var(--ink);border:1px solid var(--border);}
.rp-rec-intro{background:var(--card);border-radius:13px;border:1px solid var(--border);padding:18px;margin-bottom:22px;font-size:12px;color:var(--muted);line-height:1.8;}
.rp-cc-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));gap:9px;margin-bottom:22px;}
.rp-cc{display:flex;align-items:center;gap:9px;background:var(--card);border:1.5px solid var(--border);border-radius:9px;padding:9px 12px;cursor:pointer;transition:all .2s;}
.rp-cc.on{background:var(--ink);color:#f4ede0;border-color:var(--ink);}
.rp-cbox{width:17px;height:17px;border-radius:4px;border:2px solid var(--border);background:var(--card);display:flex;align-items:center;justify-content:center;font-size:10px;flex-shrink:0;transition:all .2s;}
.rp-cc.on .rp-cbox{background:var(--warm);border-color:var(--warm);color:var(--ink);font-weight:700;}
.rp-clabel{font-size:12px;font-weight:600;color:var(--ink);}
.rp-csub{font-size:9px;color:var(--muted);margin-top:1px;}
.rp-cc.on .rp-clabel{color:#f4ede0;}
.rp-cc.on .rp-csub{color:rgba(244,237,224,.65);}
.rp-recbtn{padding:11px 26px;background:var(--accent);color:#f4ede0;border:none;border-radius:9px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:13px;font-weight:700;transition:background .2s;}
.rp-recbtn:hover{background:var(--accent2);}
.rp-result{display:none;margin-top:22px;}
.rp-result.on{display:block;}
.rp-rcard{background:var(--card);border-radius:13px;border:2px solid var(--border);padding:18px;margin-bottom:14px;}
.rp-rcard.best{border-color:var(--gold);}
.rp-rhead{display:flex;align-items:center;gap:11px;margin-bottom:11px;}
.rp-rrank{font-size:20px;}
.rp-rname{font-weight:700;font-size:14px;color:var(--ink);}
.rp-rsub{font-size:10px;color:var(--muted);}
.rp-rwhy{font-size:12px;color:var(--muted);line-height:1.8;margin-bottom:11px;}
.rp-rsave{display:inline-block;font-size:10px;font-weight:700;padding:3px 11px;border-radius:18px;background:rgba(74,112,64,.12);color:var(--green);margin-bottom:11px;border:1px solid rgba(74,112,64,.25);}
.rp-bestbadge{display:inline-block;font-size:9px;font-weight:700;padding:2px 8px;border-radius:18px;background:var(--gold);color:#fff;margin-left:7px;}
.rp-rbtn{padding:6px 13px;color:#f4ede0;border:none;border-radius:7px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:10px;font-weight:700;text-decoration:none;display:inline-flex;align-items:center;gap:4px;}

/* ════ TRANSPORT PAGE ════ */
.tp-city-wrap{max-width:1040px;margin:0 auto;padding:24px 18px 0;}
.tp-stitle{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--green);padding-left:11px;margin-bottom:16px;color:var(--ink);}
.tp-city-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(145px,1fr));gap:10px;margin-bottom:28px;}
.tp-city-btn{background:var(--card);border:1.5px solid var(--border);border-radius:11px;padding:12px;cursor:pointer;text-align:center;transition:all .2s;font-family:'Noto Sans Thai',sans-serif;}
.tp-city-btn:hover,.tp-city-btn.on{background:var(--ink);color:#f4ede0;border-color:var(--ink);transform:translateY(-2px);box-shadow:0 6px 16px rgba(44,31,15,.14);}
.tp-city-btn .tci{font-size:24px;display:block;margin-bottom:5px;}
.tp-city-btn .tcn{font-size:12px;font-weight:700;color:var(--ink);}
.tp-city-btn.on .tcn{color:#f4ede0;}
.tp-city-btn .tcs{font-size:10px;color:var(--muted);margin-top:2px;}
.tp-city-btn.on .tcs{color:rgba(244,237,224,.65);}
.tp-detail{max-width:1040px;margin:0 auto;padding:0 18px 60px;display:none;}
.tp-detail.on{display:block;}
.tp-detail-hdr{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px;margin-bottom:20px;}
.tp-detail-hdr h2{font-family:'Cormorant Garamond',serif;font-size:clamp(22px,4vw,36px);letter-spacing:2px;color:var(--ink);font-weight:700;}
.tp-tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:20px;}
.tp-tab{padding:7px 16px;border-radius:18px;border:1.5px solid var(--border);background:var(--card);cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.tp-tab.on{background:var(--green);color:#f4ede0;border-color:var(--green);}
.tp-pane{display:none;}
.tp-pane.on{display:block;}
.tp-line-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:16px;}
.tp-line-card{background:var(--card);border-radius:12px;border:1px solid var(--border);overflow:hidden;transition:box-shadow .2s;}
.tp-line-card:hover{box-shadow:0 6px 20px rgba(44,31,15,.12);}
.tp-line-head{padding:14px 16px 10px;display:flex;align-items:center;gap:10px;}
.tp-line-dot{width:14px;height:14px;border-radius:50%;flex-shrink:0;}
.tp-line-name{font-weight:700;font-size:14px;color:var(--ink);}
.tp-line-sub{font-size:10px;color:var(--muted);margin-top:1px;}
.tp-line-body{padding:0 16px 14px;}
.tp-line-info{font-size:11px;color:var(--muted);line-height:1.8;margin-bottom:10px;}
.tp-stops{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:10px;}
.tp-stop{font-size:9px;padding:2px 7px;border-radius:8px;background:var(--paper);color:var(--muted);border:1px solid var(--border);}
.tp-stop.key{background:rgba(74,112,64,.12);color:var(--green);font-weight:700;border-color:rgba(74,112,64,.3);}
.tp-line-links{display:flex;gap:7px;flex-wrap:wrap;}
.tp-lbtn{display:inline-flex;align-items:center;gap:5px;padding:5px 11px;border-radius:8px;font-size:10px;font-weight:700;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.tp-lbtn:hover{opacity:.85;}
.tp-lbtn.official{background:var(--blue);color:#f4ede0;}
.tp-lbtn.map{background:var(--green);color:#f4ede0;}
.tp-lbtn.info{background:var(--paper);color:var(--ink);border:1px solid var(--border);}
.tp-map-section{margin-bottom:24px;}
.tp-map-section h3{font-size:13px;font-weight:700;margin-bottom:10px;display:flex;align-items:center;gap:6px;color:var(--ink);}
.tp-map-img{width:100%;max-height:340px;object-fit:contain;border-radius:10px;border:1px solid var(--border);background:var(--paper);display:block;}
.tp-map-fb{display:none;flex-direction:column;align-items:center;gap:8px;padding:24px;background:var(--paper);border-radius:10px;border:1px solid var(--border);text-align:center;}
.tp-map-fb p{font-size:11px;color:var(--muted);}
.tp-map-src{font-size:9px;color:var(--muted);margin-top:4px;text-align:right;}
.tp-map-src a{color:var(--blue);text-decoration:none;}
.tp-tip{background:#fdf6ec;border:1px solid #d6c090;border-radius:10px;padding:13px;margin-bottom:16px;font-size:12px;line-height:1.9;color:var(--muted);}
.tp-tip strong{color:var(--orange);}
.tp-empty{color:var(--muted);font-size:12px;padding:16px 0;}

/* ════ AIRPORT PAGE ════ */
.ap-wrap{max-width:1040px;margin:0 auto;padding:26px 18px 60px;}
.ap-stitle{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--blue);padding-left:11px;margin-bottom:18px;color:var(--ink);}
.ap-tip{background:#edf2f8;border:1px solid #b0c4d8;border-radius:11px;padding:13px;margin-bottom:22px;font-size:12px;line-height:1.9;color:var(--muted);}
.ap-tip strong{color:var(--blue);}
.ap-tip a{color:var(--blue);}
.ap-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:18px;}
.ap-card{background:var(--card);border-radius:14px;border:1px solid var(--border);overflow:hidden;transition:box-shadow .2s;}
.ap-card:hover{box-shadow:0 8px 24px rgba(44,31,15,.12);}
.ap-card-head{padding:16px 18px 12px;border-bottom:1px solid var(--border);display:flex;align-items:flex-start;gap:12px;}
.ap-iata{font-family:'Cormorant Garamond',serif;font-size:28px;letter-spacing:2px;line-height:1;font-weight:700;}
.ap-airport-name{font-weight:700;font-size:13px;line-height:1.3;color:var(--ink);}
.ap-airport-city{font-size:11px;color:var(--muted);margin-top:2px;}
.ap-jrpass{display:inline-block;font-size:9px;font-weight:700;padding:2px 7px;border-radius:8px;margin-top:5px;}
.jrfree{background:rgba(74,112,64,.12);color:var(--green);border:1px solid rgba(74,112,64,.3);}
.jrno{background:rgba(138,58,42,.1);color:var(--red);border:1px solid rgba(138,58,42,.25);}
.ap-trains{padding:14px 18px;}
.ap-train{border-bottom:1px solid var(--border);padding-bottom:12px;margin-bottom:12px;}
.ap-train:last-child{border:none;margin:0;padding:0;}
.ap-train-head{display:flex;align-items:center;gap:8px;margin-bottom:7px;}
.ap-train-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0;}
.ap-train-name{font-weight:700;font-size:13px;color:var(--ink);}
.ap-train-op{font-size:10px;color:var(--muted);}
.ap-route-table{width:100%;border-collapse:collapse;font-size:11px;margin-bottom:8px;}
.ap-route-table th{background:var(--paper);padding:5px 8px;text-align:left;font-weight:700;border-bottom:1px solid var(--border);color:var(--ink);}
.ap-route-table td{padding:5px 8px;border-bottom:1px solid var(--border);color:var(--muted);}
.ap-route-table tr:last-child td{border:none;}
.ap-route-table .hl{font-weight:700;color:var(--blue);}
.ap-fare-badge{display:inline-block;font-size:9px;font-weight:700;padding:2px 6px;border-radius:6px;margin-left:4px;}
.afc{background:rgba(74,112,64,.12);color:var(--green);}
.afm{background:rgba(160,96,32,.12);color:var(--orange);}
.afp{background:rgba(122,90,138,.12);color:#7a5a8a;}
.ap-train-note{font-size:11px;color:var(--muted);line-height:1.7;margin-bottom:8px;}
.ap-train-links{display:flex;gap:6px;flex-wrap:wrap;}
.ap-lbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;border-radius:7px;font-size:10px;font-weight:700;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.ap-lbtn:hover{opacity:.85;}
.ap-lbtn.off{background:var(--blue);color:#f4ede0;}
.ap-lbtn.sched{background:var(--green);color:#f4ede0;}
.ap-lbtn.gd{background:var(--paper);color:var(--ink);border:1px solid var(--border);}
.ap-lbtn.bk{background:var(--accent);color:#f4ede0;}
.ap-compare{width:100%;border-collapse:collapse;font-size:11px;margin-top:20px;background:var(--card);border-radius:12px;overflow:hidden;border:1px solid var(--border);}
.ap-compare th{background:var(--ink);color:#f4ede0;padding:9px 10px;text-align:left;font-size:11px;}
.ap-compare td{padding:9px 10px;border-bottom:1px solid var(--border);vertical-align:top;font-size:11px;color:var(--muted);}
.ap-compare tr:last-child td{border:none;}
.ap-compare tr:hover td{background:var(--paper);}
.ap-best{color:var(--green);font-weight:700;}
.ap-warn{color:var(--orange);}

/* ════ SCROLLBAR & MISC ════ */
::-webkit-scrollbar{width:5px;height:5px;}
::-webkit-scrollbar-track{background:var(--paper);}
::-webkit-scrollbar-thumb{background:var(--border2);border-radius:4px;}
::-webkit-scrollbar-thumb:hover{background:var(--muted);}

*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--paper);font-family:'Noto Sans Thai',sans-serif;color:var(--ink);overflow-x:hidden;}
.page{display:none;min-height:100vh;}
.page.active{display:block;}

/* ── TOP NAV ── */
.top-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;}
.top-nav .logo{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#fff;letter-spacing:4px;white-space:nowrap;}
.top-nav .logo span{color:var(--gold);}
.top-nav .spacer{flex:1;}
.nav-btn{padding:5px 13px;border-radius:16px;border:1px solid rgba(255,255,255,.25);background:transparent;color:#ccc;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:11px;transition:all .2s;white-space:nowrap;}
.nav-btn:hover,.nav-btn.on{background:var(--red);color:#fff;border-color:var(--red);}
.breadcrumb{font-size:11px;color:#aaa;display:flex;align-items:center;gap:5px;flex-wrap:wrap;}
.breadcrumb span{color:var(--gold);cursor:pointer;}
.breadcrumb span:hover{text-decoration:underline;}

/* ════════════════════ HOME ════════════════════ */
.hero{background:linear-gradient(160deg,#1a1a2e 60%,#2d1810);padding:36px 20px 28px;text-align:center;}
.hero h2{font-family:'Bebas Neue',sans-serif;font-size:clamp(26px,5vw,58px);color:#fff;letter-spacing:6px;}
.hero h2 span{color:var(--gold);}
.hero p{color:#aaa;font-size:12px;margin-top:5px;}

.home-wrap{display:grid;grid-template-columns:1fr 290px;gap:0;max-width:1080px;margin:0 auto;padding:24px 18px;}
@media(max-width:720px){.home-wrap{grid-template-columns:1fr;}}

/* MAP */
.map-box{background:#fff;border-radius:14px;border:1px solid var(--border);padding:18px;}
.box-title{font-family:'Shippori Mincho',serif;font-size:15px;border-bottom:2px solid var(--red);padding-bottom:7px;margin-bottom:10px;}
.map-hint{font-size:10px;color:var(--muted);margin-bottom:8px;}
svg#jmap{width:100%;max-height:450px;display:block;margin:0 auto;}
.mr{fill:#e8dcc8;stroke:#c5b99a;stroke-width:1.5;cursor:pointer;transition:all .2s;}
.mr:hover,.mr.hi{fill:var(--gold);stroke:var(--red);stroke-width:2;}
.ml{font-size:8px;fill:#333;font-family:'Noto Sans Thai',sans-serif;pointer-events:none;font-weight:700;text-anchor:middle;}

/* REGION LIST */
.region-list{padding-left:18px;}
@media(max-width:720px){.region-list{padding-left:0;padding-top:18px;}}
.region-list .box-title{margin-bottom:10px;}
.rbtn{display:flex;align-items:center;gap:9px;width:100%;padding:10px 13px;background:#fff;border:1px solid var(--border);border-radius:10px;margin-bottom:7px;cursor:pointer;text-align:left;transition:all .2s;}
.rbtn:hover{background:var(--ink);color:#fff;transform:translateX(3px);}
.rbtn:hover .rsub{color:#aaa;}
.ricon{font-size:19px;}
.rinfo{flex:1;}
.rname{font-weight:700;font-size:13px;}
.rsub{font-size:10px;color:var(--muted);margin-top:1px;}
.rbadge{font-size:9px;padding:2px 7px;border-radius:10px;background:var(--red);color:#fff;white-space:nowrap;}

/* HOME TABS (Rail / Calendar) */
.htabs{display:flex;gap:6px;flex-wrap:wrap;}
.htab-btn{padding:7px 16px;border-radius:18px;border:1.5px solid var(--border);background:#fff;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.htab-btn:hover,.htab-btn.on{background:var(--ink);color:#fff;border-color:var(--ink);}
.sec{max-width:1080px;margin:0 auto;padding:0 18px 44px;}
.sec-title{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--red);padding-left:10px;margin-bottom:16px;}

/* RAIL PASS */
.rail-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:12px;}
.rcard{background:#fff;border-radius:12px;border:1px solid var(--border);padding:14px;transition:box-shadow .2s;}
.rcard:hover{box-shadow:0 5px 18px rgba(0,0,0,.1);}
.rcard-h{display:flex;align-items:center;gap:9px;margin-bottom:9px;}
.rice{font-size:26px;}.rn{font-weight:700;font-size:12px;}.rs{font-size:10px;color:var(--muted);}
.rcov{font-size:11px;color:#555;line-height:1.7;margin-bottom:8px;}
.rprice{font-size:11px;font-weight:700;color:var(--red);margin-bottom:7px;}
.rtags{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:8px;}
.rtag{font-size:9px;padding:2px 7px;border-radius:10px;background:#f0ebe0;}
.rlink{display:inline-flex;align-items:center;gap:3px;font-size:10px;color:var(--blue);text-decoration:none;}
.rlink:hover{text-decoration:underline;}
.tip{background:#fff9f0;border:1px solid #f0d8a0;border-radius:10px;padding:12px;font-size:11px;line-height:1.9;color:#555;}
.tip strong{color:var(--orange);}

/* CALENDAR */
.cal-wrap{overflow-x:auto;border-radius:11px;border:1px solid var(--border);}
table.cal{width:100%;border-collapse:collapse;min-width:680px;background:#fff;}
table.cal thead th{background:var(--ink);color:#fff;font-size:10px;padding:9px 4px;text-align:center;}
table.cal thead th:first-child{text-align:left;padding-left:12px;min-width:155px;}
table.cal tbody tr{border-bottom:1px solid var(--border);}
table.cal tbody tr:last-child{border:none;}
table.cal tbody tr:hover{background:#faf7f2;}
.ccity{padding:11px 12px;font-weight:700;font-size:11px;border-right:1px solid var(--border);}
.ccity span{display:block;font-size:9px;color:var(--muted);font-weight:400;}
td.cc{text-align:center;padding:7px 2px;font-size:13px;position:relative;cursor:default;}
td.cc:hover::after{content:attr(data-tip);position:absolute;bottom:calc(100%+3px);left:50%;transform:translateX(-50%);background:var(--ink);color:#fff;font-size:9px;padding:3px 7px;border-radius:5px;white-space:nowrap;z-index:99;pointer-events:none;}
.cb{background:rgba(39,174,96,.12);}.cs{background:rgba(255,105,150,.15);}.ck{background:rgba(230,126,34,.15);}
.cn{background:rgba(52,152,219,.12);}.ca{background:rgba(192,57,43,.1);}.co{background:rgba(0,0,0,.03);}.cr{background:rgba(52,73,94,.1);}
.leg-row{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:14px;}
.leg{display:flex;align-items:center;gap:4px;font-size:10px;background:#fff;border:1px solid var(--border);border-radius:18px;padding:3px 9px;}

/* ════════════════════ REGION PAGE ════════════════════ */
/* Shows sub-city cards to pick from */
.region-hero{position:relative;overflow:hidden;height:180px;display:flex;align-items:flex-end;background:linear-gradient(135deg,#1a1a2e,#2d2d4e);}
.region-hero-img{position:absolute;inset:0;background-size:cover;background-position:center;opacity:.4;}
.region-hero-content{position:relative;z-index:2;padding:18px 24px;color:#fff;width:100%;}
.region-hero-content h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(24px,4vw,46px);letter-spacing:4px;}
.region-hero-content p{color:#ddd;font-size:11px;margin-top:3px;}
.best-bar{background:var(--ink);color:#fff;padding:8px 22px;font-size:11px;display:flex;align-items:center;gap:5px;flex-wrap:wrap;}
.best-bar strong{color:var(--gold);}

.region-content{max-width:940px;margin:0 auto;padding:22px 18px 50px;}
.sec-label{font-family:'Shippori Mincho',serif;font-size:16px;color:var(--ink);border-left:3px solid var(--red);padding-left:10px;margin-bottom:14px;}

/* Sub-city CARDS grid */
.city-cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:14px;margin-bottom:28px;}
.city-card{background:#fff;border-radius:12px;border:1.5px solid var(--border);overflow:hidden;cursor:pointer;transition:transform .2s,box-shadow .2s,border-color .2s;}
.city-card:hover{transform:translateY(-4px);box-shadow:0 8px 24px rgba(0,0,0,.12);border-color:var(--red);}
.city-card-img{width:100%;height:110px;background:#e8dcc8 center/cover no-repeat;}
.city-card-body{padding:12px;}
.city-card-name{font-weight:700;font-size:14px;margin-bottom:3px;}
.city-card-sub{font-size:10px;color:var(--muted);line-height:1.5;}
.city-card-arrow{display:flex;align-items:center;justify-content:space-between;margin-top:8px;}
.city-card-count{font-size:10px;color:var(--blue);}
.city-card-go{font-size:18px;color:var(--red);}

/* ════════════════════ CITY PAGE ════════════════════ */
.city-hero{position:relative;overflow:hidden;height:160px;display:flex;align-items:flex-end;background:linear-gradient(135deg,#1a1a2e,#2d2d4e);}
.city-hero-img{position:absolute;inset:0;background-size:cover;background-position:center;opacity:.45;}
.city-hero-content{position:relative;z-index:2;padding:16px 22px;color:#fff;width:100%;}
.city-hero-content h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(22px,4vw,42px);letter-spacing:3px;}
.city-hero-content p{color:#ddd;font-size:11px;margin-top:2px;}

.city-content{max-width:940px;margin:0 auto;padding:20px 18px 50px;}

/* Progress */
.prog-wrap{margin-bottom:16px;}
.prog-label{font-size:11px;color:var(--muted);margin-bottom:4px;}
.prog-bar{height:5px;background:var(--border);border-radius:3px;overflow:hidden;}
.prog-fill{height:100%;background:var(--green);border-radius:3px;transition:width .4s;}

/* Inner tabs */
.itabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:16px;}
.itab{padding:7px 14px;border-radius:16px;border:1.5px solid var(--border);background:#fff;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.itab.on{background:var(--red);color:#fff;border-color:var(--red);}
.ipane{display:none;}
.ipane.on{display:block;}

/* Place cards */
.pg{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:13px;}
.pc{background:#fff;border-radius:11px;border:1px solid var(--border);overflow:hidden;transition:transform .2s,box-shadow .2s;}
.pc:hover{transform:translateY(-3px);box-shadow:0 7px 20px rgba(0,0,0,.1);}
.pimg{width:100%;height:125px;background:#e8dcc8 center/cover no-repeat;position:relative;}
.pbadge{position:absolute;top:6px;right:6px;font-size:9px;padding:2px 6px;border-radius:9px;font-weight:700;}
.bm{background:var(--red);color:#fff;}.bl{background:var(--green);color:#fff;}
.bf{background:var(--gold);color:#fff;}.bc{background:var(--purple);color:#fff;}
.pbody{padding:11px;}
.pname{font-weight:700;font-size:13px;margin-bottom:2px;}
.pjp{font-size:10px;color:var(--muted);margin-bottom:5px;font-family:'Shippori Mincho',serif;}
.pdesc{font-size:11px;color:#555;line-height:1.6;margin-bottom:9px;}
.pact{display:flex;gap:6px;align-items:center;flex-wrap:wrap;}
.chk{width:25px;height:25px;border-radius:50%;border:2px solid var(--border);background:#fff;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:12px;transition:all .2s;flex-shrink:0;}
.chk.on{background:var(--green);border-color:var(--green);}
.mapbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;background:var(--blue);color:#fff;border-radius:14px;font-size:10px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;border:none;cursor:pointer;}
.mapbtn:hover{opacity:.8;}
.extbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;background:#555;color:#fff;border-radius:14px;font-size:10px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.extbtn:hover{opacity:.8;}

/* Trail cards */
.tg{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:13px;}
.tc{background:#fff;border-radius:11px;border:1px solid var(--border);padding:13px;display:flex;flex-direction:column;gap:7px;transition:transform .2s,box-shadow .2s;}
.tc:hover{transform:translateY(-3px);box-shadow:0 7px 20px rgba(0,0,0,.1);}
.tc-h{display:flex;align-items:center;gap:8px;}
.tc-icon{font-size:22px;}
.tc-name{font-weight:700;font-size:13px;}
.tc-jp{font-size:10px;color:var(--muted);}
.tc-meta{display:flex;gap:6px;flex-wrap:wrap;}
.ttag{font-size:9px;padding:2px 8px;border-radius:9px;background:#f0ebe0;}
.t-easy{background:#e0ffe0;color:#1a7a1a;}
.t-med{background:#fff3d0;color:#a06010;}
.t-hard{background:#ffe0e0;color:var(--red);}
.tc-desc{font-size:11px;color:#555;line-height:1.6;}
.tc-links{display:flex;gap:6px;flex-wrap:wrap;}

/* Add form */
.add-sec{margin-top:24px;}
.add-sec h3{font-size:13px;font-weight:700;margin-bottom:11px;}
.addform{display:grid;grid-template-columns:1fr 1fr;gap:7px;}
@media(max-width:480px){.addform{grid-template-columns:1fr;}}
.addform input,.addform select,.addform textarea{padding:8px 11px;border:1.5px solid var(--border);border-radius:7px;font-family:'Noto Sans Thai',sans-serif;font-size:12px;background:#fff;color:var(--ink);}
.addform input:focus,.addform select:focus,.addform textarea:focus{outline:none;border-color:var(--red);}
.addform textarea{grid-column:1/-1;resize:vertical;min-height:56px;}
.addbtn{grid-column:1/-1;padding:9px;background:var(--ink);color:#fff;border:none;border-radius:7px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:13px;font-weight:700;transition:background .2s;}
.addbtn:hover{background:var(--red);}
.full{grid-column:1/-1;}
hr.div{border:none;border-top:1px solid var(--border);margin:22px 0;}
.empty{color:var(--muted);font-size:12px;padding:10px 0;}
</style>
</head>
<body>

<!-- ══════════════ PAGE: HOME ══════════════ -->
<div id="pgHome" class="page active">
  <div class="top-nav">
    <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
    <div class="spacer"></div>
    <div class="htabs">
      <button class="htab-btn on" onclick="homeTab('map',this)">🗾 แผนที่</button>
      <button class="htab-btn" onclick="show('pgRail')">🚄 Rail Pass</button>
      <button class="htab-btn" onclick="show('pgTransport')">🚌 Local Transport</button>
      <button class="htab-btn" onclick="show('pgAirport')">✈️ Airport Train</button>
      <button class="htab-btn" onclick="homeTab('cal',this)">📅 ปฏิทิน</button>
    </div>
  </div>

  <div class="hero">
    <h2>JAPAN <span>TRAVEL</span> PLANNER</h2>
    <p>แผนตะลุยญี่ปุ่นทั้งประเทศ • กดภูมิภาคเพื่อเลือกเมือง</p>
  </div>

  <!-- TAB MAP -->
  <div id="ht-map" class="home-wrap">
    <div class="map-box">
      <div class="box-title">🗾 แผนที่ญี่ปุ่น</div>
      <p class="map-hint">👆 กดที่ภูมิภาคบนแผนที่ หรือเลือกจากลิสต์ขวามือ</p>
      <svg id="jmap" viewBox="0 0 400 580" xmlns="http://www.w3.org/2000/svg">
        <g onclick="goRegion('hokkaido')" style="cursor:pointer">
          <path class="mr" id="svg-hokkaido" d="M200,20 L260,15 L300,30 L320,55 L310,80 L280,95 L250,90 L220,80 L195,65 L190,45 Z"/>
          <text class="ml" x="255" y="58">❄️ Hokkaido</text>
        </g>
        <g onclick="goRegion('tohoku')" style="cursor:pointer">
          <path class="mr" id="svg-tohoku" d="M245,105 L275,100 L285,120 L280,155 L265,165 L248,160 L238,140 L240,118 Z"/>
          <text class="ml" x="262" y="135">Tohoku</text>
        </g>
        <g onclick="goRegion('tokyo')" style="cursor:pointer">
          <path class="mr" id="svg-tokyo" d="M240,170 L275,165 L285,185 L282,210 L265,218 L245,212 L235,195 L236,178 Z"/>
          <text class="ml" x="260" y="195">🗼 Tokyo</text>
        </g>
        <g onclick="goRegion('fuji')" style="cursor:pointer">
          <path class="mr" id="svg-fuji" d="M195,200 L235,196 L238,225 L228,250 L205,255 L185,240 L183,218 Z"/>
          <text class="ml" x="210" y="228">🏔️ Fuji</text>
        </g>
        <g onclick="goRegion('takayama')" style="cursor:pointer">
          <path class="mr" id="svg-takayama" d="M148,195 L188,190 L192,215 L182,238 L160,242 L140,228 L138,210 Z"/>
          <text class="ml" x="165" y="218">🏘️ Takayama</text>
        </g>
        <g onclick="goRegion('kyoto')" style="cursor:pointer">
          <path class="mr" id="svg-kyoto" d="M125,250 L175,245 L185,268 L178,295 L155,302 L128,295 L115,275 Z"/>
          <text class="ml" x="150" y="275">⛩️ Kyoto</text>
        </g>
        <g onclick="goRegion('hiroshima')" style="cursor:pointer">
          <path class="mr" id="svg-hiroshima" d="M88,295 L128,292 L135,318 L122,342 L98,348 L78,332 L75,312 Z"/>
          <text class="ml" x="105" y="320">🕊️ Hiroshima</text>
        </g>
        <g style="opacity:.5">
          <path class="mr" d="M118,348 L158,342 L162,362 L148,378 L122,380 L108,366 Z" fill="#ddd"/>
          <text class="ml" x="135" y="362" fill="#aaa">Shikoku</text>
        </g>
        <g onclick="goRegion('fukuoka')" style="cursor:pointer">
          <path class="mr" id="svg-fukuoka" d="M62,335 L95,330 L100,360 L88,392 L62,405 L40,388 L38,362 Z"/>
          <text class="ml" x="68" y="368">🍜 Fukuoka</text>
        </g>
        <g style="opacity:.4">
          <ellipse cx="80" cy="540" rx="20" ry="11" fill="#e8dcc8" stroke="#c5b99a" stroke-width="1"/>
          <text class="ml" x="80" y="543" fill="#aaa" font-size="7.5">Okinawa</text>
        </g>
        <text x="338" y="200" font-size="7.5" fill="#bbb" font-family="sans-serif" transform="rotate(90,338,200)">Pacific Ocean</text>
        <text x="50" y="210" font-size="7.5" fill="#bbb" font-family="sans-serif" transform="rotate(-18,50,210)">Sea of Japan</text>
      </svg>
    </div>

    <div class="region-list">
      <div class="box-title">เลือกภูมิภาค</div>
      <div class="rbtn" onclick="goRegion('hokkaido')"><span class="ricon">❄️</span><div class="rinfo"><div class="rname">Hokkaido</div><div class="rsub">Sapporo · Otaru · Furano</div></div><span class="rbadge">ก.พ./พ.ค.</span></div>
      <div class="rbtn" onclick="goRegion('tokyo')"><span class="ricon">🗼</span><div class="rinfo"><div class="rname">Tokyo & Kanto</div><div class="rsub">Tokyo · Nikko · Kamakura</div></div><span class="rbadge">มี.ค.–เม.ย.</span></div>
      <div class="rbtn" onclick="goRegion('fuji')"><span class="ricon">🏔️</span><div class="rinfo"><div class="rname">Fuji & Hakone</div><div class="rsub">Kawaguchiko · Hakone</div></div><span class="rbadge">พ.ค./ต.ค.</span></div>
      <div class="rbtn" onclick="goRegion('takayama')"><span class="ricon">🏘️</span><div class="rinfo"><div class="rname">Takayama & Kanazawa</div><div class="rsub">Takayama · Shirakawago · Kanazawa</div></div><span class="rbadge">ก.พ./เม.ย.</span></div>
      <div class="rbtn" onclick="goRegion('kyoto')"><span class="ricon">⛩️</span><div class="rinfo"><div class="rname">Kyoto & Osaka</div><div class="rsub">Kyoto · Osaka · Nara · Kobe</div></div><span class="rbadge">พ.ย.ดีสุด</span></div>
      <div class="rbtn" onclick="goRegion('hiroshima')"><span class="ricon">🕊️</span><div class="rinfo"><div class="rname">Hiroshima</div><div class="rsub">Hiroshima · Miyajima · Okayama</div></div><span class="rbadge">มี.ค./พ.ย.</span></div>
      <div class="rbtn" onclick="goRegion('fukuoka')"><span class="ricon">🍜</span><div class="rinfo"><div class="rname">Fukuoka & Kyushu</div><div class="rsub">Fukuoka · Nagasaki · Kumamoto</div></div><span class="rbadge">มี.ค./ต.ค.</span></div>
    </div>
  </div>

  <!-- TAB RAIL — just a redirect card -->
  <div id="ht-rail" style="display:none" class="sec">
    <div style="height:24px"></div>
  </div>

  <!-- TAB CALENDAR -->
  <div id="ht-cal" style="display:none" class="sec" style="padding-top:24px">
    <div style="height:24px"></div>
    <h2 class="sec-title">📅 ปฏิทินช่วงเวลาแนะนำ</h2>
    <div class="leg-row">
      <div class="leg">🌸 ซากุระ</div><div class="leg">🍂 ใบไม้แดง</div><div class="leg">❄️ หิมะ</div>
      <div class="leg">✅ ช่วงดี</div><div class="leg">💸 แพง/แน่น</div><div class="leg">⚠️ Golden Week</div>
      <div class="leg">🌧️ ฝน</div><div class="leg">🥵 ร้อน</div><div class="leg">🌀 ไต้ฝุ่น</div>
    </div>
    <div class="cal-wrap">
    <table class="cal"><thead><tr><th>เมือง</th><th>ม.ค.</th><th>ก.พ.</th><th>มี.ค.</th><th>เม.ย.</th><th>พ.ค.</th><th>มิ.ย.</th><th>ก.ค.</th><th>ส.ค.</th><th>ก.ย.</th><th>ต.ค.</th><th>พ.ย.</th><th>ธ.ค.</th></tr></thead>
    <tbody>
      <tr><td class="ccity">🗼 Tokyo<span>+Yokohama</span></td><td class="cc co" data-tip="หนาว คนน้อย ถูก">🟡</td><td class="cc co" data-tip="หนาว แต่ถูก">🟡</td><td class="cc cs" data-tip="ซากุระเริ่มบาน">🌸</td><td class="cc cs ca" data-tip="ซากุระบาน แต่แพงมาก">🌸💸</td><td class="cc ca" data-tip="Golden Week แพงสุด">⚠️</td><td class="cc cr" data-tip="ฤดูฝน">🌧️</td><td class="cc ca" data-tip="ร้อนชื้นมาก">🥵</td><td class="cc ca" data-tip="ร้อนชื้น">🥵</td><td class="cc ca" data-tip="เสี่ยงไต้ฝุ่น">🌀</td><td class="cc cb" data-tip="อากาศดีมาก">✅</td><td class="cc ck" data-tip="ใบไม้แดง ดีที่สุด">✅🍂</td><td class="cc co" data-tip="เริ่มหนาว illumination สวย">🟡</td></tr>
      <tr><td class="ccity">🏔️ Fuji+Hakone<span>+Shizuoka</span></td><td class="cc co" data-tip="วิวชัด หนาวมาก">🟡</td><td class="cc co" data-tip="หนาว ออนเซ็นดี">🟡</td><td class="cc cs" data-tip="ซากุระ+ฟูจิ สวย">🌸</td><td class="cc cs" data-tip="ซากุระบาน">🌸</td><td class="cc cb" data-tip="อากาศดีหลัง GW">✅</td><td class="cc cr" data-tip="ฤดูฝน">🌧️</td><td class="cc ca" data-tip="ร้อน ปีนฟูจิได้">🥵</td><td class="cc ca" data-tip="ร้อน คนเยอะ">🥵</td><td class="cc ca" data-tip="ไต้ฝุ่น ระวัง">🌀</td><td class="cc cb" data-tip="วิวฟูจิชัดสุด ⭐">✅⭐</td><td class="cc cb" data-tip="ใบไม้แดง+ฟูจิ">✅</td><td class="cc co" data-tip="หนาว ออนเซ็น">🟡</td></tr>
      <tr><td class="ccity">🏘️ Takayama<span>+Kanazawa</span></td><td class="cc cn" data-tip="หิมะสวย">❄️✅</td><td class="cc cn" data-tip="หิมะหนาสุด ⭐">❄️⭐</td><td class="cc cs" data-tip="ซากุระ+หิมะ">🌸</td><td class="cc cs cb" data-tip="ซากุระช้า คนน้อย">🌸✅</td><td class="cc cb" data-tip="อากาศดี เขียวสด">✅</td><td class="cc cr" data-tip="ฝนตก">🌧️</td><td class="cc ca" data-tip="ร้อน ชื้น">🥵</td><td class="cc ca" data-tip="ร้อนมาก">🥵</td><td class="cc ca" data-tip="ระวังไต้ฝุ่น">🌀</td><td class="cc cb" data-tip="ใบไม้แดงสวย">✅</td><td class="cc ck" data-tip="ใบไม้แดง ดีที่สุด">✅🍂</td><td class="cc cn" data-tip="เริ่มมีหิมะ">❄️</td></tr>
      <tr><td class="ccity">⛩️ Kyoto+Osaka<span>+Nara+Kobe</span></td><td class="cc co" data-tip="คนน้อย ถูก หนาว">🟡</td><td class="cc co" data-tip="เงียบสงบ">🟡</td><td class="cc cs" data-tip="ซากุระบาน สวยมาก">🌸</td><td class="cc cs ca" data-tip="ซากุระ แต่แพงสุด">🌸💸</td><td class="cc ca" data-tip="Golden Week แน่นมาก">⚠️</td><td class="cc cr" data-tip="ฝนตกบ่อย">🌧️</td><td class="cc ca" data-tip="ร้อนชื้น">🥵</td><td class="cc ca" data-tip="ร้อนมาก">🥵</td><td class="cc ca" data-tip="ไต้ฝุ่น">🌀</td><td class="cc cb" data-tip="อากาศดี เปลี่ยนสี">✅</td><td class="cc ck" data-tip="ใบไม้แดง สวยสุด ⭐">✅🍂⭐</td><td class="cc co" data-tip="เงียบลง illumination สวย">🟡</td></tr>
      <tr><td class="ccity">🕊️ Hiroshima<span>+Miyajima</span></td><td class="cc co" data-tip="หนาวน้อย">🟡</td><td class="cc co" data-tip="อากาศดีพอประมาณ">🟡</td><td class="cc cs cb" data-tip="ซากุระบานเร็ว คนน้อย ⭐">🌸✅</td><td class="cc cs" data-tip="ซากุระบาน">🌸</td><td class="cc cb" data-tip="อากาศดี ไม่แออัด">✅</td><td class="cc cr" data-tip="ฝนตก">🌧️</td><td class="cc ca" data-tip="ร้อนชื้น">🥵</td><td class="cc ca" data-tip="ร้อนมาก">🥵</td><td class="cc ca" data-tip="ไต้ฝุ่น">🌀</td><td class="cc cb" data-tip="อากาศดีที่สุด">✅</td><td class="cc cb" data-tip="ใบไม้แดง เย็นสบาย">✅</td><td class="cc co" data-tip="เงียบสงบ">🟡</td></tr>
      <tr><td class="ccity">🍜 Fukuoka<span>+Kyushu</span></td><td class="cc co" data-tip="อากาศดีกว่าภาคกลาง">🟡</td><td class="cc co" data-tip="เริ่มอุ่น สบาย">🟡</td><td class="cc cs cb" data-tip="ซากุระบานก่อนที่อื่น ⭐">🌸⭐</td><td class="cc cs" data-tip="ซากุระบาน">🌸</td><td class="cc cb" data-tip="อากาศดีมาก">✅</td><td class="cc cr" data-tip="ฝนเยอะ">🌧️</td><td class="cc ca" data-tip="ร้อนชื้น เทศกาลสนุก">🥵</td><td class="cc ca" data-tip="ร้อน ไต้ฝุ่น">🥵🌀</td><td class="cc ca" data-tip="ไต้ฝุ่นบ่อยสุด">🌀</td><td class="cc cb" data-tip="ช่วงดีที่สุด">✅</td><td class="cc cb" data-tip="ใบไม้แดง อากาศดี">✅</td><td class="cc co" data-tip="ไม่หนาวมาก">🟡</td></tr>
      <tr><td class="ccity">❄️ Hokkaido<span>+Sapporo</span></td><td class="cc cn" data-tip="หิมะหนา สกี ออนเซ็น">❄️</td><td class="cc cn" data-tip="Snow Festival ⭐">❄️⭐</td><td class="cc co" data-tip="หิมะเริ่มละลาย">🟡</td><td class="cc cs cb" data-tip="ซากุระช้า คนน้อย ถูก">🌸✅</td><td class="cc cs cb" data-tip="ซากุระยังบาน ถูกสุด">🌸✅</td><td class="cc cb" data-tip="อากาศดีที่สุดในญี่ปุ่น">✅</td><td class="cc cb" data-tip="ลาเวนเดอร์ Furano ⭐">✅🌿</td><td class="cc cb" data-tip="เย็นสบาย หนีร้อน">✅</td><td class="cc cb" data-tip="ใบไม้เริ่มเปลี่ยน">✅</td><td class="cc ck" data-tip="ใบไม้แดงก่อนที่อื่น">🍂</td><td class="cc co" data-tip="เริ่มหนาว">🟡</td><td class="cc cn" data-tip="หิมะตก">❄️</td></tr>
    </tbody></table>
    </div>
    <p style="font-size:10px;color:var(--muted);margin-top:9px;text-align:center">⚠️ หลีกเลี่ยง: Golden Week (ปลายเม.ย.–ต้นพ.ค.) • Obon (กลางส.ค.) • New Year (ปลายธ.ค.–ต้นม.ค.)</p>
  </div>
</div>

<!-- ══════════════ PAGE: REGION (shows city cards) ══════════════ -->
<div id="pgRegion" class="page">
  <div class="top-nav">
    <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
    <div class="spacer"></div>
    <div class="breadcrumb">
      <span onclick="goHome()">🏠 หน้าแรก</span>
      <span style="color:#666;cursor:default">›</span>
      <span id="bc-region" style="color:#fff;cursor:default"></span>
    </div>
  </div>
  <div class="region-hero">
    <div class="region-hero-img" id="rHeroImg"></div>
    <div class="region-hero-content">
      <h1 id="rHeroTitle"></h1>
      <p id="rHeroSub"></p>
    </div>
  </div>
  <div class="best-bar" id="rBestBar"></div>
  <div class="region-content">
    <div class="sec-label" style="margin-bottom:16px">📍 เลือกเมืองที่อยากไป</div>
    <div class="city-cards" id="cityCardsGrid"></div>
  </div>
</div>

<!-- ══════════════ PAGE: CITY ══════════════ -->
<div id="pgCity" class="page">
  <div class="top-nav">
    <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
    <div class="spacer"></div>
    <div class="breadcrumb">
      <span onclick="goHome()">🏠 หน้าแรก</span>
      <span style="color:#666;cursor:default">›</span>
      <span id="bc-region2" onclick="backToRegion()" style="cursor:pointer"></span>
      <span style="color:#666;cursor:default">›</span>
      <span id="bc-city" style="color:#fff;cursor:default"></span>
    </div>
  </div>
  <div class="city-hero">
    <div class="city-hero-img" id="cHeroImg"></div>
    <div class="city-hero-content">
      <h1 id="cHeroTitle"></h1>
      <p id="cHeroSub"></p>
    </div>
  </div>

  <div class="city-content">
    <div class="prog-wrap">
      <div class="prog-label" id="progLabel">เช็คแล้ว 0 / 0 สถานที่</div>
      <div class="prog-bar"><div class="prog-fill" id="progFill" style="width:0%"></div></div>
    </div>

    <div class="itabs">
      <button class="itab on"  onclick="switchITab('att',this)">🏛️ ที่เที่ยว</button>
      <button class="itab"     onclick="switchITab('food',this)">🍜 ร้านอาหาร</button>
      <button class="itab"     onclick="switchITab('cafe',this)">☕ คาเฟ่</button>
      <button class="itab"     onclick="switchITab('trail',this)">🏃 Trail / วิ่ง</button>
    </div>

    <div id="ip-att"   class="ipane on"></div>
    <div id="ip-food"  class="ipane"></div>
    <div id="ip-cafe"  class="ipane"></div>
    <div id="ip-trail" class="ipane"></div>

    <hr class="div">
    <div class="add-sec">
      <h3>➕ เพิ่มสถานที่ของคุณเอง</h3>
      <div class="addform">
        <input type="text"  id="a-name" placeholder="ชื่อสถานที่ / ร้าน">
        <input type="text"  id="a-jp"   placeholder="ชื่อภาษาญี่ปุ่น (ถ้ามี)">
        <textarea           id="a-desc" placeholder="รายละเอียด / หมายเหตุ"></textarea>
        <input type="text"  id="a-map"  placeholder="Google Maps URL" class="full">
        <select id="a-tab">
          <option value="att">🏛️ ที่เที่ยว</option>
          <option value="food">🍜 ร้านอาหาร</option>
          <option value="cafe">☕ คาเฟ่</option>
        </select>
        <select id="a-badge">
          <option value="must">Must-go</option>
          <option value="local">Local Gem</option>
          <option value="food">ร้านอาหาร</option>
          <option value="cafe">คาเฟ่</option>
        </select>
        <button class="addbtn" onclick="addPlace()">เพิ่มสถานที่</button>
      </div>
    </div>
  </div>
</div>

<!-- ══════════════════════════════════════════════════════
     DATA + LOGIC
══════════════════════════════════════════════════════ -->
<script>
// ── DATA ──────────────────────────────────────────────
const REGIONS = {
  hokkaido:{
    name:'Hokkaido',sub:'ฮอกไกโด',
    bestTime:'❄️⭐ Snow Festival: กุมภาพันธ์  |  🌸✅ ซากุระช้า+ถูก: ปลายเมษายน–พฤษภาคม  |  🌿 ลาเวนเดอร์: กรกฎาคม',
    bg:'https://images.unsplash.com/photo-1542640244-7e672d6cef4e?w=1200&q=80',
    cities:{
      Sapporo:{
        sub:'เมืองหลักฮอกไกโด · Snow Festival · ซีฟู้ดสด',
        img:'https://images.unsplash.com/photo-1542640244-7e672d6cef4e?w=600&q=80',
        att:[
          {n:'Odori Park + Snow Festival',jp:'大通公園',d:'สวนกลางเมืองยาว 1.5 กม. จัดเทศกาลหิมะทุกกุมภาพันธ์ รูปปั้นหิมะขนาดยักษ์ ฟรีเข้าชม',b:'must',m:'https://maps.google.com/?q=Odori+Park+Sapporo',img:'https://images.unsplash.com/photo-1542640244-7e672d6cef4e?w=400&q=75'},
          {n:'Sapporo Clock Tower',jp:'時計台',d:'สัญลักษณ์เมืองซัปโปโร สร้างปี 1878 สไตล์อาณานิคมอเมริกัน ด้านในเป็นพิพิธภัณฑ์',b:'must',m:'https://maps.google.com/?q=Sapporo+Clock+Tower'},
          {n:'Hokkaido University Campus',jp:'北海道大学',d:'ถนน Ginkgo ใบไม้แดงสวยมาก ถนน Poplar ยาวสวย เข้าฟรี เดินเล่นได้ตลอด',b:'local',m:'https://maps.google.com/?q=Hokkaido+University'},
          {n:'Shiroi Koibito Park',jp:'白い恋人パーク',d:'โรงงาน+พิพิธภัณฑ์คุ้กกี้ดัง Shiroi Koibito คาเฟ่สวยในโรงงานเก่า ซื้อของฝากได้เลย',b:'must',m:'https://maps.google.com/?q=Shiroi+Koibito+Park+Sapporo'},
          {n:'Nakajima Park',jp:'中島公園',d:'สวนสวยใจกลางเมือง สเก็ตน้ำแข็งช่วงหนาว ซากุระช่วงฤดูใบไม้ผลิ',b:'local',m:'https://maps.google.com/?q=Nakajima+Park+Sapporo'},
        ],
        food:[
          {n:'Nijo Market',jp:'二条市場',d:'ตลาดซีฟู้ดสด 100 ปี ปูขน Kegani สด ปลาแซลมอน ทานสดได้ที่ร้านในตลาด เปิดแต่เช้า',b:'must',m:'https://maps.google.com/?q=Nijo+Market+Sapporo'},
          {n:'Sapporo Ramen Yokocho',jp:'ラーメン横丁',d:'ซอยราเมน 17 ร้าน ราเมนมิโซะซัปโปโรต้นตำรับ ซุปเข้มข้น เนย ข้าวโพด อร่อยมากตอนอากาศหนาว',b:'must',m:'https://maps.google.com/?q=Sapporo+Ramen+Yokocho'},
          {n:'Soup Curry',jp:'スープカレー',d:'อาหารพิเศษซัปโปโร แกงซุปเหลวข้นใส่ผักใหญ่และไก่ทอด ร้านแนะนำ: Garaku ย่าน Susukino',b:'local',m:'https://maps.google.com/?q=Garaku+Soup+Curry+Sapporo'},
          {n:'Sapporo Beer Garden',jp:'サッポロビール園',d:'โรงงานเบียร์ 100 ปี บุฟเฟ่ต์เนื้อย่าง Genghis Khan (เนื้อแกะ) กับเบียร์สดในโรงงานเก่า',b:'local',m:'https://maps.google.com/?q=Sapporo+Beer+Garden'},
        ],
        cafe:[
          {n:'Morihico Coffee',jp:'森彦コーヒー',d:'คาเฟ่ในบ้านไม้ยุคโชวะ ย่าน Maruyama อบอุ่น เงียบ กาแฟดีที่สุดใน Sapporo',b:'cafe',m:'https://maps.google.com/?q=Morihico+Coffee+Sapporo'},
        ],
        trails:[
          {n:'Moiwa Mountain Trail',jp:'藻岩山',dist:'5 km',lv:'easy',d:'ขึ้นเขา Moiwa ผ่านป่าดึกดำบรรพ์ จุดชมวิวซัปโปโรและ Ishikari Bay สวยงาม มีกระเช้าถ้าไม่เดิน',m:'https://maps.google.com/?q=Mt+Moiwa+Sapporo',at:'https://www.alltrails.com/trail/japan/hokkaido/mt-moiwa'},
          {n:'Toyohira River Path',jp:'豊平川',dist:'25 km (เลือกได้)',lv:'easy',d:'เส้นลาดยางริมแม่น้ำ Toyohira ยาวกว่า 25 กม. วิ่งผ่าน Nakajima Park เส้นยอดนิยมของนักวิ่ง Sapporo',m:'https://maps.google.com/?q=Toyohira+River+Sapporo',at:'https://greatruns.com/sapporo-japan/'},
        ]
      },
      Otaru:{
        sub:'คลองอิฐแดง · ซูชิสด · ดนตรีกล่อง',
        img:'https://images.unsplash.com/photo-1508780709619-79562169bc64?w=600&q=80',
        att:[
          {n:'Otaru Canal',jp:'小樽運河',d:'คลองอิฐแดงยุคเมจิ ไฟแก๊สริมคลองสวยตอนกลางคืน ช่วง Snow Light Path (ก.พ.) สวยที่สุด',b:'must',m:'https://maps.google.com/?q=Otaru+Canal'},
          {n:'Sakaimachi Street',jp:'堺町通り',d:'ถนนช้อปปิ้งในอาคารอิฐแดงเก่า ร้านขนมหวาน เครื่องแก้ว อาหารทะเล บรรยากาศโรแมนติก',b:'must',m:'https://maps.google.com/?q=Sakaimachi+Street+Otaru'},
          {n:'Music Box Museum',jp:'オルゴール堂',d:'พิพิธภัณฑ์กล่องดนตรีในอาคารเมจิ มีกล่องดนตรีหลายพันแบบ ฟังเสียงดนตรีแปลกตา',b:'local',m:'https://maps.google.com/?q=Otaru+Music+Box+Museum'},
        ],
        food:[
          {n:'Otaru Sushi',jp:'小樽寿司',d:'ซูชิโอตารูขึ้นชื่อทั่วญี่ปุ่น ปลาสดจากทะเลฮอกไกโด ร้านแนะนำ: Masazushi',b:'must',m:'https://maps.google.com/?q=Masazushi+Otaru'},
        ],
        cafe:[],
        trails:[
          {n:'Otaru Seaside Path',jp:'小樽海岸',dist:'8 km',lv:'easy',d:'เส้นทางริมชายฝั่งจากท่าเรือโอตารุ วิวทะเลฮอกไกโด เดินหรือวิ่งสบาย',m:'https://maps.google.com/?q=Otaru+Seaside',at:'https://www.alltrails.com/japan/hokkaido'},
        ]
      },
      Furano:{
        sub:'ทุ่งลาเวนเดอร์ · ฟาร์ม · ธรรมชาติ',
        img:'https://images.unsplash.com/photo-1499002238440-d264edd596ec?w=600&q=80',
        att:[
          {n:'Farm Tomita',jp:'ファーム富田',d:'ฟาร์มลาเวนเดอร์โด่งดังที่สุดในญี่ปุ่น ทุ่งสีม่วงสุดตา บานกรกฎาคม ไอศกรีมลาเวนเดอร์อร่อย',b:'must',m:'https://maps.google.com/?q=Farm+Tomita+Furano',img:'https://images.unsplash.com/photo-1499002238440-d264edd596ec?w=400&q=75'},
          {n:'Furano Wine House',jp:'富良野ワイン',d:'โรงไวน์บนเนินเขา วิวเมือง Furano สวยงาม ชิมไวน์ฮอกไกโดและอาหารท้องถิ่น',b:'local',m:'https://maps.google.com/?q=Furano+Wine+House'},
        ],
        food:[
          {n:'Furano Cheese Factory',jp:'富良野チーズ工場',d:'โรงงานชีสท้องถิ่น ชิมชีสและเนยสดจากนมฮอกไกโด ทำ pizza ด้วยเนยสด ราคาถูก คุณภาพดี',b:'local',m:'https://maps.google.com/?q=Furano+Cheese+Factory'},
        ],
        cafe:[],
        trails:[
          {n:'Daisetsuzan Trail Run',jp:'大雪山',dist:'15–50 km',lv:'hard',d:'วิ่งเทรลในอุทยาน Daisetsuzan หลายระดับ วิวทุ่งหญ้าและภูเขาฮอกไกโด มีแข่งขัน Furano Trail Run เดือนกรกฎาคม',m:'https://maps.google.com/?q=Daisetsuzan+National+Park',at:'https://www.alltrails.com/trail/japan/hokkaido/daisetsuzan'},
        ]
      },
    }
  },
  tokyo:{
    name:'Tokyo & Kanto',sub:'โตเกียว + คันโต',
    bestTime:'🌸 ซากุระ: ปลายมีนาคม–ต้นเมษายน (แพง/แน่น)  |  🍂 ใบไม้แดง: ตุลาคม–พฤศจิกายน  |  🟡 งบประหยัด: มกราคม–กุมภาพันธ์',
    bg:'https://images.unsplash.com/photo-1540959733332-eab4deabeeaf?w=1200&q=80',
    cities:{
      Tokyo:{
        sub:'เมืองหลวง · คาเฟ่ · ช้อปปิ้ง · วัด',
        img:'https://images.unsplash.com/photo-1540959733332-eab4deabeeaf?w=600&q=80',
        att:[
          {n:'Senso-ji Temple',jp:'浅草寺',d:'วัดอายุ 1,300 ปี ย่านอาซากุสะ ถนน Nakamise ยาว ไปเช้าก่อนคนเยอะ ฟรี',b:'must',m:'https://maps.google.com/?q=Senso-ji+Temple+Tokyo'},
          {n:'Shinjuku Gyoen',jp:'新宿御苑',d:'สวนแห่งชาติ จุดดูซากุระที่ดีที่สุดในโตเกียว ซากุระหลายพันธุ์บานต่อเนื่อง ค่าเข้า ¥500',b:'must',m:'https://maps.google.com/?q=Shinjuku+Gyoen+Tokyo'},
          {n:'Shibuya Crossing',jp:'渋谷スクランブル',d:'แยกคนข้ามมากที่สุดในโลก ดูจาก Starbucks ชั้น 2 สนุกทั้งกลางวันและกลางคืน',b:'must',m:'https://maps.google.com/?q=Shibuya+Crossing+Tokyo'},
          {n:'Yanaka Old Town',jp:'谷中',d:'ย่านโบราณรอดจากสงคราม บรรยากาศ Showa ซอยเล็กน่าเดิน ร้านโลคอล แมวอิสระเต็มสุสาน',b:'local',m:'https://maps.google.com/?q=Yanaka+Tokyo'},
          {n:'Shimokitazawa',jp:'下北沢',d:'ย่านวินเทจ ดนตรีสด คาเฟ่เล็กๆ ร้านเสื้อผ้ามือสอง บรรยากาศฮิปสเตอร์ญี่ปุ่น',b:'local',m:'https://maps.google.com/?q=Shimokitazawa+Tokyo'},
          {n:'Tokyo Skytree',jp:'東京スカイツリー',d:'หอชมวิว 634 เมตร สูงที่สุดในโลก วิว 360° ยามค่ำสวยมาก จองล่วงหน้าแนะนำ',b:'must',m:'https://maps.google.com/?q=Tokyo+Skytree'},
          {n:'Meiji Shrine + Yoyogi',jp:'明治神宮',d:'ศาลเจ้าสำคัญในป่า เดินเล่น Yoyogi Park กว้างใหญ่ ตลาดนัด Cosplay วันอาทิตย์',b:'must',m:'https://maps.google.com/?q=Meiji+Shrine+Tokyo'},
        ],
        food:[
          {n:'Ichiran Ramen',jp:'一蘭',d:'ราเมน Hakata นั่งบูธคนเดียว เหมาะมากสำหรับ Solo Traveler สาขาใน Shinjuku และ Shibuya',b:'must',m:'https://maps.google.com/?q=Ichiran+Ramen+Shinjuku'},
          {n:'Tsukiji Outer Market',jp:'築地場外市場',d:'ตลาดอาหารทะเลสด ซูชิเช้า ไข่หวาน ปลาย่าง ราคาดี เปิด 5:00–13:00',b:'local',m:'https://maps.google.com/?q=Tsukiji+Outer+Market+Tokyo'},
          {n:'Gyukatsu Motomura',jp:'牛かつもと村',d:'เนื้อวัวทอดปานกลาง ย่างเองบนกระทะหินร้อน อร่อยมาก คิวยาวแต่คุ้มค่า',b:'local',m:'https://maps.google.com/?q=Gyukatsu+Motomura+Shibuya'},
          {n:'Depachika (ชั้น B ห้าง)',jp:'デパ地下',d:'ชั้น B1-B2 ห้างสรรพสินค้า (Isetan, Mitsukoshi) เต็มไปด้วยอาหารและขนมพรีเมียม',b:'local',m:'https://maps.google.com/?q=Isetan+Shinjuku'},
        ],
        cafe:[
          {n:'Fuglen Tokyo',jp:'フグレン東京',d:'คาเฟ่นอร์เวย์ในบ้านญี่ปุ่นเก่า ย่าน Tomigaya กาแฟดีมาก บรรยากาศเงียบสงบ',b:'cafe',m:'https://maps.google.com/?q=Fuglen+Tokyo'},
          {n:'Blue Bottle Coffee Shibuya',jp:'ブルーボトル',d:'Specialty coffee จากแคลิฟอร์เนีย ออกแบบสวย ถ่ายรูปดี ย่าน Shibuya',b:'cafe',m:'https://maps.google.com/?q=Blue+Bottle+Coffee+Shibuya'},
        ],
        trails:[
          {n:'Imperial Palace Loop',jp:'皇居ラン',dist:'5 km',lv:'easy',d:'เส้นวิ่งที่โด่งดังที่สุดในโตเกียว รอบพระราชวัง ลาดยาง เรียบ นักวิ่งหลายร้อยคนใช้ทุกวัน',m:'https://maps.google.com/?q=Imperial+Palace+Tokyo',at:'https://www.alltrails.com/trail/japan/tokyo/imperial-palace-outer-garden'},
          {n:'Yoyogi Park Loop',jp:'代々木公園',dist:'2.5 km',lv:'easy',d:'วนในสวน Yoyogi บรรยากาศสบาย ไม่มีรถ เข้าฟรี ใกล้รถไฟ Harajuku',m:'https://maps.google.com/?q=Yoyogi+Park+Tokyo',at:'https://www.alltrails.com/trail/japan/tokyo/yoyogi-park-loop'},
          {n:'Mt. Takao Trail',jp:'高尾山',dist:'14 km',lv:'medium',d:'เทรลดังที่สุดใกล้โตเกียว ออก Mt. Jinba ลง Takaosanguchi วิวดี ใช้รถไฟจาก Shinjuku 50 นาที',m:'https://maps.google.com/?q=Mt+Takao+Tokyo',at:'https://www.alltrails.com/trail/japan/tokyo/mount-takao-trail-1'},
        ]
      },
      Nikko:{
        sub:'ศาลเจ้าทอง · น้ำตก · ธรรมชาติ',
        img:'https://images.unsplash.com/photo-1528360983277-13d401cdc186?w=600&q=80',
        att:[
          {n:'Tosho-gu Shrine',jp:'東照宮',d:'ศาลเจ้าตกแต่งหรูหราสุดในญี่ปุ่น ทองคำ+แกะสลัก รายละเอียดวิจิตร UNESCO Heritage นั่งรถไฟ 2 ชม.',b:'must',m:'https://maps.google.com/?q=Nikko+Toshogu'},
          {n:'Kegon Falls',jp:'華厳ノ滚',d:'น้ำตกสูง 97 เมตร 1 ใน 3 น้ำตกสวยที่สุดในญี่ปุ่น มีลิฟต์ลงดูด้านล่าง สวยมากช่วงใบไม้แดง',b:'must',m:'https://maps.google.com/?q=Kegon+Falls+Nikko'},
          {n:'Lake Chuzenji',jp:'中禅寺湖',d:'ทะเลสาบบนเขา 1,269 เมตร วิวสวยมาก โดยเฉพาะใบไม้แดง เดินรอบหรือนั่งเรือ',b:'must',m:'https://maps.google.com/?q=Lake+Chuzenji+Nikko'},
        ],
        food:[{n:'Yuba (ผิวเต้าหู้สด)',jp:'湯波',d:'อาหารพิเศษนิกโก้ คือผิวเต้าหู้สดจากนมถั่วเหลือง ทานเป็น Sashimi หาได้เฉพาะที่นี่',b:'local',m:'https://maps.google.com/?q=yuba+Nikko'}],
        cafe:[],
        trails:[{n:'Senjogahara Marshland',jp:'戦場ヶ原',dist:'8 km',lv:'easy',d:'เส้นทางในทุ่งหญ้าชุ่มน้ำ Senjogahara วิวเขา Nantai เส้นไม้ระแนงสบาย เหมาะทุกระดับ',m:'https://maps.google.com/?q=Senjogahara+Nikko',at:'https://www.alltrails.com/trail/japan/tochigi/senjogahara'}]
      },
      Kamakura:{
        sub:'พระพุทธใหญ่ · ทะเล · เดินเทรล',
        img:'https://images.unsplash.com/photo-1535139262971-ab8eb5e17e4c?w=600&q=80',
        att:[
          {n:'Great Buddha (Kotoku-in)',jp:'高徳院 大仏',d:'พระพุทธรูปกลางแจ้งสูง 13.35 เมตร อายุ 700 ปี เข้าไปในองค์ได้ ค่าเข้า ¥300 รถไฟจากโตเกียว 1 ชม.',b:'must',m:'https://maps.google.com/?q=Kotoku-in+Great+Buddha+Kamakura'},
          {n:'Tsurugaoka Hachimangu',jp:'鶴岡八幡宮',d:'ศาลเจ้าหลักคามาคูระ ถนนต้นซากุระยาว 1.8 กม. เดินจากสถานีรถไฟ',b:'must',m:'https://maps.google.com/?q=Tsurugaoka+Hachimangu+Kamakura'},
          {n:'Enoshima Island',jp:'江の島',d:'เกาะเล็กเชื่อมสะพาน มีถ้ำ ศาลเจ้า วิวทะเลและ Mt. Fuji',b:'local',m:'https://maps.google.com/?q=Enoshima+Island'},
        ],
        food:[{n:'Shirasu Don',jp:'しらす丼',d:'ข้าวหน้าปลาขาวจิ๋วสด อาหารพิเศษคามาคูระ ทานริมทะเล สดมาก ร้านเยอะย่าน Yuigahama',b:'must',m:'https://maps.google.com/?q=shirasu+don+Kamakura'}],
        cafe:[],
        trails:[{n:'Kamakura Hiking Trail',jp:'鎌倉アルプス',dist:'10 km',lv:'medium',d:'เส้นทางผ่านเนินเขาคามาคูระ วัดเก่าแก่กลางป่า Zuisen-ji ถึง Kencho-ji เงียบสงบ',m:'https://maps.google.com/?q=Kamakura+hiking+trail',at:'https://www.alltrails.com/trail/japan/kanagawa/kamakura-hiking-trail'}]
      },
    }
  },
  kyoto:{
    name:'Kyoto & Osaka',sub:'เกียวโต + โอซาก้า',
    bestTime:'🍂⭐ ใบไม้แดง: พฤศจิกายน (ดีที่สุด!)  |  🌸 ซากุระ: ปลายมีนาคม–เมษายน  |  ⚠️ หลีกเลี่ยง Golden Week',
    bg:'https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?w=1200&q=80',
    cities:{
      Kyoto:{
        sub:'วัด · เกชา · ตลาดโลคอล',
        img:'https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?w=600&q=80',
        att:[
          {n:'Fushimi Inari Taisha',jp:'伏見稲荷大社',d:'ประตู Torii สีแดงนับพันบนเขา Inari ไปเช้ามากหรือเย็นมากเพื่อหลีกคน ฟรี ใกล้ JR Inari',b:'must',m:'https://maps.google.com/?q=Fushimi+Inari+Taisha+Kyoto'},
          {n:'Arashiyama Bamboo Grove',jp:'嵐山竹林',d:'ป่าไผ่ขนาดใหญ่ เสียงลม สงบมาก อยู่ติดวัด Tenryu-ji เช่าเรือพายแม่น้ำ Katsura',b:'must',m:'https://maps.google.com/?q=Arashiyama+Bamboo+Grove+Kyoto'},
          {n:'Kinkaku-ji',jp:'金閣寺',d:'ปราสาทสีทองสะท้อนสระน้ำ ช่วงหิมะตกสวยสุด ค่าเข้า ¥500 ไปเช้าก่อนทัวร์มา',b:'must',m:'https://maps.google.com/?q=Kinkakuji+Kyoto'},
          {n:"Philosopher's Path",jp:'哲学の道',d:'ทางเดินริมคลอง 2 กม. ซากุระสองข้าง (เมษา) หรือใบไม้แดง (พฤศจิกา) คาเฟ่ตลอดทาง',b:'must',m:"https://maps.google.com/?q=Philosophers+Path+Kyoto"},
          {n:'Nishiki Market',jp:'錦市場',d:'ตลาดกินเดิน 400 เมตร อาหารโลคอลเกียวโต ทาโกะยากิ ปลาดอง ขนมหวาน เปิดทุกวัน',b:'local',m:'https://maps.google.com/?q=Nishiki+Market+Kyoto'},
          {n:'Gion District',jp:'祇園',d:'ย่านเกชาเก่าแก่ ถนน Hanamikoji ช่วงค่ำมีเกชาเดิน ไปเช้าตรู่ดีสุด',b:'must',m:'https://maps.google.com/?q=Gion+District+Kyoto'},
          {n:'Kiyomizu-dera',jp:'清水寺',d:'วัดบนเนินเขา เวทีไม้สูง 13 เมตรไม่มีตะปู วิวเมืองเกียวโต ซากุระและใบไม้แดงสวยสุด',b:'must',m:'https://maps.google.com/?q=Kiyomizudera+Kyoto'},
        ],
        food:[
          {n:'Tofu Cuisine Okutan',jp:'奥丹',d:'ร้านเต้าหู้อายุ 370 ปี สไตล์อาหารเกียวโตดั้งเดิม ในสวนใกล้ Nanzen-ji',b:'local',m:'https://maps.google.com/?q=Okutan+Kyoto'},
          {n:'Ippudo Ramen',jp:'一風堂',d:'ราเมน Hakata ซุปครีมมี่ เส้นเหนียว คิวสั้นกว่าโตเกียว',b:'must',m:'https://maps.google.com/?q=Ippudo+Ramen+Kyoto'},
        ],
        cafe:[
          {n:'% Arabica Arashiyama',jp:'% アラビカ',d:'คาเฟ่มินิมอล วิว Arashiyama ริมน้ำ กาแฟ Specialty ดีมาก คิวยาว',b:'cafe',m:'https://maps.google.com/?q=Arabica+Kyoto+Arashiyama'},
          {n:'Vermillion Cafe',jp:'バーミリオン',d:'คาเฟ่ใกล้ Fushimi Inari พักหลังเดินขึ้นเขา เมนูท้องถิ่น',b:'local',m:'https://maps.google.com/?q=Vermillion+Cafe+Fushimi+Kyoto'},
        ],
        trails:[
          {n:'Fushimi Inari Summit Trail',jp:'伏見稲荷',dist:'4 km',lv:'medium',d:'วิ่งผ่านประตู Torii หลายพัน บนยอดเขา Inari 233 เมตร เช้าตรู่เงียบสงบมาก',m:'https://maps.google.com/?q=Fushimi+Inari+trail',at:'https://www.alltrails.com/trail/japan/kyoto/fushimi-inari-taisha-summit-trail'},
          {n:'Daimonji Mountain',jp:'大文字山',dist:'5.5 km',lv:'medium',d:'เริ่มจาก Ginkaku-ji ขึ้นเขา Daimonji จุดชมวิวเกียวโตทั้งเมือง',m:'https://maps.google.com/?q=Daimonji+Mountain+Kyoto',at:'https://www.alltrails.com/trail/japan/kyoto/daimonji-ginkakuji-temple'},
        ]
      },
      Osaka:{
        sub:'สายกิน · กลางคืน · ช้อปปิ้ง',
        img:'https://images.unsplash.com/photo-1590559899731-a382839e5549?w=600&q=80',
        att:[
          {n:'Dotonbori',jp:'道頓堀',d:'ย่านกินดื่มที่ฮอตสุด ป้ายไฟสีสัน ป้าย Glico วิ่ง ทาโกะยากิ ราเมน กินเดินตลอด สนุกมากกลางคืน',b:'must',m:'https://maps.google.com/?q=Dotonbori+Osaka'},
          {n:'Osaka Castle Park',jp:'大阪城公園',d:'ปราสาทสีขาว-เขียว สวนซากุระ จุดชมวิวชั้น 8 พิพิธภัณฑ์ด้านใน',b:'must',m:'https://maps.google.com/?q=Osaka+Castle+Park'},
          {n:'Kuromon Ichiba Market',jp:'黒門市場',d:'ตลาดอาหารทะเลสดที่คนโอซาก้าไปซื้อ ปู ปลา เนื้อ ทานเดินได้ ราคาดี',b:'local',m:'https://maps.google.com/?q=Kuromon+Market+Osaka'},
        ],
        food:[
          {n:'Kushikatsu Daruma',jp:'串かつだるま',d:'ทอดเสียบไม้ต้นตำรับ กฎ "ห้ามจุ่มซอสสองครั้ง!" สนุก อร่อย ราคาดี',b:'must',m:'https://maps.google.com/?q=Kushikatsu+Daruma+Osaka'},
          {n:'Takoyaki Wanaka',jp:'たこ焼き わなか',d:'ทาโกะยากิต้นตำรับ ข้างในนุ่มครีมมี่ ร้านเก่าแก่ขึ้นชื่อ ย่าน Namba',b:'must',m:'https://maps.google.com/?q=Takoyaki+Wanaka+Osaka'},
        ],
        cafe:[{n:'Brooklyn Roasting Osaka',jp:'ブルックリンロースティング',d:'Specialty coffee ในโรงงานเก่า บรรยากาศ Industrial วิวแม่น้ำ ย่าน Kitahama',b:'cafe',m:'https://maps.google.com/?q=Brooklyn+Roasting+Osaka+Kitahama'}],
        trails:[{n:'Osaka Castle Moat Loop',jp:'大阪城公園',dist:'5 km',lv:'easy',d:'วนรอบคูน้ำปราสาทโอซาก้า เส้นลาดยาง นักวิ่งใช้ทุกเช้า ซากุระสวยเดือนเมษา',m:'https://maps.google.com/?q=Osaka+Castle+running+loop',at:'https://www.alltrails.com/trail/japan/osaka/osaka-castle-loop'}]
      },
      Nara:{
        sub:'กวางอิสระ · วัดใหญ่ · สวน',
        img:'https://images.unsplash.com/photo-1535139262971-ab8eb5e17e4c?w=600&q=80',
        att:[
          {n:'Nara Deer Park',jp:'奈良公園',d:'กวาง 1,200+ ตัวเดินอิสระ ซื้อ Shika-senbei ให้กวาง กวางจะโค้งคำนับ น่ารักมาก',b:'must',m:'https://maps.google.com/?q=Nara+Deer+Park'},
          {n:'Todai-ji Temple',jp:'東大寺',d:'วัดไม้ใหญ่ที่สุดในโลก พระพุทธรูปทองแดงสูง 15 เมตร ค่าเข้า ¥600',b:'must',m:'https://maps.google.com/?q=Todaiji+Temple+Nara'},
        ],
        food:[{n:'Kakinoha Sushi',jp:'柿の葉寿司',d:'ซูชิห่อใบพลับ อาหารพิเศษนารา ใบพลับช่วยถนอมรสชาติ',b:'local',m:'https://maps.google.com/?q=Kakinoha+sushi+Nara'}],
        cafe:[],
        trails:[{n:'Mt. Kasuga Forest Trail',jp:'春日山原始林',dist:'6 km',lv:'medium',d:'ป่าดึกดำบรรพ์ UNESCO บนเขา Kasuga ที่ได้รับการคุ้มครองมา 1,000 ปี',m:'https://maps.google.com/?q=Kasugayama+forest+Nara',at:'https://www.alltrails.com/trail/japan/nara/kasugayama-primeval-forest'}]
      },
    }
  },
  fukuoka:{
    name:'Fukuoka & Kyushu',sub:'ฟุกุโอกะ + คิวชู',
    bestTime:'🌸⭐ มีนาคม: ซากุระบานก่อนที่อื่น คนน้อย  |  ✅ ตุลาคม–พฤศจิกายน: ช่วงดีที่สุด',
    bg:'https://images.unsplash.com/photo-1513407030348-c983a97b98d8?w=1200&q=80',
    cities:{
      Fukuoka:{
        sub:'Yatai · ราเมน Hakata · ย่านกิน',
        img:'https://images.unsplash.com/photo-1513407030348-c983a97b98d8?w=600&q=80',
        att:[
          {n:'Fukuoka Yatai',jp:'博多屋台',d:'ร้านอาหารริมถนนบนล้อ มีเฉพาะฟุกุโอกะ เปิดกลางคืน ย่าน Nakasu/Tenjin กิน Local มากๆ',b:'local',m:'https://maps.google.com/?q=Fukuoka+Yatai+Nakasu'},
          {n:'Dazaifu Tenmangu',jp:'太宰府天満宮',d:'ศาลเจ้าเทพแห่งการเรียน บันไดดอกไม้ ประตูสีแดง ซื้อ Umegae Mochi นั่งรถไฟ 40 นาที',b:'must',m:'https://maps.google.com/?q=Dazaifu+Tenmangu'},
          {n:'Ohori Park',jp:'大濠公園',d:'สวนสวยริมทะเลสาบใจกลางเมือง วนรอบ 2 กม. นักวิ่งและปั่นจักรยานใช้ทุกวัน',b:'local',m:'https://maps.google.com/?q=Ohori+Park+Fukuoka'},
        ],
        food:[
          {n:'Ichiran Ramen Hakata',jp:'一蘭 博多本店',d:'ราเมนสาขาต้นตำรับ เส้น Sennuki บาง ซุปกระดูกหมูข้น Solo Booth นั่งคนเดียวสบาย',b:'must',m:'https://maps.google.com/?q=Ichiran+Hakata+Fukuoka'},
          {n:'Mentaiko',jp:'明太子',d:'ไข่ปลาคอดของฝากขึ้นชื่อ ซื้อที่ Fukuya หรือ Hakata Station กินสดๆ กับข้าวร้อน',b:'local',m:'https://maps.google.com/?q=Fukuya+Mentaiko+Fukuoka'},
          {n:'Hakata Mizutaki',jp:'博多水炊き',d:'หม้อไฟสไตล์ฮากาตะ ซุปไก่ใสเคี่ยวนาน กินกับน้ำจิ้มส้มยูซุ',b:'local',m:'https://maps.google.com/?q=Mizutaki+Hakata+Fukuoka'},
        ],
        cafe:[{n:'Coffee County Fukuoka',jp:'コーヒーカウンティ',d:'Specialty roaster ที่ดีที่สุดในฟุกุโอกะ ถั่วคัดพิเศษ บรรยากาศอบอุ่น',b:'cafe',m:'https://maps.google.com/?q=Coffee+County+Fukuoka'}],
        trails:[
          {n:'Ohori Park Loop',jp:'大濠公園',dist:'2 km',lv:'easy',d:'วนรอบทะเลสาบ Ohori Park สั้น สะอาด เรียบ เหมาะวอร์มอัพหรือวิ่งเล่น',m:'https://maps.google.com/?q=Ohori+Park+running',at:'https://www.alltrails.com/trail/japan/fukuoka/ohori-park-loop'},
          {n:'Mt. Aburayama Trail',jp:'油山',dist:'8 km',lv:'medium',d:'เขาใกล้เมือง วิ่งเทรลผ่านป่า วิวเมือง Fukuoka จากยอดเขา',m:'https://maps.google.com/?q=Mt+Aburayama+Fukuoka',at:'https://www.alltrails.com/trail/japan/fukuoka/aburayama'},
        ]
      },
      Nagasaki:{
        sub:'ประวัติศาสตร์ · วัฒนธรรมผสม · วิวท่าเรือ',
        img:'https://images.unsplash.com/photo-1570459027562-4a916cc6113f?w=600&q=80',
        att:[
          {n:'Nagasaki Peace Park',jp:'長崎平和公園',d:'อนุสาวรีย์สันติภาพ พิพิธภัณฑ์ระเบิดปรมาณู 1945 บรรยากาศสงบ',b:'must',m:'https://maps.google.com/?q=Nagasaki+Peace+Park'},
          {n:'Glover Garden',jp:'グラバー園',d:'สวนบนเขา รวมบ้านชาวต่างชาติยุคเมจิ วิว Nagasaki Harbor สวยงาม',b:'must',m:'https://maps.google.com/?q=Glover+Garden+Nagasaki'},
          {n:'Dejima Island',jp:'出島',d:'เกาะเล็กสมัยเอโดะที่ฮอลแลนด์ค้าขาย บูรณะใหม่ เข้าใจประวัติเปิดประเทศญี่ปุ่น',b:'local',m:'https://maps.google.com/?q=Dejima+Nagasaki'},
        ],
        food:[{n:'Champon Noodles',jp:'ちゃんぽん',d:'ก๋วยเตี๋ยวต้นกำเนิดนางาซากิ ซุปข้น ใส่ผัก เนื้อ ซีฟู้ด ร้านต้นตำรับ: Shikairo',b:'must',m:'https://maps.google.com/?q=Shikairo+Champon+Nagasaki'}],
        cafe:[],
        trails:[{n:'Mt. Inasa Night View Trail',jp:'稲佐山',dist:'4 km',lv:'medium',d:'ขึ้นเขา Inasa วิวกลางคืนนางาซากิ 1 ใน 3 วิวค่ำคืนสวยสุดในญี่ปุ่น มีกระเช้า',m:'https://maps.google.com/?q=Mt+Inasa+Nagasaki',at:'https://www.alltrails.com/trail/japan/nagasaki/mt-inasa'}]
      },
      Kumamoto:{
        sub:'ปราสาทดำ · ภูเขาไฟ Aso · เนื้อม้า',
        img:'https://images.unsplash.com/photo-1528360983277-13d401cdc186?w=600&q=80',
        att:[
          {n:'Kumamoto Castle',jp:'熊本城',d:'ปราสาทสีดำขนาดใหญ่ กำลังบูรณะหลังแผ่นดินไหว 2016 ชมการซ่อมแซมเป็นประสบการณ์พิเศษ',b:'must',m:'https://maps.google.com/?q=Kumamoto+Castle'},
          {n:'Mt. Aso Volcano',jp:'阿蘇山',d:'ภูเขาไฟคาลเดร่าใหญ่ที่สุดในโลก ปล่องสีเขียว Nakadake ขับรถขึ้นใกล้ๆ ได้',b:'must',m:'https://maps.google.com/?q=Mt+Aso+Kumamoto'},
          {n:'Suizenji Garden',jp:'水前寺成趣園',d:'สวนญี่ปุ่นสไตล์เอโดะ ภูเขาจำลอง Mt. Fuji และทะเลสาบ',b:'local',m:'https://maps.google.com/?q=Suizenji+Garden+Kumamoto'},
        ],
        food:[{n:'Basashi (เนื้อม้าดิบ)',jp:'馬刺し',d:'อาหารขึ้นชื่อสุดของ Kumamoto เนื้อม้าดิบ รสอ่อน นุ่ม กินกับขิงและซีอิ๊ว ต้องลอง',b:'local',m:'https://maps.google.com/?q=basashi+restaurant+Kumamoto'}],
        cafe:[],
        trails:[{n:'Mt. Aso Caldera Rim',jp:'阿蘇外輪山',dist:'10–30 km',lv:'hard',d:'วิ่งรอบขอบคาลเดร่า Aso ใหญ่ที่สุดในโลก วิวทุ่งหญ้าและภูเขาไฟ',m:'https://maps.google.com/?q=Mt+Aso+trail',at:'https://www.alltrails.com/trail/japan/kumamoto/aso-caldera'}]
      },
    }
  },
  hiroshima:{
    name:'Hiroshima & Chugoku',sub:'ฮิโรชิม่า + ชูโกกุ',
    bestTime:'🌸✅ มีนาคม: ซากุระบานเร็ว คนยังน้อย  |  ✅ ตุลาคม–พฤศจิกายน: อากาศดีที่สุด',
    bg:'https://images.unsplash.com/photo-1570459027562-4a916cc6113f?w=1200&q=80',
    cities:{
      Hiroshima:{
        sub:'สันติภาพ · หอยนางรม · โอโคโนมิยากิ',
        img:'https://images.unsplash.com/photo-1570459027562-4a916cc6113f?w=600&q=80',
        att:[
          {n:'Peace Memorial Park & Museum',jp:'平和記念公園',d:'สวน+พิพิธภัณฑ์ Dome ระเบิดนิวเคลียร์ 1945 ครบถ้วน ใช้เวลาครึ่งวัน',b:'must',m:'https://maps.google.com/?q=Hiroshima+Peace+Memorial+Park'},
          {n:'Hiroshima Castle',jp:'広島城',d:'ปราสาทสีดำ บูรณะใหม่หลังสงคราม วิวเมืองจากชั้นบน พิพิธภัณฑ์ประวัติศาสตร์',b:'must',m:'https://maps.google.com/?q=Hiroshima+Castle'},
          {n:'Shukkeien Garden',jp:'縮景園',d:'สวนญี่ปุ่นอายุ 400 ปี ทะเลสาบเล็ก สะพานหิน ใบไม้แดงสวยมาก ใจกลางเมือง',b:'local',m:'https://maps.google.com/?q=Shukkeien+Garden+Hiroshima'},
        ],
        food:[
          {n:'Hiroshima-style Okonomiyaki',jp:'広島風お好み焼き',d:'ทำเป็นชั้นๆ มีเส้นโซบะ ต่างจากโอซาก้าโดยสิ้นเชิง ต้องลองที่ Okonomimura มี 24 ร้าน',b:'must',m:'https://maps.google.com/?q=Okonomimura+Hiroshima'},
          {n:'Hiroshima Oyster',jp:'牡蠣',d:'ฮิโรชิม่าผลิตหอยนางรมมากที่สุดในญี่ปุ่น กินดิบ ทอด หรือย่าง ราคาถูกกว่าที่อื่น',b:'local',m:'https://maps.google.com/?q=oyster+restaurant+Hiroshima'},
        ],
        cafe:[{n:'Orizuru Tower Cafe',jp:'おりづるタワー',d:'คาเฟ่ชั้นบนตึกสูงติด Peace Park วิวเมือง Hiroshima ทั้งหมด',b:'cafe',m:'https://maps.google.com/?q=Orizuru+Tower+Hiroshima'}],
        trails:[{n:'Mitaki-dera Forest Trail',jp:'三滝寺',dist:'5 km',lv:'easy',d:'เส้นทางผ่านวัดกลางป่าและน้ำตก Mitaki ริมเมือง นั่ง JR ไป Mitaki Station',m:'https://maps.google.com/?q=Mitakidera+Hiroshima',at:'https://www.alltrails.com/trail/japan/hiroshima/mitakidera'}]
      },
      Miyajima:{
        sub:'Torii ลอยน้ำ · กวางเกาะ · ปลาไหลทะเล',
        img:'https://images.unsplash.com/photo-1528360983277-13d401cdc186?w=600&q=80',
        att:[
          {n:'Itsukushima Shrine + Torii',jp:'厳島神社',d:'ประตู Torii ลอยน้ำ วิวที่โด่งดังที่สุดในญี่ปุ่น ช่วงน้ำขึ้นดูเหมือนลอยกลางทะเล ค่ำคืนไฟส่องสวย',b:'must',m:'https://maps.google.com/?q=Itsukushima+Shrine+Miyajima'},
          {n:'Mt. Misen Ropeway',jp:'弥山',d:'กระเช้าขึ้นยอดเขา Misen 535 เมตร วิว Seto Inland Sea สวยมาก กวางเดินอิสระบนเกาะ',b:'must',m:'https://maps.google.com/?q=Mt+Misen+Miyajima+Ropeway'},
        ],
        food:[{n:'Anago Meshi',jp:'穴子飯',d:'ข้าวหน้าปลาไหลทะเล (Anago) หวานนุ่ม อาหารพิเศษเกาะ ร้าน Ueno เปิดมาตั้งแต่ 1901',b:'must',m:'https://maps.google.com/?q=Anago+Meshi+Miyajima+Ueno'}],
        cafe:[],
        trails:[{n:'Mt. Misen Hiking Trail',jp:'弥山登山道',dist:'8 km',lv:'medium',d:'เดิน/วิ่งขึ้น Mt. Misen แทนกระเช้า 3 เส้นทาง Omoto เส้นธรรมชาติสวยสุด',m:'https://maps.google.com/?q=Mt+Misen+hiking+Miyajima',at:'https://www.alltrails.com/trail/japan/hiroshima/mt-misen'}]
      },
      Okayama:{
        sub:'สวนสวย · ปราสาทดำ · ผลไม้',
        img:'https://images.unsplash.com/photo-1499002238440-d264edd596ec?w=600&q=80',
        att:[
          {n:'Korakuen Garden',jp:'後楽園',d:'1 ใน 3 สวนสวยที่สุดในญี่ปุ่น ริมแม่น้ำ Asahi มีนาในสวน ต้นสน ทะเลสาบ สวยทุกฤดู',b:'must',m:'https://maps.google.com/?q=Korakuen+Garden+Okayama'},
          {n:'Okayama Castle (Black)',jp:'岡山城',d:'ปราสาทสีดำ "Crow Castle" มองเห็นจาก Korakuen ข้ามแม่น้ำ สวยช่วงซากุระ',b:'must',m:'https://maps.google.com/?q=Okayama+Castle'},
        ],
        food:[{n:'Barazushi',jp:'ばら寿司',d:'ซูชิสไตล์โอคายาม่า ข้าวใส่ท็อปปิ้งซีฟู้ดหลายอย่าง สีสันสวย อาหารมงคลของเมือง',b:'local',m:'https://maps.google.com/?q=barazushi+Okayama'}],
        cafe:[],trails:[]
      },
    }
  },
  fuji:{
    name:'Fuji & Hakone',sub:'ฟูจิ + ฮาโกเน่',
    bestTime:'✅ พฤษภาคม (หลัง GW): อากาศดี คนน้อย  |  ✅⭐ ตุลาคม: วิวฟูจิชัดสุด  |  🌸 เมษายน: ซากุระ+ฟูจิ',
    bg:'https://images.unsplash.com/photo-1490806843957-31f4c9a91c65?w=1200&q=80',
    cities:{
      'Kawaguchiko':{
        sub:'ทะเลสาบ · วิวฟูจิ · ซากุระ+ฟูจิ',
        img:'https://images.unsplash.com/photo-1490806843957-31f4c9a91c65?w=600&q=80',
        att:[
          {n:'Lake Kawaguchiko',jp:'河口湖',d:'ทะเลสาบที่มีวิว Mt. Fuji สวยที่สุด ซากุระและใบไม้แดงสะท้อนน้ำ เช่าจักรยานรอบทะเลสาบ',b:'must',m:'https://maps.google.com/?q=Lake+Kawaguchiko'},
          {n:'Chureito Pagoda',jp:'忠霊塔',d:'เจดีย์ 5 ชั้น พื้นหลังเป็น Mt. Fuji ซากุระบาน+ฟูจิ = วิวที่โด่งดังสุด เดินขึ้น 400+ ขั้น',b:'must',m:'https://maps.google.com/?q=Chureito+Pagoda'},
          {n:'Mt. Fuji 5th Station',jp:'富士山5合目',d:'จุดเริ่มปีนฟูจิ รถบัสขึ้นไปได้ วิวดี ซื้อของที่ระลึก ปีนจริงได้ กรกฎา–กันยา',b:'must',m:'https://maps.google.com/?q=Mt+Fuji+5th+Station'},
        ],
        food:[{n:'Hoto Fudo',jp:'ほうとう不動',d:'ก๋วยเตี๋ยวเส้นแบนซุปมิโซะ อาหารท้องถิ่น ร้านทรงกลมรูปฟูจิ เป็น Landmark เลย',b:'must',m:'https://maps.google.com/?q=Hoto+Fudo+Kawaguchiko'}],
        cafe:[{n:'Kawaguchiko Herb Hall',jp:'河口湖ハーブ館',d:'คาเฟ่ริมทะเลสาบ วิวฟูจิจากหน้าต่าง ชาสมุนไพรและขนมหวาน',b:'cafe',m:'https://maps.google.com/?q=Kawaguchiko+Herb+Hall'}],
        trails:[
          {n:'Lake Yamanakako Loop',jp:'山中湖',dist:'14 km',lv:'easy',d:'วิ่งรอบทะเลสาบ Yamanakako วิว Mt. Fuji ชัดมาก เส้นลาดยาง เหมาะ Long Run',m:'https://maps.google.com/?q=Lake+Yamanakako',at:'https://www.alltrails.com/trail/japan/yamanashi/lake-yamanakako-loop'},
          {n:'Mt. Fuji Yoshida Trail',jp:'吉田ルート',dist:'14 km',lv:'hard',d:'เส้นปีนจริง Yoshida Route เปิด กรกฎา–กันยา 6-8 ชม. ขึ้น เตรียมร่างกายให้ดี',m:'https://maps.google.com/?q=Mt+Fuji+Yoshida+trail',at:'https://www.alltrails.com/trail/japan/yamanashi/mount-fuji-yoshida-trail'},
        ]
      },
      Hakone:{
        sub:'ออนเซ็น · พิพิธภัณฑ์กลางแจ้ง · ภูเขาไฟ',
        img:'https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=600&q=80',
        att:[
          {n:'Hakone Open Air Museum',jp:'箱根野外美術館',d:'พิพิธภัณฑ์กลางแจ้ง งานศิลปะทั่วโลก บ่อออนเซ็นเท้า วิวภูเขา นั่ง Romancecar 85 นาที',b:'must',m:'https://maps.google.com/?q=Hakone+Open+Air+Museum'},
          {n:'Owakudani',jp:'大涌谷',d:'หุบเขาภูเขาไฟ ควันกำมะถัน ไข่ดำ Kuro-tamago เชื่อว่าทำให้อายุยืน',b:'must',m:'https://maps.google.com/?q=Owakudani+Hakone'},
          {n:'Hakone Shrine (Lake Ashi)',jp:'箱根神社',d:'ประตู Torii ลอยน้ำทะเลสาบ Ashi วิว Mt. Fuji ล่องเรือข้ามฟากทะเลสาบ',b:'must',m:'https://maps.google.com/?q=Hakone+Shrine+Lake+Ashi'},
        ],
        food:[{n:'Hakone Ryokan Dinner',jp:'旅館夕食',d:'ค้างคืน Ryokan อาหาร kaiseki หลายคอร์ส ออนเซ็นส่วนตัว ประสบการณ์ญี่ปุ่นแท้ ¥10,000+',b:'local',m:'https://maps.google.com/?q=Ryokan+Hakone'}],
        cafe:[],
        trails:[{n:'Old Tokaido Road',jp:'旧東海道',dist:'8 km',lv:'medium',d:'ถนนหินบะซอลต์ยุคเอโดะ ผ่านป่าสน วิว Lake Ashi เชื่อม Moto-Hakone กับ Hakone-Yumoto',m:'https://maps.google.com/?q=Old+Tokaido+Road+Hakone',at:'https://www.alltrails.com/trail/japan/kanagawa/hakone-old-tokaido-trail'}]
      },
    }
  },
  takayama:{
    name:'Takayama & Kanazawa',sub:'ทาคายาม่า + คานาซาวะ',
    bestTime:'❄️⭐ กุมภาพันธ์: หิมะหนาสุด วิวโปสการ์ด  |  🌸✅ ปลายเมษายน: ซากุระช้า คนน้อย  |  🍂 พฤศจิกายน: ใบไม้แดง',
    bg:'https://images.unsplash.com/photo-1601823984263-3f28a4e8c29f?w=1200&q=80',
    cities:{
      Takayama:{
        sub:'เมืองเก่าเอโดะ · เนื้อ Hida · ตลาดเช้า',
        img:'https://images.unsplash.com/photo-1601823984263-3f28a4e8c29f?w=600&q=80',
        att:[
          {n:'Sanmachi Suji Old Town',jp:'三町筋',d:'ย่านเมืองเก่าเอโดะที่อนุรักษ์สมบูรณ์สุดในญี่ปุ่น เดินเล่น ชิมสาเก ถ่ายรูป',b:'must',m:'https://maps.google.com/?q=Sanmachi+Suji+Takayama'},
          {n:'Takayama Jinya',jp:'高山陣屋',d:'อาคารรัฐบาลเก่าเอโดะ 300 ปี ยังคงสภาพเดิม แห่งเดียวในญี่ปุ่น',b:'must',m:'https://maps.google.com/?q=Takayama+Jinya'},
          {n:'Hida Folk Village',jp:'飛騨の里',d:'หมู่บ้าน Open Air Museum บ้านทรงกาบโถจริงๆ ที่ย้ายมารวมกัน สวยมากช่วงหิมะ',b:'must',m:'https://maps.google.com/?q=Hida+Folk+Village+Takayama'},
          {n:'Takayama Morning Market',jp:'朝市',d:'ตลาดเช้าขายผักและของท้องถิ่น เปิดทุกวัน 7:00–12:00 มี 2 ตลาด',b:'local',m:'https://maps.google.com/?q=Takayama+morning+market'},
        ],
        food:[
          {n:'Hida Beef',jp:'飛騨牛',d:'วากิวของ Takayama ระดับ A5 กินเป็น sukiyaki หรือ steak ราคาถูกกว่าโตเกียว',b:'must',m:'https://maps.google.com/?q=Hida+beef+restaurant+Takayama'},
          {n:'Mitarashi Dango',jp:'みたらし団子',d:'ดังโงะจิ้มซอสมิตาราชิ ขนมประจำเมือง หาซื้อย่านเมืองเก่า กินเดินร้อนๆ',b:'local',m:'https://maps.google.com/?q=Mitarashi+dango+Takayama'},
        ],
        cafe:[{n:'Cafe Janome',jp:'カフェじゃのめ',d:'คาเฟ่ในบ้านไม้เก่าย่านเมืองเก่า Takayama กาแฟและของหวานสไตล์ญี่ปุ่น',b:'cafe',m:'https://maps.google.com/?q=cafe+Sanmachi+Takayama'}],
        trails:[{n:'Mt. Norikura Trail',jp:'乗鞍岳',dist:'10 km',lv:'medium',d:'ขึ้นยอด Norikura 3,026 เมตร จาก Tatamidaira วิวทะเลเมฆและ Japan Alps เปิดฤดูร้อน',m:'https://maps.google.com/?q=Mt+Norikura+Takayama',at:'https://www.alltrails.com/trail/japan/gifu/mt-norikura'}]
      },
      Shirakawago:{
        sub:'หมู่บ้าน UNESCO · หลังคากาบโถ · หิมะ',
        img:'https://images.unsplash.com/photo-1601823984263-3f28a4e8c29f?w=600&q=80',
        att:[
          {n:'Shirakawago Village',jp:'白川郷',d:'หมู่บ้าน UNESCO หลังคากาบโถ สวยที่สุดช่วงหิมะปกคลุม ต้องจอง shuttle bus ล่วงหน้า',b:'must',m:'https://maps.google.com/?q=Shirakawago'},
          {n:'Ogimachi Viewpoint',jp:'荻町城跡展望台',d:'จุดชมวิวหมู่บ้านจากด้านบน วิวทั้งหมู่บ้านกลางหิมะ เดินขึ้นหรือนั่ง shuttle',b:'must',m:'https://maps.google.com/?q=Ogimachi+viewpoint+Shirakawago'},
        ],
        food:[{n:'Doburoku',jp:'どぶろく',d:'เหล้าข้าวดั้งเดิมของหมู่บ้าน ข้นคล้ายโยเกิร์ต หาดื่มเฉพาะที่นี่ช่วงเทศกาล (ตุลาคม)',b:'local',m:'https://maps.google.com/?q=Shirakawago+doburoku'}],
        cafe:[],trails:[]
      },
      Kanazawa:{
        sub:'สวน Kenroku-en · ตลาดปลา · Gold Leaf',
        img:'https://images.unsplash.com/photo-1545569341-9eb8b30979d9?w=600&q=80',
        att:[
          {n:'Kenroku-en Garden',jp:'兼六園',d:'1 ใน 3 สวนสวยสุดในญี่ปุ่น สวยทุกฤดู ช่วงหิมะ Yukitsuri (ค้ำต้นสน) สวยมาก',b:'must',m:'https://maps.google.com/?q=Kenrokuen+Garden+Kanazawa'},
          {n:'Higashi Chaya District',jp:'東茶屋街',d:'ย่านชายาเก่าแก่ บ้านไม้สวย Gold Leaf ของ Kanazawa ขึ้นชื่อในทุกสิ่ง',b:'must',m:'https://maps.google.com/?q=Higashi+Chaya+Kanazawa'},
          {n:'21st Century Museum',jp:'21世紀美術館',d:'พิพิธภัณฑ์ศิลปะสมัยใหม่ ทรงกลม Swimming Pool ลวงตาโด่งดัง เข้าบางส่วนฟรี',b:'must',m:'https://maps.google.com/?q=21st+Century+Museum+Kanazawa'},
        ],
        food:[
          {n:'Omicho Market',jp:'近江町市場',d:'ตลาดสด 300 ปี ปลาดิบสดจากทะเลญี่ปุ่น ซูชิอร่อยราคาดีมาก',b:'must',m:'https://maps.google.com/?q=Omicho+Market+Kanazawa'},
          {n:'Gold Leaf Ice Cream',jp:'金箔アイス',d:'ไอศกรีมหุ้มทองคำเปลว ถ่ายรูปสวยมาก ซื้อได้ย่าน Higashi Chaya',b:'local',m:'https://maps.google.com/?q=gold+leaf+ice+cream+Kanazawa'},
        ],
        cafe:[{n:'Cafe Dorian',jp:'カフェ・ドリアン',d:'ในตึกอิฐยุคเมจิ กาแฟและขนมหวานสไตล์ญี่ปุ่นโบราณ',b:'cafe',m:'https://maps.google.com/?q=Cafe+Dorian+Kanazawa'}],
        trails:[{n:'Kanazawa Satoyama Trail',jp:'さとやま',dist:'12 km',lv:'medium',d:'เส้นทางชนบทรอบเมือง Kanazawa ผ่านนาข้าว หมู่บ้านเก่า ใบไม้แดงสวยเดือนพฤศจิกายน',m:'https://maps.google.com/?q=Kanazawa+hiking',at:'https://www.alltrails.com/japan/ishikawa'}]
      },
    }
  },
  tohoku:{
    name:'Tohoku',sub:'โทโฮกุ',
    bestTime:'🌸 เมษายน: ซากุระ Hirosaki ดังมาก  |  🎆 สิงหาคม: Nebuta Matsuri  |  ❄️ กุมภาพันธ์: เทศกาลหิมะ',
    bg:'https://images.unsplash.com/photo-1545569341-9eb8b30979d9?w=1200&q=80',
    cities:{
      Sendai:{
        sub:'Gyutan · ซากุระ Matsushima · จิ้งจอก',
        img:'https://images.unsplash.com/photo-1545569341-9eb8b30979d9?w=600&q=80',
        att:[
          {n:'Matsushima Bay',jp:'松島',d:'1 ใน 3 วิวสวยสุดในญี่ปุ่น เกาะน้อยกว่า 260 เกาะ วัดสวย ล่องเรือ ใบไม้แดงพฤศจิกายน',b:'must',m:'https://maps.google.com/?q=Matsushima+Bay+Miyagi'},
          {n:'Zuihoden Mausoleum',jp:'瑞鳳殿',d:'สุสาน Date Masamune ตกแต่งสีสันสดใสสไตล์ Momoyama ท่ามกลางป่าสน',b:'must',m:'https://maps.google.com/?q=Zuihoden+Mausoleum+Sendai'},
          {n:'Zao Fox Village',jp:'蔵王きつね村',d:'หมู่บ้านจิ้งจอกกว่า 100 ตัว เดินอิสระรอบๆ คุณ สัมผัสได้ ใกล้ Shiroishi Station',b:'local',m:'https://maps.google.com/?q=Zao+Fox+Village+Miyagi'},
        ],
        food:[{n:'Gyutan (ลิ้นวัวย่าง)',jp:'牛タン',d:'ลิ้นวัวย่างต้นตำรับเซนได หนา นุ่ม กินกับข้าวบาร์เล่ยและซุปหางวัว ร้านแนะนำ: Rikyu',b:'must',m:'https://maps.google.com/?q=Gyutan+Rikyu+Sendai'}],
        cafe:[],
        trails:[{n:'Oirase Stream Trail',jp:'奥入瀬渓流',dist:'14 km',lv:'easy',d:'เส้นทางริมลำธาร Oirase ผ่านน้ำตกเล็กๆ หลายแห่ง ป่าเมเปิ้ลใบไม้แดงสวยที่สุดในญี่ปุ่น',m:'https://maps.google.com/?q=Oirase+Stream+Aomori',at:'https://www.alltrails.com/trail/japan/aomori/oirase-gorge'}]
      },
      Aomori:{
        sub:'ซากุระ Hirosaki · Nebuta · แอปเปิ้ล',
        img:'https://images.unsplash.com/photo-1522383225653-ed111181a951?w=600&q=80',
        att:[
          {n:'Hirosaki Castle & Park',jp:'弘前城',d:'จุดดูซากุระที่สวยที่สุดในภาคเหนือ ต้นซากุระกว่า 2,600 ต้น คนน้อยกว่าโตเกียวมาก',b:'must',m:'https://maps.google.com/?q=Hirosaki+Castle'},
          {n:'Nebuta Museum Wa Rasse',jp:'ねぶたの家',d:'พิพิธภัณฑ์ตกแต่งวัวลอยขนาดใหญ่ เทศกาล Nebuta ยิ่งใหญ่สุดของโทโฮกุ',b:'must',m:'https://maps.google.com/?q=Nebuta+Museum+Aomori'},
        ],
        food:[{n:'Aomori Seafood + Apple',jp:'青森りんご',d:'แอปเปิ้ล Aomori ขึ้นชื่อ + หอยเชลล์ Hotate จาก Mutsu Bay สดและอร่อยมาก',b:'local',m:'https://maps.google.com/?q=Aomori+seafood'}],
        cafe:[],trails:[]
      },
    }
  },
};

// ── STATE ──────────────────────────────
let curR=null, curC=null;
let checks=JSON.parse(localStorage.getItem('jp3c')||'{}');
let custom=JSON.parse(localStorage.getItem('jp3x')||'{}');

// ── HOME TABS ──────────────────────────
function homeTab(t,btn){
  ['map','rail','cal'].forEach(k=>{
    const el=document.getElementById('ht-'+k);
    if(el) el.style.display='none';
  });
  document.querySelectorAll('.htab-btn').forEach(b=>b.classList.remove('on'));
  const el=document.getElementById('ht-'+t);
  if(el) el.style.display=(t==='map')?'grid':'block';
  btn.classList.add('on');
}

// ── GO REGION ─────────────────────────
function goRegion(id){
  if(!REGIONS[id]) return;
  curR=id;
  const r=REGIONS[id];
  document.getElementById('rHeroImg').style.backgroundImage=`url('${r.bg}')`;
  document.getElementById('rHeroTitle').textContent=r.name;
  document.getElementById('rHeroSub').textContent=r.sub;
  document.getElementById('rBestBar').innerHTML='⏰ ช่วงเวลาแนะนำ: <strong>'+r.bestTime+'</strong>';
  document.getElementById('bc-region').textContent=r.name;

  // Build city cards
  const grid=document.getElementById('cityCardsGrid');
  grid.innerHTML='';
  Object.entries(r.cities).forEach(([cn,cd])=>{
    const totalAtt=(cd.att||[]).length+(cd.food||[]).length+(cd.cafe||[]).length;
    const trailCount=(cd.trails||[]).length;
    const div=document.createElement('div');
    div.className='city-card';
    div.onclick=()=>goCity(id,cn);
    div.innerHTML=`
      <div class="city-card-img" style="background-image:url('${cd.img||''}')"></div>
      <div class="city-card-body">
        <div class="city-card-name">📍 ${cn}</div>
        <div class="city-card-sub">${cd.sub||''}</div>
        <div class="city-card-arrow">
          <span class="city-card-count">${totalAtt} สถานที่ · ${trailCount} trail</span>
          <span class="city-card-go">→</span>
        </div>
      </div>`;
    grid.appendChild(div);
  });

  show('pgRegion');
}

// ── GO CITY ───────────────────────────
function goCity(rid,cn){
  curR=rid; curC=cn;
  const r=REGIONS[rid], cd=r.cities[cn];

  document.getElementById('cHeroImg').style.backgroundImage=`url('${cd.img||r.bg}')`;
  document.getElementById('cHeroTitle').textContent=cn;
  document.getElementById('cHeroSub').textContent=(cd.sub||'')+' — '+r.name;
  document.getElementById('bc-region2').textContent=r.name;
  document.getElementById('bc-city').textContent=cn;

  // Reset tabs
  document.querySelectorAll('.itab').forEach((b,i)=>b.classList.toggle('on',i===0));
  document.querySelectorAll('.ipane').forEach((p,i)=>p.classList.toggle('on',i===0));

  // Render all panes
  renderPane('att',  cd.att||[]);
  renderPane('food', cd.food||[]);
  renderPane('cafe', cd.cafe||[]);
  renderTrails(cd.trails||[]);
  updateProgress();

  show('pgCity');
}

// ── RENDER PLACE PANE ─────────────────
const BL={must:'bm',local:'bl',food:'bf',cafe:'bc'};
const BT={must:'Must-go',local:'Local Gem',food:'ร้านอาหาร',cafe:'คาเฟ่'};

function renderPane(tab, baseItems){
  const ckey=curR+'|'+curC+'|'+tab;
  const extra=custom[ckey]||[];
  const baseLen=baseItems.length;
  const items=[...baseItems,...extra];
  const el=document.getElementById('ip-'+tab);
  if(!items.length){ el.innerHTML='<p class="empty">ยังไม่มีข้อมูล — เพิ่มเองได้ด้านล่าง ⬇️</p>'; return; }
  el.innerHTML='<div class="pg">'+items.map((p,i)=>{
    const ck=curR+'|'+curC+'|'+tab+'|'+i;
    const done=!!checks[ck];
    const isCustom = i >= baseLen;
    const customIdx = i - baseLen;
    const imgStyle = p.img
      ? `background-image:url('${p.img}');background-size:cover;background-position:center`
      : getBgColor(p.b);
    return `<div class="pc">
      <div class="pimg" style="${imgStyle}">
        <span class="pbadge ${BL[p.b]||'bm'}">${BT[p.b]||p.b}</span>
        ${isCustom ? `<button class="del-btn"
          data-r="${curR}" data-c="${curC}" data-tab="${tab}" data-idx="${customIdx}"
          onclick="handleDelete(this)" title="ลบสถานที่นี้">✕</button>` : ''}
      </div>
      <div class="pbody">
        <div class="pname">${p.n}${isCustom?'<span class="del-badge">เพิ่มเอง</span>':''}</div>
        ${p.jp?`<div class="pjp">${p.jp}</div>`:''}
        <div class="pdesc">${p.d}</div>
        <div class="pact">
          <button class="chk${done?' on':''}" onclick="toggleCheck('${ck}',this)">${done?'✓':''}</button>
          ${p.m?`<a class="mapbtn" href="${p.m}" target="_blank">🗺️ Maps</a>`:''}
        </div>
      </div>
    </div>`;
  }).join('')+'</div>';
}

function getBgColor(b){
  const m={must:'background:#d4c4a8',local:'background:#c4d4b8',food:'background:#d4c8a8',cafe:'background:#c8c0b0'};
  return m[b]||'background:#d0c8b8';
}

function handleDelete(btn){
  const r   = btn.getAttribute('data-r');
  const c   = btn.getAttribute('data-c');
  const tab = btn.getAttribute('data-tab');
  const idx = parseInt(btn.getAttribute('data-idx'), 10);
  const ckey = r+'|'+c+'|'+tab;
  if(!custom[ckey] || idx < 0 || idx >= custom[ckey].length){
    alert('ไม่พบสถานที่ที่จะลบ'); return;
  }
  const name = custom[ckey][idx]?.n || 'สถานที่นี้';
  if(!confirm(`ลบ "${name}" ออกจากรายการ?`)) return;
  custom[ckey].splice(idx, 1);
  if(custom[ckey].length === 0) delete custom[ckey];
  localStorage.setItem('jp3x', JSON.stringify(custom));
  const cd = REGIONS[r]?.cities[c];
  if(cd){ curR=r; curC=c; renderPane(tab, cd[tab]||[]); }
  updateProgress();
}

// ── RENDER TRAILS ─────────────────────
const LVC={easy:'t-easy',medium:'t-med',hard:'t-hard'};
const LVT={easy:'ง่าย',medium:'ปานกลาง',hard:'ยาก'};
function renderTrails(trails){
  const el=document.getElementById('ip-trail');
  if(!trails.length){ el.innerHTML='<p class="empty">ยังไม่มีข้อมูล Trail ในเมืองนี้</p>'; return; }
  el.innerHTML='<div class="tg">'+trails.map(t=>`
    <div class="tc">
      <div class="tc-h"><span class="tc-icon">🏃</span><div><div class="tc-name">${t.n}</div><div class="tc-jp">${t.jp}</div></div></div>
      <div class="tc-meta">
        <span class="ttag">📏 ${t.dist}</span>
        <span class="ttag ${LVC[t.lv]||''}">⚡ ${LVT[t.lv]||t.lv}</span>
      </div>
      <div class="tc-desc">${t.d}</div>
      <div class="tc-links">
        ${t.m?`<a class="mapbtn" href="${t.m}" target="_blank">🗺️ Google Maps</a>`:''}
        ${t.at?`<a class="extbtn" href="${t.at}" target="_blank">🌲 AllTrails</a>`:''}
      </div>
    </div>`).join('')+'</div>';
}

// ── SWITCH INNER TAB ──────────────────
function switchITab(tab, btn){
  document.querySelectorAll('.itab').forEach(b=>b.classList.remove('on'));
  document.querySelectorAll('.ipane').forEach(p=>p.classList.remove('on'));
  btn.classList.add('on');
  document.getElementById('ip-'+tab).classList.add('on');
}

// ── CHECK ─────────────────────────────
function toggleCheck(key,btn){
  checks[key]=!checks[key];
  localStorage.setItem('jp3c',JSON.stringify(checks));
  btn.classList.toggle('on');
  btn.textContent=checks[key]?'✓':'';
  updateProgress();
}
function updateProgress(){
  const cd=REGIONS[curR]?.cities[curC];
  if(!cd) return;
  let total=0,done=0;
  ['att','food','cafe'].forEach(tab=>{
    const ckey=curR+'|'+curC+'|'+tab;
    const items=[...(cd[tab]||[]),...(custom[ckey]||[])];
    items.forEach((_,i)=>{ total++; if(checks[curR+'|'+curC+'|'+tab+'|'+i]) done++; });
  });
  const pct=total>0?Math.round(done/total*100):0;
  document.getElementById('progLabel').textContent=`เช็คแล้ว ${done} / ${total} สถานที่ (${pct}%)`;
  document.getElementById('progFill').style.width=pct+'%';
}

// ── ADD PLACE ─────────────────────────
function addPlace(){
  const name=document.getElementById('a-name').value.trim();
  if(!name){alert('กรุณาใส่ชื่อสถานที่ครับ');return;}
  const tab=document.getElementById('a-tab').value;
  const ckey=curR+'|'+curC+'|'+tab;
  if(!custom[ckey]) custom[ckey]=[];
  custom[ckey].push({
    n:name,
    jp:document.getElementById('a-jp').value.trim(),
    d:document.getElementById('a-desc').value.trim()||'บันทึกส่วนตัว',
    m:document.getElementById('a-map').value.trim(),
    b:document.getElementById('a-badge').value,
  });
  localStorage.setItem('jp3x',JSON.stringify(custom));
  ['a-name','a-jp','a-desc','a-map'].forEach(id=>{ document.getElementById(id).value=''; });

  // Re-render that pane
  const cd=REGIONS[curR].cities[curC];
  renderPane(tab, cd[tab]||[]);
  updateProgress();
  // Switch to that tab
  document.querySelectorAll('.itab').forEach(b=>b.classList.remove('on'));
  document.querySelectorAll('.ipane').forEach(p=>p.classList.remove('on'));
  const tabMap={att:0,food:1,cafe:2,trail:3};
  document.querySelectorAll('.itab')[tabMap[tab]||0].classList.add('on');
  document.getElementById('ip-'+tab).classList.add('on');
  alert(`✅ เพิ่ม "${name}" แล้วครับ!`);
}

// ── NAVIGATE ──────────────────────────
function goHome(){ show('pgHome'); }
function backToRegion(){ if(curR) goRegion(curR); }
function show(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  window.scrollTo(0,0);
  // init Rail Pass page on first visit
  if(id==='pgRail' && !window._railInit){
    window._railInit=true;
    buildPassCards();
    buildCityChecklist();
  }
}
</script>

<!-- ══════════════════════════════════════════
     PAGE: RAIL PASS GUIDE
══════════════════════════════════════════ -->
<div id="pgRail" class="page">

<style>
/* ── RAIL PAGE STYLES ── */
.rp-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;}
.rp-nav .logo{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#fff;letter-spacing:4px;white-space:nowrap;}
.rp-nav .logo span{color:var(--gold);}
.rp-hero{background:linear-gradient(135deg,#1a1a2e,#0d2137);padding:32px 22px;text-align:center;}
.rp-hero h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(26px,5vw,52px);color:#fff;letter-spacing:5px;}
.rp-hero h1 span{color:var(--gold);}
.rp-hero p{color:#aaa;font-size:12px;margin-top:5px;}
.rp-tabbar{display:flex;gap:0;border-bottom:2px solid var(--border);background:#fff;position:sticky;top:57px;z-index:90;overflow-x:auto;}
.rp-tab{padding:11px 18px;font-family:'Noto Sans Thai',sans-serif;font-size:12px;background:none;border:none;cursor:pointer;color:var(--muted);border-bottom:3px solid transparent;margin-bottom:-2px;transition:all .2s;white-space:nowrap;}
.rp-tab.on{color:var(--red);border-bottom-color:var(--red);font-weight:700;}
.rp-pane{display:none;max-width:1040px;margin:0 auto;padding:26px 18px 60px;}
.rp-pane.on{display:block;}
.rp-stitle{font-family:'Shippori Mincho',serif;font-size:19px;border-left:4px solid var(--red);padding-left:11px;margin-bottom:18px;}
.rp-tip{background:#fff9f0;border:1px solid #f0d8a0;border-radius:11px;padding:14px;margin-bottom:18px;font-size:12px;line-height:1.9;color:#555;}
.rp-tip strong{color:var(--orange);}
.rp-tip a{color:var(--blue);text-decoration:none;}
.rp-tip a:hover{text-decoration:underline;}

/* Pass cards */
.rp-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(265px,1fr));gap:15px;}
.rp-card{background:#fff;border-radius:13px;border:2px solid var(--border);padding:17px;cursor:pointer;transition:all .2s;position:relative;overflow:hidden;}
.rp-card::before{content:'';position:absolute;top:0;left:0;right:0;height:4px;background:var(--rpc,var(--blue));}
.rp-card:hover{transform:translateY(-4px);box-shadow:0 10px 28px rgba(0,0,0,.12);border-color:var(--rpc,var(--blue));}
.rp-card-head{display:flex;align-items:center;gap:11px;margin-bottom:11px;}
.rp-icon{font-size:30px;}
.rp-title{font-weight:700;font-size:14px;line-height:1.3;}
.rp-sub{font-size:11px;color:var(--muted);margin-top:2px;}
.rp-badge{display:inline-block;color:#fff;font-size:10px;font-weight:700;padding:3px 9px;border-radius:18px;margin-bottom:9px;}
.rp-ctags{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:11px;}
.rp-ctag{font-size:9px;padding:2px 7px;border-radius:9px;background:#f0ebe0;}
.rp-desc{font-size:11px;color:#555;line-height:1.7;margin-bottom:11px;}
.rp-cta{display:flex;align-items:center;justify-content:space-between;}
.rp-detail{font-size:11px;font-weight:700;cursor:pointer;background:none;border:none;font-family:'Noto Sans Thai',sans-serif;}

/* Modal */
.rp-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.6);z-index:500;overflow-y:auto;padding:18px;}
.rp-overlay.on{display:flex;align-items:flex-start;justify-content:center;}
.rp-modal{background:#fff;border-radius:17px;max-width:800px;width:100%;margin:auto;overflow:hidden;}
.rp-mhero{padding:22px 26px 18px;position:relative;}
.rp-mhero h2{font-family:'Bebas Neue',sans-serif;font-size:clamp(22px,4vw,38px);letter-spacing:3px;color:#fff;}
.rp-mhero p{color:rgba(255,255,255,.8);font-size:11px;margin-top:3px;}
.rp-mclose{position:absolute;top:14px;right:14px;width:32px;height:32px;border-radius:50%;background:rgba(255,255,255,.2);border:none;color:#fff;font-size:17px;cursor:pointer;display:flex;align-items:center;justify-content:center;}
.rp-mbody{padding:22px 26px 28px;}
.rp-msecs{display:grid;grid-template-columns:1fr 1fr;gap:18px;}
@media(max-width:560px){.rp-msecs{grid-template-columns:1fr;}}
.rp-msec h3{font-size:12px;font-weight:700;margin-bottom:9px;display:flex;align-items:center;gap:5px;}
.rp-ptable{width:100%;border-collapse:collapse;font-size:11px;}
.rp-ptable th{background:#f5f0e8;padding:6px 9px;text-align:left;font-weight:700;border-bottom:1px solid var(--border);}
.rp-ptable td{padding:6px 9px;border-bottom:1px solid #f0ebe0;}
.rp-ptable tr:last-child td{border:none;}
.rp-ilist{list-style:none;}
.rp-ilist li{font-size:11px;color:#444;padding:5px 0;border-bottom:1px solid #f5f0e8;display:flex;gap:7px;line-height:1.6;}
.rp-ilist li:last-child{border:none;}
.rp-ilist li::before{content:'•';color:var(--red);flex-shrink:0;}
.rp-mapwrap{margin:18px 0;}
.rp-mapwrap h3{font-size:12px;font-weight:700;margin-bottom:9px;}
.rp-mapimg{width:100%;max-height:300px;object-fit:contain;border-radius:9px;border:1px solid var(--border);background:#f5f0e8;display:block;}
.rp-mapsrc{font-size:9px;color:var(--muted);margin-top:4px;text-align:right;}
.rp-mapsrc a{color:var(--blue);text-decoration:none;}
.rp-mapfb{display:none;align-items:center;justify-content:center;flex-direction:column;gap:9px;padding:26px;background:#f5f0e8;border-radius:9px;border:1px solid var(--border);}
.rp-schref{background:#f5f0e8;border-radius:9px;padding:12px;margin-top:14px;font-size:11px;color:#555;line-height:1.8;}
.rp-schref strong{color:var(--ink);}
.rp-schref a{color:var(--blue);text-decoration:none;}
.rp-lgrid{display:grid;grid-template-columns:1fr 1fr;gap:7px;margin-top:14px;}
@media(max-width:460px){.rp-lgrid{grid-template-columns:1fr;}}
.rp-lbtn{display:flex;align-items:center;gap:7px;padding:9px 12px;border-radius:9px;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;font-size:11px;font-weight:700;transition:opacity .2s;}
.rp-lbtn:hover{opacity:.85;}
.rp-lbtn.primary{background:var(--red);color:#fff;}
.rp-lbtn.secondary{background:var(--ink);color:#fff;}
.rp-lbtn.ext{background:#f0ebe0;color:var(--ink);}

/* Recommender */
.rp-rec-intro{background:#fff;border-radius:13px;border:1px solid var(--border);padding:18px;margin-bottom:22px;font-size:12px;color:#555;line-height:1.8;}
.rp-cc-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));gap:9px;margin-bottom:22px;}
.rp-cc{display:flex;align-items:center;gap:9px;background:#fff;border:1.5px solid var(--border);border-radius:9px;padding:9px 12px;cursor:pointer;transition:all .2s;}
.rp-cc.on{background:var(--ink);color:#fff;border-color:var(--ink);}
.rp-cbox{width:17px;height:17px;border-radius:4px;border:2px solid var(--border);background:#fff;display:flex;align-items:center;justify-content:center;font-size:10px;flex-shrink:0;transition:all .2s;}
.rp-cc.on .rp-cbox{background:var(--gold);border-color:var(--gold);color:#1a1a2e;font-weight:700;}
.rp-clabel{font-size:12px;font-weight:600;}
.rp-csub{font-size:9px;color:var(--muted);margin-top:1px;}
.rp-cc.on .rp-csub{color:rgba(255,255,255,.65);}
.rp-recbtn{padding:11px 26px;background:var(--red);color:#fff;border:none;border-radius:9px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:13px;font-weight:700;transition:background .2s;}
.rp-recbtn:hover{background:#a93226;}
.rp-result{display:none;margin-top:22px;}
.rp-result.on{display:block;}
.rp-rcard{background:#fff;border-radius:13px;border:2px solid var(--border);padding:18px;margin-bottom:14px;}
.rp-rcard.best{border-color:var(--gold);}
.rp-rhead{display:flex;align-items:center;gap:11px;margin-bottom:11px;}
.rp-rrank{font-size:20px;}
.rp-rname{font-weight:700;font-size:14px;}
.rp-rsub{font-size:10px;color:var(--muted);}
.rp-rwhy{font-size:12px;color:#555;line-height:1.8;margin-bottom:11px;}
.rp-rsave{display:inline-block;font-size:10px;font-weight:700;padding:3px 11px;border-radius:18px;background:#e8f5e9;color:var(--green);margin-bottom:11px;}
.rp-bestbadge{display:inline-block;font-size:9px;font-weight:700;padding:2px 8px;border-radius:18px;background:var(--gold);color:#fff;margin-left:7px;}
.rp-rbtn{padding:6px 13px;color:#fff;border:none;border-radius:7px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:10px;font-weight:700;text-decoration:none;display:inline-flex;align-items:center;gap:4px;}
</style>

<!-- NAV -->
<div class="rp-nav">
  <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
  <div class="spacer"></div>
  <button class="nav-btn" onclick="goHome()">← หน้าแรก</button>
</div>

<!-- HERO -->
<div class="rp-hero">
  <h1>🚄 RAIL PASS <span>GUIDE</span></h1>
  <p>เปรียบเทียบ Pass ทุกประเภท · ดูเส้นทาง · ติ๊กเมืองเพื่อรับคำแนะนำ</p>
</div>

<!-- TAB BAR -->
<div class="rp-tabbar">
  <button class="rp-tab on" onclick="rpTab('passes',this)">🎫 เลือก Pass</button>
  <button class="rp-tab" onclick="rpTab('rec',this)">🎯 แนะนำ Pass</button>
  <button class="rp-tab" onclick="rpTab('tips',this)">💡 เทคนิค</button>
</div>

<!-- PANE: PASSES -->
<div id="rpp-passes" class="rp-pane on">
  <h2 class="rp-stitle">🎫 Pass ทั้งหมด — กดเพื่อดูรายละเอียด</h2>
  <div class="rp-tip"><strong>⚠️ อัปเดต 2025:</strong> JR Pass National ปรับขึ้น 69% (7 วัน = ¥50,000) Regional Pass มักคุ้มกว่าสำหรับทริปที่ไม่ข้ามหลายภูมิภาค — <strong>ควรคำนวณก่อนซื้อเสมอ</strong></div>
  <div class="rp-grid" id="rpPassGrid"></div>
</div>

<!-- PANE: RECOMMENDER -->
<div id="rpp-rec" class="rp-pane">
  <h2 class="rp-stitle">🎯 ติ๊กเมืองที่จะไป — รับคำแนะนำ Pass</h2>
  <div class="rp-rec-intro">เลือกเมืองทั้งหมดที่คุณวางแผนจะไปในทริปเดียวกัน แล้วกด "แนะนำ Pass" ระบบจะวิเคราะห์ว่าควรซื้อ Pass ไหนและทำไม</div>
  <div class="rp-cc-grid" id="rpCityGrid"></div>
  <button class="rp-recbtn" onclick="rpRecommend()">🎯 แนะนำ Pass ให้ฉัน</button>
  <div class="rp-result" id="rpResult"></div>
</div>

<!-- PANE: TIPS -->
<div id="rpp-tips" class="rp-pane">
  <h2 class="rp-stitle">💡 เทคนิค & ข้อควรรู้</h2>
  <div class="rp-tip"><strong>📌 กฎพื้นฐาน:</strong><br>
  • ซื้อ Pass ล่วงหน้าก่อนเข้าญี่ปุ่น — บาง Pass ซื้อในญี่ปุ่นไม่ได้<br>
  • ต้องเป็น "Temporary Visitor" ถือพาสปอร์ตไทยพร้อม<br>
  • กด Activate วันแรกที่สถานีรถไฟ ระบุวันเริ่มได้เอง<br>
  • JR West Pass ต้องซื้อก่อนเข้าญี่ปุ่นเท่านั้น (ตั้งแต่ ต.ค. 2023)</div>
  <div class="rp-tip"><strong>🚄 Shinkansen ที่ต้องรู้:</strong><br>
  • <strong>Nozomi / Mizuho</strong> — เร็วสุด แต่ JR Pass National ใช้ไม่ได้ฟรี ต้องจ่ายเพิ่ม<br>
  • <strong>Hikari / Kodama / Sakura</strong> — ใช้กับ JR Pass ได้ฟรี ช้ากว่า 30–60 นาที<br>
  • <strong>Hayabusa</strong> (Tokyo–Hokkaido) — ต้องจองที่นั่ง ฟรีกับ JR Pass National<br>
  • จองที่นั่งล่วงหน้าแนะนำมาก โดยเฉพาะ Golden Week และ Obon</div>
  <div class="rp-tip"><strong>💳 IC Card (Suica/Pasmo) ควรมีคู่กับ Pass เสมอ:</strong><br>
  • ใช้สำหรับรถไฟในเมือง subway บัส แท็กซี่ ร้านสะดวกซื้อ<br>
  • เติมเงินได้ที่ตู้อัตโนมัติทุกสถานี<br>
  • ผูกกับ Apple Pay / Google Pay ได้เลย ไม่ต้องถือบัตรจริง<br>
  • Pass ส่วนใหญ่ไม่รวม subway ในเมือง ต้องใช้ IC Card แทน</div>
  <div class="rp-tip"><strong>🔢 คำนวณก่อนซื้อ:</strong><br>
  • <a href="https://www.japan-guide.com/railpass/" target="_blank">japan-guide.com/railpass</a> — เปรียบเทียบค่าตั๋วรายเที่ยวกับ Pass<br>
  • <a href="https://www.jrpass.com/farecalculator" target="_blank">jrpass.com/farecalculator</a> — คำนวณราคาแต่ละเส้นทาง<br>
  • <strong>ตัวอย่าง:</strong> Tokyo→Kyoto ¥13,850 + Kyoto→Hiroshima ¥10,560 + Hiroshima→Osaka ¥9,800 = ¥34,210 ยังไม่คุ้ม JR Pass 7 วัน ¥50,000</div>
  <div class="rp-tip"><strong>📱 App แนะนำ:</strong><br>
  • <strong>Hyperdia</strong> — ค้นเส้นทางรถไฟทุกสาย อัปเดตตารางเวลาจริง<br>
  • <strong>Google Maps</strong> — เดินทางได้ แต่บางครั้ง route ไม่ optimize สำหรับ JR Pass<br>
  • <strong>JR東日本 App</strong> — จองที่นั่ง Shinkansen โดยตรง</div>
</div>

<!-- MODAL -->
<div class="rp-overlay" id="rpOverlay" onclick="rpCloseModal(event)">
  <div class="rp-modal" id="rpModal">
    <div class="rp-mhero" id="rpMHero">
      <button class="rp-mclose" onclick="rpCloseModalDirect()">✕</button>
      <h2 id="rpMTitle"></h2>
      <p id="rpMSub"></p>
    </div>
    <div class="rp-mbody" id="rpMBody"></div>
  </div>
</div>

</div><!-- end pgRail -->

<script>
// ════════════════════════════════
// RAIL PASS DATA
// ════════════════════════════════
const RP_PASSES=[
  {id:'national',icon:'🇯🇵',name:'JR Pass National',sub:'ทั่วประเทศ',color:'#c0392b',price:'7 วัน ¥50,000',
   covers:['ทุกภูมิภาค','ชินคันเซ็น','ฮอกไกโด','คิวชู'],
   desc:'ครอบคลุมชินคันเซ็นและ JR ทั่วประเทศ ซื้อก่อนเข้าญี่ปุ่น เหมาะทริปข้ามหลายภูมิภาค',
   prices:[{t:'7 วัน (ปกติ)',p:'¥50,000'},{t:'14 วัน',p:'¥80,000'},{t:'21 วัน',p:'¥100,000'},{t:'7 วัน (Green Car)',p:'¥70,000'}],
   valid:['Shinkansen Hikari, Kodama, Sakura, Hayabusa','JR Express & Local ทั่วประเทศ','Narita Express (N\'EX)','เรือ JR West ไป Miyajima'],
   notvalid:['Nozomi/Mizuho (ต้องจ่ายเพิ่ม)','Subway ในเมือง Tokyo/Osaka','รถไฟสายเอกชน'],
   map_img:'https://www.jrailpass.com/images/maps/rosen-ja.png',
   map_src:'jrailpass.com',map_src_url:'https://www.jrailpass.com/maps',
   schedule:'Tokyo → Osaka (Hikari) ~2h45m · Tokyo → Hiroshima ~4h · Tokyo → Fukuoka ~5h · Tokyo → Sapporo ~4h30m',
   schedule_url:'https://www.japan-guide.com/e/e2018.html',
   booking:'https://www.japanrailpass.net/en/purchase/',
   guide:'https://www.japan-guide.com/e/e2361.html',
   best:'ทริปข้ามหลายภูมิภาคในเวลาจำกัด Tokyo→Kyoto→Hiroshima→Fukuoka'},
  {id:'hokkaido',icon:'❄️',name:'JR Hokkaido Rail Pass',sub:'ฮอกไกโดทั้งเกาะ',color:'#2980b9',price:'5 วัน ¥22,000',
   covers:['ซัปโปโร','โอตารุ','ฟุราโน่','อาซาฮิกาวะ','ฮาโกดาเตะ'],
   desc:'ครอบคลุม JR Hokkaido ทุกเส้น ยกเว้น Hokkaido Shinkansen มีแบบ Flexible 4 วันใน 10 วัน',
   prices:[{t:'3 วัน',p:'¥16,000'},{t:'5 วัน',p:'¥22,000'},{t:'7 วัน',p:'¥27,000'},{t:'4 วัน Flexible',p:'¥22,000'}],
   valid:['JR Hokkaido ทุกสาย','รถบัส JR Hokkaido บางสาย'],
   notvalid:['Hokkaido Shinkansen (จ่ายเพิ่ม)','SL Fuyu-no-Shitsugen','รถไฟสายเอกชน'],
   map_img:'https://www.jrhokkaido.co.jp/global/img/railpass/pass01.jpg',
   map_src:'jrhokkaido.co.jp',map_src_url:'https://www.jrhokkaido.co.jp/global/english/ticket/railpass/',
   schedule:'Sapporo→Otaru 33 นาที · Sapporo→Asahikawa 1h25m · Sapporo→Hakodate 3h30m · Sapporo→Furano 2h',
   schedule_url:'https://www.jrhokkaido.co.jp/global/english/',
   booking:'https://www.jrhokkaido.co.jp/global/english/ticket/railpass/',
   guide:'https://www.japan-guide.com/e/e2357_hokkaido.html',
   best:'ทริปฮอกไกโดโดยเฉพาะ Snow Festival (ก.พ.) หรือลาเวนเดอร์ (ก.ค.)'},
  {id:'tokyo_wide',icon:'🗼',name:'JR Tokyo Wide Pass',sub:'โตเกียวและรอบๆ 3 วัน',color:'#27ae60',price:'3 วัน ¥15,000',
   covers:['โตเกียว','นิกโก้','ฮาโกเน่','ฟูจิ','คามาคูระ','นาริตะ'],
   desc:'3 วันราคาถูกมาก ครอบคลุม Tokyo Region ทั้งหมด รวม Narita Express',
   prices:[{t:'3 วัน (ปกติ)',p:'¥15,000'},{t:'3 วัน (เด็ก 6-11)',p:'¥7,500'}],
   valid:['JR East ใน Kanto','Narita Express (N\'EX)','Fuji Excursion ไป Kawaguchiko','Nikko Revaty Express'],
   notvalid:['Tokyo Metro / Toei Subway','รถไฟ Odakyu ไป Hakone','นอกเขต Kanto'],
   map_img:'https://www.jreast.co.jp/e/tokyowidepass/img/map_pc.png',
   map_src:'jreast.co.jp',map_src_url:'https://www.jreast.co.jp/e/tokyowidepass/',
   schedule:'Tokyo→Nikko (Revaty) 2h · Tokyo→Kawaguchiko 1h45m · Tokyo→Narita Airport 60 นาที',
   schedule_url:'https://www.jreast.co.jp/e/tokyowidepass/',
   booking:'https://www.jreast.co.jp/e/tokyowidepass/',
   guide:'https://www.japan-guide.com/e/e2357_kanto.html',
   best:'ทริปโตเกียว + day trip นิกโก้ ฟูจิ ฮาโกเน่'},
  {id:'hokuriku',icon:'🏘️',name:'Hokuriku Arch Pass',sub:'Tokyo ↔ Osaka ผ่านคานาซาวะ',color:'#8e44ad',price:'14 วัน ¥29,650',
   covers:['โตเกียว','นากาโน','คานาซาวะ','เกียวโต','โอซาก้า'],
   desc:'เส้นทางพิเศษผ่านภาคเหนือ Tokyo→Kanazawa→Kyoto/Osaka ราคาถูกกว่า JR National มาก',
   prices:[{t:'14 วัน',p:'¥29,650'},{t:'เด็ก 6-11',p:'¥14,820'}],
   valid:['Hokuriku Shinkansen Tokyo→Kanazawa','Limited Express Thunderbird Kanazawa→Osaka','JR East & JR West ในเขต'],
   notvalid:['Tokaido Shinkansen Tokyo→Osaka ตรง','รถไฟ Hida Express ไป Takayama','รถไฟสายเอกชน'],
   map_img:'https://www.jreast.co.jp/e/hokuriku-arch-pass/img/map_pc.png',
   map_src:'jreast.co.jp',map_src_url:'https://www.jreast.co.jp/e/hokuriku-arch-pass/',
   schedule:'Tokyo→Kanazawa (Kagayaki) 2h28m · Kanazawa→Kyoto (Thunderbird) 2h12m · Kanazawa→Osaka 2h30m',
   schedule_url:'https://www.jreast.co.jp/e/hokuriku-arch-pass/',
   booking:'https://www.jreast.co.jp/e/hokuriku-arch-pass/',
   guide:'https://www.japan-guide.com/e/e2357_hokuriku.html',
   best:'Tokyo + Kanazawa + Kyoto/Osaka ประหยัดกว่า JR National เกือบ ¥20,000'},
  {id:'kansai',icon:'⛩️',name:'JR Kansai Area Pass',sub:'เกียวโต โอซาก้า โกเบ นารา',color:'#e67e22',price:'1–4 วัน',
   covers:['เกียวโต','โอซาก้า','โกเบ','นารา','ฮิเมจิ','KIX'],
   desc:'ครอบคลุม JR Kansai Lines ไม่รวม Shinkansen เหมาะทริปอยู่แค่ Kansai ราคาถูกมาก',
   prices:[{t:'1 วัน',p:'¥2,400'},{t:'2 วัน',p:'¥4,600'},{t:'3 วัน',p:'¥5,600'},{t:'4 วัน',p:'¥7,200'}],
   valid:['JR Lines ใน Kansai ทั้งหมด','Haruka Express สนามบิน KIX'],
   notvalid:['Shinkansen (ไม่รวม)','Kintetsu, Hankyu, Hanshin','Subway Osaka/Kyoto'],
   map_img:'https://www.westjr.co.jp/global/en/ticket/pass/kansai/img/map.png',
   map_src:'westjr.co.jp',map_src_url:'https://www.westjr.co.jp/global/en/ticket/pass/kansai/',
   schedule:'Kyoto→Osaka 15 นาที · Osaka→Kobe 20 นาที · Osaka→Nara 50 นาที · Osaka→Himeji 55 นาที',
   schedule_url:'https://www.westjr.co.jp/global/en/ticket/pass/kansai/',
   booking:'https://www.westjr.co.jp/global/en/ticket/pass/kansai/',
   guide:'https://www.japan-guide.com/e/e2357_kansai.html',
   best:'ทริป Kansai เท่านั้น ไม่ได้ไป Hiroshima หรือ Tokyo'},
  {id:'kansai_hiro',icon:'🕊️',name:'JR Kansai-Hiroshima Pass',sub:'Kansai + ฮิโรชิม่า',color:'#c0392b',price:'5 วัน ¥17,000',
   covers:['เกียวโต','โอซาก้า','ฮิโรชิม่า','มิยาจิม่า','โอคายาม่า'],
   desc:'ครอบคลุม Kansai และ Hiroshima รวม Sanyo Shinkansen เหมาะ Golden Route ฝั่งตะวันตก',
   prices:[{t:'5 วัน',p:'¥17,000'},{t:'เด็ก 6-11',p:'¥8,500'}],
   valid:['Sanyo Shinkansen Osaka→Hiroshima','JR Lines ใน Kansai','เรือ JR West ไป Miyajima','Haruka KIX'],
   notvalid:['Nozomi/Mizuho (จ่ายเพิ่ม)','Kintetsu, Hankyu','Tokyo หรือ Kyushu'],
   map_img:'https://www.westjr.co.jp/global/en/ticket/pass/kansai_hiroshima/img/map.png',
   map_src:'westjr.co.jp',map_src_url:'https://www.westjr.co.jp/global/en/ticket/pass/kansai_hiroshima/',
   schedule:'Osaka→Hiroshima (Sakura) 1h30m · Hiroshima→Miyajima 40 นาที · Kyoto→Osaka 15 นาที',
   schedule_url:'https://www.westjr.co.jp/global/en/ticket/pass/kansai_hiroshima/',
   booking:'https://www.westjr.co.jp/global/en/ticket/pass/kansai_hiroshima/',
   guide:'https://www.japan-guide.com/e/e2357_sanyo.html',
   best:'Kyoto + Osaka + Hiroshima + Miyajima Classic Golden Route ฝั่งตะวันตก'},
  {id:'kyushu',icon:'🍜',name:'JR Kyushu Rail Pass',sub:'ทั่วเกาะคิวชู',color:'#e74c3c',price:'All Kyushu 3 วัน ¥16,000',
   covers:['ฟุกุโอกะ','นางาซากิ','คุมาโมโต้','เบปปุ','คาโกชิม่า'],
   desc:'ครอบคลุม JR Kyushu ทั้งหมด รวม Kyushu Shinkansen มีแบบ All / Northern Kyushu',
   prices:[{t:'All Kyushu 3 วัน',p:'¥16,000'},{t:'All Kyushu 5 วัน',p:'¥20,000'},{t:'Northern 3 วัน',p:'¥10,000'},{t:'Northern 5 วัน',p:'¥14,000'}],
   valid:['Kyushu Shinkansen ทุกสาย','JR Kyushu ทุกเส้น','Nishi-Kyushu Shinkansen (Nagasaki)'],
   notvalid:['รถไฟสายเอกชน Nishitetsu','Subway Fukuoka','นอกเกาะ Kyushu'],
   map_img:'https://www.jrkyushu.co.jp/english/railpass/img/map_all.png',
   map_src:'jrkyushu.co.jp',map_src_url:'https://www.jrkyushu.co.jp/english/railpass/',
   schedule:'Fukuoka→Kumamoto 32 นาที · Fukuoka→Kagoshima 1h17m · Fukuoka→Beppu 2h · Fukuoka→Nagasaki 1h20m',
   schedule_url:'https://www.jrkyushu.co.jp/english/',
   booking:'https://www.jrkyushu.co.jp/english/railpass/',
   guide:'https://www.japan-guide.com/e/e2357_kyushu.html',
   best:'ทริป Kyushu ตะลุยหลายเมือง Fukuoka + Nagasaki + Kumamoto + Beppu'},
  {id:'ic',icon:'💳',name:'IC Card (Suica / Pasmo)',sub:'บัตรเติมเงิน ใช้ได้ทุกที่',color:'#1abc9c',price:'เติมได้ตามต้องการ',
   covers:['ทุกเมืองใหญ่','Subway','รถบัส','ร้านค้า'],
   desc:'ไม่ใช่ Pass แต่สำคัญมาก ใช้แทนตั๋วในเมือง subway บัส แท็กซี่ ร้านสะดวกซื้อ ผูก Apple Pay ได้',
   prices:[{t:'ราคาบัตร (คืนได้)',p:'¥500'},{t:'เงินฝากขั้นต่ำ',p:'¥1,000'},{t:'เติมสูงสุด',p:'¥20,000'}],
   valid:['Subway และ JR ทุกสาย (จ่ายตามระยะ)','รถบัสในเมืองทั่วประเทศ','ร้าน 7-Eleven, Lawson, FamilyMart'],
   notvalid:['ไม่มีส่วนลด — จ่ายตามราคาจริง'],
   map_img:'https://www.jrailpass.com/images/maps/rosen-ja.png',
   map_src:'jrailpass.com',map_src_url:'https://www.jrailpass.com/maps',
   schedule:'ใช้ได้ทุกรถไฟที่มีเครื่องอ่านบัตร IC ทั่วประเทศ ค่าโดยสารคิดตามระยะทางอัตโนมัติ',
   schedule_url:'https://www.jreast.co.jp/e/pass/suica.html',
   booking:'https://www.jreast.co.jp/e/pass/suica.html',
   guide:'https://www.japan-guide.com/e/e2359.html',
   best:'ทุกทริป ควรมีติดตัวเสมอคู่กับ Pass ใดก็ตาม'},
];

const RP_CITIES=[
  {id:'sapporo',l:'Sapporo',s:'ฮอกไกโด',ps:['hokkaido','national']},
  {id:'otaru',l:'Otaru',s:'ฮอกไกโด',ps:['hokkaido','national']},
  {id:'furano',l:'Furano',s:'ฮอกไกโด',ps:['hokkaido','national']},
  {id:'sendai',l:'Sendai',s:'โทโฮกุ',ps:['national']},
  {id:'nikko',l:'Nikko',s:'โตเกียวรอบๆ',ps:['tokyo_wide','national']},
  {id:'tokyo',l:'Tokyo',s:'คันโต',ps:['tokyo_wide','hokuriku','national','ic']},
  {id:'kamakura',l:'Kamakura',s:'โตเกียวรอบๆ',ps:['tokyo_wide','national']},
  {id:'fuji',l:'Fuji/Kawaguchiko',s:'คันโต',ps:['tokyo_wide','national']},
  {id:'hakone',l:'Hakone',s:'คันโต',ps:['tokyo_wide','national']},
  {id:'kanazawa',l:'Kanazawa',s:'โฮคุริกุ',ps:['hokuriku','national']},
  {id:'takayama',l:'Takayama',s:'ชูบุ',ps:['national']},
  {id:'kyoto',l:'Kyoto',s:'คันไซ',ps:['kansai','kansai_hiro','hokuriku','national']},
  {id:'osaka',l:'Osaka',s:'คันไซ',ps:['kansai','kansai_hiro','hokuriku','national']},
  {id:'nara',l:'Nara',s:'คันไซ',ps:['kansai','kansai_hiro','national']},
  {id:'kobe',l:'Kobe',s:'คันไซ',ps:['kansai','kansai_hiro','national']},
  {id:'hiroshima',l:'Hiroshima',s:'ชูโกกุ',ps:['kansai_hiro','national']},
  {id:'miyajima',l:'Miyajima',s:'ชูโกกุ',ps:['kansai_hiro','national']},
  {id:'okayama',l:'Okayama',s:'ชูโกกุ',ps:['kansai_hiro','national']},
  {id:'fukuoka',l:'Fukuoka',s:'คิวชู',ps:['kyushu','national']},
  {id:'nagasaki',l:'Nagasaki',s:'คิวชู',ps:['kyushu','national']},
  {id:'kumamoto',l:'Kumamoto',s:'คิวชู',ps:['kyushu','national']},
  {id:'beppu',l:'Beppu',s:'คิวชู',ps:['kyushu','national']},
];

const RP_META={
  national:{n:'JR Pass National 7 วัน',p:50000},
  hokkaido:{n:'JR Hokkaido Pass 5 วัน',p:22000},
  tokyo_wide:{n:'Tokyo Wide Pass 3 วัน',p:15000},
  hokuriku:{n:'Hokuriku Arch Pass',p:29650},
  kansai:{n:'Kansai Area Pass 4 วัน',p:7200},
  kansai_hiro:{n:'Kansai-Hiroshima Pass',p:17000},
  kyushu:{n:'JR Kyushu Pass 3 วัน',p:16000},
  ic:{n:'IC Card (Suica)',p:2000},
};

const RP_REASONS={
  national:'ครอบคลุมทั่วประเทศ เดินทางด้วยชินคันเซ็นได้ทุกเส้น คุ้มถ้าไปหลายภูมิภาค',
  hokkaido:'เฉพาะฮอกไกโด ราคาถูกกว่า JR National มาก ครอบคลุมทุกเส้นทางในเกาะ',
  tokyo_wide:'ราคาถูกที่สุดสำหรับ Tokyo Region ครอบคลุม day trip ยอดนิยมทั้งหมด',
  hokuriku:'เส้นทาง Tokyo→Kanazawa→Osaka ราคาดีมาก ประหยัดกว่า JR National เกือบ ¥20,000',
  kansai:'ราคาถูกที่สุดสำหรับทริปที่อยู่แค่ Kansai',
  kansai_hiro:'ครอบคลุม Classic Golden Route ฝั่งตะวันตก Kyoto+Osaka+Hiroshima+Miyajima',
  kyushu:'ครอบคลุม Kyushu ทั้งเกาะ รวม Shinkansen ราคาถูกกว่า JR National มาก',
  ic:'ควรมีติดตัวเสมอสำหรับเดินทางในเมือง subway บัส และร้านค้า',
};

// ── BUILD PASS CARDS ──
function buildPassCards(){
  const g=document.getElementById('rpPassGrid');
  if(!g) return;
  g.innerHTML=RP_PASSES.map(p=>`
    <div class="rp-card" style="--rpc:${p.color}" onclick="rpOpenModal('${p.id}')">
      <div class="rp-card-head">
        <span class="rp-icon">${p.icon}</span>
        <div><div class="rp-title">${p.name}</div><div class="rp-sub">${p.sub}</div></div>
      </div>
      <div class="rp-badge" style="background:${p.color}">${p.price}</div>
      <div class="rp-ctags">${p.covers.slice(0,5).map(c=>`<span class="rp-ctag">${c}</span>`).join('')}</div>
      <div class="rp-desc">${p.desc}</div>
      <div class="rp-cta">
        <button class="rp-detail" style="color:${p.color}">ดูรายละเอียด →</button>
        <span style="color:var(--muted)">🔍</span>
      </div>
    </div>`).join('');
}

// ── OPEN MODAL ──
function rpOpenModal(id){
  const p=RP_PASSES.find(x=>x.id===id);
  if(!p) return;
  document.getElementById('rpMHero').style.background=`linear-gradient(135deg,${p.color},${p.color}99)`;
  document.getElementById('rpMTitle').textContent=p.name;
  document.getElementById('rpMSub').textContent=p.sub+' — '+p.price;
  document.getElementById('rpMBody').innerHTML=`
    <div class="rp-mapwrap">
      <h3>🗺️ แผนที่เส้นทางที่ครอบคลุม</h3>
      <img class="rp-mapimg" src="${p.map_img}" alt="${p.name}"
        onerror="this.style.display='none';document.getElementById('rpfb-${p.id}').style.display='flex'"/>
      <div id="rpfb-${p.id}" class="rp-mapfb">
        <div style="font-size:28px">🗺️</div>
        <div style="font-size:11px;color:var(--muted);text-align:center">โหลดแผนที่ไม่ได้<br>กดลิงก์ด้านล่างเพื่อดูที่เว็บทางการ</div>
        <a href="${p.map_src_url}" target="_blank" style="font-size:11px;color:var(--blue)">ดูแผนที่ที่ ${p.map_src} →</a>
      </div>
      <div class="rp-mapsrc">แผนที่จาก: <a href="${p.map_src_url}" target="_blank">${p.map_src}</a></div>
    </div>
    <div class="rp-msecs">
      <div class="rp-msec">
        <h3>💴 ราคา</h3>
        <table class="rp-ptable">
          <thead><tr><th>ประเภท</th><th>ราคา</th></tr></thead>
          <tbody>${p.prices.map(r=>`<tr><td>${r.t}</td><td><strong>${r.p}</strong></td></tr>`).join('')}</tbody>
        </table>
      </div>
      <div class="rp-msec">
        <h3>✅ ใช้ได้กับ</h3>
        <ul class="rp-ilist">${p.valid.map(v=>`<li>${v}</li>`).join('')}</ul>
        <h3 style="margin-top:11px">❌ ใช้ไม่ได้</h3>
        <ul class="rp-ilist">${p.notvalid.map(v=>`<li>${v}</li>`).join('')}</ul>
      </div>
    </div>
    <div class="rp-schref">
      <strong>🕐 ตารางเวลาหลัก:</strong><br>${p.schedule}<br><br>
      <strong>📖 ดูตารางเวลาทั้งหมด:</strong> <a href="${p.schedule_url}" target="_blank">${p.schedule_url}</a>
    </div>
    <div class="rp-schref" style="margin-top:11px;background:#f0f8f0;border-color:#a8d5a2">
      <strong>⭐ เหมาะสำหรับ:</strong> ${p.best}
    </div>
    <div class="rp-lgrid">
      <a class="rp-lbtn primary" href="${p.booking}" target="_blank">🎫 ซื้อ / จอง Pass</a>
      <a class="rp-lbtn secondary" href="${p.guide}" target="_blank">📖 Japan Guide</a>
      <a class="rp-lbtn ext" href="https://www.japan-guide.com/railpass/" target="_blank">🧮 คำนวณว่าคุ้มไหม</a>
      <a class="rp-lbtn ext" href="https://www.jrpass.com/farecalculator" target="_blank">💰 JR Fare Calc</a>
    </div>`;
  document.getElementById('rpOverlay').classList.add('on');
  document.body.style.overflow='hidden';
}
function rpCloseModal(e){if(e.target===document.getElementById('rpOverlay'))rpCloseModalDirect();}
function rpCloseModalDirect(){document.getElementById('rpOverlay').classList.remove('on');document.body.style.overflow='';}

// ── BUILD CITY CHECKLIST ──
function buildCityChecklist(){
  const g=document.getElementById('rpCityGrid');
  if(!g) return;
  g.innerHTML=RP_CITIES.map(c=>`
    <div class="rp-cc" id="rpcc-${c.id}" onclick="rpToggleCity('${c.id}')">
      <div class="rp-cbox" id="rpcb-${c.id}"></div>
      <div><div class="rp-clabel">${c.l}</div><div class="rp-csub">${c.s}</div></div>
    </div>`).join('');
}
function rpToggleCity(id){
  const el=document.getElementById('rpcc-'+id);
  const cb=document.getElementById('rpcb-'+id);
  el.classList.toggle('on');
  cb.textContent=el.classList.contains('on')?'✓':'';
}

// ── RECOMMEND ──
function rpRecommend(){
  const sel=RP_CITIES.filter(c=>document.getElementById('rpcc-'+c.id)?.classList.contains('on'));
  const res=document.getElementById('rpResult');
  if(!sel.length){
    res.innerHTML='<div class="rp-tip" style="color:var(--red)"><strong>⚠️ กรุณาเลือกอย่างน้อย 1 เมืองก่อนครับ!</strong></div>';
    res.classList.add('on'); return;
  }
  const score={};const cities={};
  sel.forEach(c=>c.ps.forEach(pid=>{
    score[pid]=(score[pid]||0)+1;
    if(!cities[pid])cities[pid]=[];cities[pid].push(c.l);
  }));
  let sorted=Object.entries(score)
    .map(([pid,sc])=>({pid,sc,meta:RP_META[pid]}))
    .filter(x=>x.meta).sort((a,b)=>b.sc-a.sc||a.meta.p-b.meta.p);
  if(!sorted.find(x=>x.pid==='ic')) sorted.push({pid:'ic',sc:sel.length,meta:RP_META['ic']});

  const regions=new Set(sel.map(c=>RP_CITIES.find(x=>x.id===c.id)?.s));
  let html=`<h2 class="rp-stitle">🎯 ผลการแนะนำ สำหรับ ${sel.length} เมือง</h2>`;
  if(regions.size>=4&&sel.length>=6){
    html+=`<div class="rp-tip" style="background:#fff0f0;border-color:#e0a0a0">
      <strong>⚠️ คุณเลือก ${sel.length} เมืองใน ${regions.size} ภูมิภาค</strong><br>
      พิจารณา <strong>JR Pass National 7 วัน (¥50,000)</strong> อาจคุ้มกว่า
      ลองคำนวณที่ <a href="https://www.japan-guide.com/railpass/" target="_blank">japan-guide.com/railpass</a>
    </div>`;
  }
  sorted.slice(0,4).forEach((item,i)=>{
    const p=RP_PASSES.find(x=>x.id===item.pid);
    if(!p)return;
    const cvCities=cities[item.pid]||[];
    const pct=Math.round(item.sc/sel.length*100);
    const isBest=i===0&&item.pid!=='ic';
    html+=`<div class="rp-rcard${isBest?' best':''}">
      <div class="rp-rhead">
        <span class="rp-rrank">${i===0&&item.pid!=='ic'?'🥇':i===1?'🥈':item.pid==='ic'?'💳':'🥉'}</span>
        <div>
          <div class="rp-rname">${p.name}${isBest?'<span class="rp-bestbadge">⭐ แนะนำ</span>':''}</div>
          <div class="rp-rsub">${p.price}</div>
        </div>
      </div>
      <span class="rp-rsave">ครอบคลุม ${cvCities.length} / ${sel.length} เมือง (${pct}%)</span>
      <div class="rp-rwhy">
        <strong>เมืองที่ครอบคลุม:</strong> ${cvCities.join(' · ')}<br>
        <strong>${item.pid==='ic'?'หมายเหตุ':'เหตุผล'}:</strong> ${RP_REASONS[item.pid]||'เหมาะสำหรับเส้นทางนี้'}
      </div>
      <div style="display:flex;gap:7px;flex-wrap:wrap">
        <button onclick="rpOpenModal('${p.id}')" style="background:${p.color}" class="rp-rbtn">ดูรายละเอียด →</button>
        <a href="${p.booking}" target="_blank" style="background:var(--ink)" class="rp-rbtn">🎫 ซื้อ Pass</a>
      </div>
    </div>`;
  });
  const allCovered=new Set(sorted.slice(0,3).flatMap(x=>cities[x.pid]||[]));
  const notCov=sel.filter(c=>!allCovered.has(c.l));
  if(notCov.length){
    html+=`<div class="rp-tip"><strong>📍 เมืองที่ต้องซื้อตั๋วแยก:</strong> ${notCov.map(c=>c.l).join(', ')}</div>`;
  }
  res.innerHTML=html;res.classList.add('on');
  res.scrollIntoView({behavior:'smooth',block:'start'});
}

// ── RAIL TAB SWITCHER ──
function rpTab(t,btn){
  document.querySelectorAll('.rp-pane').forEach(p=>p.classList.remove('on'));
  document.querySelectorAll('.rp-tab').forEach(b=>b.classList.remove('on'));
  document.getElementById('rpp-'+t).classList.add('on');
  btn.classList.add('on');
}
</script>

<!-- ══════════════════════════════════════════
     PAGE: LOCAL PUBLIC TRANSPORT
══════════════════════════════════════════ -->
<div id="pgTransport" class="page">

<style>
/* ── TRANSPORT PAGE ── */
.tp-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;}
.tp-nav .logo{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#fff;letter-spacing:4px;}
.tp-nav .logo span{color:var(--gold);}
.tp-hero{background:linear-gradient(135deg,#1a2e1a,#0d2b0d);padding:30px 20px;text-align:center;}
.tp-hero h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(24px,5vw,50px);color:#fff;letter-spacing:5px;}
.tp-hero h1 span{color:var(--gold);}
.tp-hero p{color:#aaa;font-size:12px;margin-top:5px;}

/* City selector */
.tp-city-wrap{max-width:1040px;margin:0 auto;padding:24px 18px 0;}
.tp-stitle{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--green);padding-left:11px;margin-bottom:16px;}
.tp-city-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(145px,1fr));gap:10px;margin-bottom:28px;}
.tp-city-btn{background:#fff;border:1.5px solid var(--border);border-radius:11px;padding:12px;cursor:pointer;text-align:center;transition:all .2s;font-family:'Noto Sans Thai',sans-serif;}
.tp-city-btn:hover,.tp-city-btn.on{background:var(--ink);color:#fff;border-color:var(--ink);transform:translateY(-2px);box-shadow:0 6px 16px rgba(0,0,0,.1);}
.tp-city-btn .tci{font-size:24px;display:block;margin-bottom:5px;}
.tp-city-btn .tcn{font-size:12px;font-weight:700;}
.tp-city-btn .tcs{font-size:10px;color:var(--muted);margin-top:2px;}
.tp-city-btn.on .tcs{color:rgba(255,255,255,.65);}

/* City detail panel */
.tp-detail{max-width:1040px;margin:0 auto;padding:0 18px 60px;display:none;}
.tp-detail.on{display:block;}
.tp-detail-hdr{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px;margin-bottom:20px;}
.tp-detail-hdr h2{font-family:'Bebas Neue',sans-serif;font-size:clamp(22px,4vw,36px);letter-spacing:3px;}
.tp-tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:20px;}
.tp-tab{padding:7px 16px;border-radius:18px;border:1.5px solid var(--border);background:#fff;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:12px;color:var(--muted);transition:all .2s;}
.tp-tab.on{background:var(--green);color:#fff;border-color:var(--green);}
.tp-pane{display:none;}
.tp-pane.on{display:block;}

/* Transport cards */
.tp-line-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:16px;}
.tp-line-card{background:#fff;border-radius:12px;border:1px solid var(--border);overflow:hidden;transition:box-shadow .2s;}
.tp-line-card:hover{box-shadow:0 6px 20px rgba(0,0,0,.1);}
.tp-line-head{padding:14px 16px 10px;display:flex;align-items:center;gap:10px;}
.tp-line-dot{width:14px;height:14px;border-radius:50%;flex-shrink:0;}
.tp-line-name{font-weight:700;font-size:14px;}
.tp-line-sub{font-size:10px;color:var(--muted);margin-top:1px;}
.tp-line-body{padding:0 16px 14px;}
.tp-line-info{font-size:11px;color:#555;line-height:1.8;margin-bottom:10px;}
.tp-stops{display:flex;flex-wrap:wrap;gap:4px;margin-bottom:10px;}
.tp-stop{font-size:9px;padding:2px 7px;border-radius:8px;background:#f0ebe0;color:var(--ink);}
.tp-stop.key{background:#e8f5e9;color:#1a7a1a;font-weight:700;}
.tp-line-links{display:flex;gap:7px;flex-wrap:wrap;}
.tp-lbtn{display:inline-flex;align-items:center;gap:5px;padding:5px 11px;border-radius:8px;font-size:10px;font-weight:700;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.tp-lbtn:hover{opacity:.85;}
.tp-lbtn.official{background:var(--blue);color:#fff;}
.tp-lbtn.map{background:var(--green);color:#fff;}
.tp-lbtn.info{background:#f0ebe0;color:var(--ink);}

/* Map image section */
.tp-map-section{margin-bottom:24px;}
.tp-map-section h3{font-size:13px;font-weight:700;margin-bottom:10px;display:flex;align-items:center;gap:6px;}
.tp-map-img{width:100%;max-height:340px;object-fit:contain;border-radius:10px;border:1px solid var(--border);background:#f5f0e8;display:block;}
.tp-map-fb{display:none;flex-direction:column;align-items:center;gap:8px;padding:24px;background:#f5f0e8;border-radius:10px;border:1px solid var(--border);text-align:center;}
.tp-map-fb p{font-size:11px;color:var(--muted);}
.tp-map-src{font-size:9px;color:var(--muted);margin-top:4px;text-align:right;}
.tp-map-src a{color:var(--blue);text-decoration:none;}

/* Tip box */
.tp-tip{background:#f0fff0;border:1px solid #a8d5a2;border-radius:10px;padding:13px;margin-bottom:16px;font-size:12px;line-height:1.9;color:#333;}
.tp-tip strong{color:#1a6a1a;}
.tp-tip a{color:var(--blue);text-decoration:none;}
.tp-empty{color:var(--muted);font-size:12px;padding:16px 0;}
</style>

<!-- NAV -->
<div class="tp-nav">
  <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
  <div class="spacer"></div>
  <button class="nav-btn" onclick="goHome()">← หน้าแรก</button>
</div>

<!-- HERO -->
<div class="tp-hero">
  <h1>🚌 LOCAL <span>TRANSPORT</span></h1>
  <p>รถไฟท้องถิ่น · Subway · รถบัส · แต่ละเมืองทั่วญี่ปุ่น</p>
</div>

<!-- CITY SELECTOR -->
<div class="tp-city-wrap">
  <h2 class="tp-stitle">📍 เลือกเมือง</h2>
  <div class="tp-city-grid" id="tpCityGrid"></div>
</div>

<!-- CITY DETAIL -->
<div class="tp-detail" id="tpDetail">
  <div class="tp-detail-hdr">
    <h2 id="tpDetailTitle"></h2>
    <button onclick="tpClearCity()" style="padding:6px 14px;background:var(--ink);color:#fff;border:none;border-radius:8px;cursor:pointer;font-family:'Noto Sans Thai',sans-serif;font-size:11px;">← เลือกเมืองใหม่</button>
  </div>
  <div class="tp-tabs" id="tpTabBar"></div>
  <div id="tpPanes"></div>
</div>

</div><!-- end pgTransport -->

<script>
// ════════════════════════════════════════
// LOCAL TRANSPORT DATA
// ════════════════════════════════════════
const TP_CITIES = [
  { id:'tokyo',    icon:'🗼', name:'Tokyo',    sub:'โตเกียว' },
  { id:'osaka',    icon:'🏯', name:'Osaka',    sub:'โอซาก้า' },
  { id:'kyoto',    icon:'⛩️', name:'Kyoto',    sub:'เกียวโต' },
  { id:'sapporo',  icon:'❄️', name:'Sapporo',  sub:'ซัปโปโร' },
  { id:'fukuoka',  icon:'🍜', name:'Fukuoka',  sub:'ฟุกุโอกะ' },
  { id:'hiroshima',icon:'🕊️', name:'Hiroshima',sub:'ฮิโรชิม่า' },
  { id:'nagoya',   icon:'🏭', name:'Nagoya',   sub:'นาโกย่า' },
  { id:'sendai',   icon:'🌿', name:'Sendai',   sub:'เซนได' },
  { id:'kanazawa', icon:'🏘️', name:'Kanazawa', sub:'คานาซาวะ' },
  { id:'nara',     icon:'🦌', name:'Nara',     sub:'นารา' },
  { id:'kobe',     icon:'⚓', name:'Kobe',     sub:'โกเบ' },
  { id:'kumamoto', icon:'🌋', name:'Kumamoto', sub:'คุมาโมโต้' },
];

const TP_DATA = {
  tokyo: {
    title: '🗼 Tokyo Local Transport',
    mapImg: 'https://www.jrailpass.com/images/maps/miniatura-tokyo.jpg',
    mapSrc: 'jrailpass.com',
    mapSrcUrl: 'https://www.jrailpass.com/maps',
    mapAlt: 'Tokyo Metro & JR Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> ซื้อ <strong>IC Card (Suica/Pasmo)</strong> แค่ใบเดียวใช้ได้ทุกสาย ทั้ง Tokyo Metro, Toei Subway, JR Yamanote Line, รถบัส และร้านสะดวกซื้อ | <strong>Tokyo Subway Ticket</strong> (¥800/วัน) คุ้มถ้าวันนั้นเดินทางเยอะ',
    train: [
      {
        name: 'JR Yamanote Line', nameJp: '山手線', color: '#9acd32',
        info: 'วงรอบเมืองที่สำคัญที่สุด เชื่อม Shibuya, Shinjuku, Akihabara, Ueno, Tokyo Station ครบทุกย่านสำคัญ ความถี่ทุก 2-4 นาที',
        keyStops: ['Tokyo','Shibuya','Shinjuku','Harajuku','Akihabara','Ueno','Ikebukuro'],
        allStops: ['Shinagawa','Osaki','Ebisu','Meguro'],
        fare: '¥160–230 / ครั้ง',
        official: 'https://www.jreast.co.jp/e/train/yamanoteline/',
        mapLink: 'https://maps.google.com/?q=JR+Yamanote+Line+Tokyo',
        guideLink: 'https://www.japan-guide.com/e/e2364.html',
      },
      {
        name: 'Tokyo Metro', nameJp: '東京メトロ', color: '#f39700',
        info: '9 สาย ครอบคลุมทุกพื้นที่ กลาง Tokyo เส้นสำคัญ: Ginza Line (สีส้ม), Hibiya Line (สีเทา), Marunouchi Line (สีแดง) ค่าโดยสาร ¥170–310',
        keyStops: ['Ginza','Roppongi','Asakusa','Shinjuku','Ikebukuro'],
        allStops: ['Shibuya','Otemachi','Kasumigaseki','Nihombashi'],
        fare: '¥170–310 / ครั้ง | Day Pass ¥600',
        official: 'https://www.tokyometro.jp/en/index.html',
        mapLink: 'https://www.tokyometro.jp/en/subwaymap/index.html',
        guideLink: 'https://www.japan-guide.com/e/e2017.html',
      },
      {
        name: 'Toei Subway', nameJp: '都営地下鉄', color: '#0079c2',
        info: '4 สาย (Asakusa, Mita, Shinjuku, Oedo) เสริมพื้นที่ที่ Tokyo Metro ไม่ครอบคลุม Oedo Line วนรอบ Roppongi-Tsukiji-Shiodome',
        keyStops: ['Shinjuku','Roppongi','Tsukiji','Asakusa','Kasai'],
        allStops: ['Shiodome','Ryogoku','Ueno-Okachimachi'],
        fare: '¥180–330 / ครั้ง | Day Pass ¥700',
        official: 'https://www.kotsu.metro.tokyo.lg.jp/eng/',
        mapLink: 'https://www.kotsu.metro.tokyo.lg.jp/eng/services/subway.html',
        guideLink: 'https://www.japan-guide.com/e/e2017.html',
      },
    ],
    bus: [
      {
        name: 'Toei Bus', nameJp: '都営バス', color: '#e8001d',
        info: 'รถบัสของ Tokyo Metropolitan ครอบคลุมพื้นที่ที่รถไฟไม่ถึง กดหยุดป้ายที่ต้องการ ค่าโดยสาร ¥210 ตายตัว บางสายรับเฉพาะ IC Card',
        keyStops: ['Tokyo Station','Akihabara','Kanda','Asakusa','Ueno'],
        allStops: ['Ryogoku','Kiyosumi','Koto'],
        fare: '¥210 ตายตัว (เขตในเมือง)',
        official: 'https://www.kotsu.metro.tokyo.lg.jp/eng/services/bus.html',
        mapLink: 'https://maps.google.com/?q=Toei+Bus+Tokyo',
        guideLink: 'https://www.japan-guide.com/e/e2017.html',
      },
      {
        name: 'Hato Bus (Tourist)', nameJp: 'はとバス', color: '#f8c800',
        info: 'รถบัสท่องเที่ยว Tokyo วนรอบสถานที่สำคัญ มีทัวร์ครึ่งวัน-เต็มวัน มีไกด์ภาษาอังกฤษ เหมาะสำหรับวันแรกที่เพิ่งถึง Tokyo',
        keyStops: ['Tokyo Station','Asakusa','Odaiba','Akihabara','Harajuku'],
        allStops: ['Shibuya','Roppongi','Ginza'],
        fare: '¥1,800–5,000 / ทัวร์',
        official: 'https://www.hatobus.com/en/',
        mapLink: 'https://maps.google.com/?q=Hato+Bus+Tokyo+Station',
        guideLink: 'https://www.hatobus.com/en/tour/',
      },
    ],
  },

  osaka: {
    title: '🏯 Osaka Local Transport',
    mapImg: 'https://www.jrailpass.com/images/maps/miniatura-osaka.jpg',
    mapSrc: 'jrailpass.com',
    mapSrcUrl: 'https://www.jrailpass.com/maps',
    mapAlt: 'Osaka Metro Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Osaka Amazing Pass</strong> (¥2,800/วัน) รวม Osaka Metro + Bus + เข้าสถานที่ท่องเที่ยวกว่า 40 แห่งฟรี คุ้มมากถ้าจะเที่ยวหลายที่ | Midosuji Line เป็นเส้นหลักที่สำคัญที่สุด เชื่อม Umeda–Namba–Tennoji',
    train: [
      {
        name: 'Osaka Metro (Midosuji Line)', nameJp: '御堂筋線', color: '#e60012',
        info: 'เส้นหลักที่ยุ่งที่สุดในโอซาก้า วิ่งแนวเหนือ-ใต้ผ่านทุกย่านสำคัญ Umeda (ช้อปปิ้ง) → Shinsaibashi → Namba (กิน) → Tennoji ความถี่ทุก 2–3 นาที',
        keyStops: ['Shin-Osaka','Umeda','Shinsaibashi','Namba','Tennoji','Nakamozu'],
        allStops: ['Nishimidosuji','Yodoyabashi','Hommachi'],
        fare: '¥190–360 / ครั้ง | Day Pass ¥800',
        official: 'https://subway.osakametro.co.jp/en/',
        mapLink: 'https://subway.osakametro.co.jp/en/guide/routemap.php',
        guideLink: 'https://www.japan-guide.com/e/e4001.html',
      },
      {
        name: 'Osaka Metro (ทุกสาย)', nameJp: '大阪メトロ', color: '#0079c2',
        info: '8 สาย ครอบคลุมทั้งเมือง สายสำคัญอื่น: Tanimachi Line (สีม่วง), Yotsubashi Line (สีน้ำเงิน), Chuo Line (เขียว) ใช้ IC Card หรือตั๋วรายเที่ยว',
        keyStops: ['Osaka Castle (Tanimachi)','Dotonbori (Namba)','Universal City (Chuo)','Fukushima'],
        allStops: ['Tsuruhashi','Sakaisuji Hommachi','Kyobashi'],
        fare: '¥190–360 / ครั้ง',
        official: 'https://subway.osakametro.co.jp/en/',
        mapLink: 'https://subway.osakametro.co.jp/en/guide/routemap.php',
        guideLink: 'https://www.japan-guide.com/e/e4001.html',
      },
      {
        name: 'Hankyu Railway', nameJp: '阪急電鉄', color: '#8b4513',
        info: 'รถไฟเอกชนเชื่อม Osaka (Umeda) ↔ Kyoto ↔ Kobe ถูกกว่า JR และสวยงาม สาย Kyoto Line: Umeda → Katsura → Kyoto (Kawaramachi) ใช้ IC Card ได้',
        keyStops: ['Osaka-Umeda','Juso','Kyoto-Kawaramachi','Kobe-Sannomiya'],
        allStops: ['Awaji','Takatsuki','Ibaraki'],
        fare: 'Osaka–Kyoto ¥430 | Osaka–Kobe ¥330',
        official: 'https://www.hankyu.co.jp/global/en/',
        mapLink: 'https://maps.google.com/?q=Hankyu+Railway+Osaka+Umeda',
        guideLink: 'https://www.japan-guide.com/e/e4001.html',
      },
    ],
    bus: [
      {
        name: 'Osaka Metro Bus', nameJp: '大阪メトロバス', color: '#0079c2',
        info: 'รถบัสของ Osaka Metro ครอบคลุมพื้นที่ที่ subway ไม่ถึง เช่น Namba → Dotonbori → Shinsaibashi ค่าโดยสาร ¥210 ตายตัว ใช้ IC Card ได้',
        keyStops: ['Namba','Shinsaibashi','Tennoji','Umeda','Dotonbori'],
        allStops: ['Abeno','Tsuruhashi','Kyobashi'],
        fare: '¥210 ตายตัว',
        official: 'https://bus.osakametro.co.jp/en/',
        mapLink: 'https://bus.osakametro.co.jp/en/guide/routemap.php',
        guideLink: 'https://www.japan-guide.com/e/e4001.html',
      },
    ],
  },

  kyoto: {
    title: '⛩️ Kyoto Local Transport',
    mapImg: 'https://www.jrailpass.com/images/maps/map_kyoto_metro.jpg',
    mapSrc: 'jrailpass.com',
    mapSrcUrl: 'https://www.jrailpass.com/maps',
    mapAlt: 'Kyoto Subway & Bus Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Subway & Bus 1-Day Pass</strong> (¥1,100/วัน) คุ้มที่สุดสำหรับ Kyoto ใช้ได้ทั้ง Kyoto Municipal Subway และ Kyoto City Bus ทั้งหมด | วัดส่วนใหญ่เข้าถึงได้ด้วยรถบัสสาย 100/101/102/110',
    train: [
      {
        name: 'Kyoto Municipal Subway (Karasuma Line)', nameJp: '烏丸線', color: '#00a73c',
        info: 'สายหลัก วิ่งแนวเหนือ-ใต้ผ่านใจกลางเมือง Kyoto Station → Karasuma Oike → Marutamachi → Kitaoji ต่อ Kintetsu Line ไป Nara ได้ที่ Kyoto Station',
        keyStops: ['Kyoto Station','Gojo','Shijo','Oike','Marutamachi','Kitaoji','Kokusaikaikan'],
        allStops: ['Kuramaguchi','Imadegawa','Matsugasaki'],
        fare: '¥220–360 / ครั้ง | Day Pass ¥600',
        official: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/',
        mapLink: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/comm/routemap.html',
        guideLink: 'https://www.japan-guide.com/e/e3951.html',
      },
      {
        name: 'Kyoto Municipal Subway (Tozai Line)', nameJp: '東西線', color: '#e8000b',
        info: 'สายแนวตะวันออก-ตะวันตก เชื่อม Nijo Castle, Fushimi, Daigo ต่อ Keihan Line ที่ Misasagi และ Keihan-Sanjo เหมาะสำหรับไปย่านฝั่งตะวันออก',
        keyStops: ['Nijo Castle','Karasuma-Oike','Sanjo-Keihan','Higashiyama','Misasagi','Daigo'],
        allStops: ['Ono','Rokujizo'],
        fare: '¥220–360 / ครั้ง',
        official: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/',
        mapLink: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/comm/routemap.html',
        guideLink: 'https://www.japan-guide.com/e/e3951.html',
      },
    ],
    bus: [
      {
        name: 'Kyoto City Bus (สาย 100/101/102)', nameJp: '京都市バス', color: '#c8420e',
        info: 'รถบัสหลักสำหรับนักท่องเที่ยว <strong>สาย 100</strong>: Kyoto Station → Sanjusangendo → Kiyomizudera → Gion → Heian Shrine | <strong>สาย 101</strong>: Kyoto Station → Nijo Castle → Kitano Tenmangu → Kinkakuji ค่าโดยสาร ¥230/ครั้ง',
        keyStops: ['Kyoto Station','Kinkakuji','Ryoanji','Gion','Kiyomizudera','Fushimi Inari'],
        allStops: ['Nijo Castle','Nishiki Market','Arashiyama'],
        fare: '¥230 / ครั้ง | 1-Day Pass ¥700',
        official: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/',
        mapLink: 'https://www2.city.kyoto.lg.jp/kotsu/webguide/en/comm/routemap.html',
        guideLink: 'https://www.insidekyoto.com/kyoto-buses',
      },
      {
        name: 'Kyoto Bus', nameJp: '京都バス', color: '#0068b7',
        info: 'รถบัสสายเอกชนเสริม Kyoto City Bus ครอบคลุม Arashiyama, Kurama, Kibune, Ohara พื้นที่ชานเมืองที่ City Bus ไม่ถึง',
        keyStops: ['Arashiyama','Kurama','Kibune','Ohara','Demachiyanagi'],
        allStops: ['Kifune-guchi','Kibuneguchi'],
        fare: '¥270–500 ขึ้นกับระยะทาง',
        official: 'https://www.kyotobus.jp/route/routemap.html',
        mapLink: 'https://maps.google.com/?q=Kyoto+Bus+Arashiyama',
        guideLink: 'https://www.japan-guide.com/e/e3951.html',
      },
    ],
  },

  sapporo: {
    title: '❄️ Sapporo Local Transport',
    mapImg: 'https://www.city.sapporo.jp/st/english/img/subway_map_en.jpg',
    mapSrc: 'city.sapporo.jp',
    mapSrcUrl: 'https://www.city.sapporo.jp/st/english/',
    mapAlt: 'Sapporo Subway Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Donichika Ticket</strong> (¥520/วัน — ใช้ได้เสาร์-อาทิตย์-วันหยุด) หรือ <strong>1-Day Pass</strong> (¥830/วัน) คุ้มถ้าขึ้น subway มากกว่า 3 ครั้ง | ย่านใจกลางเมืองเดินได้ แต่ฤดูหนาวแนะนำ subway มากกว่า',
    train: [
      {
        name: 'Sapporo Municipal Subway (Namboku Line)', nameJp: '南北線', color: '#009b44',
        info: 'สายเหนือ-ใต้หลักของซัปโปโร เชื่อม Odori (ใจกลาง) → Susukino (ย่านบันเทิง) → Nakajimakouen → Makomanai เป็น subway สายเดียวที่วิ่งบนยางลม',
        keyStops: ['Kita-Sanjuyon-Jo','Kita-Juyon-Jo','Sapporo','Odori','Susukino','Nakajima-Koen','Makomanai'],
        allStops: ['Hiragishi','Minami-Hiragishi'],
        fare: '¥210–380 / ครั้ง',
        official: 'https://www.city.sapporo.jp/st/english/',
        mapLink: 'https://www.city.sapporo.jp/st/english/subway/index.html',
        guideLink: 'https://www.japan-guide.com/e/e5300.html',
      },
      {
        name: 'Sapporo Municipal Subway (Tozai Line)', nameJp: '東西線', color: '#f5a623',
        info: 'สายตะวันออก-ตะวันตก เชื่อม Shin-Sapporo (ฝั่งตะวัน ออก) → Odori → Maruyama → Miyanosawa ผ่าน Maruyama Zoo ที่ Maruyama-Koen',
        keyStops: ['Shin-Sapporo','Higashi-Sapporo','Odori','Nishi-11-Chome','Maruyama-Koen','Miyanosawa'],
        allStops: ['Nishi-Jugo-Chome','Nishi-Juhachi-Chome'],
        fare: '¥210–380 / ครั้ง',
        official: 'https://www.city.sapporo.jp/st/english/',
        mapLink: 'https://www.city.sapporo.jp/st/english/subway/index.html',
        guideLink: 'https://www.japan-guide.com/e/e5300.html',
      },
      {
        name: 'Sapporo Streetcar (Tram)', nameJp: '札幌市電', color: '#e9546b',
        info: 'รถรางวงรอบ ย่านใต้ของ Sapporo เชื่อม Susukino → Higashi-Honganji → Nishi-Juhachi-Jo ค่าโดยสาร ¥200 ตายตัว ใช้ IC Card ได้',
        keyStops: ['Susukino','Higashi-Honganji','Tanuki-Koji','Nishi-Juhachi-Jo'],
        allStops: ['Nishi-Juroku-Jo','Haiden-Mae'],
        fare: '¥200 ตายตัว',
        official: 'https://www.city.sapporo.jp/st/english/streetcar/',
        mapLink: 'https://maps.google.com/?q=Sapporo+Streetcar+Tram',
        guideLink: 'https://www.japan-guide.com/e/e5300.html',
      },
    ],
    bus: [
      {
        name: 'Jotetsu Bus', nameJp: 'じょうてつバス', color: '#009944',
        info: 'รถบัสหลักของ Sapporo ครอบคลุมชานเมืองและพื้นที่ที่ subway ไม่ถึง รวมถึงบัสไป Jozankei Onsen (¥600 จาก Makomanai Station)',
        keyStops: ['Sapporo Station','Odori','Susukino','Jozankei Onsen','Fushimi'],
        allStops: ['Makomanai','Minami-Sapporo'],
        fare: '¥220–600 ขึ้นกับระยะ',
        official: 'https://www.jotetsu.co.jp/bus/',
        mapLink: 'https://maps.google.com/?q=Jotetsu+Bus+Sapporo',
        guideLink: 'https://www.japan-guide.com/e/e5300.html',
      },
    ],
  },

  fukuoka: {
    title: '🍜 Fukuoka Local Transport',
    mapImg: 'https://subway.city.fukuoka.lg.jp/static/img/rosen_map/subway_map_en.png',
    mapSrc: 'subway.city.fukuoka.lg.jp',
    mapSrcUrl: 'https://subway.city.fukuoka.lg.jp/en/',
    mapAlt: 'Fukuoka City Subway Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Fukuoka City Subway 1-Day Pass</strong> (¥660/วัน) คุ้มถ้าขึ้นมากกว่า 3 ครั้ง | Hakata Station และ Tenjin เป็น Hub หลัก ย่าน Nakasu ใกล้ Nakasu-Kawabata Station',
    train: [
      {
        name: 'Fukuoka City Subway (Kuko Line)', nameJp: '空港線', color: '#e60012',
        info: 'สายหลักที่สำคัญที่สุด เชื่อมสนามบิน Fukuoka → Hakata Station → Tenjin → Meinohama ระยะเวลาจากสนามบิน-Hakata แค่ 5 นาที ถูกและรวดเร็วมาก',
        keyStops: ['Fukuoka Airport','Hakata','Nakasu-Kawabata','Tenjin','Muromi','Meinohama'],
        allStops: ['Ohori-Koen','Nishijin','Kawakami'],
        fare: '¥210–360 / ครั้ง | Airport–Hakata ¥260',
        official: 'https://subway.city.fukuoka.lg.jp/en/',
        mapLink: 'https://subway.city.fukuoka.lg.jp/en/route/',
        guideLink: 'https://www.japan-guide.com/e/e4800.html',
      },
      {
        name: 'Nishitetsu (Nishitetsudo)', nameJp: '西鉄電車', color: '#f7931e',
        info: 'รถไฟเอกชน เชื่อม Tenjin → Dazaifu (ศาลเจ้า) → Omuta มีสาย Dazaifu Line พิเศษตกแต่งสวย (¥410 จาก Tenjin) ใช้ IC Card Nimoca ได้',
        keyStops: ['Fukuoka (Tenjin)','Futsukaichi','Dazaifu','Kurume','Omuta'],
        allStops: ['Nishitetsu-Nitta','Ogori'],
        fare: 'Tenjin–Dazaifu ¥410',
        official: 'https://www.nishitetsu.jp/en/train/',
        mapLink: 'https://maps.google.com/?q=Nishitetsu+Tenjin+Station',
        guideLink: 'https://www.japan-guide.com/e/e4800.html',
      },
    ],
    bus: [
      {
        name: 'Nishitetsu Bus', nameJp: '西鉄バス', color: '#f7931e',
        info: 'รถบัสที่ใหญ่ที่สุดในฟุกุโอกะ ครอบคลุมทุกย่าน Tenjin Bus Center เป็นจุดศูนย์กลาง บัสยาตาย Nakasu จะใช้บัสสาย 100 จาก Hakata Station',
        keyStops: ['Tenjin Bus Center','Hakata Station','Nakasu','Ohori Park','Momochihama'],
        allStops: ['Kashii','Uminonakamichi'],
        fare: '¥100–230 / ครั้ง',
        official: 'https://www.nishitetsu.jp/en/bus/',
        mapLink: 'https://maps.google.com/?q=Nishitetsu+Bus+Tenjin+Fukuoka',
        guideLink: 'https://www.japan-guide.com/e/e4800.html',
      },
    ],
  },

  hiroshima: {
    title: '🕊️ Hiroshima Local Transport',
    mapImg: 'https://www.hiroden.co.jp/en/tram/img/rosen_en.jpg',
    mapSrc: 'hiroden.co.jp',
    mapSrcUrl: 'https://www.hiroden.co.jp/en/',
    mapAlt: 'Hiroshima Tram & Bus Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Hiroshima 1-Day Pass</strong> (¥700/วัน) ใช้ได้กับรถรางทุกสายและเรือไป Miyajima คุ้มมากถ้าไปมิยาจิม่าด้วย | รถรางคือการเดินทางหลักในฮิโรชิม่า เชื่อม Peace Park ทุกจุด',
    train: [
      {
        name: 'Hiroshima Electric Railway (Tram)', nameJp: '広島電鉄', color: '#e60012',
        info: 'รถรางเครือข่ายใหญ่ที่สุดในญี่ปุ่น 8 สาย เชื่อม Hiroshima Station → Peace Memorial → Genbaku Dome → Hondori (ช้อปปิ้ง) ค่าโดยสาร ¥220 ตายตัวในเขตเมือง',
        keyStops: ['Hiroshima Station','Kamiya-cho','Peace Memorial','Genbaku Dome','Hondori','Ujina Port'],
        allStops: ['Nagarekawa','Shukkeien','Eba'],
        fare: '¥220 ตายตัว (เขตเมือง) | Day Pass ¥700',
        official: 'https://www.hiroden.co.jp/en/',
        mapLink: 'https://www.hiroden.co.jp/en/tram/rosen.html',
        guideLink: 'https://www.japan-guide.com/e/e3400.html',
      },
      {
        name: 'JR Hiroshima Local Lines', nameJp: 'JR広島', color: '#0068b7',
        info: 'รถไฟ JR สายท้องถิ่น เชื่อม Hiroshima Station → Miyajima-guchi (แล้วต่อเรือไป Miyajima) → Kure → Onomichi ใช้ JR Pass ได้',
        keyStops: ['Hiroshima','Nishi-Hiroshima','Miyajima-guchi','Kure','Onomichi'],
        allStops: ['Inokuchi','Itsukaichi'],
        fare: 'Hiroshima–Miyajima-guchi ¥410 (ใช้ JR Pass ได้)',
        official: 'https://www.jr-odekake.net/railroad/hiroshima/',
        mapLink: 'https://maps.google.com/?q=JR+Hiroshima+Station',
        guideLink: 'https://www.japan-guide.com/e/e3400.html',
      },
    ],
    bus: [
      {
        name: 'Hiroshima Bus Center (広島バスセンター)', nameJp: '広島バスセンター', color: '#009944',
        info: 'ศูนย์กลางรถบัสใจกลาง Hiroshima บัสไป Miyoshi, Iwakuni, รอบจังหวัด รถบัส Loop ท่องเที่ยว (Meipuru-pu) วนรอบ Peace Park ทุก 20 นาที ค่าโดยสาร ¥200/ครั้ง',
        keyStops: ['Hiroshima Bus Center','Peace Memorial','Hiroshima Castle','Shukkei-en','Hiroshima Station'],
        allStops: ['Asa','Miyoshi','Iwakuni'],
        fare: '¥200 / ครั้ง (Loop Bus)',
        official: 'https://www.chugokubus.jp/',
        mapLink: 'https://maps.google.com/?q=Hiroshima+Bus+Center',
        guideLink: 'https://www.japan-guide.com/e/e3400.html',
      },
    ],
  },

  nagoya: {
    title: '🏭 Nagoya Local Transport',
    mapImg: 'https://www.kotsu.city.nagoya.jp/en/img/route_map_en.gif',
    mapSrc: 'kotsu.city.nagoya.jp',
    mapSrcUrl: 'https://www.kotsu.city.nagoya.jp/en/',
    mapAlt: 'Nagoya Municipal Subway Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Nagoya 1-Day Pass</strong> (¥760/วัน) ใช้ได้ subway และบัสทั้งหมด | Nagoya Station เป็น Hub หลัก ต่อรถไฟไปทุกทิศ | Meijo Line วนรอบเมืองเหมือน Yamanote ของ Tokyo',
    train: [
      {
        name: 'Nagoya Municipal Subway (Higashiyama Line)', nameJp: '東山線', color: '#ffcc00',
        info: 'สายที่ยุ่งที่สุดใน Nagoya วิ่งตะวันออก-ตะวันตก เชื่อม Nagoya Station → Sakae (ช้อปปิ้ง) → Higashiyama Zoo → Fujigaoka ผ่าน Oasis 21',
        keyStops: ['Nagoya','Fushimi','Sakae','Ikeshita','Higashiyama-Koen','Fujigaoka'],
        allStops: ['Kamimaezu','Chikusa'],
        fare: '¥210–350 / ครั้ง',
        official: 'https://www.kotsu.city.nagoya.jp/en/',
        mapLink: 'https://www.kotsu.city.nagoya.jp/en/subway/',
        guideLink: 'https://www.japan-guide.com/e/e2162.html',
      },
      {
        name: 'Nagoya Municipal Subway (Meijo Line)', nameJp: '名城線', color: '#9b59b6',
        info: 'สายวงกลม (วนรอบเมือง) เชื่อม Nagoya Castle, Kanayama, Port of Nagoya, Ozone เหมาะสำหรับท่องเที่ยวรอบเมือง',
        keyStops: ['Nagoya Castle','Shiyakusho','Sakae','Kanayama','Nagoya Port','Ozone'],
        allStops: ['Heian-Dori','Yagoto'],
        fare: '¥210–350 / ครั้ง',
        official: 'https://www.kotsu.city.nagoya.jp/en/',
        mapLink: 'https://www.kotsu.city.nagoya.jp/en/subway/',
        guideLink: 'https://www.japan-guide.com/e/e2162.html',
      },
    ],
    bus: [
      {
        name: 'Nagoya City Bus', nameJp: '名古屋市バス', color: '#e67e22',
        info: 'รถบัสเทศบาลครอบคลุมพื้นที่ที่ subway ไม่ถึง ใช้ร่วมกับ 1-Day Pass ได้ ค่าโดยสาร ¥210 ตายตัว ใช้ IC Manaca ได้',
        keyStops: ['Nagoya Station','Sakae','Kanayama','Ozone','Meijo Park'],
        allStops: ['Mizuho','Tempaku'],
        fare: '¥210 ตายตัว',
        official: 'https://www.kotsu.city.nagoya.jp/en/',
        mapLink: 'https://maps.google.com/?q=Nagoya+City+Bus',
        guideLink: 'https://www.japan-guide.com/e/e2162.html',
      },
    ],
  },

  sendai: {
    title: '🌿 Sendai Local Transport',
    mapImg: 'https://www.kotsu.city.sendai.jp/subway/img/rosen_map_en.gif',
    mapSrc: 'kotsu.city.sendai.jp',
    mapSrcUrl: 'https://www.kotsu.city.sendai.jp/english/',
    mapAlt: 'Sendai Subway Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Sendai City Subway 1-Day Pass</strong> (¥620/วัน) | Downtown Loop Bus (100円バス) วนรอบใจกลางเมืองแค่ ¥100 | Sendai เป็นเมืองเล็ก เดินได้ระหว่างย่านช้อปปิ้ง',
    train: [
      {
        name: 'Sendai City Subway (Namboku Line)', nameJp: '南北線', color: '#009944',
        info: 'สายเหนือ-ใต้หลัก เชื่อม Sendai Station → Ichibancho → Nanbodai สาย Tozai Line ใหม่เชื่อม Aoba-jo (ปราสาท) → Sendai Station → Arai',
        keyStops: ['Izumi-Chuo','Kita-Yobancho','Sendai','Gokokujinja','Nambodai'],
        allStops: ['Nagamachi','Taihakunishi'],
        fare: '¥210–360 / ครั้ง',
        official: 'https://www.kotsu.city.sendai.jp/english/',
        mapLink: 'https://www.kotsu.city.sendai.jp/english/subway/',
        guideLink: 'https://www.japan-guide.com/e/e5250.html',
      },
    ],
    bus: [
      {
        name: 'Sendai City Bus + Loop Bus 100', nameJp: 'るーぷる仙台', color: '#e60012',
        info: '<strong>Loop Bus "Loople Sendai"</strong> (¥260/ครั้ง หรือ ¥630/วัน) วนรอบสถานที่ท่องเที่ยวหลัก Sendai Castle → Zuihoden → Osaki Hachimangu → Sendai Station ความถี่ทุก 20-30 นาที',
        keyStops: ['Sendai Station','Sendai Castle','Zuihoden Mausoleum','Osaki Hachimangu','Otamaya-bashi'],
        allStops: ['Toubu-Municipal-Museum'],
        fare: '¥260 / ครั้ง | Day Pass ¥630',
        official: 'https://www.kotsu.city.sendai.jp/english/',
        mapLink: 'https://www.kotsu.city.sendai.jp/english/bus/',
        guideLink: 'https://www.japan-guide.com/e/e5250.html',
      },
    ],
  },

  kanazawa: {
    title: '🏘️ Kanazawa Local Transport',
    mapImg: 'https://www.hokutetsu.co.jp/bus/img/route_map_en.jpg',
    mapSrc: 'hokutetsu.co.jp',
    mapSrcUrl: 'https://www.hokutetsu.co.jp/bus/kanazawa/',
    mapAlt: 'Kanazawa Loop Bus Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> Kanazawa ไม่มี Subway! ใช้รถบัสเป็นหลัก | <strong>Loop Bus "Kenroku" & "Kanazawa Loop"</strong> (¥200/ครั้ง หรือ ¥500/วัน) วนรอบสถานที่ท่องเที่ยวทั้งหมด | เช่าจักรยานก็สะดวกมากสำหรับย่านเก่า',
    train: [
      {
        name: 'IR Ishikawa Railway', nameJp: 'IRいしかわ鉄道', color: '#0068b7',
        info: 'รถไฟเชื่อม Kanazawa → Tsubata → Mikawa ใช้แทน Hokuriku Shinkansen บางช่วง ใช้ JR Pass ได้บางส่วน เหมาะเดินทางออกนอกเมือง',
        keyStops: ['Kanazawa','Noto-Kashima','Tsubata','Mikawa'],
        allStops: ['Ono'],
        fare: '¥190–400 / ครั้ง',
        official: 'https://www.ishikawa-railway.jp/',
        mapLink: 'https://maps.google.com/?q=Kanazawa+Station',
        guideLink: 'https://www.japan-guide.com/e/e3700.html',
      },
    ],
    bus: [
      {
        name: 'Kanazawa Loop Bus (兼六ループ)', nameJp: '兼六ループ', color: '#009944',
        info: 'วนรอบสถานที่ท่องเที่ยวหลักทั้งหมด: Kanazawa Station → Kenroku-en → 21st Century Museum → Higashi Chaya → ย้อนกลับ ความถี่ทุก 15-20 นาที คุ้มมาก',
        keyStops: ['Kanazawa Station','Kenroku-en','21st Century Museum','Higashi Chaya','Kanazawa Castle'],
        allStops: ['Honda-machi','Hashiba-cho'],
        fare: '¥200 / ครั้ง | Day Pass ¥500',
        official: 'https://www.hokutetsu.co.jp/bus/kanazawa/',
        mapLink: 'https://maps.google.com/?q=Kenroku-en+Loop+Bus+Kanazawa',
        guideLink: 'https://www.japan-guide.com/e/e3700.html',
      },
    ],
  },

  nara: {
    title: '🦌 Nara Local Transport',
    mapImg: 'https://narashikanko.or.jp/wp-content/uploads/2023/03/nara_koutu_map_en.jpg',
    mapSrc: 'narashikanko.or.jp',
    mapSrcUrl: 'https://narashikanko.or.jp/en/',
    mapAlt: 'Nara City Bus & Train Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> Nara Park เดินจาก Kintetsu Nara Station ได้เลย (5 นาที) | ใช้บัสสาย 2/10 จาก JR Nara Station ไป Nara Park | <strong>Nara Kotsu Bus Pass</strong> (¥500/วัน) สำหรับย่านนอกเมือง เช่น Horyuji Temple',
    train: [
      {
        name: 'Kintetsu Nara Line', nameJp: '近鉄奈良線', color: '#fc0d1b',
        info: 'รถไฟที่เร็วและสะดวกที่สุดจาก Osaka/Kyoto มา Nara มาถึง Kintetsu Nara Station ซึ่งใกล้ Nara Park มากกว่า JR Nara Station แนะนำใช้สายนี้',
        keyStops: ['Osaka-Namba','Osaka-Uehonmachi','Gakuentoshi','Yamato-Saidaiji','Kintetsu-Nara'],
        allStops: ['Tsuruhashi','Fuse'],
        fare: 'Osaka–Nara ¥570 | Kyoto–Nara ¥760',
        official: 'https://www.kintetsu.co.jp/foreign/english/',
        mapLink: 'https://maps.google.com/?q=Kintetsu+Nara+Station',
        guideLink: 'https://www.japan-guide.com/e/e4103.html',
      },
      {
        name: 'JR Nara Line', nameJp: 'JR奈良線', color: '#0068b7',
        info: 'เชื่อม Kyoto → Nara ใช้ JR Pass ได้ สถานี JR Nara อยู่ห่างจาก Nara Park ประมาณ 1.5 กม. (เดินได้หรือนั่งบัส)',
        keyStops: ['Kyoto','Rokujizo','Nishikujo','Nara'],
        allStops: ['Kohata','Joyo'],
        fare: 'Kyoto–Nara ¥720 (ใช้ JR Pass ได้)',
        official: 'https://www.jr-odekake.net/',
        mapLink: 'https://maps.google.com/?q=JR+Nara+Station',
        guideLink: 'https://www.japan-guide.com/e/e4103.html',
      },
    ],
    bus: [
      {
        name: 'Nara Kotsu Bus', nameJp: '奈良交通バス', color: '#e67e22',
        info: 'รถบัสหลักของ Nara ครอบคลุมทั้งเมืองและนอกเมือง รวมถึง Horyuji Temple (สาย 97/98), Yoshino (สาย 169) บัสใน Nara Park ¥220/ครั้ง',
        keyStops: ['JR Nara','Kintetsu Nara','Nara Park','Todai-ji','Horyuji','Kasuga Taisha'],
        allStops: ['Yoshino','Horyu-ji','Ikaruga'],
        fare: '¥220–600 ขึ้นกับระยะ',
        official: 'https://www.narakotsu.co.jp/rosen/index.html',
        mapLink: 'https://maps.google.com/?q=Nara+Bus+Center',
        guideLink: 'https://www.japan-guide.com/e/e4103.html',
      },
    ],
  },

  kobe: {
    title: '⚓ Kobe Local Transport',
    mapImg: 'https://www.city.kobe.lg.jp/a56262/img/kotsu/subway_route_en.png',
    mapSrc: 'city.kobe.lg.jp',
    mapSrcUrl: 'https://www.city.kobe.lg.jp/a56262/english/transportation/',
    mapAlt: 'Kobe Subway & Port Liner Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Kobe 1-Day Pass</strong> (¥1,000/วัน) รวม Subway, Port Liner และ City Bus | Sannomiya Station คือ Hub หลักของ Kobe เชื่อมต่อ Hankyu, Hanshin, JR, Subway, Port Liner ครบในที่เดียว',
    train: [
      {
        name: 'Kobe Municipal Subway (Seishin-Yamate Line)', nameJp: '西神・山手線', color: '#e60012',
        info: 'สายหลัก เชื่อม Sannomiya → Shin-Kobe (Shinkansen) → Tanigami → Seishin-Chuo ผ่านใจกลางเมือง ใช้ IC Card ได้',
        keyStops: ['Sannomiya','Shin-Kobe','Myodani','Gakuentoshi','Seishin-Chuo'],
        allStops: ['Tanigami','Nagata'],
        fare: '¥210–360 / ครั้ง',
        official: 'https://www.city.kobe.lg.jp/a56262/english/transportation/',
        mapLink: 'https://maps.google.com/?q=Sannomiya+Station+Kobe+Subway',
        guideLink: 'https://www.japan-guide.com/e/e3500.html',
      },
      {
        name: 'Port Liner', nameJp: 'ポートライナー', color: '#0079c2',
        info: 'รถไฟอัตโนมัติไม่มีคนขับ เชื่อม Sannomiya → Kobe Airport → Kobe-Minatojima ค่าโดยสาร ¥270 จาก Sannomiya ถึงสนามบิน ใช้เวลา 18 นาที',
        keyStops: ['Sannomiya','Minatomachi','Kobe Medical Center','Kobe Airport'],
        allStops: ['Naka-Futo','Minatojima'],
        fare: 'Sannomiya–Airport ¥270',
        official: 'https://www.knt-liner.co.jp/en/',
        mapLink: 'https://maps.google.com/?q=Port+Liner+Kobe+Sannomiya',
        guideLink: 'https://www.japan-guide.com/e/e3500.html',
      },
    ],
    bus: [
      {
        name: 'Kobe City Bus', nameJp: '神戸市バス', color: '#009944',
        info: 'รถบัสเทศบาลครอบคลุมพื้นที่ที่ subway ไม่ถึง บัส Loop Tour (City Loop ¥260/ครั้ง) วนรอบ Kitano (บ้านฝรั่ง), Meriken Park, Harborland ทุก 30 นาที',
        keyStops: ['Sannomiya','Kitano (Ijinkan)','Meriken Park','Harborland','Nada Sake District'],
        allStops: ['Suma Beach','Nunobiki Herb Garden'],
        fare: '¥260 / ครั้ง (City Loop)',
        official: 'https://www.city.kobe.lg.jp/a56262/english/transportation/',
        mapLink: 'https://maps.google.com/?q=Kobe+City+Loop+Bus',
        guideLink: 'https://www.japan-guide.com/e/e3500.html',
      },
    ],
  },

  kumamoto: {
    title: '🌋 Kumamoto Local Transport',
    mapImg: 'https://www.kotsu-kumamoto.jp/img/routemap_en.jpg',
    mapSrc: 'kotsu-kumamoto.jp',
    mapSrcUrl: 'https://www.kotsu-kumamoto.jp/en/',
    mapAlt: 'Kumamoto Tram & Bus Route Map',
    tip: '<strong>💡 เคล็ดลับ:</strong> <strong>Kumamoto 1-Day Tram Pass</strong> (¥500/วัน) คุ้มมาก | รถราง (Tram) คือการเดินทางหลักในเมือง เชื่อม Kumamoto Station → Kumamoto Castle → Shiyakusho-mae | ไป Mt. Aso ใช้รถไฟ JR Hohi Line',
    train: [
      {
        name: 'Kumamoto City Tram', nameJp: '熊本市電', color: '#e60012',
        info: '2 สาย เชื่อมทั่วเมือง: สาย A (Kumamoto Station → Castle → Shin-Suizenji) และ สาย B (Kamikumamoto → Castle → Kumamoto Station) ค่าโดยสาร ¥170 ตายตัว',
        keyStops: ['Kumamoto Station','Kumamoto-jo-mae (Castle)','Shiyakusho-mae','Suizenji-Kouen'],
        allStops: ['Shin-Suizenji','Kamikumamoto'],
        fare: '¥170 ตายตัว | Day Pass ¥500',
        official: 'https://www.kotsu-kumamoto.jp/en/',
        mapLink: 'https://www.kotsu-kumamoto.jp/en/tram/',
        guideLink: 'https://www.japan-guide.com/e/e4700.html',
      },
      {
        name: 'JR Hohi Line (ไป Mt. Aso)', nameJp: 'JR豊肥本線', color: '#0068b7',
        info: 'รถไฟ JR เชื่อม Kumamoto → Aso → Oita/Beppu ใช้ JR Pass ได้ เส้นทางสวยงามผ่านหุบเขาและทุ่งหญ้า Limited Express Aso Boy วิ่งบางวัน',
        keyStops: ['Kumamoto','Higooozu','Tateno','Aso','Miyaji','Bungo-Taketa','Oita'],
        allStops: ['Higo-Daiichi','Bungo-Ogi'],
        fare: 'Kumamoto–Aso ¥1,510 (ใช้ JR Pass ได้)',
        official: 'https://www.jrkyushu.co.jp/english/',
        mapLink: 'https://maps.google.com/?q=JR+Aso+Station',
        guideLink: 'https://www.japan-guide.com/e/e4703.html',
      },
    ],
    bus: [
      {
        name: 'Sanko Bus (ไป Mt. Aso)', nameJp: '産交バス', color: '#009944',
        info: 'รถบัสไป Mt. Aso Volcano จาก Kumamoto Station ตรงถึงบริเวณปล่องภูเขาไฟ ไม่ต้องเปลี่ยนรถไฟ มีรอบเช้า-บ่าย ใช้เวลา ~2 ชั่วโมง',
        keyStops: ['Kumamoto Station','Kumamoto Airport','Aso Station','Aso Volcano (Nakadake)'],
        allStops: ['Higo-Nishihara','Mifune'],
        fare: 'Kumamoto–Aso ¥1,500 (รถบัส)',
        official: 'https://www.sankobus.jp/',
        mapLink: 'https://maps.google.com/?q=Kumamoto+Bus+Center',
        guideLink: 'https://www.japan-guide.com/e/e4700.html',
      },
    ],
  },
};

// ── BUILD CITY BUTTONS ──
function buildTpCities() {
  const g = document.getElementById('tpCityGrid');
  if (!g) return;
  g.innerHTML = TP_CITIES.map(c => `
    <div class="tp-city-btn" id="tpcb-${c.id}" onclick="tpSelectCity('${c.id}')">
      <span class="tci">${c.icon}</span>
      <div class="tcn">${c.name}</div>
      <div class="tcs">${c.sub}</div>
    </div>`).join('');
}

// ── SELECT CITY ──
function tpSelectCity(id) {
  const data = TP_DATA[id];
  if (!data) return;

  // Highlight selected button
  document.querySelectorAll('.tp-city-btn').forEach(b => b.classList.remove('on'));
  document.getElementById('tpcb-' + id)?.classList.add('on');

  // Set title
  document.getElementById('tpDetailTitle').textContent = data.title;

  // Build tabs + panes
  const tabBar = document.getElementById('tpTabBar');
  const panes = document.getElementById('tpPanes');

  const hasTrain = (data.train || []).length > 0;
  const hasBus = (data.bus || []).length > 0;

  tabBar.innerHTML = `
    ${hasTrain ? `<button class="tp-tab on" onclick="tpSwitchTab('train',this)">🚃 รถไฟ / Subway / Tram</button>` : ''}
    ${hasBus ? `<button class="tp-tab${!hasTrain?' on':''}" onclick="tpSwitchTab('bus',this)">🚌 รถบัส</button>` : ''}`;

  // Map section HTML
  const mapHtml = `
    <div class="tp-map-section">
      <h3>🗺️ แผนที่เส้นทาง</h3>
      <img class="tp-map-img" src="${data.mapImg}" alt="${data.mapAlt}"
        onerror="this.style.display='none';document.getElementById('tpfb-${id}').style.display='flex'"/>
      <div id="tpfb-${id}" class="tp-map-fb">
        <div style="font-size:28px">🗺️</div>
        <p>โหลดแผนที่ไม่ได้ — กดลิงก์ด้านล่างเพื่อดูที่เว็บทางการ</p>
        <a href="${data.mapSrcUrl}" target="_blank" style="color:var(--blue);font-size:11px">ดูแผนที่ที่ ${data.mapSrc} →</a>
      </div>
      <div class="tp-map-src">แผนที่จาก: <a href="${data.mapSrcUrl}" target="_blank">${data.mapSrc}</a></div>
    </div>
    <div class="tp-tip">${data.tip}</div>`;

  // Build line cards
  function buildLineCards(lines) {
    return `<div class="tp-line-grid">${lines.map(l => `
      <div class="tp-line-card">
        <div class="tp-line-head">
          <div class="tp-line-dot" style="background:${l.color}"></div>
          <div><div class="tp-line-name">${l.name}</div><div class="tp-line-sub">${l.nameJp}</div></div>
        </div>
        <div class="tp-line-body">
          <div class="tp-line-info">${l.info}<br><strong>💴 ค่าโดยสาร:</strong> ${l.fare}</div>
          <div class="tp-stops">
            ${l.keyStops.map(s=>`<span class="tp-stop key">⭐ ${s}</span>`).join('')}
            ${l.allStops.map(s=>`<span class="tp-stop">${s}</span>`).join('')}
          </div>
          <div class="tp-line-links">
            <a class="tp-lbtn official" href="${l.official}" target="_blank">🌐 เว็บทางการ</a>
            <a class="tp-lbtn map" href="${l.mapLink}" target="_blank">🗺️ Google Maps</a>
            ${l.guideLink ? `<a class="tp-lbtn info" href="${l.guideLink}" target="_blank">📖 Japan Guide</a>` : ''}
          </div>
        </div>
      </div>`).join('')}</div>`;
  }

  panes.innerHTML = `
    <div id="tpp-train" class="tp-pane${hasTrain?' on':''}">
      ${mapHtml}
      ${hasTrain ? buildLineCards(data.train) : '<p class="tp-empty">ไม่มีข้อมูลรถไฟในเมืองนี้</p>'}
    </div>
    <div id="tpp-bus" class="tp-pane${!hasTrain&&hasBus?' on':''}">
      ${hasBus ? buildLineCards(data.bus) : '<p class="tp-empty">ไม่มีข้อมูลรถบัสในเมืองนี้</p>'}
    </div>`;

  document.getElementById('tpDetail').classList.add('on');
  document.getElementById('tpDetail').scrollIntoView({ behavior: 'smooth', block: 'start' });
}

function tpSwitchTab(tab, btn) {
  document.querySelectorAll('.tp-tab').forEach(b => b.classList.remove('on'));
  document.querySelectorAll('.tp-pane').forEach(p => p.classList.remove('on'));
  btn.classList.add('on');
  document.getElementById('tpp-' + tab)?.classList.add('on');
}

function tpClearCity() {
  document.querySelectorAll('.tp-city-btn').forEach(b => b.classList.remove('on'));
  document.getElementById('tpDetail').classList.remove('on');
  document.getElementById('tpCityGrid').scrollIntoView({ behavior: 'smooth' });
}

// ── INIT TRANSPORT ──
(function initTransport() {
  buildTpCities();
})();
</script>


<!-- ══════════════════════════════════════════
     PAGE: AIRPORT TRAIN GUIDE
══════════════════════════════════════════ -->
<div id="pgAirport" class="page">
<style>
.ap-nav{background:var(--ink);display:flex;align-items:center;gap:10px;padding:10px 18px;position:sticky;top:0;z-index:200;}
.ap-nav .logo{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#fff;letter-spacing:4px;}
.ap-nav .logo span{color:var(--gold);}
.ap-hero{background:linear-gradient(135deg,#0d1a2e,#1a2d4e);padding:30px 20px;text-align:center;}
.ap-hero h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(24px,5vw,50px);color:#fff;letter-spacing:5px;}
.ap-hero h1 span{color:var(--gold);}
.ap-hero p{color:#aaa;font-size:12px;margin-top:5px;}
.ap-wrap{max-width:1040px;margin:0 auto;padding:26px 18px 60px;}
.ap-stitle{font-family:'Shippori Mincho',serif;font-size:18px;border-left:4px solid var(--blue);padding-left:11px;margin-bottom:18px;}
.ap-tip{background:#f0f4ff;border:1px solid #b0c4de;border-radius:11px;padding:13px;margin-bottom:22px;font-size:12px;line-height:1.9;color:#333;}
.ap-tip strong{color:#1a3a6a;}
.ap-tip a{color:var(--blue);text-decoration:none;}
.ap-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:18px;}
.ap-card{background:#fff;border-radius:14px;border:1px solid var(--border);overflow:hidden;transition:box-shadow .2s;}
.ap-card:hover{box-shadow:0 8px 24px rgba(0,0,0,.1);}
.ap-card-head{padding:16px 18px 12px;border-bottom:1px solid var(--border);display:flex;align-items:flex-start;gap:12px;}
.ap-iata{font-family:'Bebas Neue',sans-serif;font-size:28px;letter-spacing:2px;line-height:1;}
.ap-airport-name{font-weight:700;font-size:13px;line-height:1.3;}
.ap-airport-city{font-size:11px;color:var(--muted);margin-top:2px;}
.ap-jrpass{display:inline-block;font-size:9px;font-weight:700;padding:2px 7px;border-radius:8px;margin-top:5px;}
.jrfree{background:#e8f5e9;color:#1a6a1a;}
.jrno{background:#fce4e4;color:#a00000;}
.ap-trains{padding:14px 18px;}
.ap-train{border-bottom:1px solid #f0ebe0;padding-bottom:12px;margin-bottom:12px;}
.ap-train:last-child{border:none;margin:0;padding:0;}
.ap-train-head{display:flex;align-items:center;gap:8px;margin-bottom:7px;}
.ap-train-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0;}
.ap-train-name{font-weight:700;font-size:13px;}
.ap-train-op{font-size:10px;color:var(--muted);}
.ap-route-table{width:100%;border-collapse:collapse;font-size:11px;margin-bottom:8px;}
.ap-route-table th{background:#f5f0e8;padding:5px 8px;text-align:left;font-weight:700;border-bottom:1px solid var(--border);}
.ap-route-table td{padding:5px 8px;border-bottom:1px solid #f5f0e8;}
.ap-route-table tr:last-child td{border:none;}
.ap-route-table .hl{font-weight:700;color:var(--blue);}
.ap-fare-badge{display:inline-block;font-size:9px;font-weight:700;padding:2px 6px;border-radius:6px;margin-left:4px;}
.afc{background:#e8f5e9;color:#1a6a1a;}
.afm{background:#fff3e0;color:#a05000;}
.afp{background:#f5e8f5;color:var(--purple);}
.ap-train-note{font-size:11px;color:#555;line-height:1.7;margin-bottom:8px;}
.ap-train-links{display:flex;gap:6px;flex-wrap:wrap;}
.ap-lbtn{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;border-radius:7px;font-size:10px;font-weight:700;text-decoration:none;font-family:'Noto Sans Thai',sans-serif;transition:opacity .2s;}
.ap-lbtn:hover{opacity:.85;}
.ap-lbtn.off{background:var(--blue);color:#fff;}
.ap-lbtn.sched{background:var(--green);color:#fff;}
.ap-lbtn.gd{background:#f0ebe0;color:var(--ink);}
.ap-lbtn.bk{background:var(--red);color:#fff;}
.ap-compare{width:100%;border-collapse:collapse;font-size:11px;margin-top:20px;background:#fff;border-radius:12px;overflow:hidden;border:1px solid var(--border);}
.ap-compare th{background:var(--ink);color:#fff;padding:9px 10px;text-align:left;font-size:11px;}
.ap-compare td{padding:9px 10px;border-bottom:1px solid #f0ebe0;vertical-align:top;font-size:11px;}
.ap-compare tr:last-child td{border:none;}
.ap-compare tr:hover td{background:#faf7f2;}
.ap-best{color:var(--green);font-weight:700;}
.ap-warn{color:var(--orange);}
</style>

<div class="ap-nav">
  <div class="logo">🗾 JAPAN <span>PLANNER</span></div>
  <div class="spacer"></div>
  <button class="nav-btn" onclick="goHome()">← หน้าแรก</button>
</div>
<div class="ap-hero">
  <h1>✈️ AIRPORT <span>TRAIN GUIDE</span></h1>
  <p>รถไฟจากสนามบินหลักทุกแห่งในญี่ปุ่น · ราคา · เวลา · JR Pass ที่ใช้ได้</p>
</div>
<div class="ap-wrap">
  <div class="ap-tip">
    <strong>💡 สรุปภาพรวม:</strong><br>
    • <strong>JR Pass National</strong> ครอบคลุม N'EX (Narita ✅), Tokyo Monorail (Haneda ✅), Haruka (KIX ✅), Rapid Airport (Sapporo/CTS ✅)<br>
    • <strong>Fukuoka Airport → Hakata</strong> ถูกที่สุดในญี่ปุ่น — Subway 5 นาที ¥260 เท่านั้น!<br>
    • ซื้อตั๋ว Round Trip เสมอ ถูกกว่า 1-way x2 ประมาณ 15–20%<br>
    • ดูตารางเวลาจริงได้ที่ <a href="https://www.japan-guide.com" target="_blank">japan-guide.com</a> หรือ App Hyperdia
  </div>
  <h2 class="ap-stitle">✈️ สนามบินและรถไฟเชื่อม</h2>
  <div class="ap-grid" id="apGrid"></div>
  <h2 class="ap-stitle" style="margin-top:32px;border-left-color:var(--green)">📊 ตารางเปรียบเทียบ — เร็วสุด vs ถูกสุด</h2>
  <div style="overflow-x:auto">
  <table class="ap-compare">
    <thead><tr><th>สนามบิน</th><th>ปลายทาง</th><th>เร็วสุด</th><th>ถูกสุด</th><th>JR Pass?</th></tr></thead>
    <tbody>
      <tr><td><strong>NRT Narita</strong></td><td>Tokyo Stn</td><td>N'EX ~53 นาที (¥3,020)</td><td>Keisei Ltd. ~75 นาที (¥1,270)</td><td class="ap-best">✅ ฟรี (N'EX)</td></tr>
      <tr><td><strong>NRT Narita</strong></td><td>Ueno/Nippori</td><td>Skyliner 41 นาที (¥2,580)</td><td>Keisei Ltd. ~60 นาที (¥1,270)</td><td class="ap-warn">❌ Skyliner ไม่รวม</td></tr>
      <tr><td><strong>HND Haneda</strong></td><td>Hamamatsucho</td><td>Tokyo Monorail 13 นาที (¥520)</td><td>Tokyo Monorail 13 นาที (¥520)</td><td class="ap-best">✅ ฟรี (Monorail)</td></tr>
      <tr><td><strong>HND Haneda</strong></td><td>Shinagawa</td><td>Keikyu Line 11 นาที (¥300)</td><td>Keikyu Line 11 นาที (¥300)</td><td class="ap-warn">❌ ไม่รวม</td></tr>
      <tr><td><strong>KIX Kansai</strong></td><td>Osaka Stn</td><td>Haruka ~45 นาที (¥2,690)</td><td>Kanku Kaisoku ~65 นาที (¥1,210)</td><td class="ap-best">✅ ฟรี (Haruka)</td></tr>
      <tr><td><strong>KIX Kansai</strong></td><td>Kyoto Stn</td><td>Haruka ~75 นาที (¥3,430)</td><td>Haruka ~75 นาที (¥3,430)</td><td class="ap-best">✅ ฟรี (Haruka)</td></tr>
      <tr><td><strong>CTS Chitose</strong></td><td>Sapporo Stn</td><td>Rapid Airport 36 นาที (¥1,150)</td><td>Rapid Airport 36 นาที (¥1,150)</td><td class="ap-best">✅ ฟรี</td></tr>
      <tr><td><strong>FUK Fukuoka</strong></td><td>Hakata Stn</td><td>Subway 5 นาที (¥260)</td><td>Subway 5 นาที (¥260)</td><td class="ap-warn">❌ ใช้ IC Card</td></tr>
      <tr><td><strong>NGO Centrair</strong></td><td>Nagoya Stn</td><td>μSKY 28 นาที (¥1,870)</td><td>Airport Express 41 นาที (¥890)</td><td class="ap-warn">❌ ไม่รวม</td></tr>
    </tbody>
  </table>
  </div>
</div>
</div>

<script>
const AP_DATA=[
  {iata:'NRT',color:'#c0392b',name:'Narita International Airport',nameJp:'成田国際空港',city:'Tokyo / Narita',jrpass:'free',jrLabel:"JR Pass ใช้ได้ฟรี (N'EX)",
   trains:[
    {name:"N'EX (Narita Express)",op:'JR East',color:'#c0392b',
     note:"รถไฟ Express ที่สะดวกสุด ตรงสู่ใจกลาง Tokyo ทุก 30–60 นาที ที่นั่ง Reserved ทั้งหมด | ใช้ JR Pass ฟรี | Round Trip ¥5,200 (14 วัน) ประหยัดกว่า 1-way x2",
     routes:[{d:'Tokyo Station',t:'~53 นาที',f:'¥3,020',b:'afm'},{d:'Shinagawa / Shibuya',t:'~65 นาที',f:'¥3,250',b:'afm'},{d:'Shinjuku / Ikebukuro',t:'~80 นาที',f:'¥3,250',b:'afm'},{d:'Yokohama',t:'~90 นาที',f:'¥4,370',b:'afp'}],
     freq:'ทุก 30–60 นาที | 07:44–21:44',
     off:'https://www.jreast.co.jp/en/multi/nex/',sched:'https://www.jreast.co.jp/e/nex/index.html',guide:'https://www.japan-guide.com/e/e2027.html'},
    {name:'Keisei Skyliner',op:'Keisei Railway',color:'#e67e22',
     note:"เร็วที่สุดสู่ Ueno — 41 นาที ถูกกว่า N'EX สำหรับย่าน Ueno/Asakusa | JR Pass ใช้ไม่ได้ | ซื้อ Skyliner + Tokyo Metro Pass รวมคุ้มมาก",
     routes:[{d:'Nippori Station',t:'41 นาที',f:'¥2,580',b:'afm'},{d:'Ueno Station',t:'44 นาที',f:'¥2,580',b:'afm'}],
     freq:'ทุก 20–40 นาที | 07:28–22:38',
     off:'https://www.keisei.co.jp/keisei/tetudou/skyliner/us/index.html',sched:'https://www.keisei.co.jp/keisei/tetudou/skyliner/us/timetable/',guide:'https://www.japan-guide.com/e/e2027.html'},
    {name:'Keisei Limited Express (ประหยัด)',op:'Keisei Railway',color:'#27ae60',
     note:"ตัวเลือกถูกสุด ¥1,270 หยุดหลายสถานี ~70 นาที เหมาะถ้าไม่รีบและต้องการประหยัด",
     routes:[{d:'Ueno Station',t:'~70 นาที',f:'¥1,270',b:'afc'},{d:'Nippori / Asakusa',t:'~65–75 นาที',f:'¥1,270',b:'afc'}],
     freq:'ทุก 10–20 นาที',
     off:'https://www.keisei.co.jp/keisei/tetudou/skyliner/us/index.html',sched:'https://www.keisei.co.jp/keisei/tetudou/skyliner/us/access_t.html',guide:'https://www.japan-guide.com/e/e2027.html'}
   ]},
  {iata:'HND',color:'#2980b9',name:"Tokyo Int'l Airport (Haneda)",nameJp:'東京国際空港',city:'Tokyo / Haneda',jrpass:'partial',jrLabel:'JR Pass ใช้ได้ฟรี (Monorail เท่านั้น)',
   trains:[
    {name:'Tokyo Monorail',op:'Tokyo Monorail Co.',color:'#0068b7',
     note:"วิ่งจากสนามบิน Haneda → Hamamatsucho Station ต่อ JR Yamanote Line ได้ทันที | ใช้ JR Pass ฟรี",
     routes:[{d:'Hamamatsucho (ไม่จอด)',t:'13 นาที',f:'¥520',b:'afc'},{d:'Hamamatsucho (จอดทุกป้าย)',t:'18 นาที',f:'¥500',b:'afc'}],
     freq:'ทุก 4–10 นาที',
     off:'https://www.tokyo-monorail.co.jp/english/',sched:'https://www.tokyo-monorail.co.jp/english/timetable/',guide:'https://www.japan-guide.com/e/e2020.html'},
    {name:'Keikyu Airport Line',op:'Keikyu Railway',color:'#e60012',
     note:"เร็วกว่าสำหรับย่าน Shinagawa, Asakusa, Yokohama ตรงถึง Shinagawa เพียง 11 นาที | JR Pass ใช้ไม่ได้ ใช้ IC Card",
     routes:[{d:'Shinagawa Station',t:'11 นาที',f:'¥300',b:'afc'},{d:'Asakusa Station',t:'~35 นาที',f:'¥580',b:'afc'},{d:'Yokohama Station',t:'~25 นาที',f:'¥380',b:'afc'}],
     freq:'ทุก 3–10 นาที',
     off:'https://www.haneda-tokyo-access.com/en/',sched:'https://www.haneda-tokyo-access.com/en/ride/timetable.html',guide:'https://www.japan-guide.com/e/e2020.html'}
   ]},
  {iata:'KIX',color:'#8e44ad',name:'Kansai International Airport',nameJp:'関西国際空港',city:'Osaka / Kyoto / Nara / Kobe',jrpass:'free',jrLabel:'JR Pass ใช้ได้ฟรี (Haruka)',
   trains:[
    {name:'Haruka Limited Express',op:'JR West',color:'#8e44ad',
     note:"รถไฟ Express หลักจาก KIX | ใช้ JR Pass ฟรี | Haruka 1-Way Ticket (นักท่องเที่ยว) Osaka ¥2,690 / Kyoto ¥3,430",
     routes:[{d:'Tennoji (Osaka)',t:'~30 นาที',f:'¥2,210',b:'afm'},{d:'Osaka Station',t:'~45 นาที',f:'¥2,690',b:'afm'},{d:'Shin-Osaka',t:'~50 นาที',f:'¥2,690',b:'afm'},{d:'Kyoto Station',t:'~75 นาที',f:'¥3,430',b:'afp'}],
     freq:'ทุก 30 นาที | 06:30–22:30',
     off:'https://www.westjr.co.jp/global/en/travel/shopping/access/train.html',sched:'https://www.westjr.co.jp/global/en/travel/shopping/access/train.html',guide:'https://www.japan-guide.com/e/e2029.html',book:'https://www.westjr.co.jp/travel-information/en/tickets-passes/oneway/haruka/'},
    {name:'Kanku Kaisoku (ราคาประหยัด)',op:'JR West',color:'#27ae60',
     note:"รถไฟ Rapid ธรรมดา ถูกกว่า Haruka มาก เหมาะถ้าไม่รีบ",
     routes:[{d:'Namba (Osaka)',t:'~55 นาที',f:'¥1,210',b:'afc'},{d:'Osaka Station',t:'~65 นาที',f:'¥1,210',b:'afc'}],
     freq:'ทุก 30 นาที',
     off:'https://www.westjr.co.jp/global/en/',sched:'https://www.westjr.co.jp/global/en/',guide:'https://www.japan-guide.com/e/e2029.html'},
    {name:"Nankai Rapi:t Express",op:'Nankai Railway',color:'#0079c2',
     note:"ดีไซน์เฉพาะ ตัวถังเหล็กสีเทา KIX → Namba ตรง JR Pass ใช้ไม่ได้",
     routes:[{d:'Namba Station (Osaka)',t:'~38 นาที',f:'¥1,450',b:'afm'}],
     freq:'ทุก 30–60 นาที',
     off:'https://www.nankai.co.jp/traffic/railinfo/rapit.html',sched:'https://www.nankai.co.jp/traffic/railinfo/rapit.html',guide:'https://www.japan-guide.com/e/e2029.html'}
   ]},
  {iata:'CTS',color:'#2980b9',name:'New Chitose Airport',nameJp:'新千歳空港',city:'Sapporo / Hokkaido',jrpass:'free',jrLabel:'JR Pass & Hokkaido Pass ใช้ได้ฟรี',
   trains:[
    {name:'JR Hokkaido Rapid Airport',op:'JR Hokkaido',color:'#2980b9',
     note:"ออกทุก ~12 นาที วันละ 07:00–23:00 ใช้ JR Pass และ Hokkaido Rail Pass ฟรี | U-Seat (Reserved) เพิ่ม ¥840",
     routes:[{d:'Sapporo Station',t:'36 นาที',f:'¥1,150',b:'afc'},{d:'Otaru Station',t:'~70 นาที',f:'¥1,680',b:'afc'},{d:'Asahikawa Station',t:'~100 นาที',f:'¥3,540',b:'afm'}],
     freq:'ทุก ~12 นาที | 07:00–23:00',
     off:'https://www.jrhokkaido.co.jp/global/english/',sched:'https://www.jrhokkaido.co.jp/global/english/ticket/jrh/',guide:'https://www.japan-guide.com/e/e5310.html'}
   ]},
  {iata:'FUK',color:'#e67e22',name:'Fukuoka Airport',nameJp:'福岡空港',city:'Fukuoka / Hakata',jrpass:'no',jrLabel:'JR Pass ใช้ไม่ได้ — ใช้ IC Card',
   trains:[
    {name:'Fukuoka City Subway (Kuko Line)',op:'Fukuoka City Subway',color:'#e60012',
     note:"ถูกและเร็วสุดในญี่ปุ่น! Hakata Station 5 นาที ¥260 ใช้ IC Card (Hayakaken/Suica) ได้เลย",
     routes:[{d:'Hakata Station',t:'5 นาที',f:'¥260',b:'afc'},{d:'Tenjin Station',t:'11 นาที',f:'¥260',b:'afc'},{d:'Meinohama Station',t:'22 นาที',f:'¥360',b:'afc'}],
     freq:'ทุก 3–8 นาที',
     off:'https://subway.city.fukuoka.lg.jp/en/',sched:'https://subway.city.fukuoka.lg.jp/en/route/',guide:'https://www.japan-guide.com/e/e4800.html'}
   ]},
  {iata:'NGO',color:'#27ae60',name:'Chubu Centrair Airport',nameJp:'中部国際空港',city:'Nagoya / Chubu',jrpass:'no',jrLabel:'JR Pass ใช้ไม่ได้ — ซื้อตั๋ว Meitetsu',
   trains:[
    {name:'Meitetsu μSKY Limited Express',op:'Meitetsu Railway',color:'#e60012',
     note:"Premium Express ตรงสู่ Nagoya Station ที่นั่ง Reserved ทั้งหมด JR Pass ใช้ไม่ได้",
     routes:[{d:'Nagoya Station',t:'28 นาที',f:'¥1,870',b:'afp'}],
     freq:'ทุก 30 นาที | 06:26–23:07',
     off:'https://www.meitetsu.co.jp/foreign/en/index.html',sched:'https://www.meitetsu.co.jp/foreign/en/air.html',guide:'https://www.japan-guide.com/e/e2166.html'},
    {name:'Meitetsu Airport Express (ประหยัด)',op:'Meitetsu Railway',color:'#27ae60',
     note:"Express ธรรมดา ถูกกว่า μSKY ครึ่งราคา ใช้เวลา 41 นาที",
     routes:[{d:'Nagoya Station',t:'41 นาที',f:'¥890',b:'afc'}],
     freq:'ทุก 15–30 นาที',
     off:'https://www.meitetsu.co.jp/foreign/en/index.html',sched:'https://www.meitetsu.co.jp/foreign/en/air.html',guide:'https://www.japan-guide.com/e/e2166.html'}
   ]}
];

function buildAirportPage(){
  const g=document.getElementById('apGrid');
  if(!g) return;
  const JRL={free:'jrfree',partial:'jrfree',no:'jrno'};
  g.innerHTML=AP_DATA.map(a=>`
    <div class="ap-card">
      <div class="ap-card-head">
        <div>
          <div class="ap-iata" style="color:${a.color}">${a.iata}</div>
          <div class="ap-airport-name">${a.name}</div>
          <div class="ap-airport-city">✈️ ${a.city}</div>
          <span class="ap-jrpass ${JRL[a.jrpass]||'jrno'}">${a.jrLabel}</span>
        </div>
      </div>
      <div class="ap-trains">
        ${a.trains.map(t=>`
          <div class="ap-train">
            <div class="ap-train-head">
              <div class="ap-train-dot" style="background:${t.color}"></div>
              <div><div class="ap-train-name">${t.name}</div><div class="ap-train-op">${t.op}</div></div>
            </div>
            <div class="ap-train-note">${t.note}</div>
            <table class="ap-route-table">
              <thead><tr><th>ปลายทาง</th><th>เวลา</th><th>ค่าโดยสาร</th></tr></thead>
              <tbody>${t.routes.map(r=>`<tr>
                <td class="hl">${r.d}</td><td>${r.t}</td>
                <td>${r.f}<span class="ap-fare-badge ${r.b||''}">${r.b==='afc'?'ประหยัด':r.b==='afp'?'Premium':''}</span></td>
              </tr>`).join('')}</tbody>
            </table>
            <div style="font-size:10px;color:var(--muted);margin-bottom:7px">🕐 ${t.freq}</div>
            <div class="ap-train-links">
              <a class="ap-lbtn off" href="${t.off}" target="_blank">🌐 เว็บทางการ</a>
              <a class="ap-lbtn sched" href="${t.sched}" target="_blank">📅 ตารางเวลา</a>
              <a class="ap-lbtn gd" href="${t.guide}" target="_blank">📖 Japan Guide</a>
              ${t.book?`<a class="ap-lbtn bk" href="${t.book}" target="_blank">🎫 ซื้อตั๋ว</a>`:''}
            </div>
          </div>`).join('')}
      </div>
    </div>`).join('');
}
(function(){buildAirportPage();})();
</script>
</div>

</body></html>

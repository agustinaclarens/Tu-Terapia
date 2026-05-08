[sistema_financiero_2026okok.html](https://github.com/user-attachments/files/27539405/sistema_financiero_2026okok.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Gestión Financiera 2026</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#f5f4f1;--sur:#fff;--brd:#e6e4dd;--brd2:#ccc9c0;
  --tx:#191815;--mu:#6a6860;--mu2:#9a9890;
  --g:#1a6b3c;--gb:#edf7f2;--gbrd:#a8dfc0;
  --r:#b91c1c;--rb:#fef2f2;--rbrd:#fca5a5;
  --b:#1d4ed8;--bb:#eff6ff;--bbrd:#93c5fd;
  --am:#92400e;--amb:#fffbeb;--ambrd:#fcd34d;
  --pu:#5b21b6;--pub:#f5f3ff;
  --ar:#0070f3;--uy:#00a846;--usd:#7c3aed;--ali:#d97706;
}
body{font-family:'DM Sans',sans-serif;background:var(--bg);color:var(--tx);font-size:14px}
#login{position:fixed;top:0;left:0;right:0;bottom:0;background:#191815;display:flex;align-items:center;justify-content:center;z-index:9999}
.lbox{background:#fff;border-radius:16px;padding:40px 36px;width:320px;text-align:center}
.lbox h2{font-size:18px;font-weight:500;margin-bottom:4px}
.lbox p{color:#6a6860;font-size:12px;margin-bottom:20px}
.lbox input{width:100%;border:1px solid #e6e4dd;border-radius:8px;padding:10px;font-size:15px;text-align:center;letter-spacing:4px;margin-bottom:10px;outline:none;font-family:monospace}
.lbox input:focus{border-color:#1d4ed8;background:#eff6ff}
.lbox button{width:100%;background:#191815;color:#fff;border:none;border-radius:8px;padding:12px;font-size:14px;cursor:pointer;font-weight:500}
.lbox button:hover{background:#333}
.lerr{color:#b91c1c;font-size:12px;margin-top:8px;min-height:16px}
#app{display:block}
nav{background:var(--tx);height:50px;display:flex;align-items:center;padding:0 16px;gap:0;position:sticky;top:0;z-index:100}
.brand{color:#fff;font-weight:500;font-size:14px;margin-right:24px;white-space:nowrap;flex-shrink:0}
.brand em{font-style:normal;opacity:.4;font-size:11px;font-family:'DM Mono',monospace;margin-left:6px}
.tabs{display:flex;gap:2px;overflow-x:auto;scrollbar-width:none}
.tabs::-webkit-scrollbar{display:none}
.tab{background:none;border:none;color:rgba(255,255,255,.45);padding:5px 11px;border-radius:5px;cursor:pointer;font-size:12px;font-family:'DM Sans',sans-serif;white-space:nowrap;transition:all .12s}
.tab:hover{color:#fff;background:rgba(255,255,255,.08)}
.tab.on{color:#fff;background:rgba(255,255,255,.14)}
main{max-width:1280px;margin:0 auto;padding:20px}
.pg{display:none}.pg.on{display:block}
.ph{margin-bottom:20px}
.ph h1{font-size:20px;font-weight:500;letter-spacing:-.3px}
.ph p{color:var(--mu);font-size:12px;margin-top:3px}
.kpis{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:10px;margin-bottom:20px}
.kpi{background:var(--sur);border:1px solid var(--brd);border-radius:10px;padding:14px 16px}
.klbl{font-size:10px;color:var(--mu);text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px}
.kval{font-size:20px;font-weight:500;font-family:'DM Mono',monospace;letter-spacing:-1px}
.kval.pos{color:var(--g)}.kval.neg{color:var(--r)}
.ksub{font-size:10px;color:var(--mu2);margin-top:3px}
.cgrid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:20px}
@media(max-width:700px){.cgrid{grid-template-columns:1fr}}
.cc{background:var(--sur);border:1px solid var(--brd);border-radius:10px;padding:16px}
.cc h3{font-size:12px;font-weight:500;margin-bottom:12px}
.cw{position:relative;height:180px}
.stitle{font-size:11px;font-weight:500;color:var(--mu);text-transform:uppercase;letter-spacing:.5px;margin:20px 0 10px}
.card{background:var(--sur);border:1px solid var(--brd);border-radius:10px;overflow:hidden;margin-bottom:14px}
.card-hd{padding:12px 16px;border-bottom:1px solid var(--brd);font-size:12px;font-weight:500}
.tw{overflow-x:auto}
table{width:100%;border-collapse:collapse;min-width:800px}
th{font-size:10px;font-weight:500;color:var(--mu);text-transform:uppercase;letter-spacing:.3px;padding:7px 8px;text-align:right;background:var(--bg);border-bottom:1px solid var(--brd)}
th:first-child{text-align:left}
td{padding:6px 8px;text-align:right;border-bottom:1px solid var(--brd);font-size:12px;font-family:'DM Mono',monospace}
td:first-child{text-align:left;font-family:'DM Sans',sans-serif;color:var(--mu)}
tr:last-child td{border-bottom:none}
.tr-tot td{background:var(--bg);font-weight:500;border-top:1px solid var(--brd2)}
.tr-tot td:first-child{color:var(--tx)}
.tr-pos td{background:var(--gb);color:var(--g)}.tr-pos td:first-child{color:var(--g)}
.tr-neg td{background:var(--rb);color:var(--r)}.tr-neg td:first-child{color:var(--r)}
.tr-paid td{background:var(--gb)!important}.tr-paid td:first-child{color:var(--g)!important}
input[type=number]{width:100%;background:transparent;border:none;text-align:right;font-size:12px;font-family:'DM Mono',monospace;color:var(--tx);padding:0;outline:none;display:block}
input[type=number]:focus{background:var(--bb);color:var(--b);border-radius:2px}
input[type=number]::-webkit-inner-spin-button{opacity:0}
.est-cell{background:var(--amb)!important}
.est-cell input{color:var(--am)!important}
.paid-cb{width:14px;height:14px;accent-color:var(--g);cursor:pointer;display:block;margin:0 auto}
.saldo-row{padding:14px 16px;display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.saldo-row label{font-size:12px;color:var(--mu)}
.saldo-inp{border:1px solid var(--brd);border-radius:6px;padding:6px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right;width:160px;outline:none}

/* DOLAR TOGGLE */
.dolar-btn{display:inline-flex;align-items:center;gap:6px;background:var(--sur);border:1px solid var(--brd);border-radius:8px;padding:6px 14px;font-size:12px;cursor:pointer;font-family:'DM Sans',sans-serif;transition:all .15s;margin-bottom:14px}
.dolar-btn:hover{border-color:var(--b);color:var(--b)}
.dolar-btn.on{background:var(--bb);border-color:var(--bbrd);color:var(--b);font-weight:500}
.dolar-pill{background:var(--bb);color:var(--b);font-size:10px;padding:1px 6px;border-radius:20px;font-weight:500}

.savebar{display:none;position:sticky;bottom:0;background:var(--tx);color:#fff;padding:10px 20px;text-align:center;font-size:12px;gap:10px;align-items:center;justify-content:center;z-index:100}
.savebar.on{display:flex}
.sbtn{background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.2);color:#fff;padding:5px 14px;border-radius:5px;cursor:pointer;font-size:11px;font-family:'DM Sans',sans-serif}
.info{padding:10px 14px;border-radius:8px;font-size:12px;margin-bottom:14px;border:1px solid var(--bbrd);background:var(--bb);color:var(--b)}
.part-bar{height:36px;border-radius:8px;overflow:hidden;display:flex;margin-bottom:12px}
.part-seg{height:100%;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:500;color:#fff;min-width:0;overflow:hidden;transition:width .3s}
.esc-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;margin-bottom:20px}
@media(max-width:700px){.esc-grid{grid-template-columns:1fr}}
.esc{border-radius:10px;padding:16px;border:1px solid}
.esc-b{background:var(--bg);border-color:var(--brd2)}
.esc-o{background:var(--gb);border-color:var(--gbrd)}
.esc-p{background:var(--rb);border-color:var(--rbrd)}
.esc h4{font-size:11px;font-weight:500;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px}
.esc-b h4{color:var(--mu)}.esc-o h4{color:var(--g)}.esc-p h4{color:var(--r)}
.flujo-res{border-radius:10px;padding:18px;margin-bottom:14px;border:2px solid}
.flujo-ok{background:var(--gb);border-color:var(--gbrd)}
.flujo-mal{background:var(--rb);border-color:var(--rbrd)}
.flujo-big{font-size:26px;font-weight:500;font-family:'DM Mono',monospace}
.inv-card{background:var(--sur);border:1px solid var(--brd);border-radius:10px;padding:18px;margin-bottom:12px}
.inv-rate{font-size:22px;font-weight:500;color:var(--g);font-family:'DM Mono',monospace}
.rec-a{background:var(--gb);color:var(--g);display:inline-flex;padding:3px 10px;border-radius:20px;font-size:11px;font-weight:500;margin-top:8px}
.rec-m{background:var(--amb);color:var(--am);display:inline-flex;padding:3px 10px;border-radius:20px;font-size:11px;font-weight:500;margin-top:8px}
</style>
</head>
<body>

<div id="login">
  <div class="lbox">
    <div style="font-size:30px;margin-bottom:10px">🔐</div>
    <h2>Gestión Financiera 2026</h2>
    <p>Ingresá la contraseña para continuar</p>
    <input type="password" id="pwd" placeholder="••••••••••">
    <button id="loginbtn">Ingresar</button>
    <div class="lerr" id="lerr"></div>
  </div>
</div>

<div id="app">
<nav>
  <div class="brand">Gestión Financiera <em>2026</em></div>
  <div class="tabs">
    <button class="tab on"  data-pg="dashboard">Dashboard</button>
    <button class="tab"     data-pg="argentina">🇦🇷 Argentina</button>
    <button class="tab"     data-pg="uyu">🇺🇾 Uruguay UYU</button>
    <button class="tab"     data-pg="usd">🇺🇾 Uruguay USD</button>
    <button class="tab"     data-pg="alianzas">🤝 Alianzas</button>
    <button class="tab"     data-pg="participacion">📊 Participación</button>
    <button class="tab"     data-pg="proyecciones">📈 Proyecciones</button>
    <button class="tab"     data-pg="inversion">💰 Inversión UY</button>
    <button class="tab"     data-pg="flujo">🔄 Flujo AR</button>
    <button class="tab"     data-pg="flujouy">🔄 Flujo UY</button>
  </div>
</nav>
<main>
  <div class="pg on" id="pg-dashboard">
    <div class="ph"><h1>Dashboard ejecutivo 2026</h1><p id="dash-subtitle">Resumen consolidado · datos reales</p></div>
    <div class="kpis" id="d-kpis"></div>
    <div class="cgrid">
      <div class="cc"><h3>Facturación AR (ARS)</h3><div class="cw"><canvas id="ch-ar"></canvas></div></div>
      <div class="cc"><h3>Facturación UY — canales UYU</h3><div class="cw"><canvas id="ch-uy"></canvas></div></div>
      <div class="cc"><h3>Resultado neto AR (ARS)</h3><div class="cw"><canvas id="ch-res"></canvas></div></div>
      <div class="cc"><h3>Alianzas — top 8 (UYU)</h3><div class="cw"><canvas id="ch-ali"></canvas></div></div>
    </div>
    <div id="d-tables"></div>
  </div>
  <div class="pg" id="pg-argentina"><div id="ar-wrap"></div></div>
  <div class="pg" id="pg-uyu"><div id="uyu-wrap"></div></div>
  <div class="pg" id="pg-usd"><div id="usd-wrap"></div></div>
  <div class="pg" id="pg-alianzas"><div id="ali-wrap"></div></div>
  <div class="pg" id="pg-participacion"><div id="part-wrap"></div></div>
  <div class="pg" id="pg-proyecciones"><div id="proy-wrap"></div></div>
  <div class="pg" id="pg-inversion"><div id="inv-wrap"></div></div>
  <div class="pg" id="pg-flujo"><div id="flujo-wrap"></div></div>
  <div class="pg" id="pg-flujouy"><div id="flujouy-wrap"></div></div>
</main>
</div>

<div class="savebar" id="savebar">
  Cambios sin guardar
  <button class="sbtn" onclick="saveD()">Guardar</button>
  <button class="sbtn" onclick="exportD()">Exportar JSON</button>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<script>
const DEFAULT = {
  ar_mp: [39053300, 53345300, 56460750, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  ar_hon: [20170900, 25972200, 29143500, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  ar_sueldos: {
  'Agustina Clarens': [2355657,2484992,2557097,2643967,0,0,0,0,0,0,0,0],
  'Sofia Harduín': [1366799,1845145,1767680,1922022,0,0,0,0,0,0,0,0],
  'Josefina Di Boscio': [2453866,2525028,2598254,2686594.64,0,0,0,0,0,0,0,0],
  'Belen Camargo': [1900649,2416344,2574221,2506503,0,0,0,0,0,0,0,0],
  'Sol Celaya': [1500000,1500000,1673551,1673551,0,0,0,0,0,0,0,0],
  'Ornella Mamone': [695419,1077900,1077900,1479222,0,0,0,0,0,0,0,0]
},
  ar_servicios: {
  'Contables (Iridoy)': [789000,858000,858000,4427020,0,0,0,0,0,0,0,0],
  'Clases de inglés': [400000, 360000, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Consultoría datos': [1514810,249920,0,280170,0,0,0,0,0,0,0,0],
  'Adelanto MP': [216670, 293852, 744803, 0, 0, 0, 0, 0, 0, 0, 0, 0]
},
  ar_impositiva: {
  'Cargas sociales 931': [4379998,5313892,5373042,5701923,0,0,0,0,0,0,0,0],
  'IVA': [3219906, 4286517, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Ingresos Brutos': [224741,269299,4377136,0,0,0,0,0,0,0,0,0],
  'Autonomos': [125485,129062,279469,136628,0,0,0,0,0,0,0,0]
},
  ar_metas: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  ar_saldo_ini: 0,
  uy_mp: [1943575, 2055298, 2890914, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  uy_ali: [1248634, 1426582, 1498827, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  uy_tall: [0, 41358, 38530, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  uy_hon: [1785111, 2233355, 2607490, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  uy_sueldos: {
  'Nico (CEO)': [200000,200000,200000,200000,0,0,0,0,0,0,0,0],
  'Nacho (COO)': [200000,200000,200000,200000,0,0,0,0,0,0,0,0],
  'Carolina (HCP)': [80000,80000,80000,80000,0,0,0,0,0,0,0,0],
  'Vittoria (Social)': [100000,100000,100000,61538,115384,0,0,0,0,0,0,0],
  'Sofia (Design)': [36155,42000,42000,51800,0,0,0,0,0,0,0,0],
  'Florencia (B2B)': [65164,80000,80000,80000,0,0,0,0,0,0,0,0],
  'Ismael (B2B)': [41320,41320,48000,48000,0,0,0,0,0,0,0,0]
},
  uy_servicios: {
  'Contables (Pinot)': [44091,44091,43005,43993,0,0,0,0,0,0,0,0],
  'Biller': [2316,2316,2316,2316,0,0,0,0,0,0,0,0],
  'Podcast': [16348, 12688, 16688, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Meta Facebook': [61399,66084,137778,144311,0,0,0,0,0,0,0,0]
},
  uy_impositiva: {
  'BPS': [107977,137033,139710,0,0,0,0,0,0,0,0,0],
  'IVA': [66199, 48819, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Anticipo IP': [1403,1403,2236,0,0,0,0,0,0,0,0,0],
  'Anticipo IRAE': [110672,115589,129271,0,0,0,0,0,0,0,0,0]
},
  uy_otros: {
  'Eventos': [16348, 10750, 72236, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Reembolsos': [3680, 45794, 10555, 0, 0, 0, 0, 0, 0, 0, 0, 0]
},
  uy_metas: [0,0,0,0,2600,0,0,0,0,0,0,0],
  uy_saldo_ini: 0,
  usd_pp: [7827, 6467, 6628, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  usd_gastos: {
  'Boron (dev)': [939,1927,4185,170,0,0,0,0,0,0,0,0],
  'Google Ads': [38,1030,1334,1545,0,0,0,0,0,0,0,0],
  'Meta Ventia': [338,0,419,411,0,0,0,0,0,0,0,0],
  'Meta publi': [0,3091,180,360,0,0,0,0,0,0,0,0],
  'Calendly': [15, 15, 15, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Brevo': [803,643,643,720,0,0,0,0,0,0,0,0],
  'GW UY': [252,252,252,252,0,0,0,0,0,0,0,0],
  'GW AR': [100,100,100,100,0,0,0,0,0,0,0,0],
  'GW CL': [67,67,67,67,0,0,0,0,0,0,0,0],
  'ChatGPT': [20,20,20,20,0,0,0,0,0,0,0,0],
  'Zoom': [160,69,69,69,0,0,0,0,0,0,0,0],
  'VENTIA': [232,232,232,232,0,0,0,0,0,0,0,0],
  'Otros': [1078, 1117, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]
},
  usd_metas: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  usd_saldo_ini: 0,
  ali_cupones: {
    'ANII': [6720.0, 25920.0, 11520.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Kinko': [8880.0, 7770.0, 11100.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Vesta Hub': [7025.0, 2775.0, 2525.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Genexus': [29575.0, 24450.0, 31975.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Greycon': [4000.0, 12075.0, 10900.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Uruware': [4800.0, 5175.0, 1600.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Nodum': [13625.0, 26625.0, 23125.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Datalogic': [800.0, 4625.0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Fraylog': [1600.0, 3700.0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Farmashop': [94225.0, 120450.0, 156700.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Qubika/Luneso': [33808.0, 33707.0, 39660.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Paselibre': [2240.0, 8960.0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Big Cheese': [9000.0, 12875.0, 14050.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'ISA Portal': [2775.0, 6650.0, 800.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Fosmetal': [24723.0, 57760.0, 63840.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Kaizen': [19225.0, 27225.0, 16650.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Quanam SGE': [9425.0, 13300.0, 13925.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Orangeloops': [1850.0, 4250.0, 3700.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'Cantegril CC': [5175.0, 6225.0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
    'SECURITAS': [0, 0, 1480.0, 0, 0, 0, 0, 0, 0, 0, 0, 0],
  },
  ali: {
  'ANII': [18000, 18000, 18000,18000, 0, 0, 0, 0, 0, 0, 0, 0],
  'Kinko': [10000, 10000, 10000,10000, 0, 0, 0, 0, 0, 0, 0, 0],
  'AXO (SISI)': [20423, 15473, 20423,15473, 20423, 15473, 20423, 15473, 20423, 15473, 20423, 15473],
  'Vesta Hub': [2597, 2597, 2597,2597, 0, 0, 0, 0, 0, 0, 0, 0],
  'Genexus': [21457, 21457, 21457,21457, 0, 0, 0, 0, 0, 0, 0, 0],
  'Greycon': [3613, 3613, 3613,3613, 0, 0, 0, 0, 0, 0, 0, 0],
  'Uruware': [4856, 4856, 4856,4856, 0, 0, 0, 0, 0, 0, 0, 0],
  'Nodum': [8244, 8244, 8244,8244, 0, 0, 0, 0, 0, 0, 0, 0],
  'Datalogic': [10164, 10164, 10164,10164, 0, 0, 0, 0, 0, 0, 0, 0],
  'Fraylog': [29700, 29700, 29700,29700, 0, 0, 0, 0, 0, 0, 0, 0],
  'Farmashop': [240900, 240900, 240900,240900, 0, 0, 0, 0, 0, 0, 0, 0],
  'TCS': [412500, 430068, 412500,412500, 0, 0, 0, 0, 0, 0, 0, 0],
  'Qubika/Luneso': [14720, 18080, 21200,17200, 0, 0, 0, 0, 0, 0, 0, 0],
  'Paselibre': [960, 3840, 0,0, 0, 0, 0, 0, 0, 0, 0, 0],
  'LOreal': [22860, 0, 0,0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Arcsona': [14400, 27585, 44100,28035, 0, 0, 0, 0, 0, 0, 0, 0],
  'Cedarcode': [2880, 0, 0,0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Big Cheese': [8550, 12231, 13347,14107.5, 0, 0, 0, 0, 0, 0, 0, 0],
  'ISA Portal': [7406, 10862, 42790,27945, 0, 0, 0, 0, 0, 0, 0, 0],
  'Interfase': [1440, 1440, 27045,28485, 0, 0, 0, 0, 0, 0, 0, 0],
  'Fosmetal': [79240, 106407, 116596,124520, 0, 0, 0, 0, 0, 0, 0, 0],
  'Kaizen': [18264, 25863, 15817,23180, 0, 0, 0, 0, 0, 0, 0, 0],
  'Quanam ATEL': [0, 3800, 4916,7315, 0, 0, 0, 0, 0, 0, 0, 0],
  'Quanam SGE': [8954, 8835, 8312,5795, 0, 0, 0, 0, 0, 0, 0, 0],
  'Sofka': [5794, 4995, 0,0, 0, 0, 0, 0, 0, 0, 0, 0],
  'ROOTSTRAP': [4320, 0, 0,0, 0, 0, 0, 0, 0, 0, 0, 0],
  'Orangeloops': [1758, 4037, 1850,3050, 0, 0, 0, 0, 0, 0, 0, 0],
  'Cantegril CC': [0, 5913, 2543,1665, 0, 0, 0, 0, 0, 0, 0, 0],
  'SECURITAS': [0, 0, 2109,10545, 0, 0, 0, 0, 0, 0, 0, 0],
  'AFAP ITAU': [0, 9540, 10980,6660, 0, 0, 0, 0, 0, 0, 0, 0],
  'Montajes Nunez': [0, 0, 1218,609, 0, 0, 0, 0, 0, 0, 0, 0],
  'DARNEL': [0,0,0,878.75,0,0,0,0,0,0,0,0]
},
  paid: {},
  flujo_fac: 59784300,
  flujo_dias: 18,
  flujo_pct: 3.38,
  flujo_adelanto_pct: 7.15
};
let D = JSON.parse(JSON.stringify(DEFAULT));
let dirty = false;
try { 
  const s=localStorage.getItem('fin2026'); 
  if(s) {
    const saved=JSON.parse(s);
    // Merge: if saved has empty/missing ali_cupones, use defaults
    if(!saved.ali_cupones || Object.keys(saved.ali_cupones).length===0){
      saved.ali_cupones=DEFAULT.ali_cupones;
    }
    D=saved;
  }
} catch(e){}
if(!D.ali_cupones) D.ali_cupones={};

function saveD(){ localStorage.setItem('fin2026',JSON.stringify(D)); dirty=false; document.getElementById('savebar').classList.remove('on'); }
function exportD(){ const a=document.createElement('a'); a.href='data:application/json,'+encodeURIComponent(JSON.stringify(D,null,2)); a.download='financiero2026.json'; a.click(); }
function markDirty(){ dirty=true; document.getElementById('savebar').classList.add('on'); }

const M=['Ene','Feb','Mar','Abr','May','Jun','Jul','Ago','Sep','Oct','Nov','Dic'];
const f=(n)=>isNaN(n)||n===null?'-':new Intl.NumberFormat('es-AR',{maximumFractionDigits:0}).format(Math.round(n));
const fv=(n)=>n>=0?'$ '+f(n):'($ '+f(Math.abs(n))+')';
const fp=(n)=>n===0?'—':(n>0?'▲ +':'▼ ')+Math.abs(n).toFixed(1)+'%';
const sumO=(o,m)=>Object.values(o).reduce((a,v)=>a+(v[m]||0),0);
const rowS=(a)=>a.slice(0,12).reduce((a,b)=>a+b,0);

function arFac(m){ return D.ar_mp[m]||0; }
function arGas(m){
  const IVA_P=4286517/39053300, IIBB_P=269299/53345300;
  const fp_=m>0?arFac(m-1):arFac(0);
  let iva=D.ar_impositiva['IVA'][m], iibb=D.ar_impositiva['Ingresos Brutos'][m];
  if(m>=2&&iva===0) iva=fp_*IVA_P;
  if(m>=2&&iibb===0) iibb=fp_*IIBB_P;
  return D.ar_hon[m]+sumO(D.ar_sueldos,m)+sumO(D.ar_servicios,m)+
    D.ar_impositiva['Cargas sociales 931'][m]+iva+iibb+
    D.ar_impositiva['Autonomos'][m];
}
function arRes(m){ return arFac(m)-arGas(m); }

function uyFac(m){ return (D.uy_mp[m]||0)+(D.uy_ali[m]||0)+(D.uy_tall[m]||0); }
function uyGas(m){
  const fac=uyFac(m);
  const BPS_P=137033/3192209, IVA_P=48819/3192209, IP_P=1403/3192209, IRAE_P=115589/3192209;
  let bps=D.uy_impositiva['BPS'][m], iva=D.uy_impositiva['IVA'][m];
  let ip=D.uy_impositiva['Anticipo IP'][m], irae=D.uy_impositiva['Anticipo IRAE'][m];
  if(m>=3&&bps===0) bps=fac*BPS_P;
  if(m>=2&&iva===0) iva=fac*IVA_P;
  if(m>=2&&ip===0) ip=fac*IP_P;
  if(m>=2&&irae===0) irae=fac*IRAE_P;
  return D.uy_hon[m]+sumO(D.uy_sueldos,m)+sumO(D.uy_servicios,m)+bps+iva+ip+irae+sumO(D.uy_otros,m);
}
function uyRes(m){ return uyFac(m)-uyGas(m); }

function usdFac(m){ return D.usd_pp[m]||0; }
function usdGas(m){ return sumO(D.usd_gastos,m); }
function usdRes(m){ return usdFac(m)-usdGas(m); }

function aliFac(m){ return sumO(D.ali,m); }

function cfAR(){ let s=D.ar_saldo_ini||0; return M.map((_,m)=>{s+=arRes(m);return s;}); }
function cfUY(){ let s=D.uy_saldo_ini||0; return M.map((_,m)=>{s+=uyRes(m);return s;}); }
function cfUSD(){ let s=D.usd_saldo_ini||0; return M.map((_,m)=>{s+=usdRes(m);return s;}); }

// Charts
const CHS={};
function mkChart(id,cfg){ if(CHS[id]) CHS[id].destroy(); const el=document.getElementById(id); if(!el) return; CHS[id]=new Chart(el,cfg); }
const BOPTS=(cur)=>({responsive:true,maintainAspectRatio:false,
  plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>`${cur} ${f(c.raw)}`}}},
  scales:{x:{grid:{display:false},ticks:{font:{size:10}}},y:{grid:{color:'rgba(0,0,0,.04)'},ticks:{font:{size:10},callback:v=>`${cur} ${f(v)}`}}}});

function renderCharts(){
  const lbl=M.slice(0,3);
  mkChart('ch-ar',{type:'bar',data:{labels:lbl,datasets:[{data:lbl.map((_,m)=>arFac(m)),backgroundColor:'rgba(0,112,243,.12)',borderColor:'rgba(0,112,243,.7)',borderWidth:1.5,borderRadius:4}]},options:BOPTS('$')});
  mkChart('ch-uy',{type:'bar',data:{labels:lbl,datasets:[
    {label:'MP UY',data:lbl.map((_,m)=>D.uy_mp[m]),backgroundColor:'rgba(0,168,70,.15)',borderColor:'rgba(0,168,70,.8)',borderWidth:1.5,borderRadius:4},
    {label:'Alianzas',data:lbl.map((_,m)=>D.uy_ali[m]),backgroundColor:'rgba(0,168,70,.35)',borderColor:'rgba(0,168,70,1)',borderWidth:1.5,borderRadius:4},
    {label:'Talleres',data:lbl.map((_,m)=>D.uy_tall[m]),backgroundColor:'rgba(0,168,70,.55)',borderColor:'rgba(0,168,70,1)',borderWidth:1.5,borderRadius:4},
  ]},options:{...BOPTS('$'),plugins:{legend:{display:true,labels:{font:{size:10},boxWidth:8}},tooltip:{callbacks:{label:c=>`${c.dataset.label}: $ ${f(c.raw)}`}}}}});
  const rd=lbl.map((_,m)=>arRes(m));
  mkChart('ch-res',{type:'bar',data:{labels:lbl,datasets:[{data:rd,backgroundColor:rd.map(v=>v>=0?'rgba(26,107,60,.15)':'rgba(185,28,28,.15)'),borderColor:rd.map(v=>v>=0?'rgba(26,107,60,.7)':'rgba(185,28,28,.7)'),borderWidth:1.5,borderRadius:4}]},options:BOPTS('$')});
  const tops=Object.entries(D.ali).map(([n,v])=>({n,t:v.slice(0,3).reduce((a,b)=>a+b,0)})).sort((a,b)=>b.t-a.t).slice(0,8);
  mkChart('ch-ali',{type:'bar',data:{labels:tops.map(t=>t.n),datasets:[{data:tops.map(t=>t.t),backgroundColor:'rgba(217,119,6,.15)',borderColor:'rgba(217,119,6,.7)',borderWidth:1.5,borderRadius:4}]},options:{...BOPTS('$'),indexAxis:'y',scales:{x:{grid:{color:'rgba(0,0,0,.04)'},ticks:{font:{size:10}}},y:{grid:{display:false},ticks:{font:{size:10}}}}}});
}

function renderKPIs(){
  // Find last month with any data
  let lastM = 0;
  for(let m=11;m>=0;m--){
    if(arFac(m)>0||uyFac(m)>0||usdFac(m)>0){ lastM=m; break; }
  }
  const range = lastM===0 ? M[0] : M[0]+'–'+M[lastM];
  const firstM = 0;
  
  // Accumulate from first to last month with data
  let tAR=0,tUY=0,tUSD=0,tAli=0,rAR=0,rUY=0;
  for(let m=firstM;m<=lastM;m++){
    tAR+=arFac(m); tUY+=uyFac(m); tUSD+=usdFac(m);
    tAli+=aliFac(m); rAR+=arRes(m); rUY+=uyRes(m);
  }
  const vAR=arFac(0)>0?(arFac(lastM)-arFac(0))/arFac(0)*100:0;
  
  // Update subtitle
  const sub = document.getElementById('dash-subtitle');
  if(sub) sub.textContent = 'Resumen consolidado · Ene–'+M[lastM]+' · datos reales';
  
  document.getElementById('d-kpis').innerHTML=[
    {l:'Facturado AR',v:'$ '+f(tAR),s:'ARS · Ene–'+M[lastM],b:vAR},
    {l:'Facturado UY',v:'$ '+f(tUY),s:'UYU · Ene–'+M[lastM],b:null},
    {l:'Alianzas UY',v:'$ '+f(tAli),s:'UYU · Ene–'+M[lastM],b:null},
    {l:'PayPal UY',v:'U$D '+f(tUSD),s:'USD · Ene–'+M[lastM],b:null},
    {l:'Resultado AR',v:fv(rAR),s:'neto ARS',cls:rAR>=0?'pos':'neg',b:null},
    {l:'Resultado UY',v:fv(rUY),s:'neto UYU',cls:rUY>=0?'pos':'neg',b:null},
  ].map(k=>`<div class="kpi"><div class="klbl">${k.l}</div><div class="kval ${k.cls||''}">${k.v}</div><div class="ksub">${k.s}</div>${k.b!==null?`<div style="font-size:10px;margin-top:4px;color:${k.b>=0?'var(--g)':'var(--r)'}">${fp(k.b)} Ene→${M[lastM]}</div>`:''}</div>`).join('');
}

function renderDashTables(){ renderDTables(); }

function renderDTables(){
  // Only show months that have data
  let maxM=0;
  for(let m=11;m>=0;m--){ if(arFac(m)>0||uyFac(m)>0||usdFac(m)>0){maxM=m;break;} }
  const VM=maxM+1; // number of visible months
  const tbl=(rows,cur)=>`<div class="card"><div class="tw"><table><thead><tr><th>${cur}</th>${M.slice(0,VM).map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>${
    rows.map(r=>{
      const cls=typeof r.cls==='function'?r.cls():(r.cls||'');
      const cells=M.slice(0,VM).map((_,m)=>`<td>${r.fmt?r.fmt(r.fn(m)):f(r.fn(m))}</td>`).join('');
      const tot=M.slice(0,VM).reduce((a,_,m)=>a+r.fn(m),0);
      return `<tr class="${cls}"><td>${r.l}</td>${cells}<td>${r.fmt?r.fmt(tot):f(tot)}</td></tr>`;
    }).join('')
  }</tbody></table></div></div>`;
  const resClsAR=()=>{ let t=0; for(let m=0;m<VM;m++) t+=arRes(m); return t>=0?'tr-pos':'tr-neg'; };
  const resClsUY=()=>{ let t=0; for(let m=0;m<VM;m++) t+=uyRes(m); return t>=0?'tr-pos':'tr-neg'; };
  const resClsUSD=()=>{ let t=0; for(let m=0;m<VM;m++) t+=usdRes(m); return t>=0?'tr-pos':'tr-neg'; };
  document.getElementById('d-tables').innerHTML=
    '<div class="stitle">Argentina (ARS)</div>'+tbl([
      {l:'Facturación',fn:arFac},
      {l:'Gastos',fn:arGas},
      {l:'Resultado',fn:arRes,cls:resClsAR},
      {l:'Margen %',fn:m=>arFac(m)>0?arRes(m)/arFac(m)*100:0,fmt:v=>v.toFixed(1)+'%'},
      {l:'Variación m/m %',fn:m=>m===0?0:arFac(m-1)>0?(arFac(m)-arFac(m-1))/arFac(m-1)*100:0,fmt:fp},
    ],'ARS')+
    '<div class="stitle">Uruguay UYU</div>'+tbl([
      {l:'Facturación total',fn:uyFac},
      {l:'MP UY',fn:m=>D.uy_mp[m]},
      {l:'Alianzas',fn:m=>D.uy_ali[m]},
      {l:'Talleres',fn:m=>D.uy_tall[m]},
      {l:'Gastos',fn:uyGas},
      {l:'Resultado',fn:uyRes,cls:resClsUY},
      {l:'Variación m/m %',fn:m=>m===0?0:uyFac(m-1)>0?(uyFac(m)-uyFac(m-1))/uyFac(m-1)*100:0,fmt:fp},
    ],'UYU')+
    '<div class="stitle">Uruguay USD</div>'+tbl([
      {l:'PayPal UY',fn:usdFac},
      {l:'Gastos USD',fn:usdGas},
      {l:'Resultado USD',fn:usdRes,cls:resClsUSD},
      {l:'Variación m/m %',fn:m=>m===0?0:usdFac(m-1)>0?(usdFac(m)-usdFac(m-1))/usdFac(m-1)*100:0,fmt:fp},
    ],'USD');
}

// ── INPUT HELPER ──────────────────────────────────────────────────────────
function inp(val, path, est, country){
  const converted = country && dolarOn[country] ? Math.round((val||0)/TC[country]) : null;
  const displayVal = converted !== null ? converted : Math.round(val||0);
  const displayColor = est ? 'var(--am)' : (converted!==null ? 'var(--b)' : 'var(--tx)');
  return `<td style="padding:0;background:${est?'var(--amb)':converted!==null?'var(--bb)':''}" class="${est?'est-cell':''}">
    <input type="number" step="1" value="${displayVal}" style="color:${displayColor}" 
     onchange="${path}=parseFloat(this.value)${converted!==null?'*'+TC[country]:''};markDirty();refresh()">
    ${converted!==null?'<div style=\"font-size:9px;color:var(--mu2);text-align:right;padding:0 4px\">ARS</div>':''}
  </td>`;
}

function paidKey(cat, name){ return cat+'__'+name; }
function isPaid(cat, name){ return !!(D.paid && D.paid[paidKey(cat,name)]); }
function togglePaid(cat, name, rowId){
  if(!D.paid) D.paid={};
  D.paid[paidKey(cat,name)] = !D.paid[paidKey(cat,name)];
  const tr=document.getElementById(rowId);
  if(tr){ if(D.paid[paidKey(cat,name)]) tr.classList.add('tr-paid'); else tr.classList.remove('tr-paid'); }
  saveD();
}
function paidCell(cat, name, rowId){
  const pd=isPaid(cat,name);
  return `<td style="text-align:center;padding:4px"><input type="checkbox" class="paid-cb" ${pd?'checked':''} onchange="togglePaid('${cat}','${name}','${rowId}')"></td>`;
}

// ── PAID CELL PER MONTH ───────────────────────────────────────────────────
function paidKeyM(cat, name, m){ return cat+'__'+name+'__'+m; }
function isPaidM(cat, name, m){ return !!(D.paid && D.paid[paidKeyM(cat,name,m)]); }
function togglePaidM(cat, name, m, cellId){
  if(!D.paid) D.paid={};
  const k=paidKeyM(cat,name,m);
  D.paid[k]=!D.paid[k];
  const td=document.getElementById(cellId);
  if(td) td.style.background=D.paid[k]?'var(--gb)':'';
  saveD();
}
function paidCellM(cat, name, m){
  const k=paidKeyM(cat,name,m);
  const pd=isPaidM(cat,name,m);
  const cid='pc-'+cat+'-'+name.replace(/[^a-z0-9]/gi,'_')+'-'+m;
  return `<td id="${cid}" style="padding:2px 4px;text-align:center;background:${pd?'var(--gb)':''};border-bottom:1px solid var(--brd)"><input type="checkbox" class="paid-cb" ${pd?'checked':''} onchange="togglePaidM('${cat}','${name}',${m},'${cid}')"></td>`;
}

// inpWithPaid: input + checkbox in SAME td
function inpWithPaid(val, path, cat, name, m, est){
  const k=paidKeyM(cat,name,m);
  const pd=isPaidM(cat,name,m);
  const cid='pc-'+cat+'-'+name.replace(/[^a-z0-9]/gi,'_')+'-'+m;
  const color=pd?'var(--g)':est?'var(--am)':'var(--tx)';
  const bg=pd?'var(--gb)':est?'var(--amb)':'';
  return `<td id="${cid}" style="padding:0;background:${bg}">
    <input type="number" step="1" value="${Math.round(val||0)}" style="color:${color};width:100%;background:transparent;border:none;text-align:right;font-size:12px;font-family:'DM Mono',monospace;padding:3px 4px 0;outline:none" onchange="${path}=parseFloat(this.value)||0;markDirty();refresh()">
    <div style="text-align:center;padding:0 2px 2px"><input type="checkbox" class="paid-cb" style="width:11px;height:11px" ${pd?'checked':''} onchange="togglePaidM('${cat}','${name}',${m},'${cid}')"></div>
  </td>`;
}

// ── RENDER AR ─────────────────────────────────────────────────────────────
function renderAR(){
  const IVA_P=4286517/39053300, IIBB_P=269299/53345300;
  const arDol=dolarOn['ar'];
  let h=`<div class="ph"><h1>Argentina <span style="color:var(--ar);font-family:'DM Mono',monospace;font-size:13px">${arDol?'USD':'ARS'} · 2026</span></h1><p>Celdas naranja = estimación por % histórico</p></div>`;
  h+=`<button class="dolar-btn ${arDol?'on':''}" id="dbtn-ar" onclick="toggleDolar('ar')">💵 ${arDol?'Viendo en USD':'Ver en USD'} <span class="dolar-pill">TC $1.450</span></button>`;
  h+=`<div class="info">Celdas con fondo naranja son estimaciones automáticas. Reemplazalas cuando llegue el dato real.</div>`;
  h+=`<div class="card"><div class="saldo-row"><label>Saldo inicial caja Enero (ARS):</label><input class="saldo-inp" type="number" value="${D.ar_saldo_ini||0}" onchange="D.ar_saldo_ini=parseFloat(this.value)||0;markDirty();refresh()"></div></div>`;

  // Facturación
  h+=`<div class="stitle">Facturación</div><div class="card"><div class="tw"><table><thead><tr><th>Canal</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  h+=`<tr><td>Mercado Pago AR</td>${M.map((_,m)=>inp(D.ar_mp[m], `D.ar_mp[${m}]`, false, 'ar')).join('')}<td>${f(rowS(D.ar_mp))}</td></tr>`;
  h+=`<tr><td style="color:var(--mu2);font-size:11px">Variación m/m</td>${M.map((_,m)=>{const v=m===0?null:(D.ar_mp[m-1]>0?(D.ar_mp[m]-D.ar_mp[m-1])/D.ar_mp[m-1]*100:null);return `<td style="color:${v===null?'var(--mu2)':v>=0?'var(--g)':'var(--r)'};font-size:11px">${v===null?'—':fp(v)}</td>`;}).join('')}<td></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Meta mensual</td>${M.map((_,m)=>inp(D.ar_metas[m], `D.ar_metas[${m}]`, false, 'ar')).join('')}<td></td></tr>`;
  h+=`<tr class="tr-tot"><td>% Cumplimiento</td>${M.map((_,m)=>`<td>${D.ar_metas[m]>0?((arFac(m)/D.ar_metas[m])*100).toFixed(0)+'%':'—'}</td>`).join('')}<td></td></tr>`;
  h+=`</tbody></table></div></div>`;

  // Honorarios
  h+=`<div class="stitle">Honorarios psicólogos</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  h+=`<tr><td>Honorarios psicólogos</td>${M.map((_,m)=>inpWithPaid(D.ar_hon[m], `D.ar_hon[${m}]`, 'ar_hon', 'Honorarios', m, false)).join('')}<td>${fWithUSD(rowS(D.ar_hon),1450)}</td></tr>`;
  h+=`</tbody></table></div></div>`;

  // Sueldos
  h+=`<div class="stitle">Sueldos</div><div class="card"><div class="tw"><table><thead><tr><th>Persona</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>✓</th></tr></thead><tbody>`;
  Object.entries(D.ar_sueldos).forEach(([n,v],i)=>{
    const rid='tr-ar-s'+i; const pd=isPaid('ar_sue',n);
    h+=`<tr id="${rid}" class="${pd?'tr-paid':''}"><td>${n}</td>${M.map((_,m)=>{const path=`D.ar_sueldos['${n}'][${m}]`; return inp(v[m],path);}).join('')}<td>${f(rowS(v))}</td>${paidCell('ar_sue',n,rid)}</tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total sueldos</td>${M.map((_,m)=>`<td>${f(sumO(D.ar_sueldos,m))}</td>`).join('')}<td>${f(M.reduce((a,_,m)=>a+sumO(D.ar_sueldos,m),0))}<div style="font-size:9px;color:var(--b);font-family:'DM Mono',monospace">U$D ${f(M.reduce((a,_,m)=>a+sumO(D.ar_sueldos,m),0)/1450)}</div></td><td></td></tr>`;
  h+=`</tbody></table></div></div>`;

  // Servicios
  h+=`<div class="stitle">Servicios y costo financiero</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.ar_servicios).forEach(([n,v])=>{
    h+=`<tr><td>${n}</td>${M.map((_,m)=>inpWithPaid(v[m], `D.ar_servicios['${n}'][${m}]`, 'ar_srv', n, m, false)).join('')}<td>${f(rowS(v))}</td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total servicios</td>${M.map((_,m)=>`<td>${f(sumO(D.ar_servicios,m))}</td>`).join('')}<td>${fWithUSD(M.reduce((a,_,m)=>a+sumO(D.ar_servicios,m),0),1450)}</td></tr>`;
  h+=`</tbody></table></div></div>`;

  // Impositiva
  h+=`<div class="stitle">Impositiva y cargas sociales</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.ar_impositiva).forEach(([n,v])=>{
    const isIVA=n==='IVA', isIIBB=n==='Ingresos Brutos';
    h+=`<tr><td>${n}</td>${M.map((_,m)=>{
      const fp_=m>0?arFac(m-1):arFac(0);
      const est=(isIVA&&m>=2&&v[m]===0)||(isIIBB&&m>=2&&v[m]===0);
      const dv=est?(isIVA?fp_*IVA_P:fp_*IIBB_P):v[m];
      return inpWithPaid(dv, `D.ar_impositiva['${n}'][${m}]`, 'ar_imp', n, m, est);
    }).join('')}<td>${fWithUSD(rowS(v),1450)}</td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total impositiva</td>${M.map((_,m)=>`<td>${f(sumO(D.ar_impositiva,m))}</td>`).join('')}<td>${fWithUSD(M.reduce((a,_,m)=>a+sumO(D.ar_impositiva,m),0),1450)}</td></tr>`;
  h+=`</tbody></table></div></div>`;

  // Resultado
  h+=`<div class="stitle">Resultado y cashflow</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  const rAR=M.reduce((a,_,m)=>a+arRes(m),0);
  h+=`<tr class="${rAR>=0?'tr-pos':'tr-neg'}"><td>Resultado neto</td>${M.map((_,m)=>`<td>${fv(arRes(m))}</td>`).join('')}<td>${fv(rAR)}<div style="font-size:9px;color:var(--b);font-family:'DM Mono',monospace;margin-top:1px">≈ U$D ${f(rAR/1450)}</div></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Margen %</td>${M.map((_,m)=>`<td>${arFac(m)>0?((arRes(m)/arFac(m))*100).toFixed(1)+'%':'—'}</td>`).join('')}<td></td></tr>`;
  const cfA=cfAR(); h+=`<tr><td style="color:var(--mu2)">Caja disponible</td>${M.map((_,m)=>`<td>${f(cfA[m])}</td>`).join('')}<td></td></tr>`;
  h+=`</tbody></table></div></div>`;

  document.getElementById('ar-wrap').innerHTML=h;
  // restore paid states
  Object.entries(D.ar_sueldos).forEach(([n],i)=>{
    const rid='tr-ar-s'+i;
    if(isPaid('ar_sue',n)) document.getElementById(rid)&&document.getElementById(rid).classList.add('tr-paid');
  });
}

// ── RENDER UYU ────────────────────────────────────────────────────────────
function renderUYU(){
  const BPS_P=137033/3192209,IVA_P=48819/3192209,IP_P=1403/3192209,IRAE_P=115589/3192209;
  const estFrom={BPS:3,IVA:2,'Anticipo IP':2,'Anticipo IRAE':2};
  const pcts={BPS:BPS_P,IVA:IVA_P,'Anticipo IP':IP_P,'Anticipo IRAE':IRAE_P};
  const uyDol=dolarOn['uy'];
  let h=`<div class="ph"><h1>Uruguay UYU <span style="color:var(--uy);font-family:'DM Mono',monospace;font-size:13px">${uyDol?'USD':'UYU'} · 2026</span></h1><p>MP UY · Alianzas · Talleres · Gastos en pesos uruguayos</p></div>`;
  h+=`<button class="dolar-btn ${uyDol?'on':''}" id="dbtn-uy" onclick="toggleDolar('uy')">💵 ${uyDol?'Viendo en USD':'Ver en USD'} <span class="dolar-pill">TC $40</span></button>`;
  h+=`<div class="card"><div class="saldo-row"><label>Saldo inicial caja Enero (UYU):</label><input class="saldo-inp" type="number" value="${D.uy_saldo_ini||0}" onchange="D.uy_saldo_ini=parseFloat(this.value)||0;markDirty();refresh()"></div></div>`;

  h+=`<div class="stitle">Facturación UYU</div><div class="card"><div class="tw"><table><thead><tr><th>Canal</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>%</th></tr></thead><tbody>`;
  [['Mercado Pago UY','uy_mp'],['Alianzas','uy_ali'],['Talleres','uy_tall']].forEach(([n,k])=>{
    const tot=rowS(D[k]); const grand=M.reduce((a,_,m)=>a+uyFac(m),0);
    h+=`<tr><td>${n}</td>${M.map((_,m)=>inp(D[k][m], `D.${k}[${m}]`, false, 'uy')).join('')}<td>${f(tot)}</td><td>${grand>0?(tot/grand*100).toFixed(1)+'%':'—'}</td></tr>`;
    h+=`<tr><td style="color:var(--mu2);font-size:11px;padding-left:12px">↳ var. m/m</td>${M.map((_,m)=>{const v=m===0?null:(D[k][m-1]>0?(D[k][m]-D[k][m-1])/D[k][m-1]*100:null);return `<td style="color:${v===null?'var(--mu2)':v>=0?'var(--g)':'var(--r)'};font-size:11px">${v===null?'—':fp(v)}</td>`;}).join('')}<td></td><td></td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total facturación UYU</td>${M.map((_,m)=>`<td>${f(uyFac(m))}</td>`).join('')}<td>${fWithUSD(M.reduce((a,_,m)=>a+uyFac(m),0),40)}</td><td>100%</td></tr>`;
  h+=`<tr><td style="color:var(--mu2);font-size:11px;padding-left:12px">↳ var. m/m total</td>${M.map((_,m)=>{const v=m===0?null:(uyFac(m-1)>0?(uyFac(m)-uyFac(m-1))/uyFac(m-1)*100:null);return `<td style="color:${v===null?'var(--mu2)':v>=0?'var(--g)':'var(--r)'};font-size:11px;font-weight:500">${v===null?'—':fp(v)}</td>`;}).join('')}<td></td><td></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Variación m/m</td>${M.map((_,m)=>`<td style="color:${m===0?'var(--mu2)':uyFac(m)>=uyFac(Math.max(0,m-1))?'var(--g)':'var(--r)'}">${m===0?'—':fp(uyFac(m-1)>0?(uyFac(m)-uyFac(m-1))/uyFac(m-1)*100:0)}</td>`).join('')}<td></td><td></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Meta mensual</td>${M.map((_,m)=>inp(D.uy_metas[m], `D.uy_metas[${m}]`, false, 'uy')).join('')}<td></td><td></td></tr>`;
  h+=`</tbody></table></div></div>`;

  h+=`<div class="stitle">Honorarios psicólogos</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>✓</th></tr></thead><tbody>`;
  h+=`<tr><td>Honorarios psicólogos</td>${M.map((_,m)=>inp(D.uy_hon[m], `D.uy_hon[${m}]`, false, 'uy')).join('')}<td>${f(rowS(D.uy_hon))}</td>${paidCell('uy_hon','honorarios','tr-uy-hon')}</tr>`;
  h+=`</tbody></table></div></div>`;

  h+=`<div class="stitle">Sueldos</div><div class="card"><div class="tw"><table><thead><tr><th>Persona</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>✓</th></tr></thead><tbody>`;
  Object.entries(D.uy_sueldos).forEach(([n,v],i)=>{
    const rid='tr-uy-s'+i; const pd=isPaid('uy_sue',n);
    h+=`<tr id="${rid}" class="${pd?'tr-paid':''}"><td>${n}</td>${M.map((_,m)=>inp(v[m], `D.uy_sueldos['${n}'][${m}]`, false, 'uy')).join('')}<td>${f(rowS(v))}</td>${paidCell('uy_sue',n,rid)}</tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total sueldos</td>${M.map((_,m)=>`<td>${f(sumO(D.uy_sueldos,m))}</td>`).join('')}<td>${fWithUSD(M.reduce((a,_,m)=>a+sumO(D.uy_sueldos,m),0),40)}</td><td></td></tr>`;
  h+=`</tbody></table></div></div>`;

  h+=`<div class="stitle">Servicios y marketing</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.uy_servicios).forEach(([n,v])=>{
    h+=`<tr><td>${n}</td>${M.map((_,m)=>inpWithPaid(v[m], `D.uy_servicios['${n}'][${m}]`, 'uy_srv', n, m, false)).join('')}<td>${f(rowS(v))}</td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total servicios</td>${M.map((_,m)=>`<td>${f(sumO(D.uy_servicios,m))}</td>`).join('')}<td>${fWithUSD(M.reduce((a,_,m)=>a+sumO(D.uy_servicios,m),0),40)}</td></tr>`;
  h+=`</tbody></table></div></div>`;

  h+=`<div class="stitle">Impositiva</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${M[m]}<br><small style="font-size:9px;color:var(--mu2)">✓</small></th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.uy_impositiva).forEach(([n,v])=>{
    h+=`<tr><td>${n}</td>${M.map((_,m)=>{
      const est=pcts[n]&&m>=(estFrom[n]||99)&&v[m]===0;
      const dv=est?uyFac(m)*pcts[n]:v[m];
      return inpWithPaid(dv, `D.uy_impositiva['${n}'][${m}]`, 'uy_imp', n, m, est);
    }).join('')}<td>${f(rowS(v))}</td></tr>`;
  });
  h+=`</tbody></table></div></div>`;

  h+=`<div class="stitle">Otros gastos</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.uy_otros).forEach(([n,v])=>{
    h+=`<tr><td>${n}</td>${M.map((_,m)=>inp(v[m], `D.uy_otros['${n}'][${m}]`, false, 'uy')).join('')}<td>${f(rowS(v))}</td></tr>`;
  });
  h+=`</tbody></table></div></div>`;

  const rUY=M.reduce((a,_,m)=>a+uyRes(m),0);
  h+=`<div class="stitle">Resultado y cashflow</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  h+=`<tr class="${rUY>=0?'tr-pos':'tr-neg'}"><td>Resultado neto</td>${M.map((_,m)=>`<td>${fv(uyRes(m))}</td>`).join('')}<td>${fv(rUY)}</td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Margen %</td>${M.map((_,m)=>`<td>${uyFac(m)>0?((uyRes(m)/uyFac(m))*100).toFixed(1)+'%':'—'}</td>`).join('')}<td></td></tr>`;
  const cfU=cfUY(); h+=`<tr><td style="color:var(--mu2)">Caja disponible</td>${M.map((_,m)=>`<td>${f(cfU[m])}</td>`).join('')}<td></td></tr>`;
  h+=`</tbody></table></div></div>`;
  document.getElementById('uyu-wrap').innerHTML=h;
}

// ── RENDER USD ────────────────────────────────────────────────────────────
function renderUSD(){
  let h=`<div class="ph"><h1>Uruguay USD <span style="color:var(--usd);font-family:'DM Mono',monospace;font-size:13px">2026</span></h1><p>PayPal UY · Gastos en dólares</p></div>`;
  h+=`<div class="card"><div class="saldo-row"><label>Saldo inicial caja Enero (USD):</label><input class="saldo-inp" type="number" value="${D.usd_saldo_ini||0}" onchange="D.usd_saldo_ini=parseFloat(this.value)||0;markDirty();refresh()"></div></div>`;
  h+=`<div class="stitle">Facturación USD — PayPal UY</div><div class="card"><div class="tw"><table><thead><tr><th>Canal</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  h+=`<tr><td>PayPal UY</td>${M.map((_,m)=>inp(D.usd_pp[m],`D.usd_pp[${m}]`)).join('')}<td>${f(rowS(D.usd_pp))}</td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Variación m/m</td>${M.map((_,m)=>`<td style="color:${m===0?'var(--mu2)':usdFac(m)>=usdFac(Math.max(0,m-1))?'var(--g)':'var(--r)'}">${m===0?'—':fp(usdFac(m-1)>0?(usdFac(m)-usdFac(m-1))/usdFac(m-1)*100:0)}</td>`).join('')}<td></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Meta mensual</td>${M.map((_,m)=>inp(D.usd_metas[m],`D.usd_metas[${m}]`)).join('')}<td></td></tr>`;
  h+=`</tbody></table></div></div>`;
  h+=`<div class="stitle">Gastos USD</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  Object.entries(D.usd_gastos).forEach(([n,v])=>{
    h+=`<tr><td>${n}</td>${M.map((_,m)=>inpWithPaid(v[m], `D.usd_gastos['${n}'][${m}]`, 'usd_gas', n, m, false)).join('')}<td>${f(rowS(v))}</td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>Total gastos</td>${M.map((_,m)=>`<td>${f(usdGas(m))}</td>`).join('')}<td>${f(M.reduce((a,_,m)=>a+usdGas(m),0))}</td></tr>`;
  h+=`</tbody></table></div></div>`;
  const rUSD=M.reduce((a,_,m)=>a+usdRes(m),0);
  h+=`<div class="stitle">Resultado y cashflow USD</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th></tr></thead><tbody>`;
  h+=`<tr class="${rUSD>=0?'tr-pos':'tr-neg'}"><td>Resultado neto USD</td>${M.map((_,m)=>`<td>${fv(usdRes(m))}</td>`).join('')}<td>${fv(rUSD)}</td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Margen %</td>${M.map((_,m)=>`<td>${usdFac(m)>0?((usdRes(m)/usdFac(m))*100).toFixed(1)+'%':'—'}</td>`).join('')}<td></td></tr>`;
  const cfUs=cfUSD(); h+=`<tr><td style="color:var(--mu2)">Caja disponible</td>${M.map((_,m)=>`<td>${f(cfUs[m])}</td>`).join('')}<td></td></tr>`;
  h+=`</tbody></table></div></div>`;
  document.getElementById('usd-wrap').innerHTML=h;
}

// ── RENDER ALIANZAS ───────────────────────────────────────────────────────
function renderAlianzas(){
  // Dynamic months
  const aliMs=[]; for(let m=0;m<12;m++) if(aliFac(m)>0) aliMs.push(m);
  let h=`<div class="ph"><h1>Alianzas empresariales <span style="color:var(--ali);font-family:'DM Mono',monospace;font-size:13px">Uruguay · UYU · 2026</span></h1><p>Fee mensual por empresa · análisis mes a mes</p></div>`;
  h+=`<button class="dolar-btn ${dolarOn['ali']?'on':''}" id="dbtn-ali" onclick="dolarOn['ali']=!dolarOn['ali'];renderAlianzas()" style="margin-bottom:14px">💵 ${dolarOn['ali']?'Viendo en USD':'Ver en USD'} <span class="dolar-pill">TC $40</span></button>`;
  const TC_ALI=40;
  const fali=(v)=>dolarOn['ali']?'U$D '+f(v/TC_ALI):'$ '+f(v);
  h+=`<div class="kpis" style="margin-bottom:20px">`;
  aliMs.forEach((m,i)=>{
    const v=aliFac(m), prev=i>0?aliFac(aliMs[i-1]):null;
    const pct=prev&&prev>0?(v-prev)/prev*100:null;
    h+=`<div class="kpi"><div class="klbl">Total ${M[m]}</div><div class="kval" style="color:var(--ali)">${fali(v)}</div>${pct!==null?`<div class="ksub" style="color:${pct>=0?'var(--g)':'var(--r)'}">${fp(pct)} vs ${M[aliMs[i-1]]}</div>`:''}</div>`;
  });
  const acum=aliMs.reduce((a,m)=>a+aliFac(m),0);
  const acumLbl=aliMs.length>0?(aliMs.length>1?M[aliMs[0]]+'–'+M[aliMs[aliMs.length-1]]:M[aliMs[0]]):'—';
  const activeCount=Object.values(D.ali).filter(v=>aliMs.some(m=>v[m]>0)).length;
  h+=`<div class="kpi"><div class="klbl">Acumulado ${acumLbl}</div><div class="kval" style="color:var(--ali)">${fali(acum)}</div><div class="ksub">${activeCount} empresas activas</div></div></div>`;
  const grandTot=acum;
  h+=`<div class="stitle">Fee mensual por empresa</div><div class="card"><div class="tw"><table>
  <thead><tr><th>Empresa</th>${M.map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>Var Ene→Mar</th></tr></thead><tbody>`;
  const FEE_FIJO=new Set(['Kinko','AXO (SISI)','Vesta Hub','Genexus','Greycon','Uruware','Nodum','Datalogic','Fraylog','Farmashop']);
  Object.entries(D.ali).sort((a,b)=>rowS(b[1])-rowS(a[1])).forEach(([n,v])=>{
    const tot=rowS(v);
    const showVar=!FEE_FIJO.has(n);
    // Last month with data for overall variation
    const lastM=v.reduce((a,x,i)=>x>0?i:a,-1);
    const overallVar=showVar&&v[0]>0&&lastM>0?(v[lastM]-v[0])/v[0]*100:null;
    const cells=M.map((_,m)=>{
      const val=v[m]||0;
      const prev=m>0?v[m-1]:null;
      const pct=showVar&&prev!==null&&prev>0&&val>0?(val-prev)/prev*100:null;
      return `<td style="padding:0"><input type="number" step="1" value="${Math.round(val)}" onchange="D.ali['${n}'][${m}]=parseFloat(this.value)||0;markDirty();refresh()" style="width:100%;background:transparent;border:none;text-align:right;font-size:12px;font-family:'DM Mono',monospace;padding:${pct!==null?'2px':'4px'} 4px 0;outline:none">${pct!==null?`<div style="font-size:9px;color:${pct>=0?'var(--g)':'var(--r)'};text-align:right;padding:0 4px 2px;font-weight:500">${fp(pct)}</div>`:''}</td>`;
    }).join('');
    h+=`<tr style="${tot===0?'opacity:.4':''}"><td style="font-weight:500">${n}${!showVar?' <span style="font-size:9px;color:var(--mu2)">·fijo</span>':''}</td>${cells}<td style="font-weight:500">${f(tot)}</td><td style="color:${overallVar===null?'var(--mu2)':overallVar>=0?'var(--g)':'var(--r)'}">${overallVar===null?'—':fp(overallVar)}</td></tr>`;
    // Cupones row
    if(!D.ali_cupones) D.ali_cupones={};
    if(!D.ali_cupones[n]) D.ali_cupones[n]=[0,0,0,0,0,0,0,0,0,0,0,0];
    const cups=D.ali_cupones[n];
    const totCups=rowS(cups);
    const cupCells=M.map((_,m)=>`<td style="padding:0;background:var(--pub)"><input type="number" step="1" value="${Math.round(cups[m]||0)}" onchange="if(!D.ali_cupones)D.ali_cupones={};if(!D.ali_cupones['${n}'])D.ali_cupones['${n}']=[0,0,0,0,0,0,0,0,0,0,0,0];D.ali_cupones['${n}'][${m}]=parseFloat(this.value)||0;markDirty();refresh()" style="width:100%;background:transparent;border:none;text-align:right;font-size:11px;font-family:'DM Mono',monospace;padding:3px 4px;outline:none;color:var(--pu)"></td>`).join('');
    h+=`<tr style="${tot===0?'opacity:.35':''}"><td style="font-size:11px;color:var(--pu);padding-left:16px">↳ Paciente</td>${cupCells}<td style="font-size:11px;color:var(--pu);font-style:italic">${totCups>0?f(totCups):'—'}</td><td></td></tr>`;
    // Total row: empresa + paciente
    const totalCells=M.map((_,m)=>{
      const sum=(v[m]||0)+(cups[m]||0);
      return `<td style="background:var(--bg);font-weight:500;font-size:11px;color:var(--tx);border-top:1px solid var(--brd);padding:3px 4px">${sum>0?f(sum):'—'}</td>`;
    }).join('');
    const grandTotal=tot+totCups;
    h+=`<tr style="${grandTotal===0?'opacity:.35':''};border-bottom:2px solid var(--brd2)"><td style="font-size:11px;font-weight:500;padding-left:16px;background:var(--bg);border-top:1px solid var(--brd)">↳ TOTAL (empresa + paciente)</td>${totalCells}<td style="background:var(--bg);font-weight:600;font-size:11px;color:var(--tx);border-top:1px solid var(--brd)">${grandTotal>0?f(grandTotal):'—'}</td><td style="background:var(--bg);border-top:1px solid var(--brd)"></td></tr>`;
  });
  const allTots=M.map((_,m)=>aliFac(m));
  h+=`<tr class="tr-tot"><td>TOTAL</td>${allTots.map(v=>`<td>${f(v)}</td>`).join('')}<td>${f(allTots.reduce((a,b)=>a+b,0))}</td><td></td></tr>`;
  h+=`<tr><td style="color:var(--mu2)">Variación m/m</td>${allTots.map((v,m)=>`<td style="color:${m===0?'var(--mu2)':v>=(allTots[m-1]||0)?'var(--g)':'var(--r)'}">${m===0?'—':fp(allTots[m-1]>0?(v-allTots[m-1])/allTots[m-1]*100:0)}</td>`).join('')}<td></td><td></td></tr>`;
  h+=`</tbody></table></div></div>`;
  document.getElementById('ali-wrap').innerHTML=h;
}

// ── RENDER PARTICIPACION ──────────────────────────────────────────────────
function renderParticipacion(){
  const TC_AR=1450, TC_UY=40;
  const segs=[
    {n:'Argentina MP AR',fn:m=>D.ar_mp[m]/TC_AR,c:'#0070f3'},
    {n:'UY — MP UY',fn:m=>D.uy_mp[m]/TC_UY,c:'#00a846'},
    {n:'UY — Alianzas',fn:m=>D.uy_ali[m]/TC_UY,c:'#34d399'},
    {n:'UY — Talleres',fn:m=>D.uy_tall[m]/TC_UY,c:'#6ee7b7'},
    {n:'PayPal UY',fn:m=>D.usd_pp[m],c:'#7c3aed'},
  ];
  const grand=segs.reduce((a,s)=>a+[0,1,2].reduce((x,m)=>x+s.fn(m),0),0);
  const segTots=segs.map(s=>[0,1,2].reduce((a,m)=>a+s.fn(m),0));
  let h=`<div class="ph"><h1>Participación por país y canal</h1><p>Distribución en USD · TC AR $1.450 · TC UY $40</p></div>`;
  h+=`<div class="card" style="padding:20px"><div class="part-bar">`;
  segs.forEach((s,i)=>{
    const pct=grand>0?segTots[i]/grand*100:0;
    if(pct<0.5) return;
    h+=`<div class="part-seg" style="width:${pct.toFixed(1)}%;background:${s.c}" title="${s.n}: ${pct.toFixed(1)}%">${pct>=5?pct.toFixed(1)+'%':''}</div>`;
  });
  h+=`</div><div style="display:flex;flex-wrap:wrap;gap:10px;margin-bottom:12px">`;
  segs.forEach((s,i)=>{
    const pct=grand>0?segTots[i]/grand*100:0;
    h+=`<div style="display:flex;align-items:center;gap:6px;font-size:12px"><div style="width:10px;height:10px;border-radius:3px;background:${s.c}"></div>${s.n} <strong style="font-family:'DM Mono',monospace">${pct.toFixed(1)}%</strong> <span style="color:var(--mu2);font-size:11px">U$D ${f(segTots[i])}</span></div>`;
  });
  h+=`</div><div style="text-align:right;font-size:12px;color:var(--mu)">Total empresa Ene–Mar: <strong style="font-size:15px;font-family:'DM Mono',monospace">U$D ${f(grand)}</strong></div></div>`;
  h+=`<div class="stitle">Mes a mes (USD)</div><div class="card"><div class="tw"><table><thead><tr><th>Canal</th>${['Ene','Feb','Mar'].map(m=>`<th>${m}</th>`).join('')}<th>Total</th><th>%</th></tr></thead><tbody>`;
  segs.forEach((s,i)=>{
    h+=`<tr><td><span style="display:inline-block;width:8px;height:8px;border-radius:2px;background:${s.c};margin-right:6px"></span>${s.n}</td>${[0,1,2].map(m=>`<td>U$D ${f(s.fn(m))}</td>`).join('')}<td style="font-weight:500">U$D ${f(segTots[i])}</td><td style="color:${s.c};font-weight:500">${grand>0?(segTots[i]/grand*100).toFixed(1)+'%':'—'}</td></tr>`;
  });
  h+=`<tr class="tr-tot"><td>TOTAL EMPRESA</td>${[0,1,2].map(m=>`<td>U$D ${f(segs.reduce((a,s)=>a+s.fn(m),0))}</td>`).join('')}<td>U$D ${f(grand)}</td><td>100%</td></tr>`;
  h+=`</tbody></table></div></div>`;
  document.getElementById('part-wrap').innerHTML=h;
  // stacked bar chart
  const CID='ch-part'; if(CHS[CID]) CHS[CID].destroy();
  const el=document.createElement('canvas'); el.id=CID;
  const wrap=document.createElement('div'); wrap.style.cssText='background:var(--sur);border:1px solid var(--brd);border-radius:10px;padding:16px;margin-top:14px';
  const title=document.createElement('div'); title.style.cssText='font-size:12px;font-weight:500;margin-bottom:12px'; title.textContent='Composición mensual en USD';
  const cw=document.createElement('div'); cw.style.cssText='height:200px;position:relative';
  cw.appendChild(el); wrap.appendChild(title); wrap.appendChild(cw);
  document.getElementById('part-wrap').appendChild(wrap);
  CHS[CID]=new Chart(el,{type:'bar',data:{labels:['Ene','Feb','Mar'],datasets:segs.map(s=>({label:s.n,data:[0,1,2].map(m=>Math.round(s.fn(m))),backgroundColor:s.c+'cc',borderColor:s.c,borderWidth:1,borderRadius:2}))},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:true,labels:{font:{size:10},boxWidth:8}},tooltip:{callbacks:{label:c=>`${c.dataset.label}: U$D ${f(c.raw)}`}}},scales:{x:{stacked:true,grid:{display:false},ticks:{font:{size:10}}},y:{stacked:true,grid:{color:'rgba(0,0,0,.04)'},ticks:{font:{size:10},callback:v=>'U$D '+f(v)}}}}});
}

// ── RENDER PROYECCIONES ───────────────────────────────────────────────────
function renderProjections(){
  // ── Statistical projection engine ──────────────────────────────────────
  // Uses median growth rate (robust to outliers) + std dev confidence intervals
  // Base rate capped at realistic maximums to avoid first-month distortion

  function median(arr){
    if(!arr.length) return 0;
    const s=[...arr].sort((a,b)=>a-b);
    const mid=Math.floor(s.length/2);
    return s.length%2?s[mid]:(s[mid-1]+s[mid])/2;
  }
  function mean(a){ return a.length?a.reduce((x,y)=>x+y,0)/a.length:0; }
  function stddev(a){
    if(a.length<2) return 0;
    const m=mean(a);
    return Math.sqrt(a.reduce((x,y)=>x+(y-m)**2,0)/(a.length-1));
  }
  function monthlyGrowthRates(arr){
    const r=[];
    for(let i=1;i<arr.length;i++) if(arr[i-1]>0&&arr[i]>0) r.push((arr[i]-arr[i-1])/arr[i-1]);
    return r;
  }
  function project(hist, nMonths, g_base, g_std){
    // Cap base rate: realistic monthly growth max 8%, floor -5%
    const g_capped = Math.min(0.08, Math.max(-0.05, g_base));
    // Pessimistic floor: never go below 0% growth (assume flat if trend negative)
    const g_pes_rate = Math.max(-0.03, g_capped - Math.abs(g_std)*1.28);
    const g_opt_rate = g_capped + Math.abs(g_std)*1.28;
    const last = hist[hist.length-1];
    const base=[], opt=[], pes=[];
    let vb=last, vo=last, vp=last;
    for(let i=0;i<nMonths;i++){
      vb = Math.max(last*0.7, vb*(1+g_capped));
      vo = Math.max(vb, vo*(1+g_opt_rate));
      vp = Math.max(last*0.5, vp*(1+g_pes_rate));
      base.push(Math.round(vb));
      opt.push(Math.round(vo));
      pes.push(Math.round(vp));
    }
    return {base, opt, pes, g_used: g_capped, g_opt: g_opt_rate, g_pes: g_pes_rate};
  }

  // Find months with data
  let lastDataM=0; for(let m=11;m>=0;m--){ if(arFac(m)>0){lastDataM=m;break;} }
  const nFut=11-lastDataM;
  const futureM=M.slice(lastDataM+1);

  const series=[
    {name:'Argentina (ARS)', cur:'$', hist:M.slice(0,lastDataM+1).map((_,m)=>arFac(m)).filter(v=>v>0)},
    {name:'Uruguay UYU',     cur:'$', hist:M.slice(0,lastDataM+1).map((_,m)=>uyFac(m)).filter(v=>v>0)},
    {name:'PayPal USD',      cur:'U$D', hist:M.slice(0,lastDataM+1).map((_,m)=>usdFac(m)).filter(v=>v>0)},
  ];

  let h=`<div class="ph"><h1>Proyecciones 2026</h1><p>Metodología estadística · media ponderada + intervalos de confianza 90% · base ${M[0]}–${M[lastDataM]}</p></div>`;

  // Methodology explanation
  h+=`<div style="background:var(--sur);border:1px solid var(--brd);border-radius:10px;padding:16px 20px;margin-bottom:20px;font-size:12px;color:var(--mu);line-height:1.6">
    <strong style="color:var(--tx)">Metodología:</strong> Tasa de crecimiento base = media ponderada de las tasas mensuales reales (más peso a meses recientes). 
    Escenario <strong style="color:var(--g)">optimista</strong> = base + 1.28σ·√t (percentil 90). 
    Escenario <strong style="color:var(--r)">pesimista</strong> = base − 1.28σ·√t (percentil 10). 
    El intervalo se ensancha con el tiempo porque la incertidumbre crece. Con ${lastDataM+1} meses de datos reales el intervalo es ${lastDataM+1>=4?'moderado':'amplio — se estrecha al cargar más meses'}.
  </div>`;

  const esc_grid=`<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;margin-bottom:20px">
    <div style="background:var(--bg);border:1px solid var(--brd2);border-radius:10px;padding:14px"><div style="font-size:11px;font-weight:500;color:var(--mu);text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px">⚖️ Base</div><p style="font-size:12px;color:var(--mu)">Tendencia histórica ponderada. Probabilidad implícita: 50%</p></div>
    <div style="background:var(--gb);border:1px solid var(--gbrd);border-radius:10px;padding:14px"><div style="font-size:11px;font-weight:500;color:var(--g);text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px">🚀 Optimista</div><p style="font-size:12px;color:var(--g)">Percentil 90 — ocurre 1 de cada 10 meses buenos. Nuevas alianzas o pico estacional.</p></div>
    <div style="background:var(--rb);border:1px solid var(--rbrd);border-radius:10px;padding:14px"><div style="font-size:11px;font-weight:500;color:var(--r);text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px">⚠️ Pesimista</div><p style="font-size:12px;color:var(--r)">Percentil 10 — ocurre 1 de cada 10 meses malos. Churn o estacionalidad negativa.</p></div>
  </div>`;
  h+=esc_grid;

  series.forEach(s=>{
    if(s.hist.length<2){ h+=`<div class="stitle">${s.name}</div><div class="card" style="padding:16px;color:var(--mu);font-size:12px">Necesitás al menos 2 meses de datos para proyectar.</div>`; return; }
    const rates=monthlyGrowthRates(s.hist);
    const g_raw=median(rates);
    const g_std=stddev(rates);
    const {base,opt,pes,g_used,g_opt,g_pes}=project(s.hist, nFut, g_raw, g_std);
    const histSum=s.hist.reduce((a,b)=>a+b,0);
    const baseSum=histSum+base.reduce((a,b)=>a+b,0);
    const optSum=histSum+opt.reduce((a,b)=>a+b,0);
    const pesSum=histSum+pes.reduce((a,b)=>a+b,0);
    const histLabels=M.slice(0,s.hist.length);

    h+=`<div class="stitle">${s.name} <span style="font-size:11px;color:var(--mu);font-weight:400">· tasa base ${(g_used*100).toFixed(1)}%/mes · σ ${(g_std*100).toFixed(1)}% · optimista ${(g_opt*100).toFixed(1)}% · pesimista ${(g_pes*100).toFixed(1)}%</span></div>`;
    h+=`<div class="card"><div class="tw"><table>
    <thead><tr><th>Escenario</th>
      ${histLabels.map(m=>`<th style="color:var(--mu2)">${m} ✓</th>`).join('')}
      ${futureM.map(m=>`<th>${m}</th>`).join('')}
      <th>Total año</th><th>Prob.</th>
    </tr></thead><tbody>
    <tr style="color:var(--mu2)"><td>Real</td>${s.hist.map(v=>`<td>${s.cur} ${f(v)}</td>`).join('')}${futureM.map(()=>`<td>—</td>`).join('')}<td>${s.cur} ${f(histSum)}</td><td>—</td></tr>
    <tr><td style="font-weight:500">Base</td>${s.hist.map(()=>`<td style="color:var(--mu2)">—</td>`).join('')}${base.map(v=>`<td>${s.cur} ${f(v)}</td>`).join('')}<td style="font-weight:500">${s.cur} ${f(baseSum)}</td><td style="color:var(--mu)">~50%</td></tr>
    <tr style="color:var(--g)"><td style="font-weight:500">Optimista</td>${s.hist.map(()=>`<td style="color:var(--mu2)">—</td>`).join('')}${opt.map(v=>`<td>${s.cur} ${f(v)}</td>`).join('')}<td style="font-weight:500">${s.cur} ${f(optSum)}</td><td>~10%</td></tr>
    <tr style="color:var(--r)"><td style="font-weight:500">Pesimista</td>${s.hist.map(()=>`<td style="color:var(--mu2)">—</td>`).join('')}${pes.map(v=>`<td>${s.cur} ${f(v)}</td>`).join('')}<td style="font-weight:500">${s.cur} ${f(pesSum)}</td><td>~10%</td></tr>
    </tbody></table></div></div>`;

    // Chart
    const cid='ch-pr-'+s.name.replace(/[^a-z]/gi,'_');
    h+=`<div class="cc" style="margin-bottom:20px"><h3>Proyección ${s.name} — intervalo de confianza 90%</h3><div class="cw" style="height:200px"><canvas id="${cid}"></canvas></div></div>`;
    setTimeout(()=>{
      const ctx=document.getElementById(cid); if(!ctx) return;
      if(CHS[cid]) CHS[cid].destroy();
      const allLabels=[...histLabels,...futureM];
      const histFull=[...s.hist,...Array(nFut).fill(null)];
      const baseFull=[...Array(s.hist.length).fill(null),...base];
      const optFull=[...Array(s.hist.length).fill(null),...opt];
      const pesFull=[...Array(s.hist.length).fill(null),...pes];
      CHS[cid]=new Chart(ctx,{type:'line',data:{labels:allLabels,datasets:[
        {label:'Real',data:histFull,borderColor:'#191815',backgroundColor:'transparent',borderWidth:2.5,pointRadius:4,spanGaps:false},
        {label:'Optimista (p90)',data:optFull,borderColor:'rgba(26,107,60,.5)',backgroundColor:'rgba(26,107,60,.06)',borderWidth:1.5,borderDash:[5,3],pointRadius:2,fill:'+1'},
        {label:'Base',data:baseFull,borderColor:'#1d4ed8',backgroundColor:'rgba(29,78,216,.08)',borderWidth:2,borderDash:[4,2],pointRadius:2,fill:false},
        {label:'Pesimista (p10)',data:pesFull,borderColor:'rgba(185,28,28,.5)',backgroundColor:'rgba(185,28,28,.06)',borderWidth:1.5,borderDash:[5,3],pointRadius:2,fill:false},
      ]},options:{responsive:true,maintainAspectRatio:false,
        plugins:{legend:{display:true,labels:{font:{size:10},boxWidth:8}},tooltip:{callbacks:{label:c=>c.dataset.label+': '+s.cur+' '+f(c.raw)}}},
        scales:{x:{grid:{display:false},ticks:{font:{size:10}}},y:{grid:{color:'rgba(0,0,0,.04)'},ticks:{font:{size:10},callback:v=>s.cur+' '+f(v)}}}}});
    },100);
  });

  document.getElementById('proy-wrap').innerHTML=h;
}
// ── RENDER INVERSIÓN ──────────────────────────────────────────────────────
function renderInversion(){
  const cfU=cfUY(); const saldo=Math.max(0,cfU[2]);
  const opts=[
    {n:'Letras de Regulación Monetaria (LRM) — BCU',t:'Renta fija soberana',d:'Títulos emitidos por el Banco Central en UYU. Plazos 30–365 días. Riesgo mínimo, liquidez alta.',rate:9.5,riesgo:'Muy bajo',liq:'Alta',rec:'a'},
    {n:'Depósito a plazo fijo UYU — BROU',t:'Depósito bancario',d:'Depósito en BROU con tasa fija. Garantizado por el Fondo de Garantía de Depósitos hasta UYU 250.000.',rate:8.5,riesgo:'Muy bajo',liq:'Baja',rec:'a'},
    {n:'Fondo de inversión — AFAP Sura / Republic',t:'Fondo regulado BCU',d:'Invierte en LRM y bonos corporativos locales. Diversificación automática con gestión profesional.',rate:10.2,riesgo:'Bajo–medio',liq:'Media (T+2)',rec:'m'},
    {n:'Bonos corporativos UYU — BVM',t:'Renta fija privada',d:'Bonos de empresas uruguayas (Ancap, UTE, bancos). Mayor retorno que LRM con algo más de riesgo crediticio.',rate:11.5,riesgo:'Medio',liq:'Media',rec:'m'},
    {n:'Cuenta remunerada UYU — Itaú / Santander',t:'Cuenta de ahorro',d:'Remuneración diaria sobre el saldo. Tasa menor pero liquidez inmediata — ideal como colchón.',rate:4.0,riesgo:'Muy bajo',liq:'Inmediata',rec:'m'},
  ];
  let h=`<div class="ph"><h1>Inversión UY <span style="color:var(--uy);font-family:'DM Mono',monospace;font-size:13px">UYU · 2026</span></h1><p>Opciones para el sobrante de caja en pesos uruguayos</p></div>`;
  h+=`<div class="kpis" style="margin-bottom:20px">
    <div class="kpi"><div class="klbl">Saldo disponible UYU</div><div class="kval">$ ${f(saldo)}</div><div class="ksub">Caja acumulada a marzo</div></div>
    <div class="kpi"><div class="klbl">Equivalente USD</div><div class="kval">U$D ${f(saldo/40)}</div><div class="ksub">TC 40 UYU/USD</div></div>
  </div>`;
  h+=`<div class="stitle">Simulador de rendimiento</div><div class="card" style="padding:18px">
    <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;margin-bottom:14px">
      <div><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:4px">Monto (UYU)</label><input type="number" id="inv-m" value="${Math.round(saldo*0.6)}" onchange="calcInv()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:6px 8px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
      <div><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:4px">Plazo (meses)</label><input type="number" id="inv-p" value="6" min="1" max="24" onchange="calcInv()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:6px 8px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
      <div><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:4px">Tasa anual (%)</label><input type="number" id="inv-t" value="9.5" step="0.1" onchange="calcInv()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:6px 8px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
    </div>
    <div id="inv-res" style="background:var(--gb);border:1px solid var(--gbrd);border-radius:8px;padding:12px;font-size:13px"></div>
  </div>`;
  h+=`<div class="info">Tasas referenciales del mercado uruguayo a mayo 2026. Consultá con un asesor regulado por el BCU.</div>`;
  h+=`<div class="stitle">Opciones de inversión</div>`;
  opts.forEach(o=>{
    h+=`<div class="inv-card"><div style="display:flex;justify-content:space-between;gap:12px;align-items:flex-start">
      <div><div style="font-size:13px;font-weight:500;margin-bottom:3px">${o.n}</div><div style="font-size:11px;color:var(--mu2)">${o.t}</div></div>
      <div style="text-align:right;flex-shrink:0"><div class="inv-rate">${o.rate}%</div><div style="font-size:10px;color:var(--mu)">tasa anual ref.</div></div>
    </div>
    <div style="font-size:12px;color:var(--mu);margin:10px 0;line-height:1.5">${o.d}</div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:6px;font-size:12px;margin-bottom:8px">
      <div><span style="color:var(--mu2)">Riesgo:</span> ${o.riesgo}</div>
      <div><span style="color:var(--mu2)">Liquidez:</span> ${o.liq}</div>
      <div><span style="color:var(--mu2)">Retorno estimado/año:</span> <strong style="color:var(--g)">$ ${f(saldo*0.6*o.rate/100)}</strong></div>
    </div>
    <span class="${o.rec==='a'?'rec-a':'rec-m'}">${o.rec==='a'?'✅ Recomendado':'⚖️ Evaluar según horizonte'}</span></div>`;
  });
  document.getElementById('inv-wrap').innerHTML=h;
  calcInv();
}
function calcInv(){
  const m=parseFloat(document.getElementById('inv-m')?.value)||0;
  const p=parseFloat(document.getElementById('inv-p')?.value)||6;
  const t=parseFloat(document.getElementById('inv-t')?.value)||9.5;
  const int=m*(t/100)*(p/12);
  const el=document.getElementById('inv-res');
  if(el) el.innerHTML=`Capital: <strong>$ ${f(m)}</strong> &nbsp;·&nbsp; Interés en ${p} meses: <strong style="color:var(--g)">$ ${f(int)}</strong> &nbsp;·&nbsp; Total: <strong style="font-size:15px">$ ${f(m+int)}</strong>`;
}

// ── RENDER FLUJO AR ───────────────────────────────────────────────────────
function renderFlujo(){
  // Auto-use latest month with data if flujo_fac not manually set
  let lastDataM=0;
  for(let m=11;m>=0;m--){ if(arFac(m)>0){lastDataM=m;break;} }
  const fac = D.flujo_fac_manual ? D.flujo_fac : arFac(lastDataM);
  const fac_display = fac;
  const mes_label = D.flujo_fac_manual ? 'personalizado' : M[lastDataM];
  const dias=D.flujo_dias||18;
  const pct=(D.flujo_pct||3.38)/100;
  const pct_adv=(D.flujo_adelanto_pct||7.15)/100;
  
  // Sueldos: use the latest month that has data
  let lastSueldoM=0;
  for(let m=11;m>=0;m--){ if(Object.values(D.ar_sueldos).some(v=>v[m]>0)){lastSueldoM=m;break;} }
  const sueldos=Object.values(D.ar_sueldos).reduce((a,v)=>a+(v[lastSueldoM]||0),0);
  
  // Honorarios: use ALL months that have data (not just first 3)
  const hon_pct=[];
  for(let m=0;m<12;m++){
    if(arFac(m)>0 && D.ar_hon[m]>0) hon_pct.push(D.ar_hon[m]/arFac(m));
  }
  const avg_hon=hon_pct.length>0 ? hon_pct.reduce((a,b)=>a+b,0)/hon_pct.length : 0.507;
  const hon_estimado=fac*avg_hon;
  const dias_lib=Math.min(30,Math.max(0,30+10-dias));
  const pct_lib=dias_lib/30;
  const neto_1ra=fac*pct_lib*(1-pct);
  const bruto_2da=fac*(1-pct_lib);
  const costo_adv=bruto_2da*pct_adv;
  const neto_2da=bruto_2da-costo_adv;
  const disp_sin=neto_1ra;
  const disp_con=neto_1ra+neto_2da;
  const oblig=sueldos+hon_estimado;
  const res_sin=disp_sin-oblig;
  const res_con=disp_con-oblig;

  let h=`<div class="ph"><h1>Flujo de caja Argentina <span style="color:var(--ar);font-family:'DM Mono',monospace;font-size:13px">Simulador de desfase</span></h1><p>Calculá si llegás para pagar sueldos (día 1) y honorarios (día 10) del mes siguiente</p></div>`;
  h+=`<div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:20px">
    <div class="card" style="padding:18px"><div style="font-size:12px;font-weight:500;margin-bottom:14px">Datos del mes</div>
      <div style="margin-bottom:10px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:4px">Facturación a analizar (ARS) <span style="color:var(--b);font-size:10px">· usando ${mes_label}</span></label><input type="number" value="${fac_display}" onchange="D.flujo_fac=parseFloat(this.value)||0;D.flujo_fac_manual=true;renderFlujo()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"><button onclick="D.flujo_fac_manual=false;renderFlujo()" style="margin-top:4px;font-size:11px;color:var(--b);background:none;border:none;cursor:pointer;padding:0">↺ Usar último mes real</button></div>
      <div style="margin-bottom:10px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">Días de liberación MP</label><input type="number" value="${dias}" onchange="D.flujo_dias=parseFloat(this.value)||18;renderFlujo()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
      <div><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">Costo liberación (%)</label><input type="number" value="${D.flujo_pct||3.38}" step="0.01" onchange="D.flujo_pct=parseFloat(this.value)||3.38;renderFlujo()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
    </div>
    <div class="card" style="padding:18px"><div style="font-size:12px;font-weight:500;margin-bottom:14px">Adelanto semanal</div>
      <div style="margin-bottom:10px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">Costo adelanto semanal (%)</label><input type="number" value="${D.flujo_adelanto_pct||7.15}" step="0.01" onchange="D.flujo_adelanto_pct=parseFloat(this.value)||7.15;renderFlujo()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
      <div style="margin-bottom:6px;font-size:12px;color:var(--mu)">% hon. psicólogos (auto): <strong style="color:var(--tx)">${(avg_hon*100).toFixed(1)}%</strong></div>
      <div style="font-size:12px;color:var(--mu)">Sueldos estimados: <strong style="color:var(--tx)">$ ${f(sueldos)}</strong></div>
    </div>
  </div>`;

  h+=`<div class="flujo-res ${res_sin>=0?'flujo-ok':'flujo-mal'}">
    <div style="font-size:12px;font-weight:500;margin-bottom:8px">${res_sin>=0?'✅':'🔴'} Sin adelanto — resultado al día 10 del mes siguiente</div>
    <div class="flujo-big" style="color:${res_sin>=0?'var(--g)':'var(--r)'}">${fv(res_sin)}</div>
    <div style="font-size:12px;margin-top:4px;opacity:.8">${res_sin>=0?'Alcanza para cubrir sueldos y honorarios':'Falta esta plata para cubrir los pagos'}</div>
  </div>
  <div class="flujo-res ${res_con>=0?'flujo-ok':'flujo-mal'}">
    <div style="font-size:12px;font-weight:500;margin-bottom:8px">${res_con>=0?'✅':'🔴'} Con adelanto semanal — resultado al día 10</div>
    <div class="flujo-big" style="color:${res_con>=0?'var(--g)':'var(--r)'}">${fv(res_con)}</div>
    <div style="font-size:12px;margin-top:4px;opacity:.8">Costo del adelanto: $ ${f(costo_adv)}</div>
  </div>`;

  h+=`<div class="stitle">Desglose</div><div class="card"><div class="tw"><table><thead><tr><th>Concepto</th><th>Sin adelanto</th><th>Con adelanto</th></tr></thead><tbody>
    <tr><td>Liberación 1ra quincena (neto)</td><td>$ ${f(neto_1ra)}</td><td>$ ${f(neto_1ra)}</td></tr>
    <tr><td>Adelanto 2da quincena (neto)</td><td style="color:var(--mu2)">—</td><td>$ ${f(neto_2da)}</td></tr>
    <tr class="tr-tot"><td>Total disponible</td><td>$ ${f(disp_sin)}</td><td>$ ${f(disp_con)}</td></tr>
    <tr><td style="color:var(--r)">Sueldos (día 1)</td><td style="color:var(--r)">– $ ${f(sueldos)}</td><td style="color:var(--r)">– $ ${f(sueldos)}</td></tr>
    <tr><td style="color:var(--r)">Honorarios ${(avg_hon*100).toFixed(1)}% (día 10)</td><td style="color:var(--r)">– $ ${f(hon_estimado)}</td><td style="color:var(--r)">– $ ${f(hon_estimado)}</td></tr>
    <tr class="tr-tot" style="${res_sin>=0?'background:var(--gb)':'background:var(--rb)'}"><td>RESULTADO</td><td style="font-weight:500;color:${res_sin>=0?'var(--g)':'var(--r)'}">${fv(res_sin)}</td><td style="font-weight:500;color:${res_con>=0?'var(--g)':'var(--r)'}">${fv(res_con)}</td></tr>
  </tbody></table></div></div>`;

  // Find all months with data
  const mesesConDatos=[];
  for(let m=0;m<12;m++){ if(arFac(m)>0||D.ar_hon[m]>0) mesesConDatos.push(m); }
  const tituloHist='Histórico '+M[mesesConDatos[0]||0]+(mesesConDatos.length>1?'–'+M[mesesConDatos[mesesConDatos.length-1]]:'');
  h+=`<div class="stitle">${tituloHist}</div><div class="card"><div class="tw"><table><thead><tr><th>Mes</th><th>Facturación</th><th>Honorarios</th><th>% Hon.</th><th>Sueldos</th><th>Disponible (sin adel.)</th><th>Resultado</th></tr></thead><tbody>`;
  mesesConDatos.forEach(m=>{
    const fac_m=arFac(m), hon_m=D.ar_hon[m];
    const sue_m=Object.values(D.ar_sueldos).reduce((a,v)=>a+(v[m]||0),0);
    const disp_m=fac_m*pct_lib*(1-pct);
    const res_m=disp_m-sue_m-hon_m;
    h+=`<tr><td>${M[m]}</td><td>$ ${f(fac_m)}</td><td>$ ${f(hon_m)}</td><td>${fac_m>0?(hon_m/fac_m*100).toFixed(1)+'%':'—'}</td><td>$ ${f(sue_m)}</td><td>$ ${f(disp_m)}</td><td style="color:${res_m>=0?'var(--g)':'var(--r)'};font-weight:500">${fv(res_m)}</td></tr>`;
  });
  h+=`</tbody></table></div></div>`;
  document.getElementById('flujo-wrap').innerHTML=h;
}



// ── USD TOTALS HELPER ─────────────────────────────────────────────────────
function fWithUSD(val, tc){
  return f(val)+'<div style="font-size:9px;color:var(--b);font-family:monospace;margin-top:1px">U$D '+f(val/tc)+'</div>';
}

// ── DOLARIZAR ─────────────────────────────────────────────────────────────
const TC = {ar: 1450, uy: 40};
const dolarOn = {ar: false, uy: false, ali: false};

function toggleDolar(country){
  dolarOn[country] = !dolarOn[country];
  const btn = document.getElementById('dbtn-'+country);
  if(btn){
    if(dolarOn[country]){
      btn.classList.add('on');
      btn.innerHTML = '💵 Viendo en USD <span class="dolar-pill">TC $'+TC[country].toLocaleString('es-AR')+'</span>';
    } else {
      btn.classList.remove('on');
      btn.innerHTML = '💵 Ver en USD <span class="dolar-pill">TC $'+TC[country].toLocaleString('es-AR')+'</span>';
    }
  }
  if(country==='ar') renderAR();
  else renderUYU();
}

function fd(val, country){
  // Format value — if dolar mode, convert and prefix U$D
  if(!dolarOn[country]) return f(val);
  return 'U$D '+f(val/TC[country]);
}

// ── FLUJO URUGUAY (caja real + inversión Meta) ───────────────────────────
function renderFlujoUY(){
  if(D.flujouy_meta_semanal===undefined) D.flujouy_meta_semanal=60000;
  if(D.flujouy_inicio_meta===undefined) D.flujouy_inicio_meta=4; // mes desde el cual arranca la inversión (0=Ene, 4=May)
  if(D.flujouy_saldo_ini===undefined) D.flujouy_saldo_ini=0;

  const metaSem=D.flujouy_meta_semanal;
  const metaMes=metaSem*4;
  const inicioMeta=D.flujouy_inicio_meta;
  const saldoIni=D.flujouy_saldo_ini;

  let h=`<div class="ph"><h1>Flujo de caja Uruguay <span style="color:var(--uy);font-family:'DM Mono',monospace;font-size:13px">UYU · 2026</span></h1><p>Caja real con la inversión de $${f(metaSem)} UYU/semana = $${f(metaMes)} UYU/mes en Meta</p></div>`;

  // Settings
  h+=`<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;margin-bottom:20px">
    <div class="card" style="padding:14px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">Saldo inicial UYU (Enero)</label><input type="number" value="${saldoIni}" onchange="D.flujouy_saldo_ini=parseFloat(this.value)||0;markDirty();renderFlujoUY()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"></div>
    <div class="card" style="padding:14px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">Meta UYU/semana</label><input type="number" value="${metaSem}" onchange="D.flujouy_meta_semanal=parseFloat(this.value)||0;markDirty();renderFlujoUY()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Mono',monospace;font-size:13px;text-align:right"><div style="font-size:10px;color:var(--mu2);margin-top:3px">= $${f(metaSem*4)}/mes (4 semanas)</div></div>
    <div class="card" style="padding:14px"><label style="font-size:11px;color:var(--mu);display:block;margin-bottom:3px">A partir de qué mes</label><select onchange="D.flujouy_inicio_meta=parseInt(this.value);markDirty();renderFlujoUY()" style="width:100%;border:1px solid var(--brd);border-radius:6px;padding:7px 10px;font-family:'DM Sans',sans-serif;font-size:13px;outline:none">${M.map((m,i)=>`<option value="${i}" ${i===inicioMeta?'selected':''}>${m}</option>`).join('')}</select></div>
  </div>`;

  // Find last month with real data
  let lastDataM=-1;
  for(let m=11;m>=0;m--){ if(uyFac(m)>0||uyGas(m)>0){lastDataM=m;break;} }
  
  // For months without data, use average of months with data as estimation
  const realMs=[]; for(let m=0;m<=lastDataM;m++) if(uyFac(m)>0) realMs.push(m);
  const avgFac=realMs.length>0?realMs.reduce((a,m)=>a+uyFac(m),0)/realMs.length:0;
  const avgGas=realMs.length>0?realMs.reduce((a,m)=>a+uyGas(m),0)/realMs.length:0;

  // Build cashflow row by row
  let saldoSinMeta=saldoIni;
  let saldoConMeta=saldoIni;
  const filas=[];
  for(let m=0;m<12;m++){
    const esReal=m<=lastDataM&&uyFac(m)>0;
    const fac=esReal?uyFac(m):avgFac;
    const gas=esReal?uyGas(m):avgGas;
    const meta=m>=inicioMeta?metaMes:0;
    const resSinMeta=fac-gas;
    const resConMeta=fac-gas-meta;
    saldoSinMeta+=resSinMeta;
    saldoConMeta+=resConMeta;
    filas.push({m, esReal, fac, gas, meta, resSinMeta, resConMeta, saldoSinMeta, saldoConMeta});
  }

  // Info banner
  h+=`<div style="background:var(--bb);border:1px solid var(--bbrd);border-radius:10px;padding:14px 18px;margin-bottom:20px;font-size:12px;color:var(--b);line-height:1.6">
    <strong>Datos reales:</strong> ${M[0]}–${M[lastDataM]} (${realMs.length} ${realMs.length===1?'mes':'meses'} con datos). 
    <strong>Estimación:</strong> meses sin datos usan el promedio de los reales (Fac avg: $${f(avgFac)} · Gas avg: $${f(avgGas)}). 
    <strong>Inversión Meta:</strong> arranca desde ${M[inicioMeta]} con $${f(metaMes)}/mes.
  </div>`;

  // Main cashflow table
  h+=`<div class="stitle">Flujo de caja mes a mes</div>`;
  h+=`<div class="card"><div class="tw"><table>
    <thead><tr>
      <th>Concepto</th>
      ${M.map((mLbl,i)=>`<th style="${i<=lastDataM?'':'color:var(--mu2)'}">${mLbl}${i<=lastDataM&&uyFac(i)>0?' ✓':' (est.)'}</th>`).join('')}
      <th>Total</th>
    </tr></thead>
    <tbody>
      <tr><td>Facturación UYU</td>
        ${filas.map(f_=>`<td style="${f_.esReal?'':'color:var(--mu2)'}">${f(f_.fac)}</td>`).join('')}
        <td>${f(filas.reduce((a,r)=>a+r.fac,0))}</td>
      </tr>
      <tr style="color:var(--r)"><td>Gastos UYU</td>
        ${filas.map(f_=>`<td style="${f_.esReal?'':'color:var(--mu2);opacity:.7'}">${f(f_.gas)}</td>`).join('')}
        <td>${f(filas.reduce((a,r)=>a+r.gas,0))}</td>
      </tr>
      <tr style="color:var(--am)"><td>+ Inversión Meta</td>
        ${filas.map(f_=>`<td>${f_.meta>0?f(f_.meta):'—'}</td>`).join('')}
        <td>${f(filas.reduce((a,r)=>a+r.meta,0))}</td>
      </tr>
      <tr class="tr-tot"><td>Resultado SIN Meta</td>
        ${filas.map(f_=>`<td style="color:${f_.resSinMeta>=0?'var(--g)':'var(--r)'}">${fv(f_.resSinMeta)}</td>`).join('')}
        <td>${fv(filas.reduce((a,r)=>a+r.resSinMeta,0))}</td>
      </tr>
      <tr class="tr-tot"><td>Resultado CON Meta</td>
        ${filas.map(f_=>`<td style="color:${f_.resConMeta>=0?'var(--g)':'var(--r)'}">${fv(f_.resConMeta)}</td>`).join('')}
        <td>${fv(filas.reduce((a,r)=>a+r.resConMeta,0))}</td>
      </tr>
      <tr style="background:var(--bg);border-top:2px solid var(--brd2)"><td style="font-weight:500">📦 Caja acumulada SIN Meta</td>
        ${filas.map(f_=>`<td style="font-family:'DM Mono',monospace;font-weight:500;color:${f_.saldoSinMeta>=0?'var(--g)':'var(--r)'}">${fv(f_.saldoSinMeta)}</td>`).join('')}
        <td></td>
      </tr>
      <tr style="background:var(--gb)"><td style="font-weight:500;color:var(--g)">📦 Caja acumulada CON Meta</td>
        ${filas.map(f_=>`<td style="font-family:'DM Mono',monospace;font-weight:500;color:${f_.saldoConMeta>=0?'var(--g)':'var(--r)'}">${fv(f_.saldoConMeta)}</td>`).join('')}
        <td></td>
      </tr>
    </tbody>
  </table></div></div>`;

  // Summary cards
  const finalSinMeta=filas[filas.length-1].saldoSinMeta;
  const finalConMeta=filas[filas.length-1].saldoConMeta;
  const costoTotalMeta=filas.reduce((a,r)=>a+r.meta,0);
  const minCajaConMeta=Math.min(...filas.map(f_=>f_.saldoConMeta));
  const minMesM=filas.findIndex(f_=>f_.saldoConMeta===minCajaConMeta);

  h+=`<div style="display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:12px;margin-top:20px">
    <div class="flujo-res" style="background:var(--bg);border-color:var(--brd2)">
      <div style="font-size:11px;color:var(--mu);margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px">Caja final Dic — sin Meta</div>
      <div class="flujo-big" style="color:${finalSinMeta>=0?'var(--g)':'var(--r)'}">${fv(finalSinMeta)}</div>
    </div>
    <div class="flujo-res ${finalConMeta>=0?'flujo-ok':'flujo-mal'}">
      <div style="font-size:11px;font-weight:500;margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px">${finalConMeta>=0?'✅':'🔴'} Caja final Dic — con Meta</div>
      <div class="flujo-big" style="color:${finalConMeta>=0?'var(--g)':'var(--r)'}">${fv(finalConMeta)}</div>
    </div>
    <div class="flujo-res" style="background:var(--amb);border-color:var(--ambrd)">
      <div style="font-size:11px;color:var(--am);font-weight:500;margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px">Costo total Meta</div>
      <div class="flujo-big" style="color:var(--am)">$ ${f(costoTotalMeta)}</div>
      <div style="font-size:10px;color:var(--am);margin-top:4px;opacity:.8">${12-inicioMeta} meses × $${f(metaMes)}</div>
    </div>
    <div class="flujo-res" style="background:${minCajaConMeta>=0?'var(--gb)':'var(--rb)'};border-color:${minCajaConMeta>=0?'var(--gbrd)':'var(--rbrd)'}">
      <div style="font-size:11px;font-weight:500;margin-bottom:6px;text-transform:uppercase;letter-spacing:.5px">${minCajaConMeta>=0?'⚠️':'🔴'} Mínimo de caja</div>
      <div class="flujo-big" style="color:${minCajaConMeta>=0?'var(--g)':'var(--r)'}">${fv(minCajaConMeta)}</div>
      <div style="font-size:10px;margin-top:4px;opacity:.8">en ${M[minMesM]}</div>
    </div>
  </div>`;

  document.getElementById('flujouy-wrap').innerHTML=h;
}

// ── NAV ───────────────────────────────────────────────────────────────────
document.querySelectorAll('.tab').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('.tab').forEach(t=>t.classList.remove('on'));
    document.querySelectorAll('.pg').forEach(p=>p.classList.remove('on'));
    btn.classList.add('on');
    const id='pg-'+btn.dataset.pg;
    document.getElementById(id).classList.add('on');
    const pg=btn.dataset.pg;
    if(pg==='dashboard'){ renderKPIs(); renderDashTables(); renderCharts(); }
    else if(pg==='argentina') renderAR();
    else if(pg==='uyu') renderUYU();
    else if(pg==='usd') renderUSD();
    else if(pg==='alianzas') renderAlianzas();
    else if(pg==='participacion') renderParticipacion();
    else if(pg==='proyecciones') renderProjections();
    else if(pg==='inversion') renderInversion();
    else if(pg==='flujo') renderFlujo();
    else if(pg==='flujouy') renderFlujoUY();
  });
});

// ── COMPUTED ──────────────────────────────────────────────────────────────
function updateComputed(){ /* dynamic rows already rendered */ }

// ── REFRESH ───────────────────────────────────────────────────────────────
function refresh(){
  // Always update dashboard
  renderKPIs();
  renderDashTables();
  renderCharts();
  // Re-render current page to update variations etc
  // Save focused element info to restore after re-render
  const active=document.querySelector('.tab.on');
  if(!active) return;
  const pg=active.dataset.pg;
  if(pg==='argentina'||pg==='uyu'||pg==='usd'||pg==='alianzas'||pg==='flujo'){
    const focused=document.activeElement;
    const focusedValue=focused?focused.value:null;
    // Find position of focused input among all inputs in its container
    const wrap=document.getElementById(pg==='argentina'?'ar-wrap':pg==='uyu'?'uyu-wrap':pg==='usd'?'usd-wrap':pg==='alianzas'?'ali-wrap':'flujo-wrap');
    let focusIdx=-1;
    if(wrap&&focused&&wrap.contains(focused)){
      const inputs=[...wrap.querySelectorAll('input[type=number]')];
      focusIdx=inputs.indexOf(focused);
    }
    if(pg==='argentina') renderAR();
    else if(pg==='uyu') renderUYU();
    else if(pg==='usd') renderUSD();
    else if(pg==='alianzas') renderAlianzas();
    else if(pg==='flujo') renderFlujo();
    else if(pg==='flujouy') renderFlujoUY();
    // Restore focus
    if(focusIdx>=0){
      const wrap2=document.getElementById(pg==='argentina'?'ar-wrap':pg==='uyu'?'uyu-wrap':pg==='usd'?'usd-wrap':pg==='alianzas'?'ali-wrap':pg==='flujouy'?'flujouy-wrap':'flujo-wrap');
      if(wrap2){
        const inputs2=[...wrap2.querySelectorAll('input[type=number]')];
        if(inputs2[focusIdx]){
          inputs2[focusIdx].focus();
          inputs2[focusIdx].select();
        }
      }
    }
  }
}

// ── LOGIN ─────────────────────────────────────────────────────────────────
window.addEventListener('load', function(){
  try {
    renderAR(); renderUYU(); renderUSD(); renderAlianzas();
    renderKPIs(); renderDashTables(); renderCharts();
  } catch(e) {
    console.error('Init error:', e);
    document.getElementById('app').style.display='block';
  }
  document.getElementById('loginbtn').addEventListener('click', doLogin);
  document.getElementById('pwd').addEventListener('keydown', function(e){ if(e.key==='Enter') doLogin(); });
  document.getElementById('pwd').focus();
});

function doLogin(){
  var v = document.getElementById('pwd').value;
  if(v === 'Hillman2026'){
    document.getElementById('login').style.display = 'none';
  } else {
    document.getElementById('lerr').textContent = 'Contraseña incorrecta';
    document.getElementById('pwd').value = '';
    document.getElementById('pwd').focus();
  }
}
</script>
</body>
</html>

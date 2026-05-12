<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RD Saúde S.A. — Análise de Desempenho Empresarial</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=IBM+Plex+Mono:wght@300;400;600&family=IBM+Plex+Sans:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #080c14;
    --surface: #0d1420;
    --surface2: #111a2e;
    --border: #1e2d47;
    --accent: #00d4ff;
    --accent2: #ff6b35;
    --accent3: #7fff6b;
    --accent4: #ffd166;
    --text: #e8edf5;
    --muted: #5a6a82;
    --positive: #4ade80;
    --negative: #f87171;
    --warning: #fbbf24;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'IBM Plex Sans', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Background grid */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,212,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,212,255,0.03) 1px, transparent 1px);
    background-size: 40px 40px;
    pointer-events: none;
    z-index: 0;
  }

  .container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 40px 32px;
    position: relative;
    z-index: 1;
  }

  /* Header */
  header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    margin-bottom: 48px;
    padding-bottom: 32px;
    border-bottom: 1px solid var(--border);
  }

  .header-left {}
  .eyebrow {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    letter-spacing: 3px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 12px;
  }
  h1 {
    font-family: 'Playfair Display', serif;
    font-size: 48px;
    font-weight: 900;
    line-height: 1.05;
    background: linear-gradient(135deg, #e8edf5 0%, #00d4ff 60%, #7fff6b 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
  .subtitle {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 13px;
    color: var(--muted);
    margin-top: 8px;
  }

  .header-badge {
    text-align: right;
  }
  .badge-label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .verdict {
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 700;
    color: var(--positive);
  }

  /* Section headers */
  .section-title {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .section-title::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  /* KPI row */
  .kpi-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
    margin-bottom: 40px;
  }
  .kpi-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 20px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s;
  }
  .kpi-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: var(--accent-color, var(--accent));
  }
  .kpi-card:hover { border-color: var(--accent); }
  .kpi-label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    letter-spacing: 1px;
    text-transform: uppercase;
    margin-bottom: 10px;
  }
  .kpi-value {
    font-family: 'Playfair Display', serif;
    font-size: 32px;
    font-weight: 700;
    color: var(--text);
    line-height: 1;
  }
  .kpi-sub {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    color: var(--muted);
    margin-top: 6px;
  }
  .kpi-trend {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    margin-top: 8px;
  }
  .up { color: var(--positive); }
  .down { color: var(--negative); }
  .neutral { color: var(--warning); }

  /* Main grid */
  .main-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 20px;
    margin-bottom: 24px;
  }

  /* Chart card */
  .chart-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 24px;
  }
  .chart-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 24px;
  }
  .chart-title {
    font-family: 'Playfair Display', serif;
    font-size: 18px;
    font-weight: 700;
    color: var(--text);
  }
  .chart-legend {
    display: flex;
    gap: 16px;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
  }
  .legend-item {
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .legend-dot {
    width: 8px; height: 8px;
    border-radius: 50%;
  }

  /* SVG Chart */
  .chart-wrapper { position: relative; }
  svg.linechart {
    width: 100%;
    overflow: visible;
  }

  /* Bar chart */
  .bar-chart-wrap { display: flex; flex-direction: column; gap: 10px; }
  .bar-row { display: flex; align-items: center; gap: 10px; }
  .bar-label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    width: 36px;
    text-align: right;
    flex-shrink: 0;
  }
  .bar-track {
    flex: 1;
    height: 20px;
    background: var(--surface2);
    border-radius: 3px;
    overflow: hidden;
    position: relative;
  }
  .bar-fill {
    height: 100%;
    border-radius: 3px;
    transition: width 1s ease;
    position: relative;
  }
  .bar-val {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    color: var(--text);
    width: 50px;
    text-align: right;
    flex-shrink: 0;
  }

  /* Three-column grid */
  .three-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-bottom: 24px;
  }

  /* Table card */
  .table-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 24px;
  }
  .data-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 12px;
  }
  .data-table th {
    text-align: right;
    padding: 6px 8px;
    color: var(--muted);
    font-size: 10px;
    letter-spacing: 1px;
    border-bottom: 1px solid var(--border);
    font-weight: 400;
  }
  .data-table th:first-child { text-align: left; }
  .data-table td {
    padding: 8px 8px;
    border-bottom: 1px solid rgba(30,45,71,0.5);
    text-align: right;
    color: var(--text);
  }
  .data-table td:first-child {
    text-align: left;
    color: var(--muted);
    font-size: 11px;
  }
  .data-table tr:last-child td { border-bottom: none; }
  .data-table tr:hover td { background: rgba(0,212,255,0.03); }
  .td-accent { color: var(--accent) !important; font-weight: 600; }

  /* Diagnosis panel */
  .diag-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
    margin-bottom: 24px;
  }
  .diag-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 20px;
  }
  .diag-question {
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 13px;
    color: var(--muted);
    margin-bottom: 12px;
    line-height: 1.4;
    font-style: italic;
  }
  .diag-answer {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    font-weight: 700;
    margin-bottom: 8px;
  }
  .diag-text {
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 12px;
    color: var(--muted);
    line-height: 1.5;
  }

  /* Sparkline inline */
  .sparkline {
    display: inline-block;
    vertical-align: middle;
  }

  /* Insight box */
  .insight-box {
    background: linear-gradient(135deg, rgba(0,212,255,0.05), rgba(127,255,107,0.05));
    border: 1px solid rgba(0,212,255,0.2);
    border-radius: 8px;
    padding: 24px 32px;
    margin-bottom: 24px;
  }
  .insight-title {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    letter-spacing: 3px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 16px;
  }
  .insight-points {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }
  .insight-point {
    display: flex;
    gap: 12px;
    align-items: flex-start;
  }
  .insight-icon {
    font-size: 16px;
    flex-shrink: 0;
    margin-top: 1px;
  }
  .insight-text {
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 13px;
    color: var(--text);
    line-height: 1.5;
  }
  .insight-text strong { color: var(--accent); }

  /* Kanitz */
  .kanitz-bar {
    position: relative;
    height: 48px;
    border-radius: 6px;
    overflow: hidden;
    margin-bottom: 8px;
    background: linear-gradient(90deg,
      #f87171 0%, #f87171 20%,
      #fbbf24 20%, #fbbf24 50%,
      #4ade80 50%, #4ade80 100%
    );
    opacity: 0.3;
  }
  .kanitz-markers {
    position: relative;
    height: 48px;
    margin-bottom: 16px;
  }
  .kanitz-mark {
    position: absolute;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2px;
  }
  .kanitz-needle {
    width: 2px;
    height: 48px;
    background: white;
    border-radius: 1px;
    box-shadow: 0 0 8px rgba(255,255,255,0.8);
  }
  .kanitz-label {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 9px;
    color: var(--text);
    white-space: nowrap;
  }
  .kanitz-zone {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    display: flex;
    justify-content: space-between;
  }

  /* Gauge */
  .gauge-row {
    display: flex;
    gap: 20px;
    align-items: center;
    flex-wrap: wrap;
    margin-top: 12px;
  }
  .gauge-item {
    display: flex;
    align-items: center;
    gap: 8px;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 11px;
    color: var(--muted);
  }
  .gauge-dot {
    width: 10px; height: 10px; border-radius: 50%;
  }

  /* Footer */
  footer {
    border-top: 1px solid var(--border);
    padding-top: 24px;
    margin-top: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .footer-note {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 10px;
    color: var(--muted);
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(16px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .animate { animation: fadeIn 0.6s ease forwards; }
  .delay-1 { animation-delay: 0.1s; opacity: 0; }
  .delay-2 { animation-delay: 0.2s; opacity: 0; }
  .delay-3 { animation-delay: 0.3s; opacity: 0; }
  .delay-4 { animation-delay: 0.4s; opacity: 0; }

  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 24px; }
</style>
</head>
<body>
<div class="container">

  <!-- HEADER -->
  <header class="animate">
    <div class="header-left">
      <div class="eyebrow">// Análise de Desempenho Empresarial — 2021–2025</div>
      <h1>RD Saúde S.A.</h1>
      <div class="subtitle">Indicadores Financeiros · Econômicos · Capital de Giro · Ciclos</div>
    </div>
    <div class="header-badge">
      <div class="badge-label">Diagnóstico Geral</div>
      <div class="verdict">✦ Solvente & Crescente</div>
      <div class="subtitle" style="margin-top:4px;">Kanitz 2025: 4,19 → Área de Solvência</div>
    </div>
  </header>

  <!-- KPIs -->
  <div class="section-title animate delay-1">01 — Principais Indicadores (2025)</div>
  <div class="kpi-grid animate delay-1">
    <div class="kpi-card" style="--accent-color: #00d4ff">
      <div class="kpi-label">Liquidez Corrente</div>
      <div class="kpi-value">1,41</div>
      <div class="kpi-sub">AC / PC</div>
      <div class="kpi-trend up">▲ Acima de 1,0 → Saudável</div>
    </div>
    <div class="kpi-card" style="--accent-color: #7fff6b">
      <div class="kpi-label">Margem Bruta</div>
      <div class="kpi-value">30,73<span style="font-size:18px;color:var(--muted)">%</span></div>
      <div class="kpi-sub">RB / VL</div>
      <div class="kpi-trend neutral">► Estável ~31% desde 2021</div>
    </div>
    <div class="kpi-card" style="--accent-color: #ff6b35">
      <div class="kpi-label">ROE</div>
      <div class="kpi-value">18,86<span style="font-size:18px;color:var(--muted)">%</span></div>
      <div class="kpi-sub">RL / PLm</div>
      <div class="kpi-trend up">▲ Forte retorno ao acionista</div>
    </div>
    <div class="kpi-card" style="--accent-color: #ffd166">
      <div class="kpi-label">EBITDA</div>
      <div class="kpi-value" style="font-size:22px;">2.762.675</div>
      <div class="kpi-sub">RO + Depr./Amort.</div>
      <div class="kpi-trend up">▲ +104% vs 2021</div>
    </div>
  </div>

  <!-- EBITDA + LIQUIDEZ CHART -->
  <div class="section-title animate delay-2">02 — Evolução Temporal</div>
  <div class="main-grid animate delay-2">
    <!-- EBITDA Line Chart -->
    <div class="chart-card">
      <div class="chart-header">
        <div>
          <div class="chart-title">Evolução do EBITDA</div>
          <div style="font-family:'IBM Plex Mono',monospace;font-size:11px;color:var(--muted);margin-top:4px;">em R$ mil — crescimento contínuo 2021–2025</div>
        </div>
        <div class="chart-legend">
          <div class="legend-item"><div class="legend-dot" style="background:var(--accent)"></div> EBITDA</div>
          <div class="legend-item"><div class="legend-dot" style="background:var(--accent3)"></div> ROE %</div>
        </div>
      </div>
      <svg class="linechart" viewBox="0 0 580 180" preserveAspectRatio="none">
        <!-- Grid lines -->
        <line x1="0" y1="30" x2="580" y2="30" stroke="#1e2d47" stroke-width="1"/>
        <line x1="0" y1="70" x2="580" y2="70" stroke="#1e2d47" stroke-width="1"/>
        <line x1="0" y1="110" x2="580" y2="110" stroke="#1e2d47" stroke-width="1"/>
        <line x1="0" y1="150" x2="580" y2="150" stroke="#1e2d47" stroke-width="1"/>

        <!-- Y labels -->
        <text x="0" y="25" fill="#5a6a82" font-size="9" font-family="IBM Plex Mono">2.8M</text>
        <text x="0" y="65" fill="#5a6a82" font-size="9" font-family="IBM Plex Mono">2.4M</text>
        <text x="0" y="105" fill="#5a6a82" font-size="9" font-family="IBM Plex Mono">1.8M</text>
        <text x="0" y="148" fill="#5a6a82" font-size="9" font-family="IBM Plex Mono">1.3M</text>

        <!-- EBITDA area fill -->
        <!-- Points: 2021=1350618, 2022=1776141, 2023=2080489, 2024=2409975, 2025=2762675 -->
        <!-- Scale: min~1.3M, max~2.8M → range 1.5M, height 140px -->
        <!-- y = 160 - ((val - 1300000)/1500000)*140 -->
        <!-- 2021: y=159, 2022: y=108, 2023: y=74, 2024: y=42, 2025: y=6 -->
        <!-- x positions: 40, 175, 310, 445, 540 -->
        <defs>
          <linearGradient id="ebitdaGrad" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#00d4ff" stop-opacity="0.3"/>
            <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <polygon points="40,157 175,108 310,74 445,42 540,8 540,160 40,160" fill="url(#ebitdaGrad)"/>
        <polyline points="40,157 175,108 310,74 445,42 540,8"
          fill="none" stroke="#00d4ff" stroke-width="2.5" stroke-linejoin="round"/>
        <!-- Dots EBITDA -->
        <circle cx="40" cy="157" r="4" fill="#00d4ff"/>
        <circle cx="175" cy="108" r="4" fill="#00d4ff"/>
        <circle cx="310" cy="74" r="4" fill="#00d4ff"/>
        <circle cx="445" cy="42" r="4" fill="#00d4ff"/>
        <circle cx="540" cy="8" r="5" fill="#00d4ff" stroke="#080c14" stroke-width="2"/>

        <!-- ROE line (scale 0-25%, height 140px) -->
        <!-- 2021=10.28, 2022=19.82, 2023=19.25, 2024=19.37, 2025=18.86 -->
        <!-- y = 160 - (val/25)*140 -->
        <!-- 2021:y=102, 2022:y=49, 2023:y=52, 2024:y=51, 2025:y=54 -->
        <polyline points="40,102 175,49 310,52 445,51 540,54"
          fill="none" stroke="#7fff6b" stroke-width="2" stroke-dasharray="5,3" stroke-linejoin="round"/>
        <circle cx="40" cy="102" r="3" fill="#7fff6b"/>
        <circle cx="175" cy="49" r="3" fill="#7fff6b"/>
        <circle cx="310" cy="52" r="3" fill="#7fff6b"/>
        <circle cx="445" cy="51" r="3" fill="#7fff6b"/>
        <circle cx="540" cy="54" r="4" fill="#7fff6b" stroke="#080c14" stroke-width="2"/>

        <!-- X labels -->
        <text x="40" y="175" fill="#5a6a82" font-size="10" font-family="IBM Plex Mono" text-anchor="middle">2021</text>
        <text x="175" y="175" fill="#5a6a82" font-size="10" font-family="IBM Plex Mono" text-anchor="middle">2022</text>
        <text x="310" y="175" fill="#5a6a82" font-size="10" font-family="IBM Plex Mono" text-anchor="middle">2023</text>
        <text x="445" y="175" fill="#5a6a82" font-size="10" font-family="IBM Plex Mono" text-anchor="middle">2024</text>
        <text x="540" y="175" fill="#5a6a82" font-size="10" font-family="IBM Plex Mono" text-anchor="middle">2025</text>

        <!-- Value labels -->
        <text x="540" y="4" fill="#00d4ff" font-size="9" font-family="IBM Plex Mono" text-anchor="middle">2.763M</text>
        <text x="40" y="152" fill="#00d4ff" font-size="9" font-family="IBM Plex Mono" text-anchor="middle">1.351M</text>
      </svg>
    </div>

    <!-- Liquidez bars -->
    <div class="chart-card">
      <div class="chart-header">
        <div class="chart-title">Índices de Liquidez</div>
      </div>
      <div class="bar-chart-wrap">
        <!-- LC -->
        <div style="font-family:'IBM Plex Mono',monospace;font-size:9px;color:var(--muted);letter-spacing:1px;text-transform:uppercase;margin-bottom:6px;">Liquidez Corrente</div>
        <div class="bar-row"><div class="bar-label">2021</div><div class="bar-track"><div class="bar-fill" style="width:65%;background:linear-gradient(90deg,#00d4ff,#7fff6b)"></div></div><div class="bar-val">1,30</div></div>
        <div class="bar-row"><div class="bar-label">2022</div><div class="bar-track"><div class="bar-fill" style="width:75%;background:linear-gradient(90deg,#00d4ff,#7fff6b)"></div></div><div class="bar-val">1,50</div></div>
        <div class="bar-row"><div class="bar-label">2023</div><div class="bar-track"><div class="bar-fill" style="width:72%;background:linear-gradient(90deg,#00d4ff,#7fff6b)"></div></div><div class="bar-val">1,44</div></div>
        <div class="bar-row"><div class="bar-label">2024</div><div class="bar-track"><div class="bar-fill" style="width:67%;background:linear-gradient(90deg,#00d4ff,#7fff6b)"></div></div><div class="bar-val">1,34</div></div>
        <div class="bar-row"><div class="bar-label">2025</div><div class="bar-track"><div class="bar-fill" style="width:70.5%;background:linear-gradient(90deg,#00d4ff,#7fff6b)"></div></div><div class="bar-val">1,41</div></div>

        <div style="height:12px"></div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:9px;color:var(--muted);letter-spacing:1px;text-transform:uppercase;margin-bottom:6px;">Liquidez Geral</div>
        <div class="bar-row"><div class="bar-label">2021</div><div class="bar-track"><div class="bar-fill" style="width:39%;background:linear-gradient(90deg,#ffd166,#ff6b35)"></div></div><div class="bar-val">0,78</div></div>
        <div class="bar-row"><div class="bar-label">2022</div><div class="bar-track"><div class="bar-fill" style="width:42.5%;background:linear-gradient(90deg,#ffd166,#ff6b35)"></div></div><div class="bar-val">0,85</div></div>
        <div class="bar-row"><div class="bar-label">2023</div><div class="bar-track"><div class="bar-fill" style="width:43%;background:linear-gradient(90deg,#ffd166,#ff6b35)"></div></div><div class="bar-val">0,86</div></div>
        <div class="bar-row"><div class="bar-label">2024</div><div class="bar-track"><div class="bar-fill" style="width:42.5%;background:linear-gradient(90deg,#ffd166,#ff6b35)"></div></div><div class="bar-val">0,85</div></div>
        <div class="bar-row"><div class="bar-label">2025</div><div class="bar-track"><div class="bar-fill" style="width:43.5%;background:linear-gradient(90deg,#ffd166,#ff6b35)"></div></div><div class="bar-val">0,87</div></div>
      </div>
    </div>
  </div>

  <!-- ECONOMIC INDICATORS TABLE -->
  <div class="two-col animate delay-3">
    <div class="table-card">
      <div class="section-title" style="margin-bottom:16px;">03 — Indicadores Econômicos</div>
      <table class="data-table">
        <thead>
          <tr>
            <th>Indicador</th>
            <th>2021</th>
            <th>2022</th>
            <th>2023</th>
            <th>2024</th>
            <th>2025</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Margem Bruta (%)</td>
            <td>30,82</td><td>31,33</td><td>30,04</td><td>31,57</td><td class="td-accent">30,73</td>
          </tr>
          <tr>
            <td>Margem Operacional (%)</td>
            <td>5,91</td><td>6,50</td><td>6,12</td><td>6,76</td><td class="td-accent">6,72</td>
          </tr>
          <tr>
            <td>Margem Líquida (%)</td>
            <td>3,29</td><td>3,63</td><td>3,20</td><td>3,37</td><td class="td-accent">3,16</td>
          </tr>
          <tr>
            <td>Giro do Ativo</td>
            <td>1,58</td><td>1,64</td><td>1,78</td><td>1,68</td><td class="td-accent">1,68</td>
          </tr>
          <tr>
            <td>ROA (%)</td>
            <td>9,35</td><td>10,65</td><td>10,90</td><td>11,36</td><td class="td-accent">11,33</td>
          </tr>
          <tr>
            <td>ROE (%)</td>
            <td>10,28</td><td>19,82</td><td>19,25</td><td>19,37</td><td class="td-accent">18,86</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="table-card">
      <div class="section-title" style="margin-bottom:16px;">04 — Capital de Giro & Ciclos</div>
      <table class="data-table">
        <thead>
          <tr>
            <th>Indicador</th>
            <th>2021</th>
            <th>2023</th>
            <th>2025</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>CDG (R$)</td>
            <td>1.668.131</td><td>3.227.042</td><td class="td-accent">3.930.733</td>
          </tr>
          <tr>
            <td>NCG (R$)</td>
            <td>842.602</td><td>1.009.336</td><td class="td-accent">1.367.827</td>
          </tr>
          <tr>
            <td>Saldo Tesouraria</td>
            <td>825.529</td><td>2.217.706</td><td class="td-accent">2.562.906</td>
          </tr>
          <tr>
            <td>PMP (dias)</td>
            <td>83</td><td>71</td><td class="td-accent">81</td>
          </tr>
          <tr>
            <td>PMR (dias)</td>
            <td>79</td><td>73</td><td class="td-accent">80</td>
          </tr>
          <tr>
            <td>Ciclo Financeiro (dias)</td>
            <td style="color:var(--positive)">−4</td><td>+2</td><td class="td-accent" style="color:var(--positive)">−1</td>
          </tr>
        </tbody>
      </table>
      <div style="margin-top:14px;padding:10px;background:rgba(74,222,128,0.07);border-radius:4px;border-left:3px solid var(--positive)">
        <div style="font-family:'IBM Plex Mono',monospace;font-size:10px;color:var(--positive)">✦ Ciclo Financeiro Negativo</div>
        <div style="font-family:'IBM Plex Sans',sans-serif;font-size:12px;color:var(--muted);margin-top:4px;">A empresa recebe dos clientes <strong style="color:var(--text)">antes</strong> de pagar fornecedores — posição de caixa privilegiada, típico de grandes varejistas.</div>
      </div>
    </div>
  </div>

  <!-- KANITZ -->
  <div class="section-title animate delay-3">05 — Fator de Insolvência de Kanitz</div>
  <div class="chart-card animate delay-3" style="margin-bottom:24px;">
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:32px;align-items:center;">
      <div>
        <div style="font-family:'Playfair Display',serif;font-size:20px;font-weight:700;margin-bottom:16px;">Termômetro de Solvência</div>
        <!-- Zone bar -->
        <div style="position:relative;height:36px;border-radius:6px;overflow:hidden;background:linear-gradient(90deg,#f87171 0%,#f87171 21%,#fbbf24 21%,#fbbf24 50%,#4ade80 50%,#4ade80 100%);margin-bottom:32px;opacity:0.7">
        </div>
        <!-- Markers -->
        <div style="position:relative;height:40px;margin-top:-56px;margin-bottom:16px;">
          <!-- Scale: -7 to +7 → 14 range → 100% = 14 units -->
          <!-- -3 = ((-3+7)/14)*100 = 28.5% -->
          <!-- 0 = 50% -->
          <!-- +3 = (10/14)*100 = 71.4% -->
          <!-- Values: 3.83=78%, 4.45=81.7%, 4.28=79.8%, 3.99=78.5%, 4.19=79.2% -->
          <!-- 2021: (3.83+7)/14 = 77.4% -->
          <div style="position:absolute;left:28.5%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:1px;height:36px;background:rgba(251,191,36,0.5)"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:8px;color:#fbbf24;">−3</span>
          </div>
          <div style="position:absolute;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:1px;height:36px;background:rgba(255,255,255,0.2)"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:8px;color:var(--muted);">0</span>
          </div>
          <!-- Year needles -->
          <div style="position:absolute;left:77.4%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:2px;height:28px;background:rgba(0,212,255,0.5);border-radius:1px;"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:7px;color:#00d4ff;">'21</span>
          </div>
          <div style="position:absolute;left:81.7%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:2px;height:28px;background:rgba(0,212,255,0.6);border-radius:1px;"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:7px;color:#00d4ff;">'22</span>
          </div>
          <div style="position:absolute;left:79.8%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:2px;height:28px;background:rgba(0,212,255,0.6);border-radius:1px;"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:7px;color:#00d4ff;">'23</span>
          </div>
          <div style="position:absolute;left:78.5%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:2px;height:28px;background:rgba(0,212,255,0.7);border-radius:1px;"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:7px;color:#00d4ff;">'24</span>
          </div>
          <!-- 2025 highlighted -->
          <div style="position:absolute;left:79.2%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;">
            <div style="width:3px;height:36px;background:white;border-radius:1px;box-shadow:0 0 10px rgba(255,255,255,0.8)"></div>
            <span style="font-family:'IBM Plex Mono',monospace;font-size:8px;color:white;font-weight:600;">'25</span>
          </div>
        </div>

        <div style="display:flex;justify-content:space-between;font-family:'IBM Plex Mono',monospace;font-size:9px;color:var(--muted);">
          <span style="color:#f87171">■ Insolvência (&lt;−3)</span>
          <span style="color:#fbbf24">■ Risco (−3 a 0)</span>
          <span style="color:#4ade80">■ Solvência (&gt;0)</span>
        </div>
      </div>

      <div>
        <table class="data-table">
          <thead>
            <tr>
              <th>Ano</th>
              <th>Kanitz (FIk)</th>
              <th>Zona</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>2021</td>
              <td>3,83</td>
              <td style="color:var(--positive)">Solvência</td>
            </tr>
            <tr>
              <td>2022</td>
              <td>4,45</td>
              <td style="color:var(--positive)">Solvência</td>
            </tr>
            <tr>
              <td>2023</td>
              <td>4,28</td>
              <td style="color:var(--positive)">Solvência</td>
            </tr>
            <tr>
              <td>2024</td>
              <td>3,99</td>
              <td style="color:var(--positive)">Solvência</td>
            </tr>
            <tr>
              <td><strong style="color:var(--accent)">2025</strong></td>
              <td class="td-accent"><strong>4,19</strong></td>
              <td style="color:var(--positive)">✦ Solvência</td>
            </tr>
          </tbody>
        </table>
        <div style="margin-top:12px;font-family:'IBM Plex Sans',sans-serif;font-size:12px;color:var(--muted);line-height:1.5;">
          Todos os anos situam-se confortavelmente na <strong style="color:var(--positive)">Área de Solvência</strong>. O FIk de 2022 (4,45) foi o pico do período; 2025 segue em território seguro.
        </div>
      </div>
    </div>
  </div>

  <!-- DIAGNÓSTICO -->
  <div class="section-title animate delay-4">06 — Diagnóstico Estratégico</div>
  <div class="diag-grid animate delay-4">
    <div class="diag-card">
      <div class="diag-question">A empresa é saudável financeiramente?</div>
      <div class="diag-answer" style="color:var(--positive)">✦ Sim</div>
      <div class="diag-text">LC consistentemente acima de 1,0 (1,41 em 2025). Liquidez Seca igual à Corrente indica estoque negligenciável — típico do varejo farmacêutico. Kanitz &gt;3,8 em todo o período.</div>
    </div>
    <div class="diag-card">
      <div class="diag-question">Está eficiente operacionalmente?</div>
      <div class="diag-answer" style="color:var(--positive)">✦ Sim</div>
      <div class="diag-text">Giro do Ativo subiu de 1,58 para 1,68 (+6%). ROA cresceu de 9,4% para 11,3%. Ciclo Financeiro negativo ou próximo de zero — capital de giro autofinanciado pelos fornecedores.</div>
    </div>
    <div class="diag-card">
      <div class="diag-question">Está assumindo risco excessivo?</div>
      <div class="diag-answer" style="color:var(--warning)">◐ Moderado</div>
      <div class="diag-text">Endividamento cresceu de 208% para 233% — estrutura alavancada. CE ~56% em 2025 indica que mais da metade do capital de terceiros é de CP. Liquidez Geral &lt;1 (0,87) merece acompanhamento.</div>
    </div>
    <div class="diag-card">
      <div class="diag-question">Está melhorando ao longo do tempo?</div>
      <div class="diag-answer" style="color:var(--positive)">✦ Sim</div>
      <div class="diag-text">EBITDA +104% em 5 anos. ROA +21%. ROE saltou de 10,3% para 18,9% com estabilização após 2022. Saldo de Tesouraria triplicou, sinalizando folga de caixa crescente e saúde estrutural.</div>
    </div>
  </div>

  <!-- INSIGHT BOX -->
  <div class="insight-box animate delay-4">
    <div class="insight-title">// Síntese & Pontos de Atenção</div>
    <div class="insight-points">
      <div class="insight-point">
        <div class="insight-icon">🏆</div>
        <div class="insight-text">A RD Saúde apresenta <strong>crescimento robusto e consistente</strong> em rentabilidade (EBITDA +104%, ROA +21%) — empresa em trajetória de expansão saudável.</div>
      </div>
      <div class="insight-point">
        <div class="insight-icon">⚡</div>
        <div class="insight-text">O <strong>Ciclo Financeiro negativo</strong> em 2021 e 2025 é uma vantagem competitiva estrutural: fornecedores financiam as operações, reduzindo necessidade de capital de giro externo.</div>
      </div>
      <div class="insight-point">
        <div class="insight-icon">⚠️</div>
        <div class="insight-text">Atenção ao <strong>endividamento crescente</strong> (208% → 233%) e Liquidez Geral &lt;1. Em cenários de crise de crédito, a dependência de CP pode pressionar o caixa.</div>
      </div>
      <div class="insight-point">
        <div class="insight-icon">📊</div>
        <div class="insight-text">A <strong>Margem Líquida estável (~3,2–3,6%)</strong> é característica do varejo farmacêutico de alto volume. A alavancagem financeira é o principal motor do ROE elevado (~19%).</div>
      </div>
    </div>
  </div>

  <footer>
    <div class="footer-note">RD Saúde S.A. · Análise Fundamentalista · Exercícios 2021–2025</div>
    <div class="footer-note">Fórmula Kanitz: 0,05×14 + 1,65×3 + 3,55×2 − 1,06×1 − 0,33×4</div>
  </footer>

</div>
</body>
</html>

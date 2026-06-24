<!DOCTYPE html>
<html lang="es" data-theme="dark">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Taller del Irbis</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
  <script src="https://www.gstatic.com/firebasejs/12.0.0/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/12.0.0/firebase-firestore-compat.js"></script>
  <style>
    :root,
    [data-theme="dark"] {
      --bg: #171109;
      --panel: #221A11;
      --panel2: #2C2114;
      --border: #3A2C1A;
      --gold: #CD8E30;
      --gold-light: #E8B05C;
      --cream: #F3E9D8;
      --muted: #A98F6B;
      --green: #7FAE72;
      --red: #C2584B;
    }

    [data-theme="light"] {
      --bg: #FBF6EC;
      --panel: #FFFFFF;
      --panel2: #F3E9D8;
      --border: #E4D6BA;
      --gold: #B5762A;
      --gold-light: #8C5E22;
      --cream: #2E2414;
      --muted: #7A6A4E;
      --green: #3E7A3A;
      --red: #A23F33;
    }

    body {
      background-color: var(--bg);
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cg fill='none' stroke='%23CD8E30' stroke-width='1.4' opacity='0.07'%3E%3Cpath d='M20 25c4-6 14-6 17 1 5-3 12 1 11 7 6 1 8 9 2 12 2 6-4 11-10 9-3 5-12 5-14-1-6 2-12-3-10-9-5-2-5-10 1-12-1-4 1-7 3-7z'/%3E%3Cpath d='M75 70c4-6 14-6 17 1 5-3 12 1 11 7 6 1 8 9 2 12 2 6-4 11-10 9-3 5-12 5-14-1-6 2-12-3-10-9-5-2-5-10 1-12-1-4 1-7 3-7z'/%3E%3C/g%3E%3C/svg%3E");
      color: var(--cream);
      font-family: 'Iowan Old Style', Georgia, serif;
      min-height: 100vh;
    }

    .sans {
      font-family: ui-sans-serif, system-ui, sans-serif
    }

    .card {
      background: var(--panel);
      border: 1px solid var(--border);
      border-radius: 1rem;
      transition: transform .28s cubic-bezier(.34, 1.2, .64, 1), box-shadow .28s ease, border-color .28s ease;
    }

    .card-interactive {
      cursor: default
    }

    .card-interactive:hover {
      transform: translateY(-4px);
      box-shadow: 0 14px 36px rgba(0, 0, 0, .22), 0 0 0 1px rgba(205, 142, 48, .12);
      border-color: rgba(205, 142, 48, .35);
    }

    [data-theme="light"] .card-interactive:hover {
      box-shadow: 0 12px 28px rgba(46, 36, 20, .12), 0 0 0 1px rgba(181, 118, 42, .2)
    }

    .input-base {
      width: 100%;
      border-radius: .625rem;
      padding: .5625rem .875rem;
      font-size: .875rem;
      background: var(--bg);
      border: 1px solid var(--border);
      color: var(--cream);
      font-family: ui-sans-serif, system-ui, sans-serif;
      transition: border-color .2s, box-shadow .2s, background .2s;
      outline: none;
    }

    .input-base:hover {
      border-color: rgba(205, 142, 48, .45)
    }

    .input-base:focus {
      border-color: var(--gold);
      box-shadow: 0 0 0 3px rgba(205, 142, 48, .18), 0 2px 8px rgba(0, 0, 0, .08);
    }

    select.input-base option {
      background: var(--panel);
      color: var(--cream)
    }

    /* —— Botones principales —— */
    .btn-gold {
      position: relative;
      overflow: hidden;
      isolation: isolate;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: .4rem;
      border-radius: .625rem;
      padding: .65rem 1rem;
      font-size: .875rem;
      font-weight: 600;
      background: linear-gradient(135deg, var(--gold-light) 0%, var(--gold) 55%, #B5762A 100%);
      background-size: 200% 200%;
      color: #1B1208;
      font-family: ui-sans-serif, system-ui, sans-serif;
      cursor: pointer;
      border: none;
      box-shadow: 0 2px 10px rgba(205, 142, 48, .28), inset 0 1px 0 rgba(255, 255, 255, .28);
      transition: transform .22s cubic-bezier(.34, 1.56, .64, 1), box-shadow .25s ease, background-position .4s ease, filter .2s;
    }

    .btn-gold::before {
      content: '';
      position: absolute;
      inset: 0;
      z-index: 0;
      background: linear-gradient(105deg, transparent 35%, rgba(255, 255, 255, .35) 50%, transparent 65%);
      transform: translateX(-120%) skewX(-12deg);
      transition: transform .55s cubic-bezier(.34, 1.2, .64, 1);
    }

    .btn-gold>* {
      position: relative;
      z-index: 1
    }

    .btn-gold:hover {
      transform: translateY(-2px);
      background-position: 100% 50%;
      box-shadow: 0 8px 24px rgba(205, 142, 48, .38), inset 0 1px 0 rgba(255, 255, 255, .32);
      filter: brightness(1.04);
    }

    .btn-gold:hover::before {
      transform: translateX(120%) skewX(-12deg)
    }

    .btn-gold:active {
      transform: translateY(0) scale(.96);
      box-shadow: 0 2px 8px rgba(205, 142, 48, .22)
    }

    .btn-gold:focus-visible {
      outline: 2px solid var(--gold-light);
      outline-offset: 2px
    }

    .btn-ghost {
      position: relative;
      overflow: hidden;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: .4rem;
      border-radius: .625rem;
      padding: .5625rem .875rem;
      font-size: .875rem;
      border: 1px solid var(--border);
      color: var(--cream);
      background: transparent;
      font-family: ui-sans-serif, system-ui, sans-serif;
      cursor: pointer;
      transition: transform .22s cubic-bezier(.34, 1.2, .64, 1), background .22s, border-color .22s, box-shadow .22s, color .2s;
    }

    .btn-ghost:hover {
      background: var(--panel2);
      border-color: rgba(205, 142, 48, .55);
      transform: translateY(-1px);
      box-shadow: 0 6px 16px rgba(0, 0, 0, .14);
      color: var(--gold-light);
    }

    .btn-ghost:active {
      transform: scale(.96);
      box-shadow: none
    }

    .btn-ghost:focus-visible {
      outline: 2px solid var(--gold);
      outline-offset: 2px
    }

    .btn-sm {
      padding: .375rem .625rem;
      font-size: .75rem;
      border-radius: .5rem
    }

    .btn-icon {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 2.125rem;
      height: 2.125rem;
      padding: 0;
      border-radius: .625rem;
      border: 1px solid var(--border);
      background: transparent;
      color: var(--muted);
      cursor: pointer;
      transition: transform .2s cubic-bezier(.34, 1.56, .64, 1), background .2s, border-color .2s, color .2s, box-shadow .2s;
    }

    .btn-icon:hover {
      background: var(--panel2);
      border-color: rgba(205, 142, 48, .5);
      color: var(--gold-light);
      transform: translateY(-1px) scale(1.05);
      box-shadow: 0 4px 12px rgba(0, 0, 0, .12);
    }

    .btn-icon:active {
      transform: scale(.92)
    }

    .btn-icon-danger:hover {
      border-color: var(--red);
      color: var(--red);
      background: rgba(194, 88, 75, .1)
    }

    .btn-link {
      display: inline-flex;
      align-items: center;
      gap: .25rem;
      font-size: .75rem;
      color: var(--gold-light);
      background: none;
      border: none;
      cursor: pointer;
      padding: .125rem .25rem;
      border-radius: .25rem;
      font-family: ui-sans-serif, system-ui, sans-serif;
      transition: color .2s, transform .15s, opacity .2s;
    }

    .btn-link:hover {
      color: var(--gold);
      transform: translateX(2px)
    }

    .btn-link:active {
      transform: scale(.95);
      opacity: .85
    }

    .btn-danger-ghost {
      border-color: rgba(194, 88, 75, .45) !important;
      color: var(--red) !important
    }

    .btn-danger-ghost:hover {
      background: rgba(194, 88, 75, .12) !important;
      border-color: var(--red) !important;
      color: var(--red) !important
    }

    .btn-gold-accent {
      color: var(--gold-light) !important;
      border-color: rgba(205, 142, 48, .4) !important
    }

    .badge {
      font-size: .625rem;
      padding: .125rem .5rem;
      border-radius: 9999px;
      white-space: nowrap;
      background: var(--panel2);
      font-family: ui-sans-serif, system-ui, sans-serif;
      transition: transform .2s ease, box-shadow .2s ease;
    }

    .card-interactive:hover .badge {
      transform: scale(1.03)
    }

    .tab-btn {
      position: relative;
      display: inline-flex;
      align-items: center;
      gap: .4rem;
      padding: .7rem .95rem;
      font-size: .875rem;
      border: none;
      border-bottom: 2px solid transparent;
      white-space: nowrap;
      font-family: ui-sans-serif, system-ui, sans-serif;
      background: transparent;
      cursor: pointer;
      color: var(--muted);
      transition: color .25s ease, background .25s ease, transform .2s ease;
      border-radius: .5rem .5rem 0 0;
    }

    .tab-btn::after {
      content: '';
      position: absolute;
      bottom: -1px;
      left: 50%;
      transform: translateX(-50%);
      width: 0;
      height: 2px;
      border-radius: 2px;
      background: linear-gradient(90deg, var(--gold-light), var(--gold));
      transition: width .32s cubic-bezier(.34, 1.4, .64, 1), left .32s cubic-bezier(.34, 1.4, .64, 1), transform .32s;
    }

    .tab-btn:hover:not(.active) {
      color: var(--gold-light);
      background: rgba(205, 142, 48, .07);
    }

    .tab-btn.active {
      color: var(--gold-light);
      font-weight: 600;
      background: rgba(205, 142, 48, .1);
    }

    .tab-btn.active::after {
      left: 0;
      transform: none;
      width: 100%
    }

    .tab-btn:active {
      transform: scale(.97)
    }

    .field-label {
      display: block;
      font-size: .6875rem;
      font-weight: 600;
      margin-bottom: .25rem;
      letter-spacing: .1em;
      text-transform: uppercase;
      color: var(--muted);
      font-family: ui-sans-serif, system-ui, sans-serif;
    }

    .field-hint {
      display: block;
      font-size: .6875rem;
      margin-top: .25rem;
      color: var(--muted);
      opacity: .8;
      font-family: ui-sans-serif, system-ui, sans-serif
    }

    .paw-divider {
      display: flex;
      align-items: center;
      gap: .5rem;
      margin: 1.25rem 0;
      user-select: none
    }

    .paw-divider::before,
    .paw-divider::after {
      content: '';
      flex: 1;
      height: 1px;
      background: linear-gradient(90deg, transparent, var(--border), transparent)
    }

    .panel2-bg {
      background: var(--panel2)
    }

    .bar-chart-bar {
      height: 24px;
      border-radius: 4px;
      background: var(--gold);
      min-width: 4px;
      transition: width .6s cubic-bezier(.34, 1.2, .64, 1)
    }

    /* —— Animaciones —— */
    @keyframes irbisFade {
      from {
        opacity: 0;
        transform: translateY(10px)
      }

      to {
        opacity: 1;
        transform: translateY(0)
      }
    }

    @keyframes irbisSlideUp {
      from {
        opacity: 0;
        transform: translateY(18px)
      }

      to {
        opacity: 1;
        transform: translateY(0)
      }
    }

    @keyframes irbisScaleIn {
      from {
        opacity: 0;
        transform: scale(.94) translateY(8px)
      }

      to {
        opacity: 1;
        transform: scale(1) translateY(0)
      }
    }

    @keyframes irbisPulse {

      0%,
      100% {
        transform: scale(1)
      }

      50% {
        transform: scale(1.06)
      }
    }

    @keyframes irbisFloat {

      0%,
      100% {
        transform: translateY(0) rotate(-2deg)
      }

      50% {
        transform: translateY(-8px) rotate(2deg)
      }
    }

    @keyframes irbisGlow {

      0%,
      100% {
        box-shadow: 0 0 0 0 rgba(232, 176, 92, 0)
      }

      50% {
        box-shadow: 0 0 20px 4px rgba(232, 176, 92, .25)
      }
    }

    @keyframes irbisShimmer {
      0% {
        background-position: -200% center
      }

      100% {
        background-position: 200% center
      }
    }

    @keyframes countUp {
      from {
        opacity: 0;
        transform: translateY(6px)
      }

      to {
        opacity: 1;
        transform: translateY(0)
      }
    }

    @keyframes modalIn {
      from {
        opacity: 0
      }

      to {
        opacity: 1
      }
    }

    @keyframes modalContentIn {
      from {
        opacity: 0;
        transform: translateY(16px) scale(.98)
      }

      to {
        opacity: 1;
        transform: translateY(0) scale(1)
      }
    }

    @keyframes noteCheck {
      0% {
        transform: scale(.6)
      }

      60% {
        transform: scale(1.15)
      }

      100% {
        transform: scale(1)
      }
    }

    @keyframes progressShine {
      0% {
        transform: translateX(-100%)
      }

      100% {
        transform: translateX(200%)
      }
    }

    @keyframes ripplePop {
      to {
        transform: scale(1);
        opacity: 0
      }
    }

    .fade-in {
      animation: irbisFade .45s cubic-bezier(.34, 1.2, .64, 1) both
    }

    .stagger-item {
      animation: irbisSlideUp .5s cubic-bezier(.34, 1.2, .64, 1) both
    }

    .stagger-item:nth-child(1) {
      animation-delay: .04s
    }

    .stagger-item:nth-child(2) {
      animation-delay: .08s
    }

    .stagger-item:nth-child(3) {
      animation-delay: .12s
    }

    .stagger-item:nth-child(4) {
      animation-delay: .16s
    }

    .stagger-item:nth-child(5) {
      animation-delay: .20s
    }

    .stagger-item:nth-child(6) {
      animation-delay: .24s
    }

    .stagger-item:nth-child(7) {
      animation-delay: .28s
    }

    .stagger-item:nth-child(8) {
      animation-delay: .32s
    }

    .stagger-item:nth-child(9) {
      animation-delay: .36s
    }

    .stagger-item:nth-child(n+10) {
      animation-delay: .40s
    }

    .kpi-card {
      animation: irbisScaleIn .55s cubic-bezier(.34, 1.3, .64, 1) both
    }

    .kpi-card:nth-child(1) {
      animation-delay: .05s
    }

    .kpi-card:nth-child(2) {
      animation-delay: .10s
    }

    .kpi-card:nth-child(3) {
      animation-delay: .15s
    }

    .kpi-card:nth-child(4) {
      animation-delay: .20s
    }

    .kpi-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 28px rgba(0, 0, 0, .18);
      border-color: rgba(205, 142, 48, .3)
    }

    .kpi-value {
      animation: countUp .6s cubic-bezier(.34, 1.2, .64, 1) both
    }

    #logo-icon {
      animation: irbisPulse 3.5s ease-in-out infinite, irbisGlow 4s ease-in-out infinite;
      transition: transform .3s cubic-bezier(.34, 1.56, .64, 1);
    }

    #logo-icon:hover {
      transform: scale(1.12) rotate(-8deg) !important;
      animation-play-state: paused
    }

    #theme-toggle {
      transition: transform .25s cubic-bezier(.34, 1.56, .64, 1), background .2s, border-color .2s, box-shadow .2s;
    }

    #theme-toggle:hover {
      background: var(--panel2);
      border-color: var(--gold);
      transform: rotate(15deg) scale(1.08);
      box-shadow: 0 4px 14px rgba(205, 142, 48, .2);
    }

    #theme-toggle:active {
      transform: rotate(15deg) scale(.94)
    }

    .search-box {
      transition: border-color .25s, box-shadow .25s, transform .2s;
    }

    .search-box:focus-within {
      border-color: rgba(205, 142, 48, .6) !important;
      box-shadow: 0 0 0 3px rgba(205, 142, 48, .14);
      transform: translateY(-1px);
    }

    .note-check {
      transition: background .2s, border-color .2s, transform .2s cubic-bezier(.34, 1.56, .64, 1);
    }

    .note-check:hover {
      transform: scale(1.15);
      border-color: var(--gold-light) !important
    }

    .note-check.done {
      animation: noteCheck .35s cubic-bezier(.34, 1.56, .64, 1)
    }

    .progress-bar {
      height: 10px;
      border-radius: 9999px;
      background: var(--panel2);
      overflow: hidden;
      position: relative
    }

    .progress-fill {
      height: 100%;
      border-radius: 9999px;
      background: linear-gradient(90deg, var(--gold), var(--gold-light), var(--gold));
      background-size: 200% 100%;
      transition: width .8s cubic-bezier(.34, 1.2, .64, 1);
      position: relative;
      overflow: hidden;
    }

    .progress-fill::after {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, .35), transparent);
      animation: progressShine 2.5s ease-in-out infinite;
    }

    .modal-overlay {
      position: fixed;
      inset: 0;
      z-index: 50;
      display: flex;
      align-items: flex-start;
      justify-content: center;
      overflow: auto;
      padding: 1rem;
      background: rgba(0, 0, 0, .72);
      backdrop-filter: blur(4px);
      animation: modalIn .3s ease both;
    }

    .modal-overlay>.w-full {
      animation: modalContentIn .4s cubic-bezier(.34, 1.2, .64, 1) both
    }

    .cal-day {
      transition: transform .2s cubic-bezier(.34, 1.56, .64, 1), background .2s, box-shadow .2s;
    }

    .cal-day:hover:not([style*="var(--gold)"]) {
      transform: scale(1.08);
      background: var(--panel2) !important
    }

    .cal-day:active {
      transform: scale(.95)
    }

    .tag-pill {
      transition: transform .2s, box-shadow .2s, filter .2s;
    }

    .tag-pill:hover {
      transform: translateY(-1px);
      filter: brightness(1.08)
    }

    .tag-pill:active {
      transform: scale(.96)
    }

    ::-webkit-scrollbar {
      height: 6px;
      width: 6px
    }

    ::-webkit-scrollbar-thumb {
      background: var(--border);
      border-radius: 4px;
      transition: background .2s
    }

    ::-webkit-scrollbar-thumb:hover {
      background: var(--gold)
    }

    @media (prefers-reduced-motion:reduce) {

      *,
      *::before,
      *::after {
        animation-duration: .01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: .01ms !important
      }
    }

    @media print {
      body * {
        visibility: hidden
      }

      #price-list-print,
      #price-list-print * {
        visibility: visible
      }

      #price-list-print {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        background: white;
        color: black
      }

      .no-print {
        display: none !important
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header id="app-header" class="sticky top-0 z-20 backdrop-blur-md sans"
    style="border-bottom:1px solid var(--border);transition:box-shadow .3s ease">
    <div class="max-w-6xl mx-auto px-4 py-4 flex items-center gap-3 flex-wrap">
      <div id="logo-icon"
        class="w-10 h-10 rounded-full flex items-center justify-center text-lg shrink-0 text-[#1B1208]"
        style="background:radial-gradient(circle at 30% 30%,var(--gold-light),var(--gold))">🐆</div>
      <div class="mr-auto">
        <h1 class="text-lg font-semibold leading-tight tracking-wide" style="color:var(--cream)">Taller del Irbis</h1>
        <p class="text-xs sans" style="color:var(--muted)">Gestión de bordados</p>
      </div>
      <div class="search-box flex items-center gap-1.5 rounded-lg px-2.5 py-1.5 sans"
        style="background:var(--panel2);border:1px solid var(--border)">
        <i data-lucide="search" style="width:14px;height:14px;color:var(--muted)"></i>
        <input id="global-search" placeholder="Buscar diseño…"
          class="bg-transparent text-sm focus:outline-none w-32 sm:w-44 sans" style="color:var(--cream)" />
      </div>
      <button id="theme-toggle" class="btn-icon w-9 h-9" style="color:var(--gold-light)">
        <i data-lucide="sun" id="theme-icon" style="width:16px;height:16px"></i>
      </button>
    </div>
    <nav id="tab-nav" class="max-w-6xl mx-auto px-4 flex gap-0.5 overflow-x-auto"></nav>
  </header>

  <main class="max-w-6xl mx-auto px-4 py-6 pb-20" id="main-content"></main>

  <!-- PRICE LIST OVERLAY -->
  <div id="price-list-overlay" class="modal-overlay" style="display:none">
    <div class="w-full max-w-xl my-8">
      <div class="flex justify-end gap-2 mb-2 no-print">
        <button onclick="window.print()" class="btn-gold"><i data-lucide="printer" style="width:14px;height:14px"></i>
          Imprimir / PDF</button>
        <button onclick="closePriceList()" class="btn-ghost"><i data-lucide="x" style="width:14px;height:14px"></i>
          Cerrar</button>
      </div>
      <div id="price-list-print"
        style="background:#FEFCF7;color:#1E1608;font-family:'Georgia',serif;border-radius:16px;overflow:hidden;box-shadow:0 8px 40px rgba(0,0,0,.3)">
        <div style="background:linear-gradient(135deg,#2C1F0A,#3D2B10);padding:36px 40px 28px;color:#F3E9D8">
          <div style="display:flex;align-items:center;gap:16px;margin-bottom:12px">
            <div style="font-size:42px;line-height:1">🐆</div>
            <div>
              <div style="font-size:22px;font-weight:700;letter-spacing:.04em;color:#E8B05C">Taller del Irbis</div>
              <div
                style="font-size:11px;letter-spacing:.18em;text-transform:uppercase;color:#A98F6B;font-family:ui-sans-serif,system-ui;margin-top:2px">
                Bordados artesanales · a máquina</div>
            </div>
          </div>
          <div style="height:1px;background:rgba(205,142,48,.35);margin:16px 0 14px"></div>
          <div style="display:flex;justify-content:space-between;align-items:flex-end">
            <div>
              <div style="font-size:18px;font-weight:600;color:#E8B05C;letter-spacing:.02em">Lista de precios</div>
              <div id="price-list-date"
                style="font-size:11px;color:#A98F6B;font-family:ui-sans-serif,system-ui;margin-top:3px"></div>
            </div>
            <div id="price-list-counts"
              style="text-align:right;font-size:11px;color:#A98F6B;font-family:ui-sans-serif,system-ui"></div>
          </div>
        </div>
        <div id="price-list-body" style="padding:28px 40px 36px"></div>
      </div>
    </div>
  </div>

  <script>
    // =====================================================================
    // CONSTANTS
    // =====================================================================
    const DEFAULT_TYPES = ["Pasapañuelo", "Pañuelo", "Remera", "Gorra", "Parche", "Insignia", "Otro"];
    const HOOP_SIZES = [{ label: "14x14 cm", cm: 14 }, { label: "20x20 cm", cm: 20 }, { label: "Otro", cm: 0 }];
    const MATERIAL_KINDS = [{ key: "tela", label: "Tela / Gabardina" }, { key: "entretela", label: "Entretela" }, { key: "hilo", label: "Hilo" }, { key: "otro", label: "Otro" }];
    const ESTADOS = ["Cotizado", "En curso", "Vendido", "Entregado"];
    const ESTADO_COLOR = { Cotizado: "var(--muted)", "En curso": "var(--gold-light)", Vendido: "var(--green)", Entregado: "#6FA0C9" };
    const FIN_CATS = [{ key: "ingreso", label: "Ingreso", color: "var(--green)" }, { key: "gasto", label: "Gasto", color: "var(--red)" }, { key: "reinversion", label: "Reinversión", color: "var(--gold-light)" }];
    const DEFAULT_SETTINGS = { marginCm: 3, mmPerStitch: 3, colorWasteCm: 20 };
    const POST_TAGS = [{ key: "publicacion", label: "Publicación", color: "#6FA0C9" }, { key: "historia", label: "Historia", color: "#E8B05C" }, { key: "reel", label: "Reel", color: "#C97FAE" }];
    const MONTHS = ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"];
    const MONTHS_SHORT = ["Ene", "Feb", "Mar", "Abr", "May", "Jun", "Jul", "Ago", "Sep", "Oct", "Nov", "Dic"];
    const WEEKDAYS = ["Lu", "Ma", "Mi", "Ju", "Vi", "Sá", "Do"];
    const TABS = [
      { key: "inicio", label: "Inicio", icon: "paw-print" },
      { key: "calculadora", label: "Calculadora", icon: "calculator" },
      { key: "historial", label: "Historial", icon: "history" },
      { key: "calendario", label: "Calendario", icon: "calendar-days" },
      { key: "clientes", label: "Clientes", icon: "users" },
      { key: "galeria", label: "Galería", icon: "images" },
      { key: "proveedores", label: "Proveedores", icon: "truck" },
      { key: "inventario", label: "Inventario", icon: "boxes" },
      { key: "resumen", label: "Resumen", icon: "bar-chart-3" },
      { key: "herramientas", label: "Herramientas", icon: "settings" },
    ];

    // =====================================================================
    // STATE
    // =====================================================================
    let STATE = {
      tab: "inicio",
      theme: "dark",
      types: [...DEFAULT_TYPES],
      products: [],
      materials: [],
      finance: [],
      settings: { ...DEFAULT_SETTINGS },
      posts: [],
      clients: [],
      suppliers: [],
      templates: [],
      notes: [],
      salesGoal: 0,
      search: "",
    };

    // =====================================================================
    // STORAGE
    // =====================================================================
    async function load() {

      try {
        const snap = await getDoc(
          doc(db, "irbis", "principal")
        );
        if (snap.exists()) {
          const data = snap.data();
          Object.keys(data).forEach(k => {
            if (k in STATE) {
              STATE[k] = data[k];
            }
          });
          return;
        }
      } catch (e) {
        console.error("Firebase load error:", e);
      }
      // Respaldo: localStorage
      const keys = [
        "theme",
        "types",
        "products",
        "materials",
        "finance",
        "settings",
        "posts",
        "clients",
        "suppliers",
        "templates",
        "notes",
        "salesGoal"
      ];
      keys.forEach(k => {
        try {
          const v = localStorage.getItem("irbis_" + k);
          if (v != null) STATE[k] = JSON.parse(v);
        } catch (e) { }
      });
    }
      async function save(key) {
        try {
        await db
          .collection("irbis")
          .doc("principal")
          .set(STATE);

      } catch (e) {
        console.error("Firebase save error:", e);
      }
      }
      function saveAll() {
        ["theme", "types", "products", "materials", "finance", "settings", "posts", "clients", "suppliers", "templates", "notes", "salesGoal"]
        .forEach(k => save(k));
      }
      function set(key, val) {
        STATE[key] = val;
        save(key);
      }

      // =====================================================================
      // UTILS
      // =====================================================================
      const uid = () => Math.random().toString(36).slice(2, 10) + Date.now().toString(36);
      const money = n => "$" + (Number(n) || 0).toLocaleString("es-AR", { maximumFractionDigits: 0 });
      const today = () => new Date().toISOString().slice(0, 10);
      const round2 = n => Math.round(n * 100) / 100;
      const esc = s => String(s || "").replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;").replace(/"/g, "&quot;");

      function autoCalc(product, materials, settings) {
        const margin = Number(settings.marginCm) || 0;
        const sideCm = (Number(product.hoopCm) || 0) + margin * 2;
        const areaM2 = sideCm > 0 ? Math.pow(sideCm / 100, 2) : 0;
        const tela = materials.find(m => m.id === product.calc?.telaId);
        const entretela = materials.find(m => m.id === product.calc?.entretelaId);
        const hilo = materials.find(m => m.id === product.calc?.hiloId);
        const telaCost = tela && tela.pricePerM2 ? areaM2 * tela.pricePerM2 : 0;
        const entretelaCost = entretela && entretela.pricePerM2 ? areaM2 * entretela.pricePerM2 : 0;
        const stitches = Number(product.calc?.stitches) || 0;
        const colors = Number(product.calc?.colors) || 0;
        const mmPerStitch = Number(settings.mmPerStitch) || 0;
        const colorWasteCm = Number(settings.colorWasteCm) || 0;
        const threadMm = stitches * mmPerStitch + colors * colorWasteCm * 10;
        const threadMeters = threadMm / 1000;
        const hiloCost = hilo && hilo.pricePerMeter ? threadMeters * hilo.pricePerMeter : 0;
        return { areaM2, telaCost, entretelaCost, threadMeters, hiloCost, sideCm };
      }
      function calcCost(p) {
        const items = (p.items || []).reduce((s, it) => s + (Number(it.cost) || 0), 0);
        const labor = (Number(p.laborHours) || 0) * (Number(p.laborRate) || 0);
        return items + labor;
      }
      function pendingAmount(p) {
        const total = (Number(p.salePrice) || 0) * (Number(p.quantity) || 1);
        return Math.max(0, total - (Number(p.amountPaid) || 0));
      }
      function greet() {
        const h = new Date().getHours();
        return h < 12 ? "Buen día" : h < 19 ? "Buenas tardes" : "Buenas noches";
      }
      function dateStr(d) { return d.toISOString().slice(0, 10) }
      function formatDate(s) { if (!s) return "—"; const [y, m, d] = s.split("-"); return `${d}/${m}/${y}` }

      async function compressImage(file, maxW = 700) {
        return new Promise((resolve, reject) => {
          const reader = new FileReader();
          reader.onload = e => {
            const img = new Image();
            img.onload = () => {
              const scale = Math.min(1, maxW / img.width);
              const canvas = document.createElement("canvas");
              canvas.width = img.width * scale; canvas.height = img.height * scale;
              canvas.getContext("2d").drawImage(img, 0, 0, canvas.width, canvas.height);
              resolve(canvas.toDataURL("image/jpeg", 0.75));
            };
            img.onerror = reject;
            img.src = e.target.result;
          };
          reader.onerror = reject;
          reader.readAsDataURL(file);
        });
      }

      // =====================================================================
      // RENDER ENGINE
      // =====================================================================
      let _currentRenderFn = null;
      function render(fn) {
        _currentRenderFn = fn || _currentRenderFn;
        if (_currentRenderFn) _currentRenderFn();
        lucide.createIcons();
      }

      function renderApp() {
        // Theme
        document.documentElement.setAttribute("data-theme", STATE.theme);
        const isDark = STATE.theme === "dark";
        document.getElementById("app-header").style.background = isDark ? "rgba(23,17,9,0.92)" : "rgba(251,246,236,0.92)";
        // Theme icon
        document.getElementById("theme-icon").setAttribute("data-lucide", isDark ? "sun" : "moon");
        // Nav
        const nav = document.getElementById("tab-nav");
        nav.innerHTML = TABS.map(t => `
    <button onclick="switchTab('${t.key}')" class="tab-btn${STATE.tab === t.key ? " active" : ""}">
      <i data-lucide="${t.icon}" style="width:14px;height:14px"></i>${t.label}
    </button>`).join("");
        // Main
        const main = document.getElementById("main-content");
        main.className = "max-w-6xl mx-auto px-4 py-6 pb-20";
        void main.offsetWidth;
        main.classList.add("fade-in");
        switch (STATE.tab) {
          case "inicio": main.innerHTML = renderDashboard(); break;
          case "calculadora": main.innerHTML = renderCalculadora(); break;
          case "historial": main.innerHTML = renderHistorial(); break;
          case "calendario": main.innerHTML = renderCalendario(); break;
          case "clientes": main.innerHTML = renderClientes(); break;
          case "galeria": main.innerHTML = renderGaleria(); break;
          case "proveedores": main.innerHTML = renderProveedores(); break;
          case "inventario": main.innerHTML = renderInventario(); break;
          case "resumen": main.innerHTML = renderResumen(); break;
          case "herramientas": main.innerHTML = renderHerramientas(); break;
        }
        lucide.createIcons();
        attachTabListeners();
      }

      function switchTab(key) {
        STATE.tab = key;
        // Reset form state for modules
        _calcState = { editing: null, showNewType: false, newType: "" };
        _clientState = { form: null, expanded: null };
        _supplierState = { form: null };
        _inventoryState = { form: null, historyOpen: null };
        _resumenState = { form: null };
        _calState = { selected: dateStr(new Date()), cursor: new Date(), form: null };
        renderApp();
      }

      function attachTabListeners() {
        const gs = document.getElementById("global-search");
        if (gs) {
          gs.value = STATE.search || "";
          gs.oninput = e => { STATE.search = e.target.value; };
          gs.onkeydown = e => { if (e.key === "Enter" && STATE.search.trim()) { switchTab("historial") } };
        }
        document.getElementById("theme-toggle").onclick = () => {
          STATE.theme = STATE.theme === "dark" ? "light" : "dark";
          save("theme");
          renderApp();
        };
      }

      // =====================================================================
      // COMPONENTS (HTML string helpers)
      // =====================================================================
      function field(label, html, hint = "") {
        return `<label class="block mb-3">
    <span class="field-label">${esc(label)}</span>
    ${html}
    ${hint ? `<span class="field-hint">${esc(hint)}</span>` : ""}
  </label>`;
      }
      function inputEl(attrs, extraStyle = "") {
        return `<input class="input-base" style="${extraStyle}" ${attrs} />`;
      }
      function selectEl(name, options, value, attrs = "", extraStyle = "") {
        const opts = options.map(o => {
          const v = typeof o === "object" ? o.value : o;
          const l = typeof o === "object" ? o.label : o;
          return `<option value="${esc(v)}"${v === value ? " selected" : ""}>${esc(l)}</option>`;
        }).join("");
        return `<select class="input-base sans" style="${extraStyle}" ${attrs}>${opts}</select>`;
      }
      function textareaEl(attrs, extraStyle = "") {
        return `<textarea class="input-base" style="${extraStyle}" ${attrs}></textarea>`;
      }
      function pawDivider() { return `<div class="paw-divider"><span style="color:var(--border);font-size:14px;letter-spacing:6px">🐾</span></div>`; }
      function kpiCard(label, value, color = "var(--gold-light)", sub = "") {
        return `<div class="card kpi-card p-4">
    <p class="text-xs uppercase tracking-widest mb-1 sans" style="color:var(--muted)">${esc(label)}</p>
    <p class="text-2xl font-bold kpi-value" style="color:${color};font-family:ui-sans-serif,system-ui">${value}</p>
    ${sub ? `<p class="text-xs mt-0.5 sans" style="color:var(--muted)">${sub}</p>` : ""}
  </div>`;
      }
      function badge(text, color) {
        return `<span class="badge" style="color:${color}">${esc(text)}</span>`;
      }
      function alertBox(icon, title, items, color = "var(--red)") {
        if (!items.length) return "";
        return `<div class="card p-4 mb-3" style="border-color:${color}20">
    <div class="flex items-center gap-2 mb-2 sans text-xs font-semibold uppercase tracking-widest" style="color:${color}">
      <i data-lucide="${icon}" style="width:13px;height:13px"></i>${esc(title)}
    </div>
    <div class="space-y-1 sans text-xs" style="color:var(--cream)">
      ${items.map(i => `<div class="flex items-center justify-between gap-2"><span>${esc(i.label)}</span><span style="color:${color}">${esc(i.value)}</span></div>`).join("")}
    </div>
  </div>`;
      }

      // =====================================================================
      // DASHBOARD
      // =====================================================================
      function renderDashboard() {
        const { products, materials, finance, posts, notes, salesGoal } = STATE;
        const now = new Date();
        const thisMonth = now.getMonth(), thisYear = now.getFullYear();
        const totals = { ingreso: 0, gasto: 0, reinversion: 0 };
        finance.forEach(f => { if (totals[f.type] !== undefined) totals[f.type] += (Number(f.amount) || 0) });
        const balance = totals.ingreso - totals.gasto - totals.reinversion;
        const vendidos = products.filter(p => p.estado === "Vendido" || p.estado === "Entregado");
        const thisMonthInc = finance.filter(f => f.type === "ingreso" && new Date(f.date).getMonth() === thisMonth && new Date(f.date).getFullYear() === thisYear).reduce((s, f) => s + (Number(f.amount) || 0), 0);
        const lowStock = materials.filter(m => m.minStock && Number(m.stockQty) <= Number(m.minStock));
        const pendCobro = products.filter(p => (p.estado === "Vendido" || p.estado === "Entregado") && pendingAmount(p) > 0);
        const in7 = new Date(now); in7.setDate(in7.getDate() + 7);
        const proxEntregas = products.filter(p => p.deliveryDate && p.estado !== "Entregado" && new Date(p.deliveryDate) >= new Date(dateStr(now)) && new Date(p.deliveryDate) <= in7).sort((a, b) => a.deliveryDate > b.deliveryDate ? 1 : -1);
        const proxPubs = posts.filter(p => p.date >= dateStr(now)).sort((a, b) => a.date > b.date ? 1 : -1).slice(0, 3);
        const goalPct = salesGoal > 0 ? Math.min(100, (thisMonthInc / salesGoal * 100).toFixed(1)) : 0;

        return `
  <div>
    <!-- HERO -->
    <div class="card card-interactive p-6 mb-5 relative overflow-hidden stagger-item">
      <div class="absolute -right-6 -top-6 text-7xl opacity-10 select-none pointer-events-none" style="animation:irbisFloat 4s ease-in-out infinite">🐆</div>
      <p class="text-xs uppercase tracking-widest mb-1 sans" style="color:var(--gold-light)">${greet()}</p>
      <h2 class="text-xl font-semibold mb-1">Bienvenida al Taller del Irbis</h2>
      <p class="text-sm sans mb-4" style="color:var(--muted)">${products.length} diseños · ${vendidos.length} vendidos · ${materials.length} insumos</p>
      <div class="flex flex-wrap gap-2">
        <button onclick="switchTab('calculadora')" class="btn-gold"><i data-lucide="sparkles" style="width:14px;height:14px"></i> Calcular diseño nuevo</button>
        <button onclick="switchTab('resumen')" class="btn-ghost">Ver resumen <i data-lucide="arrow-right" style="width:13px;height:13px"></i></button>
      </div>
    </div>

    <!-- KPIs -->
    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 mb-5">
      ${kpiCard("Diseños totales", products.length, "var(--gold-light)")}
      ${kpiCard("Vendidos / Entregados", vendidos.length, "var(--green)")}
      ${kpiCard("Ingresos del mes", money(thisMonthInc), "var(--gold-light)")}
      ${kpiCard("Balance total", money(balance), balance >= 0 ? "var(--green)" : "var(--red)")}
    </div>

    <!-- META MENSUAL -->
    ${salesGoal > 0 ? `<div class="card p-4 mb-5">
      <div class="flex justify-between items-center mb-2">
        <p class="text-xs sans font-semibold uppercase tracking-widest" style="color:var(--gold-light)">Meta mensual</p>
        <span class="text-xs sans" style="color:var(--muted)">${money(thisMonthInc)} / ${money(salesGoal)}</span>
      </div>
      <div class="progress-bar"><div class="progress-fill" style="width:${goalPct}%"></div></div>
      <p class="text-xs mt-1 sans" style="color:var(--muted)">${goalPct}% completado</p>
    </div>`: ""}

    ${pawDivider()}

    <!-- ALERTAS -->
    <div class="mb-5">
      <p class="text-xs sans font-semibold uppercase tracking-widest mb-3" style="color:var(--muted)">Alertas críticas</p>
      ${alertBox("alert-triangle", "Stock bajo", lowStock.map(m => ({ label: m.name, value: `${m.stockQty} restantes` })), "var(--red)")}
      ${alertBox("receipt", "Cobros pendientes", pendCobro.map(p => ({ label: p.name, value: money(pendingAmount(p)) })), "var(--gold-light)")}
      ${alertBox("calendar-clock", "Entregas próximas (7 días)", proxEntregas.map(p => ({ label: p.name, value: formatDate(p.deliveryDate) })), "#6FA0C9")}
      ${!lowStock.length && !pendCobro.length && !proxEntregas.length ?
            `<div class="card p-4 text-center text-sm sans" style="color:var(--muted)">Sin alertas críticas. ¡Todo en orden! 🐾</div>` : ""}
    </div>

    ${pawDivider()}

    <!-- PRÓXIMAS PUBS + NOTAS -->
    <div class="grid md:grid-cols-2 gap-4">
      <div class="card p-4">
        <div class="flex items-center gap-1.5 text-xs sans font-semibold uppercase tracking-widest mb-3" style="color:var(--gold-light)">
          <i data-lucide="calendar-days" style="width:13px;height:13px"></i> Próximas publicaciones
        </div>
        ${proxPubs.length === 0 ?
            `<p class="text-sm sans" style="color:var(--muted)">Sin publicaciones planificadas.</p>` :
            `<div class="space-y-2">${proxPubs.map(p => {
              const tag = POST_TAGS.find(t => t.key === p.tag);
              return `<div class="flex items-center gap-3">
              <div class="text-xs px-2 py-1 rounded-lg shrink-0 sans" style="background:var(--panel2);color:var(--muted)">${formatDate(p.date)}</div>
              <p class="text-sm flex-1 truncate">${esc(p.title)}</p>
              ${badge(tag?.label || p.tag, tag?.color || "var(--muted)")}
            </div>`;
            }).join("")}</div>`}
      </div>

      <div class="card p-4">
        <div class="flex items-center gap-1.5 text-xs sans font-semibold uppercase tracking-widest mb-3" style="color:var(--gold-light)">
          <i data-lucide="sticky-note" style="width:13px;height:13px"></i> Notas rápidas
        </div>
        <div class="flex gap-2 mb-3">
          <input id="note-input" placeholder="Ej: comprar hilo blanco…" class="input-base flex-1" style="font-family:ui-sans-serif" onkeydown="if(event.key==='Enter')addNote()" />
          <button onclick="addNote()" class="btn-gold"><i data-lucide="plus" style="width:14px;height:14px"></i></button>
        </div>
        ${notes.length === 0 ?
            `<p class="text-sm sans" style="color:var(--muted)">Sin notas pendientes.</p>` :
            `<div class="space-y-1.5 sans">${notes.map(n => `
            <div class="flex items-center gap-2 text-sm stagger-item">
              <button onclick="toggleNote('${n.id}')" class="note-check w-4 h-4 rounded flex items-center justify-center shrink-0${n.done ? " done" : ""}" style="border:1px solid ${n.done ? "var(--green)" : "var(--border)"};background:${n.done ? "var(--green)" : "transparent"};cursor:pointer">
                ${n.done ? `<i data-lucide="check" style="width:11px;height:11px;color:#171109"></i>` : ""}
              </button>
              <span class="flex-1" style="text-decoration:${n.done ? "line-through" : "none"};color:${n.done ? "var(--muted)" : "var(--cream)"}">${esc(n.text)}</span>
              <button onclick="removeNote('${n.id}')" class="btn-icon btn-icon-danger" style="width:1.75rem;height:1.75rem"><i data-lucide="x" style="width:13px;height:13px"></i></button>
            </div>`).join("")}</div>`}
      </div>
    </div>
  </div>`;
      }

      function addNote() {
        const inp = document.getElementById("note-input");
        if (!inp || !inp.value.trim()) return;
        STATE.notes = [{ id: uid(), text: inp.value.trim(), done: false }, ...STATE.notes];
        save("notes");
        renderApp();
      }
      function toggleNote(id) {
        STATE.notes = STATE.notes.map(n => n.id === id ? { ...n, done: !n.done } : n);
        save("notes");
        renderApp();
      }
      function removeNote(id) {
        STATE.notes = STATE.notes.filter(n => n.id !== id);
        save("notes");
        renderApp();
      }

      // =====================================================================
      // CALCULADORA
      // =====================================================================
      let _calcState = { editing: null, showNewType: false, newType: "" };

      function renderCalculadora() {
        const { products, materials, types, clients, templates } = STATE;
        const cs = _calcState;
        if (cs.editing) {
          return renderProductForm(cs.editing);
        }
        return `
  <div>
    <div class="flex items-center justify-between mb-4 flex-wrap gap-2">
      <div>
        <h2 class="text-base font-semibold" style="color:var(--gold-light)">Calculadora de precios</h2>
        <p class="text-xs sans" style="color:var(--muted)">${products.length} diseños cargados</p>
      </div>
      <div class="flex gap-2 items-center sans">
        ${templates.length > 0 ? `<select class="input-base sans" style="width:auto" onchange="if(this.value)startFromTemplate(this.value);this.value=''">
          <option value="">Usar plantilla…</option>
          ${templates.map(t => `<option value="${t.id}">${esc(t.name)}</option>`).join("")}
        </select>`: ""}
        <button onclick="startNewProduct()" class="btn-gold"><i data-lucide="plus" style="width:15px;height:15px"></i> Nuevo diseño</button>
      </div>
    </div>
    ${products.length === 0 ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Todavía no cargaste ningún diseño. Creá el primero para calcular su precio.</div>` :
            `<div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        ${products.map(p => {
              const cost = calcCost(p);
              const qty = Number(p.quantity) || 1;
              const profit = ((Number(p.salePrice) || 0) - cost) * qty;
              return `<div class="card card-interactive overflow-hidden flex flex-col stagger-item">
            <div class="h-32 flex items-center justify-center overflow-hidden" style="background:var(--panel2)">
              ${p.image ? `<img src="${p.image}" class="w-full h-full object-cover transition-transform duration-500 hover:scale-105" />` : `<i data-lucide="image" style="width:26px;height:26px;color:var(--border)"></i>`}
            </div>
            <div class="p-3 flex-1 flex flex-col sans">
              <div class="flex items-start justify-between gap-2 mb-2">
                <div><p class="font-medium text-sm">${esc(p.name || "Sin nombre")}</p><p class="text-xs" style="color:var(--muted)">${esc(p.type)} · ${esc(p.hoop)}</p></div>
                ${badge(p.estado, ESTADO_COLOR[p.estado] || "var(--muted)")}
              </div>
              <div class="text-xs space-y-0.5 mb-2" style="color:var(--cream)">
                <div class="flex justify-between"><span style="color:var(--muted)">Costo unit.</span><span>${money(cost)}</span></div>
                <div class="flex justify-between"><span style="color:var(--muted)">Venta unit.</span><span>${money(p.salePrice)}</span></div>
                <div class="flex justify-between" style="color:${profit >= 0 ? "var(--green)" : "var(--red)"};font-weight:600"><span>Ganancia (x${qty})</span><span>${money(profit)}</span></div>
              </div>
              <div class="flex gap-2 mt-auto">
                <button onclick="editProduct('${p.id}')" class="btn-ghost btn-sm flex-1"><i data-lucide="pencil" style="width:12px;height:12px"></i> Editar</button>
                <button onclick="saveAsTemplate('${p.id}')" class="btn-ghost btn-sm btn-gold-accent" title="Guardar como plantilla"><i data-lucide="layers" style="width:13px;height:13px"></i></button>
                <button onclick="deleteProduct('${p.id}')" class="btn-ghost btn-sm btn-danger-ghost"><i data-lucide="trash-2" style="width:12px;height:12px"></i></button>
              </div>
            </div>
          </div>`;
            }).join("")}
      </div>`}
  </div>`;
      }

      function blankProduct() {
        const { types } = STATE;
        return {
          id: uid(), name: "", type: types[0] || "", hoop: HOOP_SIZES[0].label, hoopCm: HOOP_SIZES[0].cm,
          date: today(), estado: "Cotizado", image: null, items: [],
          calc: { telaId: "", entretelaId: "", stitches: "", colors: 1, hiloId: "" },
          laborHours: "", laborRate: "", quantity: 1, salePrice: "", clientId: "", deliveryDate: "", amountPaid: "",
          alloc: { gasto: "", ingreso: "", reinversion: "" }, notes: ""
        };
      }
      function startNewProduct() { _calcState.editing = blankProduct(); renderApp(); }
      function editProduct(id) {
        _calcState.editing = STATE.products.find(p => p.id === id) || null;
        if (_calcState.editing) renderApp();
      }
      function startFromTemplate(tid) {
        const t = STATE.templates.find(x => x.id === tid); if (!t) return;
        _calcState.editing = { ...blankProduct(), type: t.type, hoop: t.hoop, hoopCm: t.hoopCm, calc: t.calc, items: t.items || [], laborHours: t.laborHours, laborRate: t.laborRate };
        renderApp();
      }
      function deleteProduct(id) {
        if (!confirm("¿Eliminar este diseño?")) return;
        STATE.products = STATE.products.filter(p => p.id !== id); save("products"); renderApp();
      }
      function saveAsTemplate(id) {
        const p = STATE.products.find(x => x.id === id); if (!p) return;
        const name = prompt("Nombre para esta plantilla:", `${p.type} ${p.hoop}`); if (!name) return;
        STATE.templates = [{ id: uid(), name, type: p.type, hoop: p.hoop, hoopCm: p.hoopCm, calc: p.calc, items: (p.items || []).filter(i => i.auto), laborHours: p.laborHours, laborRate: p.laborRate }, ...STATE.templates];
        save("templates"); alert("Plantilla guardada.");
      }

      function applyAutoItems(editing) {
        const c = autoCalc(editing, STATE.materials, STATE.settings);
        const manual = (editing.items || []).filter(it => !it.auto);
        const auto = [];
        if (c.telaCost > 0) auto.push({ id: "auto-tela", auto: true, name: "Tela / Gabardina (auto)", cost: round2(c.telaCost) });
        if (c.entretelaCost > 0) auto.push({ id: "auto-entretela", auto: true, name: "Entretela (auto)", cost: round2(c.entretelaCost) });
        if (c.hiloCost > 0) auto.push({ id: "auto-hilo", auto: true, name: `Hilo (auto, ${c.threadMeters.toFixed(1)}m)`, cost: round2(c.hiloCost) });
        editing.items = [...auto, ...manual];
        return c;
      }

      function renderProductForm(p) {
        const { materials, types, clients, settings } = STATE;
        const cs = _calcState;
        const telas = materials.filter(m => m.kind === "tela");
        const entretelas = materials.filter(m => m.kind === "entretela");
        const hilos = materials.filter(m => m.kind === "hilo");
        const calc = autoCalc(p, materials, settings);
        const cost = calcCost(p);
        const qty = Number(p.quantity) || 1;
        const profitUnit = (Number(p.salePrice) || 0) - cost;
        const marginPct = p.salePrice ? ((profitUnit / Number(p.salePrice)) * 100).toFixed(0) : null;
        const pending = pendingAmount(p);
        const allocTotal = (Number(p.alloc?.gasto) || 0) + (Number(p.alloc?.ingreso) || 0) + (Number(p.alloc?.reinversion) || 0);

        return `<div class="max-w-2xl fade-in">
    <button onclick="cancelEditProduct()" class="btn-link mb-4"><i data-lucide="x" style="width:13px;height:13px"></i> Volver</button>
    <div class="card p-5">
      <div class="grid sm:grid-cols-2 gap-x-4">
        ${field("Nombre del diseño", `<input class="input-base" id="pf-name" value="${esc(p.name)}" placeholder="Ej: Pañuelo flores azules" oninput="pf_set('name',this.value)" />`)}
        ${field("Fecha", `<input class="input-base" type="date" id="pf-date" value="${p.date}" oninput="pf_set('date',this.value)" />`)}
        ${field("Categoría", `<div class="flex gap-2">
          <select class="input-base sans" oninput="pf_set('type',this.value)">${types.map(t => `<option${t === p.type ? " selected" : ""}>${esc(t)}</option>`).join("")}</select>
          <button onclick="toggleNewType()" class="btn-link">+ tipo</button>
        </div>
        ${cs.showNewType ? `<div class="flex gap-2 mt-2">
          <input class="input-base" id="new-type-inp" value="${esc(cs.newType)}" placeholder="Nuevo tipo" oninput="_calcState.newType=this.value" />
          <button onclick="addNewType()" class="btn-icon" style="color:var(--green)"><i data-lucide="check" style="width:18px;height:18px"></i></button>
        </div>`: ""}
        `)}
        ${field("Tamaño de bastidor", `<select class="input-base sans" onchange="pf_hoop(this.value)">${HOOP_SIZES.map(h => `<option${h.label === p.hoop ? " selected" : ""}>${esc(h.label)}</option>`).join("")}</select>`)}
        ${field("Estado", `<select class="input-base sans" onchange="pf_set('estado',this.value)">${ESTADOS.map(e => `<option style="color:${ESTADO_COLOR[e]}"${e === p.estado ? " selected" : ""}>${esc(e)}</option>`).join("")}</select>`)}
        ${field("Cantidad a vender", `<input class="input-base" type="number" min="1" value="${p.quantity}" oninput="pf_set('quantity',this.value)" />`)}
        ${field("Cliente (opcional)", `<select class="input-base sans" onchange="pf_set('clientId',this.value)">
          <option value="">— sin cliente —</option>
          ${clients.map(c => `<option value="${c.id}"${c.id === p.clientId ? " selected" : ""}>${esc(c.name)}</option>`).join("")}
        </select>`)}
        ${field("Fecha de entrega", `<input class="input-base" type="date" value="${p.deliveryDate || ""}" oninput="pf_set('deliveryDate',this.value)" />`)}
      </div>

      ${field("Foto", `<div class="flex items-center gap-3">
        ${p.image ? `<img src="${p.image}" class="w-16 h-16 rounded-lg object-cover" style="border:1px solid var(--border)" />` : ""}
        <button onclick="document.getElementById('pf-img-inp').click()" class="btn-ghost" style="font-size:.75rem"><i data-lucide="upload" style="width:13px;height:13px"></i> ${p.image ? "Cambiar imagen" : "Subir imagen"}</button>
        <input type="file" id="pf-img-inp" accept="image/*" class="hidden" onchange="pf_image(this)" />
      </div>`)}

      <!-- CALCULADORA AUTOMÁTICA -->
      <div class="rounded-xl p-3 mb-4" style="background:var(--panel2);border:1px solid var(--border)">
        <div class="flex items-center gap-1.5 text-xs font-semibold uppercase tracking-widest mb-2 sans" style="color:var(--gold-light)">
          <i data-lucide="calculator" style="width:13px;height:13px"></i> Calculadora automática
        </div>
        <div class="grid sm:grid-cols-2 gap-x-3">
          ${field("Tela / Gabardina", `<select class="input-base sans" onchange="pf_calc('telaId',this.value)">
            <option value="">— sin tela —</option>
            ${telas.map(m => `<option value="${m.id}"${m.id === p.calc?.telaId ? " selected" : ""}>${esc(m.name)} (${money(m.pricePerM2)}/m²)</option>`).join("")}
          </select>`)}
          ${field("Entretela", `<select class="input-base sans" onchange="pf_calc('entretelaId',this.value)">
            <option value="">— sin entretela —</option>
            ${entretelas.map(m => `<option value="${m.id}"${m.id === p.calc?.entretelaId ? " selected" : ""}>${esc(m.name)} (${money(m.pricePerM2)}/m²)</option>`).join("")}
          </select>`)}
        </div>
        ${calc.areaM2 > 0 ? `<p class="text-[11px] mb-2 sans" style="color:var(--muted)">Área a cortar con margen: ${(calc.areaM2 * 10000).toFixed(0)} cm² (${calc.sideCm}x${calc.sideCm} cm)</p>` : ""}
        <div class="grid sm:grid-cols-3 gap-x-3">
          ${field("Puntadas", `<input class="input-base" type="number" value="${p.calc?.stitches || ""}" placeholder="Ej: 5000" oninput="pf_calc('stitches',this.value)" />`)}
          ${field("Colores", `<input class="input-base" type="number" value="${p.calc?.colors || ""}" placeholder="Ej: 4" oninput="pf_calc('colors',this.value)" />`)}
          ${field("Hilo", `<select class="input-base sans" onchange="pf_calc('hiloId',this.value)">
            <option value="">— sin hilo —</option>
            ${hilos.map(m => `<option value="${m.id}"${m.id === p.calc?.hiloId ? " selected" : ""}>${esc(m.name)} (${money(m.pricePerMeter)}/m)</option>`).join("")}
          </select>`)}
        </div>
        ${calc.threadMeters > 0 ? `<p class="text-[11px] sans" style="color:var(--muted)">Hilo estimado: ${calc.threadMeters.toFixed(1)} metros</p>` : ""}
      </div>

      <!-- INSUMOS MANUALES -->
      <div class="mt-2 mb-1 flex items-center justify-between">
        <span class="field-label">Insumos del diseño</span>
        <button onclick="pf_addItem()" class="btn-link"><i data-lucide="plus" style="width:12px;height:12px"></i> Insumo manual</button>
      </div>
      <div id="pf-items" class="space-y-2 mb-3">
        ${(p.items || []).map(it => it.auto ?
          `<div class="flex gap-2 items-center">
            <div class="input-base flex-1 sans" style="background:var(--panel2);color:var(--gold-light)">${esc(it.name)}</div>
            <input type="number" class="input-base w-24" value="${it.cost}" disabled />
          </div>`:
          `<div class="flex gap-2 items-center">
            <input class="input-base flex-1" placeholder="Nombre" value="${esc(it.name)}" oninput="pf_updateItem('${it.id}','name',this.value)" />
            <input type="number" class="input-base w-24" placeholder="Costo" value="${it.cost}" oninput="pf_updateItem('${it.id}','cost',this.value)" />
            <button onclick="pf_removeItem('${it.id}')" class="btn-icon btn-icon-danger"><i data-lucide="trash-2" style="width:14px;height:14px"></i></button>
          </div>`
        ).join("")}
        ${(!p.items || p.items.length === 0) ? `<p class="text-xs sans" style="color:var(--muted)">Sin insumos cargados todavía.</p>` : ""}
      </div>

      <div class="grid sm:grid-cols-2 gap-x-4">
        ${field("Horas de trabajo", `<input class="input-base" type="number" value="${p.laborHours || ""}" placeholder="0" oninput="pf_set('laborHours',this.value)" />`)}
        ${field("Valor de tu hora", `<input class="input-base" type="number" value="${p.laborRate || ""}" placeholder="0" oninput="pf_set('laborRate',this.value)" />`)}
      </div>

      <div class="rounded-lg p-3 my-3 text-sm sans" style="background:var(--panel2)">
        <div class="flex justify-between"><span style="color:var(--muted)">Costo unitario</span><span class="font-semibold">${money(cost)}</span></div>
      </div>

      ${field("Precio de venta (unitario)", `<input class="input-base" type="number" value="${p.salePrice || ""}" placeholder="0" oninput="pf_set('salePrice',this.value)" />`)}
      ${field("Seña / monto ya cobrado", `<input class="input-base" type="number" value="${p.amountPaid || ""}" placeholder="0" oninput="pf_set('amountPaid',this.value)" />`)}

      <div class="rounded-lg p-3 mb-4 text-sm space-y-1 sans" style="background:var(--panel2)">
        <div class="flex justify-between font-semibold" style="color:${profitUnit >= 0 ? "var(--green)" : "var(--red)"}">
          <span>Ganancia unitaria</span><span>${money(profitUnit)}${marginPct !== null ? ` (${marginPct}%)` : ""}
        </span></div>
        <div class="flex justify-between font-semibold" style="color:var(--gold-light)"><span>Total venta (x${qty})</span><span>${money((Number(p.salePrice) || 0) * qty)}</span></div>
        ${pending > 0 ? `<div class="flex justify-between font-semibold" style="color:var(--red)"><span>Saldo pendiente</span><span>${money(pending)}</span></div>` : ""}
      </div>

      <p class="field-label mb-1">Si ya lo vendiste: distribuí el dinero (opcional)</p>
      <div class="grid grid-cols-3 gap-2 mb-2">
        ${FIN_CATS.map(({ key, label }) => `${field(label, `<input class="input-base" type="number" value="${p.alloc?.[key] || ""}" placeholder="0" oninput="pf_alloc('${key}',this.value)" />`)}`).join("")}
      </div>
      ${allocTotal > 0 ? `<p class="text-xs mb-3 sans" style="color:var(--muted)">Total distribuido: ${money(allocTotal)}. Se guarda como movimientos en Resumen al guardar.</p>` : ""}

      ${field("Notas", `<textarea class="input-base" rows="2" oninput="pf_set('notes',this.value)">${esc(p.notes || "")}</textarea>`)}

      <div class="flex gap-2 mt-4 flex-wrap">
        <button onclick="pf_save()" class="btn-gold flex-1">Guardar diseño</button>
        <button onclick="saveAsTemplateFromForm()" class="btn-ghost"><i data-lucide="layers" style="width:14px;height:14px"></i> Plantilla</button>
        <button onclick="cancelEditProduct()" class="btn-ghost">Cancelar</button>
      </div>
    </div>
  </div>`;
      }

      function cancelEditProduct() { _calcState.editing = null; renderApp(); }
      function toggleNewType() { _calcState.showNewType = !_calcState.showNewType; renderApp(); }
      function addNewType() {
        const t = _calcState.newType.trim();
        if (t && !STATE.types.includes(t)) { STATE.types = [...STATE.types, t]; save("types"); }
        _calcState.newType = ""; _calcState.showNewType = false; renderApp();
      }

      // Product form setters — work directly on _calcState.editing and re-render
      function pf_set(key, val) {
        if (!_calcState.editing) return;
        _calcState.editing[key] = val;
        // Re-render only specific elements without full page reload to keep focus
        _pfUpdateSummary();
      }
      function pf_hoop(label) {
        if (!_calcState.editing) return;
        const h = HOOP_SIZES.find(x => x.label === label) || { label, cm: 0 };
        _calcState.editing.hoop = label; _calcState.editing.hoopCm = h.cm;
        applyAutoItems(_calcState.editing);
        renderApp();
      }
      function pf_calc(key, val) {
        if (!_calcState.editing) return;
        _calcState.editing.calc = { ..._calcState.editing.calc, [key]: val };
        applyAutoItems(_calcState.editing);
        renderApp();
      }
      function pf_alloc(key, val) {
        if (!_calcState.editing) return;
        _calcState.editing.alloc = { ..._calcState.editing.alloc, [key]: val };
      }
      function pf_addItem() {
        if (!_calcState.editing) return;
        _calcState.editing.items = [..._calcState.editing.items, { id: uid(), name: "", cost: "" }];
        renderApp();
      }
      function pf_updateItem(id, key, val) {
        if (!_calcState.editing) return;
        _calcState.editing.items = _calcState.editing.items.map(it => it.id === id ? { ...it, [key]: val } : it);
      }
      function pf_removeItem(id) {
        if (!_calcState.editing) return;
        _calcState.editing.items = _calcState.editing.items.filter(it => it.id !== id);
        renderApp();
      }
      async function pf_image(inp) {
        if (!inp.files[0] || !_calcState.editing) return;
        _calcState.editing.image = await compressImage(inp.files[0]);
        renderApp();
      }
      function _pfUpdateSummary() { }

      function pf_save() {
        const p = _calcState.editing; if (!p) return;
        if (!p.name.trim()) { alert("Poné un nombre para el diseño."); return; }
        const exists = STATE.products.some(x => x.id === p.id);
        STATE.products = exists ? STATE.products.map(x => x.id === p.id ? p : x) : [p, ...STATE.products];
        // Finance injection
        FIN_CATS.forEach(({ key }) => {
          const amt = Number(p.alloc?.[key]);
          if (amt) STATE.finance = [{ id: uid(), type: key, amount: amt, date: p.date, place: "", category: "Venta de producto", projectId: p.id, projectName: p.name }, ...STATE.finance];
        });
        save("products"); save("finance");
        _calcState.editing = null; renderApp();
      }
      function saveAsTemplateFromForm() {
        const p = _calcState.editing; if (!p) return;
        const name = prompt("Nombre para esta plantilla:", `${p.type} ${p.hoop}`); if (!name) return;
        STATE.templates = [{ id: uid(), name, type: p.type, hoop: p.hoop, hoopCm: p.hoopCm, calc: p.calc, items: (p.items || []).filter(i => i.auto), laborHours: p.laborHours, laborRate: p.laborRate }, ...STATE.templates];
        save("templates"); alert("Plantilla guardada.");
      }

      // =====================================================================
      // HISTORIAL
      // =====================================================================
      let _histState = { filterType: "", filterEstado: "" };
      function renderHistorial() {
        const { products, types, clients } = STATE;
        const { filterType, filterEstado } = _histState;
        const search = (STATE.search || "").trim().toLowerCase();
        const filtered = products.filter(p =>
          (!filterType || p.type === filterType) &&
          (!filterEstado || p.estado === filterEstado) &&
          (!search || p.name.toLowerCase().includes(search) || p.type.toLowerCase().includes(search) || (clients.find(c => c.id === p.clientId)?.name || "").toLowerCase().includes(search))
        ).slice().sort((a, b) => a.date < b.date ? 1 : -1);
        return `<div>
    <div class="flex items-center justify-between mb-4"><h2 class="text-base font-semibold" style="color:var(--gold-light)">Historial de diseños</h2></div>
    <div class="flex flex-wrap gap-2 mb-4 sans">
      <div class="flex items-center gap-1.5 rounded-lg px-2.5" style="background:var(--panel2);border:1px solid var(--border)">
        <i data-lucide="search" style="width:13px;height:13px;color:var(--muted)"></i>
        <input value="${esc(STATE.search || "")}" oninput="STATE.search=this.value;renderApp()" placeholder="Buscar…" class="bg-transparent text-sm py-2 focus:outline-none w-32 sans" style="color:var(--cream)" />
      </div>
      <select class="input-base sans" style="width:auto" onchange="_histState.filterType=this.value;renderApp()">
        <option value="">Todas las categorías</option>${types.map(t => `<option${t === filterType ? " selected" : ""}>${esc(t)}</option>`).join("")}
      </select>
      <select class="input-base sans" style="width:auto" onchange="_histState.filterEstado=this.value;renderApp()">
        <option value="">Todos los estados</option>${ESTADOS.map(e => `<option${e === filterEstado ? " selected" : ""}>${esc(e)}</option>`).join("")}
      </select>
      ${filterType || filterEstado || search ? `<button onclick="_histState.filterType='';_histState.filterEstado='';STATE.search='';renderApp()" class="btn-link">Limpiar filtros</button>` : ""}
    </div>
    ${filtered.length === 0 ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">No hay diseños con esos filtros.</div>` :
            `<div class="space-y-2 sans">${filtered.map(p => {
              const cost = calcCost(p);
              const qty = Number(p.quantity) || 1;
              const total = (Number(p.salePrice) || 0) * qty;
              const pending = pendingAmount(p);
              const cname = clients.find(c => c.id === p.clientId)?.name || "";
              return `<div class="card card-interactive p-3 flex items-center gap-3 flex-wrap stagger-item">
          <div class="w-10 h-10 rounded-lg overflow-hidden flex items-center justify-center shrink-0" style="background:var(--panel2)">
            ${p.image ? `<img src="${p.image}" class="w-full h-full object-cover" />` : `<i data-lucide="image" style="width:16px;height:16px;color:var(--border)"></i>`}
          </div>
          <div class="flex-1 min-w-0">
            <p class="text-sm font-medium truncate">${esc(p.name)}${cname ? ` · ${esc(cname)}` : ""}</p>
            <p class="text-xs truncate" style="color:var(--muted)">${p.date} · ${esc(p.type)} · ${esc(p.hoop)} · costo ${money(cost)}${pending > 0 ? ` · debe ${money(pending)}` : ""}</p>
          </div>
          <div class="text-right">
            <p class="text-sm font-semibold" style="color:var(--gold-light)">${money(total)}</p>
            <p class="text-[11px]" style="color:var(--muted)">x${qty}</p>
          </div>
          <select class="input-base sans" style="width:auto;padding:.25rem .5rem;font-size:.75rem;color:${ESTADO_COLOR[p.estado]}" onchange="histSetEstado('${p.id}',this.value)">
            ${ESTADOS.map(e => `<option style="color:${ESTADO_COLOR[e]}"${e === p.estado ? " selected" : ""}>${esc(e)}</option>`).join("")}
          </select>
          <button onclick="editProduct('${p.id}');STATE.tab='calculadora';renderApp()" class="btn-icon btn-sm"><i data-lucide="pencil" style="width:12px;height:12px"></i></button>
        </div>`;
            }).join("")}</div>`}
  </div>`;
      }
      function histSetEstado(id, estado) {
        STATE.products = STATE.products.map(p => p.id === id ? { ...p, estado } : p);
        save("products"); renderApp();
      }

      // =====================================================================
      // CALENDARIO
      // =====================================================================
      let _calState = { selected: dateStr(new Date()), cursor: new Date(), form: null };
      function renderCalendario() {
        const { posts } = STATE;
        const { selected, cursor, form } = _calState;
        const year = cursor.getFullYear(), month = cursor.getMonth();
        const firstDay = new Date(year, month, 1);
        const lastDay = new Date(year, month + 1, 0);
        let startDow = (firstDay.getDay() + 6) % 7; // Mon=0
        const days = [];
        for (let i = 0; i < startDow; i++) days.push(null);
        for (let d = 1; d <= lastDay.getDate(); d++) days.push(new Date(year, month, d));
        const selectedPosts = posts.filter(p => p.date === selected);
        return `<div>
    <div class="grid md:grid-cols-2 gap-4">
      <!-- CALENDAR -->
      <div class="card p-4">
        <div class="flex items-center justify-between mb-3 sans">
          <button onclick="calPrev()" class="btn-icon"><i data-lucide="chevron-left" style="width:16px;height:16px"></i></button>
          <p class="font-semibold text-sm" style="color:var(--gold-light)">${MONTHS[month]} ${year}</p>
          <button onclick="calNext()" class="btn-icon"><i data-lucide="chevron-right" style="width:16px;height:16px"></i></button>
        </div>
        <div class="grid grid-cols-7 gap-0.5 mb-1">
          ${WEEKDAYS.map(w => `<div class="text-center text-[10px] font-semibold sans" style="color:var(--muted)">${w}</div>`).join("")}
        </div>
        <div class="grid grid-cols-7 gap-0.5">
          ${days.map(d => {
          if (!d) return `<div></div>`;
          const ds = dateStr(d);
          const hasPosts = posts.some(p => p.date === ds);
          const isToday = ds === dateStr(new Date());
          const isSel = ds === selected;
          return `<button onclick="calSelect('${ds}')" class="cal-day aspect-square flex flex-col items-center justify-center rounded-lg text-xs sans relative" style="background:${isSel ? "var(--gold)" : isToday ? "var(--panel2)" : "transparent"};color:${isSel ? "#1B1208" : isToday ? "var(--gold-light)" : "var(--cream)"};cursor:pointer;border:none${isToday && !isSel ? ";box-shadow:inset 0 0 0 1px var(--border)" : ""}">
              ${d.getDate()}
              ${hasPosts ? `<div class="w-1.5 h-1.5 rounded-full absolute bottom-1" style="background:${isSel ? "#1B1208" : "var(--gold)"}"></div>` : ""}
            </button>`;
        }).join("")}
        </div>
      </div>
      <!-- DAY DETAIL -->
      <div class="card p-4">
        <div class="flex items-center justify-between mb-3">
          <p class="text-sm font-semibold sans" style="color:var(--gold-light)">${formatDate(selected)}</p>
          <button onclick="calStartNew()" class="btn-link"><i data-lucide="plus" style="width:13px;height:13px"></i> Agregar</button>
        </div>
        ${form ? `<div class="rounded-lg p-3 mb-3" style="background:var(--panel2)">
          ${field("Título", `<input class="input-base" value="${esc(form.title)}" placeholder="Ej: Pañuelo nuevo en stock" oninput="calFormSet('title',this.value)" />`)}
          ${field("Tipo", `<div class="flex gap-2">${POST_TAGS.map(t => `<button onclick="calFormSet('tag','${t.key}')" class="tag-pill flex-1 text-xs py-1.5 rounded-lg flex items-center justify-center gap-1 sans" style="background:${form.tag === t.key ? t.color : "transparent"};color:${form.tag === t.key ? "#171109" : "var(--muted)"};border:1px solid ${form.tag === t.key ? t.color : "var(--border)"};cursor:pointer">${esc(t.label)}</button>`).join("")}</div>`)}
          ${field("Descripción", `<textarea class="input-base" rows="3" placeholder="Detalle, guion, hashtags…" oninput="calFormSet('description',this.value)">${esc(form.description || "")}</textarea>`)}
          <div class="flex gap-2"><button onclick="calSave()" class="btn-gold flex-1">Guardar</button><button onclick="_calState.form=null;renderApp()" class="btn-ghost">Cancelar</button></div>
        </div>`: ""}
        ${selectedPosts.length === 0 && !form ?
            `<p class="text-sm sans" style="color:var(--muted)">Sin publicaciones este día.</p>` :
            `<div class="space-y-2">${selectedPosts.map(p => {
              const tag = POST_TAGS.find(t => t.key === p.tag);
              return `<div class="rounded-lg p-3" style="background:var(--panel2)">
              <div class="flex items-start justify-between gap-2 mb-1">
                <p class="text-sm font-medium sans">${esc(p.title)}</p>
                ${badge(tag?.label || p.tag, tag?.color || "var(--muted)")}
              </div>
              ${p.description ? `<p class="text-xs mb-2 sans" style="color:var(--muted)">${esc(p.description)}</p>` : ""}
              <div class="flex gap-2">
                <button onclick="calEditPost('${p.id}')" class="btn-link">Editar</button>
                <button onclick="calDeletePost('${p.id}')" class="btn-link" style="color:var(--red)!important">Eliminar</button>
              </div>
            </div>`;
            }).join("")}</div>`}
      </div>
    </div>
  </div>`;
      }
      function calPrev() { _calState.cursor = new Date(_calState.cursor.getFullYear(), _calState.cursor.getMonth() - 1, 1); renderApp(); }
      function calNext() { _calState.cursor = new Date(_calState.cursor.getFullYear(), _calState.cursor.getMonth() + 1, 1); renderApp(); }
      function calSelect(ds) { _calState.selected = ds; _calState.form = null; renderApp(); }
      function calStartNew() { _calState.form = { id: uid(), date: _calState.selected, title: "", tag: "publicacion", description: "" }; renderApp(); }
      function calFormSet(k, v) { if (_calState.form) { _calState.form[k] = v; if (k === "tag") renderApp(); } }
      function calSave() {
        const f = _calState.form; if (!f || !f.title.trim()) { alert("Poné un título."); return; }
        const exists = STATE.posts.some(p => p.id === f.id);
        STATE.posts = exists ? STATE.posts.map(p => p.id === f.id ? f : p) : [f, ...STATE.posts];
        save("posts"); _calState.form = null; renderApp();
      }
      function calEditPost(id) { _calState.form = { ...STATE.posts.find(p => p.id === id) }; renderApp(); }
      function calDeletePost(id) { STATE.posts = STATE.posts.filter(p => p.id !== id); save("posts"); renderApp(); }

      // =====================================================================
      // CLIENTES
      // =====================================================================
      let _clientState = { form: null, expanded: null };
      function renderClientes() {
        const { clients, products } = STATE;
        const { form, expanded } = _clientState;
        return `<div>
    <div class="flex items-center justify-between mb-4">
      <div><h2 class="text-base font-semibold" style="color:var(--gold-light)">Clientes</h2><p class="text-xs sans" style="color:var(--muted)">${clients.length} clientes</p></div>
      <button onclick="clientStartNew()" class="btn-gold"><i data-lucide="plus" style="width:15px;height:15px"></i> Nuevo cliente</button>
    </div>
    ${form ? `<div class="card p-4 mb-4">
      <div class="grid sm:grid-cols-2 gap-x-4">
        ${field("Nombre", `<input class="input-base" value="${esc(form.name)}" oninput="_clientState.form.name=this.value" />`)}
        ${field("Teléfono / contacto", `<input class="input-base" value="${esc(form.phone || "")}" oninput="_clientState.form.phone=this.value" />`)}
      </div>
      ${field("Notas", `<textarea class="input-base" rows="2" placeholder="Preferencias, talles, colores favoritos…" oninput="_clientState.form.notes=this.value">${esc(form.notes || "")}</textarea>`)}
      <div class="flex gap-2"><button onclick="clientSave()" class="btn-gold flex-1">Guardar</button><button onclick="_clientState.form=null;renderApp()" class="btn-ghost">Cancelar</button></div>
    </div>`: ""}
    ${clients.length === 0 && !form ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Todavía no cargaste clientes.</div>` :
            `<div class="space-y-2 sans">${clients.map(c => {
              const orders = products.filter(p => p.clientId === c.id);
              const totalSpent = orders.reduce((s, p) => s + (Number(p.salePrice) || 0) * (Number(p.quantity) || 1), 0);
              const isOpen = expanded === c.id;
              return `<div class="card p-3">
          <div class="flex items-center gap-3">
            <div class="flex-1 min-w-0 cursor-pointer" onclick="clientToggle('${c.id}')">
              <p class="text-sm font-medium">${esc(c.name)}</p>
              <p class="text-xs" style="color:var(--muted)">${esc(c.phone || "—")} · ${orders.length} pedido(s) · ${money(totalSpent)} gastado</p>
            </div>
            <button onclick="clientEdit('${c.id}')" class="btn-icon"><i data-lucide="pencil" style="width:14px;height:14px"></i></button>
            <button onclick="clientDelete('${c.id}')" class="btn-icon btn-icon-danger"><i data-lucide="trash-2" style="width:14px;height:14px"></i></button>
          </div>
          ${isOpen ? `<div class="mt-3 pt-3 space-y-1.5" style="border-top:1px solid var(--border)">
            ${c.notes ? `<p class="text-xs mb-2" style="color:var(--muted)">${esc(c.notes)}</p>` : ""}
            ${orders.length === 0 ? `<p class="text-xs" style="color:var(--muted)">Sin pedidos todavía.</p>` :
                    orders.map(o => `<div class="flex justify-between text-xs"><span>${esc(o.name)} (${o.date})</span><span style="color:var(--gold-light)">${money((Number(o.salePrice) || 0) * (Number(o.quantity) || 1))}</span></div>`).join("")}
          </div>`: ""}
        </div>`;
            }).join("")}</div>`}
  </div>`;
      }
      function clientStartNew() { _clientState.form = { id: uid(), name: "", phone: "", notes: "" }; renderApp(); }
      function clientEdit(id) { _clientState.form = { ...STATE.clients.find(c => c.id === id) }; renderApp(); }
      function clientToggle(id) { _clientState.expanded = _clientState.expanded === id ? null : id; renderApp(); }
      function clientSave() {
        const f = _clientState.form; if (!f.name.trim()) { alert("Poné un nombre."); return; }
        const exists = STATE.clients.some(c => c.id === f.id);
        STATE.clients = exists ? STATE.clients.map(c => c.id === f.id ? f : c) : [f, ...STATE.clients];
        save("clients"); _clientState.form = null; renderApp();
      }
      function clientDelete(id) { if (!confirm("¿Eliminar este cliente?")) return; STATE.clients = STATE.clients.filter(c => c.id !== id); save("clients"); renderApp(); }

      // =====================================================================
      // GALERÍA
      // =====================================================================
      function renderGaleria() {
        const withImage = STATE.products.filter(p => p.image).slice().sort((a, b) => a.date < b.date ? 1 : -1);
        return `<div>
    <h2 class="text-base font-semibold mb-1" style="color:var(--gold-light)">Galería</h2>
    <p class="text-xs mb-4 sans" style="color:var(--muted)">${withImage.length} fotos de tus diseños.</p>
    ${withImage.length === 0 ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Todavía no subiste fotos. Agregalas desde la Calculadora al crear un diseño.</div>` :
            `<div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-3">
        ${withImage.map(p => `<div class="card card-interactive overflow-hidden stagger-item">
          <div class="aspect-square overflow-hidden" style="background:var(--panel2)"><img src="${p.image}" class="w-full h-full object-cover transition-transform duration-500 hover:scale-105" /></div>
          <div class="p-2 sans"><p class="text-xs font-medium truncate">${esc(p.name)}</p><p class="text-[11px]" style="color:var(--muted)">${esc(p.type)} · ${p.date}</p></div>
        </div>`).join("")}
      </div>`}
  </div>`;
      }

      // =====================================================================
      // PROVEEDORES
      // =====================================================================
      let _supplierState = { form: null };
      function renderProveedores() {
        const { suppliers, materials } = STATE;
        const { form } = _supplierState;
        return `<div>
    <div class="flex items-center justify-between mb-4">
      <div><h2 class="text-base font-semibold" style="color:var(--gold-light)">Proveedores</h2><p class="text-xs sans" style="color:var(--muted)">${suppliers.length} lugares de compra</p></div>
      <button onclick="suppStartNew()" class="btn-gold"><i data-lucide="plus" style="width:15px;height:15px"></i> Nuevo proveedor</button>
    </div>
    ${form ? `<div class="card p-4 mb-4">
      <div class="grid sm:grid-cols-2 gap-x-4">
        ${field("Nombre", `<input class="input-base" value="${esc(form.name)}" placeholder="Ej: Mercería Don José" oninput="_supplierState.form.name=this.value" />`)}
        ${field("Teléfono / contacto", `<input class="input-base" value="${esc(form.phone || "")}" oninput="_supplierState.form.phone=this.value" />`)}
      </div>
      ${field("Dirección", `<input class="input-base" value="${esc(form.address || "")}" oninput="_supplierState.form.address=this.value" />`)}
      ${field("Qué le compro", `<input class="input-base" value="${esc(form.items || "")}" placeholder="Ej: hilos, entretela" oninput="_supplierState.form.items=this.value" />`)}
      ${field("Notas", `<textarea class="input-base" rows="2" oninput="_supplierState.form.notes=this.value">${esc(form.notes || "")}</textarea>`)}
      <div class="flex gap-2"><button onclick="suppSave()" class="btn-gold flex-1">Guardar</button><button onclick="_supplierState.form=null;renderApp()" class="btn-ghost">Cancelar</button></div>
    </div>`: ""}
    ${suppliers.length === 0 && !form ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Todavía no cargaste proveedores.</div>` :
            `<div class="space-y-2 sans">${suppliers.map(s => {
              const mats = materials.filter(m => m.supplierId === s.id);
              return `<div class="card p-3">
          <div class="flex items-center gap-3">
            <div class="flex-1 min-w-0">
              <p class="text-sm font-medium">${esc(s.name)}</p>
              <p class="text-xs" style="color:var(--muted)">${esc(s.phone || "—")} · ${esc(s.items || "sin detallar")} · ${mats.length} insumo(s)</p>
              ${s.address ? `<p class="text-xs" style="color:var(--muted)">${esc(s.address)}</p>` : ""}
            </div>
            <button onclick="suppEdit('${s.id}')" class="btn-icon"><i data-lucide="pencil" style="width:14px;height:14px"></i></button>
            <button onclick="suppDelete('${s.id}')" class="btn-icon btn-icon-danger"><i data-lucide="trash-2" style="width:14px;height:14px"></i></button>
          </div>
          ${mats.length > 0 ? `<div class="mt-2 pt-2 text-xs space-y-1 sans" style="border-top:1px solid var(--border)">
            <p class="font-semibold" style="color:var(--gold-light)">Insumos asociados</p>
            ${mats.map(m => `<div class="flex justify-between"><span>${esc(m.name)}</span><span style="color:var(--gold-light)">${m.kind === "hilo" ? money(m.pricePerMeter) + "/m" : (m.kind === "tela" || m.kind === "entretela") ? money(m.pricePerM2) + "/m²" : money(m.unitCost)}</span></div>
            ${(m.priceHistory && m.priceHistory.length > 0) ? `<div class="ml-2 text-[10px]" style="color:var(--muted)">Historial: ${m.priceHistory.slice(-3).map(h => `${h.date}: ${money(h.price)}`).join(" → ")}</div>` : ""}`).join("")}
          </div>`: ""}
        </div>`;
            }).join("")}</div>`}
  </div>`;
      }
      function suppStartNew() { _supplierState.form = { id: uid(), name: "", phone: "", address: "", items: "", notes: "" }; renderApp(); }
      function suppEdit(id) { _supplierState.form = { ...STATE.suppliers.find(s => s.id === id) }; renderApp(); }
      function suppSave() {
        const f = _supplierState.form; if (!f.name.trim()) { alert("Poné un nombre."); return; }
        const exists = STATE.suppliers.some(s => s.id === f.id);
        STATE.suppliers = exists ? STATE.suppliers.map(s => s.id === f.id ? f : s) : [f, ...STATE.suppliers];
        save("suppliers"); _supplierState.form = null; renderApp();
      }
      function suppDelete(id) { if (!confirm("¿Eliminar este proveedor?")) return; STATE.suppliers = STATE.suppliers.filter(s => s.id !== id); save("suppliers"); renderApp(); }

      // =====================================================================
      // INVENTARIO
      // =====================================================================
      let _inventoryState = { form: null, historyOpen: null };
      function renderInventario() {
        const { materials, suppliers } = STATE;
        const { form, historyOpen } = _inventoryState;
        return `<div>
    <div class="flex items-center justify-between mb-4">
      <div><h2 class="text-base font-semibold" style="color:var(--gold-light)">Inventario de insumos</h2><p class="text-xs sans" style="color:var(--muted)">${materials.length} insumos cargados</p></div>
      <button onclick="invStartNew()" class="btn-gold"><i data-lucide="plus" style="width:15px;height:15px"></i> Nuevo insumo</button>
    </div>
    ${form ? `<div class="card p-5 mb-4">${renderInvForm(form, suppliers)}</div>` : ""}
    ${materials.length === 0 && !form ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Todavía no cargaste insumos.</div>` :
            `<div class="space-y-2 sans">${materials.map(m => {
              const low = m.minStock && Number(m.stockQty) <= Number(m.minStock);
              const isOpen = historyOpen === m.id;
              const kindLabel = MATERIAL_KINDS.find(k => k.key === m.kind)?.label || m.kind;
              return `<div class="card p-3" style="${low ? "border-color:var(--red)" : ""}">
          <div class="flex items-center gap-3">
            <div class="flex-1 min-w-0 cursor-pointer" onclick="invToggleHistory('${m.id}')">
              <p class="text-sm font-medium truncate">${esc(m.name)} <span style="color:var(--muted)">· ${esc(kindLabel)}</span> ${low ? `<i data-lucide="alert-triangle" style="width:12px;height:12px;display:inline;color:var(--red)"></i>` : ""}</p>
              <p class="text-xs" style="color:var(--muted)">${esc(m.place || "—")} · ${m.date || ""}${m.stockQty !== undefined && m.stockQty !== "" ? ` · stock: ${m.stockQty}${m.minStock ? ` (mín: ${m.minStock})` : ""}` : ""}</p>
            </div>
            <span class="text-sm font-semibold whitespace-nowrap sans" style="color:var(--gold-light)">
              ${m.kind === "hilo" ? `${money(m.pricePerMeter)}/m` : m.kind === "tela" || m.kind === "entretela" ? `${money(m.pricePerM2)}/m²` : money(m.unitCost || 0)}
            </span>
            <div class="flex gap-1">
              <button onclick="invEdit('${m.id}')" class="btn-icon"><i data-lucide="pencil" style="width:14px;height:14px"></i></button>
              <button onclick="invDelete('${m.id}')" class="btn-icon btn-icon-danger"><i data-lucide="trash-2" style="width:14px;height:14px"></i></button>
            </div>
          </div>
          ${isOpen && m.priceHistory && m.priceHistory.length > 0 ? `<div class="mt-2 pt-2 text-xs space-y-1" style="border-top:1px solid var(--border);color:var(--muted)">
            <p class="font-semibold" style="color:var(--gold-light)">Historial de precios</p>
            ${m.priceHistory.slice().reverse().map(h => `<div class="flex justify-between"><span>${h.date}</span><span>${money(h.price)}</span></div>`).join("")}
          </div>`: ""}
        </div>`;
            }).join("")}</div>`}
  </div>`;
      }
      function renderInvForm(form, suppliers) {
        const isTelaEnt = form.kind === "tela" || form.kind === "entretela";
        const pp = isTelaEnt && form.purchasePrice && form.lengthM && form.widthM ? round2(Number(form.purchasePrice) / (Number(form.lengthM) * Number(form.widthM))) : 0;
        const pm = form.kind === "hilo" && form.purchasePrice && form.spoolMeters ? round2(Number(form.purchasePrice) / Number(form.spoolMeters)) : 0;
        if (isTelaEnt && pp) form.pricePerM2 = pp;
        if (form.kind === "hilo" && pm) form.pricePerMeter = pm;
        return `
    <div class="grid sm:grid-cols-2 gap-x-4">
      ${field("Tipo", `<select class="input-base sans" onchange="invSetKind(this.value)">${MATERIAL_KINDS.map(k => `<option value="${k.key}"${k.key === form.kind ? " selected" : ""}>${esc(k.label)}</option>`).join("")}</select>`)}
      ${field("Nombre", `<input class="input-base" value="${esc(form.name)}" placeholder="${form.kind === "hilo" ? "Ej: Mouliné azul DMC" : "Ej: Lino crudo"}" oninput="_inventoryState.form.name=this.value" />`)}
    </div>
    ${isTelaEnt ? `
      <div class="grid sm:grid-cols-3 gap-x-4">
        ${field("Precio pagado", `<input class="input-base" type="number" value="${form.purchasePrice || ""}" oninput="_inventoryState.form.purchasePrice=this.value;invRecalc()" />`)}
        ${field("Largo comprado (m)", `<input class="input-base" type="number" step="0.1" value="${form.lengthM || ""}" oninput="_inventoryState.form.lengthM=this.value;invRecalc()" />`)}
        ${field("Ancho del rollo (m)", `<input class="input-base" type="number" step="0.1" value="${form.widthM || ""}" oninput="_inventoryState.form.widthM=this.value;invRecalc()" />`)}
      </div>
      <p class="text-xs -mt-2 mb-3 sans" style="color:var(--muted)">Precio por m²: <strong style="color:var(--gold-light)">${money(form.pricePerM2)}</strong></p>` : ""}
    ${form.kind === "hilo" ? `
      <div class="grid sm:grid-cols-2 gap-x-4">
        ${field("Precio pagado", `<input class="input-base" type="number" value="${form.purchasePrice || ""}" oninput="_inventoryState.form.purchasePrice=this.value;invRecalc()" />`)}
        ${field("Metros de la madeja/cono", `<input class="input-base" type="number" value="${form.spoolMeters || ""}" oninput="_inventoryState.form.spoolMeters=this.value;invRecalc()" />`)}
      </div>
      <p class="text-xs -mt-2 mb-3 sans" style="color:var(--muted)">Precio por metro: <strong style="color:var(--gold-light)">${money(form.pricePerMeter)}</strong></p>` : ""}
    ${form.kind === "otro" ? field("Costo unitario", `<input class="input-base" type="number" value="${form.unitCost || ""}" oninput="_inventoryState.form.unitCost=this.value" />`) : ""}
    <div class="grid sm:grid-cols-2 gap-x-4">
      ${field("Cantidad en stock", `<input class="input-base" type="number" value="${form.stockQty || ""}" oninput="_inventoryState.form.stockQty=this.value" />`, "Para recibir alerta cuando se esté por terminar.")}
      ${field("Stock mínimo (alerta)", `<input class="input-base" type="number" value="${form.minStock || ""}" oninput="_inventoryState.form.minStock=this.value" />`)}
    </div>
    <div class="grid sm:grid-cols-2 gap-x-4">
      ${field("Proveedor", `<select class="input-base sans" onchange="_inventoryState.form.supplierId=this.value">
        <option value="">— sin proveedor —</option>
        ${suppliers.map(s => `<option value="${s.id}"${s.id === form.supplierId ? " selected" : ""}>${esc(s.name)}</option>`).join("")}
      </select>`)}
      ${field("Lugar de compra", `<input class="input-base" value="${esc(form.place || "")}" oninput="_inventoryState.form.place=this.value" />`)}
    </div>
    ${field("Fecha", `<input class="input-base" type="date" value="${form.date || today()}" oninput="_inventoryState.form.date=this.value" />`)}
    ${field("Notas", `<textarea class="input-base" rows="2" oninput="_inventoryState.form.notes=this.value">${esc(form.notes || "")}</textarea>`)}
    <div class="flex gap-2"><button onclick="invSave()" class="btn-gold flex-1">Guardar</button><button onclick="_inventoryState.form=null;renderApp()" class="btn-ghost">Cancelar</button></div>
  `;
      }
      function invBlank() { return { id: uid(), kind: "tela", name: "", purchasePrice: "", lengthM: "", widthM: "", pricePerM2: 0, spoolMeters: "", pricePerMeter: 0, unitCost: "", stockQty: "", minStock: "", supplierId: "", place: "", date: today(), notes: "", priceHistory: [] }; }
      function invStartNew() { _inventoryState.form = invBlank(); renderApp(); }
      function invEdit(id) { _inventoryState.form = { ...STATE.materials.find(m => m.id === id) }; renderApp(); }
      function invSetKind(kind) { if (_inventoryState.form) { _inventoryState.form.kind = kind; renderApp(); } }
      function invToggleHistory(id) { _inventoryState.historyOpen = _inventoryState.historyOpen === id ? null : id; renderApp(); }
      function invRecalc() {
        const f = _inventoryState.form; if (!f) return;
        if (f.kind === "tela" || f.kind === "entretela") {
          if (f.purchasePrice && f.lengthM && f.widthM) f.pricePerM2 = round2(Number(f.purchasePrice) / (Number(f.lengthM) * Number(f.widthM)));
        } else if (f.kind === "hilo") {
          if (f.purchasePrice && f.spoolMeters) f.pricePerMeter = round2(Number(f.purchasePrice) / Number(f.spoolMeters));
        }
      }
      function invSave() {
        const f = _inventoryState.form; if (!f.name.trim()) { alert("Poné un nombre."); return; }
        invRecalc();
        const existing = STATE.materials.find(m => m.id === f.id);
        // Track price history
        let history = (f.priceHistory || []);
        if (existing) {
          const oldPrice = existing.kind === "hilo" ? existing.pricePerMeter : existing.kind === "tela" || existing.kind === "entretela" ? existing.pricePerM2 : existing.unitCost;
          const newPrice = f.kind === "hilo" ? f.pricePerMeter : f.kind === "tela" || f.kind === "entretela" ? f.pricePerM2 : f.unitCost;
          if (oldPrice && newPrice && oldPrice !== newPrice) history = [...history, { date: today(), price: newPrice }];
        }
        f.priceHistory = history;
        const exists = STATE.materials.some(m => m.id === f.id);
        STATE.materials = exists ? STATE.materials.map(m => m.id === f.id ? f : m) : [f, ...STATE.materials];
        save("materials"); _inventoryState.form = null; renderApp();
      }
      function invDelete(id) { if (!confirm("¿Eliminar este insumo?")) return; STATE.materials = STATE.materials.filter(m => m.id !== id); save("materials"); renderApp(); }

      // =====================================================================
      // RESUMEN FINANCIERO
      // =====================================================================
      let _resumenState = { form: null };
      function renderResumen() {
        const { finance, products, types, salesGoal } = STATE;
        const { form } = _resumenState;
        const totals = { ingreso: 0, gasto: 0, reinversion: 0 };
        finance.forEach(f => { if (totals[f.type] !== undefined) totals[f.type] += (Number(f.amount) || 0) });
        const balance = totals.ingreso - totals.gasto - totals.reinversion;
        const vendidos = products.filter(p => p.estado === "Vendido" || p.estado === "Entregado");
        const ingresos = finance.filter(f => f.type === "ingreso");
        const ticketProm = ingresos.length ? Math.round(totals.ingreso / ingresos.length) : 0;
        const pendientesCobro = products.filter(p => (p.estado === "Vendido" || p.estado === "Entregado") && pendingAmount(p) > 0);
        // Monthly ingresos
        const monthMap = {};
        ingresos.forEach(f => { const d = new Date(f.date); if (isNaN(d)) return; const k = `${d.getFullYear()}-${String(d.getMonth()).padStart(2, "0")}`; monthMap[k] = (monthMap[k] || 0) + Number(f.amount); });
        const monthly = Object.entries(monthMap).sort((a, b) => a[0] > b[0] ? 1 : -1).slice(-8).map(([k, v]) => { const [y, m] = k.split("-").map(Number); return { name: `${MONTHS_SHORT[m]} '${String(y).slice(2)}`, total: v }; });
        const maxMonthly = Math.max(...monthly.map(m => m.total), 1);
        // Rentabilidad
        const rentabilidad = types.map(t => {
          const ps = vendidos.filter(p => p.type === t);
          const revenue = ps.reduce((s, p) => s + (Number(p.salePrice) || 0) * (Number(p.quantity) || 1), 0);
          const costs = ps.reduce((s, p) => s + calcCost(p) * (Number(p.quantity) || 1), 0);
          const ganancia = revenue - costs;
          const pct = revenue > 0 ? ((ganancia / revenue) * 100).toFixed(0) : 0;
          return { name: t, ganancia, revenue, pct, count: ps.length };
        }).filter(r => r.revenue > 0).sort((a, b) => b.ganancia - a.ganancia);
        const maxGanancia = Math.max(...rentabilidad.map(r => r.ganancia), 1);

        return `<div>
    <h2 class="text-base font-semibold mb-1" style="color:var(--gold-light)">Resumen financiero</h2>
    <!-- KPIs -->
    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 mb-5">
      ${kpiCard("Ingresos totales", money(totals.ingreso), "var(--green)")}
      ${kpiCard("Gastos totales", money(totals.gasto), "var(--red)")}
      ${kpiCard("Reinversión", money(totals.reinversion), "var(--gold-light)")}
      ${kpiCard("Balance neto", money(balance), balance >= 0 ? "var(--green)" : "var(--red)")}
    </div>
    <div class="grid sm:grid-cols-3 gap-3 mb-5">
      ${kpiCard("Ticket promedio", money(ticketProm), "var(--gold-light)")}
      ${kpiCard("Movimientos", finance.length, "var(--muted)")}
      ${kpiCard("Cobros pendientes", money(pendientesCobro.reduce((s, p) => s + pendingAmount(p), 0)), "var(--red)")}
    </div>

    <!-- META MENSUAL -->
    <div class="card p-4 mb-5">
      <div class="flex items-center justify-between mb-2">
        <p class="text-xs sans font-semibold uppercase tracking-widest" style="color:var(--gold-light)">Meta mensual de ventas</p>
        <button onclick="resSetGoal()" class="btn-link"><i data-lucide="pencil" style="width:12px;height:12px"></i> Editar</button>
      </div>
      ${salesGoal > 0 ? `
        <div class="flex justify-between text-xs sans mb-2" style="color:var(--muted)">
          <span>Meta: ${money(salesGoal)}</span>
          <span>${Math.min(100, ((totals.ingreso / salesGoal) * 100).toFixed(1))}%</span>
        </div>
        <div class="progress-bar"><div class="progress-fill" style="width:${Math.min(100, (totals.ingreso / salesGoal) * 100)}%"></div></div>`
            : `<p class="text-sm sans" style="color:var(--muted)">Sin meta definida. Hacé clic en "Editar" para configurarla.</p>`}
    </div>

    ${pawDivider()}

    <!-- GRÁFICO INGRESOS MENSUALES -->
    ${monthly.length > 0 ? `<div class="card p-4 mb-5">
      <p class="text-xs sans font-semibold uppercase tracking-widest mb-4" style="color:var(--gold-light)">Ingresos por mes</p>
      <div class="space-y-2 sans">
        ${monthly.map(m => `<div class="flex items-center gap-2 text-xs">
          <span style="color:var(--muted);width:52px;text-align:right">${m.name}</span>
          <div style="flex:1;background:var(--panel2);border-radius:4px;height:20px;overflow:hidden">
            <div class="bar-chart-bar" style="width:${(m.total / maxMonthly * 100).toFixed(1)}%;height:100%"></div>
          </div>
          <span style="color:var(--gold-light);width:72px">${money(m.total)}</span>
        </div>`).join("")}
      </div>
    </div>`: ""}

    <!-- RENTABILIDAD POR CATEGORÍA -->
    ${rentabilidad.length > 0 ? `<div class="card p-4 mb-5">
      <p class="text-xs sans font-semibold uppercase tracking-widest mb-4" style="color:var(--gold-light)">Rentabilidad por categoría</p>
      <div class="space-y-3 sans">
        ${rentabilidad.map(r => `<div>
          <div class="flex items-center justify-between text-xs mb-1">
            <span>${esc(r.name)} <span style="color:var(--muted)">(${r.count} unid.)</span></span>
            <span style="color:${r.ganancia >= 0 ? "var(--green)" : "var(--red)"};font-weight:600">${money(r.ganancia)} (${r.pct}%)</span>
          </div>
          <div style="background:var(--panel2);border-radius:4px;height:12px;overflow:hidden">
            <div style="width:${Math.max(0, (r.ganancia / maxGanancia * 100)).toFixed(1)}%;height:100%;background:${r.ganancia >= 0 ? "var(--green)" : "var(--red)"};border-radius:4px;transition:.4s"></div>
          </div>
        </div>`).join("")}
      </div>
    </div>`: ""}

    ${pawDivider()}

    <!-- MOVIMIENTOS -->
    <div class="flex items-center justify-between mb-3">
      <p class="text-xs sans font-semibold uppercase tracking-widest" style="color:var(--gold-light)">Movimientos</p>
      <div class="flex gap-2">
        ${FIN_CATS.map(c => `<button onclick="resNewFin('${c.key}')" class="btn-ghost" style="font-size:.75rem;padding:.375rem .625rem;color:${c.color}"><i data-lucide="plus" style="width:12px;height:12px"></i> ${c.label}</button>`).join("")}
      </div>
    </div>
    ${form ? `<div class="card p-4 mb-4">${renderFinForm(form)}</div>` : ""}
    ${finance.length === 0 && !form ?
            `<div class="card p-8 text-center text-sm sans" style="color:var(--muted)">Sin movimientos registrados todavía.</div>` :
            `<div class="space-y-1.5 sans">
        ${finance.slice().sort((a, b) => a.date < b.date ? 1 : -1).slice(0, 50).map(f => {
              const cat = FIN_CATS.find(c => c.key === f.type);
              return `<div class="card p-3 flex items-center gap-3">
            <div class="w-2 h-2 rounded-full shrink-0" style="background:${cat?.color || "var(--muted)"}"></div>
            <div class="flex-1 min-w-0 sans">
              <p class="text-sm truncate">${esc(f.category || f.type)}${f.projectName ? ` · ${esc(f.projectName)}` : ""}</p>
              <p class="text-xs" style="color:var(--muted)">${f.date} · ${esc(cat?.label || f.type)}${f.place ? ` · ${esc(f.place)}` : ""}</p>
            </div>
            <p class="text-sm font-semibold whitespace-nowrap" style="color:${cat?.color || "var(--cream)"}">${money(f.amount)}</p>
            <div class="flex gap-1">
              <button onclick="resEditFin('${f.id}')" class="btn-icon"><i data-lucide="pencil" style="width:13px;height:13px"></i></button>
              <button onclick="resDeleteFin('${f.id}')" class="btn-icon btn-icon-danger"><i data-lucide="trash-2" style="width:13px;height:13px"></i></button>
            </div>
          </div>`;
            }).join("")}
        ${finance.length > 50 ? `<p class="text-xs text-center sans" style="color:var(--muted)">Mostrando los 50 más recientes de ${finance.length} movimientos</p>` : ""}
      </div>`}
  </div>`;
      }
      function renderFinForm(form) {
        const products = STATE.products;
        return `
    <div class="grid sm:grid-cols-2 gap-x-4">
      ${field("Tipo", `<select class="input-base sans" onchange="_resumenState.form.type=this.value">
        ${FIN_CATS.map(c => `<option value="${c.key}"${c.key === form.type ? " selected" : ""}>${c.label}</option>`).join("")}
      </select>`)}
      ${field("Monto", `<input class="input-base" type="number" value="${form.amount || ""}" placeholder="0" oninput="_resumenState.form.amount=this.value" />`)}
    </div>
    ${field("Fecha", `<input class="input-base" type="date" value="${form.date || today()}" oninput="_resumenState.form.date=this.value" />`)}
    ${field("Descripción / categoría", `<input class="input-base" value="${esc(form.category || "")}" placeholder="Ej: Compra de hilos" oninput="_resumenState.form.category=this.value" />`)}
    ${field("Lugar", `<input class="input-base" value="${esc(form.place || "")}" placeholder="Ej: Mercería Don José" oninput="_resumenState.form.place=this.value" />`)}
    ${field("Diseño asociado", `<select class="input-base sans" onchange="_resumenState.form.projectId=this.value;_resumenState.form.projectName=STATE.products.find(p=>p.id===this.value)?.name||''">
      <option value="">— sin diseño —</option>
      ${products.map(p => `<option value="${p.id}"${p.id === form.projectId ? " selected" : ""}>${esc(p.name)}</option>`).join("")}
    </select>`)}
    <div class="flex gap-2"><button onclick="resSaveFin()" class="btn-gold flex-1">Guardar</button><button onclick="_resumenState.form=null;renderApp()" class="btn-ghost">Cancelar</button></div>
  `;
      }
      function resSetGoal() {
        const v = prompt("Meta mensual de ventas:", STATE.salesGoal || 0);
        if (v !== null) { STATE.salesGoal = Number(v) || 0; save("salesGoal"); renderApp(); }
      }
      function resNewFin(type) { _resumenState.form = { id: uid(), type, amount: "", date: today(), place: "", category: "", projectId: "", projectName: "" }; renderApp(); }
      function resEditFin(id) { _resumenState.form = { ...STATE.finance.find(f => f.id === id) }; renderApp(); }
      function resSaveFin() {
        const f = _resumenState.form; if (!f.amount) { alert("Poné un monto."); return; }
        const exists = STATE.finance.some(x => x.id === f.id);
        STATE.finance = exists ? STATE.finance.map(x => x.id === f.id ? f : x) : [f, ...STATE.finance];
        save("finance"); _resumenState.form = null; renderApp();
      }
      function resDeleteFin(id) { if (!confirm("¿Eliminar este movimiento?")) return; STATE.finance = STATE.finance.filter(f => f.id !== id); save("finance"); renderApp(); }

      // =====================================================================
      // HERRAMIENTAS
      // =====================================================================
      function renderHerramientas() {
        const { settings } = STATE;
        return `<div class="max-w-xl">
    <h2 class="text-base font-semibold mb-1" style="color:var(--gold-light)">Herramientas</h2>
    <p class="text-xs mb-4 sans" style="color:var(--muted)">Ajustá la calculadora, generá tu lista de precios y respaldá tus datos.</p>

    <!-- AJUSTES CALCULADORA -->
    <div class="card p-5 mb-5">
      <p class="text-xs font-semibold uppercase tracking-widest mb-3 sans" style="color:var(--gold-light)">Calculadora de costos</p>
      ${field("Margen de tela para tensar en el bastidor", `<div class="flex items-center gap-2"><input class="input-base" type="number" value="${settings.marginCm}" oninput="toolSetSetting('marginCm',this.value)" /><span class="text-sm sans" style="color:var(--muted)">cm por lado</span></div>`)}
      ${field("Milímetros de hilo por puntada", `<div class="flex items-center gap-2"><input class="input-base" type="number" step="0.1" value="${settings.mmPerStitch}" oninput="toolSetSetting('mmPerStitch',this.value)" /><span class="text-sm sans" style="color:var(--muted)">mm / puntada</span></div>`)}
      ${field("Desperdicio de hilo por cambio de color", `<div class="flex items-center gap-2"><input class="input-base" type="number" value="${settings.colorWasteCm}" oninput="toolSetSetting('colorWasteCm',this.value)" /><span class="text-sm sans" style="color:var(--muted)">cm por color</span></div>`)}
    </div>

    <!-- META MENSUAL -->
    <div class="card p-5 mb-5">
      <p class="text-xs font-semibold uppercase tracking-widest mb-3 sans" style="color:var(--gold-light)">Meta mensual de ventas</p>
      ${field("Objetivo de ingresos mensuales", `<div class="flex items-center gap-2"><span class="text-sm sans" style="color:var(--muted)">$</span><input class="input-base" type="number" value="${STATE.salesGoal || ""}" placeholder="0" oninput="STATE.salesGoal=Number(this.value)||0;save('salesGoal')" /></div>`)}
    </div>

    <!-- LISTA DE PRECIOS -->
    <div class="card p-5 mb-5">
      <p class="text-xs font-semibold uppercase tracking-widest mb-3 sans" style="color:var(--gold-light)">Lista de precios pública</p>
      <p class="text-xs mb-3 sans" style="color:var(--muted)">Genera una lista lista para imprimir o guardar como PDF, agrupada por categoría.</p>
      <button onclick="openPriceList()" class="btn-gold"><i data-lucide="printer" style="width:14px;height:14px"></i> Generar lista de precios</button>
    </div>

    <!-- RESPALDO -->
    <div class="card p-5 mb-5">
      <p class="text-xs font-semibold uppercase tracking-widest mb-3 sans" style="color:var(--gold-light)">Respaldo completo</p>
      <p class="text-xs mb-3 sans" style="color:var(--muted)">Descargá todos tus datos en un archivo y restauralos cuando quieras.</p>
      <div class="flex flex-wrap gap-2">
        <button onclick="downloadBackup()" class="btn-ghost"><i data-lucide="download" style="width:14px;height:14px"></i> Descargar respaldo</button>
        <button onclick="document.getElementById('restore-inp').click()" class="btn-ghost"><i data-lucide="upload" style="width:14px;height:14px"></i> Restaurar respaldo</button>
        <input type="file" id="restore-inp" accept=".json" class="hidden" onchange="restoreBackup(this)" />
      </div>
    </div>

    <!-- EXPORTAR JSON -->
    <div class="card p-5">
      <p class="text-xs font-semibold uppercase tracking-widest mb-3 sans" style="color:var(--gold-light)">Importar movimientos</p>
      <p class="text-xs mb-3 sans" style="color:var(--muted)">Pegá datos de finanzas en formato JSON (array de objetos con "tipo","monto","fecha","descripcion").</p>
      <textarea id="import-json-area" class="input-base mb-3" rows="4" placeholder='[{"tipo":"gasto","monto":1500,"fecha":"2025-01-10","descripcion":"Compra hilos"}]'></textarea>
      <button onclick="importJSON()" class="btn-ghost"><i data-lucide="file-json" style="width:14px;height:14px"></i> Importar</button>
      <p id="import-msg" class="text-xs mt-2 sans" style="color:var(--muted)"></p>
    </div>
  </div>`;
      }
      function toolSetSetting(key, val) {
        STATE.settings = { ...STATE.settings, [key]: Number(val) || val };
        save("settings");
      }
      function downloadBackup() {
        const all = { types: STATE.types, products: STATE.products, materials: STATE.materials, finance: STATE.finance, settings: STATE.settings, posts: STATE.posts, clients: STATE.clients, suppliers: STATE.suppliers, templates: STATE.templates, notes: STATE.notes, salesGoal: STATE.salesGoal };
        const blob = new Blob([JSON.stringify(all, null, 2)], { type: "application/json" });
        const url = URL.createObjectURL(blob);
        const a = document.createElement("a"); a.href = url; a.download = `taller-del-irbis-backup-${today()}.json`; a.click();
        URL.revokeObjectURL(url);
      }
      async function restoreBackup(inp) {
        const file = inp.files[0]; if (!file) return;
        try {
          const text = await file.text();
          const data = JSON.parse(text);
          if (data.types) STATE.types = data.types;
          if (data.products) STATE.products = data.products;
          if (data.materials) STATE.materials = data.materials;
          if (data.finance) STATE.finance = data.finance;
          if (data.settings) STATE.settings = data.settings;
          if (data.posts) STATE.posts = data.posts;
          if (data.clients) STATE.clients = data.clients;
          if (data.suppliers) STATE.suppliers = data.suppliers;
          if (data.templates) STATE.templates = data.templates;
          if (data.notes) STATE.notes = data.notes;
          if (data.salesGoal !== undefined) STATE.salesGoal = data.salesGoal;
          saveAll(); renderApp(); alert("Respaldo restaurado con éxito.");
        } catch (e) { alert("No se pudo leer el archivo de respaldo."); }
        inp.value = "";
      }
      function importJSON() {
        const area = document.getElementById("import-json-area");
        const msg = document.getElementById("import-msg");
        if (!area || !msg) return;
        try {
          const rows = JSON.parse(area.value);
          if (!Array.isArray(rows)) { msg.textContent = "Debe ser un array JSON."; return; }
          const mapped = rows.map(r => {
            const amt = Number(r.monto || r.amount || r.importe || 0); if (!amt) return null;
            let type = (r.tipo || r.type || r.categoria || "gasto").toString().toLowerCase();
            if (type.includes("ingres")) type = "ingreso"; else if (type.includes("reinv")) type = "reinversion"; else type = "gasto";
            return { id: uid(), type, amount: amt, date: r.fecha || r.date || today(), place: r.lugar || r.place || "", category: r.descripcion || r.description || r.detalle || "", projectId: "", projectName: "" };
          }).filter(Boolean);
          if (!mapped.length) { msg.textContent = "No se encontraron filas con monto válido."; return; }
          STATE.finance = [...mapped, ...STATE.finance]; save("finance");
          msg.textContent = `Se importaron ${mapped.length} movimientos.`;
        } catch (e) { msg.textContent = "JSON inválido. Revisá el formato."; }
      }

      // =====================================================================
      // LISTA DE PRECIOS
      // =====================================================================
      function openPriceList() {
        const { products, types } = STATE;
        const grouped = types.map(t => ({ type: t, items: products.filter(p => p.type === t && p.salePrice) })).filter(g => g.items.length > 0);
        const total = grouped.reduce((s, g) => s + g.items.length, 0);
        const printDate = new Date().toLocaleDateString("es-AR", { day: "numeric", month: "long", year: "numeric" });
        document.getElementById("price-list-date").textContent = `Precios en pesos argentinos · Válida al ${printDate}`;
        document.getElementById("price-list-counts").innerHTML = `<div>${total} diseño${total !== 1 ? "s" : ""}</div><div>${grouped.length} categoría${grouped.length !== 1 ? "s" : ""}</div>`;
        const body = document.getElementById("price-list-body");
        if (grouped.length === 0) {
          body.innerHTML = `<p style="font-size:13px;color:#8A7A5E;font-family:ui-sans-serif,system-ui;text-align:center;padding:24px 0">Todavía no hay diseños con precio de venta cargado.</p>`;
        } else {
          body.innerHTML = grouped.map((g, gi) => `
      <div style="margin-bottom:${gi < grouped.length - 1 ? 28 : 0}px">
        <div style="display:flex;align-items:center;gap:10px;margin-bottom:12px">
          <div style="width:3px;height:18px;border-radius:2px;background:#CD8E30;flex-shrink:0"></div>
          <span style="font-size:11px;font-weight:700;letter-spacing:.2em;text-transform:uppercase;color:#B5762A;font-family:ui-sans-serif,system-ui">${g.type}</span>
          <div style="flex:1;height:1px;background:#E8D9BE"></div>
          <span style="font-size:10px;color:#B5A080;font-family:ui-sans-serif,system-ui">${g.items.length}</span>
        </div>
        <div>${g.items.map((p, pi) => `<div style="display:flex;justify-content:space-between;align-items:baseline;padding:7px 0;border-bottom:${pi < g.items.length - 1 ? "1px dashed #E4D0B0" : "none"};font-family:ui-sans-serif,system-ui">
          <span style="font-size:13px;color:#2A1E0A;flex:1;padding-right:16px">${p.name}</span>
          <span style="font-size:14px;font-weight:700;color:#8C5E22;white-space:nowrap">${money(p.salePrice)}</span>
        </div>`).join("")}</div>
      </div>`).join("") + `<div style="margin-top:32px;padding-top:20px;border-top:1px solid #E0CBA0"><div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:8px"><div style="font-size:10px;color:#B5A080;font-family:ui-sans-serif,system-ui;line-height:1.6"><div>Los precios pueden variar según personalización.</div><div>Consultá por diseños a medida.</div></div><div style="font-size:13px;font-weight:600;color:#8C5E22">🐆 Taller del Irbis</div></div></div>`;
        }
        document.getElementById("price-list-overlay").style.display = "flex";
        lucide.createIcons();
      }
      function closePriceList() { document.getElementById("price-list-overlay").style.display = "none"; }

      // =====================================================================
      // BOOT
      // =====================================================================
      window.addEventListener("DOMContentLoaded", async () => {
        load();
        renderApp();
        document.addEventListener("click", e => {
          const btn = e.target.closest(".btn-gold,.btn-ghost,.btn-icon");
          if (!btn || btn.disabled) return;
          const rect = btn.getBoundingClientRect();
          const ripple = document.createElement("span");
          const size = Math.max(rect.width, rect.height) * 1.6;
          ripple.style.cssText = `position:absolute;border-radius:50%;pointer-events:none;width:${size}px;height:${size}px;left:${e.clientX - rect.left - size / 2}px;top:${e.clientY - rect.top - size / 2}px;background:rgba(255,255,255,.35);transform:scale(0);animation:ripplePop .55s ease-out;z-index:0`;
          if (getComputedStyle(btn).position === "static") btn.style.position = "relative";
          btn.style.overflow = "hidden";
          btn.appendChild(ripple);
          ripple.addEventListener("animationend", () => ripple.remove());
        });
        const header = document.getElementById("app-header");
        window.addEventListener("scroll", () => {
          header.style.boxShadow = window.scrollY > 6 ? "0 8px 28px rgba(0,0,0,.22)" : "none";
        }, { passive: true });
      });
      const firebaseConfig = {
        apiKey: "AIzaSyA4D4AS5HdvsIBMudCFAgtT6FU3c3Ge7Tg",
        authDomain: "taller-del-irbis2.firebaseapp.com",
        projectId: "taller-del-irbis2",
        storageBucket: "taller-del-irbis2.firebasestorage.app",
        messagingSenderId: "558460112028",
        appId: "1:558460112028:web:a3829ae913b221a8797159"
      };

      firebase.initializeApp(firebaseConfig);
      const db = firebase.firestore();

      async function cloudSave() {
        await db.collection("irbis").doc("principal").set(STATE);
      }

      async function cloudLoad() {
        const snap = await db.collection("irbis").doc("principal").get();

        if (snap.exists) {
          Object.assign(STATE, snap.data());
        }
      }

  </script>
</body>

</html>

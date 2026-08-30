<!doctype html>
<html lang="id">
 <head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260828-05-5fe3063","C":{"Abril Fatface":"YACgEZbkUVE,0","Alfa Slab One":"YACgEYS9sJU,0","Anton":"YACgEcYqQ-A,0","Archivo":"YAHO2-t-jNE,0","Arial":"YAGyDvJ_4Ts,0","Bebas Neue":"YACgESME5ew,0","Bricolage Grotesque":"YAFyMcdwzpc,0","Canva Sans":"YAFLd8sKbwc,2","Caveat":"YALBs2ploWQ,0","Comic Sans MS":"YAHO2VMiyZo,0","Cormorant Garamond":"YAFdJhX-538,0","Courier New":"YAGzXiGs0_8,0","DM Sans":"YAD1aU3sLnI,0","DM Serif Display":"YAD1aYG82rc,0","Forum":"YACgEcnnqB4,0","Fraunces":"YAEul-FRQw4,0","Georgia":"YAGzXkO0pEM,0","Helvetica Neue":"YAFcf6CtJfI,0","Impact":"YAFcfnjI7Vk,0","Inter":"YAFdJvSyp_k,3","Iowan Old Style":"YAGNIFa8j9o,0","Jacques Francois":"YAHO2a5g66Q,0","JetBrains Mono":"YAFdJksXcAk,0","Libre Baskerville":"YACgEUFdPdA,0","Manrope":"YAHO2b2feC4,0","Merriweather":"YACgEXvHxxs,0","Montserrat":"YADLjI9qxTA,0","Nunito":"YACgEX8C5Gg,0","Oleo Script":"YACgEQQ14jI,0","Phantom Sans":"YAHO2E8Pb88,0","Playfair Display":"YACgEYmuCJE,0","Poppins":"YAFdJjbTu24,1","Press Start 2P":"YAFyGr-8pmQ,0","Quicksand":"YADWjpfPmdk,0","Raleway":"YACgEVg3xZg,0","Segoe UI":"YAHNdRD1Klw,0","Source Sans 3":"YAG4lO1Mj10,0","Spectral":"YAHO2rVUHIM,0","Times New Roman":"YAGzXW3gftg,0","Times":"YAGzXW3gftg,0","Ubuntu":"YACgERDU--Q,0","Work Sans":"YAGXhLOKv44,0","Yellowtail":"YACgEYG4kG4,0","ui-monospace":"YADlN8CFZ8Q,0","ui-sans-serif":"YACkoN-xg4g,0"}}');</script><script src="/_sdk/50d846425a1e5082.telemetry_sdk.js" integrity="sha512-Otbex+ztlVbcEGql0rXGd/3E3ee/hqAntg6DeuUEMG6pIPbXGOSvZbFZVzknAXi1tH/itQ+ijEhOTr2aWj6CXg=="></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mathematics of Champion</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet">
  <style>
    :root {
      --navy: #071a36;
      --navy-2: #0b2850;
      --cyan: #66d9ff;
      --soft-blue: #bcecff;
      --red: #ef4444;
      --yellow: #f5c542;
      --pink: #ec4899;
      --green: #22c55e;
      --purple: #6d28d9;
      --orange: #f97316;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: "DM Sans", sans-serif;
      color: #eef8ff;
      background: var(--navy);
      overflow-x: hidden;
    }
    .arena-bg {
      min-height: calc(100 * min(var(--vh, 1vh), 1vh));
      width: 100%;
      background:
        radial-gradient(circle at 15% 5%, rgba(43, 163, 222, .24), transparent 27rem),
        radial-gradient(circle at 88% 16%, rgba(109, 40, 217, .18), transparent 22rem),
        linear-gradient(135deg, #06152e 0%, #0a2850 50%, #071a36 100%);
      position: relative;
      overflow: hidden;
    }
    .arena-bg::before {
      content: "";
      position: absolute;
      inset: 0;
      pointer-events: none;
      opacity: .22;
      background-image: linear-gradient(rgba(127, 218, 255, .14) 1px, transparent 1px), linear-gradient(90deg, rgba(127, 218, 255, .14) 1px, transparent 1px);
      background-size: 42px 42px;
      mask-image: linear-gradient(to bottom, black, transparent 82%);
    }
    .glass {
      background: rgba(8, 34, 70, .74);
      border: 1px solid rgba(154, 225, 255, .18);
      box-shadow: 0 20px 50px rgba(0, 0, 0, .24);
      backdrop-filter: blur(15px);
    }
    .title-glow { text-shadow: 0 0 30px rgba(102, 217, 255, .45); }
    .pulse-dot { animation: pulseDot 1.5s infinite; }
    @keyframes pulseDot { 50% { transform: scale(1.45); opacity: .4; } }
    .question-tile {
      min-height: 62px;
      border: 1px solid rgba(255,255,255,.35);
      background: linear-gradient(145deg, #c7f0ff, #85d5f6);
      color: #0b3152;
      font-weight: 800;
      border-radius: 13px;
      transition: transform .18s ease, box-shadow .18s ease, filter .18s ease;
      position: relative;
      overflow: hidden;
    }
    .question-tile:not(.locked):hover {
      transform: translateY(-4px) scale(1.04);
      box-shadow: 0 10px 24px rgba(72, 205, 255, .45);
      filter: brightness(1.08);
    }
    .question-tile:not(.locked):active { transform: scale(.96); }
    .question-tile.locked { cursor: not-allowed; color: white; }
    .question-tile .team-mini { font-size: 8px; display: block; letter-spacing: .05em; margin-top: 2px; }
    .score-card { transition: transform .3s ease, box-shadow .3s ease; }
    .score-card.pop { transform: scale(1.08); box-shadow: 0 0 22px rgba(255,255,255,.4); }
    .modal-layer {
      position: fixed; inset: 0; z-index: 50; display: flex; align-items: center; justify-content: center;
      padding: 18px; background: rgba(2, 10, 25, .73); backdrop-filter: blur(9px);
    }
    .hidden-layer { display: none !important; }
    .modal-card {
      width: min(610px, 100%); border-radius: 25px; border: 1px solid rgba(164,232,255,.3);
      background: linear-gradient(150deg, #0e3766, #071a36); box-shadow: 0 30px 80px rgba(0,0,0,.5);
    }
    .success-ring { animation: victory .75s cubic-bezier(.2,.9,.25,1) both; }
    @keyframes victory { from { opacity: 0; transform: scale(.35) rotate(-15deg); } to { opacity: 1; transform: scale(1) rotate(0); } }
    .wrong-shake { animation: shake .5s ease-in-out both; }
    @keyframes shake { 20%,60% { transform: translateX(-14px); } 40%,80% { transform: translateX(14px); } }
    .confetti { position: fixed; width: 10px; height: 15px; z-index: 70; animation: fall 1.6s linear forwards; }
    @keyframes fall { to { transform: translate(var(--x), calc(100 * min(var(--vh, 1vh), 1vh))) rotate(620deg); opacity: 0; } }
    .tab-btn.active { background: #66d9ff; color: #082448; }
    .podium-card { animation: rise .65s ease both; }
    @keyframes rise { from { transform: translateY(45px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
    .team-choice { transition: transform .18s ease, filter .18s ease; }
    .team-choice:hover { transform: translateY(-4px); filter: brightness(1.12); }
    .input-arena { background: rgba(1,13,31,.6); border: 1px solid rgba(151,224,255,.25); color: white; }
    .input-arena:focus { outline: 2px solid #66d9ff; outline-offset: 2px; }
    #teacher-panel { max-height: calc(90 * min(var(--vh, 1vh), 1vh)); overflow-y: auto; }
  </style>
  <script src="/_sdk/b3bf9e8ac58e6ad6.data_sdk.js" type="text/javascript" integrity="sha512-otc1u9NYq9Ms5Jt//7vmhrrqR5CLPr8Jdgs6741gqniClfLMcfmC+jK/cKuQdhLv6G0esJ/FzaMS9tv0T/vj/Q=="></script>
  <script src="/_sdk/a6de989e8af05ea5.resizing_sdk.js" type="text/javascript" integrity="sha512-cceAQMIleYr/3eg7o5WzN46w0HpgI1sxi+5kDUb7CmTjHEpgBtINDxtOpnNeUtujjui8NG0OSDgUMl0/E2lT2A=="></script>
 </head>
 <body data-template-id="__page-root">
  <div class="arena-bg">
   <header class="relative z-10 w-full px-4 pt-4 md:px-7 md:pt-6">
    <div data-template-id="header-panel" class="canva-header glass mx-auto max-w-[1450px] rounded-3xl px-5 py-5 md:px-7">
     <div class="flex flex-col gap-5 xl:flex-row xl:items-center xl:justify-between">
      <div>
       <div class="mb-2 flex items-center gap-2 text-xs font-bold tracking-[.22em] text-cyan-200"><span class="pulse-dot h-2 w-2 rounded-full bg-cyan-300"></span> LIVE CLASSROOM ARENA
       </div>
       <h1 data-template-id="game-title" class="canva-text title-glow text-3xl font-extrabold tracking-tight md:text-4xl"></h1>
       <p data-template-id="game-tagline" class="canva-text mt-1 text-sm text-blue-100 md:text-base"></p>
      </div>
      <div class="flex flex-wrap items-center gap-3">
       <div class="rounded-2xl border border-cyan-200/20 bg-slate-950/35 px-4 py-2 text-center"><span data-template-id="class-label" class="canva-text block text-[10px] font-bold tracking-widest text-cyan-200"></span> <span id="class-name-display" class="text-sm font-bold">Kelas Matematika</span>
       </div>
       <div class="rounded-2xl border border-cyan-200/20 bg-slate-950/35 px-4 py-2 text-center"><span data-template-id="teacher-label" class="canva-text block text-[10px] font-bold tracking-widest text-cyan-200"></span> <span id="teacher-name-display" class="text-sm font-bold">Guru Champion</span>
       </div><button id="teacher-open" type="button" aria-label="Buka Teacher Control Panel" class="rounded-2xl border border-cyan-200/25 bg-cyan-300/15 p-3 text-cyan-100 transition hover:bg-cyan-300 hover:text-slate-900 focus:outline-none focus:ring-2 focus:ring-cyan-200"> <i data-lucide="graduation-cap" class="h-5 w-5"></i> </button>
      </div>
     </div>
     <div class="mt-5 flex flex-col gap-4 border-t border-cyan-100/10 pt-4 lg:flex-row lg:items-center lg:justify-between">
      <div class="flex flex-wrap gap-2"><button id="start-btn" data-template-id="start-button" type="button" class="canva-button rounded-xl px-4 py-2 text-sm font-extrabold transition hover:brightness-110 focus:outline-none focus:ring-2 focus:ring-white"></button> <button id="pause-btn" data-template-id="pause-button" type="button" class="canva-button rounded-xl px-4 py-2 text-sm font-extrabold transition hover:brightness-110 focus:outline-none focus:ring-2 focus:ring-white"></button> <button id="gameover-btn" data-template-id="gameover-button" type="button" class="canva-button rounded-xl px-4 py-2 text-sm font-extrabold transition hover:brightness-110 focus:outline-none focus:ring-2 focus:ring-white"></button>
      </div>
      <div class="flex items-center gap-3">
       <div class="rounded-xl bg-slate-950/45 px-4 py-2"><span data-template-id="timer-label" class="canva-text mr-2 text-xs font-bold tracking-wider text-cyan-100"></span> <span id="timer" class="font-mono text-xl font-bold text-white">00:00</span>
       </div><span id="game-status" class="rounded-full border border-cyan-200/20 px-3 py-2 text-xs font-bold text-cyan-100">SIAP DIMULAI</span>
      </div>
     </div>
    </div>
   </header>
   <main class="relative z-10 mx-auto w-full max-w-[1450px] px-4 py-5 md:px-7 md:py-7">
    <section aria-label="Scoreboard kelompok" class="mb-5">
     <h2 data-template-id="scoreboard-title" class="canva-text mb-3 text-sm font-extrabold tracking-[.16em] text-cyan-100"></h2>
     <div id="scoreboard" class="grid grid-cols-2 gap-3 sm:grid-cols-3 xl:grid-cols-6"></div>
    </section>
    <div class="grid gap-5 xl:grid-cols-[1fr_330px]">
     <section data-template-id="arena-panel" class="canva-section glass rounded-3xl p-4 md:p-6">
      <div class="mb-5 flex flex-wrap items-end justify-between gap-3">
       <div>
        <h2 data-template-id="arena-title" class="canva-text text-2xl font-extrabold"></h2>
        <p data-template-id="arena-description" class="canva-text mt-1 text-sm text-blue-100"></p>
       </div>
       <div class="rounded-full border border-cyan-200/20 bg-cyan-200/10 px-4 py-2 text-xs font-bold text-cyan-50"><span id="answered-count">0</span> / 100 SOAL TERKUNCI
       </div>
      </div>
      <div id="question-grid" class="grid grid-cols-5 gap-2 sm:grid-cols-8 md:grid-cols-10 lg:grid-cols-10 xl:grid-cols-10"></div>
     </section>
     <aside data-template-id="leaderboard-panel" class="canva-sidebar glass rounded-3xl p-5">
      <div class="mb-4 flex items-center justify-between">
       <h2 data-template-id="leaderboard-title" class="canva-text text-xl font-extrabold"></h2><i data-lucide="trophy" class="h-5 w-5 text-yellow-300"></i>
      </div>
      <div id="leaderboard" class="space-y-2"></div>
      <p data-template-id="leaderboard-help" class="canva-text mt-5 border-t border-cyan-100/10 pt-4 text-xs leading-relaxed text-blue-100"></p>
     </aside>
    </div>
   </main>
  </div>
  <div id="question-modal" class="modal-layer hidden-layer" role="dialog" aria-modal="true" aria-labelledby="question-heading">
   <form id="answer-form" class="modal-card p-6 md:p-8">
    <div class="flex items-start justify-between gap-4">
     <div>
      <p id="question-number" class="text-xs font-extrabold tracking-[.2em] text-cyan-200">SOAL 01</p>
      <h2 id="question-heading" class="mt-2 text-2xl font-extrabold">Pilih Jawaban</h2>
     </div><button id="close-question" type="button" aria-label="Tutup soal" class="rounded-xl bg-white/10 p-2 text-white hover:bg-white/20 focus:outline-none focus:ring-2 focus:ring-cyan-200"><i data-lucide="x"></i></button>
    </div>
    <fieldset class="mt-4"><legend class="mb-2 text-sm font-bold text-cyan-50">PILIH JAWABAN</legend>
     <div id="answer-choices" class="grid grid-cols-1 gap-3 sm:grid-cols-2" role="radiogroup" aria-label="Pilihan jawaban"></div>
    </fieldset>
    <p id="answer-message" class="mt-2 min-h-[20px] text-sm text-red-200"></p><button data-template-id="submit-answer-button" type="submit" class="canva-button mt-3 w-full rounded-xl px-5 py-3 font-extrabold transition hover:brightness-110 focus:outline-none focus:ring-2 focus:ring-white"></button>
   </form>
  </div>
  <div id="result-overlay" class="modal-layer hidden-layer" role="status" aria-live="assertive">
   <div id="result-card" class="modal-card max-w-md p-9 text-center">
    <div id="result-symbol" class="success-ring text-8xl font-black"></div>
    <h2 id="result-title" class="mt-3 text-4xl font-extrabold"></h2>
    <p id="result-detail" class="mt-3 text-lg font-bold"></p>
   </div>
  </div>
  <div id="team-modal" class="modal-layer hidden-layer" role="dialog" aria-modal="true" aria-labelledby="team-heading">
   <div class="modal-card p-6 md:p-8">
    <p class="text-center text-xs font-bold tracking-[.2em] text-cyan-200">JAWABAN BENAR</p>
    <h2 id="team-heading" data-template-id="team-heading" class="canva-text mt-2 text-center text-3xl font-extrabold"></h2>
    <p data-template-id="team-helper" class="canva-text mx-auto mt-2 max-w-sm text-center text-sm text-blue-100"></p>
    <div id="team-choices" class="mt-6 grid grid-cols-2 gap-3 sm:grid-cols-3"></div>
   </div>
  </div>
  <div id="teacher-modal" class="modal-layer hidden-layer" role="dialog" aria-modal="true" aria-labelledby="teacher-panel-title">
   <section id="teacher-panel" class="modal-card w-[min(1050px,100%)] p-5 md:p-7">
    <div class="flex items-center justify-between gap-4">
     <div>
      <p class="text-xs font-bold tracking-[.2em] text-cyan-200">PENGATURAN KELAS</p>
      <h2 id="teacher-panel-title" data-template-id="teacher-title" class="canva-text mt-1 text-2xl font-extrabold"></h2>
     </div><button id="teacher-close" type="button" aria-label="Tutup panel guru" class="rounded-xl bg-white/10 p-2 hover:bg-white/20 focus:outline-none focus:ring-2 focus:ring-cyan-200"><i data-lucide="x"></i></button>
    </div>
    <div class="mt-6 flex flex-wrap gap-2 border-b border-cyan-100/15 pb-4"><button type="button" class="tab-btn active rounded-xl px-4 py-2 text-sm font-bold" data-tab="dashboard">Dashboard</button> <button type="button" class="tab-btn rounded-xl px-4 py-2 text-sm font-bold text-cyan-50" data-tab="bank">Bank Soal</button> <button type="button" class="tab-btn rounded-xl px-4 py-2 text-sm font-bold text-cyan-50" data-tab="teams">Kelompok</button> <button type="button" class="tab-btn rounded-xl px-4 py-2 text-sm font-bold text-cyan-50" data-tab="controls">Kontrol Game</button>
    </div>
    <div id="tab-dashboard" class="teacher-tab mt-5">
     <div class="grid gap-4 md:grid-cols-3">
      <div class="rounded-2xl bg-cyan-300/10 p-5">
       <p class="text-xs font-bold text-cyan-100">STATUS</p>
       <p id="dashboard-status" class="mt-2 text-xl font-extrabold">SIAP DIMULAI</p>
      </div>
      <div class="rounded-2xl bg-cyan-300/10 p-5">
       <p class="text-xs font-bold text-cyan-100">SOAL TERJAWAB</p>
       <p id="dashboard-answered" class="mt-2 text-xl font-extrabold">0 / 100</p>
      </div>
      <div class="rounded-2xl bg-cyan-300/10 p-5">
       <p class="text-xs font-bold text-cyan-100">DURASI</p>
       <p id="dashboard-time" class="mt-2 text-xl font-extrabold">00:00</p>
      </div>
     </div>
     <div class="mt-5 rounded-2xl border border-cyan-100/15 bg-slate-950/20 p-5">
      <h3 class="font-extrabold">Identitas Kelas</h3>
      <p class="mt-2 text-sm leading-relaxed text-blue-100">Ubah nama kelas dan guru yang tampil pada header arena.</p>
      <div class="mt-4 grid gap-4 md:grid-cols-2">
       <div><label for="class-name-input" class="mb-2 block text-sm font-bold text-cyan-100">Nama Kelas</label> <input id="class-name-input" type="text" class="input-arena w-full rounded-xl px-4 py-3" value="Kelas Matematika">
       </div>
       <div><label for="teacher-name-input" class="mb-2 block text-sm font-bold text-cyan-100">Nama Guru</label> <input id="teacher-name-input" type="text" class="input-arena w-full rounded-xl px-4 py-3" value="Guru Champion">
       </div>
      </div><button id="save-class-info" type="button" class="mt-4 rounded-xl bg-cyan-300 px-5 py-3 font-extrabold text-slate-900 hover:bg-cyan-200">Simpan Identitas Kelas</button>
      <p id="class-info-message" class="mt-2 min-h-[20px] text-sm text-cyan-100"></p>
     </div>
    </div>
    <div id="tab-bank" class="teacher-tab mt-5 hidden">
     <div class="mb-4 flex flex-wrap items-center justify-between gap-2">
      <div>
       <h3 class="font-extrabold">Bank Soal: Kunci Jawaban &amp; Poin</h3>
       <p class="text-sm text-blue-100">Tidak ada input pertanyaan. Ubah jawaban benar atau poin sebelum soal dimainkan.</p>
      </div><button id="save-bank" type="button" class="rounded-xl bg-cyan-300 px-4 py-2 text-sm font-extrabold text-slate-900 hover:bg-cyan-200">Simpan Perubahan</button>
     </div>
     <p id="bank-message" class="mb-3 min-h-[20px] text-sm text-cyan-100"></p>
     <div class="overflow-x-auto rounded-2xl border border-cyan-100/15">
      <table class="w-full min-w-[600px] text-left text-sm">
       <thead class="bg-cyan-300/10 text-cyan-100">
        <tr>
         <th class="px-4 py-3">No.</th>
         <th class="px-4 py-3">A</th>
         <th class="px-4 py-3">B</th>
         <th class="px-4 py-3">C</th>
         <th class="px-4 py-3">D</th>
         <th class="px-4 py-3">E</th>
         <th class="px-4 py-3">Kunci</th>
         <th class="px-4 py-3">Poin</th>
         <th class="px-4 py-3">Status</th>
        </tr>
       </thead>
       <tbody id="bank-body"></tbody>
      </table>
     </div>
    </div>
    <div id="tab-teams" class="teacher-tab mt-5 hidden">
     <h3 class="font-extrabold">Pengaturan Nama Kelompok</h3>
     <p class="mt-1 text-sm text-blue-100">Warna kelompok tetap digunakan sebagai identitas arena.</p>
     <div id="team-settings" class="mt-5 grid gap-3 md:grid-cols-2"></div><button id="save-teams" type="button" class="mt-5 rounded-xl bg-cyan-300 px-5 py-3 font-extrabold text-slate-900 hover:bg-cyan-200">Simpan Nama Kelompok</button>
    </div>
    <div id="tab-controls" class="teacher-tab mt-5 hidden">
     <h3 class="font-extrabold">Kontrol Permainan</h3>
     <div class="mt-5 grid gap-3 sm:grid-cols-2"><button id="panel-start" type="button" class="rounded-2xl bg-green-500 px-5 py-4 font-extrabold text-white hover:brightness-110">MULAI / LANJUTKAN</button> <button id="panel-pause" type="button" class="rounded-2xl bg-yellow-400 px-5 py-4 font-extrabold text-slate-900 hover:brightness-110">PAUSE GAME</button> <button id="panel-reset" type="button" class="rounded-2xl bg-slate-600 px-5 py-4 font-extrabold text-white hover:brightness-110">RESET ARENA</button> <button id="panel-gameover" type="button" class="rounded-2xl bg-red-500 px-5 py-4 font-extrabold text-white hover:brightness-110">GAME OVER</button>
     </div>
    </div>
   </section>
  </div>
  <div id="confirm-modal" class="modal-layer hidden-layer" role="dialog" aria-modal="true" aria-labelledby="confirm-title">
   <div class="modal-card max-w-md p-7 text-center"><i data-lucide="circle-alert" class="mx-auto h-12 w-12 text-yellow-300"></i>
    <h2 id="confirm-title" data-template-id="confirm-title" class="canva-text mt-4 text-2xl font-extrabold"></h2>
    <p data-template-id="confirm-message" class="canva-text mt-2 text-blue-100"></p>
    <div class="mt-6 grid grid-cols-2 gap-3"><button id="confirm-end" data-template-id="confirm-end-button" type="button" class="canva-button rounded-xl px-4 py-3 font-extrabold"></button> <button id="cancel-end" data-template-id="cancel-end-button" type="button" class="canva-button rounded-xl px-4 py-3 font-extrabold"></button>
    </div>
   </div>
  </div>
  <div id="gameover-screen" class="modal-layer hidden-layer" role="dialog" aria-modal="true" aria-labelledby="final-title">
   <section class="w-full max-w-5xl px-3 text-center">
    <p class="text-sm font-bold tracking-[.25em] text-cyan-200">PERTANDINGAN TELAH BERAKHIR</p>
    <h2 id="final-title" data-template-id="gameover-title" class="canva-text title-glow mt-2 text-4xl font-extrabold md:text-6xl"></h2>
    <p data-template-id="gameover-subtitle" class="canva-text mt-3 text-lg text-blue-100"></p>
    <div id="podium" class="mt-8 flex items-end justify-center gap-3 md:gap-6"></div>
    <div class="glass mx-auto mt-6 max-w-3xl rounded-3xl p-5 text-left">
     <h3 data-template-id="final-ranking-title" class="canva-text font-extrabold"></h3>
     <div id="final-ranking" class="mt-3 space-y-2"></div>
    </div>
    <div class="mt-6 flex justify-center gap-3"><button id="play-again" data-template-id="play-again-button" type="button" class="canva-button rounded-xl px-5 py-3 font-extrabold"></button> <button id="back-settings" data-template-id="back-settings-button" type="button" class="canva-button rounded-xl px-5 py-3 font-extrabold"></button>
    </div>
   </section>
  </div>
  <script src="/_sdk/c6bcadf20ce5820f.editing_sdk.js" integrity="sha512-LVukVCTKnKSxy98w+wCVzDAxVXBG2vy32XblXlmJD9CPFnF2/FVc75CFngl41IdXcX3sVHJc9olw64zrPM/FIA=="></script>
  <script>
    const pointValues = [
      30,30,30,30,30,30,30,30,30,30,50,50,50,50,50,50,50,50,50,50,
      25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,25,
      10,70,50,70,20,70,70,70,30,70,50,50,50,50,50,50,50,50,50,50,
      50,50,50,50,50,70,70,70,70,70,70,70,70,70,70,70,70,70,70,70,
      100,100,100,100,100,100,100,100,100,100,100,100,100,100,100,100,100,100,100,100
    ];

    const exponentQuestions = [
      ["2¹", "1"], ["2³", "8"], ["2⁴", "16"], ["3²", "9"], ["5²", "25"],
      ["10²", "100"], ["2⁵", "32"], ["3³", "27"], ["4²", "16"], ["10³", "1000"],
      ["2⁶", "64"], ["3⁴", "81"], ["5³", "125"], ["2⁷", "128"], ["4³", "64"],
      ["10⁴", "10000"], ["2⁸", "256"], ["3⁵", "243"], ["5⁴", "625"], ["2⁹", "512"],
      ["log₂ 4", "2"], ["log₂ 8", "3"], ["log₃ 9", "2"], ["log₅ 25", "2"],
      ["log₁₀ 100", "2"], ["log₂ 16", "4"], ["log₃ 27", "3"], ["log₄ 16", "2"],
      ["log₅ 125", "3"], ["log₁₀ 1000", "3"], ["log₂ 32", "5"], ["log₃ 81", "4"],
      ["log₄ 64", "3"], ["log₅ 625", "4"], ["log₁₀ 10000", "4"], ["log₂ 64", "6"],
      ["log₃ 243", "5"], ["log₄ 256", "4"], ["log₅ 3125", "5"], ["log₁₀ 100000", "5"]
    ];

    const questions = Array.from({ length: 100 }, (_, index) => {
      const n = index + 1;
      if (n <= 40) {
        const [expression, answer] = exponentQuestions[index];
        return { id: n, options: [answer, "0", "1", "2", "3"], correct: "A", points: pointValues[index], locked: false, winner: null };
      }
      if (n <= 60) {
        const base = (n % 4) + 2;
        const pow = (n % 5) + 2;
        const value = Math.pow(base, pow);
        return { id: n, options: [String(pow), "0", "1", "2", "3"], correct: "A", points: pointValues[index], locked: false, winner: null };
      }
      if (n <= 80) {
        const base = n % 2 === 0 ? 10 : 2;
        const pow = (n % 6) + 2;
        const value = Math.pow(base, pow);
        return { id: n, options: [String(pow), "0", "1", "2", "3"], correct: "A", points: pointValues[index], locked: false, winner: null };
      }
      const answers = ["4", "5", "6", "7", "8", "9", "10", "3", "2", "1", "12", "15", "16", "20", "25", "30", "32", "36", "40", "50"];
      const answer = answers[n - 81];
      const base = n % 3 === 0 ? 3 : 2;
      const exponent = Math.max(2, Math.round(Math.log(Number(answer) || 4) / Math.log(base)));
      return { id: n, options: [answer, "0", "1", "2", "3"], correct: "A", points: pointValues[index], locked: false, winner: null };
    });

    const teams = [
      { id: "blue", name: "BIRU", color: "#3b82f6", score: 0, emoji: "🔵" },
      { id: "red", name: "MERAH", color: "#ef4444", score: 0, emoji: "🔴" },
      { id: "purple", name: "UNGU", color: "#6d28d9", score: 0, emoji: "🟣" },
      { id: "yellow", name: "KUNING", color: "#f5c542", score: 0, emoji: "🟡" },
      { id: "green", name: "HIJAU", color: "#22c55e", score: 0, emoji: "🟢" },
      { id: "orange", name: "ORANGE", color: "#f97316", score: 0, emoji: "🟠" }
    ];

    let currentQuestion = null;
    let selectedAnswer = "";
    let gameState = "ready";
    let elapsedSeconds = 0;
    let timerInterval = null;

    const $ = (id) => document.getElementById(id);
    const normalize = (value) => value.toLowerCase().replace(/\s+/g, "").replace(/,/g, ".").replace(/[×x]/g, "*").replace(/\^/g, "").trim();

    function renderQuestions() {
      const grid = $("question-grid");
      grid.innerHTML = "";
      questions.forEach(q => {
        const button = document.createElement("button");
        button.type = "button";
        button.className = "question-tile " + (q.locked ? "locked" : "");
        button.dataset.id = q.id;
        button.innerHTML = `<span>${q.id}</span>${q.locked ? `<span class="team-mini">${teams.find(t => t.id === q.winner).name}</span>` : ""}`;
        if (q.locked) button.style.background = teams.find(t => t.id === q.winner).color;
        button.addEventListener("click", () => openQuestion(q));
        grid.appendChild(button);
      });
      $("answered-count").textContent = questions.filter(q => q.locked).length;
      $("dashboard-answered").textContent = `${questions.filter(q => q.locked).length} / 100`;
    }

    function sortedTeams() { return [...teams].sort((a, b) => b.score - a.score || a.name.localeCompare(b.name)); }

    function renderScores() {
      const board = $("scoreboard");
      board.innerHTML = "";
      teams.forEach(team => {
        const card = document.createElement("div");
        card.id = `score-${team.id}`;
        card.className = "score-card glass flex items-center justify-between rounded-2xl px-4 py-3";
        card.innerHTML = `<div class="flex items-center gap-2"><span class="h-3 w-3 rounded-full" style="background:${team.color}"></span><span class="text-xs font-extrabold tracking-wide">${team.name}</span></div><strong class="text-xl">${team.score}</strong>`;
        board.appendChild(card);
      });

      const leaderboard = $("leaderboard");
      leaderboard.innerHTML = "";
      sortedTeams().forEach((team, index) => {
        const ranks = ["🥇", "🥈", "🥉"];
        const row = document.createElement("div");
        row.className = "flex items-center gap-3 rounded-xl border border-cyan-100/10 bg-slate-950/20 px-3 py-3";
        row.innerHTML = `<span class="w-6 text-center text-sm font-bold">${ranks[index] || index + 1}</span><span class="h-3 w-3 rounded-full" style="background:${team.color}"></span><span class="min-w-0 flex-1 truncate text-sm font-bold">${team.name}</span><strong class="text-lg">${team.score}</strong>`;
        leaderboard.appendChild(row);
      });
    }

    function updateTimer() {
      const mins = String(Math.floor(elapsedSeconds / 60)).padStart(2, "0");
      const secs = String(elapsedSeconds % 60).padStart(2, "0");
      $("timer").textContent = `${mins}:${secs}`;
      $("dashboard-time").textContent = `${mins}:${secs}`;
    }

    function setGameState(state) {
      gameState = state;
      clearInterval(timerInterval);
      if (state === "playing") {
        timerInterval = setInterval(() => { elapsedSeconds++; updateTimer(); }, 1000);
        $("game-status").textContent = "GAME BERLANGSUNG";
        $("game-status").className = "rounded-full border border-green-300/30 bg-green-400/15 px-3 py-2 text-xs font-bold text-green-100";
      } else if (state === "paused") {
        $("game-status").textContent = "GAME DIJEDA";
        $("game-status").className = "rounded-full border border-yellow-300/30 bg-yellow-400/15 px-3 py-2 text-xs font-bold text-yellow-100";
      } else {
        $("game-status").textContent = "SIAP DIMULAI";
        $("game-status").className = "rounded-full border border-cyan-200/20 px-3 py-2 text-xs font-bold text-cyan-100";
      }
      $("dashboard-status").textContent = $("game-status").textContent;
    }

    function openQuestion(q) {
      if (q.locked || gameState !== "playing") return;
      currentQuestion = q;
      selectedAnswer = "";
      $("question-number").textContent = `SOAL ${String(q.id).padStart(2, "0")}`;
      $("answer-message").textContent = "";
      const choices = q.options.map((value, index) => ({ value, letter: String.fromCharCode(65 + index) }));
      const holder = $("answer-choices");
      holder.innerHTML = "";
      choices.forEach((choice, index) => {
        const button = document.createElement("button");
        button.type = "button";
        button.className = "choice-button min-h-[64px] rounded-xl border border-cyan-200/25 bg-slate-950/35 px-4 py-4 text-center text-lg font-bold text-white transition hover:-translate-y-1 hover:border-cyan-200 hover:bg-cyan-300/20 focus:outline-none focus:ring-2 focus:ring-cyan-200";
        button.setAttribute("role", "radio");
        button.setAttribute("aria-checked", "false");
        button.innerHTML = `<span class="mr-2 text-cyan-200">${choice.letter}.</span>${choice.value}`;
        button.addEventListener("click", () => {
          selectedAnswer = choice.letter;
          holder.querySelectorAll("button").forEach(item => { item.classList.remove("ring-2", "ring-cyan-300", "bg-cyan-300/25"); item.setAttribute("aria-checked", "false"); });
          button.classList.add("ring-2", "ring-cyan-300", "bg-cyan-300/25");
          button.setAttribute("aria-checked", "true");
          $("answer-message").textContent = "";
        });
        holder.appendChild(button);
      });
      $("question-modal").classList.remove("hidden-layer");
      setTimeout(() => $("answer-choices").querySelector("button")?.focus(), 80);
    }

    function closeQuestion() {
      $("question-modal").classList.add("hidden-layer");
      currentQuestion = null;
    }

    function showResult(correct, points = 0) {
      const card = $("result-card");
      $("result-symbol").textContent = correct ? "✓" : "✕";
      $("result-symbol").className = correct ? "success-ring text-8xl font-black text-green-400" : "wrong-shake text-8xl font-black text-red-400";
      $("result-title").textContent = correct ? "BENAR!" : "SALAH!";
      $("result-title").className = correct ? "mt-3 text-4xl font-extrabold text-green-200" : "mt-3 text-4xl font-extrabold text-red-200";
      $("result-detail").textContent = correct ? `+ ${points} POIN` : "Coba lagi, kamu pasti bisa!";
      card.classList.toggle("wrong-shake", !correct);
      $("result-overlay").classList.remove("hidden-layer");
      if (correct) createConfetti();
      setTimeout(() => {
        $("result-overlay").classList.add("hidden-layer");
        if (correct) {
          $("question-modal").classList.add("hidden-layer");
          showTeamChoices();
        } else {
          $("answer-choices").querySelector("button")?.focus();
        }
      }, correct ? 1450 : 1000);
    }

    function createConfetti() {
      const colors = ["#66d9ff", "#f5c542", "#ec4899", "#22c55e", "#ffffff"];
      for (let i = 0; i < 38; i++) {
        const bit = document.createElement("div");
        bit.className = "confetti";
        bit.style.left = `${42 + Math.random() * 16}%`;
        bit.style.top = `${20 + Math.random() * 14}%`;
        bit.style.background = colors[i % colors.length];
        bit.style.setProperty("--x", `${(Math.random() - .5) * 700}px`);
        document.body.appendChild(bit);
        setTimeout(() => bit.remove(), 1700);
      }
    }

    function showTeamChoices() {
      const choices = $("team-choices");
      choices.innerHTML = "";
      teams.forEach(team => {
        const button = document.createElement("button");
        button.type = "button";
        button.className = "team-choice rounded-2xl p-4 text-center font-extrabold text-white shadow-lg";
        button.style.background = team.color;
        button.textContent = team.name;
        button.addEventListener("click", () => awardTeam(team));
        choices.appendChild(button);
      });
      $("team-modal").classList.remove("hidden-layer");
    }

    function awardTeam(team) {
      if (!currentQuestion) return;
      currentQuestion.locked = true;
      currentQuestion.winner = team.id;
      team.score += Number(currentQuestion.points);
      $("team-modal").classList.add("hidden-layer");
      const scoreCard = $(`score-${team.id}`);
      renderQuestions();
      renderScores();
      setTimeout(() => {
        const freshCard = $(`score-${team.id}`);
        freshCard.classList.add("pop");
        setTimeout(() => freshCard.classList.remove("pop"), 420);
      }, 30);
      currentQuestion = null;
    }

    function renderBank() {
      const body = $("bank-body");
      body.innerHTML = "";
      questions.forEach(q => {
        const row = document.createElement("tr");
        row.className = "border-t border-cyan-100/10";
        row.innerHTML = `<td class="px-4 py-2 font-bold">${q.id}</td>
          ${q.options.map((option, index) => `<td class="px-2 py-2"><input aria-label="Pilihan ${String.fromCharCode(65 + index)} soal ${q.id}" data-option="${q.id}-${index}" class="input-arena w-20 rounded-lg px-3 py-2" value="${option}"></td>`).join("")}
          <td class="px-2 py-2"><select aria-label="Jawaban benar soal ${q.id}" data-correct="${q.id}" class="input-arena rounded-lg px-3 py-2">${["A","B","C","D","E"].map(letter => `<option ${q.correct === letter ? "selected" : ""}>${letter}</option>`).join("")}</select></td>
          <td class="px-2 py-2"><input aria-label="Poin soal ${q.id}" data-points="${q.id}" type="number" min="0" class="input-arena w-20 rounded-lg px-3 py-2" value="${q.points}"></td>
          <td class="px-4 py-2 text-xs font-bold ${q.locked ? "text-green-300" : "text-blue-100"}">${q.locked ? "TERKUNCI" : "TERBUKA"}</td>`;
        body.appendChild(row);
      });
    }

    function renderTeamSettings() {
      const holder = $("team-settings");
      holder.innerHTML = "";
      teams.forEach(team => {
        const item = document.createElement("label");
        item.className = "flex items-center gap-3 rounded-2xl border border-cyan-100/15 bg-slate-950/20 p-4";
        item.innerHTML = `<span class="h-5 w-5 rounded-full" style="background:${team.color}"></span><span class="w-20 text-sm font-bold">${team.name}</span><input aria-label="Nama kelompok ${team.name}" data-team-name="${team.id}" class="input-arena min-w-0 flex-1 rounded-lg px-3 py-2" value="${team.name}">`;
        holder.appendChild(item);
      });
    }

    function resetGame() {
      clearInterval(timerInterval);
      elapsedSeconds = 0;
      updateTimer();
      questions.forEach(q => { q.locked = false; q.winner = null; });
      teams.forEach(t => t.score = 0);
      setGameState("ready");
      renderQuestions();
      renderScores();
    }

    function showFinal() {
      const ranking = sortedTeams();
      const podium = $("podium");
      podium.innerHTML = "";
      const order = [ranking[1], ranking[0], ranking[2]];
      const labels = ["🥈 JUARA 2", "🏆 JUARA 1", "🥉 JUARA 3"];
      const heights = ["h-40", "h-56", "h-32"];
      order.forEach((team, index) => {
        const card = document.createElement("div");
        card.className = `podium-card flex w-[30%] max-w-[220px] flex-col justify-end rounded-t-3xl p-3 md:p-5 ${heights[index]}`;
        card.style.background = `linear-gradient(160deg, ${team.color}, ${team.color}a8)`;
        card.style.animationDelay = `${index * .15}s`;
        card.innerHTML = `<span class="text-sm font-extrabold md:text-base">${labels[index]}</span><strong class="mt-2 text-sm md:text-xl">${team.name}</strong><span class="mt-1 text-xs font-bold md:text-sm">${team.score} POIN</span>`;
        podium.appendChild(card);
      });
      const list = $("final-ranking");
      list.innerHTML = "";
      ranking.forEach((team, index) => {
        const row = document.createElement("div");
        row.className = "flex items-center gap-3 rounded-xl bg-white/5 px-4 py-3";
        row.innerHTML = `<span class="w-6 font-bold">${index + 1}</span><span class="h-3 w-3 rounded-full" style="background:${team.color}"></span><span class="flex-1 font-bold">${team.name}</span><strong>${team.score} poin</strong>`;
        list.appendChild(row);
      });
      $("gameover-screen").classList.remove("hidden-layer");
    }

    $("answer-form").addEventListener("submit", (event) => {
      event.preventDefault();
      if (!currentQuestion) return;
      if (!selectedAnswer) {
        $("answer-message").textContent = "Silakan pilih salah satu jawaban terlebih dahulu.";
        return;
      }
      const answer = selectedAnswer;
      if (answer === currentQuestion.correct) {
        showResult(true, currentQuestion.points);
      } else {
        $("answer-message").textContent = "Jawaban belum tepat. Silakan coba kembali.";
        showResult(false);
      }
    });

    $("start-btn").addEventListener("click", () => { if (gameState !== "playing") setGameState("playing"); });
    $("pause-btn").addEventListener("click", () => { if (gameState === "playing") setGameState("paused"); });
    $("close-question").addEventListener("click", closeQuestion);
    $("teacher-open").addEventListener("click", () => { renderBank(); renderTeamSettings(); $("teacher-modal").classList.remove("hidden-layer"); });
    $("teacher-close").addEventListener("click", () => $("teacher-modal").classList.add("hidden-layer"));
    $("gameover-btn").addEventListener("click", () => $("confirm-modal").classList.remove("hidden-layer"));
    $("panel-gameover").addEventListener("click", () => { $("teacher-modal").classList.add("hidden-layer"); $("confirm-modal").classList.remove("hidden-layer"); });
    $("cancel-end").addEventListener("click", () => $("confirm-modal").classList.add("hidden-layer"));
    $("confirm-end").addEventListener("click", () => { $("confirm-modal").classList.add("hidden-layer"); closeQuestion(); setGameState("ended"); showFinal(); });
    $("panel-start").addEventListener("click", () => setGameState("playing"));
    $("panel-pause").addEventListener("click", () => setGameState("paused"));
    $("panel-reset").addEventListener("click", resetGame);
    $("play-again").addEventListener("click", () => { $("gameover-screen").classList.add("hidden-layer"); resetGame(); });
    $("back-settings").addEventListener("click", () => { $("gameover-screen").classList.add("hidden-layer"); $("teacher-modal").classList.remove("hidden-layer"); });

    $("save-bank").addEventListener("click", () => {
      questions.forEach(q => {
        const pointInput = document.querySelector(`[data-points="${q.id}"]`);
        if (!q.locked) {
          q.options = q.options.map((option, index) => document.querySelector(`[data-option="${q.id}-${index}"]`).value.trim() || option);
          q.correct = document.querySelector(`[data-correct="${q.id}"]`).value;
          q.points = Math.max(0, Number(pointInput.value) || 0);
        }
      });
      $("bank-message").textContent = "Kunci jawaban dan poin berhasil disimpan untuk sesi permainan ini.";
      setTimeout(() => $("bank-message").textContent = "", 2600);
    });

    $("save-teams").addEventListener("click", () => {
      teams.forEach(team => {
        const input = document.querySelector(`[data-team-name="${team.id}"]`);
        team.name = input.value.trim().toUpperCase() || team.name;
      });
      renderQuestions();
      renderScores();
      renderTeamSettings();
    });

    $("save-class-info").addEventListener("click", () => {
      const className = $("class-name-input").value.trim();
      const teacherName = $("teacher-name-input").value.trim();
      if (className) $("class-name-display").textContent = className;
      if (teacherName) $("teacher-name-display").textContent = teacherName;
      $("class-info-message").textContent = "Identitas kelas berhasil disimpan.";
      setTimeout(() => $("class-info-message").textContent = "", 2600);
    });

    document.querySelectorAll(".tab-btn").forEach(button => {
      button.addEventListener("click", () => {
        document.querySelectorAll(".tab-btn").forEach(tab => tab.classList.remove("active"));
        document.querySelectorAll(".teacher-tab").forEach(tab => tab.classList.add("hidden"));
        button.classList.add("active");
        $(`tab-${button.dataset.tab}`).classList.remove("hidden");
        if (button.dataset.tab === "bank") renderBank();
        if (button.dataset.tab === "teams") renderTeamSettings();
      });
    });

    updateTimer();
    renderQuestions();
    renderScores();
    setGameState("ready");
    lucide.createIcons();
  </script>
 </body>
</html>

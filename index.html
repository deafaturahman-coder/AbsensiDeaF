<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Absensi Digital — SMK Pasundan Rancaekek</title>
<style>
  :root{
    --ink:#1c2a2e;
    --paper:#f6f3ea;
    --paper-raised:#ffffff;
    --line:#d8d0bd;
    --brass:#9c7a3c;
    --brass-deep:#7a5e2b;
    --pine:#2f4d43;
    --pine-deep:#213932;
    --hadir:#2f6b4f;
    --izin:#8a6d1f;
    --sakit:#8a4a1f;
    --alpa:#a13a3a;
    --hadir-bg:#e4efe6;
    --izin-bg:#f4ecd6;
    --sakit-bg:#f3e4d6;
    --alpa-bg:#f6dede;
    font-family:'Source Serif 4', Georgia, serif;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    background:
      radial-gradient(1200px 600px at 10% -10%, #fbf8ee 0%, transparent 60%),
      var(--paper);
    color:var(--ink);
    font-family: 'Iowan Old Style','Source Serif 4', Georgia, serif;
    min-height:100vh;
    padding:28px 16px 60px;
  }
  .sheet{
    max-width:980px;
    margin:0 auto;
    background:var(--paper-raised);
    border:1px solid var(--line);
    box-shadow:0 1px 0 rgba(0,0,0,0.03), 0 18px 40px -24px rgba(33,57,50,0.35);
    position:relative;
    overflow:hidden;
  }
  .sheet::before{
    content:"";
    position:absolute; top:0; left:0; right:0; height:6px;
    background:repeating-linear-gradient(90deg, var(--pine) 0 18px, var(--brass) 18px 22px);
    opacity:0.9;
  }
  header.masthead{
    padding:30px 34px 20px;
    border-bottom:2px solid var(--pine-deep);
    display:flex;
    align-items:flex-end;
    justify-content:space-between;
    gap:16px;
    flex-wrap:wrap;
  }
  .masthead .school{
    display:flex; align-items:center; gap:14px;
  }
  .crest{
    width:46px;height:46px;border-radius:50%;
    background:conic-gradient(from 210deg, var(--pine) 0 40%, var(--brass) 40% 100%);
    display:flex;align-items:center;justify-content:center;
    color:var(--paper);
    font-family:'Iowan Old Style', serif;
    font-weight:700;
    font-size:15px;
    flex-shrink:0;
    box-shadow: inset 0 0 0 3px rgba(255,255,255,0.15);
  }
  .school h1{
    font-size:20px;
    letter-spacing:0.02em;
    margin:0 0 2px;
    font-weight:700;
    color:var(--pine-deep);
  }
  .school p{
    margin:0;
    font-family: -apple-system, 'Helvetica Neue', Arial, sans-serif;
    font-size:11.5px;
    color:#6b6151;
    letter-spacing:0.03em;
  }
  .masthead .doc-title{
    text-align:right;
  }
  .doc-title .eyebrow{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:10.5px;
    letter-spacing:0.16em;
    text-transform:uppercase;
    color:var(--brass-deep);
    font-weight:600;
  }
  .doc-title h2{
    margin:2px 0 0;
    font-size:22px;
    color:var(--ink);
    font-weight:700;
  }

  nav.tabs{
    display:flex;
    gap:2px;
    padding:0 34px;
    background:var(--pine-deep);
  }
  nav.tabs button{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    background:transparent;
    border:none;
    color:#cfe0d8;
    padding:11px 18px;
    font-size:13px;
    letter-spacing:0.04em;
    cursor:pointer;
    border-bottom:3px solid transparent;
    transition:all .15s ease;
  }
  nav.tabs button:hover{ color:#fff; }
  nav.tabs button.active{
    color:#fff;
    border-bottom:3px solid var(--brass);
    font-weight:600;
  }

  main{ padding:26px 34px 34px; }

  .controls{
    display:grid;
    grid-template-columns:1fr 1fr 1fr;
    gap:16px;
    margin-bottom:22px;
  }
  @media (max-width:680px){ .controls{grid-template-columns:1fr;} }

  .field label{
    display:block;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:10.5px;
    letter-spacing:0.1em;
    text-transform:uppercase;
    color:var(--brass-deep);
    font-weight:600;
    margin-bottom:6px;
  }
  .field select, .field input[type=date]{
    width:100%;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:14.5px;
    padding:10px 12px;
    border:1px solid var(--line);
    background:var(--paper);
    color:var(--ink);
    border-radius:2px;
    appearance:none;
  }
  .field select:focus, .field input:focus{
    outline:2px solid var(--pine);
    outline-offset:1px;
  }

  .meta-row{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
    gap:10px;
    margin-bottom:14px;
    padding-bottom:14px;
    border-bottom:1px dashed var(--line);
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
  }
  .wali{ font-size:12.5px; color:#6b6151; }
  .wali b{ color:var(--ink); }

  .bulk-actions{
    display:flex; gap:8px; flex-wrap:wrap;
  }
  .btn{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:12px;
    padding:7px 13px;
    border-radius:20px;
    border:1px solid var(--line);
    background:var(--paper-raised);
    color:var(--ink);
    cursor:pointer;
    transition: all .12s ease;
  }
  .btn:hover{ border-color:var(--pine); color:var(--pine-deep); }
  .btn.primary{
    background:var(--pine-deep);
    color:#fff;
    border-color:var(--pine-deep);
    font-weight:600;
  }
  .btn.primary:hover{ background:var(--pine); }
  .btn.ghost{ background:transparent; }

  table.roster{
    width:100%;
    border-collapse:collapse;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
  }
  table.roster thead th{
    text-align:left;
    font-size:10.5px;
    letter-spacing:0.08em;
    text-transform:uppercase;
    color:#6b6151;
    font-weight:600;
    padding:8px 8px;
    border-bottom:2px solid var(--pine-deep);
  }
  table.roster tbody tr{
    border-bottom:1px solid #ece6d6;
  }
  table.roster tbody tr:hover{ background:#fbf8ee; }
  table.roster td{
    padding:8px 8px;
    font-size:14px;
    vertical-align:middle;
  }
  td.no{ color:#a89e88; width:30px; }
  td.jk{ color:#a89e88; width:30px; font-size:12px; }
  td.nama{ font-weight:500; }

  .status-group{
    display:flex; gap:5px;
  }
  .status-btn{
    width:34px; height:30px;
    border-radius:4px;
    border:1px solid var(--line);
    background:#fff;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:12px;
    font-weight:700;
    cursor:pointer;
    color:#9a9282;
    transition: all .1s ease;
  }
  .status-btn:hover{ transform:translateY(-1px); }
  .status-btn[data-code="H"].active{ background:var(--hadir-bg); border-color:var(--hadir); color:var(--hadir); }
  .status-btn[data-code="I"].active{ background:var(--izin-bg); border-color:var(--izin); color:var(--izin); }
  .status-btn[data-code="S"].active{ background:var(--sakit-bg); border-color:var(--sakit); color:var(--sakit); }
  .status-btn[data-code="A"].active{ background:var(--alpa-bg); border-color:var(--alpa); color:var(--alpa); }

  .footer-bar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
    gap:14px;
    margin-top:22px;
    padding-top:16px;
    border-top:1px dashed var(--line);
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
  }
  .summary{
    display:flex; gap:14px; flex-wrap:wrap;
    font-size:12.5px;
  }
  .summary span{ display:flex; align-items:center; gap:5px; }
  .dot{ width:8px;height:8px;border-radius:50%; display:inline-block; }
  .dot.H{background:var(--hadir);} .dot.I{background:var(--izin);}
  .dot.S{background:var(--sakit);} .dot.A{background:var(--alpa);}

  .save-status{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:11.5px;
    color:#6b6151;
    min-height:16px;
  }
  .save-status.ok{ color:var(--hadir); }

  /* Riwayat / Recap tab */
  .recap-controls{ display:flex; gap:16px; margin-bottom:18px; flex-wrap:wrap; }
  .recap-controls .field{ min-width:200px; flex:1; }

  table.recap{
    width:100%; border-collapse:collapse;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
  }
  table.recap thead th{
    text-align:center;
    font-size:11px; letter-spacing:0.06em; text-transform:uppercase;
    color:#6b6151; font-weight:600; padding:8px 6px;
    border-bottom:2px solid var(--pine-deep);
  }
  table.recap thead th:first-child, table.recap thead th:nth-child(2){ text-align:left; }
  table.recap tbody td{
    padding:7px 6px; font-size:13.5px; text-align:center;
    border-bottom:1px solid #ece6d6;
  }
  table.recap tbody td:first-child{ color:#a89e88; }
  table.recap tbody td:nth-child(2){ text-align:left; font-weight:500; }
  table.recap tfoot td{
    padding:9px 6px; font-size:12.5px; text-align:center;
    border-top:2px solid var(--pine-deep); font-weight:700; color:var(--pine-deep);
  }
  table.recap tfoot td:first-child, table.recap tfoot td:nth-child(2){ text-align:left; }

  .history-list{
    display:flex; flex-direction:column; gap:6px; margin-top:18px;
  }
  .history-item{
    display:flex; justify-content:space-between; align-items:center;
    padding:10px 14px; border:1px solid var(--line); border-radius:4px;
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif; font-size:13px;
    background:var(--paper);
  }
  .history-item .counts{ display:flex; gap:10px; font-size:12px; color:#6b6151; }
  .history-item button{
    font-family:inherit; font-size:11.5px; padding:5px 11px; border-radius:14px;
    border:1px solid var(--pine); background:transparent; color:var(--pine-deep); cursor:pointer;
  }
  .history-item button:hover{ background:var(--pine); color:#fff; }

  .empty-note{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:13px; color:#8a806e; padding:30px 10px; text-align:center;
  }

  .loading-note{
    font-family:-apple-system,'Helvetica Neue',Arial,sans-serif;
    font-size:12.5px; color:#8a806e; padding:10px 0;
  }
</style>
</head>
<body>
<div class="sheet">
  <header class="masthead">
    <div class="school">
      <div class="crest">BD</div>
      <div>
        <h1>SMK Pasundan Rancaekek</h1>
        <p>Bisnis Digital · Tahun Pelajaran 2025/2026</p>
      </div>
    </div>
    <div class="doc-title">
      <div class="eyebrow">Buku Kehadiran</div>
      <h2>Absensi Digital</h2>
    </div>
  </header>

  <nav class="tabs">
    <button class="active" data-tab="absen">Isi Absensi</button>
    <button data-tab="rekap">Rekap Kehadiran</button>
    <button data-tab="riwayat">Riwayat</button>
  </nav>

  <main>
    <!-- ABSEN TAB -->
    <section id="tab-absen">
      <div class="controls">
        <div class="field">
          <label for="sel-kelas">Kelas</label>
          <select id="sel-kelas">
            <option value="XI BDG 1">XI BDG 1</option>
            <option value="XI BDG 2">XI BDG 2</option>
          </select>
        </div>
        <div class="field">
          <label for="sel-mapel">Mata Pelajaran</label>
          <select id="sel-mapel">
            <option value="Digital Marketing">Digital Marketing</option>
            <option value="Marketing">Marketing</option>
            <option value="Komunikasi Bisnis">Komunikasi Bisnis</option>
          </select>
        </div>
        <div class="field">
          <label for="sel-tanggal">Tanggal</label>
          <input type="date" id="sel-tanggal">
        </div>
      </div>

      <div class="meta-row">
        <div class="wali">Wali Kelas: <b id="wali-nama">—</b></div>
        <div class="bulk-actions">
          <button class="btn" id="btn-all-hadir">Tandai semua Hadir</button>
          <button class="btn ghost" id="btn-reset">Kosongkan</button>
        </div>
      </div>

      <div id="loading-absen" class="loading-note" style="display:none;">Memuat data…</div>
      <table class="roster" id="roster-table">
        <thead>
          <tr><th class="no">No</th><th>Nama</th><th class="jk">JK</th><th>Status</th></tr>
        </thead>
        <tbody id="roster-body"></tbody>
      </table>

      <div class="footer-bar">
        <div class="summary" id="summary-counts"></div>
        <div style="display:flex; align-items:center; gap:12px;">
          <span class="save-status" id="save-status"></span>
          <button class="btn primary" id="btn-simpan">Simpan Absensi</button>
        </div>
      </div>
    </section>

    <!-- REKAP TAB -->
    <section id="tab-rekap" style="display:none;">
      <div class="recap-controls">
        <div class="field">
          <label for="rekap-kelas">Kelas</label>
          <select id="rekap-kelas">
            <option value="XI BDG 1">XI BDG 1</option>
            <option value="XI BDG 2">XI BDG 2</option>
          </select>
        </div>
        <div class="field">
          <label for="rekap-mapel">Mata Pelajaran</label>
          <select id="rekap-mapel">
            <option value="Digital Marketing">Digital Marketing</option>
            <option value="Marketing">Marketing</option>
            <option value="Komunikasi Bisnis">Komunikasi Bisnis</option>
          </select>
        </div>
      </div>
      <div id="rekap-content"></div>
    </section>

    <!-- RIWAYAT TAB -->
    <section id="tab-riwayat" style="display:none;">
      <div class="recap-controls">
        <div class="field">
          <label for="riwayat-kelas">Kelas</label>
          <select id="riwayat-kelas">
            <option value="XI BDG 1">XI BDG 1</option>
            <option value="XI BDG 2">XI BDG 2</option>
          </select>
        </div>
        <div class="field">
          <label for="riwayat-mapel">Mata Pelajaran</label>
          <select id="riwayat-mapel">
            <option value="Digital Marketing">Digital Marketing</option>
            <option value="Marketing">Marketing</option>
            <option value="Komunikasi Bisnis">Komunikasi Bisnis</option>
          </select>
        </div>
      </div>
      <div id="riwayat-content"></div>
    </section>
  </main>
</div>

<script>
// ---------- Data siswa (dari Absensi_Kelas_XI_BDGG.xlsx) ----------
const ROSTER = {
  "XI BDG 1": {
    wali: "Wildan Nur Mu'min, S.M.",
    siswa: [
      "A. Rifki|L","Akbar Ibnu Suli|L","Alivia Nurul Hidayah|P","Alyaa Jahra Raasyidah|P",
      "Andini Gita Satriani|P","Andre Firmansyah|L","Anzani Nurmayati K|P","Azmi Annisa Hafdi|P",
      "Calya Siti Umamah|P","Chelsea Alif Putra Zulfikar|L","Citra Aisyah Lestari|P","Dani Firmansyah|L",
      "Delita Putri Hermawan|P","Devia Christin Novisyah|P","Diandry Mahendra C|L","Dina|P",
      "Dzafia Nurul Azhar|P","Ersa Novianty|P","Fita Hardayanti|P","Hadiansyah Putra|L",
      "Intan Cahyanti|P","Kheila Nur Ramadhani|P","Laela Nur Khodijah|P","Lulu Adiyanti|P",
      "Nanda Roudia Kasih|P","Nayshilla Alifah R|P","Nazwa Humaera|P","Nehemia Steven Surbakti|L",
      "Nida Nurjannah|P","Nisha Ramadhani|P","Noura Nouf|P","Novia Mega Juliani|P",
      "Resa Viona Eka Putri|P","Reysa Safitri|P","Reza Rizkia|L","Ridwan Abdul Aman|L",
      "Salsa Trisyananda|P","Silvia Septiani|P","Sintya Nuraini|P","Siti Padilah Nur Ajijah|P",
      "Tasya Nur Amelia|P","Tiara KM|P","Wili Aulia|L","Willya Iren Juana|P",
      "Windi Wulandari|P","Zaelani Sidik Putra Raihan|L","Zahra Choirunisa|P","Zanet Ratu Novarina|P",
      "Zianka Septia Ramadhani|P","Zulfi Alis Almahira|P"
    ]
  },
  "XI BDG 2": {
    wali: "Maulani Budi Sari, S.Pd.",
    siswa: [
      "Agnisya Alniawati|P","Alwin|L","Anggri Nuraeni|P","Annisa Drisna Novianti|P",
      "Apni Aditia Pratiwi|P","Arinda Irgi Vemillian|P","Ayu Nayra Azahra|P","Ayu Riyanti|P",
      "Dena Muhamad Rafa|L","Dio Alief Putra Pratama|L","Farras Aribi Benarli|L","Firman Sidik|L",
      "Ikpal Fathurrahman|L","Layla Ramadina|P","Levana Frederika Erlen|P","M. Refandi Alhabsyie|L",
      "Marlina Julianti|P","Meisyah As Safar|P","Muhamad Ikhsan|L","Nadhif Erland A|L",
      "Nanda Alya Putri|P","Natasya Azahra|P","Nazril Adira Wildan|L","Nazwa Rasyfa Azzahra|P",
      "Nisa Amelia|P","Pahrizal Riskiyana|L","Puteri Tsaniya Faza|P","R. Ginna Fatihah|P",
      "Rasya Alfiana Putra|L","Rasya Nabila Nandagia|P","Refani Mulandari|P","Riane Nurmalla|P",
      "Rizki Aura Amanda|P","Sania Nurfadilah|P","Saskia Dupijasika|P","Shafana Zivilia M|P",
      "Shidqii Hansam Pranata|L","Silva Nuraeni|P","Siti Munawaroh|P","Sri Rahayu|P",
      "Syahria Ayu Angdiani|P","Syahla K R|P","Syarif Fadhil A|L","Syifa Maulida|P",
      "Tasya Regina Putri|P","Tiara Najla Muspirah|P","Tri Cahyani|P","Vitra Tri Setia|L",
      "Wilda Oktavia|P","Wulan Sucianti|P"
    ]
  }
};
const STATUS_CODES = ["H","I","S","A"];
const STATUS_LABEL = {H:"Hadir", I:"Izin", S:"Sakit", A:"Alpa"};

function todayStr(){
  const d = new Date();
  return d.toISOString().slice(0,10);
}
function keyFor(kelas, mapel, tanggal){
  return `att:${kelas}::${mapel}::${tanggal}`;
}
function prefixFor(kelas, mapel){
  return `att:${kelas}::${mapel}::`;
}

// ---------- Tabs ----------
const tabButtons = document.querySelectorAll('nav.tabs button');
const tabSections = { absen: document.getElementById('tab-absen'), rekap: document.getElementById('tab-rekap'), riwayat: document.getElementById('tab-riwayat') };
tabButtons.forEach(btn=>{
  btn.addEventListener('click', ()=>{
    tabButtons.forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    Object.values(tabSections).forEach(s=>s.style.display='none');
    tabSections[btn.dataset.tab].style.display='block';
    if(btn.dataset.tab === 'rekap') renderRekap();
    if(btn.dataset.tab === 'riwayat') renderRiwayat();
  });
});

// ---------- Absen tab ----------
const selKelas = document.getElementById('sel-kelas');
const selMapel = document.getElementById('sel-mapel');
const selTanggal = document.getElementById('sel-tanggal');
const rosterBody = document.getElementById('roster-body');
const waliNama = document.getElementById('wali-nama');
const summaryEl = document.getElementById('summary-counts');
const saveStatusEl = document.getElementById('save-status');
const loadingAbsenEl = document.getElementById('loading-absen');

selTanggal.value = todayStr();

let currentStatus = {}; // idx -> code

function buildRoster(){
  const kelas = selKelas.value;
  waliNama.textContent = ROSTER[kelas].wali;
  rosterBody.innerHTML = '';
  ROSTER[kelas].siswa.forEach((entry, idx)=>{
    const [nama, jk] = entry.split('|');
    const tr = document.createElement('tr');
    tr.innerHTML = `
      <td class="no">${idx+1}</td>
      <td class="nama">${nama}</td>
      <td class="jk">${jk}</td>
      <td><div class="status-group" data-idx="${idx}">
        ${STATUS_CODES.map(c=>`<button type="button" class="status-btn" data-code="${c}">${c}</button>`).join('')}
      </div></td>
    `;
    rosterBody.appendChild(tr);
  });
  // attach handlers
  rosterBody.querySelectorAll('.status-group').forEach(group=>{
    const idx = group.dataset.idx;
    group.querySelectorAll('.status-btn').forEach(btn=>{
      btn.addEventListener('click', ()=>{
        currentStatus[idx] = btn.dataset.code;
        refreshStatusButtons();
        updateSummary();
        saveStatusEl.textContent = '';
        saveStatusEl.classList.remove('ok');
      });
    });
  });
}

function refreshStatusButtons(){
  rosterBody.querySelectorAll('.status-group').forEach(group=>{
    const idx = group.dataset.idx;
    const active = currentStatus[idx];
    group.querySelectorAll('.status-btn').forEach(btn=>{
      btn.classList.toggle('active', btn.dataset.code === active);
    });
  });
}

function updateSummary(){
  const counts = {H:0,I:0,S:0,A:0};
  const total = ROSTER[selKelas.value].siswa.length;
  Object.values(currentStatus).forEach(c=>{ if(counts[c]!==undefined) counts[c]++; });
  const belum = total - Object.keys(currentStatus).length;
  summaryEl.innerHTML = `
    <span><span class="dot H"></span>Hadir ${counts.H}</span>
    <span><span class="dot I"></span>Izin ${counts.I}</span>
    <span><span class="dot S"></span>Sakit ${counts.S}</span>
    <span><span class="dot A"></span>Alpa ${counts.A}</span>
    <span style="color:#a89e88;">Belum diisi ${belum}</span>
  `;
}

async function loadAbsen(){
  loadingAbsenEl.style.display = 'block';
  currentStatus = {};
  const k = keyFor(selKelas.value, selMapel.value, selTanggal.value);
  try{
    const res = await window.storage.get(k, false);
    if(res && res.value){
      const data = JSON.parse(res.value);
      currentStatus = data.status || {};
    }
  }catch(e){
    // key not found -> empty
  }
  buildRoster();
  refreshStatusButtons();
  updateSummary();
  loadingAbsenEl.style.display = 'none';
}

document.getElementById('btn-all-hadir').addEventListener('click', ()=>{
  ROSTER[selKelas.value].siswa.forEach((_, idx)=>{ currentStatus[idx] = 'H'; });
  refreshStatusButtons();
  updateSummary();
});
document.getElementById('btn-reset').addEventListener('click', ()=>{
  currentStatus = {};
  refreshStatusButtons();
  updateSummary();
});

document.getElementById('btn-simpan').addEventListener('click', async ()=>{
  const k = keyFor(selKelas.value, selMapel.value, selTanggal.value);
  const payload = {
    kelas: selKelas.value,
    mapel: selMapel.value,
    tanggal: selTanggal.value,
    status: currentStatus
  };
  try{
    const result = await window.storage.set(k, JSON.stringify(payload), false);
    if(result){
      saveStatusEl.textContent = 'Tersimpan ✓';
      saveStatusEl.classList.add('ok');
    }else{
      saveStatusEl.textContent = 'Gagal menyimpan, coba lagi.';
      saveStatusEl.classList.remove('ok');
    }
  }catch(e){
    saveStatusEl.textContent = 'Gagal menyimpan, coba lagi.';
    saveStatusEl.classList.remove('ok');
  }
});

selKelas.addEventListener('change', loadAbsen);
selMapel.addEventListener('change', loadAbsen);
selTanggal.addEventListener('change', loadAbsen);

// ---------- Rekap tab ----------
const rekapKelas = document.getElementById('rekap-kelas');
const rekapMapel = document.getElementById('rekap-mapel');
const rekapContent = document.getElementById('rekap-content');

rekapKelas.addEventListener('change', renderRekap);
rekapMapel.addEventListener('change', renderRekap);

async function fetchAllRecords(kelas, mapel){
  const prefix = prefixFor(kelas, mapel);
  let keys = [];
  try{
    const listRes = await window.storage.list(prefix, false);
    keys = (listRes && listRes.keys) ? listRes.keys : [];
  }catch(e){ keys = []; }
  const records = [];
  for(const k of keys){
    try{
      const r = await window.storage.get(k, false);
      if(r && r.value) records.push(JSON.parse(r.value));
    }catch(e){ /* skip */ }
  }
  records.sort((a,b)=> a.tanggal.localeCompare(b.tanggal));
  return records;
}

async function renderRekap(){
  const kelas = rekapKelas.value;
  const mapel = rekapMapel.value;
  rekapContent.innerHTML = '<div class="loading-note">Memuat rekap…</div>';
  const records = await fetchAllRecords(kelas, mapel);
  if(records.length === 0){
    rekapContent.innerHTML = '<div class="empty-note">Belum ada data absensi untuk kelas dan mapel ini.</div>';
    return;
  }
  const siswa = ROSTER[kelas].siswa;
  const perSiswa = siswa.map(()=>({H:0,I:0,S:0,A:0}));
  records.forEach(rec=>{
    Object.entries(rec.status || {}).forEach(([idx, code])=>{
      if(perSiswa[idx] && perSiswa[idx][code] !== undefined) perSiswa[idx][code]++;
    });
  });
  const totalCounts = {H:0,I:0,S:0,A:0};
  perSiswa.forEach(c=>{ STATUS_CODES.forEach(code=>{ totalCounts[code]+=c[code]; }); });

  let html = `<p class="loading-note">${records.length} pertemuan tercatat · ${records[0].tanggal} s/d ${records[records.length-1].tanggal}</p>`;
  html += `<table class="recap"><thead><tr><th>No</th><th>Nama</th><th>H</th><th>I</th><th>S</th><th>A</th></tr></thead><tbody>`;
  siswa.forEach((entry, idx)=>{
    const [nama] = entry.split('|');
    const c = perSiswa[idx];
    html += `<tr><td>${idx+1}</td><td>${nama}</td><td>${c.H}</td><td>${c.I}</td><td>${c.S}</td><td>${c.A}</td></tr>`;
  });
  html += `</tbody><tfoot><tr><td colspan="2">Total</td><td>${totalCounts.H}</td><td>${totalCounts.I}</td><td>${totalCounts.S}</td><td>${totalCounts.A}</td></tr></tfoot></table>`;
  rekapContent.innerHTML = html;
}

// ---------- Riwayat tab ----------
const riwayatKelas = document.getElementById('riwayat-kelas');
const riwayatMapel = document.getElementById('riwayat-mapel');
const riwayatContent = document.getElementById('riwayat-content');

riwayatKelas.addEventListener('change', renderRiwayat);
riwayatMapel.addEventListener('change', renderRiwayat);

async function renderRiwayat(){
  const kelas = riwayatKelas.value;
  const mapel = riwayatMapel.value;
  riwayatContent.innerHTML = '<div class="loading-note">Memuat riwayat…</div>';
  const records = await fetchAllRecords(kelas, mapel);
  if(records.length === 0){
    riwayatContent.innerHTML = '<div class="empty-note">Belum ada riwayat absensi untuk kelas dan mapel ini.</div>';
    return;
  }
  records.sort((a,b)=> b.tanggal.localeCompare(a.tanggal));
  let html = '<div class="history-list">';
  records.forEach(rec=>{
    const counts = {H:0,I:0,S:0,A:0};
    Object.values(rec.status||{}).forEach(c=>{ if(counts[c]!==undefined) counts[c]++; });
    html += `<div class="history-item">
      <span><b>${rec.tanggal}</b></span>
      <span class="counts">
        <span>H ${counts.H}</span><span>I ${counts.I}</span><span>S ${counts.S}</span><span>A ${counts.A}</span>
      </span>
      <button data-date="${rec.tanggal}">Buka</button>
    </div>`;
  });
  html += '</div>';
  riwayatContent.innerHTML = html;
  riwayatContent.querySelectorAll('button[data-date]').forEach(btn=>{
    btn.addEventListener('click', ()=>{
      selKelas.value = kelas;
      selMapel.value = mapel;
      selTanggal.value = btn.dataset.date;
      tabButtons.forEach(b=>b.classList.remove('active'));
      document.querySelector('nav.tabs button[data-tab="absen"]').classList.add('active');
      Object.values(tabSections).forEach(s=>s.style.display='none');
      tabSections.absen.style.display='block';
      loadAbsen();
    });
  });
}

// ---------- Init ----------
loadAbsen();
</script>
</body>
</html>

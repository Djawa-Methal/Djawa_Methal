<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Djawa Methal – Sistem Manajemen</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');

  :root {
    --kuning:   #E53935;
    --coklat:   #B71C1C;
    --krem:     #FFF8E7;
    --putih:    #FFFFFF;
    --abu:      #6B6B6B;
    --abu-muda: #F5EEEE;
    --merah:    #C62828;
    --hijau:    #2A9D5C;
    --biru:     #2563EB;
    --border:   #EDCFCF;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Plus Jakarta Sans', sans-serif;
    background: var(--krem);
    color: #2D1010;
    min-height: 100vh;
  }

  /* ── HEADER ── */
  header {
    background: #E53935;
    padding: 0 24px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 60px;
    position: sticky;
    top: 0;
    z-index: 100;
  }

  .logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: 800;
    font-size: 18px;
    color: #fff;
    letter-spacing: -0.3px;
  }

  .logo span { color: rgba(255,255,255,.7); font-weight: 400; font-size: 14px; }

  nav { display: flex; gap: 4px; }

  nav button {
    background: transparent;
    border: none;
    color: #aaa;
    font-family: inherit;
    font-size: 13px;
    font-weight: 600;
    padding: 6px 16px;
    border-radius: 6px;
    cursor: pointer;
    transition: background .15s, color .15s;
  }

  nav button.active {
    background: #fff;
    color: var(--coklat);
  }

  /* ── LAYOUT ── */
  main { max-width: 960px; margin: 0 auto; padding: 28px 20px; }

  .page { display: none; }
  .page.active { display: block; }

  /* ── CARDS ── */
  .card {
    background: var(--putih);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 22px 24px;
    margin-bottom: 20px;
  }

  .card-title {
    font-size: 13px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: .8px;
    color: var(--abu);
    margin-bottom: 16px;
  }

  /* ── FORM ── */
  label {
    display: block;
    font-size: 13px;
    font-weight: 600;
    margin-bottom: 5px;
    color: var(--coklat);
  }

  input[type="text"], input[type="number"], select {
    width: 100%;
    padding: 10px 13px;
    border: 1.5px solid var(--border);
    border-radius: 8px;
    font-family: inherit;
    font-size: 14px;
    color: var(--coklat);
    background: var(--krem);
    margin-bottom: 14px;
    transition: border-color .15s;
    outline: none;
  }

  input:focus, select:focus { border-color: #E53935; }

  .row-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
  .row-3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 14px; }

  /* ── BUTTONS ── */
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    padding: 10px 20px;
    border-radius: 8px;
    font-family: inherit;
    font-size: 14px;
    font-weight: 700;
    cursor: pointer;
    border: none;
    transition: opacity .15s, transform .1s;
  }

  .btn:active { transform: scale(.97); }
  .btn-primary { background: var(--kuning); color: #fff; }
  .btn-danger  { background: var(--merah);  color: #fff; }
  .btn-ghost   { background: var(--abu-muda); color: var(--coklat); }

  .btn-full { width: 100%; justify-content: center; }

  /* ── MENU KASIR (3 cards) ── */
  .menu-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 12px; margin-bottom: 16px; }

  .menu-item {
    border: 2px solid var(--border);
    border-radius: 12px;
    padding: 16px;
    text-align: center;
    cursor: pointer;
    transition: border-color .15s, background .15s;
    background: var(--krem);
  }

  .menu-item:hover { border-color: var(--kuning); }
  .menu-item.selected { border-color: var(--kuning); background: #FDECEA; }

  .menu-item .icon { font-size: 30px; margin-bottom: 6px; }
  .menu-item .nama { font-weight: 700; font-size: 14px; }
  .menu-item .harga { font-size: 13px; color: var(--abu); margin-top: 2px; }

  /* ── KERANJANG ── */
  .keranjang-item {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 0;
    border-bottom: 1px solid var(--border);
    font-size: 14px;
  }

  .keranjang-item:last-child { border-bottom: none; }

  .keranjang-nama { font-weight: 600; }
  .keranjang-detail { color: var(--abu); font-size: 12px; margin-top: 2px; }

  .qty-ctrl {
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .qty-btn {
    width: 28px; height: 28px;
    border: 1.5px solid var(--border);
    border-radius: 6px;
    background: var(--krem);
    font-size: 16px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    color: var(--coklat);
  }

  .qty-num {
    font-family: 'DM Mono', monospace;
    font-weight: 500;
    width: 24px;
    text-align: center;
  }

  .keranjang-subtotal {
    font-family: 'DM Mono', monospace;
    font-weight: 500;
    font-size: 14px;
    min-width: 80px;
    text-align: right;
  }

  /* ── TOTAL BOX ── */
  .total-box {
    background: #E53935;
    border-radius: 12px;
    padding: 20px;
    color: #fff;
  }

  .total-row {
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    margin-bottom: 8px;
  }

  .total-row.big {
    font-size: 20px;
    font-weight: 800;
    margin-top: 12px;
    padding-top: 12px;
    border-top: 1px solid rgba(255,255,255,.2);
  }

  .badge-diskon {
    background: #fff;
    color: var(--kuning);
    font-size: 11px;
    font-weight: 700;
    padding: 2px 8px;
    border-radius: 99px;
  }

  /* ── STRUK ── */
  .struk {
    font-family: 'DM Mono', monospace;
    font-size: 13px;
    background: #fafafa;
    border: 1px dashed #bbb;
    border-radius: 10px;
    padding: 20px;
    white-space: pre;
    line-height: 1.7;
    margin-bottom: 16px;
  }

  /* ── LAPORAN TABLE ── */
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 14px;
  }

  th {
    text-align: left;
    padding: 9px 12px;
    background: #E53935;
    color: #fff;
    font-size: 12px;
    font-weight: 600;
  }

  th:first-child { border-radius: 8px 0 0 0; }
  th:last-child  { border-radius: 0 8px 0 0; }

  td {
    padding: 10px 12px;
    border-bottom: 1px solid var(--border);
    vertical-align: middle;
  }

  tr:last-child td { border-bottom: none; }
  tr:nth-child(even) td { background: var(--krem); }

  .badge {
    display: inline-block;
    padding: 2px 10px;
    border-radius: 99px;
    font-size: 11px;
    font-weight: 700;
  }

  .badge-laba  { background: #d1fae5; color: #065f46; }
  .badge-rugi  { background: #fee2e2; color: #991b1b; }
  .badge-impas { background: #fef3c7; color: #92400e; }

  /* ── STAT CARDS ── */
  .stats { display: grid; grid-template-columns: repeat(3,1fr); gap: 12px; margin-bottom: 20px; }

  .stat {
    background: var(--putih);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 16px;
  }

  .stat-label { font-size: 12px; color: var(--abu); font-weight: 600; margin-bottom: 4px; }
  .stat-value { font-size: 22px; font-weight: 800; color: var(--coklat); font-family: 'DM Mono', monospace; }
  .stat-sub   { font-size: 12px; color: var(--abu); margin-top: 2px; }

  /* ── MODAL ── */
  .modal-overlay {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,.45);
    z-index: 200;
    align-items: center;
    justify-content: center;
  }

  .modal-overlay.open { display: flex; }

  .modal {
    background: var(--putih);
    border-radius: 16px;
    padding: 28px;
    width: 100%;
    max-width: 420px;
    margin: 20px;
  }

  .modal h3 { font-size: 18px; margin-bottom: 16px; }

  /* ── EMPTY ── */
  .empty { text-align: center; padding: 40px 20px; color: var(--abu); }
  .empty .emoji { font-size: 40px; margin-bottom: 10px; }

  /* ── TOAST ── */
  #toast {
    position: fixed;
    bottom: 24px; right: 24px;
    background: var(--coklat);
    color: #fff;
    padding: 12px 20px;
    border-radius: 10px;
    font-size: 14px;
    font-weight: 600;
    opacity: 0;
    transform: translateY(10px);
    transition: opacity .2s, transform .2s;
    z-index: 999;
  }

  #toast.show { opacity: 1; transform: translateY(0); }

  @media (max-width: 600px) {
    .row-2, .row-3, .stats { grid-template-columns: 1fr; }
    .menu-grid { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>

<header>
  <div class="logo">🍽️ Djawa Methal <span>/ Manajemen UMKM</span></div>
  <nav>
    <button class="active" onclick="switchPage('kasir', this)">🛒 Kasir</button>
    <button onclick="switchPage('laporan', this)">📊 Laba Rugi</button>
  </nav>
</header>

<main>

  <!-- ══════════════════════════════════
       HALAMAN KASIR
  ══════════════════════════════════ -->
  <div id="page-kasir" class="page active">

    <div class="card">
      <div class="card-title">Pilih Menu</div>
      <div class="menu-grid">
        <div class="menu-item" onclick="pilihMenu(0)">
          <div class="icon">🧆</div>
          <div class="nama">Tahu Kocek</div>
          <div class="harga">Rp 8.000</div>
        </div>
        <div class="menu-item" onclick="pilihMenu(1)">
          <div class="icon">🧀</div>
          <div class="nama">Cireng Keju</div>
          <div class="harga">Rp 10.000</div>
        </div>
        <div class="menu-item" onclick="pilihMenu(2)">
          <div class="icon">🥤</div>
          <div class="nama">Es Kuwut</div>
          <div class="harga">Rp 8.000</div>
        </div>
      </div>

      <div style="display:flex; gap:10px; align-items:flex-end;">
        <div style="flex:1">
          <label>Jumlah Pesanan</label>
          <input type="number" id="inputJumlah" min="1" value="1" placeholder="1">
        </div>
        <button class="btn btn-primary" onclick="tambahKeranjang()" style="margin-bottom:14px">
          + Tambah
        </button>
      </div>
    </div>

    <div class="card">
      <div class="card-title">Keranjang</div>
      <div id="keranjangList">
        <div class="empty"><div class="emoji">🛒</div><div>Belum ada pesanan</div></div>
      </div>
    </div>

    <div class="total-box" id="totalBox" style="display:none; margin-bottom:20px">
      <div class="total-row"><span>Subtotal</span><span id="txtSubtotal">Rp 0</span></div>
      <div class="total-row" id="rowDiskon" style="display:none">
        <span>Diskon <span class="badge-diskon" id="txtBadgeDiskon"></span></span>
        <span id="txtDiskon" style="color:var(--kuning)"></span>
      </div>
      <div class="total-row big"><span>Total Bayar</span><span id="txtTotal">Rp 0</span></div>
    </div>

    <button class="btn btn-primary btn-full" onclick="bukaBayar()" id="btnBayar" style="display:none; margin-bottom:12px">
      💳 Bayar Sekarang
    </button>
    <button class="btn btn-ghost btn-full" onclick="resetKeranjang()" id="btnReset" style="display:none">
      🗑️ Kosongkan
    </button>

    <!-- Riwayat Kasir -->
    <div class="card" style="margin-top:24px">
      <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:16px">
        <div class="card-title" style="margin:0">Riwayat Transaksi</div>
        <button class="btn btn-ghost" style="padding:6px 12px; font-size:12px" onclick="hapusRiwayatKasir()">Hapus Semua</button>
      </div>
      <div id="riwayatKasir">
        <div class="empty"><div class="emoji">📋</div><div>Belum ada transaksi</div></div>
      </div>
    </div>
  </div>

  <!-- ══════════════════════════════════
       HALAMAN LAPORAN KEUANGAN
  ══════════════════════════════════ -->
  <div id="page-laporan" class="page">

    <!-- FORM INPUT -->
    <div class="card">
      <div class="card-title">Input Transaksi Baru</div>

      <label>Nama Produk</label>
      <input type="text" id="lNama" placeholder="cth: Tahu Kocek">

      <div class="row-2">
        <div>
          <label>Harga Jual / unit (Rp)</label>
          <input type="number" id="lHarga" min="0" placeholder="0">
        </div>
        <div>
          <label>Jumlah Terjual</label>
          <input type="number" id="lJumlah" min="0" placeholder="0">
        </div>
      </div>

      <div>
        <label>Modal / unit (HPP) (Rp)</label>
        <input type="number" id="lModal" min="0" placeholder="0">
      </div>

      <div style="margin-bottom:6px; font-size:13px; font-weight:700; color:var(--abu)">Beban Operasional</div>
      <div class="row-3">
        <div>
          <label>Listrik (Rp)</label>
          <input type="number" id="lListrik" min="0" placeholder="0">
        </div>
        <div>
          <label>Gaji (Rp)</label>
          <input type="number" id="lGaji" min="0" placeholder="0">
        </div>
        <div>
          <label>Lain-lain (Rp)</label>
          <input type="number" id="lLain" min="0" placeholder="0">
        </div>
      </div>

      <button class="btn btn-primary btn-full" onclick="tambahLaporan()">
        ➕ Tambah & Hitung
      </button>
    </div>

    <!-- STAT CARDS -->
    <div class="stats" id="statsBox" style="display:none">
      <div class="stat">
        <div class="stat-label">Total Transaksi</div>
        <div class="stat-value" id="sTx">0</div>
      </div>
      <div class="stat">
        <div class="stat-label">Total Laba Bersih</div>
        <div class="stat-value" id="sLaba" style="font-size:16px">Rp 0</div>
      </div>
      <div class="stat">
        <div class="stat-label">Rata-rata Margin</div>
        <div class="stat-value" id="sMargin">0%</div>
        <div class="stat-sub" id="sBestProduk"></div>
      </div>
    </div>

    <!-- TABLE -->
    <div class="card">
      <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:16px">
        <div class="card-title" style="margin:0">Laporan Keuangan</div>
        <button class="btn btn-ghost" style="padding:6px 12px; font-size:12px" onclick="hapusLaporan()">Hapus Semua</button>
      </div>
      <div id="laporanTable">
        <div class="empty"><div class="emoji">📊</div><div>Belum ada data laporan</div></div>
      </div>
    </div>
  </div>

</main>

<!-- ══ MODAL BAYAR ══ -->
<div class="modal-overlay" id="modalBayar">
  <div class="modal">
    <h3>💳 Pembayaran</h3>
    <div id="struklMini" style="margin-bottom:16px"></div>
    <label>Uang Diterima (Rp)</label>
    <input type="number" id="inputUang" min="0" placeholder="Masukkan nominal uang">
    <div id="kembalianBox" style="display:none; margin-bottom:14px">
      <div style="background:var(--krem); border-radius:8px; padding:12px; font-size:14px">
        Kembalian: <strong id="txtKembalian" style="font-family:'DM Mono',monospace"></strong>
      </div>
    </div>
    <div style="display:flex; gap:10px">
      <button class="btn btn-ghost" style="flex:1" onclick="tutupModal()">Batal</button>
      <button class="btn btn-primary" style="flex:1" onclick="prosesKasir()">✓ Selesai</button>
    </div>
  </div>
</div>

<!-- ══ MODAL STRUK ══ -->
<div class="modal-overlay" id="modalStruk">
  <div class="modal">
    <h3>🧾 Struk Transaksi</h3>
    <div class="struk" id="struklFull"></div>
    <div style="display:flex; gap:10px">
      <button class="btn btn-ghost" style="flex:1" onclick="document.getElementById('modalStruk').classList.remove('open')">Tutup</button>
      <button class="btn btn-primary" style="flex:1" onclick="printStruk()">🖨️ Print</button>
    </div>
  </div>
</div>

<!-- ══ TOAST ══ -->
<div id="toast"></div>

<script>
// ════════════════════════════════════════════════
// UTILITY
// ════════════════════════════════════════════════
const rp = n => 'Rp ' + Number(n).toLocaleString('id-ID');

function toast(msg, dur=2200) {
  const el = document.getElementById('toast');
  el.textContent = msg;
  el.classList.add('show');
  setTimeout(() => el.classList.remove('show'), dur);
}

function switchPage(id, btn) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('nav button').forEach(b => b.classList.remove('active'));
  document.getElementById('page-' + id).classList.add('active');
  btn.classList.add('active');
}

// ════════════════════════════════════════════════
// DATA (localStorage)
// ════════════════════════════════════════════════
const MENU = [
  { nama: 'Tahu Kocek',  harga: 8000  },
  { nama: 'Cireng Keju', harga: 10000 },
  { nama: 'Es Kuwut',    harga: 8000  },
];

function loadKasirHistory() {
  return JSON.parse(localStorage.getItem('tk_kasir') || '[]');
}
function saveKasirHistory(d) {
  localStorage.setItem('tk_kasir', JSON.stringify(d));
}
function loadLaporan() {
  return JSON.parse(localStorage.getItem('tk_laporan') || '[]');
}
function saveLaporan(d) {
  localStorage.setItem('tk_laporan', JSON.stringify(d));
}

// ════════════════════════════════════════════════
// KASIR STATE
// ════════════════════════════════════════════════
let keranjang  = [];  // [{idx, nama, harga, qty}]
let menuTerpilih = -1;

function pilihMenu(idx) {
  menuTerpilih = idx;
  document.querySelectorAll('.menu-item').forEach((el, i) => {
    el.classList.toggle('selected', i === idx);
  });
}

function hitungTotal() {
  const sub = keranjang.reduce((s, it) => s + it.harga * it.qty, 0);
  const diskon = sub >= 50000 ? Math.round(sub * 0.1) : 0;
  const total  = sub - diskon;
  return { sub, diskon, total };
}

function renderKeranjang() {
  const list = document.getElementById('keranjangList');
  const totalBox = document.getElementById('totalBox');
  const btnBayar = document.getElementById('btnBayar');
  const btnReset = document.getElementById('btnReset');

  if (keranjang.length === 0) {
    list.innerHTML = `<div class="empty"><div class="emoji">🛒</div><div>Belum ada pesanan</div></div>`;
    totalBox.style.display = 'none';
    btnBayar.style.display = 'none';
    btnReset.style.display = 'none';
    return;
  }

  list.innerHTML = keranjang.map((it, i) => `
    <div class="keranjang-item">
      <div>
        <div class="keranjang-nama">${it.nama}</div>
        <div class="keranjang-detail">${rp(it.harga)} / pcs</div>
      </div>
      <div class="qty-ctrl">
        <button class="qty-btn" onclick="ubahQty(${i}, -1)">−</button>
        <span class="qty-num">${it.qty}</span>
        <button class="qty-btn" onclick="ubahQty(${i}, 1)">+</button>
      </div>
      <div class="keranjang-subtotal">${rp(it.harga * it.qty)}</div>
    </div>
  `).join('');

  const {sub, diskon, total} = hitungTotal();

  document.getElementById('txtSubtotal').textContent = rp(sub);
  document.getElementById('txtTotal').textContent = rp(total);

  const rowDiskon = document.getElementById('rowDiskon');
  if (diskon > 0) {
    rowDiskon.style.display = 'flex';
    document.getElementById('txtBadgeDiskon').textContent = '10%';
    document.getElementById('txtDiskon').textContent = '− ' + rp(diskon);
  } else {
    rowDiskon.style.display = 'none';
  }

  totalBox.style.display = 'block';
  btnBayar.style.display = 'flex';
  btnReset.style.display = 'flex';
}

function tambahKeranjang() {
  if (menuTerpilih < 0) { toast('⚠️ Pilih menu dulu'); return; }
  const qty = parseInt(document.getElementById('inputJumlah').value) || 1;
  if (qty < 1) { toast('⚠️ Jumlah minimal 1'); return; }

  const menu = MENU[menuTerpilih];
  const exist = keranjang.find(it => it.idx === menuTerpilih);
  if (exist) { exist.qty += qty; }
  else { keranjang.push({ idx: menuTerpilih, nama: menu.nama, harga: menu.harga, qty }); }

  document.getElementById('inputJumlah').value = 1;
  renderKeranjang();
  toast(`✓ ${menu.nama} ×${qty} ditambahkan`);
}

function ubahQty(i, delta) {
  keranjang[i].qty += delta;
  if (keranjang[i].qty <= 0) keranjang.splice(i, 1);
  renderKeranjang();
}

function resetKeranjang() {
  keranjang = [];
  menuTerpilih = -1;
  document.querySelectorAll('.menu-item').forEach(el => el.classList.remove('selected'));
  renderKeranjang();
}

// ════════════════════════════════════════════════
// BAYAR
// ════════════════════════════════════════════════
function bukaBayar() {
  const {sub, diskon, total} = hitungTotal();
  const items = keranjang.map(it => `  ${it.nama.padEnd(14)} ×${String(it.qty).padStart(2)}  ${rp(it.harga * it.qty)}`).join('\n');
  document.getElementById('struklMini').innerHTML = `
    <div class="struk" style="margin:0">Total: <strong>${rp(total)}</strong>${diskon ? '\n(Diskon 10% sudah termasuk)' : ''}</div>`;
  document.getElementById('inputUang').value = '';
  document.getElementById('kembalianBox').style.display = 'none';
  document.getElementById('modalBayar').classList.add('open');
}

document.getElementById('inputUang').addEventListener('input', function() {
  const {total} = hitungTotal();
  const uang = parseInt(this.value) || 0;
  if (uang >= total) {
    document.getElementById('kembalianBox').style.display = 'block';
    document.getElementById('txtKembalian').textContent = rp(uang - total);
  } else {
    document.getElementById('kembalianBox').style.display = 'none';
  }
});

function tutupModal() {
  document.getElementById('modalBayar').classList.remove('open');
}

function prosesKasir() {
  const {sub, diskon, total} = hitungTotal();
  const uang = parseInt(document.getElementById('inputUang').value) || 0;

  if (uang < total) { toast('⚠️ Uang kurang!'); return; }

  const kembalian = uang - total;
  const now = new Date().toLocaleString('id-ID');

  // simpan riwayat
  const history = loadKasirHistory();
  const tx = { waktu: now, items: [...keranjang], subtotal: sub, diskon, total, uang, kembalian };
  history.unshift(tx);
  saveKasirHistory(history);

  // buat struk
  const header = 'STAN DJAWA METHAL';
  const sep    = '─'.repeat(36);
  const itemLines = keranjang.map(it =>
    it.nama.padEnd(16) + ('×' + it.qty).padStart(4) + rp(it.harga * it.qty).padStart(14)
  ).join('\n');

  const struk = [
    header.padStart(18 + header.length/2),
    now.padStart(18 + now.length/2),
    sep,
    itemLines,
    sep,
    'Subtotal'.padEnd(20) + rp(sub).padStart(16),
    ...(diskon ? ['Diskon 10%'.padEnd(20) + ('- ' + rp(diskon)).padStart(16)] : []),
    'TOTAL'.padEnd(20) + rp(total).padStart(16),
    sep,
    'Uang'.padEnd(20) + rp(uang).padStart(16),
    'Kembalian'.padEnd(20) + rp(kembalian).padStart(16),
    sep,
    '   Terima kasih telah berbelanja! 🧆',
  ].join('\n');

  document.getElementById('struklFull').textContent = struk;
  document.getElementById('modalBayar').classList.remove('open');
  document.getElementById('modalStruk').classList.add('open');

  resetKeranjang();
  renderRiwayatKasir();
  toast('✅ Transaksi berhasil!');
}

function printStruk() {
  const txt = document.getElementById('struklFull').textContent;
  const w = window.open('','','width=400,height=500');
  w.document.write(`<pre style="font-family:monospace;font-size:13px;padding:16px">${txt}</pre>`);
  w.print();
  w.close();
}

// ════════════════════════════════════════════════
// RIWAYAT KASIR
// ════════════════════════════════════════════════
function renderRiwayatKasir() {
  const history = loadKasirHistory();
  const el = document.getElementById('riwayatKasir');

  if (history.length === 0) {
    el.innerHTML = `<div class="empty"><div class="emoji">📋</div><div>Belum ada transaksi</div></div>`;
    return;
  }

  el.innerHTML = `
    <table>
      <thead>
        <tr>
          <th>Waktu</th>
          <th>Item</th>
          <th style="text-align:right">Total</th>
          <th style="text-align:right">Kembalian</th>
        </tr>
      </thead>
      <tbody>
        ${history.slice(0,20).map(tx => `
          <tr>
            <td style="font-size:12px;color:var(--abu)">${tx.waktu}</td>
            <td style="font-size:12px">${tx.items.map(it => it.nama + ' ×' + it.qty).join(', ')}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px">${rp(tx.total)}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px">${rp(tx.kembalian)}</td>
          </tr>
        `).join('')}
      </tbody>
    </table>
  `;
}

function hapusRiwayatKasir() {
  if (!confirm('Hapus semua riwayat transaksi kasir?')) return;
  saveKasirHistory([]);
  renderRiwayatKasir();
  toast('🗑️ Riwayat dihapus');
}

// ════════════════════════════════════════════════
// LAPORAN KEUANGAN
// ════════════════════════════════════════════════
function val(id) { return parseFloat(document.getElementById(id).value) || 0; }
function str(id) { return document.getElementById(id).value.trim(); }

function tambahLaporan() {
  const nama    = str('lNama');
  const harga   = val('lHarga');
  const jumlah  = val('lJumlah');
  const modal   = val('lModal');
  const listrik = val('lListrik');
  const gaji    = val('lGaji');
  const lain    = val('lLain');

  if (!nama) { toast('⚠️ Nama produk wajib diisi'); return; }

  const pendapatan  = harga * jumlah;
  const hpp         = modal * jumlah;
  const labaKotor   = pendapatan - hpp;
  const totalBeban  = listrik + gaji + lain;
  const labaBersih  = labaKotor - totalBeban;
  const margin      = pendapatan > 0 ? (labaBersih / pendapatan) * 100 : 0;
  const status      = labaBersih > 0 ? 'LABA' : labaBersih === 0 ? 'IMPAS' : 'RUGI';

  const data = loadLaporan();
  data.push({ nama, pendapatan, hpp, labaKotor, totalBeban, labaBersih, margin, status });
  saveLaporan(data);

  // reset form
  ['lNama','lHarga','lJumlah','lModal','lListrik','lGaji','lLain'].forEach(id => {
    document.getElementById(id).value = '';
  });

  renderLaporan();
  toast(`✅ ${nama} – ${status} ${rp(labaBersih)}`);
}

function renderLaporan() {
  const data = loadLaporan();
  const statsBox = document.getElementById('statsBox');
  const tableEl  = document.getElementById('laporanTable');

  if (data.length === 0) {
    statsBox.style.display = 'none';
    tableEl.innerHTML = `<div class="empty"><div class="emoji">📊</div><div>Belum ada data laporan</div></div>`;
    return;
  }

  statsBox.style.display = 'grid';

  const totalLaba   = data.reduce((s, d) => s + d.labaBersih, 0);
  const totalMargin = data.reduce((s, d) => s + d.margin, 0);
  const rataMargin  = totalMargin / data.length;
  const best        = data.reduce((a, b) => a.labaBersih > b.labaBersih ? a : b);

  document.getElementById('sTx').textContent     = data.length;
  document.getElementById('sLaba').textContent   = rp(totalLaba);
  document.getElementById('sLaba').style.color   = totalLaba >= 0 ? 'var(--hijau)' : 'var(--merah)';
  document.getElementById('sMargin').textContent = rataMargin.toFixed(1) + '%';
  document.getElementById('sBestProduk').textContent = '🏆 ' + best.nama;

  tableEl.innerHTML = `
    <div style="overflow-x:auto">
    <table>
      <thead>
        <tr>
          <th>#</th>
          <th>Produk</th>
          <th style="text-align:right">Pendapatan</th>
          <th style="text-align:right">HPP</th>
          <th style="text-align:right">Beban</th>
          <th style="text-align:right">Laba Bersih</th>
          <th style="text-align:right">Margin</th>
          <th>Status</th>
          <th></th>
        </tr>
      </thead>
      <tbody>
        ${data.map((d, i) => `
          <tr>
            <td style="color:var(--abu);font-size:12px">${i+1}</td>
            <td style="font-weight:600">${d.nama}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px">${rp(d.pendapatan)}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px;color:var(--abu)">${rp(d.hpp)}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px;color:var(--abu)">${rp(d.totalBeban)}</td>
            <td style="text-align:right;font-family:'DM Mono',monospace;font-size:13px;font-weight:700;color:${d.labaBersih >= 0 ? 'var(--hijau)' : 'var(--merah)'}">${rp(d.labaBersih)}</td>
            <td style="text-align:right;font-size:13px">${d.margin.toFixed(1)}%</td>
            <td><span class="badge badge-${d.status.toLowerCase()}">${d.status}</span></td>
            <td><button class="qty-btn" onclick="hapusRow(${i})" title="Hapus">×</button></td>
          </tr>
        `).join('')}
      </tbody>
    </table>
    </div>
  `;
}

function hapusRow(i) {
  const data = loadLaporan();
  data.splice(i, 1);
  saveLaporan(data);
  renderLaporan();
  toast('🗑️ Data dihapus');
}

function hapusLaporan() {
  if (!confirm('Hapus semua data laporan keuangan?')) return;
  saveLaporan([]);
  renderLaporan();
  toast('🗑️ Laporan dihapus');
}

// ════════════════════════════════════════════════
// INIT
// ════════════════════════════════════════════════
renderKeranjang();
renderRiwayatKasir();
renderLaporan();
</script>
</body>
</html>

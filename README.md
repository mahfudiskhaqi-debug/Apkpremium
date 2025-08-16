<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>SVARKA SHOP – Reseller Premium #1 Sejak Januari 2025</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet"/>
<style>
:root{
  --bg:#0d1117;
  --card:#161b22;
  --accent:#00d4aa;
  --text:#f0f6fc;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:var(--bg);color:var(--text);padding:25px}
header{text-align:center;margin-bottom:30px}
header h1{font-size:2.2em;font-weight:600;color:var(--accent)}
header p{font-size:1em;opacity:.8;margin-top:4px}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:20px;max-width:480px;margin:auto}
.card{background:var(--card);border-radius:12px;padding:15px 10px;text-align:center;cursor:pointer;transition:.3s}
.card:hover{transform:translateY(-6px);box-shadow:0 0 20px var(--accent)}
.card img{width:52px;height:52px;margin-bottom:8px;object-fit:contain}
.card h3{font-size:15px;font-weight:600}
.card p{font-size:12px;opacity:.7;margin-top:4px}
.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,.75);align-items:center;justify-content:center;z-index:999}
.modal.show{display:flex}
.modal-content{background:var(--card);border-radius:14px;width:90%;max-width:340px;padding:20px;animation:pop .3s}
@keyframes pop{from{transform:scale(.8)}to{transform:scale(1)}}
.modal h2{font-size:1.2em;margin-bottom:10px;color:var(--accent)}
.price-btn{background:transparent;border:2px solid var(--accent);color:var(--accent);width:100%;margin:6px 0;padding:9px;border-radius:8px;font-size:13px;cursor:pointer;transition:.3s}
.price-btn:hover{background:var(--accent);color:#000}
.close{position:absolute;top:10px;right:15px;font-size:1.4em;cursor:pointer}
footer{background:var(--card);margin-top:40px;padding:20px;border-radius:12px;font-size:13px;text-align:center;color:var(--text)}
footer a{color:var(--accent);text-decoration:none}
</style>
</head>
<body>

<header>
  <h1>SVARKA SHOP</h1>
  <p>Reseller Premium Digital Terpercaya • Berdiri Januari 2025</p>
</header>

<div class="grid">
  <!-- Netflix -->
  <div class="card" onclick="openModal('Netflix Premium UHD','Netflix',[
      {label:'1P1U 1 Minggu',price:'Rp 12.000'},
      {label:'1P1U 1 Bulan',price:'Rp 24.000'},
      {label:'1P1U 2 Bulan',price:'Rp 42.000'},
      {label:'1P2U 1 Bulan',price:'Rp 16.000'},
      {label:'Semi-Private 1 Bulan',price:'Rp 28.000'},
      {label:'Private 1 Bulan',price:'Rp 110.000'}
    ])">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" alt="Netflix">
    <h3>Netflix UHD</h3>
    <p>Streaming bebas, full garansi!</p>
  </div>

  <!-- Spotify -->
  <div class="card" onclick="openModal('Spotify Premium','Spotify',[
      {label:'Family Plan 1 Bulan',price:'Rp 15.000'},
      {label:'Family Plan 2 Bulan',price:'Rp 30.000'},
      {label:'Individual 1 Bulan',price:'Rp 20.000'},
      {label:'Individual No-Garansi',price:'Rp 10.000'}
    ])">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg" alt="Spotify">
    <h3>Spotify Premium</h3>
    <p>Offline & no-ads, langsung jalan!</p>
  </div>

  <!-- ChatGPT -->
  <div class="card" onclick="openModal('ChatGPT Plus','ChatGPT',[
      {label:'Team Family 1 Bulan',price:'Rp 33.000'},
      {label:'Head 5 User 1 Bulan',price:'Rp 69.000'},
      {label:'Head No-Garansi',price:'Rp 140.000'},
      {label:'Sharing 5U',price:'Rp 32.000'},
      {label:'Private',price:'Rp 220.000'}
    ])">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" alt="ChatGPT">
    <h3>ChatGPT Plus</h3>
    <p>GPT-4 tanpa limit, jawaban kilat!</p>
  </div>

  <!-- Canva -->
  <div class="card" onclick="openModal('Canva Pro','Canva',[
      {label:'Member 1 Bulan',price:'Rp 2.000'},
      {label:'Member 1 Tahun',price:'Rp 7.000'},
      {label:'Lifetime EDU',price:'Rp 15.000'},
      {label:'Head Owner 1b ',price:'Rp 8.000'}
    ])">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEieF4svO2HZwTv-YUsqtsGfXU6TFkZ9reshzKI1TI0buE5v9ihtbyGBnIa4cjUrwxuckvTPXzkagK1GhqSYAB84wqZtrAl1n5qJ_YKozb12nWV0nX0s5jE4BPxra8YKG1xMdz_5BJBdzxSVnSeNZ_AhqqgP97R9rveLb-OHuunpInKDnwCaJQAZUzVCfvM/s320/41746.png" alt="Canva">
    <h3>Canva Pro</h3>
    <p>Template premium & magic resize!</p>
  </div>

  <!-- Vidio -->
  <div class="card" onclick="openModal('Vidio Platinum','Vidio',[
      {label:'Private TV 1 Th (No-Gar)',price:'Rp 9.000'},
      {label:'Private TV 1 Th (Gar 12B)',price:'Rp 20.000'},
      {label:'Sharing All 1 Bulan',price:'Rp 22.000'},
      {label:'Private All 1 Bulan',price:'Rp 35.000'},
      {label:'Diamond All 1 Bulan',price:'Rp 100.000'}
    ])">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhmxbKfVHK-AR_jN43EmY0XjCoCyhAGsURCJQTukdnRSE9gcwxyDMI02QYwRdquldpUU-M_RJ8VUhAETNKv_kz1it3PX1THY9GvyIdm3fJ9r4Ui9smUEKZyAqI3yFPqalYI-ltIV22uKJV6_xnSylOVQBQO9PZ_Xj61TQQbPhkIyKqJJND4SoUWehteQbk/s320/41742.png" alt="Vidio">
    <h3>Vidio Platinum</h3>
    <p>Nobar liga & drama korea HD!</p>
  </div>

  <!-- CapCut -->
  <div class="card" onclick="openModal('CapCut Pro','CapCut',[
      {label:'Sharing 3U 1 Bulan',price:'Rp 6.000'},
      {label:'Private 7 Day',price:'Rp 5.000'},
      {label:'Private 1 Bulan',price:'Rp 15.000'},
      {label:'Private 6 Bulan',price:'Rp 90.000'}
    ])">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhr4FELjmux885QLwvcgBIc3Fscy84t7zcgdwDsad7nikfXVwLUGFX0QWf4LTjhU5uhXPZ463UEXUY7Di4maSbBLCdq4N-Gb8mwUR7Fy0Tv4d75GVNb3bQRmqwWz8GZ2lpC473cEawlTysKMDGwMH5dM3L8ALS5bDldcROWq_3Xoa9cTXwH_99PbSR2V8I/s320/41736.jpg" alt="CapCut">
    <h3>CapCut Pro</h3>
    <p>Effect premium & no watermark!</p>
  </div>
</div>

<!-- Modal -->
<div class="modal" id="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal()">&times;</span>
    <h2 id="modalTitle"></h2>
    <div id="priceList"></div>
  </div>
</div>

<footer>
  <strong>Kebijakan Privasi</strong><br>
  SVARKA SHOP tidak pernah menyimpan kata sandi atau data pribadi Anda. Semua transaksi aman & garansi 100 % sesuai ketentuan.<br>
  <a href="https://wa.me/6285857898319?text=Halo%20SVARKA%20SHOP,%20saya%20ingin%20tanya%20privasi">Hubungi Admin</a>
</footer>

<script>
const WA = "6285857898319";
function openModal(title,_,items){
  document.getElementById("modalTitle").textContent = title;
  const list = document.getElementById("priceList");
  list.innerHTML = "";
  items.forEach(i=>{
    const btn = document.createElement("button");
    btn.className = "price-btn";
    btn.textContent = `${i.label} – ${i.price}`;
    btn.onclick = () => {
      const msg = `Halo *SVARKA SHOP* , saya mau beli ${title} (${i.label} - ${i.price}).`;
      window.open(`https://wa.me/${WA}?text=${encodeURIComponent(msg)}`);
    };
    list.appendChild(btn);
  });
  document.getElementById("modal").classList.add("show");
}
function closeModal(){
  document.getElementById("modal").classList.remove("show");
}
</script>

</body>
</html>
>

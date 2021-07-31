---
toc: true
type: docs
date: 2021-04-01T02:39:00.000Z
weight: 1

menu:
    layanan-2:
        identifier: tanya
        parent: Pustaka Pertanyaan
        name: Tata Surya
        weight: 1
    



---
<!--
+++
title = "Tata Surya"
date = 2021-03-15T00:00:00
toc = true
type = "docs"

linktitle = "Tata Surya"

[menu.layanan]
    parent = "Pustaka Pertanyaan"
    weight = 1
+++
-->
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  transition: 0.4s;
  font-size:16px;
}

.actives, .accordion:hover {
  background-color: #ccc;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.actives:after {
  content: "\2212";
}

.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  font-size:15px;
  transition: max-height 0.2s ease-out;
}
</style>

<h2>Pustaka Pertanyaan</h2>

### Bumi
<div>Seputar Bumi</div>
<button class="accordion">Jika melompat di luar angkasa apakah bisa kembali lagi?</button>	
<div class="panel">Bergantung pada kecepatan melompatnya. Jika kecepatan melompat kita jauh lebih tinggi daripada kecepatan lepas (yang bergantung pada kekuatan gravitasi Bumi), maka ia bisa bebas meninggalkan permukaan Bumi dan tak jatuh lagi. Itu yang diupayakan oleh roket-roket yang keluar angkasa. Karena manusia tidak bertenaga setinggi itu, maka manusia hanya bisa melompat rendah saja dan jatuh lagi ke permukaan Bumi.
</div>

### Matahari
<div>Seputar Matahari</div>
<button class="accordion">Kenapa Matahari bisa "mati"?</button>	
<div class="panel">Matahari memiliki "bahan bakar" berupa atom-atom hidrogen sehingga dapat menghasilkan energi melalui fusi nuklir di intinya. Hingga pada suatu masa, bahan bakar tersebut akan habis digunakan, dan "mati". Tidak hanya Matahari, semua bintang di langit juga akan mengalami hal yang kurang lebih sama: mereka akan mengakhiri masa hidupnya ketika bahan bakarnya habis. 
</div>

### Planet dan planet kerdil
<div>Seputar planet</div>
<button class="accordion">Mengapa retakan di Mars jauh lebih besar daripada yang ada di Bumi?</button>
<div class="panel">
  <p>Retakan di Mars bernama Valles Marineris. Retakan ini terbentuk akibat adanya patahan di lapisan kerak Mars. Ukurannya yang sangat besar disebabkan oleh erosi dan runtuhnya dinding retakan tersebut.</p>
</div>
<button class="accordion">Mengapa Mars dapat dijadikan sebagai objek <em>terraforming</em>?</button>
<div class="panel">
  <p>Salah satu alasan mengapa Mars dapat dijadikan sebagai objek <em>terraforming</em> yaitu keberadaan air dalam bentuk es di Mars dan sejarah geologisnya menunjukkan bahwa Mars pernah memiliki atmosfer yang mirip dengan Bumi. Akan tetapi, dengan teknologi yang ada saat ini, masih kurang memungkinkan untuk melakukan <em>terraforming</em> di Mars.</p>
</div>

### Bulan
<div>Seputar Bulan</div>

### Asteroid
<div>Seputar asteroid</div>

### Komet dan meteor
<div>Seputar komet dan meteor</div>
<button class="accordion">Apakah yang dimaksud dengan Awan Oort dan dampaknya bagi Tata Surya kita?</button>
<div class="panel">
  <p>Awan Oort adalah daerah di bagian luar tata surya kita yang terdiri atas objek-objek kecil tata surya, mayoritas terbuat dari es, seperti komet. Awan Oort diprediksi menyelingkupi seluruh objek di tata surya seperti sebuah kulit bola. Dampaknya kita kedatangan komet-komet dengan periode panjang, karena Awan Oort adalah rumah bagi calon-calon komet yang akan masuk ke tata surya kita karena gangguan di sekitarnya dan jaraknya cukup jauh dari kita, sekitar 2.000-100.000x jarak Bumi-Matahari.</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("actives");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>


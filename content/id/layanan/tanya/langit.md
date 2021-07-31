---
toc: true
type: docs
date: 2020-07-19T10:30:00+07:00

linktitle: Pengamatan Langit
identifier: langit

menu:
    layanan-2:
        parent: Pustaka Pertanyaan
        weight: 3
weight: 3
---
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
  transition: max-height 0.2s ease-out;
}
</style>

<h2>Pustaka Pertanyaan</h2>

### Gerhana, Transit, dan Okultasi
<div>Seputar gerhana, transit, dan okultasi</div>

### Observasi Kasat Mata
<div>Seputar observasi kasat mata</div>
<button class="accordion">Bagaimana cara para ilmwuan mengukur jarak benda-benda di alam semesta?</button>
<div class="panel">
  <p>Teknik mengukur jarak dalam astronomi ada bermacam-macam. Untuk jarak-jarak 'dekat' bisa menggunakan paralaks trigonometri. Untuk jarak yang lebih jauh bisa menggunakan bintang variabel, supernova tipe Ia (supernova pada bintang ganda), atau dengan hukum Hubble.</p>
</div>
<button class="accordion">Rasi bintang apa saja yang bisa dilihat secara langsung tanpa teropong?</button>
<div class="panel">
  <p>Pada dasarnya semua rasi bintang dapat dilihat secara langsung tanpa alat bantu, karena mayoritas, secara historis, mereka "dibuat" oleh peradaban kuno sebelum diciptakannya teleskop. Bahkan rasi bintang digunakan sebagai penanda perubahan musim atau penanda arah. Untuk saat ini, kembali pada kualitas langit di tempat pengamatan, karena mungkin ada bintang-bintang yang lebih redup yang jadi tidak bisa dilihat secara langsung. Namun bintang-bintang terang yang membuat rasi-rasi bintang harusnya bisa dilihat menggunakan mata telanjang.</p>
</div>
<button class="accordion">Mengapa terdapat perubahan bentuk pada gambar objek yang ditangkap pada panjang gelombang yang berbeda?</button>
<div class="panel">
  <p>Pengamatan pada panjang gelombang yang berbeda dapat diartikan bahwa pengamatan yang dilakukan menyasar ke unsur yang berbeda di objek tersebut. Di dalam sebuah objek astronomis, unsur-unsur penyusunnya terdiri dari berbagai jenis atom yang berbeda (seperti hidrogen, oksigen, nitrogen, dll.), serta jumlah dan sebaran yang berbeda. Hal-hal tersebut menyebabkan penampakan suatu objek astronomis berubah pada panjang gelombang yang berbeda.</p>
</div>
<button class="accordion">Apakah aplikasi astronomi seperti Stellarium, Star Tracker, dsb. itu betul-betul menampilkan kenampakan langit beserta objek-objeknya sesuai dengan lokasi kita?</button>
<div class="panel">
  <p>Aplikasi Stellarium ataupun Star Tracker dapat digunakan untuk membantu kita dalam mengamati objek-objek di langit dengan menyesuaikan pengaturan lokasi dan waktu yang digunakan. Aplikasi semacam ini menggunakan data astronomis yang valid untuk mendeteksi melalui sistem sensor yang terdapat pada perangkat terkait objek-objek yang dapat teramati pada suatu arah langit dan waktu tertentu.</p>
</div>
<button class="accordion">Apakah kita bisa menamai objek-objek antariksa?</button>
<div class="panel">
  <p>Pada umumnya, objek-objek antariksa memiliki pola penamaannya tersendiri, seperti posisinya, waktu ditemukan, jenis objeknya, urutannya pada katalog dan sebagainya. IAU (International Astronomical Union), perkumpulan astronomi internasional, memiliki beberapa program yang berkaitan dengan menamai objek-objek antariksa sehingga memilik nama yang khas. Salah satunya "NamingExoWorlds", yaitu masyarakat di seluruh dunia diberikan kesempatan untuk menamai eksoplanet (planet-planet di luar Tata Surya) dan bintang induknya yang telah terkonfirmasi. Beberapa negara ikut serta dalam program ini, salah satunya Indonesia. Nama eksoplanet dengan istilah Indonesia yang telah diresmikan adalah "Noifasui" dan bintang induknya bernama "Dofida", yang diambil dari bahasa Nias.</p>
</div>
<button class="accordion">Mengapa sulit melihat bintang ketika berawan?</button>
<div class="panel">
  <p>Keberadaan awan membuat atmosfer tidak transparan dan menghalangi cahaya bintang untuk dapat kita lihat dari Bumi. Semakin tebal awan yang menutupi, semakin bintang tidak terlihat hingga akhirnya tidak terlihat sama sekali.</p>
</div>

### Astrofotografi
<div>Seputar astrofotografi</div>

### Instrumen Pengamatan
<div>Seputar instrumen pengamatan</div>


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

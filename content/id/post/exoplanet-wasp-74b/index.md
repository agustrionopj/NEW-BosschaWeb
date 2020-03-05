+++
title = "Pengamatan Transit Eksoplanet WASP-74b"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = ""

date = 2016-11-17T05:53:24+07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin"]

# Is this a featured post? (true/false)
featured = true

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["exoplanet", "internal"]
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

Eksoplanet adalah planet yang mengorbit bintang lain selain Matahari. Hingga saat ini, lebih dari 3400 eksoplanet ditemukan dan sudah terkonfirmasi. Terdapat beberapa metode untuk mendeteksi adanya planet di bintang lain. Metode yang paling banyak/mudah dilakukan adalah metode transit. Transit eksoplanet merupakan peristiwa lewatnya planet di depan bintang sehingga cahaya bintang sedikit meredup (mirip gerhana atau transit planet Venus). Peredupan ini yang kemudian dapat dideteksi dan menjadi indikator adanya planet.

{{< figure src="ilustrasi_transit.png" title="Ilustrasi transit eksoplanet (kredit: www.nasa.gov)" >}}

Salah satu kegiatan yang dilakukan di Observatorium Bosscha adalah mencari eksoplanet baru dan juga melakukan konfirmasi adanya eksoplanet. Kali ini akan dipaparkan salah satu hasil pengamatan transit eksoplanet WASP-74 b di Observatorium Bosscha. Pengamatan eksoplanet WASP-74 b dilakukan menggunakan teleskop Planewave CDK 14″ (~36 cm) f/7.2  dan detektor (CCD) FLI Proline 11002.

Planet WASP-74 b merupakan eksoplanet yang mengorbit bintang dengan magnitudo 9.7, sehingga merupakan salah satu sistem keplanetan luar surya paling terang yang dapat diamati di belahan langit selatan. Planet ini ditemukan menggunakan metode transit oleh tim WASP, dan telah dikonfirmasi dengan pengukuran kecepatan radial. Penemuan eksoplanet ini dipaparkan di makalah Coel Hellier (2014). Planet WASP-74 b memiliki massa 0.95 massa Jupiter dan radius 1.56 radius Jupiter, mengorbit dengan periode 2.1378 hari di bintang kelas F9 dengan massa 1.48 dan radius 1.64 Matahari.

Kurva cahaya ketika terjadi transit seperti ditunjukkan pada plot di bawah ini diperoleh setelah dilakukan reduksi data fotometri. Dari dua kurva cahaya transit (selang 2 hari) yang diperoleh, hanya satu yang ditampilkan (hasil pada tanggal 28 Juli 2016).

{{< figure src="lightcurve_wasp-74b.png" title="Kurva cahaya WASP-74b" >}}

Terlihat perubahan kecerlangan bintang, menurun kemudian naik kembali, mengindikasikan adanya objek yang menghalangi cahaya bintang tersebut, dalam hal ini planet WASP-74 b yang sedang lewat di depan bintang. Data transit ini kemudian dapat diolah untuk mendapatkan parameter fisis planet. Parameter yang paling penting adalah perbandingan antara radius planet dengan radius bintang.

Walaupun kurva cahaya terlihat cukup datar, tetapi masih mungkin adanya kontaminasi (*noise*) yang bisa berasal dari instrumen, bintangnya sendiri (misal aktivitas bintang), atau massa udara (*airmass*). *Red noise* ini dapat dihilangkan apabila kita mengetahui sumber *noise*-nya dengan baik. Setelah menghilangkan *noise* terkorelasi tersebut (disebut proses *de-trending* di kalangan pengamat eksoplanet),  *fitting* baru dapat dilakukan untuk memperoleh parameter fisis planet. Pada kenyataannya sangat sulit untuk menghilangkan noise ini secara langsung. Untuk menyederhanakan kasus, proses *de-trending* dan *fitting* dilakukan bersama dengan menyederhanakan model kurva cahaya terkorelasi (berlaku untuk data transit pendek). Bentuk kurva cahaya bintang sesaat sebelum hingga sesaat sesudah transit dimodelkan dengan bentuk melengkung (persamaan kuadrat) lalu ditambahkan peredupan akibat transit planet ($F_\mathrm{ratio}$).

$$
  \Delta m = A - 2.5 \log (F_\mathrm{ratio}) + B(t - \bar{t}) + C(t - \bar{t})^2
$$

Cara ini dilakukan juga pada <a href="http://var2.astro.cz/EN/" target="_blank"> web penampungan data pengamatan transit eksoplanet republik Czech </a>. Bedanya, pada pekerjaan ini, *fitting* dilakukan dengan pendekatan Bayesian (i.e. metode <font color='red'>Markov Chain Monte Carlo</font> atau <font color='red'>MCMC</font>). Model transit ($F_\mathrm{ratio}$) yang digunakan menggunakan persamaan Mandel & Agol (2002); *quadratic limb darkening*, dengan koefisien *limb darkening* (penggelapan tepi) diparameterisasi mengikuti Kipping (2013) untuk memudahkan pengusulan *Prior*.

Hasil *fitting* ditunjukkan pada plot berikut.

{{< figure src="featured.png" title="Hasil *fitting* kurva cahaya WASP-74b" >}}

dengan nilai parameter hasil *fitting* ditunjukkan pada tabel berikut (median + error 1-sigma diambil dari *quantile* 0.16 dan 0.84).

{{< figure src="table1.png" width="400px" title="Hasil *fitting* data terhadap model (Mandel & Agol + *de-trending*)" >}}

{{< figure src="table2.png" width="400px" title="Parameter lain yang diturunkan dari hasil *fitting*" >}}



*Posterior density function* (PDF) akhir hasil MCMC setelah dilakukan cek konvergensi parameter serta proses “burning” dan “thining” dapat dilihat pada plot berikut.

{{< figure src="cornerplot.png" title="PDF dari proses MCMC kurva cahaya WASP-74b" >}}

Dengan pengamatan kurva cahaya seperti ini saja sebetulnya belum diperoleh kepastian adanya planet yang sedang transit. Bisa saja penurunan intensitas cahaya bintang (secara periodik) ini disebabkan hal fisis lain, misal apabila bintang ini adalah bintang ganda dekat yang orbitnya kebetulan mengalami sedikit sekali penggerhanaan (eclipsing binary) yang menghasilkan kurva cahaya menyerupai transit planet. Konfirmasi kebenaran adanya planet dapat dilakukan dengan pengamatan kecepatan radial (hal ini sudah dilakukan oleh tim WASP penemu planet ini) atau pengamatan transit diberbagai filter khusus. Pengamatan transit juga hanya dapat mengkonstrain/membatasi rasio antara radius planet dengan bintang, serta rasio semi mayor orbit planet dengan radius bintang (bintang terang ditutupi planet besar akan menghasilkan perubahan fluks cahaya yang sama dengan bintang redup ditutupi oleh planet kecil). Artinya, diperlukan data lain untuk mendapatkan dimensi planet sebenarnya; misal massa atau radius bintang dari pengamatan menggunakan metode lain.

Jika kita menggunakan data massa bintang sebesar $1.48 \pm 0.12$ massa Matahari, maka radius planet WASP-74 b dapat diturunkan dari data pengamatan ini, yaitu sebesar $1.53 \pm 0.1$ radius Jupiter. Hasil ini masih sesuai dengan perhitungan tim WASP, yaitu sebesar $1.56 \pm 0.06$ radius Jupiter.

Pengamatan ini membuktikan bahwa dengan kondisi langit di Lembang yang sudah memburuk akibat polusi cahaya, pengamatan transit eksoplanet masih dapat dilakukan hingga orde delta magnitudo, $\Delta m = 0.01$ (untuk bintang induk dengan terang 9.7 mag). Di sisi lain, pengamatan kecepatan radial masih perlu dilakukan untuk mengonfirmasi keberadaan planet ini dengan pasti. Sayangnya, Observatorium Bosscha belum memiliki instrumen (spektrograf)  dengan resolusi tinggi yang dapat mendeteksi perubahan kecepatan radial hingga orde di bawah 100 m/s.

Hasil pengamatan dan analisis ini telah dipresentasikan di <font color='red'>International Conference on Mathematics and Natural Sciences (ICMNS)</font> yang diadakan di ITB pada tanggal 2-3 November 2016 lalu.

Pengamatan dan reduksi data dilakukan oleh Muhammad Yusuf (Research assistant, pemecah rekor pengamatan bulan sabit serta pengembang robotic telescope di Observatorium Bosscha), sedangkan analisis data dilakukan oleh Ridlo W. Wibowo (Research assistant, mahasiswa Program Doktor Astronomi ITB).
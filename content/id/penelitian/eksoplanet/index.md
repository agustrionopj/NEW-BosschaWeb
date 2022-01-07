+++
title = "Eksoplanet"

date = 2021-10-07T05:00:00
# lastmod = 2021-09-21T05:00:00

draft = false  # Is this a draft? true/false
toc = false  # Show table of contents? true/false
type = "docs"  # Do not modify.

# Add menu entry to sidebar.
[menu.topik]
  parent = "Topik"
  name = "Eksoplanet"
  weight = 3
+++

{{<figure src="wasp74b.png" width="60%" caption="Kurva cahaya eksoplanet WASP-74b pada peristiwa transit, diamati dari Observatorium Bosscha$^1$">}}

Riset eksoplanet di Observatorium Bosscha sudah terhitung cukup dewasa dan telah dimulai sejak tahun 2006. Pengamatan eksoplanet dimulai sejak Michel Mayor dan Didier Queloz mempublikasikan variasi kecepatan radial pada bintang 51 Pegasi yang menunjukkan keberadaan eksoplanet untuk pertama kali pada tahun 1995. Sejak saat itu, berbagai macam metode pengamatan eksoplanet telah didesain dan diterapkan. Salah satu teknik yang digunakan adalah fotometri transit, yaitu dengan mengukur kecerlangan bintang pada periode tertentu dan kemudian mendeteksi adanya peredupan pada kecerlangan yang diakibatkan oleh lewatnya eksoplanet yang mengorbit bintang tersebut di antara bintang dan pengamat. Menggunakan metode ini, tidak diperlukan spesifikasi instrumen yang terlalu tinggi. Untuk eksoplanet yang berada pada rentang kelas *Hot Jupiter*, penurunan kecerlangan bintang induk dapat bernilai hingga dua persen. Sebagai ilustrasi, peristiwa ini dapat digambarkan sebagai penurunan kecerlangan mercusuar ketika terdapat seekor nyamuk yang lewat di depannya. Hal yang diperlukan untuk melakukan pengamatan menggunakan metode ini adalah tingkat kepresisian yang tinggi. Upaya yang dapat dilakukan untuk mencapai tingkat kepresisian ini adalah dengan memperbaiki kalibrasi *flat* dan mengembangkan sistem *tracking* dengan ketelitian yang sangat tinggi hingga ke orde piksel.

Dua instrumen yang digunakan dalam riset eksoplanet adalah teleskop BRT dan STEVia. Teleskop BRT digunakan untuk melakukan konfirmasi eksoplanet yang telah terdeteksi sebelumnya serta memperbaiki parameter fisis dari eksoplanet tersebut. Selain itu, teleskop ini digunakan untuk mengkonfirmasi eksoplanet yang telah terdeteksi oleh satelit *Transiting Exoplanet Survey Satellite* (TESS) dengan kandidat eksoplanet mulai dari kelas *Trans-Neptunian* hingga *Super Earth*. Melengkapi pekerjaan yang dilakukan menggunakan BRT, teleskop STEVia digunakan untuk melakukan survei eksoplanet pada gugus bintang terbuka. Hasil terbaik yang mungkin didapat menggunakan teleskop ini adalah penurunan kecerlangan sebesar satu persen yang berkaitan dengan eksoplanet kelas *Hot Jupiter*.

Pengembangan lanjutan yang dilakukan oleh tim riset ini adalah dengan memperbaiki sistem *tracking* hingga ke skala sub-detik busur (ketelitian hingga setengah detik busur). Ketelitian ini dapat dicapai dengan melakukan kalibrasi *real-time* ketika pengamatan dilakukan. Selain itu, akan dikembangkan juga *pipeline* pengolahan data eksoplanet yang akan menerima kurva cahaya hasil pengamatan sebagai masukan, kemudian menghasilkan klasifikasi apakah pada sistem tertentu terdapat eksoplanet atau tidak. Klasifikasi ini nantinya akan dilakukan menggunakan algoritma *machine learning* yang tersimpan di server. Upaya terakhir yang akan dicoba dilakukan adalah mencari lokasi pengamatan eksoplanet yang lebih baik, salah satunya dengan cara bergabung dalam konsorsium internasional pengamatan eksoplanet.

{{%alert note%}}
Peneliti Utama: Muhammad Yusuf, S.Si.
- <i class='fas fa-envelope'></i> yusuf(at)as.itb.ac.id
{{%/alert%}}

Referensi:

1. Wibowo, R. W., Yusuf, M., Hidayat, T., Mahasena, P., Mandey, D., dan Dermawan, B., 2019. *Light Curve Analysis for The Transit of Exoplanet WASP-74b Observed at Bosscha Observatory*. Journal of Physics: Conference Series, **1127**, 012055
+++
title = "Kalkulator Skala Tata Surya"
date = 2021-03-15T00:00:00
lastmod = 2021-09-02T00:00:00
toc = true
type = "docs"
draft = false

linktitle = "Kalkulator Skala Tata Surya"

[menu.layanan]
    parent = "Materi Edukasi Astronomi"
    weight = 2
+++

Tata Surya kita sangatlah besar. Dimensi ukuran dan jarak pada benda-benda astronomis terkadang sangat ekstrim sehingga sulit dibayangkan dari pengalaman sehari-hari. 

Bayangkan, Matahari berukuran satu juta Bumi sementara kita sendiri yang tinggal di permukaan Bumi masih kesulitan membayangkan besarnya Bumi. Oleh karena itu, para astronom membangun satuan besaran baru untuk membantu menyatakan dimensi yang sangat besar. Jarak rata-rata Bumi ke Matahari sebesar 149.000.000 km. Berdasarkan perhitungan tersebut, dibuatlah besaran baru, yaitu Satuan Astronomis (SA) yang menjadikan jarak Bumi-Matahari sebesar 1 SA. Jarak-jarak planet atau benda lain kemudian dapat dinyatakan dengan satuan SA, sehingga kita langsung dapat membayangkan dimensi tersebut karena dibandingkan dengan jarak Bumi-Matahari. 

Faktanya, akan lebih mudah membayangkan ukuran maupun letak benda-benda di Tata Surya dengan membuat model berskala. Anda dapat membuat skala dimensi atau ukuran benda-benda di Tata Surya dengan bantuan kalkulator ini. 

- Yang perlu dilakukan adalah mengisi kolom ukuran diameter Matahari (dalam mm) yang akan digunakan sebagai perbandingan. Misal, Anda memiliki sebuah bola basket yang akan digunakan sebagai model Matahari. Masukan diameter bola, pilih “hitung” dan kolom-kolom ukuran dan jarak planet lain akan otomatis terisi.

- Dengan informasi ini, Anda dapat membangun model Tata Surya. Carilah benda-benda yang memiliki ukuran/berukuran seperti diameter planet  yang tertera (Anda dapat membuatnya sendiri dari material tanah liat atau plastisin).

- Gunakan pita, benang kasur atau tali lainnya untuk meletakan planet-planet tersebut pada jarak orbitnya. 

Untuk mempelajari skala dimensi yang lebih sederhana bagi anak-anak usia TK atau sekolah dasar dapat mengadaptasi aktivitas [ini](https://bosscha.itb.ac.id/files/Membuat-Model-Ukuran-Tata-Surya.pdf).

<hr>
<form id="SolCalcForm"
      name="SolCalcForm">
  Ukuran Matahari dalam mm: <input name="x"
        size="18"
        type="text"> <input onclick="Calculate(document.SolCalcForm)"
        type="button"
        value="Hitung!">
  <hr>
  <table border="0"
          cellpadding="2"
          cellspacing="2"
          width="100%">
    <tbody style="width: 100%; display: table;;">
      <tr>
        <th valign="top"></th>
        <td valign="middle">
          <div align="left">
            <strong>Diameter Sesungguhnya</strong>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <strong>Diameter Skala</strong>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <strong>Jarak Orbit Sesungguhnya</strong>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <strong>Jarak Orbit Skala</strong>
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Matahari<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_sun_real"
                  readonly
                  size="18"
                  type="text"
                  value="1.391.900"> km
          </div>
        </td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Merkurius<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_mercury_real"
                  readonly
                  size="18"
                  type="text"
                  value="4.866"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_mercury"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_mercury_real"
                  readonly
                  size="18"
                  type="text"
                  value="57.950.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_mercury"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Venus<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_venus_real"
                  readonly
                  size="18"
                  type="text"
                  value="12.106"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_venus"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_venus_real"
                  readonly
                  size="18"
                  type="text"
                  value="108.110.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_venus"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Bumi<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_earth_real"
                  readonly
                  size="18"
                  type="text"
                  value="12.742"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_earth"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_earth_real"
                  readonly
                  size="18"
                  type="text"
                  value="149.570.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_earth"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Mars<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_mars_real"
                  readonly
                  size="18"
                  type="text"
                  value="6.760"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_mars"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_mars_real"
                  readonly
                  size="18"
                  type="text"
                  value="227.840.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_mars"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Jupiter<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_jupiter_real"
                  readonly
                  size="18"
                  type="text"
                  value="139.516"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_jupiter"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_jupiter_real"
                  readonly
                  size="18"
                  type="text"
                  value="778.140.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_jupiter"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Saturnus<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_saturn_real"
                  readonly
                  size="18"
                  type="text"
                  value="116.438"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_saturn"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_saturn_real"
                  readonly
                  size="18"
                  type="text"
                  value="1.427.000.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_saturn"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Uranus<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_uranus_real"
                  readonly
                  size="18"
                  type="text"
                  value="46.940"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_uranus"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_uranus_real"
                  readonly
                  size="18"
                  type="text"
                  value="2.870.300.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_uranus"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Neptunus<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_neptune_real"
                  readonly
                  size="18"
                  type="text"
                  value="45.432"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_neptune"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_neptune_real"
                  readonly
                  size="18"
                  type="text"
                  value="4.499.900.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_neptune"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Pluto<br>
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_pluto_real"
                  readonly
                  size="18"
                  type="text"
                  value="3.400"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="d_pluto"
                  readonly
                  size="18"
                  type="text"
                  value=""> mm
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_pluto_real"
                  readonly
                  size="18"
                  type="text"
                  value="5.913.000.000"> km
          </div>
        </td>
        <td valign="middle">
          <div align="left">
            <input name="r_pluto"
                  readonly
                  size="18"
                  type="text"
                  value=""> m
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Bintang $\alpha$ Cen<br>
          </div>
        </td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle">
          <div align="left">
            <input name="r_acentauri"
                  readonly
                  size="18"
                  type="text"
                  value=""> km
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Bintang Sirius<br>
          </div>
        </td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle">
          <div align="left">
            <input name="r_sirius"
                  readonly
                  size="18"
                  type="text"
                  value=""> km
          </div>
        </td>
      </tr>
      <tr valign="top">
        <td valign="middle">
          <div align="right">
            Galaksi Andromeda<br>
          </div>
        </td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle"><br></td>
        <td valign="middle">
          <div align="left">
            <input name="r_andromeda"
                  readonly
                  size="18"
                  type="text"
                  value=""> km
          </div>
        </td>
      </tr>
    </tbody>
  </table>
</form>


<script language="JavaScript">      
  function int_zero(x){
    if ( x < 1 )
  return 0 ;
    else
  return parseInt( x ,10 );
  }
  function Calculate(form) {
    var b = form.x.value;
    if ( b != 0) {
    scale_factor = (b / 25.4) / 1391900;
    }
    form.d_mercury.value = (int_zero(scale_factor * 4866 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_mercury.value = (int_zero(scale_factor * 57950000 * .0254 *1000  ) / 1000).toLocaleString('id-ID');
    
    form.d_venus.value = (int_zero(scale_factor * 12106 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_venus.value = (int_zero(scale_factor * 108110000 * .0254 *1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_earth.value = (int_zero(scale_factor * 12742 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_earth.value = (int_zero(scale_factor * 149570000 * .0254 *1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_mars.value = (int_zero(scale_factor * 6760 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_mars.value = (int_zero(scale_factor * 227840000 * .0254 *1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_jupiter.value = (int_zero(scale_factor * 142984 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_jupiter.value = (int_zero(scale_factor * 778140000 * .0254 * 1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_saturn.value = (int_zero(scale_factor * 116438 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_saturn.value = (int_zero(scale_factor * 1427000000 * .0254 * 1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_uranus.value = (int_zero(scale_factor * 46940 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_uranus.value = (int_zero(scale_factor * 2870300000 * .0254 * 1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_neptune.value = (int_zero(scale_factor * 45432 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_neptune.value = (int_zero(scale_factor * 4499900000 * .0254 * 1000 ) / 1000).toLocaleString('id-ID');
    
    form.d_pluto.value = (int_zero(scale_factor * 2274 * 25.4 * 10 ) / 10).toLocaleString('id-ID');
    form.r_pluto.value = (int_zero(scale_factor * 5913000000 * .0254 * 1000 ) / 1000).toLocaleString('id-ID');
    
    form.r_acentauri.value = (int_zero(scale_factor * 4.03964E+13 * .0000254 * 10 ) / 10).toLocaleString('id-ID');
    form.r_sirius.value  = (int_zero(scale_factor * 8.17388E+13 * .0000254 * 10 ) / 10).toLocaleString('id-ID');
    }      
</script>

<hr>
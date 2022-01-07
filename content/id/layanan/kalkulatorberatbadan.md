---
title: Berat Badan di Dunia yang Lain
date: 2021-03-15T00:00:00.000
lastmod: 2021-09-02T00:00:00.000
toc: true
type: docs
draft: false
linktitle: Kalkulator Berat Badan
menu:
  layanan:
    parent: Materi Edukasi Astronomi
    weight: 3
---

Saat ada di planet lain, berat/bobot (atau *weight*) Anda dapat sangat berbeda dengan saat di permukaan Bumi. Seberapa tinggi Anda dapat melompat sedikit banyak bergantung kepada berapa berat Anda di tempat tersebut, semakin ringan berat Anda semakin tinggi Anda bisa melompat. Berat Anda di sebuah planet adalah hasil dari massa dan kekuatan gravitasi di planet tersebut. 

Dengan kalkulator ini, temukan berapa berat Anda di planet atau objek lain di Tata Surya. Masukkan **besaran berat badan (angka yang ditunjukkan di timbangan badan)** Anda pada kolom di bawah dan klik **hitung** . Lihatlah bagaimana beragamnya berat Anda di tempat-tempat tersebut.

<hr>
<form id="WeightCalcForm"
    name="WeightCalcForm">
Berat badan Anda <input name="x"
        size="18"
        type="text"> <input onclick="Calculate(document.WeightCalcForm)"
        type="button"
        value="Hitung!">
<hr>
<table border="0"
        cellpadding="2"
        cellspacing="2"
        width="100%">
    <tbody style="width: 100%; display: table;;">
    <tr>
        <td valign="middle">
        <div align="left">
            <strong>Planet Tata Surya</strong>
        </div>
        </td>
        <td valign="middle">
        <div align="left">
            <strong>Berat Skala</strong>
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Merkurius</td>
        <td valign="middle">
        <div align="left">
            <input name="mercury"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Venus</td>
        <td valign="middle">
        <div align="left">
            <input name="venus"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Bumi</td>
        <td valign="middle">
        <div align="left">
            <input name="earth"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Mars</td>
        <td valign="middle">
        <div align="left">
            <input name="mars"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Jupiter</td>
        <td valign="middle">
        <div align="left">
            <input name="jupiter"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Saturnus</td>
        <td valign="middle">
        <div align="left">
            <input name="saturn"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Uranus</td>
        <td valign="middle">
        <div align="left">
            <input name="uranus"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Neptunus</td>
        <td valign="middle">
        <div align="left">
            <input name="neptune"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle"><strong>Objek lain</strong></td>
        <td valign="middle"></td>
    </tr>
    <tr>
        <td valign="middle">Bulan</td>
        <td valign="middle">
        <div align="left">
            <input name="moon"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Europa (satelit Jupiter)</td>
        <td valign="middle">
        <div align="left">
            <input name="europa"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Titan (satelit Saturnus)</td>
        <td valign="middle">
        <div align="left">
            <input name="titan"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Matahari</td>
        <td valign="middle">
        <div align="left">
            <input name="sun"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Bintang katai putih</td>
        <td valign="middle">
        <div align="left">
            <input name="wdwarf"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    <tr>
        <td valign="middle">Bintang Neutron</td>
        <td valign="middle">
        <div align="left">
            <input name="neutron"
                readonly
                size="18"
                type="text"
                value="">
        </div>
        </td>
    </tr>
    </tbody>
</table>
</form>

<script type="text/javascript">
function int_zero(x){
    if ( x < 1 )
        return 0 ;
    else
        return parseInt( x ,10 );
}
function Calculate(form) {
var b = form.x.value;
    if ( b != 0) {
        form.mercury.value=(int_zero(10*b*.378)/10).toLocaleString('id-ID');
        form.venus.value=(int_zero(10*b*.907)/10).toLocaleString('id-ID');
        form.earth.value=(b).toLocaleString('id-ID');
        form.mars.value=(int_zero(10*b*.377)/10).toLocaleString('id-ID');
        form.jupiter.value=(int_zero(10*b*2.528)/10).toLocaleString('id-ID');
        form.saturn.value=(int_zero(10*b*1.064)/10).toLocaleString('id-ID');
        form.uranus.value=(int_zero(10*b*.889)/10).toLocaleString('id-ID');
        form.neptune.value=(int_zero(10*b*1.125)/10).toLocaleString('id-ID');

        form.moon.value=(int_zero(10*b*.166)/10).toLocaleString('id-ID');
        form.europa.value=(int_zero(100*b*.13358)/100).toLocaleString('id-ID');
        form.titan.value=(int_zero(10*b*.138)/10).toLocaleString('id-ID');
        form.sun.value=(int_zero(10*b*27.072)/10).toLocaleString('id-ID');
        form.wdwarf.value=(int_zero(10*b*13e5)/10).toLocaleString('id-ID');
        form.neutron.value=(int_zero(14e10*b)).toLocaleString('id-ID');
    }
}
</script>
<hr>

## Apa yang terjadi?

Massa berbeda dengan berat. Massa adalah banyaknya materi yang terkandung dalam suatu benda sehingga sifatnya tidak berubah dimanapun objek berada. Berat, di lain sisi, akan berkaitan dengan gaya tarik/gravitasi objek. Setiap objek bermassa di alam semesta akan menarik objek bermassa lain. Besarnya gaya tarikan akan bergantung kepada massa masing-masing objek dan jarak keduanya. Apakah kita sedang dalam pengaruh gaya gravitasi? Tentu, besarnya akan bergantung kepada objek lain yang menjadi referensi. Besar gaya antara kita dengan objek-objek di sekeliling kita sehari-sehari terlalu kecil, namun, bila kita bandingkan gaya antara kita dengan objek bermassa besar seperti Bumi, maka besarnya gaya akan menjadi signifikan. 

Berat badan Anda di sebuah objek merupakan besarnya tarikan gravitasi antara badan Anda dengan objek di mana Anda berdiri. Hal ini akan bergantung kepada massa Anda, massa objek dimana Anda berdiri, dan jarak Anda terhadap pusat objek tersebut. Semakin besar massa Anda, semakin besar tarikan gravitasi yang Anda rasakan, begitu pula bila semakin besar massa planet tempat Anda berdiri, semakin besar tarikan gravitasi yang Anda rasakan. Sementara itu semakin jauh jarak Anda dari pusat planet, semakin lemah tarikan antara planet dan tubuh Anda. Kekuatan tarikan gravitasi akan berkurang sangat jauh bila kita memperbesar jarak antara kedua objek. Jika Anda menggandakan jarak dari planet, gaya menjadi seperempat. Gaya turun dengan kuadrat jarak. 

Bila kita masukan dalam persamaan, akan terlihat seperti ini:

$$ F \sim \frac{Mm}{r^2}$$
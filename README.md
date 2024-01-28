# Credit Risk Prediction

<h3>Overview</h3>
<h6>
Sebuah perusahaan pembiayaan di Indonesia ingin mengetahui potensi kelayakan klien yang akan mengajukan credit, juga ingin mengetahui apa yang membuat klien berpotensi atau tidak berpotensi memiliki kredit macet kedepannya. Sehingga dalam hal ini, tim Data Science diminta untuk membuat model data yang dapat memprediksi potensi kelayakan klien dan menemukan pola data yang dapat digunakan untuk tim mereka dalam membuat rencana jika ada klien yang cukup beresiko tetapi perusahaan ingin mengambil resiko tersebut.
</h6>

<h3>Data Understanding</h3>
<h6>
  Dataset yang digunakan yaitu:
  Application_train & application_test: data train dan test utama dengan informasi tentang setiap aplikasi pinjaman di Home Credit. Setiap pinjaman memiliki baris sendiri dan diidentifikasi oleh kolom. Dataset dilengkapi dengan yang menunjukkan: SK_ID_CURRTARGET
      <ul>
        <li>0: Klien yang tidak memiliki kesulitan pembayaran</li>
        <li>1: Klien yang memiliki kesulitan pembayaran</li>
      </ul>
</h6>

<h3>Data Preprocessing</h3>
<h6>
  <ul>
    <li>Dilakukan normalisasi dan standarization pada feature numeric</li>
    <li>Dilakukan label encoding pada fitur education type</li>
    <li>Dilakukan one-hot encoding pada semua fitur categorical selain fitur education type</li>
  </ul>
</h6>

<h3>Modelling</h3>
<h6>
  Pembuatan model ini menggunakan beberapa algoritma untuk menentukan model dengan algoritma mana yang dapat memberikan prediksi terbaik dan pemodelan ini fokus terhadap metric Recall untuk membuat nilai false negatif tidak terlalu besar, dimana nilai false negatif merupakan klien yang berpotensi gagal bayar tetapi diprediksi oleh model tidak akan gagal bayar.
</h6>

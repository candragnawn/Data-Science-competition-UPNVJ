<h1>Analisis Tren Penjualan FMCG Personal Care (2020–2025)</h1>

<h2>Pendahuluan</h2>
<p>
Proyek ini bertujuan untuk melakukan analisis mendalam terhadap data penjualan produk FMCG (Fast-Moving Consumer Goods) kategori Personal Care dalam rentang waktu 2020 hingga 2025. Analisis ini mencakup:
</p>
<ul>
  <li>Pemodelan data</li>
  <li>Innovation radar</li>
  <li>Peramalan tren (trend forecasting)</li>
  <li>Analisis kanibalisasi produk (product cannibalization)</li>
</ul>

<hr>

<h2>Atribut Dataset</h2>
<p>Dataset utama yang digunakan terdiri dari empat file:</p>

<h3>1. products.csv</h3>
<p>Informasi dasar produk seperti ID, nama, brand (Sunsilk, Dove, Clear, dll.), tipe kategori, ukuran (ml), harga dasar, dan tanggal peluncuran.</p>

<h3>2. sales.csv</h3>
<p>Detail transaksi yang mencakup tanggal, wilayah, kanal penjualan (Shopee, Tokopedia, Indomaret, dll.), unit terjual, pendapatan (revenue), dan diskon.</p>

<h3>3. marketing.csv</h3>
<p>Data kampanye pemasaran, anggaran (IDR), kanal kampanye, dan tingkat keterlibatan (engagement rate).</p>

<h3>4. reviews.csv</h3>
<p>Ulasan pelanggan, skor rating, sentimen (Positif/Netral/Negatif), dan platform ulasan.</p>

<hr>

<h2>Tahapan Proyek</h2>
<p>Secara garis besar, analisis dilakukan melalui langkah-langkah berikut:</p>
<ul>
  <li><strong>Persiapan Data</strong>: Mengimpor library (Pandas, NumPy, dll.) dan memuat dataset.</li>
  <li><strong>Data Understanding</strong>: Eksplorasi struktur data, pengecekan nilai kosong, dan statistik ringkasan.</li>
  <li><strong>Penggabungan Data</strong>: Mengintegrasikan data penjualan dengan informasi produk untuk melihat performa per brand.</li>
  <li><strong>Analisis Brand</strong>: Menyusun ringkasan total pendapatan, unit terjual, dan jumlah produk unik.</li>
</ul>

<hr>

<h2>Teknologi yang Digunakan</h2>
<ul>
  <li><strong>Bahasa Pemrograman</strong>: Python</li>
  <li><strong>Analisis & Statistik</strong>: pandas, numpy, sklearn, statsmodels, scipy</li>
  <li><strong>Visualisasi</strong>: matplotlib, seaborn, wordcloud</li>
  <li><strong>Platform</strong>: Google Colab</li>
</ul>

<hr>

<h2>Ringkasan Temuan Awal</h2>
<p>
Analisis melibatkan brand seperti Clear, Dove, Lifebuoy, Love Beauty & Planet, Ponds, Rexona, Sunsilk, dan Vaseline. Ditemukan bahwa brand seperti Dove dan Sunsilk memberikan kontribusi pendapatan terbesar dengan jumlah variasi produk yang lebih banyak dibandingkan brand lainnya.
</p>

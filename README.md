Analisis Tren Penjualan FMCG Personal Care (2020–2025)
Pendahuluan
Proyek ini bertujuan untuk melakukan analisis mendalam terhadap data penjualan produk FMCG (Fast-Moving Consumer Goods) kategori Personal Care dalam rentang waktu 2020 hingga 2025. Analisis ini mencakup pemodelan data, inovation radar, peramalan tren (trend forecasting), serta analisis kanibalisasi produk (product cannibalization).

Atribut Dataset
Dataset yang digunakan dalam analisis ini terdiri dari empat file utama:

products.csv: Berisi informasi produk seperti ID produk, nama, brand (Sunsilk, Dove, Clear, dll.), tipe kategori, ukuran (ml), harga dasar, dan tanggal peluncuran.

sales.csv: Berisi detail transaksi termasuk ID transaksi, tanggal (2020-2025), wilayah, kanal penjualan (Shopee, Tokopedia, Indomaret, dll.), unit terjual, harga rata-rata, diskon, pendapatan (revenue), dan selisih hari sejak peluncuran.

marketing.csv: Informasi mengenai kampanye pemasaran, anggaran (IDR), kanal kampanye, dan tingkat keterlibatan (engagement rate).

reviews.csv: Berisi ulasan pelanggan, skor rating, sentimen (Positif/Netral/Negatif), teks ulasan, platform, dan tanggal ulasan.

Tahapan Proyek
Secara garis besar, notebook ini melakukan langkah-langkah berikut:

Persiapan Data: Mengimpor library yang diperlukan (Pandas, NumPy, Scikit-learn, Statsmodels, dll.) dan mengunduh dataset dari sumber eksternal.

Data Understanding: Melakukan eksplorasi struktur data, pengecekan nilai kosong, statistik ringkasan, serta verifikasi konsistensi ID produk di seluruh tabel.

Penggabungan Data: Mengintegrasikan data penjualan dengan informasi produk untuk mendapatkan gambaran performa berdasarkan brand dan tipe produk.

Analisis Brand: Menyusun ringkasan performa per brand yang mencakup total pendapatan, total unit terjual, jumlah produk unik, dan harga rata-rata.

Teknologi yang Digunakan
Bahasa Pemrograman: Python

Library Utama:

Analisis Data: pandas, numpy

Visualisasi: matplotlib, seaborn, wordcloud

Machine Learning & Statistik: sklearn, statsmodels, scipy

Platform: Google Colab

Ringkasan Temuan Awal
Berdasarkan data yang diproses, brand yang terlibat dalam analisis ini meliputi Clear, Dove, Lifebuoy, Love Beauty & Planet, Ponds, Rexona, Sunsilk, dan Vaseline. Analisis menunjukkan variasi performa yang signifikan antar brand, di mana brand seperti Dove dan Sunsilk memiliki kontribusi pendapatan yang besar dengan jumlah produk yang lebih banyak dibandingkan brand lain.

Analisis Tren Penjualan FMCG Personal Care (2020–2025)
Pendahuluan
Proyek ini bertujuan untuk melakukan analisis mendalam terhadap data penjualan produk FMCG (Fast-Moving Consumer Goods) kategori Personal Care dalam rentang waktu 2020 hingga 2025. Analisis ini mencakup:

Pemodelan data

Innovation radar

Peramalan tren (trend forecasting)

Analisis kanibalisasi produk (product cannibalization)

Atribut Dataset
Dataset utama yang digunakan terdiri dari empat file:

1. products.csv
Informasi dasar produk seperti ID, nama, brand (Sunsilk, Dove, Clear, dll.), tipe kategori, ukuran (ml), harga dasar, dan tanggal peluncuran.

2. sales.csv
Detail transaksi yang mencakup tanggal, wilayah, kanal penjualan (Shopee, Tokopedia, Indomaret, dll.), unit terjual, pendapatan (revenue), dan diskon.

3. marketing.csv
Data kampanye pemasaran, anggaran (IDR), kanal kampanye, dan tingkat keterlibatan (engagement rate).

4. reviews.csv
Ulasan pelanggan, skor rating, sentimen (Positif/Netral/Negatif), dan platform ulasan.

Tahapan Proyek
Secara garis besar, analisis dilakukan melalui langkah-langkah berikut:

Persiapan Data: Mengimpor library (Pandas, NumPy, dll.) dan memuat dataset.

Data Understanding: Eksplorasi struktur data, pengecekan nilai kosong, dan statistik ringkasan.

Penggabungan Data: Mengintegrasikan data penjualan dengan informasi produk untuk melihat performa per brand.

Analisis Brand: Menyusun ringkasan total pendapatan, unit terjual, dan jumlah produk unik.

Teknologi yang Digunakan
Bahasa Pemrograman: Python

Analisis & Statistik: pandas, numpy, sklearn, statsmodels, scipy

Visualisasi: matplotlib, seaborn, wordcloud

Platform: Google Colab

Ringkasan Temuan Awal
Analisis melibatkan brand seperti Clear, Dove, Lifebuoy, Love Beauty & Planet, Ponds, Rexona, Sunsilk, dan Vaseline. Ditemukan bahwa brand seperti Dove dan Sunsilk memberikan kontribusi pendapatan terbesar dengan jumlah variasi produk yang lebih banyak dibandingkan brand lainnya.

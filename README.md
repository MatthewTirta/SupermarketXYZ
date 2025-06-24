# Analisis Supermarket XYZ - Capstone

## Overview

Proyek ini bertujuan untuk menganalisis dataset supermarket untuk memahami kinerja perusahaan dan perilaku pelanggan berdasarkan empat kategori utama: **Pelanggan**, **Produk**, **Kampanye**, dan **Tempat**.

## Perumusan Masalah

Supermarket menghadapi penurunan penjualan, dan analisis ini bertujuan untuk mengidentifikasi penyebabnya melalui empat kategori berikut:

1. **Pelanggan**: Memahami bagaimana karakteristik pelanggan memengaruhi pola pembelian mereka.
2. **Produk**: Mengidentifikasi produk yang paling populer dan hubungannya dengan pelanggan atau promosi.
3. **Kampanye**: Mengevaluasi seberapa efektif kampanye pemasaran yang dilakukan.
4. **Tempat/Saluran Penjualan**: Membandingkan perilaku pembelian di berbagai saluran penjualan (toko fisik, web, dan katalog).

## Pembersihan Data

- Terdapat 24 Missing value pada Column “INCOME” maka dari itu kita harus meremove 24 data dari dataset agar dataset lebih Clean dan dapat digunakan.
- Kolom-kolom yang relevan telah dipivot dan dibersihkan untuk memastikan tipe data yang tepat untuk analisis lebih lanjut.
  
## Analysis yang dilakukan

- **Pelanggan**: Profil pelanggan berdasarkan pola pembelian mereka untuk segmentasi yang lebih efektif.
- **Saluran Penjualan**: Perbandingan pengeluaran rata-rata di berbagai saluran penjualan seperti web, toko fisik, katalog, dan promo (deals).
- **Kampanye Pemasaran**: Menilai dampak kampanye pemasaran terhadap pengeluaran pelanggan.

## Insights and Recommendations

### **Rata-rata Pengeluaran per Pembelian**
- **Deals**: Menunjukkan pengeluaran tertinggi per pembelian (411.59), yang kemungkinan disebabkan oleh pembelian produk bernilai tinggi saat ada diskon atau promosi.
- **Catalog**: Rata-rata pengeluaran per pembelian (238.61), menunjukkan bahwa pelanggan cenderung membeli lebih banyak atau lebih mahal melalui katalog.
- **Web**: Pengeluaran rata-rata per pembelian lebih rendah (139.99), tetapi masih lebih tinggi dari **Store**.
- **Store**: Rata-rata pengeluaran per pembelian terendah (90.44), mencerminkan pembelian dengan harga lebih rendah atau dalam jumlah kecil.

### **Rata-rata Jumlah Pembelian**
- **Store**: Memiliki rata-rata jumlah pembelian tertinggi (5.80), meskipun pengeluaran per transaksi rendah.
- **Web**: Menyusul di posisi kedua dengan rata-rata jumlah pembelian (4.09).
- **Catalog** dan **Deals**: Mempunyai jumlah pembelian lebih rendah (2.67 dan 2.32), menunjukkan transaksi yang lebih jarang melalui kedua saluran ini.

### **Rekomendasi Tindakan**
1. **Store**: Fokus pada peningkatan nilai transaksi rata-rata melalui penempatan produk berharga tinggi dan program loyalitas.
2. **Deals & Catalog**: Pertimbangkan promosi eksklusif dan penawaran khusus untuk saluran ini, mengingat pengeluaran per transaksi yang tinggi.
3. **Web**: Tingkatkan pengalaman pengguna dan personalisasi penawaran untuk meningkatkan pengeluaran rata-rata per kunjungan.
4. **Analisis Lebih Lanjut**: Profilkan pelanggan yang berbelanja melalui **Deals** dan **Catalog** untuk menargetkan promosi lebih efektif.



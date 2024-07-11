# CapstoneProject2
# Analisis Supermarket Customers

## Gambaran Proyek

Proyek ini melibatkan analisis data pelanggan supermarket untuk mendapatkan wawasan tentang perilaku dan demografi pelanggan. Analisis ini berfokus pada mengidentifikasi anomali, memahami faktor demografi, segmentasi pelanggan berdasarkan perilaku pembelian, dan memberikan rekomendasi yang dapat ditindaklanjuti.

## Pertanyaan yang Akan Dijawab

1. **Bagaimana distribusi usia pelanggan?**
   - Analisis ini akan melihat distribusi usia pelanggan untuk memahami rentang usia mana yang paling dominan di antara pelanggan supermarket.

2. **Bagaimana distribusi pelanggan berdasarkan kelompok usia?**
   - Kami akan mengelompokkan pelanggan ke dalam kategori `Dewasa`, `Paruh Baya`, dan `Lansia` untuk melihat distribusi pelanggan di setiap kelompok usia.

3. **Berapa rata-rata pengeluaran pelanggan untuk setiap kategori produk?**
   - Kami akan menghitung dan memvisualisasikan rata-rata pengeluaran pelanggan untuk berbagai kategori produk seperti wine, buah, daging, ikan, permen, dan emas.

4. **Bagaimana total pengeluaran untuk setiap kategori produk berdasarkan kelompok usia?**
   - Analisis ini akan menunjukkan total pengeluaran di setiap kategori produk berdasarkan kelompok usia pelanggan.

5. **Bagaimana segmentasi pelanggan berdasarkan pendapatan dan pengeluaran mereka?**
   - Kami akan membuat segmentasi pelanggan berdasarkan pendapatan mereka dan pengeluaran di berbagai kategori produk untuk memahami kelompok pelanggan yang berbeda.
     
## Persiapan Data

### Pembersihan Data dan Penanganan Anomali
1. **Nilai Hilang:**
   - Kolom numerik dengan nilai hilang diisi menggunakan median dari kolom yang bersangkutan.
   - Analisis deskriptif dilakukan untuk memahami dampak nilai hilang.

2. **Outlier:**
   - Outlier diidentifikasi menggunakan metode Interquartile Range (IQR) dan ditangani dengan tepat.

3. **Format Data:**
   - Memastikan semua format tanggal konsisten dan dikonversi ke format datetime yang sesuai.

4. **Duplikasi Data:**
   - Rekor duplikat diidentifikasi dan dihapus untuk menjaga integritas data.

### Penambahan Kolom Usia
- Kolom `Usia` dihitung berdasarkan kolom `Tahun_Lahir` untuk memfasilitasi analisis demografi.

## Analisis dan Visualisasi

### Analisis Demografi
1. **Distribusi Usia:**
   - Membuat histogram untuk memvisualisasikan distribusi usia pelanggan.

2. **Distribusi Kelompok Usia:**
   - Mengelompokkan pelanggan menjadi `Adult`, `Midle-Aged`, dan `Elderly`.
   - Membuat diagram batang untuk memvisualisasikan distribusi kelompok usia ini.

3. **Rata-rata Pengeluaran per Kategori Produk:**
   - Membuat diagram batang horizontal untuk menunjukkan rata-rata pengeluaran di berbagai kategori produk.

4. **Total Pengeluaran Berdasarkan Kelompok Usia:**
   - Membuat diagram batang bertumpuk untuk menunjukkan total pengeluaran di setiap kategori produk berdasarkan kelompok usia.

### Segmentasi Perilaku
1. **Segmentasi Pendapatan vs Pengeluaran:**
   - Membuat Diagram batang untuk mengelompokkan pelanggan berdasarkan pendapatan dan pengeluaran mereka di berbagai kategori produk menggunakan clustering K-Means.

2. **Segmentasi Frekuensi Pembelian:**
   - Membuat Diagram batang untuk mengelompokkan pelanggan berdasarkan frekuensi pembelian online dan di toko fisik.

### Visualisasi
- Mengembangkan berbagai visualisasi termasuk diagram pie, diagram batang menggunakan Tableau untuk memberikan tampilan interaktif dan komprehensif dari data.

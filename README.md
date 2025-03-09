# Analisis RFM dalam Meningkatkan Loyalitas dan Profitabilitas Pelanggan

## Deskripsi
Repositori ini berisi analisis **Recency, Frequency, and Monetary (RFM)** untuk memahami pola transaksi pelanggan dan meningkatkan loyalitas serta profitabilitas mereka. Analisis ini dilakukan dengan menggunakan dataset transaksi pelanggan untuk mengidentifikasi pelanggan bernilai tinggi serta merancang strategi pemasaran yang lebih efektif.

## Tujuan Analisis RFM
Analisis ini bertujuan untuk:
1. Mengelompokkan pelanggan berdasarkan pola transaksi mereka.
2. Meningkatkan loyalitas pelanggan melalui strategi pemasaran yang lebih personal.
3. Mengoptimalkan program promosi dengan menargetkan pelanggan yang memiliki nilai tinggi.
4. Memaksimalkan profitabilitas dengan fokus pada pelanggan yang paling sering bertransaksi.

## Dataset
Dataset yang digunakan terdiri dari:
- **Jumlah transaksi**: 20.000 transaksi unik
- **Jumlah pelanggan**: 3.494 pelanggan
- **Fitur utama**: Tanggal transaksi, jumlah transaksi, dan nilai transaksi per pelanggan

## Metodologi Analisis RFM
1. **Recency**: Mengukur seberapa baru pelanggan melakukan transaksi terakhir.
2. **Frequency**: Menghitung jumlah transaksi yang dilakukan oleh setiap pelanggan dalam periode analisis.
3. **Monetary**: Mengukur total nilai transaksi yang dilakukan oleh pelanggan.
4. **Scoring**: Pelanggan diberi skor berdasarkan nilai RFM mereka untuk segmentasi yang lebih spesifik.

## Hasil Analisis
- **Distribusi pelanggan berdasarkan Recency, Frequency, dan Monetary** ditampilkan dalam bentuk histogram.
- **Segmentasi pelanggan berdasarkan skor RFM** dikategorikan ke dalam beberapa kelompok, seperti:
  - Champions
  - Loyal Customers
  - Potential Loyalists
  - Promising
  - At Risk
  - Lost
- **Analisis per brand** menunjukkan perbedaan jumlah pelanggan dan total transaksi pada masing-masing brand.

## Diagram dan Visualisasi
Visualisasi yang digunakan dalam analisis ini:
- Histogram distribusi Recency, Frequency, dan Monetary
- Diagram segmentasi pelanggan berdasarkan skor RFM
- Grafik jumlah pelanggan per brand dan total uang yang dikeluarkan per brand

## Cara Menggunakan Repositori
1. Clone repositori:
   ```bash
   git clone https://github.com/username/analisis-rfm.git
   ```
2. Instal dependensi yang diperlukan:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan analisis dengan script Python:
   ```bash
   python rfm_analysis.py
   ```
4. Lihat hasil analisis dalam bentuk visualisasi dan laporan.

## Kontribusi
Kontribusi terbuka untuk perbaikan dan pengembangan lebih lanjut. Silakan lakukan **fork** dan **pull request** jika ingin menambahkan fitur baru atau meningkatkan analisis.

## Lisensi
Repositori ini dilisensikan di bawah lisensi **MIT**.


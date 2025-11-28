# TUGAS BESAR-ADS-Kelompok 8-RC

📘 **Deskripsi**

Akses internet merupakan kebutuhan utama bagi mahasiswa dalam kegiatan akademik seperti perkuliahan daring, pencarian literatur, maupun pengumpulan tugas. Namun, kualitas internet dapat berbeda berdasarkan jenis tempat tinggal, seperti kos, rumah pribadi, kontrakan, atau asrama.

Perbedaan kondisi geografis, ketersediaan penyedia layanan, serta infrastruktur jaringan dapat menyebabkan variasi kualitas internet.  
Penelitian ini bertujuan untuk mengetahui apakah jenis tempat tinggal memiliki hubungan dan pengaruh signifikan terhadap kualitas akses internet mahasiswa.

---

⚙️ **Metode Penelitian**

Jenis penelitian: *Kuantitatif deskriptif dan inferensial*  
Data: Skor kualitas internet (kecepatan, stabilitas, latency) dari responden mahasiswa.  

**Variabel:**  
- X = Jenis tempat tinggal (kos, rumah, asrama, kontrakan)  
- Y = Kualitas akses internet  

**Metode Statistik:**  
Karena data tidak memenuhi asumsi normalitas, digunakan uji nonparametrik:  
- Uji **Kruskal–Wallis** → melihat perbedaan kualitas internet antar kategori tempat tinggal  
- Uji **Spearman Rank** → melihat hubungan antara jenis tempat tinggal dan kualitas internet  

**Alat Analisis:** Excel / R  
**Grafik yang Digunakan:** barplot, grafik bertumpuk, heatmap  

---

📑 **Penjelasan Singkat Dataset**

Dataset mencakup:

- 🏠 **Jenis tempat tinggal mahasiswa**  
  (kos, tinggal bersama orang tua, rumah mengontrak pribadi, rumah mengontrak bersama, asrama)

- 🌐 **Jenis akses internet**  
  (paket data seluler, Wi-Fi pribadi, fasilitas kampus, lainnya)

- 🎯 **Tujuan penelitian**  
  Mengetahui hubungan dan pengaruh jenis tempat tinggal terhadap kualitas akses internet mahasiswa.

---

🚀 **Cara menjalankan script**

- Load library
- Baca dataset
- Bersihkan nama kolom
- Bersihkan data (jika ada missing values)
- Buat statistik deskriptif (tabel frekuensi dan tabel kontingensi)
- Buat barplot
- Uji chi-square
- Buat mosaic plot
- Analisis post-hoc (jika chi-square signifikan)
- Buat proporsi persentase
- Bandingkan proporsi
- Simpulkan hasil akhir


📦 **Paket R yang Digunakan**

```r
library(readxl)
library(dplyr)
library(ggplot2)
```

📁 **Struktur Repository**

```
📁 project/
│
├── 📂 Data hasil olahan/
│     │──  Dataset_output.csv
│     │──  Distribusi akses internet.png
│     │──  Distribusi Hasil.png
│     │──  Heatmap hubungan akses internet.png
│     │──  Hubungan akses internet dan tempat tinggal.png
│     └──  Ringkasan Statistik.txt
│
├── 📂 poster/
│     └──  Poster_8_RC.pdf
│
├── 📂 script R/
│     └──  codeR_8_RC.Rmd
│
└── 📘 README.md

```



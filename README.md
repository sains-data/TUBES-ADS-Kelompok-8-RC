# TUBES-ADS-Kelompok 8-RC

📘# Deskripsi

Akses internet merupakan kebutuhan utama bagi mahasiswa dalam kegiatan akademik seperti perkuliahan daring, pencarian literatur, maupun pengumpulan tugas. Namun, kualitas internet dapat berbeda berdasarkan jenis tempat tinggal, seperti kos, rumah pribadi, atau asrama.
Perbedaan kondisi geografis, ketersediaan penyedia layanan, serta infrastruktur jaringan dapat menyebabkan variasi kualitas internet.
Penelitian ini bertujuan untuk mengetahui apakah jenis tempat tinggal memiliki hubungan dan pengaruh signifikan terhadap kualitas akses internet mahasiswa.

⚙️ # Metode Penelitian

Jenis penelitian: Kuantitatif deskriptif dan inferensial.
Data: Skor kualitas internet (kecepatan, stabilitas, latency) dari responden mahasiswa.
**Variabel**:
X = Jenis tempat tinggal (kos, rumah, asrama, kontrakan)
Y = Kualitas akses internet
**Metode Statistik**:
Karena data tidak memenuhi asumsi normalitas, digunakan uji nonparametrik, yaitu:
Uji Kruskal–Wallis untuk melihat perbedaan kualitas internet berdasarkan beberapa kategori tempat tinggal.
Uji Spearman Rank untuk melihat hubungan antara jenis tempat tinggal dan kualitas internet.
Alat Analisis: Excel/R
Grafik yang digunakan: barplot, grafik bertumpuk, dan headmap.

📑 ## Penjelasan Singkat Dataset

Dataset mencakup:
🏠 **Jenis tempat tinggal mahasiswa**
(kos, tinggal bersama orang tua, rumah mengontrak pribadi, rumah mengontrak bersama, asrama)
🌐 **Jenis akses internet**
(paket data seluler, Wi-Fi pribadi, fasilitas kampus, lainnya) 
🎯 **Tujuan penelitian**:
Mengetahui hubungan dan pengaruh jenis tempat tinggal terhadap kualitas akses internet mahasiswa.

📦 ## Paket R yang Dipakai

library(readxl)
library(dplyr)
library(ggplot2)

📁 Struktur Repository
'''r
📁 project/
│
│── 📄 Dataset_output.csv
│── 🖼️ Distribusi akses internet.png
│── 🖼️ Distribusi Hasil.png
│── 🖼️ Heatmap hubungan akses internet.png
│── 🖼️ Hubungan akses internet dan tempat tinggal.png
│── 📄 Ringkasan Statistik.txt
│
├── 📂 script R/
│     └── 📝 codeR_8_RC.Rmd
│
└── 📘 README.md

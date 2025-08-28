# Analisis Regresi Penjualan Clothing Store (Model Linier)

Proyek ini dibuat untuk mata kuliah **Model Linier (MoLin)** dan menganalisis faktor-faktor  
yang memengaruhi pengeluaran tahunan pelanggan di sebuah Clothing Store di New York.  
Analisis dilakukan dengan **regresi linier berganda dengan interaksi** untuk mengidentifikasi  
variabel yang paling berpengaruh serta memberikan rekomendasi strategi bisnis.

## 🔹 Latar Belakang
Perusahaan ingin memahami apakah platform online (aplikasi, website) serta membership  
memiliki peran signifikan terhadap penjualan tahunan. Dengan mengetahui variabel yang paling berdampak,  
perusahaan dapat memperbaiki area yang lemah dan memperkuat area yang sudah baik.

## 🔹 Tujuan
- Membuat model regresi untuk mengidentifikasi prediktor signifikan terhadap pengeluaran tahunan.  
- Memberikan insight dan rekomendasi strategi untuk meningkatkan pendapatan secara konsisten.  
- Menjadikan model sebagai alat evaluasi tren pendapatan di masa depan.  

## 🔹 Detail
- **Dataset**: Data pelanggan Clothing Store  
- **Variabel**:  
  - `Time on App`  
  - `Time on Website`  
  - `Length of Membership`  
  - `Yearly Amount Spent` (target)  
- **Metode**: Regresi Linier Berganda dengan interaksi  
- **Tools**: R, RStudio, SmartPLS  

## 🔹 Hasil & Insight
Model akhir:  

\[
Y = 281.0190 - 12.0441 \times Website + 60.4242 \times Membership + 1.0100 \times (App \times Website) + \varepsilon
\]

Insight utama:  
- **Membership**: Berpengaruh positif kuat → semakin lama membership, semakin tinggi pengeluaran tahunan.  
- **App**: Memberi dampak positif, terutama jika dikombinasikan dengan Website.  
- **Website**: Sendiri berdampak negatif, tetapi bisa berubah positif bila penggunaan App meningkat.  

## 🔹 Rekomendasi
- **Tingkatkan kualitas App**: Perbaikan UX/UI, navigasi, dan engagement agar pelanggan betah.  
- **Perkuat program Membership**: Buat program loyalitas (diskon, hadiah, akses eksklusif) untuk retensi pelanggan.  
- **Optimalkan Website**: Perbaiki tampilan dan pengalaman pengguna agar dampak Website lebih positif.  
- **Gunakan model sebagai alat monitoring**: Bandingkan pendapatan aktual dengan prediksi model untuk memantau tren.  

📄 [Klik untuk melihat laporan lengkap](https://drive.google.com/file/d/1KucagtCB_tEpvQjui3FIKd0bDtkbTx1R/view?usp=sharing)

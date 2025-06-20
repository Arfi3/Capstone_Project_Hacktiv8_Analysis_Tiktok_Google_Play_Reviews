#  🤳🏻Capstone Project (Tiktok Review Analysis) 📊


---

## 🔍 Project Overview
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/a/a9/TikTok_logo.svg" alt="Logo TikTok" width="150">
</div>

Proyek ini bertujuan untuk mengolah dan menganalisis ulasan pengguna aplikasi TikTok yang bersumber dari dataset publik di Kaggle. Dengan memanfaatkan model kecerdasan buatan IBM Granite, dilakukan analisis sentimen untuk mengidentifikasi persepsi pengguna terhadap berbagai aspek aplikasi. Fokus utama analisis ini adalah mengeksplorasi area-area yang dipandang positif maupun negatif oleh pengguna, serta menyusun rekomendasi berbasis data yang dapat dimanfaatkan oleh pengembang untuk meningkatkan fitur dan kualitas aplikasi.

---

## 📂 Raw Dataset
Dataset yang digunakan tersedia di repositori: 
[🔗 TikTok - Google Play Store Review](https://www.kaggle.com/datasets/shivkumarganesh/tiktok-google-play-store-review)

---

## Atribut
| Nama Kolom       | Deskripsi |
|------------|------|
| UserName       | Nama pengguna   |
| userImage    | Foto profil yang dimiliki pengguna   |
| content    | Ulasan yang dibuat oleh pengguna   |
| score    | Skor/rating antara 1 sampai 5   |
| thumbsUpCount    | Jumlah like yang diterima pengguna   |
| reviewCreatedVersion    | Nomor versi yang digunakan untuk membuat ulasan    |
| at    | Kapan ulasan dibuat   |
| replyContent    | Balasan ulasan dari perusahaan   |
| repliedAt    | Tanggal dan waktu balasan   |
| reviewId    | Kode unik   |
---


## 📌 Insights & Findings
### 🪄 Analisis Sentimen
- Mayoritas ulasan pengguna menunjukkan sentimen positif, yang menandakan tingkat kepuasan yang tinggi terhadap performa dan kualitas aplikasi.
- Sentimen negatif umumnya berkaitan dengan keluhan teknis, seperti:
  - Kesulitan dalam proses login.
  - Pembatasan akses akun.
  - Kompatibilitas aplikasi pada berbagai jenis perangkat.

### 🔍 Topik Utama yang Disoroti
- Beberapa topik yang paling sering dibahas dalam ulasan meliputi:
  - Fitur aplikasi.
  - Konten video yang tersedia.
  - Pengalaman penggunaan secara keseluruhan.
- Pengguna dengan sentimen positif umumnya menyoroti:
  - Kualitas video.
  - Kemudahan penggunaan fitur.
  - Kenyamanan antarmuka aplikasi.
- Pengguna dengan sentimen negatif menyoroti:
  - Masalah pada perangkat.
  - Proses login yang rumit.
  - Pembatasan atau kendala akses akun.

### 🔠 Temuan Visualisasi Wordcloud
- **Ulasan Positif**: Kata-kata seperti `"good"`, `"videos"`, `"nice"`, dan `"love"` mendominasi, yang menunjukkan bahwa banyak pengguna merasa puas terhadap konten dan fitur TikTok.
- **Ulasan Negatif**: Kata seperti `"device"`, `"let"`, dan `"login"` muncul lebih sering, menunjukkan adanya isu teknis dan hambatan akses yang perlu diperhatikan oleh pengembang.

---

##  🤖AI Support Explanation

Analisis ini dilakukan menggunakan model Large Language Model (LLM) dari IBM, yaitu Granite (granite-3.3-8b-instruct) yang diakses melalui layanan Replicate API. Model ini digunakan untuk:
- Mendeteksi sentimen (positive, negative, dan neutral)
- mengetahui fokus area dan keyword dari ulasan
- Mengklasifikasi permasalahan yang dikeluhkan pengguna
- Menyusun ringkasan secara otomatis dari ulasan
---

## 🚀 Let’s Connect!

If you’re also passionate about data science, feel free to connect or reach out to me on  [LinkedIn](https://www.linkedin.com/in/arfinadhifahananti/)!

## Analisis Ulasan Pelanggan GoFood di Twitter ##

## Project Overview
Proyek ini bertujuan untuk menganalisis ulasan pelanggan GoFood yang diperoleh dari media sosial. 
Dengan bantuan AI (Large Language Model), dilakukan klasifikasi sentimen, identifikasi kategori ulasan, peringkasan insight, 
hingga pembuatan rekomendasi berbasis data. 
Target pengguna dari hasil analisis ini adalah pihak manajemen layanan GoFood 
yang ingin memahami persepsi konsumen untuk meningkatkan kualitas layanan.

## Dataset
Dataset ulasan GoFood ini bersifat publik dan diperoleh dari Kaggle:
https://www.kaggle.com/datasets/muhammadhadi28/gofood-review-data-from-twitter?resource=download

## Insight & Findings

Berdasarkan hasil klasifikasi dan analisis terhadap lebih dari 100 ulasan:
- **Mayoritas ulasan bersentimen positif**, menunjukkan apresiasi terhadap kemudahan penggunaan aplikasi dan variasi menu yang ditawarkan.
- **Keluhan umum** meliputi harga yang dianggap tinggi, keterbatasan promo, serta kendala akun seperti soft-banned dan kesulitan menggunakan voucher.
- **Pelanggan menghargai fitur seperti split bill**, rekomendasi menu, serta keberagaman pilihan restoran lokal.

## AI Support Explanation

Model AI yang digunakan: `ibm-granite/granite-3.3-8b-instruct` dari Replicate, diakses melalui `LangChain`.

Aktivitas yang didukung AI:

- **Klasifikasi Sentimen & Kategori**  
  Untuk menandai ulasan sebagai *Positif, Negatif, atau Campuran* dan mengelompokkannya ke dalam tema
   seperti kualitas makanan, pengalaman pengguna, pembayaran, waktu pengiriman, atau ongkos kirim

- **Summarization (Peringkasan Insight)**  
  Model AI digunakan untuk membuat ringkasan naratif yang mencakup kesan umum, keluhan yang sering muncul, dan hal-hal yang disukai pelanggan.

- **Evaluasi & Rekomendasi Otomatis**  
  AI membantu menyusun poin evaluasi beserta saran perbaikan berdasarkan hasil analisis data yang diperoleh.

## Tools & Libraries

- Google Colab (Python)
- Pandas, Seaborn, Matplotlib
- LangChain
- Replicate API

## Output Akhir

- Klasifikasi Sentimen & Kategori Ulasan
- Ringkasan Insight Pelanggan
- Evaluasi dan Rekomendasi Strategis
- Visualisasi Distribusi Sentimen

## Visualisasi 
![visualisasi](https://github.com/user-attachments/assets/eabe18ef-841c-4cc6-a5dc-c120fed0e08d)




# 🛰️ Media Comments Scraping & Classification — Indonesia Flood Topic

Proyek ini bertujuan untuk mengumpulkan dan melakukan klasifikasi komentar publik terkait isu **banjir di Indonesia** dari berbagai platform media sosial, yaitu **YouTube, Twitter, dan TikTok**. Dataset hasil scraping selanjutnya digunakan untuk analisis opini publik mengenai isu lingkungan dan sosial.

---

## 📌 Tujuan Proyek

- Mengumpulkan data komentar real dari media sosial
- Melabeli komentar berdasarkan isu yang relevan
- Membersihkan teks dan menyiapkan dataset untuk text mining
- Menjadi dataset untuk penelitian terkait **bencana banjir** di Indonesia

---

## 📂 Struktur Direktori

```
indonesian-flood-text-mining/
│
├── Output/
│   ├── Comment_YT_Banjir.csv         # Hasil scraping YouTube
│   ├── Comment_Tweet_Banjir.csv      # Hasil scraping Twitter
│   ├── Comment_TikTok_Banjir.csv     # Hasil scraping TikTok
│
├── ScrapingWithYoutube.ipynb        # Notebook scraping YouTube
├── ScrapingWithTwitter.ipynb        # Notebook scraping Twitter
├── ScrapingWithTikTok.ipynb         # Notebook scraping TikTok
│
└── README.md
```

---

## 🛠️ Teknologi & Tools yang Digunakan

| Kebutuhan          | Teknologi                   |
|-------------------|----------------------------|
| Bahasa Pemrograman | Python                     |
| Platform           | Google Colab               |
| Scraping YouTube   | YouTube Comment API        |
| Scraping Twitter   | tweet-harvest (Node.js)    |
| Scraping TikTok    | Apify API                  |
| Text Processing    | Pandas, Sastrawi           |
| Penyimpanan Data   | CSV Dataset                |

---

## 🧠 Label Kategori yang Digunakan

Komentar diklasifikasikan ke dalam **6 kategori**:

| Label                | Deskripsi                                  |
|---------------------|---------------------------------------------|
| Kebijakan Pemerintah | Opini terkait aturan & tindakan pemerintah |
| Pembalakan Liar      | Isu penebangan hutan ilegal                |
| Alih Fungsi Hutan    | Perubahan lahan yang memicu banjir         |
| Perubahan Iklim      | Opini terkait isu lingkungan global        |
| Sosial Kemanusiaan   | Empati dan bantuan terhadap korban         |
| Komentar Biasa       | Tidak relevan dengan isu banjir            |

---

## 🧹 Tahapan Proses Data

1. Scraping komentar dari YouTube, Twitter, dan TikTok  
2. Pembersihan dan normalisasi teks (text preprocessing)
3. Pelabelan berdasarkan topik/bidang isu
4. Penyimpanan hasil dalam bentuk CSV
5. Siap digunakan untuk:
   - Analisis opini publik
   - Model klasifikasi teks
   - Visualisasi dan dashboard data

---

## 📦 Dataset

📍 Semua data tersedia dalam folder:  
📁 **Output/**

Format dataset yang digunakan:

```
predicted_label | Komentar
```

Dataset ini berisi **ribuan komentar** berbahasa Indonesia yang relevan dengan isu banjir.

---

## 👤 Kontributor

- Nama: **Hardika Setiyawan**
- Program Studi / Mata Kuliah: **Informatika — Pengolahan Bahasa Alami**
- Tahun: **2025**

---

## 📝 Lisensi

Dataset ini dibuat untuk **keperluan penelitian dan edukasi**.  
Tidak diperkenankan digunakan untuk tujuan komersial tanpa izin.

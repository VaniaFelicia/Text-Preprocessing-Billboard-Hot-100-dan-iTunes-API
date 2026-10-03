Tugas Text Preprocessing - Pemrosesan Teks
Anggota
- Eifellyne Putri Widayanto (25031554011)
- Vania Felicia Gita Wulandari (25031554058)
Deskripsi
Preprocessing teks dari hasil scraping sebelumnya:
- Billboard Hot 100 (web scraping HTML)
- iTunes API (JSON, artis Taylor Swift)
Tahapan preprocessing: hapus tag HTML, hashtag, URL/email, tanda baca, dan emoji; lowercasing; stemming (Porter); hapus stopword. Hasil divisualisasikan dengan WordCloud sebelum dan sesudah preprocessing.
Isi Repository
- Text_Preprocessing.ipynb: notebook utama
- Song_Preprocessed.csv: dataset hasil preprocessing
Note: Buka notebook di Google Colab, lalu jalankan semua sel secara berurutan. Library yang dibutuhkan: requests, beautifulsoup4, pandas, nltk, wordcloud, matplotlib, demoji.

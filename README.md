# Credit Risk Prediction Modeling

## Deskripsi Proyek
Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat memprediksi risiko kredit menggunakan dataset pinjaman yang disetujui dan ditolak. Dengan menggunakan teknik analisis data dan machine learning, proyek ini bertujuan untuk meningkatkan akurasi penilaian risiko, mengoptimalkan keputusan bisnis, dan mengurangi kerugian bagi pemberi pinjaman.

## Latar Belakang
ID/X Partners adalah perusahaan yang menyediakan layanan konsultasi dalam manajemen risiko dan analitik data. Proyek ini merupakan bagian dari upaya untuk membantu perusahaan pemberi pinjaman dalam mengembangkan model yang lebih baik untuk menilai kelayakan pinjaman.

## Dataset
Dataset yang digunakan dalam proyek ini mencakup informasi tentang pinjaman, termasuk status pinjaman, jumlah pinjaman, dan informasi peminjam. Dataset ini memiliki 74 kolom dengan berbagai tipe data, termasuk numerik dan kategorikal.

### Kolom Dataset
- **Kolom Numerik**: 33 kolom (misalnya, `loan_amnt`, `annual_inc`, `dti`, dll.)
- **Kolom Kategorikal**: 22 kolom (misalnya, `grade`, `home_ownership`, `loan_status`, dll.)

## Tools dan Teknologi
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Langkah-langkah Proyek
1. **Data Preprocessing**: Membersihkan dan mempersiapkan data untuk analisis.
2. **Exploratory Data Analysis (EDA)**: Menganalisis data untuk menemukan pola dan wawasan.
3. **Modeling**: Mengembangkan model machine learning menggunakan algoritma seperti Logistic Regression dan Random Forest.
4. **Evaluasi Model**: Mengukur kinerja model menggunakan metrik seperti akurasi, precision, recall, dan F1 score.
5. **Kesimpulan**: Menyimpulkan hasil dan memberikan rekomendasi berdasarkan analisis.

## Hasil
Model yang dikembangkan menunjukkan performa yang kuat dengan akurasi mencapai 90,5%. Model ini dapat diandalkan untuk berbagai skenario klasifikasi dalam penilaian risiko kredit.

## Instalasi
Untuk menjalankan proyek ini, Anda perlu menginstal beberapa paket Python. Anda dapat menggunakan pip untuk menginstalnya:

```bash
pip install pandas scikit-learn matplotlib seaborn

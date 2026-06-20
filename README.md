# 📊 Portofolio Data Science - Pertemuan 1 s.d. 7

## 👤 Identitas Mahasiswa
- **Nama Lengkap**: Muhammad Sulthan Al Ihsan
- **NIM**: 250401020154
- **Matkul**: Data Science
- **Kelas**: IF401
- **Program Studi**: PJJ Informatika - Universitas Siber Asia

---

##  Deskripsi Repository
Repository ini merupakan kumpulan tugas praktikum (hands-on) mata kuliah **Data Science** dari Pertemuan 1 hingga Pertemuan 7. Tujuan utama dari penyusunan portofolio ini adalah untuk mendokumentasikan perjalanan belajar saya dalam menguasai fondasi Data Science, mulai dari pemrograman Python dasar, manipulasi data, statistika, hingga visualisasi data.

Di dalamnya terdapat 7 notebook Jupyter yang mencakup materi:

Pertemuan 1: Pengenalan Data Science

Pertemuan 2: Struktur Data Python, NumPy & Pandas

Pertemuan 3: Data Cleaning: Missing Values, Outlier & Ekstraksi Data

Pertemuan 4: Statistika Dasar & Analisis Data

Pertemuan 5: Visualisasi Data

Pertemuan 6: Persiapan Data (Encoding, Scaling, & Train-Test Split)

Pertemuan 7: Pengantar Machine Learning: Regresi Linear

---

## 📚 Daftar Notebook Praktikum

| Pertemuan | Topik Utama | Link Notebook |
| :--- | :--- | :--- |
| **Pertemuan 1** | Pertemuan 1: Pengenalan Data Science | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan1_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |
| **Pertemuan 2** | Pertemuan 2: Struktur Data Python, NumPy & Pandas | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan2_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |
| **Pertemuan 3** | Pertemuan 3: Data Cleaning | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan3_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |
| **Pertemuan 4** | Pertemuan 4: Statistika Dasar & Analisis Data | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan4_Muhamad_Sulthan_Al_Ihsan_250401020154_ipynb.ipynb) |
| **Pertemuan 5** | Pertemuan 5: Visualisasi Data | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan5_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |
| **Pertemuan 6** | Pertemuan 6: Persiapan Datal | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan6_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |
| **Pertemuan 7** | Pertemuan 7: Pengantar Regresi Linear & Evaluasi Model | [🔗 Buka Notebook](https://github.com/sulthanalihsan/data-science-2026/blob/main/Pertemuan7_Muhamad_Sulthan_Al_Ihsan_250401020154.ipynb) |


---

## 🚀 Cara Menjalankan Notebook
Anda dapat menjalankan notebook ini dengan dua cara:

1. **Google Colab (Direkomendasikan)**:
   Klik link pada tabel di atas, lalu pilih menu `File > Save a copy in Drive` untuk menyimpan salinan dan menjalankannya secara online tanpa instalasi.

2. **Lokal (Local Environment)**:
   - Clone repository ini: `git clone`
   - Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn scipy`
   - Jalankan Jupyter: `jupyter notebook`
   - Buka file `.ipynb` yang diinginkan.

---

## 🛠️ Tools & Libraries
Proyek ini menggunakan ekosistem Python standar untuk Data Science:
- **Bahasa Pemrograman**: Python 3.x
- **Manipulasi Data**: Pandas, NumPy
- **Visualisasi**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-Learn
- **Statistika**: SciPy
- **Environment**: Google Colab / Jupyter Notebook


## 💡 Kesimpulan Perjalanan Belajar (Pertemuan 1-7)

Kesimpulan Umum:
- **Pertemuan 1: Pengenalan Data Science**: Data Science adalah bidang multidisiplin (Statistika, Ilmu Komputer, Domain Knowledge) untuk mengekstrak wawasan dari data. Siklus proyek standar menggunakan kerangka CRISP-DM (Business Understanding -> Data Understanding -> Preparation-> Modeling-> Evaluation-> Deployment) yang bersifat iteratif. Tools utama meliputi Python, Google Colab/Jupyter Notebook, dan GitHub untuk version control serta portofolio.
- **Pertemuan 2: Struktur Data Python, NumPy & Pandas**: Python memiliki empat struktur data dasar: List (mutable), Tuple (immutable), Dictionary (key-value), dan Set (unik). NumPy menyediakan array homogen kecepatan tinggi untuk komputasi numerik dgn vektorisasi. Pandas menawarkan DataFrame dua dimensi berlabel untuk manipulasi data tabular, mencakup filtering dan agregasi.
- **Pertemuan 3: Data Cleaning**: Kualitas data adalah fondasi analisis (Garbage In, Garbage Out). Masalah umum meliputi missing values, duplikat (drop_duplicates), outlier (deteksi IQR Fence/Z-Score, penanganan capping/winsorization), dan inkonsisten string. Selain itu, data dapat diekstraksi dari file JSON lokal maupun REST API publik menggunakan library requests dan json_normalize.
- **Pertemuan 4: Statistika Dasar & Analisis Data**: Statistika deskriptif merangkum data melalui ukuran pemusatan (mean, median, modus) dan penyebaran (varians, std dev, IQR). Distribusi data diidentifikasi lewat skewness (asimetri) dan kurtosis (ketebalan ekor). Analisis univariat menggunakan histogram, boxplot, dan violin plot, sedangkan analisis bivariat menggunakan scatter plot serta korelasi Pearson/Spearman untuk mengukur hubungan linear antar variabel numerik.
- **Pertemuan 5: Visualisasi Data**: Visualisasi efektif harus memenuhi lima prinsip: Kejelasan, Akurasi, Efisiensi, Estetika, dan Konteks. Matplotlib digunakan untuk kustomisasi grafik tingkat rendah, sementara Seaborn menyederhanakan visualisasi statistik tingkat tinggi. Interpretasi insight dilakukan dengan framework "What? So what? Now what?" untuk menerjemahkan temuan visual menjadi rekomendasi yang actionable dan mudah dipahami stakeholder.
- **Pertemuan 6: Persiapan Data**: Sebelum data bisa masuk ke model, kita harus "merapikannya" dulu datanya agar algoritma bisa jalan. telah dipelajari mengubah teks kategori menjadi angka (Encoding), menyamakan skala fitur numerik (Scaling) agar tidak ada variabel yang mendominasi perhitungan, serta membagi data menjadi latih dan uji (Train-Test Split). Poin kuncinya adalah urutan pengerjaan yang benar terutama melakukan split sebelum scaling untuk mencegah kebocoran informasi (data leak) yang membuat evaluasi model jadi tidak akurat.
- **Pertemuan 7: Pengantar Regresi Linear & Evaluasi Model**:  langkah pertama membangun model prediktif untuk menebak nilai kontinu (seperti gaji atau harga). Kita menggunakan Regresi Linear untuk mencari hubungan pola antar variabel, lalu mengevaluasi akurasinya pakai metrik MAE (rata-rata selisih mutlak), RMSE (penalti untuk kesalahan besar), dan R² (persentase variasi yang berhasil dijelaskan). Intinya, kita tidak hanya sekadar melatih model, tapi juga harus paham cara membaca hasil evaluasinya untuk memastikan prediksi tersebut layak dipakai di dunia nyata.


---

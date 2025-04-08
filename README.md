# Klasifikasi Usia pada Subset NHANES Menggunakan Gaussian Naive Bayes

## Deskripsi Proyek
Dataset yang digunakan berasal dari **National Health and Nutrition Examination Survey (NHANES)**, yang dilaksanakan oleh **Centers for Disease Control (CDC)**. Survei ini mengumpulkan informasi kesehatan dan gizi dari populasi AS yang beragam. Namun, karena sifat dataset yang sangat luas, kami mempersempit cakupan analisis untuk memprediksi **kelas usia responden** dengan memilih subset fitur dari dataset NHANES yang lebih besar.

Fitur-fitur yang kami gunakan meliputi:
- **Pengukuran fisiologis**: Gender, Body Mass Index (BMI), dll.
- **Pilihan gaya hidup**: Apakah responden melakukan aktivitas berat, dll.
- **Penanda biokimia**: Apakah responden menderita diabetes, tingkat insulin, gula darah, dll.

Kami memilih fitur-fitur ini karena memiliki korelasi kuat dengan usia responden.

---

## Tahapan Proses Data
1. **Inisialisasi Data**
   - Pengumpulan dan pengelolaan data awal.

2. **Visualisasi Data**
   - Menyajikan distribusi data melalui:
     - *Pair Plot*
     - *Box Plot*
     - *Pie Chart*
     - *Bar Chart*

3. **Data Preprocessing**
   - Membersihkan data di DataFrame `df` dan memfilter nilai berdasarkan kolom tertentu untuk memastikan data valid.
   - Melakukan normalisasi pada fitur dalam DataFrame.

4. **Data Splitting**
   - Memisahkan data menjadi *training set* dan *testing set*.

---

## Metode
Kami menggunakan model klasifikasi **Gaussian Naive Bayes** untuk memprediksi kelas usia responden berdasarkan fitur yang dipilih.

---

## Cara Penggunaan
1. Clone repositori ini ke lokal Anda:
   ```bash
   git clone https://github.com/username/nama-repositori.git

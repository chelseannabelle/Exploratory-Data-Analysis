## 📌 Deskripsi
Analisis data Titanic menggunakan **Python (Pandas, Matplotlib, Seaborn)** untuk memahami pola pada data korban Titanic, seperti distribusi umur, kelas penumpang, tarif, dan tingkat kelangsungan hidup.

Dataset Titanic tersedia secara built-in dari library **Seaborn**.

---

## 🔍 Tujuan
- Melakukan eksplorasi data awal (EDA)
- Menangani **missing values**
- Visualisasi data kategori (jenis kelamin, kelas, status selamat)
- Visualisasi data numerik (usia, tarif)
- Melihat korelasi antar variabel numerik
- Membuat visualisasi hubungan antar variabel (scatter, pairplot)

---

## 📊 Langkah Analisis
1. **Load Dataset**: Titanic dari Seaborn.
2. **Data Cleaning**: identifikasi missing values pada `age`, `deck`, `embark_town`.
3. **Analisis Variabel Kategorik**:
   - Distribusi `sex`, `class`, dan `survived`.
   - Tingkat survival lebih tinggi pada perempuan.
4. **Analisis Variabel Numerik**:
   - Distribusi `age` → mayoritas 20–40 tahun.
   - Distribusi `fare` → ada outlier (tarif sangat tinggi).
5. **Korelasi Antar Variabel**:
   - `fare` berkorelasi dengan `class`.
   - `sex_numeric` berkorelasi dengan `survived`.
6. **Visualisasi Hubungan**:
   - Scatter `age vs fare` dengan warna survival.
   - Pairplot untuk `age`, `fare`, `pclass`.

---

## 📈 Hasil Utama
- **Gender berperan besar**: tingkat survival perempuan jauh lebih tinggi daripada laki-laki.
- **Kelas sosial berpengaruh**: penumpang kelas 1 memiliki tingkat survival lebih tinggi.
- **Umur**: anak-anak memiliki survival rate relatif lebih tinggi.
- **Outlier**: terlihat pada variabel `fare`.

---

## 📸 Visualisasi
- Distribusi umur penumpang
- Histogram tarif (fare)
- Countplot kelas penumpang
- Heatmap korelasi variabel numerik
- Scatter plot umur vs tarif (warna survival)

---

## 📝 Kesimpulan
- **Jenis kelamin, kelas, dan usia** sangat memengaruhi tingkat survival.
- Ada **missing values signifikan** di beberapa kolom → perlu preprocessing lebih lanjut untuk modeling.
- Dataset Titanic cocok untuk latihan **EDA, data preprocessing, dan machine learning** (prediksi survival).

# Analisis A/B Testing untuk Meningkatkan Pendapatan Situs Web

Proyek ini bertujuan untuk menganalisis hasil dari eksperimen A/B yang dilakukan oleh situs web dengan tujuan meningkatkan pendapatannya. Data yang digunakan diperoleh dari Kaggle dan mencakup informasi mengenai hasil eksperimen, jenis sampel (variant_name), dan pendapatan yang dihasilkan oleh pengguna (revenue).

## Tujuan

Tujuan utama dari proyek ini adalah melakukan analisis data untuk memahami dampak perubahan tata letak pada pendapatan situs web. Analisis ini akan dilakukan melalui langkah-langkah berikut:

1. **Data Understanding**: Memahami struktur data, melihat variabel-variabel yang ada, dan memastikan integritas data.

2. **Exploratory Data Analysis (EDA)**: Melakukan analisis deskriptif untuk mendapatkan wawasan tentang karakteristik data dan distribusi pendapatan antara varian A dan B.

3. **Uji Hipotesis**: Melakukan uji hipotesis statistik untuk menguji apakah perbedaan pendapatan antara varian A dan B signifikan secara statistik.

4. **Kesimpulan**: Merumuskan kesimpulan berdasarkan hasil analisis dan memberikan rekomendasi terkait apakah perubahan tata letak berpotensi meningkatkan pendapatan situs web.

## Data

Data dalam proyek ini terdiri dari tiga kolom utama:

- `user_id`: ID unik untuk setiap pengguna yang berpartisipasi dalam eksperimen.
- `variant_name`: Jenis sampel atau varian yang diberikan kepada pengguna (A atau B).
- `revenue`: Jumlah pendapatan yang dihasilkan oleh masing-masing pengguna.

## Langkah-langkah Analisis

1. **Data Understanding**: Memahami struktur data, mengecek integritas data, dan memahami jenis informasi yang terkandung dalam setiap kolom.

2. **Exploratory Data Analysis (EDA)**: Melakukan analisis visual dan deskriptif terhadap data, termasuk histogram, diagram pencar (scatter plot), dan metrik statistik seperti rata-rata dan median. Ini akan membantu mengidentifikasi tren dan pola dalam distribusi pendapatan.

3. **Uji Hipotesis**: Menggunakan metode statistik yang sesuai (seperti uji t independen atau uji mann-whitney U) untuk menguji apakah perbedaan pendapatan antara varian A dan B adalah signifikan secara statistik.

4. **Kesimpulan**: Merangkum hasil analisis EDA dan uji hipotesis untuk menyimpulkan apakah perubahan tata letak memiliki dampak yang signifikan terhadap pendapatan situs web. Rekomendasi juga akan diberikan berdasarkan temuan tersebut.

# Tugas Resume Visualisasi Data dan Informasi

Nama    : Chalifia Wananda

NIM     : 122450076

----

## Judul Jurnal
Makingdatavisualization more efficient and effective: a survey
## Nama Penulis
Xuedi Qin ·Yuyu Luo ·Nan Tang ·Guoliang Li
## Latar Belakang
Visualisasi data adalah alat penting dalam analisis dan pengambilan keputusan berbasis data. Dengan semakin banyaknya data yang tersedia, kebutuhan akan visualisasi data yang efisien dan efektif menjadi sangat penting untuk memudahkan interpretasi dan komunikasi hasil analisis.
## Tujuan
Tujuan dari jurnal ini adalah untuk meninjau teknik-teknik yang dapat membuat visualisasi data lebih efisien dan efektif. Penulis bertujuan untuk menyediakan panduan tentang bagaimana visualisasi data dapat  ditingkatkan melalui pendekatan yang lebih efisien, baik dari sisi pemrosesan data maupun dalam pembuatan visualisasi yang mampu menampilkan informasi dengan lebih cepat dan lebih menarik.
## Metode Penelitian
Jurnal ini menggunakan metode survei untuk meninjau berbagai pendekatan yang digunakan dalam visualisasi data. Pendekatan yang dibahas meliputi:
1. Spesifikasi visualisasi: Cara menentukan kebutuhan pengguna untuk menghasilkan visualisasi yang sesuai.
2. Pendekatan efisien untuk visualisasi data: Pemrosesan data dan spesifikasi visualisasi yang efisien untuk menghasilkan visualisasi yang cepat dan dapat diskalakan.
3. Rekomendasi visualisasi data: Melengkapi spesifikasi yang tidak lengkap secara otomatis atau menemukan visualisasi yang lebih menarik berdasarkan referensi visualisasi.

## Kajian Jurnal
Alur Visualisasi Data:
1.  Impor data adalah mengambil data yang diperlukan dari sumber data yang diinginkan.
2. Persiapan data adalah mempersiapkan data yang diimpor untuk visualisasi.
3. Manipulasi data adalah memilih data yang akan divisualisasikan (alias memfilter dari komunitas visualisasi) dan mungkin dengan operasi umum lainnya seperti penggabungan dan pengelompokan.
4. Pemetaan adalah memetakan data yang diperoleh dari proses di atas ke dalam geometri primitif (misalnya titik dan garis), beserta atributnya (misalnya warna, posisi, dan ukuran).
5. . Rendering adalah mengubah data geometri di atas menjadi representasi visual.

Spesifikasi Visualisasi
- Spesifikasi visualisasi data
    - Data
    - Tanda
    - Pemetaan
-  Kategorisasi bahasa visualisasi data
Strategi yang umum digunakan untuk mengkategorikan bahasa visualisasi data didasarkan pada ekspresifitasnya
    - **Bahasa Tingkat Rendah** co : Prefuse, Flare, Protvis, D3, Vega, dan Reactive Vega
    - **Bahasa Tingkat Tinggi** co : ggplot, Vega-lite, Altair, Ercharts, VizQL, dan ZQL

###  Pendekatan efisien untuk visualisasi data
Pada bagian ini, kita akan membahas pendekatan yang efisien untuk visualisasi data; hal ini penting karena siklus hidup visualisasi data selalu berulang (lihat Gambar 1), dengan human-in-the-loop.

1. Visualisasi data yang tepat
    - Mengintegrasikan Sistem Visualisasi dengan DBMS
    - Kolom Menyimpan Dalam pengelolaan data
    - **Indeks** Indeks banyak digunakan untuk meningkatkan kinerja pencarian dengan mengurangi jumlah catatan/baris
    - Komputasi Paralel 
    - Prediksi dan Pengambilan Awal

2. Perkiraan visualisasi data
Ketika volume data tumbuh secara eksponensial, data tradisional modul pemrosesan tidak dapat memberikan hasil pemrosesan interaktif yang cepat. Untuk menjembatani kesenjangan antara volume data dan interaktivitas, banyak pekerjaan [24–28,99] mempercepat fase pemrosesan data dengan memanfaatkan perkiraan pemrosesan kueri (AQP) yang memberikan perkiraan hasil visualisasi.

Kami membahas perkiraan visualisasi data dari tiga perspektif: pendekatan berbasis AQP yang memanfaatkan teknik
- **Berbasis AQP** Cara mudah untuk menghasilkan visualisasi perkiraan dalam waktu interaktif adalah dengan memanfaatkan teknik AQP. Menggunakan subset representatif dari data dapat memberikan perkiraan visualisasi kepada pengguna interaksi online dengan mengorbankan kualitas. 
 - **Berbasis Pengambilan Sampel Inkremental** Ide utama dari perkiraan visualisasi dengan pengambilan sampel bertahap adalah bahwa sistem menghasilkan perkiraan visualisasi berdasarkan sampel representatif dari kumpulan data dengan cepat.Kemudian, sistem meningkatkan ukuran sampel dari waktu ke waktu untuk terus meningkatkan kualitas visualisasi. Pengguna biasanya dapat memperoleh beberapa wawasan awal dari perkiraan visualisasi dan memutuskan untuk menghentikannya jika kualitas visualisasi cukup untuk memverifikasi wawasan ini.
- **Berbasis Persepsi Manusia**

3. Visualisasi data progresif
- Binning Berbasis Rentang
- Pengelompokan Berbasis Rentang dan Konten

###  Rekomendasi visualisasi

#### Rekomendasi berdasarkan spesifikasi
1.  Spesifikasi tidak lengkap
2. Spesifikasi berbasis referensi

####  Rekomendasi berbasis perilaku
Sistem rekomendasi berbasis perilaku menangkap perilaku pengguna saat ini sebagai masukan, kemudian menyimpulkan tugas yang diinginkan pengguna dan merekomendasikan visualisasi yang berguna berdasarkan tugas mereka.

#### Rekomendasi yang dipersonalisasi
Sistem rekomendasi yang dipersonalisasi menangkap perilaku historis pengguna sebagai masukan untuk merekomendasikan visualisasi menarik yang dipersonalisasi.
1. Metode Linier
2. Pemfilteran Kolaboratif

## Kesimpulan 
Visualisasi data yang efisien dan efektif sangat penting untuk mendukung pengambilan keputusan di berbagai bidang. Inovasi terus-menerus dalam teknologi dan alat visualisasi diperlukan untuk memenuhi kebutuhan data yang semakin kompleks. Jurnal ini menekankan pentingnya peningkatan efisiensi dan skalabilitas dalam pembuatan visualisasi data agar lebih bermanfaat bagi pengguna.

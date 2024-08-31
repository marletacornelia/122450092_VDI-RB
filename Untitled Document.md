Marleta Cornelia Leander 
122450092 / RB VDI

## PENDAHULUAN
Di era digital saat ini, dunia bisnis sangat memerlukan suatu hal yang sangat penting untuk pengambilan keputusan yaitu visualisasi data, mengingat semua hal itu berbasis dengan data yang jumlahnya banyak. Hal ini berguna untuk mengambil sebuah keputusan dikemudian hari. Oleh karena itu, sebelum dilakukan visualisasi, para industri memerlukan para ahli yang dapat memroses data dengan baik agar mendapatkan hasil visualisasi yang efektif dan efisien.

Visualisasi data berguna untuk mengubah data yang bentuknya abstrak menjadi bentuk yang dapat dilihat dengan persepsi yang baik dan orang yang melihatnya mendapat suatu pengetahuan baru dan berguna sebagai pengambikan keputusan.

Terdapat 5 alur visualisasi data, yaitu :
1.	Impor data
2.	Persiapan data (Normalisasi, interpolasi nilai yang hilang, dll)
3.	Manipulasi data (Memilih data yang akan divisualisasikan)
4.	Pemetaan (Memetakan data yang telah diperoleh ke bentuk geometri primitif)
5.	Rendering (Mengubah data geometri menjadi representasi visual)

3 arah visualisasi data agar efisien dan efektif :
1.	Spesifikasi Visualisasi 
2.	Pendekatan Efisien untuk Visualisasi Data
3.	Rekomendasi Visualisasi Data

## SPESIFIKASI VISUALISASI
1.	Spesifikasi Visualisasi Data
Terdapat 3 bagian bahasa visualisasi data, yaitu:
-	Tanggal (Catatan dan transformasi)
-	Tanda (Tipe, ukuran, legenda, dll)
-	Pemetaan

2.	Kategorisasi Bahasa Visualisasi Data
-	Bahasa Tingkat Rendah (Prefuse, Flare, Protvis, Vega, dll) = Bahasa ini mudah digunakan karena bahasa yang lebih dekat dengan manusia seperti  menentukan diagram apa yang akan dipakai
-	Bahasa Tingkat Tinggi (ggplot2, Vega-Lite, Altair, dll) = Bahasa yang berguna untuk membuat detail teknis di balik visualisasi data seperti algoritma apa yang digunakan utnuk menghasilkan grafik.
-	Alat Berbasis GUI (Tavleau, Excel, Keshif, dll)
-	Bahasa yang tidak ditentukan (Zenvisage, DeepEye, APT, dll)

3.	Operasi Visual Berbasis GUI (Graphic User Interface)
GUI memanfaatkan interaksi lewat elemen visual seperti menu, ikon, dll tanpa user menulikan kode. Namun, perlu diketahui bahwa ada beberapa jenis dari bagan yang kemampuannya terbatas dan tidak fleksibel, sehingga GUI umumnya hanya digunakan agar melakukan pembuatan sebuah prototipe secara cepat dan hasil visualisasi yang berguna.

4.	Spesifikasi yang Tidak Ditentukan
Pada dasarnya, pengguna tidak mengetahui tentang semua aspek data sehingga diperlukannya alat agar mereka dapat melakukan eksplorasi data secara multidimensi. Dalam hal ini ada beberapa cara untuk memberikan petunjuk visualisasi dari pengguna, yaitu:
-	Berbasis refrensi
-	Berbasis kata kunci
-	Berbasis bahasa alami

PENDEKATAN EFISIEN UNTUK VISUALISASI DATA
1.	Visualisasi data yang tepat
-	Terjemahan Kueri : Melakukan cara dengan menerjemahkan kueri visualisasi ke kueri yang diterima sistem contohnya mengubah bahasa visualisasi target menjadi kueri SQL
-	Integrasi DBMS : Melakukan pengintegrasian antara saat pengambilan data dengan rendering visualisasi. Hal ini dapat mempercepat proses.
-	Penyimpanan Kolom : Melakukan penyimpanan data berbasis kolom agar lebih mudah saat memvisualisasikan data
-	Penggunaan Indeks : Salah satu contohnya dengan menggunakan indeks berbasis pohon hierarki. Hal ini berguna untuk melakukan pemilihan opsi untuk pengguna. Hal ini juga berguna agar pencarian data dapat dilakukan dengan cepat
-	Komputasi Paralel : Berguna untuk mempercepat kegiatan saat kueri diproses
-	Prediksi dan Pengambilan Awal : Memanfaatkan sistem visualisasi sebagai alat untuk memprediksi data.

2.	Perkiraan visualisasi data
Terdapat 3 perspektif untuk perkiraan visualisasi data, yaitu:
-	Berbasis AQP : Memvisualisasikan data secara cepat lewat kueri yang hasilnya adalah sebuah perkiraan
-	Berbasis Pengamilan Sampel Inkremental : Teknik pengambilan data secara bertahap mulai dari yang kecil 
-	Berbasis Persepsi Manusia : Manusia memroses informasi yang dilihat secara visual lalu disederhanakan dengan cara yang efektif dan kognitif

3.	Visualisasi Data Progresif
Visualisasi data progresif mengarah kepada hasil dari visualisasi akan ditampilkan kepada pengguna secara bertahap. Hal ini dapat membuat pengguna untuk eksplorasi data secara interaktif. Ada 2 teknik dalam visualisasi data progresif, yaitu :
-	Binning Berbasis Rentang : Teknik yang membagi data numerik berdasarkan rentang nilai yang ditentukan lalu pembagian ini dimasukkan ke dalam wadah.
-	Pengelompokan Berbasis Rentang dan Konten : Teknik yang digabungkan antara pendekatan pengelompokan data berdasarkan rentang nilai dan pendekatan pengelompokan data berdasarkan jumlah data di setiap wadah.

REKOMENDASI VISUALISASI
1.	Rekomendasi Berdasarkan  Spesifikasi
-	Spesifikasi tidak lengkap : Tidak memerlukan masukan pengguna
-	




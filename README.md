# Capstone Project Modul 2 - SQL & Data Analysis
Capstone project ini bertujuan untuk melakukan data analisis terhadap dataset Airbnb Listing Bangkok

- Nama: Radif Ramadan
- Program: Job Connector Data Science and Machine Learning (Online)
- Batch: JCDSOL-014
- Case Study: Airbnb Listing Bangkok
- Dataset bisa di unduh di sini -> [link](https://drive.google.com/drive/folders/1A_KBMRFTS5Mthpp46nulso679ML4ZwTF?usp=sharing)
- YouTube Video About This Project -> [link](https://youtu.be/Xm280jk201A?si=4KkFttfMPLLa13hJ)
- Story Tableau -> [link](https://public.tableau.com/app/profile/radif.ramadan/viz/RadifRamadan_CapstoneModul2/NeighbourhoodsbyNumberofListings?publish=yes)


# Business Understanding:
Airbnb adalah platform online untuk menyewakan hunian atau kamar, menyediakan layanan bagi host untuk menawarkan tempat tinggal dan guest untuk menemukan akomodasi sementara. Airbnb memperoleh pendapatan dari komisi setiap pemesanan yang dilakukan. Komisi ini diambil dari host dan guest. Oleh karena itu, Airbnb sangat bergantung pada host untuk pendapatan.

## Problem
 - Konsentrasi listing yang tidak merata menyebabkan potensi pasar yang belum dimanfaatkan di area kurang terwakili.
 - Host kesulitan menetapkan harga optimal karena kurangnya data perbandingan harga.
 - Listing dengan sedikit atau tanpa ulasan terlihat kurang kredibel, menghalangi tamu potensial.
## Tujuan
 - Identifikasi area dengan sedikit listing namun permintaan tinggi untuk menyeimbangkan distribusi properti.
 - Berikan wawasan harga kepada host berdasarkan jenis kamar dan lokasi.
 - Dorong tamu memberikan ulasan untuk meningkatkan kredibilitas listing dan menarik lebih banyak pemesanan.

# Data Understanding
Deskripsi dataset:

1. id = ID unik untuk tiap hunian
1. name = Nama Hunian
1. host_id = ID unik untuk tiap host
1. host_name = Nama Host (yang punya hunian)
1. neighbourhood = Daerah tempat hunian berada (distrik)
1. latitude = Latitude lokasi hunian
1. longitude = Longitude lokasi hunian
1. room_type = Tipe hunian (airbnb), terdapat 4 tipe
    * Entire home 
    * Private room 
    * Shared room
    * Hotel
1. price = Harga sewa per malam (Baht)
1. minimum_nights = Jumlah minimal malam untuk menginap
1. number_of_reviews = Total jumlah review yang diterima
1. last_reviews = Tanggal review terakhir 
1. reviews_per_month = Jumlah review dalamm per bulan
1. calculated_host_listing_count = Total Jumlah hunian yang di-listing oleh host
1. availability_365 = Ketersediaan hunian dalam setahun (365 Days)
1. number_of_reviews_ltm = Jumlah review dalam 12 bulan terakhir

# Data Manipulation and Cleansing
Proses pada bagian ini data akan di manipulasi dan juga akan di bersihkan untuk mempermudah analisis serta meningkatkan kualitas data.

# Exploratory Data Analysis
Mengeksplorasi dataset untuk mendapatkan analisis yang dapat dijadikan Insight dan juga Rekomendasi

# Insight 
Salah satu insight yang ditemukan adalah sebagian besar hunian yang di-listing memiliki harga di bawah **5.000 Baht per malam**, dan kebanyakkan di sekitar **1.000-2.000 Baht**.

# Rekomendasi 
`host` harus mempertimbangkan harga yang kompetitif berdasarkan jenis kamar dan lokasi. Memanfaatkan data harga rata-rata dapat membantu menetapkan harga optimal untuk menarik lebih banyak pemesanan sekaligus memaksimalkan pendapatan.

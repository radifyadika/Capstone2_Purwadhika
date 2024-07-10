# Capstone-Project-M2
Capstone project ini bertujuan untuk melakukan data analisis terhadap dataset Airbnb Listing Bangkok

- Story Tableau -> [link](https://public.tableau.com/app/profile/fadhlan.auffar/viz/CapstoneProjectM2Fadhlan/CapstoneProjectStory?publish=yes)
- Presentasi -> [link](https://drive.google.com/drive/folders/1SxeOOUvlzRKSrtgGfH2vB0ogUR_-js4f?usp=sharing)
- Distrik Bangkok Geojson -> [link](https://github.com/pcrete/gsvloader-demo/blob/master/geojson/Bangkok-districts.geojson)

# Business Understanding:
Pendapatan Airbnb berasal dari geust fee serta host fee. Bisnis model yang dimiliki adalah asset-light business model, dimana tidak memiliki asset yang benyak, melainkan mendapatkan asset dari kerjasama dengan host

- Permasalahan: Guest membuka web sendiri untuk proses penyewaan, sehingga transaksi terjadi di luar aplikasi yang menyebabkan potensi pendapatan berkurang. Ingin terus menambah jumlah hunian (asset) dan memanfaatkan daya tarik kota Bangkok

- Tujuan: Mendapatkan insight host behaviour berdasarkan data hunian listing, sehingga dapat dipergunakan untuk membuat program yang lebih sesuai dengan karakteristik untuk bisa mempertahankan host atau mendapatkan potential host

- Bagaimana karakteristik host yang paling sesuai untuk dibuatkan program? Sehingga meminimalisr penggunaan sumber daya yang dimiliki.

# Data Understanding
Setiap baris data merepresentasikan data hunian yang di-listing oleh host

1. id = id unik untuk nama hunian
1. name = nama hunian
1. host_id = id unik untuk nama host
1. host_name = nama host
1. neighbourhood = daerah tempat airbnb (distrik)
1. latitude = lokasi neighbourhood (WGS84)
1. longitude = lokasi neighbourhood (WGS84)
1. room_type = tipe airbnb, terdapat 4 tipe
    * Entire home
    * Private room
    * Shared room
    * Hotel
1. price = harga sewa (baht)
1. minimum_nights = kuantitas minimal untuk menginap 
1. number_of_reviews = total jumlah riview yang dimiliki 
1. last_reviws = tanggal review terakhir 
1. reviews_per_month = jumlah review per bulan
1. calculated_host_listing_count = jumlah kalkulasi airbnb yang dimiliki host
1. availability_365 = ketersedian hari yang dapat disewa
1. number_of_reviews_ltm = jumlah review dalam 12 bulan terakhir

# Data Preparation
Proses yang dilakukan adalah memanipulasi data sehingga kualitas data menjadi lebih baik. Beberapa proses yang dilakukan adalah menanggulangi missing value dengan default value serta mengubah tipe data.

# Data Analysis
Menganilis data dengan beberapa domain pendekatan, diantaranya adalah wilayah, harga, dan jumlah listing. Memvisualisasikan data, serta menarik kesimpulan berdasarkan temuan analisis.

# Insight 
Salah satu insight yang ditemukan adalah bahwa sebaran hunian Airbnb hanya cenderung terpusat pada wilayah Bangkok Tengah

# Rekomendasi 
Dapat memperoleh potential host pada distrik di wilayah pinggiran bangkok karena daya saing yang masih rendah dan untuk membuat pernyebaran hunian lebih melebar.

Lengkapnya dapat dilihat pada notebook yang tersedia.

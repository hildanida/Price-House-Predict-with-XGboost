# <center> California Housing Price

**Context**

Tempat tinggal merupakan kebutuhan pokok setiap manusia. Tetapi tidak semua orang memiliki pengetahuan tentang harga rumah yang sesuai dengan value yang di berikan. Di setiap negara cukup sulit untuk orang awam mengetahui harga rumah yang memiliki harga yang sesuai dengan value yang di berikan rumah atau perumahan tsb. Begitupun di negara california yang memiliki 50 lebih daerah yang tentunya tiap daerah memiliki harga rumah yang berbeda-beda. Fenomena ini menjadi kesempatan dan tantangan tersendiri untuk para developer perumahan untuk dapat membangun perumahan yang memiliki harga yang dapat bersaing di daerah tersebut dan tentunya memiliki value yang sesuai.
**Problem Statement**

Salah satu tantangan utama dalam analisis data real estate adalah kemampuan untuk memprediksi harga rumah secara akurat berdasarkan berbagai fitur yang ada. Hal ini dapat membantu berbagai pihak seperti agen real estate, pengembang properti, dan pembuat kebijakan dalam membuat keputusan yang lebih baik.

Menggunakan dataset dari sensus California 1990, kita akan mengembangkan model prediksi yang dapat memperkirakan nilai rumah berdasarkan fitur-fitur yang tersedia dalam dataset. Dengan `memahami faktor-faktor yang mempengaruhi harga rumah dapat memberikan wawasan yang berharga bagi para pemangku kepentingan, seperti dapat memberikan keuntungan financial yang maksimal dan rumah yang di bangun juga dapat terjual dengan cepat.`

**Goals**

Berdasarkan permasalahan tersebut, tujuan dari analisis ini adalah:

1. Mengidentifikasi faktor-faktor utama yang mempengaruhi harga rumah di California berdasarkan data sensus 1990.
1. Mengembangkan model prediksi yang dapat memperkirakan nilai rumah berdasarkan variabel-variabel yang tersedia.
1. Menyediakan wawasan yang dapat membantu dalam pengambilan keputusan terkait pembelian, penjualan, dan pembangunan properti di California.

**Analytic Approach**

Jadi, yang perlu kita lakukan adalah menganalisis data untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan satu properti dengan yang lainnya.

Selanjutnya, kita akan membangun suatu model regresi yang akan membantu dalam memprediksi nilai rumah berdasarkan data sensus 1990.

**Metric Evaluation**

Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MSE, di mana lebih ditekankan nilai MAE nya. RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MSE adalah mengambil selisih kuadrat antara prediksi model dan nilai yang sebenarnya untuk setiap titik data, kemudian menghitung rata-rata dari selisih kuadrat tersebut. Semakin kecil nilai RMSE, MAE, dan MSE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan.

| Kolom             | Deskripsi                                      |
|-------------------|------------------------------------------------|
| `longitude`           | Ukuran seberapa jauh barat sebuah rumah; nilai yang lebih tinggi berarti lebih jauh ke barat |
| `latitude`         | Ukuran seberapa jauh utara sebuah rumah; nilai yang lebih tinggi berarti lebih jauh ke utara |
| `housingMedianAge`  | Usia median sebuah rumah dalam satu blok; angka yang lebih rendah berarti bangunan yang lebih baru |
| `totalRooms`       | Jumlah total kamar dalam satu blok       |
| `totalBedrooms`        | Jumlah total kamar tidur dalam satu blok |
| `population`  | Jumlah total orang yang tinggal dalam satu blok                     |
| `households`        | Jumlah total rumah tangga, yaitu sekelompok orang yang tinggal dalam satu unit rumah, dalam satu blok |
| `medianIncome`      | Pendapatan median untuk rumah tangga dalam satu blok rumah (diukur dalam puluhan ribu Dolar AS)         |
| `medianHouseValue`  | Nilai median rumah untuk rumah tangga dalam satu blok (diukur dalam Dolar AS) |
| `oceanProximity`    | Lokasi rumah terhadap laut/samudera         |




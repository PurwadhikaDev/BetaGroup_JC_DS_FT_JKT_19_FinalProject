# BetaGroup_JC_DS_FT_JKT_19_FinalProject
## Group Members: Refa Yudhatama Ramadhan & Dhimas Aditya Zulhajmi
### Mentors: Mas Albert & Mas Ahmad
### JCDS 1904

Ini adalah file readme untuk sebuah proyek pembelajaran mesin yang dibuat untuk membantu Bank Portugal meningkatkan pangsa pasarnya dengan meningkatkan kampanye pemasarannya. Bank telah beroperasi selama lebih dari 50 tahun dan menawarkan berbagai produk keuangan, termasuk deposito, pinjaman, dan hipotek. Divisi pemasaran bank telah memutuskan untuk menggunakan kampanye pemasaran langsung untuk mempromosikan produk deposito jangka tetapnya kepada pelanggan. Untuk meningkatkan efektivitas kampanye ini dan mengurangi biaya pemasaran, bank telah menyewa tim ilmuwan data untuk membangun model pembelajaran mesin yang dapat memprediksi pelanggan mana yang paling mungkin menerima tawaran tersebut.

Model pembelajaran mesin akan dibangun menggunakan data pelanggan, termasuk usia, pekerjaan, status pernikahan, pendidikan, dan data pinjaman. Variabel target akan diatur menjadi 'ya' jika pelanggan setuju untuk mengambil deposito dan 'tidak' sebaliknya. Tujuan dari proyek ini adalah meningkatkan efektivitas kampanye pemasaran, memastikan bahwa pelanggan yang dihubungi oleh telemarketer sudah diidentifikasi sebagai yang kemungkinan besar menerima tawaran. Tim proyek akan menganalisis data untuk mengidentifikasi pola yang membedakan pelanggan yang menerima tawaran dari mereka yang tidak. Kemudian, mereka akan membangun model klasifikasi yang dapat memprediksi probabilitas bahwa pelanggan akan menerima tawaran tersebut.

Metrik evaluasi yang digunakan untuk proyek ini adalah presisi. Fokusnya adalah meningkatkan True Positive, artinya pelanggan yang diprediksi akan menerima tawaran dan benar-benar melakukannya, dan mengurangi False Positive, di mana pelanggan diprediksi akan menerima tawaran tetapi pada akhirnya tidak melakukannya. Keberhasilan model dalam mencapai tujuan ini akan dievaluasi menggunakan matriks kebingungan.

Secara ringkas, proyek ini bertujuan untuk membantu Bank Portugal meningkatkan pangsa pasarnya dengan meningkatkan efektivitas kampanye pemasarannya, mengurangi biaya pemasaran, dan meningkatkan jumlah pelanggan yang menerima tawaran deposito jangka tetap.

## Data Understanding 

Sumber Dataset : https://www.kaggle.com/datasets/volodymyrgavrysh/bank-marketing-campaigns-dataset?datasetId=473216&sortBy=voteCount

* Terdapat ketidakseimbangan pada dataset.
* Sebagian besar fitur pada dataset bersifat kategorikal, baik nominal maupun ordinal, dengan beberapa fitur memiliki kardinalitas yang tinggi.
* Setiap baris pada dataset merepresentasikan informasi kandidat nasabah yang pernah melakukan deposit di masa lalu.

## **Attribute Information**

|Feature|Data Type|Description|
| --- | --- | --- |
| age | int64 | Age of the Customer |
| job | Object | Type of customer occupation |
| marital | Object | Marital status of customers |
| education | Object | Last education of customers |
| default | Object | Customer's current creadit status |
| housing | Integer | Does customer in housing loan |
| loan | Object | Does customer has personal loan |
| contact | int64 | Contact communication type |
| month | int64 | Last contact month of year |
| day_of_week | Integer | Last contact day of the week |
| duration | Object | Last contact duration, in seconds |
| campaign | Object | Number of contacts performed during this campaign and for this client |
| pdays | Object | Number of days that passed by after the client was last contacted from a previous campaign |
| previous | Object | Number of contact performed before this campaign and for this client |
| poutcome | Object | Outcome of the previous marketing campaign |
| emp.var.rate | Object | Employment variation rate |
| cons.price.idx | Object | Consumer price index |
| cons.conf.idx | Object | Consumer confidence index |
| euribor3m | Object | Euro Interbank Offered Rate, 3 month rate |
| nr.employed | Object | number of employees, quarterly indicator |
| y | Object | Has the client subscribed a term deposit |

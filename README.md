# Project_Capstone_HCAI
# Judul Topik Project Capstone
"Prediksi Jumlah Pembayaran Penumpang Transjakarta Menggunakan Model Regresi pada Data Transaksi Transportasi Publik"
# Latar belakang
Jakarta, kota termacet di Indonesia, menghadapi masalah serius dalam bentuk kemacetan lalu lintas. Pemerintah mencoba mengatasi masalah ini dengan meningkatkan layanan transportasi umum, seperti Transjakarta. Namun, untuk meningkatkan efisiensi operasional dan pengalaman penumpang, pemahaman mendalam tentang perilaku penumpang, termasuk pola pembayaran, sangat penting. Melalui proyek berbasis kecerdasan buatan dan machine learning, tujuan utamanya adalah mengembangkan model prediksi regresi untuk memperkirakan pembayaran penumpang di Transjakarta. Dengan wawasan yang dihasilkan, operator transportasi dapat mengambil tindakan yang lebih cerdas dalam perencanaan, pengelolaan layanan, dan optimalisasi rute, dengan harapan mengatasi masalah kemacetan yang sudah lama menjadi perhatian serius di Jakarta.
# Tujuan
1.	Meningkatkan Efisiensi Operasi Transjakarta
    Melalui prediksi jumlah pembayaran, Transjakarta dapat mengatur jumlah armada dan staf yang diperlukan untuk melayani penumpang       dengan lebih efisien. Contohnya, jika prediksi menunjukkan peningkatan jumlah penumpang pada hari tertentu, operator dapat menambah jumlah armada atau staf untuk menghindari keterlambatan atau kepadatan. Dengan mengoptimalkan operasional, Transjakarta dapat meningkatkan keandalan dan kualitas layanan mereka.
2.	Meningkatkan Pengalaman Penumpang
Prediksi jumlah pembayaran juga dapat digunakan untuk mengurangi antrian di loket tiket. Dengan mengetahui berapa banyak penumpang yang diharapkan melakukan pembayaran pada waktu tertentu, Transjakarta dapat menyesuaikan jumlah loket tiket yang dibuka secara efisien. Hal ini akan mengurangi waktu tunggu penumpang, meningkatkan pengalaman mereka, dan membuat perjalanan dengan Transjakarta lebih nyaman.
3.	Meningkatkan Pendapatan Transjakarta
Dengan memprediksi jumlah pembayaran penumpang, Transjakarta dapat merencanakan promosi dan diskon yang lebih efektif. Contohnya, mereka dapat menawarkan diskon kepada penumpang yang melakukan perjalanan pada waktu tertentu atau dengan jarak tertentu, yang dapat meningkatkan daya tarik transportasi publik ini dan, pada gilirannya, meningkatkan pendapatan Transjakarta.
4.	Pengambilan Keputusan Berbasis Data
Memberikan dasar yang kuat bagi manajemen Transjakarta untuk mengambil keputusan yang didukung oleh data, sehingga mereka dapat merespons dengan lebih baik terhadap perubahan dalam pola perjalanan dan mengelola sistem transportasi secara efektif.
5.	Perencanaan Anggaran yang Lebih Tepat
Tujuan ini adalah memberikan alat yang lebih akurat bagi pihak berwenang untuk merencanakan anggaran operasional dengan memproyeksikan jumlah pendapatan dari penumpang. Ini akan membantu dalam alokasi anggaran yang efisien. Contohnya, dengan menggunakan prediksi jumlah pembayaran. Transjakarta dapat memperkirakan pendapatan yang akan mereka terima dari penumpang dalam bulan tertentu. Dengan pemahaman yang lebih baik tentang potensi pendapatan ini, mereka dapat mengalokasikan anggaran mereka secara lebih cerdas, misalnya, untuk pemeliharaan armada atau perbaikan infrastruktur, sehingga mengoptimalkan penggunaan sumber daya finansial.
Dengan mencapai tujuan-tujuan ini, proyek ini berkontribusi pada upaya meningkatkan efisiensi dan kualitas layanan transportasi publik, mengurangi kemacetan, dan membuat pengalaman perjalanan penumpang lebih baik di Jakarta.
# Dataset
![image](https://github.com/Azizahfatmas/Project_Capstone_HCAI/assets/92080188/64af5a4b-d7b1-47da-a319-4aa2913b0a55)
Dataset laporan proyek capstone ini diambil dari sumber Kaggle, https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction.
Dengan atribut-atribut berikut:
1.	transID: Nomor identifikasi transaksi.
2.	payCardID: ID kartu pembayaran yang digunakan dalam transaksi.
3.	payCardBank: Nama bank yang terkait dengan kartu pembayaran.
4.	payCardName: Nama pemilik kartu pembayaran.
5.	payCardSex: Jenis kelamin pemilik kartu pembayaran.
6.	payCardBirthDate: Tanggal lahir pemilik kartu pembayaran.
7.	corridorID: ID koridor tempat transaksi ini terjadi.
8.	corridorName: Nama koridor tempat transaksi ini terjadi.
9.	direction: Arah perjalanan dalam transaksi.
10.	tapInStops: Jumlah tap-in stops yang terjadi dalam perjalanan.
11.	tapInStopsName: Nama-nama tap-in stops.
12.	tapInStopsLat: Koordinat lintang tap-in stops.
13.	tapInStopsLon: Koordinat bujur tap-in stops.
14.	stopStartseq: Urutan mulai berhenti dalam perjalanan.
15.	tapInTime: Waktu tap-in dalam transaksi.
16.	tapOutStops: Jumlah tap-out stops yang terjadi dalam perjalanan.
17.	tapOutStopsName: Nama-nama tap-out stops.
18.	tapOutStopsLat: Koordinat lintang tap-out stops.
19.	tapOutStopLon: Koordinat bujur tap-out stops.
20.	stopEndSeq: Urutan berhenti berakhir dalam perjalanan.
21.	tapOutTime: Waktu tap-out dalam transaksi.
22.	payAmount: Jumlah uang yang dibayarkan dalam transaksi.
# Flowchart
![image](https://github.com/Azizahfatmas/Project_Capstone_HCAI/assets/92080188/773e5452-3780-45ad-a940-a885f840f798)
1.	Pengguna mengirimkan eksperimen AutoAI dengan pengaturan bawaan.
2.	Beberapa model pipa dibuat. Salah satu model pipa pilihan dari peringkat teratas disimpan sebagai Jupyter Notebook.
3.	Jupyter Notebook tersebut dieksekusi.
# Komponen
1.	IBM Watson Studio - IBM Watson® Studio membantu ilmuwan dan analis data mempersiapkan data dan membangun model dalam skala besar di semua cloud.
2.	IBM Watson Machine Learning - IBM Watson® Machine Learning membantu ilmuwan dan pengembang data mempercepat penerapan AI dan pembelajaran mesin,
3.	IBM Cloud Object Storage - IBM Cloud™ Object Storage memungkinkan penyimpanan data dalam jumlah praktis tanpa batas, secara sederhana dan hemat biaya.
# Langkah-langkah Pengerjaan Project Capstone Prediksi Jumlah Pembayaran Penumpang Transjakarta Menggunakan Model Regresi pada Data Transaksi Transportasi Publik
1. Mencari dataset tentang topik yang akan saya bahas yaitu dataset transaksi angkutan umum transjakarta dari kaggle https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction

![image](https://github.com/Azizahfatmas/Project_Capstone_HCAI/assets/92080188/8c45f647-4342-4596-8231-6ef363649b46)
2.	Login ke dalam ibm cloud
 ![image](https://github.com/Azizahfatmas/Project_Capstone_HCAI/assets/92080188/c8ce5f42-fedd-4708-9030-bfca557f2338)


3.	Setelah berhasil login maka akan muncul tampilan dashboard ibm cloud
 









4.	Lalu pada menu search saya mencari service watsonx
 

5.	Lalu saya memilih watson.ai
 









6.	Setelah itu saya memilih build machine learning models automatically with auto ai  
 

7.	Lalu memilih asset dan membuat new task
 








8.	Lalu memilih kembali build machine learning models automatically with autoai
 

9.	Lalu saya membuat nama untuk eksperimen yang akan dilakukan. Setelah konfigurasinya telah terkonfirmasi maka kemudian di create.
 







10.	Unggah file dataset dalam format CSV.
 

11.	Pada konfigurasi detail, pilih opsi "No" untuk analisis time series.
 









12.	Tentukan kolom yang akan dijadikan target prediksi, yaitu kolom "payAmount." Lalu atur pengaturan eksperimen lainnya.
 

13.	Pilih model regresi, karena dapat memodelkan hubungan antara fitur-fitur lain dalam dataset dengan variabel target numerik yaitu "payAmount."
 







14.	Pilih algoritma "Algorithm" dan "Gradient Classifier."
 

15.	Pilih algoritma ketiga, simpan pengaturan, dan jalankan eksperimen.
 
 

16.	Sedang memproses dan terdapat RMSE (Root Mean Square Error): ukuran seberapa jauh perkiraan dari nilai sebenarnya. Cross validation score: ukuran seberapa akurat perkiraan pada data yang tidak digunakan untuk melatih model.

  

17.	Terdapat Pipeline yaitu serangkaian langkah yang digunakan untuk memproses data sebelum digunakan untuk melatih model pembelajaran mesin. Dalam kasus ini, pipeline terdiri dari dua langkah, yaitu: Feature transformers digunakan untuk mengubah data menjadi format yang dapat digunakan oleh model pembelajaran mesin. Model adalah algoritma pembelajaran mesin yang digunakan untuk memprediksi jumlah penumpang Transjakarta.

  

18.	Pipeline peringkat tertinggi dan memiliki RMSE terendah adalah Pipeline 4
 










19.	Model dengan peringkat tertinggi adalah model "Pipeline 4". Model ini memiliki RMSE (Optimized) terendah, yaitu 264.358. Model ini juga memiliki R squared tertinggi, yaitu 0.997.
 

20.	Fitur "corridorName" memiliki feature importance tertinggi, yaitu 100% Hal ini berarti bahwa fitur "corridorName" adalah fitur yang paling penting dalam memprediksi payAmount.
 






21.	Selanjutnya Create a new deployment space, masukkan nama, dan kaitkan dengan machine learning service kemudian pilih Create
 

22.	Download CSV templetenya terlebih dahulu.
 









23.	Setelah memasukan data pada CSV templete yang sudah di download, maka upload kembali, lalu pilih predict.
 

24.	Maka hasil predict akan terlihat. Hasil nilai prediksi untuk baris pertama adalah 3697.2, sedangkan nilai sebenarnya adalah 3500. Selisih antara nilai prediksi dan nilai sebenarnya adalah 197.2. Selisih ini cukup kecil, sehingga menunjukkan bahwa model regresi memiliki akurasi yang cukup baik.

 



II.2  Hasil project capstone
Berdasarkan hasil prediksi Prediksi Jumlah Pembayaran Penumpang Transjakarta Menggunakan Model Regresi pada Data Transaksi Transportasi Publik:
1.	Peringkat tertinggi adalah pipeline 4. Model ini memiliki RMSE (Optimized) terendah, yaitu 264.358. Model ini juga memiliki R squared tertinggi, yaitu 0.997.
2.	Algoritma LGBM Regressor adalah singkatan dari "Light Gradient Boosting Machine Regressor." Ini adalah salah satu algoritma dalam pembelajaran mesin yang digunakan untuk tugas regresi, yaitu memprediksi nilai numerik berdasarkan data input yang ada. LGBM Regressor adalah implementasi dari pustaka LightGBM, yang merupakan model boosting berbasis pohon yang sangat efisien dan efektif. 
3.	Feature importance adalah ukuran seberapa penting suatu fitur dalam memprediksi target. Fitur "corridorName" memiliki feature importance tertinggi, yaitu 100% Hal ini berarti bahwa fitur "corridorName" adalah fitur yang paling penting dalam memprediksi payAmount.
4.	Beberapa enhancements telah diterapkan pada model, termasuk 1st hyperparameter optimization (HPO-1) dan 2nd hyperparameter optimization, yang disertai dengan Feature engineering. Enhancements ini bertujuan untuk meningkatkan kinerja model.
Dengan demikian, hasil Project Capstone ini memberikan wawasan yang berharga dalam pengembangan Prediksi Jumlah Pembayaran Penumpang Transjakarta Menggunakan Model Regresi pada Data Transaksi Transportasi Publik, yang dapat digunakan untuk perencanaan dan pengelolaan layanan transportasi yang lebih efisien dan akurat di masa depan. 






Grade Classification and Article Summarization with IBM Granite

#Project Overview
Dalam suatu kelas di universitas, terdapat data-data penilaian untuk tiap mahasiswa. Untuk mengetahui siapa saja siswa/siswi persebaran kemampuan siswa, perlu dilakukan klasifikasi.
Klasifikasi secara manual tentunya memakan waktuyang lama. Oleh karena itu, diperlukan pemanfaatan teknologi seperti IBM granite. IBM granite ini dapat membantu mengklasifikasikan
data berdasarkan prompt yang diberikan.  Selain untuk klasifikasi, AI IBM ini juga dapat membantu meringkasparagraf yang panjang seperti artikel. Hal ini dapat digunakan dalam 
hidup sehari-hari seperti membantu meringkas materi pelajaran. Teks yang lebih ringkas umumnya lebih mudah dipahami dan lebih mudah untuk diingat.

Saya ingin menyelesaikan masalah terkait klasifikasi data nilai mahasiwa serta menyelesaikan permasalahan artikel yang panjang. 
Target pengguna ialah dosen/asisten dosen yang mengecek nilai mahasiswa. Klasifikasi ini digunakan untuk mengecek tingkat pemahaman 
berdasarkan nilai dan klasifikasinya. Kemudian untuk rangkuman artikel, tergetnya mahasiswa. 
Karena seringkali membaca tulisan yang panjang sulit dimengerti dan sulit untuk diingat. 

#Raw Dataset
https://www.kaggle.com/datasets/larsen0966/student-performance-data-set
https://www.nationalgeographic.com/health/article/digital-smartphone-cameras-memory

#Analysis Process
Untuk klasifikasi, lihat dan pahami terlebih dahulu data yang ada. Pilih data yang ingin dianalisis lebih lanjut. 
Setelah menentukan data, tentukan apa saja penjelasan yang memungkinkan untuk data tersebut. Pada data nilai mahasiswa yang tertera, 
secara sederhana data dapat diklasifikasikan menjadi 3 macam. Pengklasifikasian tersebut bertujuan untukmelihat performa mahasiswa. 
Kemudian bisa juga dilihat apakah performa antar penilaian (G1,G2,G3) meningkat atau menurun.

#Insigt
Dengan kelasifikasi data,pengelompokan nilai dapat terlihat lebih jelas dan dapat dilihat peningkatan/penurunan performanya.
Untuk artikel yang dirangkum berupa poin-poin penting lebih mudah dimengert

#Conclusion 
Perlu penjelasan yang jelas danterstruktur, tetapi tidak terlalu rumit.
Terkadang perlu waktu cukup lama untuk menjalankan prompt menggunakan Google Colab. Coba
gunakan metode lain seperti menggunakan aplikasi Watson AI. Mungkin IBM Granite ini lebih cocok
untuk data berupa kalimat dibandingkan dengan angka.

#AI Support Explanation
AI yang digunakan di sini ialah IBM granite-3.3-8b-instruct.
Untuk classification dan summarization, kodenya kurang lebih sama 
jika menggunakan Google Colab. Tuliskan kode untuk hal yang akan 
diklasifikasikan atau dirangkum. Kemudian tulis promptnya dan 
keluarkan outputnya menggunakan output.invoke. 
Agar hasil lebih akurat, buat penjelasan yang runtut 
dan beri contoh pada AInya. AI akan membantu classification 
dan summarization berdasarkan kejelasan prompt. 


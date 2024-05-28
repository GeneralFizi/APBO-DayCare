# APBO-DayCare Adi Pramono 4520210001
Repo untuk tugas daycare matkul APBO 

------------------------------------------------------------------------------------------------------------------------
  #TUGAS ANALISIS SISTEM INFORMASI DAYCARE BERBASIS OBJEK
------------------------------------------------------------------------------------------------------------------------

**Latar Belakang**
--------------
Daycare adalah layanan yang menyediakan perawatan dan pengawasan bagi anak-anak usia bayi 
hingga pra sekolah saat orang tua atau wali mereka bekerja ataupun memiliki keperluan lain.
Layanan utama daycare secara garis besar meliputi penyediaan kebutuhan anak makan, minum, 
tidur siang, dan mengganti popok. Menawarkan aktivitas bermain dan belajar yang sesuai dengan 
usia anak untuk mendukung perkembangan kognitif, fisik, sosial, dan emosional. Memastikan 
lingkungan yang aman dan terlindungi bagi anak-anak. Menyediakan makanan dan minuman yang 
sehat dan bergizi. Menjaga kebersihan lingkungan dan menerapkan praktik kesehatan yang baik 
untuk mencegah penyebaran penyakit.
Tujuan Tugas
1. Menerapkan teknik analisis objek seperti use case, class diagram, dan ERD untuk 
memodelkan sistem informasi daycare
2. Mengidentifikasi kebutuhan fungsional sistem
3. Merancang solusi sistem informasi sesuai dengan kebutuhan daycare.
Deskripsi Tugas
1. Secara mendasar, kebutuhan daycare adalah pengelolaan data anak, orang tua/wali, staf, 
jadwal, kehadiran, dan laporan.
2. Identifikasi aktor yang terlibat
3. Gunakan teknik use case untuk memodelkan interaksi antara aktor dan sistem
4. Gunakan class diagram untuk memodelkan struktur objek
5. Gunakan ERD untuk memodelkan hubungan antara entitas dalam sistem


**CLASS DIAGRAM**
------------------------------------------------------------------------------------------------------------------------
![Class Diagram](https://github.com/GeneralFizi/APBO-DayCare/assets/135718695/a6f044b7-3798-411b-8935-041af9c61727)






**ERD**
------------------------------------------------------------------------------------------------------------------------
![ERD](https://github.com/GeneralFizi/APBO-DayCare/assets/135718695/32923eed-d363-4e57-a86f-c467c81ff8c1)







**Use Case Diagram**
------------------------------------------------------------------------------------------------------------------------
![Usecase](https://github.com/GeneralFizi/APBO-DayCare/assets/135718695/ef1ab99a-1aba-4e3c-a336-11330f072556)




Keterangan : 
1. terdapat 4 aktor yaitu : anak, orang tua, staff dan admin
2. untuk kebutuhan fungsional, menurut saya daycare tidak perlu membangun aplikasi. cukup membuat sistem informasi berbasis web yang dijalankan di localhost. dengan begitu, semua archive, absen, penjadwalan bisa dilakukan locally
3. orang tua mempunyai banyak anak sehingga hubungannya one to many
4. orang tua tidak perlu login untuk mendapatkan laporan harian.
5. presensi kehadian anak hanya sebatas " hari ini si A nitip anaknya disini"
6. Menurut google, daycare masih bisa sampai usia belasan tahun. jadi, disini saya membuat fitur lihat laporan yang bisa diakses oleh anak maupun orang tua. 


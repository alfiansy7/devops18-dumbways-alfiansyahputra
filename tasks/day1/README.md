# Day 1 - Introduction to DevOps

## 1. Definisi

<img src="images/definisi.png" width="200">

DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna menggabungkan proses development/pengembangan dari sebuah sistem/aplikasi dengan operation/operasional. DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien.

## 2.Lifecycle  

<img src="images/lifecycle.jpg" width="300">

- Continuous Development adalah pendekatan di mana tim pengembangan secara terus-menerus melakukan perubahan, peningkatan, dan pengembangan kode secara berkesinambungan. Tim ini berfokus pada menghasilkan kode yang berkualitas tinggi dengan cepat dan secara konsisten.

- Continuous Integration melibatkan integrasi kode dari berbagai anggota tim pengembangan secara otomatis dan secara berulang ke dalam satu repositori bersama. Tujuan utamanya adalah untuk mendeteksi masalah integrasi sesegera mungkin, memastikan bahwa perubahan kode yang dilakukan oleh berbagai anggota tim tidak menyebabkan konflik atau kerusakan.

- Continuous Testing adalah praktik yang melibatkan otomatisasi pengujian perangkat lunak pada setiap tahap dari siklus pengembangan. Tujuannya adalah untuk memastikan bahwa perubahan kode yang dilakukan tidak mempengaruhi fungsionalitas yang sudah ada dan untuk menemukan masalah secara dini.

- Continuous Deployment melibatkan otomatisasi dalam merilis perangkat lunak ke lingkungan produksi secara otomatis setelah melalui tahap pengujian yang berhasil. Ini memungkinkan perangkat lunak dapat dirilis lebih cepat.

- Continuous Monitoring melibatkan pemantauan sistem, kinerja, dan fungsionalitas perangkat lunak secara berkelanjutan setelah dirilis ke lingkungan produksi. Ini membantu dalam mendeteksi masalah dan ancaman keamanan, serta memberikan wawasan tentang bagaimana perangkat lunak berperforma dalam lingkungan nyata.

- Continuous Feedback melibatkan umpan balik yang diberikan secara berkelanjutan kepada tim pengembangan tentang kualitas perangkat lunak, performa, dan tanggapan pengguna. Umpan balik ini membantu tim untuk terus memperbaiki dan meningkatkan produk mereka.

- Continuous Operations melibatkan otomatisasi dalam mengelola dan memelihara lingkungan produksi serta infrastruktur perangkat lunak. Tujuannya adalah untuk memastikan ketersediaan, keandalan, dan keamanan sistem sepanjang waktu.

## 3. Instalasi Ubuntu Server

1. Klik Create a new virtual machine 
<img src="images/image001.jpg">

2. Kemudian masukan file .iso ubuntu  
<img src="images/image002.png">

3. Isikan nama vm dan lokasinya 
<img src="images/image003.png">

4. Gunakan 20gb disk dengan mode split 
<img src="images/image004.png">

5. Kemudian customize hardware 
<img src="images/image005.png">

6. Gunakan memory 2GB, 1 Core dan Network Adaptor Bridged
<img src="images/image006.jpg">

7. Finish 
<img src="images/image007.png">

8. Pilih Bahasa yang ingin digunakan 
<img src="images/image008.jpg">

9. Continue without updating karena kita akan tetap menggunakan versi 20.04 
<img src="images/image009.jpg">

10. Kemudian pilih layout keyboard yang di inginkan 
<img src="images/image010.jpg">

11. Lalu gunakan ip statik sesuai dengan subnet 
<img src="images/image011.jpg">
<img src="images/image012.jpg">

12. Custom storage layout. Root 15G dan swap 5G 
<img src="images/image013.jpg">

13. Masukan data profile 
<img src="images/image014.jpg">

14. Centang Install OpenSSH Server agar bisa di remote via ssh 
<img src="images/image015.jpg">

15. Jika button reboot now sudah muncul berarti ubuntu live server sudah berhasil di instal dan siap digunakan 
<img src="images/image016.jpg">

[**Back**](../../README.md)
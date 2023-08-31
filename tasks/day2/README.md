# Day 2 - Basic Shell & Computer Networking

## 1. Perbedaan IP Private & Public

**IP Private**

- Digunakan dalam jaringan lokal, seperti di rumah atau kantor.
- Tidak dapat diakses langsung dari Internet . Untuk mengakses Internet, IP Private harus diubah menjadi IP Public melalui mekanisme yang disebut Network Address Translation (NAT).
- Diberikan kepada perangkat dalam jaringan lokal untuk komunikasi internal antara perangkat-perangkat tersebut.
- Hanya bersifat lokal dan tidak bisa digunakan untuk mengakses Internet secara langsung.
- Memberikan keamanan tambahan karena hanya perangkat dalam jaringan lokal yang dapat mengaksesnya.

**IP Public**

- Alamat IP yang digunakan dalam jaringan global Internet.
- Diberikan oleh penyedia layanan Internet (ISP) kepada perangkat yang terhubung langsung ke Internet.
- Dapat diakses langsung dari Internet oleh perangkat di seluruh dunia.
- Digunakan untuk komunikasi antar jaringan di Internet.
- Bersifat unik dan tidak ada dua perangkat yang dapat menggunakan IP Public yang sama.
- Dapat dilacak dan diakses oleh perangkat lain di Internet.

## 2. Perbedaan IP Dynamic & Static

**IP Dynamic**

- Alamat IP yang diberikan oleh server atau router secara otomatis.
- Dapat berubah setiap kali perangkat dimatikan atau dikonfigurasi ulang.
- Umumnya digunakan dalam jaringan rumahan atau individu karena lebih mudah dikelola dan tidak memerlukan konfigurasi manual.
- Keuntungan dari IP Dynamic adalah bahwa mereka memungkinkan lebih banyak perangkat terhubung ke jaringan karena alamat IP dapat digunakan secara dinamis oleh perangkat yang berbeda.

**IP Static**

- Alamat IP yang ditetapkan secara manual pada perangkat.
- Tidak berubah kecuali diubah secara manual.
- Sering digunakan oleh layanan publik atau situs web yang memerlukan koneksi stabil dan alamat IP yang konsisten.
- Keuntungan dari IP Static adalah bahwa mereka memungkinkan untuk mengakses perangkat atau layanan yang terhubung secara langsung menggunakan alamat IP yang tetap.

## 3. Diagram Jaringan

Spesifikasi 
- CIDR Block : 192.168.1.xxx/24 (Class C)
- Subnet : 255.255.255.0
- Gateway : 192.168.1.1

<img src="dumbways-drawio.png">
[**File diagrams**](https://drive.google.com/file/d/1ZJq4o6Mjl-jUxdrPM3OtloSpXsFKylgB)

[**Back**](../../README.md)

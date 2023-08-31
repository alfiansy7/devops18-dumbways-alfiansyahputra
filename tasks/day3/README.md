# Day 3 - Application in Server

## 1. Deploy Aplikasi wayshub-frontend (NodeJS)

1.	Login ke vm terlebih dahulu
```bash
Ssh al@192.168.0.11
``` 
<img src="images/image001.png">
 
2.	Perbarui paket yang tersedia terlebih dahulu
```bash
sudo apt update
``` 
<img src="images/image002.png">

3.	Kemudian install Node Version Manager (NVM)
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
``` 
<img src="images/image003.png">

4.	Lalu restart shell
```bash
exec bash
```

5.	Instal nvm versi 16
```bash
nvm install 16
```
<img src="images/image005.png">
 
6.	Cek versi node dan npm nya
```bash
Node -v
```
```bash
Npm -v
```
<img src="images/image006.png">
 
7.	Kemudian clone wayshub-frontend
```bash
Git clone https://github.com/dumbwaysdev/wayshub-frontend.git
```
<img src="images/image007.png">
 
8.	Masuk ke folder wayshub-frontend dan instal dependensi nya
```bash
cd wayshub-frontend/
npm install
```
<img src="images/image008.png">
 
9.	Lalu jalankan aplikasinya
```bash
npm start
```
<img src="images/image009.png">
 
10.	Cek menggunakan web browser
<img src="images/image010.png">
 
## 2. Deploy Golang & Python dengan menampilkan nama masing-masing

1.	Instal golang terlebih dahulu dan switch user root
wget https://golang.org/dl/go1.16.5.linux-amd64.tar.gz && sudo su
 
2.	Hapus folder go dan extract file yang didownload tadi lalu keluar dari mode root
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.16.5.linux-amd64.tar.gz && exit
 
3.	Tambahkan environment go pada bashrc
sudo nano .bashrc
 
4.	Masukan path go di bagian paling akhir
export PATH=$PATH:/usr/local/go/bin
 

5.	Lalu cek versi go
go version
 
6.	Buat folder go dan file index.go
mkdir go && nano go/index.go 
7.	Buat script print line
 
8.	Masuk ke folder go dan jalan kan index.go
cd go && go run index.go
 

9.	Cek versi python3 dan install pip
python3 –version
 
10.	Install package manager python3
sudo apt install python3-pip -y
 
11.	Lalu install flask
Pip install flask
 
12.	Buat folder python dan index.py
Mkdir python && python/index.py
13.	Lalu masukan script berikut dan save
 
14.	Masuk ke folder python dan jalan kan index.py
cd python/
python3 index.py
 
15.	Kemudian coba menggunakan browser
 




[**Back**](../../README.md)

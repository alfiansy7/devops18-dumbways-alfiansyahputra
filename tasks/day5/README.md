# Day 5 - Version Control System

## 1. Distributed Version Control

<img src="images/dvc.jpg" width="500">

Distributed Version Control (DVC) adalah sistem manajemen versi yang digunakan untuk mengelola perubahan dalam source code atau file project perangkat lunak. DVC memungkinkan beberapa pengembang untuk bekerja pada project yang sama secara bersamaan dan melacak semua perubahan yang dibuat dalam project tersebut.

Perbedaan utama antara Distributed Version Control dengan sistem manajemen versi tradisional adalah bahwa DVC menyimpan salinan lengkap dari repositori project pada setiap komputer yang terlibat dalam pengembangan. Ini berarti setiap pengembang memiliki salinan penuh dari repositori, termasuk sejarah perubahan, sehingga mereka dapat bekerja secara mandiri tanpa koneksi internet aktif ke repositori sentral.

## 2. Create Repository

1.	Konfigurasi akun github pada server terlebih dahulu
```bash
git config --global user.name "alfiansy7"
git config --global user.email "alfiansy@yandex.com"
``` 
<img src="images/image001.png">
 
2.	Cek konfigurasi apakah sudah benar
```bash
git config --list
``` 
<img src="images/image002.png">
 
3.	Generate key ssh
```bash
ssh-keygen
``` 
<img src="images/image003.png">
 
4.	Copy isi dari id_rsa.pub yang sudah di generate tadi 
```bash
cat /home/al/.ssh/id_rsa.pub
``` 
<img src="images/image004.png">
 
5.	Add SSH Key yang sudah di generate ke akun github anda
<img src="images/image005.png">
 
6.	Kemudian lakukan pengecekan apakah akun github anda sudah berhasil terkoneksi
```bash
ssh git@github.com -T
``` 
<img src="images/image006.png">
 
7.	Membuat repositori pada github
<img src="images/image007.png">
 
8.	Membuat direktori nasi-padang dan masuk ke dalamnya
```bash
mkdir nasi-padang
cd nasi-padang/
``` 
<img src="images/image008.png">
 
9.	Membuat 3 file
```bash
echo "nasi padang pakai tunai sambel" > nasi-tuna
echo "nasi padang pakai telor dadar" > nasi-telor
echo "nasi padang pakai perkedel" > nasi-perkedel
``` 
<img src="images/image009.png">
 
10.	Inisiasi direktori
<img src="images/image010.png">
 
11.	Masukan 3 file tersebut ke dalam stage
```bash
git add .
``` 
<img src="images/image011.png">
 
12.	Commit file yang sudah masuk ke stage
```bash
git commit -m "Baru buka"
``` 
<img src="images/image012.png">
 
13.	Remote repositori yang sudah kita buat tadi
```bash
git remote add origin git@github.com:alfiansy7/nasi-padang.git
``` 
<img src="images/image013.png">
 
14.	Lalu push pada branch main
```bash
git branch -M main
git push -u origin main
``` 
<img src="images/image014.png">

15.	Cek repositori nasi-padang
<img src="images/image015.png">
 
## 3. Create Branch

1.	Buat branch staging dan production
```bash
git branch Staging
git branch Production 
``` 
<img src="images/image016.png">

2.	Cek branch yang sudah dibuat
```bash
git branch -a
``` 
<img src="images/image017.png">
 
3.	Push branch yang sudah dibuat tadi
```bash
git push --all
``` 
<img src="images/image018.png">

## 4. Git Commands

1. Membersihkan folder kerja Anda dari untracked files
<img src="images/image019.png">

```bash
git clean -f
``` 
dengan menggunakan git clean maka file uji-coba-git-clean akan terhapus karena termasuk untracked files
<img src="images/image020.png">

2. Melihat daftar commit yang ada
```bash
git log
``` 
<img src="images/image021.png">

3. Menghapus branch
<img src="images/image022.png">
Melihat branch terlebih dahulu

```bash
git branch -a
``` 
Menghapus branch

```bash
git branch -d test-branch 
``` 
<img src="images/image023.png">


[**Back**](../../README.md)

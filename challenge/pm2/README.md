# Challenge - Process Manager [PM2]

## 1. Instalasi PM2 secara global kemudian run NodeJS & Python

1.	Install pm2 secara global
```bash
npm install -g pm2
``` 
<img src="images/image001.png">

2.	Masuk ke direktori dumb-flix
```bash
cd dumbflix-frontend/
``` 
<img src="images/image002.png">
 
3.	Kemudian menjalankan npm melalui pm2
```bash
pm2 start npm --name "dumb-flix" – start
``` 
<img src="images/image003.png">
 
4.	Mencoba di web browser
<img src="images/image004.png">
 
5.	Masuk ke direktori project python
```bash
cd ../python/
``` 

6.	Lalu jalankan python dari pm2
```bash
pm2 start python3 --name "python" -- index.py
``` 
<img src="images/image006.png">
 
7.	Mencoba di web browser
<img src="images/image007.png">

[**Back**](../../README.md)
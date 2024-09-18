# Network-scanning-tools-on-kali-linux

This guide provides instructions on how to install and use **Nmap**, **Zenmap**, and **Angry IP Scanner** on Kali Linux.

## 1. Nmap
Biasanya, Nmap sudah terpasang di Kali Linux. Cek dengan:

nmap --version

Jika belum terpasang:

sudo apt install nmap

![2024-09-18_21-16_1](https://github.com/user-attachments/assets/2ce06f15-a32d-4dbb-af45-79813f95d23a)

- Penggunaan

sudo nmap casn.bulog.co.id

![2024-09-18_20-41](https://github.com/user-attachments/assets/4e56c5c2-3d64-4a9c-af77-e522901e1a14)

Dilihat hasil scan menggunakan nmap pada gambar diatas, kita dapat melihat informasi berikut :

Ip dan port yang digunakan pada website tersebut

## 2. Zenmap
Instalasi

Zenmap adalah antarmuka grafis untuk Nmap. Instal dengan:

sudo apt install zenmap
![2024-09-18_20-43](https://github.com/user-attachments/assets/1559c5f5-2683-4055-ac3b-a63682a0b2ab)
![3](https://github.com/user-attachments/assets/bc3420a0-4f0f-4c16-a99d-d44d7ec10726)

- penggunaan
  
jalankan Zenmap:

sudo zenmap

- Masukkan IP atau hostname target.

- Pilih profil scan (Quick Scan, Intense Scan, dll.).

- Klik "Scan" untuk memulai.

Zenmap memudahkan penggunaan Nmap melalui GUI.

## 3. Angry IP Scanner

1. Instalasi

Unduh paket .deb dari Angry IP Scanner GitHub Releases(https://github.com/angryip/ipscan/releases/)

![2024-09-18_21-05](https://github.com/user-attachments/assets/45ecb92c-3200-496a-a74f-a389d4b9968a)

2. Install paket dengan:

sudo dpkg -i ipscan_3.9.1_amd64.deb

![2024-09-18_21-10](https://github.com/user-attachments/assets/0b3485f7-043b-4d30-adeb-94cfd6ad047e)

- Penggunaan

1. Jalankan Angry IP Scanner
   
   ![2024-09-18_21-10_1](https://github.com/user-attachments/assets/1364c471-4c03-4c70-af5e-098702d651b8)
   
2. Masuk pada menu setting
   
   ![2024-09-18_21-11](https://github.com/user-attachments/assets/89c25abf-0551-419d-b490-395c29df1c41)
![2024-09-18_21-12](https://github.com/user-attachments/assets/570595d5-9971-400d-bfc8-3a917bc8504d)
![2024-09-18_21-13](https://github.com/user-attachments/assets/9f1d63e8-d242-4472-b75d-a9be337873d7)
![2024-09-18_21-13_1](https://github.com/user-attachments/assets/0c1b6bf6-e108-44ad-85cb-a9ec8e0ae148)

3. Masukkan rentang IP yang akan di-scan.
 
4. Klik "Start" untuk memulai scanning.
   
   ![2024-09-18_21-16](https://github.com/user-attachments/assets/85ddcb3a-efb0-4121-91f4-8ab00f270597)
![2024-09-18_21-15](https://github.com/user-attachments/assets/fd124fc5-8a4f-4d51-92cb-940fd608aa06)

Hasil scan dapat diekspor dalam format CSV atau TXT.

## Kesimpulan
- Nmap: Tools yang sangat kuat dan fleksibel untuk scanning jaringan mendalam, ideal bagi profesional keamanan jaringan yang memerlukan deteksi mendalam terhadap sistem dan layanan.

- Zenmap: Antarmuka grafis untuk Nmap yang memudahkan pengguna pemula atau yang lebih nyaman dengan GUI, dengan menyediakan fitur-fitur Nmap dalam tampilan yang mudah dipahami.
  
- Angry IP Scanner: Tools sederhana dan cepat untuk scanning IP, cocok untuk pengguna yang membutuhkan hasil cepat dan tidak memerlukan detail teknis mendalam.

Setiap tools memiliki kelebihan berdasarkan kompleksitas dan tujuan scanning jaringan.

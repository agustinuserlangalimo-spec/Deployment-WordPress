# Deployment-WordPress
ini merupakan pembuatan Deployment WordPress


## Teknologi yang Digunakan
1. Docker
2. Docker Compose
3. WordPress
4. MariaDB
5. Docker Volume
6. Docker Network
7. Git
8. GitHub
9. Ubuntu (WSL)

## Cara Menjalankan
1. Masuk ke folder project
cd ~/Deployment-WordPress
2. Menjalankan container
docker compose up -d
3. Memeriksa status container
docker ps
4. Membuka WordPress

Buka browser dan akses:

http://localhost:8080

Untuk halaman admin:

http://localhost:8080/wp-admin
5. Menghentikan container
docker compose down

## Progress Project

## mingu 1
1.Membuat repository GitHub
2.Membuat file docker-compose.yml
3.Deploy container WordPress
4.Deploy container MariaDB
5.Konfigurasi Docker Volume
6.Konfigurasi Docker Network
7.Pengujian akses WordPress
8.Pengujian penyimpanan data persisten
9.Push project ke GitHub

## minggu 2
1.Implementasi Caching Layer
Pada minggu kedua, kami berhasil mengimplementasikan Redis sebagai caching layer untuk WordPress. Redis dijalankan menggunakan Docker Container dan diintegrasikan dengan WordPress melalui plugin Redis Object Cache. Setelah konfigurasi berhasil, Redis mampu menyimpan cache query dan objek WordPress sehingga meningkatkan performa akses website.

2.Implementasi Object Storage
Kami berhasil mengimplementasikan MinIO sebagai Object Storage berbasis S3 yang berjalan pada Docker Container. MinIO digunakan sebagai media penyimpanan file upload WordPress sehingga file tidak lagi hanya tersimpan pada storage lokal container.

3.Integrasi WordPress dengan Object Storage
WordPress berhasil dikonfigurasi agar file media yang diunggah melalui dashboard WordPress secara otomatis tersimpan ke MinIO.

4.Dokumentasi dan Repository
Seluruh konfigurasi dan perubahan sistem telah didokumentasikan dan diunggah ke repository GitHub kelompok.

6.Pelatihan Cloud Computing
Seluruh anggota kelompok mengikuti course Cloud Computing pada platform bisa.ai serta menyelesaikan seluruh kuis yang disediakan.





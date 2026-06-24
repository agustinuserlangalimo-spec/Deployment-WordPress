# Deployment WordPress Cloud Computing

## Deskripsi Project

Project ini bertujuan untuk melakukan deployment WordPress menggunakan Docker Container dengan arsitektur yang terdiri dari WordPress, MariaDB, Redis Cache, dan MinIO Object Storage. Project ini dikembangkan sebagai implementasi Cloud Computing yang menerapkan konsep containerization, persistent storage, caching, object storage, serta security hardening menggunakan file .env.

## Teknologi yang Digunakan

1. Docker
2. Docker Compose
3. WordPress
4. MariaDB
5. Redis
6. MinIO
7. Docker Volume
8. Docker Network
9. Git
10. GitHub
11. Ubuntu (WSL)

## Arsitektur Project

Browser
↓
WordPress Container
↓
Docker Network
↓
MariaDB Container

Redis Container (Caching Layer)

MinIO Container (Object Storage)

## Cara Menjalankan Project

### 1. Masuk ke folder project

```bash
cd ~/Deployment-WordPress
```

### 2. Menjalankan container

```bash
docker compose up -d
```

### 3. Memeriksa status container

```bash
docker ps
```

### 4. Membuka WordPress

Frontend:

http://localhost:8080

Admin Dashboard:

http://localhost:8080/wp-admin

### 5. Membuka MinIO Dashboard

http://localhost:9001

### 6. Menghentikan container

```bash
docker compose down
```

## Progress Project

### Minggu 1 - Deployment Dasar

* Membuat repository GitHub
* Membuat file docker-compose.yml
* Deploy WordPress Container
* Deploy MariaDB Container
* Konfigurasi Docker Volume
* Konfigurasi Docker Network
* Pengujian akses WordPress
* Pengujian persistent storage
* Push project ke GitHub

### Minggu 2 - Optimasi Performa & Object Storage

* Implementasi Redis sebagai caching layer
* Integrasi Redis Object Cache pada WordPress
* Deploy MinIO Container
* Pembuatan Bucket Object Storage
* Integrasi WordPress dengan MinIO
* Pengujian upload file media
* Monitoring Redis dan MinIO
* Dokumentasi repository GitHub

### Minggu 3 - Hardening & Dokumentasi

* Memisahkan credential ke file .env
* Membuat file .env.example
* Menambahkan .gitignore
* Dokumentasi project pada README.md
* Dokumentasi kontribusi anggota
* Persiapan pengumpulan repository final

## Hasil yang Dicapai

* WordPress berjalan menggunakan Docker
* Database MariaDB terintegrasi
* Data tersimpan menggunakan Docker Volume
* Redis digunakan sebagai caching layer
* MinIO digunakan sebagai object storage
* Konfigurasi keamanan menggunakan file .env
* Project terdokumentasi dan tersimpan di GitHub

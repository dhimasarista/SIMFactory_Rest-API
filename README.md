# SimFactory REST API

SimFactory REST API adalah proyek yang dibangun dengan menggunakan bahasa pemrograman Golang dan database MySQL untuk menyediakan layanan RESTful API untuk simulasi pabrik. Aplikasi ini memungkinkan pengguna untuk mengakses dan mengelola data simulasi pabrik melalui antarmuka HTTP.

## Persyaratan

Sebelum Anda dapat mulai menggunakan API ini, pastikan Anda telah memenuhi persyaratan berikut:

- Golang (versi yang direkomendasikan: [versi Golang terbaru](https://golang.org/dl/))
- MySQL (versi yang direkomendasikan: [MySQL Community Server](https://dev.mysql.com/downloads/mysql/))
- Git (opsional, namun disarankan untuk mengelola proyek Anda)

## Instalasi

Untuk menginstal dan menjalankan API ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1. Clone repositori ini ke komputer Anda menggunakan perintah berikut:

   ```bash
   git clone https://github.com/namauser/simfactory-rest-api.git
   ```

2. Beralih ke direktori proyek:

   ```bash
   cd simfactory-rest-api
   ```

3. Salin file `.env.example` ke `.env` dan sesuaikan dengan konfigurasi MySQL Anda:

   ```bash
   cp .env.example .env
   ```

4. Instal dependensi proyek dengan menggunakan perintah:

   ```bash
   go mod tidy
   ```

5. Migrasi database dengan menjalankan perintah:

   ```bash
   go run migrate.go
   ```

6. Terakhir, jalankan aplikasi dengan perintah:

   ```bash
   go run main.go
   ```

Aplikasi akan berjalan di `http://localhost:8080` secara default.

## Penggunaan

API ini menyediakan beberapa endpoint yang dapat Anda akses untuk mengelola data simulasi pabrik. Untuk informasi lebih lanjut tentang bagaimana menggunakan API ini, lihat dokumentasi API yang tersedia di [URL dokumentasi].

## Kontribusi

Kami menyambut kontribusi dari komunitas. Jika Anda ingin berkontribusi pada proyek ini, harap ikuti pedoman kontribusi yang terdapat di [CONTRIBUTING.md].

## Lisensi

Proyek ini dilisensikan di bawah lisensi [MIT License]. Lihat berkas [LICENSE] untuk informasi lebih lanjut.

---

Silakan sesuaikan README sesuai dengan proyek Anda, tambahkan dokumentasi API yang relevan, serta buat pedoman kontribusi dan lisensi sesuai kebutuhan proyek Anda.
---
---
Jekyll adalah generator situs statis yang memungkinkan Anda membuat situs web statis tanpa perlu mengelola banyak file HTML secara manual. GitHub Pages mendukung Jekyll secara bawaan, yang mempermudah hosting situs web statis Anda.

Berikut adalah langkah-langkah umum untuk menggunakan Jekyll dan GitHub Pages:
### 1. Persiapkan Lingkungan Lokal:
- Instal Ruby: Pastikan Ruby terinstal di sistem Anda.
- Instal Bundler: Jalankan perintah gem install bundler untuk menginstal Bundler.
### 2. Buat Proyek Jekyll:
- Buka terminal dan arahkan ke direktori tempat Anda ingin membuat proyek Jekyll.
- Jalankan perintah jekyll new namaprojek untuk membuat proyek Jekyll baru. Gantilah "namaprojek" dengan nama yang Anda inginkan.
### 3. Navigasi ke Direktori Proyek:
- Masuk ke direktori proyek dengan cd namaprojek.
### 4. Jalankan Proyek Jekyll secara Lokal:
- Jalankan perintah bundle exec jekyll serve untuk menjalankan server pengembangan secara lokal.
- Buka browser dan akses http://localhost:4000 untuk melihat situs web Jekyll Anda.
### 5. Edit Konten:
- Ubah konten situs web dengan mengedit file Markdown di direktori _posts atau file lainnya di direktori proyek.
### 6. Deploy ke GitHub Pages:
- Buat repositori baru di GitHub.
- Jalankan perintah git init untuk menginisialisasi repositori git lokal.
- Tambahkan remote repository GitHub dengan perintah git remote add origin URL_REPO (ganti URL_REPO dengan URL repositori GitHub Anda).
- Buat commit untuk perubahan Anda dengan perintah git add . dan git commit -m "Commit pertama".
- Push ke GitHub Pages dengan perintah git push -u origin master.
### 7. Buka Situs di GitHub Pages:
- Buka pengaturan repositori GitHub Anda.
- Pergi ke bagian "GitHub Pages".
- Pilih branch sumber (misalnya, main atau master) dan direktori root (biasanya /).
Setelah beberapa saat, situs web Anda akan dapat diakses di URL yang disediakan oleh GitHub Pages.

Itu adalah langkah-langkah dasar untuk membuat situs web statis menggunakan Jekyll dan meng-hostingnya di GitHub Pages. Anda dapat menyesuaikan tema, menambahkan halaman, atau melakukan penyesuaian lainnya sesuai kebutuhan proyek Anda.

## Hasil Praktek
![assets](/assets/hasil-praktek-web-dinamis.PNG)





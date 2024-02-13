---
layout: post
title:  "Cara Menggunakan Perintah Git Melalui Command Prompt"
date:   2024-01-29 11:49:02 +0800
categories: github
---
Cara Menggunakan Perintah Git Melalui Command Prompt
Berikut adalah langkah-langkah dasar untuk menggunakan perintah Git melalui Command Prompt (Windows) atau Terminal (Mac/Linux):

1. Instalasi Git:
Pastikan Git sudah diinstal di sistem Anda. Jika belum, Anda dapat mengunduh dan menginstalnya dari https://git-scm.com/.

2. Buka Command Prompt atau Terminal:
* Di Windows, buka Command Prompt atau PowerShell.
* Di Mac atau Linux, buka Terminal.
3. Cek Instalasi Git:
Ketik perintah berikut untuk memastikan Git sudah terinstal dengan benar: git --version
Jika berhasil diinstal, versi Git akan ditampilkan.

4. Konfigurasi Pengguna:
Sebelum mulai menggunakan Git, Anda perlu mengonfigurasi nama pengguna dan alamat email. Ketik perintah berikut dan ganti "Nama Anda" dan "email@example.com" dengan informasi Anda:
git config --global user.name "nama anda"
git config --global user.email "email@example.com"

5. Inisialisasi Repositori (Opsional):
Jika Anda belum memiliki repositori dan ingin membuat yang baru, navigasikan ke direktori proyek Anda dan inisialisasikan repositori:
cd path/ke/direktori/proyek
git init

6. Clone Repositori (Opsional):
Jika proyek Anda sudah ada di GitHub, Anda bisa mengklon repositori tersebut ke komputer lokal:
git clone https://github.com/username/nama-repositori.git

7. Tambahkan File ke Repositori:
Tambahkan file ke repositori Git dengan perintah add:
git add nama_file
Jika ingin menambahkan semua file, gunakan:
git add .

8. Buat Commit:
Buat commit untuk menyimpan perubahan yang telah ditambahkan:
git commit -m "Pesan commit"

9. Hubungkan dengan Repositori Remote:
Jika proyek Anda ada di GitHub, hubungkan repositori lokal dengan repositori di GitHub:
git remote add origin https://github.com/username/nama-repo.git

10. Kirim Perubahan ke Repositori Remote:
Kirim commit ke repositori di GitHub:
git push -u origin master
Gantilah "master" dengan nama branch yang sesuai jika Anda menggunakan branch lain.

11. Update dan Ambil Perubahan Terbaru:
Untuk mengambil perubahan terbaru dari repositori remote: Ini memperbarui repositori lokal dengan perubahan terbaru dari repositori di GitHub.
git pull origin master
Itulah beberapa perintah Git dasar yang dapat Anda gunakan melalui Command Prompt atau Terminal. Pastikan Anda berada dalam direktori proyek yang benar dan sudah mengonfigurasi informasi pengguna dengan benar sebelum mulai
---
layout: post
title:  "install Jekyll!"
date:   2024-01-25 11:49:02 +0800
categories: jekyll update
---
Instal Ruby:

Kunjungi situs resmi RubyInstaller di https://rubyinstaller.org/.
Unduh versi RubyInstaller yang stabil (pilih versi yang direkomendasikan).
Saat menginstal, pastikan Anda memeriksa opsi "Add Ruby executables to your PATH" agar perintah Ruby dapat diakses dari Command Prompt atau PowerShell.
Buka Command Prompt atau PowerShell:

Setelah instalasi Ruby selesai, buka Command Prompt atau PowerShell untuk melakukan instalasi selanjutnya.
Instal Jekyll dan Bundler:

Ketik perintah berikut dan tekan Enter:
bash
Copy code
gem install jekyll bundler
Buat Proyek Jekyll Baru:

Pilih atau buat direktori di mana Anda ingin membuat situs Jekyll.
Pindah ke direktori tersebut melalui Command Prompt atau PowerShell.
Jalankan perintah berikut untuk membuat proyek Jekyll baru:
bash
Copy code
jekyll new nama-situs
Pindah ke Direktori Proyek:

Pindah ke direktori proyek yang baru dibuat dengan perintah:
bash
Copy code
cd nama-situs
Jalankan Server Lokal:

Jalankan server lokal dengan perintah:
bash
Copy code
bundle exec jekyll serve
Buka browser dan kunjungi http://localhost:4000/ untuk melihat situs Jekyll Anda.
Selesai:

Sekarang, Anda seharusnya memiliki server lokal Jekyll yang berjalan dan dapat mengakses situs web di browser Anda.
Penting: Pastikan bahwa Anda memiliki koneksi internet saat pertama kali menjalankan bundle exec jekyll serve, karena Bundler akan mengunduh dan menginstal dependensi proyek Jekyll. Setelah dependensi terinstal, Anda dapat menjalankan server secara offline.
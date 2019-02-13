---
title: "Cara Instal Linux Ubuntu 16"
date: 2019-02-13T17:56:22+07:00
draft: false
author: "asfah"
image: "/linux/ubuntu.jpg"
---

Booting Menggunakan DVD/USB Ubuntu
Anda dapat mendownload Ubuntu di : https://www.ubuntu.com/download/desktop

Untuk membuat Bootable USB/DVD berikut panduannya : Cara Membuat Bootable USB/DVD

Setelah mempunyai Bootable USB/DVD berisikan Ubuntu, restart PC anda, jangan lupa untuk setting bios agar booting menggunakan USB/DVD terlebih dahulu sebelum masuk ke HardDisk.

Berikut tampilan booting awal Ubuntu:

ubuntu_014

Welcome Screen
Anda akan disambut dengan welcome screen berisi pilihan bahasa, dan pilihan menu untuk mencoba Ubuntu menggunakan Live CD, atau menginstallnya langsung.
ubuntu_015

Tampilan “Try Ubuntu” dari LiveCD
Anda dapat mencoba mengexplore Ubuntu dari Live CD, jika anda merasa cocok dan ingin menginstallnya, klik icon CD dengan teks “Install Ubuntu 16.04.1 LTS”
ubuntu_016

Persiapan Install
Silakan pilih bahasa yang akan digunakan pada Ubuntu.
ubuntu_017Jika anda terhubung ke internet, dan ingin meng-install driver seperti graphic, Wifi, MP3 dan lainnya silakan centang pada pilihan kedua, jida tidak langsung klik “Continue”.
ubuntu_018“Erase disk and install Ubuntu” akan mem-format seluruh isi harddisk anda, dan Ubuntu akan membuat default partisi. Jika anda yakin dengan pilihan ini, anda bisa klik “Continue”. Atau memilih “Something else” untuk menentukan partisi dan alokasi sendiri.
ubuntu_019Disini anda dapat melihat daftar harddisk anda. “/dev/sda” berarti harddisk pertama anda. jika anda menghubungkan PC dengan 2 harddisk, maka akan tampil “dev/sdb”.
ubuntu_020Klik harddisk yang akan di-install Ubuntu, lalu klik “newPartition Table” untuk membuat Partisi. Klik continue ketika muncul pesan konfirmasi untuk membuat partisi baru.
ubuntu_021Pada tampilan berikut terlihat alokasi hardisk yang tersedia, yaitu 8.5GB. klik pada baris tersebut lalu klik tombol “+” untuk membuat partisi baru.
ubuntu_022Berikut kita membuat partisi untuk swap, dengan alokasi 1GB. Klik “OK” untuk melanjutkan.
ubuntu_023Partisi swap berhasil dibuat, klik “free space” lagi dan klik tombol “+” untuk membuat partisi baru lagi.
ubuntu_024Selanjutnya kita membuat partisi dengan format Ext4 yang akan digunakan sebagai root folder “/” sebesar 7.5GB. Root folder “/” akan berisikan filesystem dan direktori home. Klik “OK” untuk lanjut.
ubuntu_025Hasil akhir partisi akan sebagai berikut.
ubuntu_026Anda juga dapat memisahkan direktori home anda dengan partisi lain dari root folder.
ubuntu_027Dalam postingan ini saya tetap menggunakan 2 partisi. Berikut tampilan konfirmasi ketika akan menyimpan perubahan partisi. klik “Continue” untuk lanjut.
ubuntu_028Pilih zona waktu yang anda inginkan dengan klik pada peta, lalu klik “Continue”.
ubuntu_029Pilih layout keyboard yang sesuai dengan keyboard anda, lalu klik “Continue”.
ubuntu_030Isikan detail user yang akan digunakan pertama kali, lalu klik “Continue”.
ubuntu_031Silakan tunggu sampai proses instalasi selesai.
ubuntu_032Setelah proses instalasi selesai, anda dapat melanjutkan mencoba Ubuntu dari LiveCD atau langsung me-restart PC anda untuk menggunakan Ubuntu yang telah diinstal.
ubuntu_033

Tampilan Ubuntu
ubuntu_034
ubuntu_035
ubuntu_036
ubuntu_037
ubuntu_038
ubuntu_039

Sekian penjelasan mengenai cara install Ubuntu 16.04, apabila anda mengalami kendala dalam proses instalasi, silakan tinggalkan komentar dibawah. Jika anda merasa tutorial cara install Ubuntu ini bermanfaat bagi teman anda, anda bisa membagikannya menggunakan tombol share dibawah.
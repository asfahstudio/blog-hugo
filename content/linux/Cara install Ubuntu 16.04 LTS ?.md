---
title: "Cara Install Ubuntu 16"
date: 2019-02-15T13:28:51+07:00
draft: false
author: "asfah"
image: "/linux/install-ubuntu.png"
---

basa-basi.........

instalasi linux di artikel ini adalah instalasi yang sederhana atau untuk pemula, untuk instalasi yang lebih kompleks mungking akan saya bagikan di artikel selanjutkan dilain waktu.

.

.

.

core in the core.........

## **Install Ubuntu 16.04 LTS ?**

.

**Persiapan yang dibutuhkan**

- niat
- komputer/laptop
- Bootable Ubuntu Flashdisk/DVD (recommended pakai flashdisk pakai aplikasi rufus)
- action
  
**Action**

- Colokan Flashdisk.
- Hidupkan komputer masuk ke BIOS.
- Ubah Booting pertama pertama dengan yang USB Bootable di atasnya Hardisk.
- Anda akan disambut dengan welcome screen berisi pilihan bahasa, dan pilihan menu untuk mencoba Ubuntu menggunakan Live CD, atau menginstallnya langsung.
- Anda dapat mencoba mengexplore Ubuntu dari Live CD, jika anda merasa cocok dan ingin menginstallnya, klik icon CD dengan teks “Install Ubuntu 16.04.1 LTS”
- Silakan pilih bahasa yang akan digunakan pada Ubuntu.
- Jika anda terhubung ke internet, dan ingin meng-install driver seperti graphic, Wifi, MP3 dan lainnya silakan centang pada pilihan kedua, jida tidak langsung klik “Continue”.
- “Erase disk and install Ubuntu” akan mem-format seluruh isi harddisk anda, dan Ubuntu akan membuat default partisi. Jika anda yakin dengan pilihan ini, anda bisa klik “Continue”. Atau memilih “Something else” untuk menentukan partisi dan alokasi sendiri. Saya sarankan pilih “Something else” untuk membagi partisi sendiri.
- Klik harddisk yang akan di-install Ubuntu, lalu klik “newPartition Table” untuk membuat Partisi. Klik continue ketika muncul pesan konfirmasi untuk membuat partisi baru.
- Pada tampilan berikut terlihat alokasi hardisk yang tersedia, yaitu ukurannya sesuai size yang anda punya/digunakan misal ukuran yang digunakan (8.5 GB). klik pada baris tersebut lalu klik tombol “+” untuk membuat partisi baru.
- Berikut kita membuat partisi untuk swap, dengan alokasi 1GB. Klik “OK” untuk melanjutkan.
- Partisi swap berhasil dibuat, klik “free space” lagi dan klik tombol “+” untuk membuat partisi baru lagi.
- Selanjutnya kita membuat partisi dengan format Ext4 yang akan digunakan sebagai root folder “/” sebesar 7.5GB. Root folder “/” akan berisikan filesystem dan direktori home. Klik “OK” untuk lanjut.
- Hasil akhir partisi akan sebagai berikut.
- Anda juga dapat memisahkan direktori home anda dengan partisi lain dari root folder.
- Dalam postingan ini saya tetap menggunakan 2 partisi. Berikut tampilan konfirmasi ketika akan menyimpan perubahan partisi. klik “Continue” untuk lanjut.
- Pilih zona waktu yang anda inginkan dengan klik pada peta, lalu klik “Continue”.
- ilih layout keyboard yang sesuai dengan keyboard anda, lalu klik “Continue”.
- Isikan detail user yang akan digunakan pertama kali, lalu klik “Continue”.
- Silakan tunggu sampai proses instalasi selesai.
- Setelah proses instalasi selesai, anda dapat melanjutkan mencoba Ubuntu dari LiveCD atau langsung me-restart PC anda untuk menggunakan Ubuntu yang telah diinstal.

Demikian tutorial instal ubuntu 16.04 LTS, semoga bermanfaat.

*sumber: [asfahstudio](https://asfahstudio.github.io), [blabak.com](https://blabak.com/ "wajib dikunjungi")*
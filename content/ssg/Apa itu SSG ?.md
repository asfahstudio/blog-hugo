---
title: "Apa Itu SSG ?"
date: 2019-02-15T13:32:17+07:00
draft: false
author: "asfah"
image: "/ssg/ssg.png"
---

core in the core.........

#### **Apa Itu Static Site Generator (SSG) ?**

Static site generator (selanjutnya disingkat SSG) adalah sebuah software yang fungsinya men-generate halaman-halaman website statis. File yang dihasilkan berupa HTML, CSS dan Javascript. Susunan file dan direktori yang dihasilkan oleh SSG sudah rapi teratur sesuai dengan aturan navigasi yang telah disusun oleh usernya. SSG ini ada banyak, beberapa diantaranya: Jekyll, Hugo, Hexo, dll. Saya sendiri memutuskan untuk memakai SSG Hugo.

Berbeda dengan WordPress yang menghasilkan halaman website dinamis dengan PHP dan konten dari database, SSG ini sudah terlebih dahulu menyajikan file website statis untuk kemudian diupload ke server (deploy). Cara mengisi kontennya juga tentu saja berbeda. Jika di WordPress user bisa langsung mengisi konten website via browser, pada SSG user harus membuat konten di text editor dalam format file MD lalu kemudian men-generate website. Memang lebih repot apabila dibandingkan dengan WordPress, penggunanya juga memerlukan sedikit pengetahuan mengenai cara kerja deployment SSG.

#### **Kelebihan Static Site Generator Dibandingkan Dengan WordPress**

Ada beberapa kelebihan SSG yang membuat saya tertarik dan mempertimbangkan untuk menggunakannya di proyek-proyek mendatang.

- Website SSG lebih aman

    Karena tidak menggunakan database dan plugin-plugin third-party seperti pada WordPress, website SSG pastinya lebih aman. Namanya juga file statis, mau di hack begimana coba? Terkecuali jika hackernya membobol server dimana file SSG ini di-host, tapi pada dasarnya tidak ada celah keamanan pada file HTML dan CSS yang digenerate SSG.

- Loading website lebih cepat

    Bukan rahasia lagi untuk semua pengguna WordPress non-hosted jika loading time selalu menjadi masalah yang perlu diselesaikan dengan berbagai solusi. Penggunaan plugin cache dan hosting dengan spesifikasi mumpuni selalu menjadi daftar checklist para pengguna WordPress non-hosted yang menginginkan performa website cepat.

    Loading website ini termasuk faktor yang penting di dunia web development karena akan berpengaruh terhadap keberhasilan SEO sebuah website. Beberapa pengguna SSG bahkan ada yang mengklaim bahwa websitenya mendapatkan peringkat baik di Google karena sangat cepat loadingnya.

    Jujur saja karena faktor waktu loading website inilah yang membuat saya sangat tertarik pada SSG.

- Layout website dapat di-customized lebih leluasa

    Setelah menggunakan SSG Hugo beberapa waktu, saya merasa teknologi themes WordPress tertinggal sangat jauh dibandingkan dengan kemampuan customization SSG. Secara sederhana, kustomisasi themes WordPress akan hanya mentok sejauh mana themes yang dipakai bisa di-customize, tapi pada SSG anda benar-benar bebas memilih themes, bahkan halaman website yang satu dapat menggunakan themes yang berbeda dengan halaman lainnya. Benar-benar kemampuan yang tidak akan anda lihat di WordPress.

*sumber: [digiweb.co.id](https://www.digiweb.co.id "wajib di kunjungi")*
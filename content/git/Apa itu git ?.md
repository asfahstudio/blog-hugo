---
title: "Apa Itu Git ?"
date: 2019-02-15T13:30:16+07:00
draft: false
author: "asfah"
image: "/git/git.png"
---

basa-basi.........

Sebelum kita membahas tentang apa itu git, alangkah baiknya kita mengetahui hal-hal berikut ini:

- Makhluk apakah Version Control itu?
- Tipe-tipe Version Control

### Version Control ?

Sebagai seorang coder, sangatlah wajar jika anda mengubah atau merevisi code anda berpuluhan kali bahkan beratus-ratus kali. Dan revisi code ini seringkali dilakukan di lebih dari satu file. Bayangkan jika saat anda sudah melakukan revisi di puluhan file untuk menambahkan fitur A di code anda, tapi tak lama kemudian anda diminta oleh bos anda untuk membatalkan fitur A tersebut. Anda bisa jadi akan mengalami kesulitan untuk mengembalikannya. Jangan kuatir, disini version control bisa membantu anda.

Version control adalah sebuah sistem yang mencatat setiap perubahan terhadap file dan folder. Catatannya pun dilengkapi dengan informasi atas apa saja perubahan yang terjadi, tanggal, dan pelaku perubahannya. Dengan menggunakan version control, coder dapat dengan mudah untuk berpindah dari satu revisi ke revisi lain.

Berkerja dan berkolaborasi dalam tim pun akan terbantu dengan version control. Salah satu alasannya adalah jika ada sebuah file yang diubah secara bersamaan oleh dua coder yang berbeda, version control bisa mengetahuinya. Maka karena itu penggunaan version control adalah wajib hukumnya untuk pengembangan software dalam sebuah tim. Jika anda bekerja sendiri pun, sangat direkomendasikan untuk menggunakan version control.

Jika anda masih berpikir menggunakan Version Control adalah hal yang percuma, coba perhatikan coder-coder kelas dunia di Google, Facebook, dll. Mereka orang-orang pintar yang belajar dari pengalaman pribadi bahwa menggunakan Version Control membantu produktifitas mereka.

### Tipe-tipe Version Control ?

Terdapat dua jenis Version Control:

**Version Control System Terpusat.**

- Sistem ini menggunakan sebuah server untuk menyimpan semua data.
- Kelebihannya adalah coder hanya perlu untuk mensalin data tertentu, sehingga lebih irit storage.
- Kekurangannya adalah coder harus terhubung ke server jika ingin mencatat perubahan, melihat perubahan, dll. Dan server bisa jadi akan sangat sibuk jika ada banyak coder yang terhubung.

**Version Control Terdistribusi.**

- Semua coder akan menyimpan semua data.
- Kelebihannya adalah coder bisa melakukan operasi terhadap version control tanpa perlu terhubung ke komputer lain. Dan operasinya akan sangat cepat karena hanya di komputer lokal dan tidak ada coder lain yang terhubung.
- Kekurangannya adalah akan banyak menggunakan storage. Akan tetapi umumnya ukuran code sangat kecil karena hanya teks saja, dan juga sekarang harga storage semakin murah.

Git adalah salah satu program version control, dan Git termasuk ke dalam Version Control Terdistribusi.

.

.

.

core in the core.........

## **Git ?**

Git dibuat oleh Linus Torvalds. Beliau adalah bapak kandung dari Linux. Linus membuat Git untuk membantu pengembangan dari Linux. Dan Git (seperti Linux) merupakan software yang free dan open source. Hebat kan Linus? Karyanya bagus, banyak, dan selalu digratiskan.

Anyway, alasan Linus memilih Git menggunakan Version Control Terdistribusi adalah karena Linux memiliki lebih dari 12 ribu coder! Bisa dibayangkan jika menggunakan Version Control Terpusat, seberapa sibuknya server jika coder sebanyak itu terhubung. Dan juga, banyak coder yang tidak bisa selalu terhubung ke internet dan itu bisa mengakibatkan mereka kesulitan untuk berkerja.

Dewasa ini Git adalah version control yang paling umum digunakan dalam pengembangan software, bahkan di perusahaan-perusahaan terkemuka dunia. Karena dengan Git, anda bisa bekerja dengan lebih baik dan efisien. CodeSaya sudah barang tentu dikembangkan dengan perkakas Git.

*sumber: [codesaya.com](https://codesaya.com "wajib di kunjungi")*
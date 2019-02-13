---
title: "Command Dasar Linux"
date: 2019-02-13T17:56:47+07:00
draft: false
author: "asfah"
image: "/linux/command.jpg"
---

Perintah Dasar Linux
Berikut ini adalah beberapa perintah dasar Linux yang banyak digunakan:

pwd
Ketika Anda pertama kali membuka terminal, Anda akan masuk ke home directory user Anda. Untuk tahu directory mana yang sedang Anda buka, Anda bisa menggunakan command pwd ini. Dengan command ini, mereka akan memberitahu path-nya dimulai dari root. Root adalah awalan dari sistem file Linux. User directory biasa memiliki format seperti “/home/username”.

Is
Gunakan command “Is” untuk mengetahui file apa saja yang ada pada directory yang sedang Anda buka. Anda bisa melihat files tersembunyi dengan menggunakan command “Is-a”.

cd
Gunakan command “cd” untuk masuk ke sebuah directory. Misalnya, jika Anda sedang ada di folder home dan Anda ingin masuk ke folder downloads, Anda bisa memasukkan command “cd Downloads”. Command yang satu ini sangat case sensitive jadi Anda perlu memasukkan nama foldernya dengan tepat. Selain itu, jika folder Anda terdiri dari dua nama atau lebih, Anda perlu memasukkan tanda \ di antara nama foldernya. Misalnya, Anda memiliki sebuah folder yang diberi nama “Dewa Web”. Jika Anda memasukkan command “cd Dewa Web”, Anda akan mendapat pesan error. Jadi, Anda perlu memasukkan commandnya sebagai “cd Dewa\Web”. Kalau Anda hanya memasukkan “cd” Anda akan dibawa ke home directory. Untuk kembali ke folder sebelumnya, Anda tinggal memasukkan “cd..”. Titik dua setelah cd memiliki arti “kembali” atau back.

mkdir & rmdir
Gunakan command mkdir ketika Anda perlu membuat folder atau directory. Misalnya, Anda ingin membuat sebuah directory dengan nama “Baru”, maka Anda tinggal memasukkan command “mkdir Baru”. Kalau Anda ingin membuat directory dengan lebih dari satu kata pada namanya, sama seperti di perintah dasar linux sebelumnya, Anda perlu menggunakan tanda \. Jadi, Anda harus ketik “mkdir Folder\Baru”.

Command rmdir digunakan untuk menghapus directory. Tetapi perintah dasar linux yang ini hanya bisa digunakan untuk menghapus directory kosong. Kalau Anda ingin menghapus directory yang masih berisi files, gunakan command rm yang akan dibahas di bawah ini.

rm
Gunakan command rm untuk menghapus file dan direktori. Jadi misalnya Anda ingin menghapus file yang bernama “lama.html”, Anda tinggal masukkan command “rm lama.html”. Tetapi perintah dasar ini tidak bisa sembarangan menghapus direktori. Gunakan rm-r untuk menghapus direktori. Ini akan menghapus direktori dan isinya.
## Login Github

Langkah kedua dalam belajar menggunakan Git adalah Anda harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.

Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini.

![15-screenshoot](/image/Screenshot_201.png)

## membuat repository

Setelah melakukan install git, langkah selanjutnya adalah memulai untuk menggunakan Github dan membuat repository baru untuk aplikasi yang kita buat agar tersimpan dalam sistem versi kontrol dari Github.
Pertama login di situs Github dengan username dan password anda, kemudian klik Create New Repository.

![16-screenshoot](/image/Screenshot_202.png)

Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.

Anda perlu mengisi detail informasi berikut:

 * Nama Repository : digunakan untuk identitas repository yang dibuat.
 * Deskripsi Repository : berfungsi untuk deskripsi dari repository yang dibuat.
 * Jenis Repository   : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.

Setelah mengisi detail informasi di atas, klik Create Repository.

## Buat Folder pada Windows

Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.

![17-screenshoot](/image/Screenshot_203.png)

## Buka Folder Menggunakan Git Bash
cara install git

![18-screenshoot](/image/Screenshot_204.png)

Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 

![19-screenshoot](/image/Screenshot_205.png)

## Ubah Folder Menjadi Repository

Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:

$ git init

![20-screenshoot](/image/Screenshot_206.png)

## Tambahkan File ke Repository

Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:

    Buat file di folder yang sudah dibuat (Test Git). Contohnya, di sini kami membuat file index.php
    Buka GitBash lalu masukkan perintah berikut:

$ git add index.php

Perintah tersebut tidak akan menghasilkan output apa pun.

## Buat Commit 

Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "first commit"

Pada tutorial ini kami membuat first commit sebagai Commit pertama kami. Anda bebas membuat membuat nama Commit apa saja.

![21-screenshoot](/image/Screenshot_207.png)

## Remote Repository Github

Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:

$ git remote add origin git@github.com:UserNameGit/NamaRepository.git

Perintah di atas tidak akan menghasilkan output apa pun.

![22screenshoot](/image/Screenshot_208.png)

## Push ke GitHub 

Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:

git push -u origin master

Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub. 

![23screenshoot](/image/Screenshot_209.png)

Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah

![24screenshoot](/image/Screenshot_210.png)

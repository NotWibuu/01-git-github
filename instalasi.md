## Langkah-Langkah Mendownload GIT

* Sebelum menggunakan GIT, anda harus terlebih dahulu mendownload GIT [di sini](https://git-scm.com/downloads)
* Sesuaikan sistem operasi yang akan anda gunakan sebelum memulai proses mendownload
* Ada tiga jenis Sistem Operasi yang dapat menggunakan GIT yaitu Windows, Linux, dan macOS
* Untuk GIT versi windows sendiri memiliki versi yang 32 bit dan 64 bit, sesuaikan dengan versi OS Windows yang anda miliki

## penginstalan Git

* Install Git
Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.

![01-screenshoot](/image/Screenshot_181.png)

* Tentukan Lokasi Instalasi Git
Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini kami menginstall di lokasi C:\Program Files\Git. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan .

![02-screenshoot](/image/Screenshot_182.png)

* Pilih Komponen Tambahan
Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.

![03-screenshoot](/image/Screenshot_183.png)

* Tentukan Nama Aplikasi Git
Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja.  

![04-screenshoot](/image/Screenshot_184.png)

* Tentukan File Editor
Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pada tutorial ini, kami menggunakan Vim Editor. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.

![05-screenshoot](/image/Screenshot_185.png)

* Atur Path Environment
Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.

![06-screenshoot](/image/Screenshot_186.png)

* Pilih Aplikasi SSH
Kemudian untuk mengeksekusi SSH, Anda bisa menggunakan aplikasi dari Git atau  dari platform lain seperti PuTTY dan Bitvise. Pada tutorial ini kami menggunakan Use OpenSSH, aplikasi default SSH dari Git. Klik Next untuk melanjutkan instalasi.

![07-screenshoot](/image/Screenshot_192.png)

* Pilih Line Ending
Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih Checkout Windows-style, commit Unix-style line endings. Klik Next untuk melanjutkan instalasi.

![08-screenshoot](/image/Screenshot_189.png)

* Pilih Emulator Terminal
Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pada tutorial ini kami memilih Use Windows’ default console windows. Klik Next untuk melanjutkan instalasi.

![09-screenshoot](/image/Screenshot_190.png)

* Tentukan Opsi ekstra
Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik Next untuk melanjutkan instalasi.

![10-screenshoot](/image/Screenshot_191.png)

* Mulai Proses Instalasi
Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.

![11-screenshoot](/image/Screenshot_193.png)

Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.

![12-screenshoot](/image/Screenshot_193.png)

* Cek Versi Git
Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.

![13-screenshoot](/image/Screenshot_196.png)

Selanjutnya masukkan perintah berikut untuk cek versi git dan cek apakah Git sudah terinstall di komputer Anda.
git --version
Jika Git berhasil terinstall, Anda akan melihat tampilan seperti di bawah ini yang menunjukkan versi Git. 

![14-screenshoot](/image/Screenshot_197.png)

## Tahap konfigurasi

Untuk konfigurasi dapat langsung membuka Git Bash dan gunakan perintah:


        $ git config --global user.name "user name di GitHub"
        $ git config --global user.email alamat@email.github

Untuk melihat konfigurasi, dapat menggunakan perintah:


        $ git config --list
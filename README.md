# Penggunaan GIT

# Apa Itu GIT ?
* Git adalah salah satu sistem pengontrol versi(Version Control System) pada proyek perangkat lunak yang diciptakan Linus Torvalds.
* Pengontrol versi bertugas memcatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.
# Instalasi GIT
* Download **GIT**, Buka website resminya Git [git-scm.com](https://git-scm.com).
* Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
* Selamat, Git sudah terinstal. Untuk mencobanya,silahkan buka **Terminal** atau **CMD**,kemudian ketik perintah <br>
```git --version.``` <br>

![git --version](https://fajars.space/ngampus/pemrograman/git/img/1.png)

# Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.
* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah ```git commit```
* Config Global Repository

``$ git config --global user.name "nama_user"``

``$ git config --global user.email "nama_user"``

# Perintah Dasar Git
* ``git init`` , perintah untuk membuat repository local
* ``git add``, perintah untuk menambahkan file baru, atau perubahan pada file
pada staging sebelum proses commit.
* ``git commit``, perintah untuk menyimpan perubahan kedalam database git.
* ``git push -u origin master``, perintah untuk mengirim perubahan pada repository local menuju server repository.
* ``git clone [url]``, perintah untuk membuat working directory yang diambil dari repositry sever.
* ``git remote add origin [url]``, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
* ``git pull``, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

# Membuat Reposiory Local
* Buka direktory aktif, misal: '/Desktop/belajar-git'
* Drop direktori ke terminal / CMD
* Buat direktory project praktikum pertama dengan nama latihan1

 &emsp ``$ mkdir latihan1``
 
 &emsp ``$ cd latihan1``
 
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)
* direktory aktif menjadi: /Desktop/belajar-git/latihan1

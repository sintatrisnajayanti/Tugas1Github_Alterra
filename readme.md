# Resume Materi Version Control and Branch Management (Git)

## Version Control System 

Version Control System atau VCS adalah sebuah kumpulan perangkat lunak yang digunakan untuk membantu mengelola source code pada program dari waktu ke waktu. Pada Version Control System, versioning digunakan untuk mengatur versi source code pada program. Dimana contohnya jika kita melakukan sebuah revisi terus menerus dan cukup maka terlihat riwayat perubahan yang terjadi. Saat membuat proyek dan berkolaborasi dengan banyak orang, Version Control System digunakan untuk mengetahui perubahan apa saja yang sudah dilakukan oleh rekan yang lain. Salah satu Version Control System populer yang digunakan para developer untuk mengembangkan software secara bersama-bersama yaitu GIT. 

Jenis-jenis Version Control System: 
* Single User
* Centralized
* Distributed

## Git

Git merupakan Salah satu version control system populer yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Git ini diciptakan oleh Linus Torvalds pada tahun 2005. Git dapat melacak setiap perubahan file yang dilakukan oleh semua rekan proyek. Git juga dapat membatalkan ke beberapa point perubahan dengan menggunakan commit. Cukup rumit untuk mengatur server Git maka dibutuhkan layanan untuk menjadi server contoh yang banyak digunakan yaitu Github. 

## Penggunaan Git pada layanan Github

Github kini hadir sebagai layanan hosting untuk repositori Git. Pada penggunaan suatu Git, langkah pertama dilakukan pembuatan repository baru pada github. Setelah itu kode program di local yang sudah dibuat dapat di push ke github dengan melakukan commit. Rekan kolabolator lain dapat melakukan pull untuk memperoleh data dari kode program yang telah disimpan pada repository git hosting service. Kemudian dilakukan branching pada repository tersebut agar pembuatan perubahan pada Kode Program lebih mudah. Pada branching dilakukan dengan memisahkan branch master dan develop serta membuat branch baru untuk setiap fitur yang sedang dikembangkan. Kemudian untuk setiap fitur tersebut akan dilakukan merge ke develop jika fitur tersebut sudah bekerja dengan maksimal. Lalu branch develop akan di merge ke branch master apabila proses pengembangan telah selesai. Hal ini bertujuan untuk meng-deploy fitur baru yang ditambahkan.

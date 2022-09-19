<p><img src="img/Picture2.png"></p>

<p align="justify">Komponen Sistem Operasi
Terdapat tiga elemen dasar yangmembangun   perancangan   sistem operasi secara umum. Komponen- komponen ini dapat disebut modular karena memiliki fungsi yang berbeda dan  dapat dikembangkan  secara terpisah. Ketiga bagian tersebut antara lain:

1. User Interface.
2. Kernel.
3. sistem manajemen file.

<p align="justify">Pada kenyataannya tidak semua sistem operasi mempunyai struktur yang sama. Namun menurut Avi Silberschatz, Peter Galvin, dan Greg Gagne, umumnya sebuah sistem operasi modern mempunyai komponen sebagai berikut:

1. Managemen Proses.
2. Managemen Memori Utama.
3. Managemen Secondary-Storage.
4. Managemen Sistem I/O.
5. Managemen Berkas.
6. Sistem Proteksi.
7. Jaringan.
8. Command-Interpreter system.

<p align="justify">Dara pembagian diatas bisa saya jelaskan lebih lanjut melalui keterangan dibawah ini;

<br>
<p><img src="img/12.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Proses adalah keadaan ketika sebuah program sedang di eksekusi. Sebuah proses membutuhkan beberapa sumber daya untuk menyelesaikan tugasnya. sumber daya tersebut dapat berupa CPU time, memori, berkas-berkas, dan perangkat-perangkat I/O.
Sistem operasi bertanggung jawab atas aktivitas-aktivitas yang berkaitan dengan managemen proses seperti:

### 1. Pembuatan dan penghapusan proses pengguna dan sistem proses.

<p>menghapus program yang sedang berjalan di laptop pada sistem operasi linux</p>

<p align="center">
masuk ke menu pencarian lalu tuliskan system monitor kemudian pilih<br><br><img src="img/1 (19).png" height="300"></p>

<p align="center">
maka akan muncul tampilan ini di sini kita bisa melihat program apa saja yg sedang berjalan di <br>laptop kita untuk menghapus proses silahkan pilih program yg ingin di hapus lalu klik end task<br><br><img src="img/1 (20).png" height="300"></p>

### 2. Menunda atau melanjutkan proses.
contoh menunda dan melanjutkan proses download pada linux

<p align="center">
pada tampilan terlihat saya sedang mendownload klik kanan pada mouse lalu pilih<br> pause maka proses mendownload akan di tunda <br><br><img src="img/1 (26).png" height="300"></p>

<p align="center">
dan jika ingin melanjutkan proses download maka klik kanan pada mouse lagi<br> lalu pilih resume untuk melanjutkan proses downloadan tadi<br><br><img src="img/1 (26).png" height="300"></p>

### 3. Menyediakan mekanisme untuk proses sinkronisasi.
contoh proses sinkronisasi pada whatsapp yang ada di android dengan di laptop melalui whatsapp web di linux.

<p align="center">
pertama buka mozila firefox<br><br><img src="img/1 (21).png" height="300"></p>

<p align="center">
lalu klik kan di pencarian whatsapp web<br><br><img src="img/1 (16).png" height="300"></p>

<p align="center">
lalu singkronisasikan whatsapp yang ada di handphone dengan yang ada di laptop <br> menggunkan QR CODE maka whatsappmu akan tersinkron dengan yang ada pada laptop<br><br><img src="img/1 (17).png" height="300"></p>

<hr>
<br>
<p><img src="img/13.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Memori utama atau lebih dikenal sebagai memori adalah sebuah array yang besar dari word atau byte, yang ukurannya mencapai ratusan, ribuan, atau bahkan jutaan. Setiap word atau byte mempunyai alamat tersendiri. Memori Utama berfungsi sebagai tempat penyimpanan yang akses datanya digunakan oleh CPU atau perangkat I/O. Memori utama termasuk tempat penyimpanan data yang sementara (volatile), artinya data dapat hilang begitu sistem dimatikan.

Sistem operasi bertanggung jawab atas aktivitas-aktivitas yang berkaitan dengan managemen memori seperti:

1. Menjaga track dari memori yang sedang digunakan dan siapa yang
menggunakannya.
2. Memilih program yang akan di-load ke memori.
3. Mengalokasikan dan meng-dealokasikan ruang memori sesuai kebutuhan.

### contoh untuk melihat penggunaan memori di terminal linux.
<p align="center"><br><br><img src="img/memory1.png" height="300"></p>

### info memory di terminal linux.
<p align="center"><br><br><img src="img/memory2.png" height="300"></p>

### untuk melihat penggunaan memori di cmd windows.
<p align="center"><br><br><img src="img/memori4.png" height="300"></p>
<p align="center"><br><br><img src="img/memori5.png" height="300"></p>

<hr>

<br>
<p><img src="img/15.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Data yang disimpan dalam memori utama bersifat sementara dan jumlahnya sangat kecil. Oleh karena itu, untuk meyimpan keseluruhan data dan program computer dibutuhkan secondary-storage yang bersifat permanen dan mampu menampung banyak data. Contoh dari secondary-storage adalah harddisk, disket, dll.

Sistem operasi bertanggung-jawab atas aktivitas-aktivitas yang berkaitan dengan disk-management seperti: 
1. Manajemen ruang kosog
2. alokasi penyimpanan.
3. penjadualan disk.

### Contoh untuk melihat penggunaan penyimpanan kosong di task manager.
<p align="center"><br><br><img src="img/second2.png" height="300"></p>
<p align="center">melihat volume disk<br><br><img src="img/second4.png" height="300"></p>


<br>
<p><img src="img/16.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Sering disebut device manager. Menyediakan “device driver” yang umum sehingga operasi I/O dapat seragam (membuka, membaca, menulis, menutup). Contoh: pengguna menggunakan operasi yang sama untuk membaca berkas pada hard-disk, CD-ROM dan floppy disk.
Komponen Sistem Operasi untuk sistem I/O:

1. Buffer: menampung sementara data dari/ ke perangkat I/O.
2. Spooling: melakukan penjadualan pemakaian I/O sistem supaya lebih efisien (antrian dsb.).
3. Menyediakan driver untuk dapat melakukan operasi “rinci” untuk perangkat keras I/O tertentu.

<p align="center">contoh input memprint file pdf <br><br><img src="img/io2.png" height="300"></p>

<br>
<p><img src="img/14.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Berkas adalah kumpulan informasi yang berhubungan sesuai dengan tujuan pembuat berkas tersebut. Berkas dapat mempunyai struktur yang bersifat hirarkis (direktori, volume, dll.). Sistem operasi bertanggung-jawab:

### 1. Contoh pembuatan dan penghapusan berkas di linux.

<p align="center">
masuk kedalam terminal lalu tuliskan <b>touch nama_file.jinis_file</b> lalu enter<br><br><img src="img/1 (9).png" height="300"></p>

<p align="center">
maka file baru dengan nama yang kamu ingin buat tadi akan muncul jika ingin<br> menghapus berkas atau file silahkan tekan tombol delete paa keyboard<br><br><img src="img/1 (10).png" height="300"></p>

### 2. Contoh pembuatan dan penghapusan direktori di linux.

<p align="center">
klik tombol activities di pjok kiri atas<br><br><img src="img/1 (1).png" height="300"></p>

<p align="center">pilih menu file<br><br><img src="img/1 (2).png" height="300"></p>

<p align="center">kemudian disini saya ingin menambah direktori ke dalam folder document <br><br><img src="img/1 (3).png" height="300"></p>

<p align="center">kemudian klik kanan pada mouse atau touch pad lalu pilih new folder<br><br><img src="img/1 (4).png" height="300"></p>

<p align="center">masukkan nama direktori baru<br><br><img src="img/1 (5).png" height="300"></p>

<p align="center">maka anda telah berhasil membuat sebuah directori baru jika ingin<br> menghapusnya silahkan tekan delete pada keyboard<br><br><img src="img/1 (6).png" height="300"></p>

### 3. contoh manipulasi berkas dan direktori di linux.

<p align="center">pilih folder yang ingin di edit klik kanan pilih rename untuk mengganti<br> atau memanipulasi nama folder tersebut<br><br><img src="img/1 (6).png" height="300"></p>

<hr>
<br>
<p><img src="img/17.png" width="300"></p>

Proteksi mengacu pada mekanisme untuk mengontrol akses yang dilakukan oleh program, prosesor, atau pengguna ke sistem sumber daya. Mekanisme proteksi harus:

### 1. membedakan antara penggunaan yang sudah diberi izin dan yang belum.
<p align="center">sistem operasi akan meminta autenthication ketika ingin mengubah setting untuk unlock printer<br><br><img src="img/protek.png" height="300"></p>

<p align="center">contoh lain sistem operasi akan meminta password ketika ingin menginstall aplikasi<br><br><img src="img/protek1.png" height="300"></p>



<br>
<p><img src="img/19.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Sistem terdistribusi adalah sekumpulan prosesor yang tidak berbagi memori atau clock. Tiap prosesor mempunyai memori sendiri. Prosesor-prosesor tersebut terhubung melalui jaringan komunikasi Sistem terdistribusi menyediakan akses pengguna ke bermacam sumber-daya sistem. Akses tersebut menyebabkan:

### 1. melihat kecepatan jaringan di cmd.
<p align="center">menggunakan perintah 8.8.8.8 -t -l 1500 <br><br><img src="img/jaringan1.png" height="300"></p>

### 1. cek aplikasi dan program yang memakan banayak kuota di task manager.
<p align="center"><br><br><img src="img/jaringan2.png" height="300"></p>

<br>
<p><img src="img/20.png" width="300"></p>

<p align="justify"> &nbsp &nbsp &nbsp Sistem Operasi menunggu instruksi dari pengguna (command driven). Program yang membaca instruksi dan mengartikan control statements umumnya disebut: control-card interpreter, command-line interpreter, dan UNIX shell.
Command-Interpreter System sangat bervariasi dari satu sistem operasi ke system operasi yang lain dan disesuaikan dengan tujuan dan teknologi I/O devices yang ada. Contohnya:

### 1. Terminal Linux 
<p align="center">terminal linux<br><br><img src="img/terminal1.png" height="300"></p>

### 2.CMD Windows
<p align="center">contoh cmd windows<br><br><img src="img/terminal2.png" height="300"></p>

<hr>
<br>
<p align="center"><img src="img/21.png" width="300"></p>
 
Layanan sistem operasi dirancang untuk membuat pemrograman menjadi lebih mudah.

1. Pembuatan Program: Sistem operasi menyediakan berbagai fasilitas yang membantu programer dalam membuat program seperti editor. Walaupun bukan bagian dari sistem operasi, tapi layanan ini diakses melalui sistem operasi. 

<p align="center">
contoh pembuatan program di visual studio code</b><br><br><img src="img/membuat.png" height="300"></p>

2. Eksekusi Program: Sistem harus bisa me-load program ke memori, dan menjalankan program tersebut. Program harus bisa menghentikan pengeksekusiannya baik secara normal maupun tidak (ada error).

<p align="center">
menjalankan program tanpa eror</b> lalu enter<br><br><img src="img/jalankan.png" height="300"></p>

3. Deteksi Error. Sistem operasi harus selalu waspada terhadap kemungkinan error. Error dapat terjadi di CPU dan memori perangkat keras, Masukan/Keluaran, dan di dalam program yang dijalankan pengguna. Untuk setiap jenis error sistem operasi harus bisa mengambil langkah yang tepat untuk mempertahankan jalannya proses komputasi. Misalnya dengan menghentikan jalannya program, mencoba kembali melakukan operasi yang dijalankan, atau melaporkan kesalahan yang terjadi agar pengguna dapat mengambil langkah selanjutnya.

<p align="center">
mendeteksi eror karena salah menuliskan code program phyton</b> lalu enter<br><br><img src="img/err.png" height="300"></p>

<br>
<p><img src="img/22.png" width="550"></p>

<p><li align="justify">Alokasi Sumber Daya. Ketika beberapa pengguna menggunakan sistem atau beberapa program dijalankan secara bersamaan, sumber daya harus dialokasikan bagi masing-masing pengguna dan program tersebut. 
<p><li align="justify">Accounting. Kita menginginkan agar jumlah pengguna yang menggunakan sumber daya, dan jenis sumber daya yang digunakan selalu terjaga. Untuk itu maka diperlukan suatu perhitungan dan statistik. Perhitungan ini diperlukan bagi seseorang yang ingin merubah konfigurasi sistem untuk meningkatkan pelayanan. 
<p><li align="justify">Proteksi. Layanan proteksi memastikan bahwa segala akses ke sumber daya terkontrol. Dan tentu saja keamanan terhadap gangguan dari luar sistem tersebut. Keamanan bisa saja dilakukan dengan terlebih dahulu mengidentifikasi pengguna. Ini bisa dilakukan dengan meminta password bila ingin menggunakan sumber daya.

<br>
<p><img src="img/23.png" width="300"></p>

System program menyediakan lingkungan yang memungkinkan pengembangan program dan eksekusi berjalan dengan baik. Dapat dikategorikan:

1. Manajemen/manipulasi berkas. Membuat, menghapus, copy, rename, print, memanipulasi berkas dan direktori.
2. Informasi status. Beberapa program meminta informasi tentang tanggal, jam, jumlah memori dan disk yang tersedia, jumlah pengguna dan informasi lain yang sejenis.
3. Modifikasi berkas. Membuat berkas dan memodifikasi isi berkas yang disimpan pada disk atau tape. 
4. Pendukung bahasa pemrograman. Kadang kala kompilator, assembler, interpreter dari bahasa pemrograman diberikan kepada pengguna dengan bantuan sistem operasi. 
5. Loading dan eksekusi program. Ketika program di-assembly atau dikompilasi, program tersebut harus di-load ke dalam memori untuk dieksekusi. Untuk itu sistem harus menyediakan absolute loaders, relocatable loaders, linkage editors, dan overlay loaders. 
6. Komunikasi Menyediakan mekanisme komunikasi antara proses, pengguna, dan sistem komputer yang berbeda. Sehingga pengguna bisa mengirim pesan, browse web pages, mengirim e-mail, atau mentransfer berkas.

<p><li align="justify">Umumnya sistem operasi dilengkapi oleh system-utilities atau program aplikasi yang di dalamnya termasuk web browser, word prossesor dan format teks, sistem database, games. System program yang paling penting adalah command interpreter yang mengambil dan menerjemahkan user-specified command selanjutnya. 

<br>
<p align="center"><img src="img/24.png" width="300"></p>

<p align="center">
manajemen proses menjalankan aplikasi photoshop dengan cmd di windows<br><br><img src="img/call1.png" height="300"></p>

<p align="center"><br><br><img src="img/call2.png" height="300"></p>

<p align="center">
manajemen sistem berkas menambahkan file baru dalam directori<br><br><img src="img/1 (9).png" height="300"></p>
<p align="center"><br><br><img src="img/1 (10).png" height="300"></p>


<br>
<p><img src="img/penutup.png"></p>




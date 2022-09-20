# komponen sistem operasi

## Managemen Proses

<p align="justify">
Proses adalah keadaan ketika sebuah program sedang di eksekusi. Sebuah proses membutuhkan beberapa sumber daya untuk menyelesaikan tugasnya. sumber daya tersebut dapat berupa CPU time, memori, berkas-berkas, dan perangkat-perangkat I/O.
Sistem operasi bertanggung jawab atas aktivitas-aktivitas yang berkaitan dengan managemen proses seperti:

- Pembuatan dan penghapusan proses pengguna dan sistem proses.
- Menunda atau melanjutkan proses.
- Menyediakan mekanisme untuk proses sinkronisasi.
- Menyediakan mekanisme untuk proses komunikasi.
- Menyediakan mekanisme untuk penanganan deadlock.

<hr>
<h3> contoh: <h3>

<img src = manajemen_memori.png>

<p align = "justify">
Pada gambar diatas adalah contoh manajemen memori utama.
Gambar tersebut diambil dari TASK MANAGER, dan terlihat disitu banyak program yang sedang berproses.

membuat task/program baru :
<img src = new_task.png>
caranaya adalah dengan mengklik tulisan <u>file</u> pada pojok kanan atas

menutup/mengakhiri program :
<img src = end_task.png>
caranya dengan mengklik program mana yang ingin di tutup, dan klik <i>end task</i>

<hr>

<p align="justify"> <h2> Manajemen Memori Utama</h2>

<p align="justify">
Memori utama atau lebih dikenal sebagai memori adalah sebuah array yang besar dari word atau byte, yang ukurannya mencapai ratusan, ribuan, atau bahkan jutaan. Setiap word atau byte mempunyai alamat tersendiri. Memori Utama berfungsi sebagai tempat penyimpanan yang akses datanya digunakan oleh CPU atau perangkat I/O. Memori utama termasuk tempat penyimpanan data yang sementara (volatile), artinya data dapat hilang begitu sistem dimatikan.
Sistem operasi bertanggung jawab atas aktivitas-aktivitas yang berkaitan dengan managemen memori seperti:

- Menjaga track dari memori yang sedang digunakan dan siapa yang
menggunakannya.
- Memilih program yang akan di-load ke memori.
- Mengalokasikan dan meng-dealokasikan ruang memori sesuai kebutuhan.

<hr>
<h3>Contoh manajemen memori utama</h3>

<p align = "justify"> 

Memilih file apa yang akan di load di memori :
<img src = customize.png><br>

1. Buka memori yang ingin di kelola.
2. klik kanan dan pilih properties.
3. pilih customize pada bagian atas.
4. pilih berkas yang ingin diload

<br>
Mengalokasikan ruang pada memori :
<img src = alokasi.png>

1. buka disk management dengan cara klik kanan pada logo windows.
2. klik memori mana yang akan di alokasikan ruang nya.
3. tentukan jumlah memori yang akan di bagi

<br>
<hr>

<p align = "justify"> <h2>Managemen Sistem I/O</h2>
Sering disebut device manager. Menyediakan “device driver” yang umum sehingga operasi I/O dapat seragam (membuka, membaca, menulis, menutup). Contoh: pengguna menggunakan operasi yang sama untuk membaca berkas pada hard-disk, CD-ROM dan floppy disk.

Komponen Sistem Operasi untuk sistem I/O:

- Buffer: menampung sementara data dari/ ke perangkat I/O.
- pooling: melakukan penjadualan pemakaian I/O sistem supaya lebih efisien (antrian dsb.).
- Menyediakan driver untuk dapat melakukan operasi “rinci” untuk perangkat keras I/O tertentu.

<br>

<p align = "justify"> <h3> Contoh anagemen Sistem I/O </h3>
<img src = io.png>
Buka DISK MANAGER dengan cara :

1. klik pada bagian <i>Type here to search</i>
2. ketik <i>disk manager</i>
3. klik tulisan <i> disk manager</i>

ketika tampilan sudah sama dengan gambar diatas berarti anda sudah masuk ke disk manager, anda dapat melakukan update,disable dan uninstall pada device yang anda pilih dengan melakukan klik kanan pada device yang ingin anda pilih.
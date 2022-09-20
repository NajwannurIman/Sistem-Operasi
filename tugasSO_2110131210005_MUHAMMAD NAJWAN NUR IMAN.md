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
<img src = customize.PNG><br>

1. Buka memori yang ingin di kelola.
2. klik kanan dan pilih properties.
3. pilih customize pada bagian atas.
4. pilih berkas yang ingin diload

<br>
Mengalokasikan ruang pada memori :
<img src = alokasi.PNG >

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
<hr>

<p align="justify"> <h1> Layanan Sistem Operasi </h1>

Sebuah sistem operasi yang baik menurut Tanenbaum harus memiliki layanan sebagai berikut:

1. <b>Pembuatan program</b>, yaitu sistem operasi menyediakan fasilitas dan layanan untuk membantu para pemrogram untuk menulis program
2. <b>Eksekusi program</b> adalah kemampuan sistem untuk "load" program ke memori dan menjalankan program yang dikehendaki user maupun sistem.
3. <b>Operasi I/O</b> merupakan kegiatan dimana pengguna tidak dapat secara langsung mengakses sumber daya perangkat keras, sehingga sistem operasi harus menyediakan mekanisme untuk melakukan operasi I/O atas nama pengguna.
4. <b> Sistem manipulasi berkas</b> adalah kemampuan program untuk operasi pada berkas (membaca, menulis, membuat, dan menghapus berkas yang berupa file atau direktori).
5. <b>Komunikasi</b> adalah pertukaran data/ informasi antar dua atau lebih proses yang berada pada satu komputer (atau lebih).
6. <b>Deteksi error</b> adalah kegiatan untuk menjaga kestabilan sistem dengan mendeteksi "error", perangkat keras maupun operasi yang dilakukan.
7. <b>Deteksi dan Pemberian tanggapan pada kesalahan</b>, jika muncul permasalahan pada sistem komputer maka sistem operasi harus memberikan tanggapan yang menjelaskan kesalahan yang terjadi serta dampaknya terhadap aplikasi yang sedang berjalan.
8. <b>Efesisensi penggunaan sistem</b>, diantaranya:

- Resource allocator, yakni: mengalokasikan sumber-daya hardware maupun software ke beberapa pengguna atau mengalokasikan job yang jalan pada saat yang bersamaan ke beberapa komputer dalam jaringan.
- Proteksi sistem untuk menjamin akses ke sistem sumber daya yang aman, dikendalikan oleh sistem sehingga pengguna dikontrol aksesnya ke sistem).

9. <b>Accounting</b> adalah kegiatan merekam aktifitas pengguna, report pemakaian sumber daya. Sistem Operasi yang bagus harus mampu mengumpulkan data statistik penggunaan beragam sumber-daya dan memonitor parameter kinerja.

<hr>
<p align = "justify"> <h3> Contoh Layanan Sistem Operasi</h3>

Contoh Pembuatan Program, bisa menggunakan vscode atau default dari pc/laptop menggunakan notepad/notepad++

<img src = notepad.PNG>
<br>
gambar di atas merupakan pembuatan program menggunakan notepad++

<hr>
<p align = "justify">

<h3>contoh eksekukusi program </h3>
<img src = eksekusi.PNG>
<br>
caranya adalah dengan klik 2 kali atau klik kanan program mana yang ingin di jalankan (jika menggunakan klik kanan pilih <i>open</i>)

<hr>
<p align = "justify">

<h3>Sistem Manipulasi Berkas</h3>
<h3>Folder</h3>

1. Membuat Folder baru 
<img src = new_folder.PNG> 
klik new folder pada bagian atas

2. rename folder 
<img src = rename.PNG>
bisa melalui klik kanan lalu pilih rename atau tekan f2 atau klik rename pada logo diatas

4. menghapus folder 
<img src = delete.PNG>
bisa belalui klik kanan lalu pilih delete atau klik ikon delete di atas
<BR>
<br>
<h3> Berkas</h3>

1. Membuat Berkas
<img src = masuk.PNG>
masuk ke folder yang akan di pakai
<br>

2. <img src = buat_berkas.PNG>
klik ikon new item pada bagian atas lalu pilih berkas apa yang ingin di buat
<br>
<br>
<hr>

<h1>System  Call </h1>
<p align="justify">System call adalah kejadian dimana kode program aplikasi memanggil kode program kernel sistem operasi. Salah satu mekanisme yang umum dipakai untuk system call adalah dengan menggunakan software interrupt.

<h3>Contoh system call pada windows</h3>
<br>
<h3> cara membuka CLI/CMD pada windows</h3>
1. buka CLI/CMD windows dengan cara <i>windows + R</i>
2. lalu ketikan <i>cmd</i>
<img src = winR.PNG>

3. lalu tekan <i>OK</i>
4. maka tampilan akan muncul seperti ini.
<img src = cmd.PNG>

<H3>Beberapa Command - Command pada CMD </h3>

1. Systeminfo
Merupakan Perintah CMD yang memilika fungsi untuk menampilkan informasi komputer yang kamu gunakan,
cara menggunakannya ketik <i>systeminfo</i>pada cmd lalu <b>enter</b>
<img src = systeminfo.PNG>
<br>

2. Tree 
Untuk Menampilkan struktur dalam suatu folder
cara menggunakannya ketik <i>tree</i>pada cmd lalu <b>enter</b>
<img src = tree.PNG>
<br>

3. Tasklist 
untuk menampilkam informasi aplikasi yang sedang berjalan pada komputer 
cara menggunakannya ketik <i>tasklist</i>pada cmd lalu 
<img src = tasklist.PNG>
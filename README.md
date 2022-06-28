## Nama: NAhrul Wijaya
## Nim: 312010415
## Kelas: TI.20.A1

### Langkah langkah praktikum 11

1. Buat file baru dengan nama header.php

## Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual

• Unduh Codeigniter dari website https://codeigniter.com/download

• Extrak file zip Codeigniter ke direktori htdocs/lab11_ci.

• Ubah nama direktory framework-4.x.xx menjadi ci4.

• Buka browser dengan alamat http://localhost/lab11_ci/ci4/public/
![p](gambar/1.PNG)

2. Membuat Route Baru.
Tambahkan kode berikut di dalam Routes.php
![p](gambar/4.PNG)

Selanjutnya coba akses route yang telah dibuat dengan mengakses alamat url http://localhost:8080/about
![p](gambar/8.PNG)
Ketika diakses akan mucul tampilan error 404 file not found, itu artinya file/page tersebut tidak ada. Untuk dapat mengakses halaman tersebut, harus dibuat terlebih dahulu Contoller yang sesuai dengan routing yang dibuat yaitu Contoller Page.

![p](gambar/6.PNG)
Selanjutnya refresh Kembali browser, maka akan ditampilkan hasilnya yaitu halaman sudah dapat diakses.
![p](gambar/9.PNG)

3. Auto Routing

Secara default fitur autoroute pada Codeiginiter sudah aktif. Untuk mengubah status autoroute dapat mengubah nilai variabelnya. Untuk menonaktifkan ubah nilai true menjadi false.
![p](gambar/10.PNG)
Tambahkan method baru pada Controller Page seperti berikut.
![p](gambar/11.PNG)

Method ini belum ada pada routing, sehingga cara mengaksesnya dengan menggunakan alamat: http://localhost:8080/page/tos

![p](gambar/12.PNG)

4. Membuat View

Selanjutnya adalam membuat view untuk tampilan web agar lebih menarik. Buat file baru dengan nama about.php pada direktori view (app/view/about.php) kemudian isi kodenya seperti berikut.

![p](gambar/13.PNG)

Ubah method about pada class Controller Page menjadi seperti berikut:

![p](gambar/14.PNG.PNG.PNG)

Kemudian lakukan refresh pada halaman tersebut.

![p](gambar/15.PNG)

5. Membuat Layout Web dengan CSS
Buat file css pada direktori public dengan nama style.css (copy file dari praktikum lab4_layout. Kita akan gunakan layout yang pernah dibuat pada praktikum 4.

![p](gambar/16.PNG)

Kemudian buat folder template pada direktori view kemudian buat file header.php dan footer.php

![p](gambar/17.PNG)

File app/view/template/footer.php

![p](gambar/18.PNG)

Selanjutnya refresh tampilan pada alamat http://localhost:8080/about

![p](gambar/19.PNG)

## Lab 11 (Lanjutan)



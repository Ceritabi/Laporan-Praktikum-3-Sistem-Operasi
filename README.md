📌Laporan Praktikum 3 Sistem Operasi

Nama : M. Rizky Taufik Nur Hidayat

NIM  : 09030582327076

Kelas: TK4B
<hr>

<h1>Sistem File</h1>

<ol>
<li>Perintah ls -l /dev | grep ^c akan menampilkan daftar character device di direktori /dev.</li>
<img  src="1.png" alt=""  width="300px">

<li>mkdir -p digunakan agar direktori dibuat secara rekursif jika latihan5 belum ada. <br>
{januari,februari,maret} digunakan untuk membuat tiga direktori sekaligus.</li>
<img  src="2.png" alt=""  width="300px">

<li>Membuat File dataku di Januari dan Menyalinnya ke Februari dan Maret <br>
  echo -e digunakan untuk membuat file dataku dengan isi yang diinginkan.<br>
cp digunakan untuk menyalin file ke subdirektori Februari dan Maret.</li>
<img  src="3.png" alt=""  width="300px">

<li>Mengubah Izin Akses File dataku di Januari agar Group dan Others Bisa Write dengan code 666</li>
<img  src="4.png" alt=""  width="300px">

<li>Mengubah Izin Akses File dataku di Februari (User: rwx, Group & Others: rx) dengan code 755</li>
<img  src="5.png" alt=""  width="300px">

<li>Mengubah Izin Akses File dataku di Maret agar Semua Bisa Read, Write, Execute dengan code 777</li>
<img  src="6.png" alt=""  width="300px">

<li>Menghapus Direktori Maret dengan komen rm -r</li>
<img  src="7.png" alt=""  width="300px">

<li>Mengubah Kepemilikan Subdirektori Februari agar User & Group Hanya Bisa Read<br>
chmod 444 membuat subdirektori hanya bisa dibaca oleh user dan group (r--r--r--).<br>
Setelah itu, coba buat direktori haha dalam februari, yang seharusnya gagal karena tidak ada izin menulis.</li>
<img  src="8.png" alt=""  width="300px">

<li>Mengubah umask untuk File dataku di Januari ke 027 dan Melihat Nilai Default-nya</li>
<img  src="9.png" alt=""  width="300px">

<li>Membuat Link ke dataku dengan Nama dataku.ini dan dataku.juga <br>
ln membuat hard link ke file dataku.<br>
ls -l akan menampilkan jumlah link yang ada pada file (dataku seharusnya memiliki 3 link).</li>
<img  src="10.png" alt=""  width="300px">

</ol>

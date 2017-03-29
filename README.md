# Komdat-13
Repository untuk tugas Komdat dari kelompok 13

<p style="font-size:20px"><b>Aplikasi Human Resource Management "Admidio"</b></p>

<p style="font-size:14px">Sekilas Tentang Admidio</p>
<p>Admidio adalah manajemen keanggotaan online gratis, yang dioptimalkan untuk klub, kelompok dan organisasi. Ini terdiri selain anggota manajemen klasik dari berbagai modul yang dapat diinstal dan disesuaikan ke rumah baru atau yang sudah ada.</p>

<p>Anda dapat membuat profil individu untuk anggota Anda dengan menambahkan atau menghapus bidang. Tambahan untuk fungsi-fungsi ini yaitu sistem memiliki beberapa modul seperti daftar anggota, manajer acara, buku tamu, album foto atau download area.</p>

<p style="font-size:20px"><b>Instalasi</b></p>
<p style="font-size:14px"><b>Prasyarat Sebelum instalasi</b></p>
<ol>
<li>Masuk ke VPS dengan alamat IP adam@172.18.88.83</li>
<li>Login dengan username : adam  dan password : first</li>

<b>Langkah instalasi dalam CLI</b>
<ol>
<li>sudo apt install apache2</li>
<li>sudo apt install mysql-server</li>
<li>sudo apt install php</li>
<li>sudo apt install libapache2-mod-php</li>
<li>sudo apt install php-mysql</li>
<li>sudo apt install php-gd php-mcrypt php-mbstring php-xml php-ssh2</li>
<li>sudo service apache2 restart</li>
<li>sudo install phpmyadmin</li>
<li>sudo wget http://sourceforge.net/projects/admidio/files/Admidio/3.2.x/admidio-3.2.6.zip/download</li>
<li>sudo apt install unzip</li>
<li>cd /var/www</li>
<li>unzip download</li>
<li>mv admidio-3.2.6 html/admidio</li>
<li>sudo chmod -R 777 adm_my_files</li>


<b>Cara Pemakaian</b>
Tampilan aplikasi web


Fungsi-fungsi utama





<b>Pembahasan</b>
<p>Aplikasi ini memudahkan user dalam mengelola data dalam sebuah kelompok atau organisasi yang 
telah dijaring oleh user terlebih dahulu, dimana dapat mengirimkan email, foto, pengumuman dan lainnya.<p>

Kelebihan Admidio :
<ul>
<li>Dapat mengelola sistem dalam jaringan kelompok yang ada pada admidio</li>
<li>Dapat menambahkan roles akun dengan authorization yang dapat dilakukan sesuai dengan kebutuhan perusahaan/kelompok.</li>
<li>Dapat melakukan backup database dengan 1 klik.</li>
</ul>

Kekurangan Admidio :
<ul>
<li>Kurang dikenal oleh khalayak ramai</li>
<li>Interface sedikit membingungkan</li>
<li>Tidak bisa memberikan info selain penggunanya walaupun email yang dimasukkan ada.</li>
</ul>

<b>Referensi</b>
https://play.google.com/store/apps/details?id=de.zettem.Appmidio&hl=in
https://www.admidio.org/dokuwiki/doku.php?id=en:2.0:index




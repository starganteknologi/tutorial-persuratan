

# Setting Development Environment

# Development Server

Sebelum kita membuat sebuah aplikasi web dapat diakses oleh publik, kita perlu memastikan bahwa aplikasi kita terbebas dari error, dan berfungsi seperti yang direncanakan.

Untuk itu itu diperlukan sebuah server yang kita gunakan untuk membuat aplikasi kita.

kita dapat membuat sebuah server lokal kita dengan menginstalasi aplikasi-aplikasi yang diperlukan untuk menjalankan sebuah aplikasi web

# Cara menginstall PHP, Web Server dan Database

kita dapat menginstall masing-masing program tersebut

untuk PHP jika anda menggunakan windows dapat menuju download page nya <https://windows.php.net/download#php-8.1>

versi terbaru stabil adalah versi 8.1

untuk web server anda dapat menggunakan apache <https://httpd.apache.org/>

untuk database anda dapat menggunakan mariadb community edition sebagai alternative mysql di <https://mariadb.com/downloads/community/>

alternative database lainnya adalah postgresql <https://www.postgresql.org/download/>

## apakah ada cara yang lebih mudah untuk menginstall PHP, apache, mysql ?

### ampps

### XAMPP

untuk menginstall semua yang kita butuhkan untuk mengembangkan Aplikasi Web berbasis PHP, kita dapat menggunakan XAMPP, anda dapat mendownloadnya dari https://www.apachefriends.org/index.html

> XAMPP is the most popular PHP development environment
>>XAMPP is a completely free, easy to install Apache distribution containing MariaDB, PHP, and Perl. The XAMPP open source package has been set up to be incredibly easy to install and to use.
 https://www.apachefriends.org/index.html

## review PHP development environment
- melihat configurari apache dari xamp control panel
- mengetahui lokasi configurasi apache
      C:\xampp\apache\conf
  dari file ini kita dapat banyak konfigurasi termasuk salah satunya yang perlu kita ketahui yaitu lokasi dimana file - file php kita disimpan

- melihat configurasi mysql
      C:\xampp\mysql\bin
- melihat logs apache
      C:\xampp\apache\logs
- melihat logs PHP
      c:\xampp\php\logs
- melihat logs mysql
      C:\xampp\mysql\data\mysql_error.log

## hello word php
1. buat folder proyek baru di ```C:\xampp\htdocs\stargan ```

  nama bisa kita ganti sesuai keinginan anda

1. buka editor (notepad, notepad++, vscode)
2. buat file index.php

  ``` php
  <?php
  // \stargan\index.php
  print("belajar PHP")
  ?>
  ```
3.simpan di lokasi folder yang sudah kita buat ```C:\xampp\htdocs\stargan\index.php ```
4. buka browser anda dan ketikkan alamat ```http://localhost/stargan/```
5. voila program pertama menggunakan PHP

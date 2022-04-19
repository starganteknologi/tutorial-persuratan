# Bab 1 : Pengenalan PHP

## Apa itu php

> PHP is a popular general-purpose scripting language that is especially suited to web
development. Fast, flexible, and pragmatic, PHP powers everything from your blog to the
most popular web sites in the world.” —www.php.net

## mengapa belajar PHP

### market share

menurut survey, market share PHP masih yang terbesar

- survey w3techs.com
  ![w3techs](/images/w3tehch-com-php-market-share.png)
  sumber <https://w3techs.com/technologies/details/pl-php>

- survey statista.com

  ![survey](/images/statista-com-php-market-share.png)
  sumber: statista.com

### dokumentasi

- dokumentasi PHP cukup lengkap dapat dilihat di <https://www.php.net/docs.php>

  bisa dilihat secara online dan juga bisa di download

- sumber-sumber belajar PHP melimpah

## Bagaimana sebuah aplikasi web bekerja

ketika seseorang mengetikkan sebuah alamat website pada browser, browser akan menghubungi sebuah web server

web server tersebut kemudian akan merespon permintaan dari client

untuk sebuah web server yang menggunakan PHP, web server akan menghubungi PHP processor yang terdapat pada server tersebut,

jika halaman yang diminta oleh client memerlukan sebuah data, PHP processor dapat menghubungi sebuah Database Server dan meminta data menggunakan sebuah bahasa SQL

Database Server akan memberikan data kepada PHP processor untuk dapat diolah oleh PHP.

setelah data diolah, PHP akan membuat response(dapat berupa html text atau file) yang diminta oleh client yang akan dikembalikan ke client melalui web server

browser kemudian menginterpretasi response yang diterima dari web server untuk dapat ditampilkan

![bagaimana-aplikasi-web-bekerja](/images/bagaimana-aplikasi-web-bekerja.svg)

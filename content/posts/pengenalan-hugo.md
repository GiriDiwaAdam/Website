---
author: "Giri Diwa Adam"
title: "Pengenalan Hugo"
date: 2022-07-15T21:20:58+07:00
draft: false
featured_image: "hugo.png"

tags:
- Hugo
---
## Pengertian Hugo ?? ##

<b>Hugo</b> Adalah sebuah framework Static Site Generator yang di buat untuk para programmer yang
ingin membuat sebuah web dengan cepat.hugo sendiri pada dasarnya menggunakan bahasa GO sebagai bahasa
utama.

Hugo juga merupakan framework yang belakangan ini terkenal di kalangan programmer di banding SSG 
Sejenis seperti Octopress dan Jekyll hingga middleman

## Sejarah Hugo ##

Hugo pertama kali dibuat oleh Steve Francia di tahun 2013, yang kemudian mendapat peningkatan besar pada fitur dan performa setelah dikembangkan oleh developer yang dipimpin oleh Bjørn Erik Pedersen sejak tahun 2015. (Source : Appekey.id)

Saat ini hugo telah dilisensi di bawah Apache License 2.0 framework ini sendiri memiliki keunggulan
diantaranya (Mudah,cepat, dan dapat di konfigurasi). Hugo sendiri mengambil direktori dengan konten
dan template dan membuatnya menjadi situs web HTML lengkap

Hugo sendiri mengambil markdown sebagai metadata anda sendiri bisa menjalakan hugo di manapun anda berada. Hal ini membuat hugo SSG dapat berfungsi dengan baik untuk host bersama dengan sistem lain.

## Cara penginstalan Hugo ##

Berikut ini cara menginstall hugo jika anda menggunakan windows silahkan ikuti tata cara penginstallan hugo di bawah ini :

Apa saja yang di perlukan :
- Terminal 
- Installer Hugo

Pertama silahkan kalian kunjungi website ini(https://github.com/gohugoio/hugo/releases) lalu kalian pilih installer sesuai dengan sistem operasi kalian Jika <b> 64bit</b> gunakan yang 64 bit jika <b> 32bit </b> Gunakan yang 32 bit, namun karena sistem operasi saya yang 64bit maka saya gunakan 64bit.

Setelah selesai di download silahkan extrak terlebih dahulu file nya dan letakkan di data <code> C:/namafolder/Site</code> dan jangan lupa edit enviroment di windows dan arahkan ke tempat kalian install hugo tadi.

Dan step terakhir buka terminal CMD dan ketikkan <code>C:\namafolder </code> kemudian Enter dan jalankan perintah berikut <code> hugo version </code>

Jika muncul seperti ini <code> hugo v0.101.0-466fa43c16709b4483689930a4f9ac8add5c9f66+extended windows/amd64 BuildDate=2022-06-16T07:09:16Z VendorInfo=gohugoio </code>, maka tandanya installasi hugo kalian berhasil dan kini kalian bisa ber experiment dengan hugo.

<b> Note : Jika masih belum berhasil silahkan check di bagian Path apakah sudah benar apa belum jika di rasa sudah benar silahkan jalankan kembali perintah <code> hugo version </code>.


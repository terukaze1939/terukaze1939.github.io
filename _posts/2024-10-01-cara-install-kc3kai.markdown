---
layout: post
title: "Cara Install dan Menggunakan KC3Kai (DESKTOP, CHROME)"
date: 2024-10-01 12:26:07 +0700
categories: tutorial
thumbnail: assets/imgs/cara_install_kc3kai/thumbnail.jpg
---

KC3Kai di Chrome Web Store kini telah `tidak didukung` lagi, yang dimana ekstensi KC3Kai tidak bisa memperbarui versi otomatis jika diinstall dari Chrome Web Store, oleh karena itu KC3Kai bisa diinstall manual lewat file dari githubnya.

<center>
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img1.png'}}">
</center>
<br>

![](/{{ 'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img2.png' }})
<br>

Pertama download file KC3Kainya [Di sini](https://github.com/KC3Kai/KC3Kai/releases), lalu pilih versi terbaru atau paling atas. Setelah didownload buka file manager atau explorer dan ekstrak filenya. Setelah diekstrak buka kembali Chromenya dan buka ke `Manage extension` atau `Kelola ekstensi`, bisa juga dengan memasukan pada bar URL dengan `chrome://extensions`. Jika sudah membuka kelola ekstensi nyalakan `Mode pengembang` atau `Developer mode`.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img3.png'}}">
</p>

Setelah `Developer mode` dinyalakan maka akan muncul opsi untuk memilih folder ekstensi yang tadi telah diekstrak, yaitu `Load unpacked`.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img4.png'}}">
</p>


Klik lalu pilih folder KC3Kai yang tadi telah diekstrak

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img5.png'}}">
</p>

Maka nanti otomatis akan pergi ke halamanan ekstensinya bahwa berhasil diinstall seperti di bawah ini.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img6.png'}}">
</p>

## Cara menggunakan KC3Kai untuk bermain game KanColle

> Perlu diingat, sebelum memainkan KanColle dari KC3Kai pastikan matikan Ad-Blocks untuk situs DMM, atau matikan saja Ad-Blockernya jika ingin bermain game KanColle. Karena kemungkinan besar file yang penting digunakan oleh situs website DMM diblokir dan tidak dapat dimuat dengan benar dan dapat menyebabkan game `Blank warna putih` atau `Stuck`.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img7.jpg'}}">
</p>

Pada gambar di atas, jika kalian menyalakan AD-Blocker maka akan muncul pesan dengan nama `net::ERR_BLOCKED_BY_CLIENT` yang dimana itu muncul karena AD-Blocker memblokir file yang diperlukan oleh DMM, berhubungan pada gambar di atas tidak ada pesan error berarti itu sudah mematikan AD-Blockernya. Oleh karena itu matikan AD-Blockernya.

Selanjutnya buka ekstensi KC3Kai dengan cara mengklik icon KC3Kainya yang berwarna kuning, lalu pergi ke pengaturan `KC3Kai Settings`.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img8.jpg'}}">
</p>

Setelah membuka ke pengaturan, pergi ke `DMM Regional Block`.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img9.jpg'}}">
</p>

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img10.jpg'}}">
</p>

Pastikan bagian di bawah ini dicentang

- `Force Cookie Hack`
- `Gadget Block Bypass`

Jika sudah, silahkan tutup Tabnya dan buka kembali ekstensi KC3Kainya. Kemudian klik bagian `Play Kantai Collection` maka nanti akan membuka Tab baru.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img11.jpg'}}">
</p>

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img12.jpg'}}">
</p>

Setelah membuka Tab barunya, `klik kanan mouse` kalian lalu pilih `Inspect` atau `Inspect element` tab sekarang. Nanti akan membuka `Web inspector` sepert di bawah ini.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img13.jpg'}}">
</p>

Kemudian cari bagian `2 tanda panah ke kanan` seperti yang saya tandai dengan warna merah, lalu pilih bagian `KanColle`, tunggu sampai game memuat.

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img14.jpg'}}">
</p>

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img15.jpg'}}">
</p>

<p align="center">
    <img src="/{{'assets/imgs/cara_install_kc3kai/cara_install_kc3kai_tutor_img16.jpg'}}">
</p>

## Dengan begini, cara install KC3Kai dan menggunakannya telah berhasil.
Bisa dilihat bahasa game yang digunakan masih default Bahasa jepang, bisa kamu gunakan `Patch Bahasa Indonesia` atau `Patch Bahasa Inggris`. Jika kamu ingin menggunakan `Patch Indonesia` atau `Patch Inggris` dan menggunakan `KCCacheProxy` pastikan opsi `Force Cookie Hack` dan `Gadget Block Bypass` di `KC3Kai Settings` dimatikan. Karena KCCacheProxy sudah bawaanya menggunakan `Gadget Block Bypass`. Jadi tidak perlu 2 kali menggunakan `Bypass`.


Jika ingin menggunakan Bahasa Indonesia silahkan kunjungi link di bawah ini.

- [Patch Bahasa Indonesia (WINDOWS)](https://terukaze1939.github.io/tutorial/2024/07/04/cara-install-kancolle-indonesia-patch-kccp-windows.html)
- [Patch Bahasa Indonesia (LINUX)](https://terukaze1939.github.io/tutorial/2024/07/04/cara-install-kancolle-indonesia-patch-kccp-linux.html)


## Jika muncul kendala
Silahkan bergabung dengan grup whatsapp BCR KanColle Community atau DM ke facebook saya.

<span class="bi bi-facebook"><a href="https://facebook.com/terukaze1939" style="text-decoration:none" target="_blank"> Teru </a></span>
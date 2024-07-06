---
layout: post
title: "Cara Install KanColle Indonesia Patch ( KCCacheProxy ) LINUX"
date: 2024-07-04 12:29:07 +0700
categories: tutorial
---


Di sini saya akan memberikan tutorial `Menginstall Patch Bahasa Indonesia ke dalam Game KanColle` menggunakan `KCCacheProxy` pada `linux`.

Jika kalian belum menginstall `KCCacheProxy`nya bisa ikuti tutorial [CARA MENGINSTALL KCACHEPROXY DI LINUX](https://terukaze1939.github.io/tutorial/2024-07-04-cara-menginstall-kcacheproxy-di-linux). Selanjutnya, download terlebih dahulu file zip [KanColle-Indonesia-Patch-KCCP.zip](https://github.com/SLAVUSworks/KanColle-Indonesia-Patch-KCCP/archive/refs/heads/master.zip), lalu ekstrak filenya setelah didownload.

Lalu buka aplikasi text editor `nano` atau `Visual Studio Code` dan buka file `config.json` di dalam folder `KCCacheProxy-linux` kalian.

> Jika file `config.json` tidak ada.

> Buka game KanCollenya menggunakan KCCacheProxy saja dengan eksekusi file `proxy-linux`  sampai kalian ditampilkan halaman awal game atau `GAME START`.

> Nanti file `config.json` otomatis akan ada.

> Pastikan file `proxy-linux` sudah menggunakan perintah `chmod +x proxy-linux`.


`config.json`

{% highlight json %}

{
    "port": 8081,
    "hostname": "127.0.0.1",
    "cacheLocation": "default",
    "checkForUpdates": true,
    "startHidden": false,
    "disableBrowserCache": false,
    "verifyCache": true,
    "serverIP": "125.6.189.135",
    "bypassGadgetUpdateCheck": true,
    "gameVersionOverwrite": "false",
    "preloadOnStart": false,
    "showExtraButtons": false,
    "enableModder": true,
    "mods": [
        {
            "path": "/home/<user>/Downloads/KanColle-Indonesia-Patch-KCCP/ID-patch.mod.json",
            "allowScripts": true
        }
	],
    "preload": {...}

}

{% endhighlight %}

Pastikan pada file `config.json` kalian, bagian 
- `verifyCache` = `true`
- `enableModder` = `true`

Setelah mengatur bagian atas, tinggal tambahkan sebuah objek JSON ke dalam array `mods` 

{% highlight json %}

    {
        "path": "/home/<user>/Downloads/KanColle-Indonesia-Patch-KCCP/ID-patch.mod.json",
        "allowScripts": true
    }

{% endhighlight %}

Untuk `path`nya bisa kalian masukan lokasi file `ID-patch.mod.json`, seperti punya saya yang lokasinya `/home/<user>/Downloads/KanColle-Indonesia-Patch-KCCP/ID-patch.mod.json`, dan ubah bagian `<user>`nya dengan username linux kalian.


Full isi file `config.json` saya:

{% highlight json %}

{
    "port": 8081,
    "hostname": "127.0.0.1",
    "cacheLocation": "default",
    "checkForUpdates": true,
    "startHidden": false,
    "disableBrowserCache": false,
    "verifyCache": true,
    "serverIP": "125.6.189.135",
    "bypassGadgetUpdateCheck": true,
    "gameVersionOverwrite": "false",
    "preloadOnStart": false,
    "showExtraButtons": false,
    "enableModder": true,
    "mods": [
        {
            "path": "/home/<user>/Downloads/KanColle-Indonesia-Patch-KCCP/ID-patch.mod.json",
            "allowScripts": true
        }
	],
    "preloader": {
        "maxSimulPreload": 4,
        "recommended": {
            "static": true,
            "assets": true,
            "servername": true,
            "maps": true,
            "useitem": true,
            "gadget": false
        },
        "sounds": {
            "titlecalls": false,
            "se": false,
            "bgm": false,
            "npcvoices": false,
            "voices": false
        },
        "extra": {
            "equips": false,
            "furniture": false,
            "ships": false
        },
        "cleanup": true
    },
    "configVersion": 3
}


{% endhighlight %}

Setelah mengatur konfigurasi file `config.json`, hapus `Cache Gambar` pada browser kalian secara manual, lalu jalankan file `proxy-linux` dan buka gamenya bisa menggunakan `KC3 KanColle Command Center` beserta konfigurasi proxynya.


## GAMEPLAY
![](/{{ 'assets/imgs/main.png' }})
<br>
![](/{{ 'assets/imgs/homeport.png' }})
<br>

## Muncul Masalah ? 
Jika ada masalah silahkan masuk ke grup Whatsapp [BCR Salty KC und Random FORUM/Group Kancolle](https://chat.whatsapp.com/BEQXUFek52T5IweZIUmYBJ){:target="_blank"}

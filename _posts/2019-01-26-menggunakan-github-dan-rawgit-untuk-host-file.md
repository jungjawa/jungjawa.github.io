---
layout: post
title:  "Menggunakan GitHub dan RawGit untuk Host File"
subtitle: "Kalo bisa pake GitHub, ya sekalian saja"
date:   2018-01-26 10:45:13 -0300
permalink: menggunakan-gitHub-dan-rawgit-untuk-host-file
comments: true
---

Kelemahan utama ketika saya melakukan _developing_ _theme_ menggunakan blogspot adalah ketiadaan _space_ untuk membuat repositori file yang akan digunakan. Jalan pintasnya adalah saya membeli sebuah _hosting_ dan dapat dengan mudah menyimpan file-file CSS dan Javascript di sana.  
  
Tapi, itu bukan solusi. Akan menjadi masalah ketika _hosting_ tersebut tidak bisa diakses.  
  
Solusinya, saya menggunakan **GitHub**. GitHub sendiri adalah sebuah website yang memberikan pelayanan untuk menyimpan repo secara gratis. Ya walaupun GitHub seharusnya berfungsi sebagai jejaring sosial, saya masih menggunakannya sebagai repositori pribadi.  
  
Dari GitHub, kita sudah bisa meletakkan _file_. Nggak perlu upload, cukup _copy_ _paste_ saja. Kemudian di GitHub. Kita bisa membuat repositori tersendiri.  
  
Jadi biar nggak _semrawut_, tiap _project_ yang berbeda diusahakan untuk memiliki repositori tersendiri. Nah, dari _file_ _host_ yang ada, itu kita gunakan sebagai _external_ _script_.  
  
Kalo pake blogspot, kendala utama adalah tidak adanya _hosting_. Jadi untuk mengakalinya, GitHub bisa jadi solusi.  
  
Tapi tidak bisa langsung begitu saja. Alamat url dari file yang kita simpan di GitHub tidak bisa langsung digunakan. Tentu, _template_ blogspot kita akan gagal nantinya.  
  
Kita perlu menggunakan **RawGit**.  

> RawGit serves raw files directly from GitHub with proper Content-Type headers.

Di RawGit, _paste_ _url_ _file_ repo yang ada di GitHub, kemudian ambil url produksi, bukan development. Nah, url ini bisa langsung kita pakai di blogspot.
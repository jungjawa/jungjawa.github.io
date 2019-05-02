---
layout: post
title:  "Membuat Blog dengan Jekyll"
subtitle: "Sebuah rasa ingin tau dan coba-coba"
date:   2019-05-03 23:45:13 -0300
permalink: mencoba-membuat-situs-web-dengan-jekyll
---

Akhirnya saya berkesempatan mencoba menggunakan Jekyll juga. Setelah sekian lama.

Pertama kali mencoba menggunakan [Jekyll](https://jekyllrb.com) untuk [dev.jungjawa.com](https://dev.jungjawa.com). Sebelumnya, subdomain blog ini menggunakan blogspot sebagai host utama.

Oh iya, bagi yang belum tau banyak. Jekyll adalah sebuah framework yang biasa digunakan untuk web static atau blog. Alternatif lain selain Jekyll seperti [Hugo](https://gohugo.io) atau Gatsby. Ya, yang saya tau baru itu saja sih.

Ya, kita tahu sih, untuk membuat blog atau website perlu domain dan hosting file. Nah, untuk hosting file, Jekyll bisa digunakan di [GitHub Pages](https://pages.github.com/). Free.

## Beberapa hal yang saya rasakan setelah menggunakan Jekyll untuk pertama kalinya:
### 1. Desain
Menurut saya, ini part yang paling krusial karena di sini bisa bebas melakukan kustomisasi. Ya, sama saja dengan PHP di Wordpress ataupun XML di blogspot. Namun, untuk blogspot saya sering merasa kesulitan karena dokumentasi dari Google masih sulit untuk dipahami.

Kalau bisa dibilang, tampilan Medium.com bisa kita kustomisasi dan dibuat semirip mungkin menggunakan Jekyll.

### 2. Publishing
Jekyll memiliki perbedaan yang sangat signifikan jika dibandingkan dengan CMS blogging seperti Blogspot maupun Wordpress. Jika menggunakan Blogspot maupun WP, kita menggunakan UI Admin/Dashboard untuk menulis artikel, di Jekyll kita diharuskan membuat file.

Yup, _literally a file_.

Saya belum eksplor apakah ada plugin atau method untuk membuat dashboard untuk membuat artikel post di Jekyll. Sejauh ini, saya menggunakan text editor. Jadi, bagi kalian yang awam, ketika membuat sebuah blog post atau artikel di Jekyll, kita benar-benar membuat sebuah file.

Jekyll bisa membaca untuk file dengan ekstensi **Markdown** dan **HTML**. Jadi, untuk membuat sebuah post, kita membuat file .md atau .html menggunakan text editor. Saya menggunakan [Visual Studio Code](https://code.visualstudio.com/).

<p>
<img class='img-fluid' src='\img\posts\editor_vs_code.jpg' alt='Editor Visual Studio Code untuk menulis artikel'>
<figcaption class="figure-caption text-center">Seems legit, right?</figcaption>
</p>

### 3. Offline Working
Sudah tau kan, kalau membuat artikel di Jekyll, kita menggunakan text editor. Sehingga, pekerjaan menulis artikel bisa dilakukan secara offline saja. Tanpa harus terkoneksi dengan internet.

Hal ini juga sama seperti kita menulis di blogspot. Tapi, Jekyll yang mampu membaca format markdown, kita tidak perlu melakukan styling setelah menulis artikel.

Kebayang kan? Sudah nulis 7000 kata terus cari satu-satu kata mana yang harus diberi bold, terus dikasih link, dibikin miring. Kan ribet. Dengan Markdown, tinggal terima beres.

### 4. Social Network
Dasar dari GitHub Pages tanpa social system. Sehingga untuk _commenting system_ menggunakan sistem terpisah. Saya mengamati pengguna Jekyll banyak menggunakan Disqus sebagai commenting blog mereka.

> Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through a converter (like Markdown) and our Liquid renderer, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server.
>> Whatever, happy blogging!

Kesimpulannya, saya ingin mendalami Jekyll lagi. Entah itu basic-nya Gem atau justru _compare_ dengan framework lain seperti Gatsby atau Hugo.

Menggunakan Jekyll bukan biar keren atau anti-yang rame-rame (mainstream) kok. Atau biar dibilang, wih _prohremmer_ nich, _developer_ nich. Tapi karena _build environment_-nya lebih menarik. Selain itu, lebih bebas.

Saran saya, kalau kamu bukan _technical user_ yang sudah ngerti gimana cara setup web baik itu struktur file di dalamnya maupun komposisi website itu sendiri, lebih baik tunda dulu menggunakan Jekyll. Pahami sedikit demi sedikit.

Soalnya, instalasi Jekyll itu ribet. Harus bikin GitHub Page dulu, kemudian clone ke repository lokal menggunakan GitHub Desktop. Kalo mau pasang theme atau develop sendiri, harus ngerti susunan file-nya. Ribet ah, serius!

Tapi, tantangannya di situ sih. Kebetulan saya menyukainya, bisa dipakai buat belajar. Sebelum saya menulis artikel ini, saya harus berjibaku untuk melakukan setup SSL untuk blog ini. Ribet, serius.

Itung-itung bisa dipake buat belajar lah. Siapa tau kan bisa belajar Ruby dikit. Ya ga rugi lah, kan host-nya gratis di GitHub, terus domainnya numpang di domain utama. Hahaha...
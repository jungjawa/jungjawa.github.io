---
layout: post
title:  "Membuat Web Blog Statis dengan Jekyll dan Github Pages (Part 2) — Instalation"
subtitle: "Jekyll dan Github bisa digunakan untuk membuat blog dengan gratis dan mudah"
date:   2019-05-04 06:45:13 -0400
permalink: membuat-web-atau-blog-statis-gratis-pada-github-dengan-jekyll
comments: true
description: Ingin membuat website statis untuk blogmu? You are in the right place to start!
background: '/img/posts/bg-part-2-menggunakan-jekyll.jpg'
---

Pada post ini, saya akan melakukan banyak sekali simplikasi, _i try to make this as simple as possible_. Ya kan nggak semua orang akan mengerti _technical stuff_ dan seenggaknya dari artikel ini, mereka akan mendapatkan gambaran yang jelas.

_By the way_, saya sudah menuliskan [Part 1 untuk Introduction](https://dev.jungjawa.com/mencoba-membuat-situs-web-dengan-jekyll). Silakan dibaca jika berminat.

Sebenarnya, untuk membuat sebuah website statis bisa saja dengan mudah menggunakan Wordpress. Tergantung _template_ atau _themes_ yang dipilih, maka website yang dibuat bisa langsung digunakan. Tapi, rasanya kurang cocok jika 'hanya' membuat sebuah website kecil atau blog post saja menggunakan Wordpress. Terlihat berlebihan jika harus menggunakan Wordpress dengan segudang fitur dan plugin-nya bisa lebih dari itu.

_That’s why I want to try a static site generator to see the alternatives_. 

## Required Tools
Berikut ini adalah beberapa tools yang kita perlukan:

- **Github Account**: bisa dengan mudah dibuat di [github.com/join](https://github.com/join) _(free)_
- **Internet Browser**: Chrome, Firefox, Safari
- **Text Editor**: Tergantung selera kalian, saya lebih prefer [Visual Studio Code](https://code.visualstudio.com/) _(free)_
- **Github Desktop**: ini penting agar mempermudah _commit_ pada repositori kita di Github Pages. Silakan download di [desktop.github.com](https://desktop.github.com/) _(free)_
- **Knowledge**: Version Control System, Markdown/HTML, Github,

Sebenarnya ada cara lain untuk membuat static website ini, yaitu menggunakan _package manager_ Gems. Namun, saya lebih memilih metode konvensional saja.

## Create Github Page Account

Setelah membuat akun github, buat repositori baru di Github dengan format username.github.io (ya terserah aja kalian ganti username-nya). Berikut ini adalah contoh repositori saya untuk blog ini.

<p>
<img class='img-fluid' src='\img\posts\github-repo.jpg' alt='Repository baru di Github'>
</p>

Nah, setelah **Create Repository**, halaman Github bisa diakses melalui http://username.github.io. Contohnya kalau saya bisa diakses di [dev-jungjawa.github.io](#)

Saat ini, repositori sudah berhasil dibuat namun username.github.io belum bisa diakses karena tidak ada file yang di-_upload_ ke repositori. Selain itu, file <code>index.html</code> dan asset lainya yang diperlukan belum tersedia.

## Install Jekyll
Saatnya mengisi blog kita dengan Jekyll. Bisa menggunakan Jekyll default yang dokumentasi lengkapnya bisa kalian baca di [Github: Using Jekyll as a static site generator with Github Pages](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages).

Jika ingin mudah, bisa menggunakan beberapa tema dari penyedia berikut yang tentu saja free. _I love free stuff_.
- [jekyllthemes.org](http://jekyllthemes.org/)
- [jekyllthemes.io](https://jekyllthemes.io/free)
- [themes.jekyllrc.org](http://themes.jekyllrc.org/)
- [Jekyll topic on Github](https://github.com/topics/jekyll-themes)

### Install via Github Desktop
Cara ini hanya berlaku jika menggunakan tema yang sudah tersedia di Github. Kita bisa langsung melakukan instalasi Jekyll menggunakan **Clone** atau **download**.

Jika menggunakan Github Desktop, pilih **Open in Desktop**. Pastikan Github Desktop sudah terinstall dan menggunakan akun Github yang sudah dibuat.

<p>
<img class='img-fluid' src='\img\posts\clone-repo-jekyll.jpg' alt='Clone Jekyll Github Repository'>
</p>

### Install via Zip files
Cara ini lebih mudah dipahami.

Download file Jekyll themes. Kemudian ekstrak file tersebut dan **Upload Files** melalui repositori Githu. File zip yang diupload seperti **_includes, _layout, _posts, css,** dan aset lainnya. Jangan lupa untuk *Commit changes* yang berfungsi seperti save file project di Github.

## Setting Up
Setelah semuanya selesai, selanjutnya konfigurasi website/blog melalui file **_config.yml**. Lengkapi data yang ada seperti Author, Title, Social Media Network dan lain sebagainya.

Saat ini, username.github.io sudah bisa diakses. Selanjutnya tinggal kustomisasi tampilan maupun struktur.

## How to write a blog post
Blog post dibuat di dalam folder **_posts**. Jenis file bisa menggunakan format <code>.html</code> atau Markdown yang memiliki ekstensi file <code>.md</code>.

Jika kamu lebih familiar dan mau menulis dengan mudah, saya rekomendasikan untuk menulis dalam format Markdown saja.

Blog post yang dibuat harus menggunakan format yang sudah ditentukan.

 <code>YEAR-MONTH-DAY-title.MARKUP</code>

Contohnya, saya membuat blog post ini dengan nama file:

<code>2019-05-04-membuat-web-atau-blog-statis-gratis-pada-github-dengan-jekyll.md</code>

Semua file post harus menggunakan **front matter** yang berisi layout atau meta data. Jika kurang jelas, Jekyll telah menyediakan dokumentasi lengkap tentang [blog post on Jekyll](https://jekyllrb.com/docs/posts/).

#### Referensi:
- [Jekyll on Github](https://github.com/jekyll/jekyll/wiki/Themes)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Markdown Cheatsheet by Adam Pritchard](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

___

<small>PS : for all the Github users expert who reads this easy post, hehe I know, I left out many important technical parts like git, using package manager or installing other tools.

But if I try to simplify this post.

Sometimes it’s better to be simplifying everything but understood, than to be over details step by step but with no one understand technical things.</small>
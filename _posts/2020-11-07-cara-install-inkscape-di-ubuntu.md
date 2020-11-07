---
layout: post
title:  "Cara Install Inkscape di Linux Ubuntu"
description: This is a post description for meta purposes. This is also the excerpt of the article that shows up on the index/home page. Change this in the post YAML.
---
Inkscape adalah aplikasi andalan untuk membuat desain jenis vector seperti adobe illustrator dan coreldraw, namun inkscape ini gratis dan open source  Tidak seperti adobe dan corel, inkscape ini tersedia untuk lintas platform, inkscape bisa diinstall di Linux, Windows, maupun Mac OS.

![Inkscape Screenshot](/assets/img/distro-linux/inkscape-ss.png)

Inkscape dikembangkan oleh The Inkscape Team yang dirilis perdana pada 2 November 2003, dibawah lisensi GNU-GPL yang menggunakan file berformat svg.

Saya biasa menggunakan inkscape untuk membuat logo, banner, flyer, desain baju, id card, dll.

Untuk menginstall inkscape di linux khususnya ubuntu, debian, dan turunannya, dapat menggunakan 4 cara, yaitu:

1. Melalui repository
2. Melalui Snap
3. Melalui Flatpak
4. Melalui Appimage (portable)

Namun yang akan saya bagikan disini hanya yang melalui repository, selain lebih ringan aplikasinya karena ukuran lebih kecil hanya 110 Mib-an, juga cara ini paling umum dilakukan.
Berikut ini caranya:

Buka terminal sobat, dan ketikan:

{% highlight bash %}
$ sudo add-apt-repository ppa:inkscape.dev/stable

$ sudo apt-get update

$ sudo apt install -y inkscape
{% endhighlight %}

Tunggu sampai proses selesai, dan inkscape pun siap dipakai, untuk membukanya bisa ketikan perintah

{% highlight bash %}
$ inkscape
{% endhighlight %}

Mungkin hanya itu yang bisa saya tulis pada kesempatan kali ini, semoga bermanfaat ^_^


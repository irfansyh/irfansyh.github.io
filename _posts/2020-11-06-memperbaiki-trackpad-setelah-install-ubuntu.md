---
layout: post
title: "Cara memperbaiki Tap to Click Trackpad tidak berfungsi setelah install Ubuntu"
comments: true
description: "GNU/Linux adalah sistem operasi sumber terbuka yang gratis dan mudah digunakan, kelebihan linux adalah banyaknya distribusi (distro) yang bisa dipilih sesuai kebutuhan penggunanya. inilah beberapa distro linux yang saya rekomendasikan untuk sobat semua yang mungkin ingin pindah ke linux"
keywords: "memperbaiki trackpad tidak berfungsi setelah install linux di laptop"
---

Artikel ini saya buat setelah saya coba memperbaiki trackpad yang tidak berfungsi di notebook teman saya, Samsung NP-N120 dan Alhamdulillah berhasil. Jadi ceritanya Notebook teman saya itu lumayan lawas, pakai windows 10 sangat berat untuk aktifitas sekadar kutak-ketik di microsoft word juga. Saya coba install ulang dengan mengganti OS ke GNU Linux, kebetulah akhir-akhir ini saya lebih suka OS dan Aplikasi yang open source, sudah cukup lama juga saya menggunakan ubuntu di komputer saya. Balik lagi ke laptop teman saya, karena sudah lumayan jadul, maka saya pilih Ubuntu dengan DE (Lingkungan desktop) LXQT alias Lubuntu, versi terbaru 20.04 LTS. Jujur, saya baru pertama kali menginstall Linux di laptop, biasanya di komputer. 

<img src="{{ '/assets/img/distro-linux/trackpad.jpg' | prepend: site.baseurl }}" alt="Memperbaiki trackpad linux yang tidak berfungsi" width="85%" height="auto">


Kendala yang saya alami pertama kali adalah laptop tidak mau booting ke usb bootable, setelah saya tanya-tanya di grup Linux, ternyata bootablenya harus dibuat menggunakan Etcher (sebelumnya saya menggunakan terminal dengan perintah dd). Setelah bisa install, masalah kedua muncul, yaitu trackpad tap tidak berfungsi, klik kanan dan kiri berfungsi. Akhirnya saya googling sana-sini, ketemu juga caranya di forum ubuntu. Mungkin masalah ini juga terjadi pada sobat, tapi tenang, sobat sedang membaca artikel yang tepat.

Berikut cara memperbaiki trackpad yang tidak berfungsi setelah install ubuntu dan turunannya (Zorin Os, Kubuntu, Xubuntu, Lubuntu, Linux Mint, Ubuntu Mate, Ubuntu Budgie, dll), mungkin cara ini juga berfungsi di distro lain seperti Debian ataupun Arc Linux.

Caranya sangat mudah, sobat hanya perlu menginstall Synaptics Touchpad driver, langkahnya:

1. Buka terminal,
2. Ketikan kode berikut:

```sudo apt-get install xserver-xorg-input-synaptics```

3. Reboot laptopmu.

Dan, trackpad sobat telah berfungsi kembali.

Itulah cara memperbaiki trackpad/touchpad/bantalan sentuh (padanan bahasa indonesia) di laptop setelah install linux, semoga membantu. Jika ada yang kurang dimengerti, mari kita diskusikan di kolom komentar.
Terima kasih.

Link rujukan [ubuntuforums.org](https://ubuntuforums.org/showthread.php?t=2396860).

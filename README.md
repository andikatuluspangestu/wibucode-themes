
Hugo Blog Wibu Code

<br>

Tasks

search
single responsive
kategori
kode highliter
List tag
Diskus
Hal about
Fix link
Fix link Lainnya
Taxonomi Bahasa
Path
Taxonomi Topik
Fitur News Later
Buat Dokumentasi 


<br><br>
💡 Dokumentasi

Persiapan Aplikasi
Aplikasi - aplikasi yang harus di install yaitu:
Visual Studio Code atau Sublime Text <br/>
  Untuk cara penginstalan VSCode sendiri bisa dilihat di situs VSCode For Linux <br/>
  Untuk penggunaan markdown bisa install extensi Markdownlint <br/>
  Untuk yang menggunakan Sublime bisa ikuti cara di situs Markdown for Sublime Text
Git <br/>
  Untuk cara penginstalan Git sendiri bisa dilihat pada situs Windows dan Linux
Hugo  
Untuk cara penginstalan hugo sendiri bisa dilihat pada web berikut : 
Linux, Windows, MacOS



&nbsp;
Buat Artikel
Sebelumnya Clone dulu repo ini.  
Jika sebelumnya sudah pernah di-clone. lakukan git pull dulu  

Untuk membuat artikel 
Pertama masuk ke direktori wibucode-blog-hugo
Lalu setelah itu buka command line/terminal/cmd, ketikan hugo new posts/nama-post.md lalu enter.  
Nanti akan ada file baru pada folder contents/posts. 
Nah disitulah tempat menulis artikel. ( Artikel ditulis dengan menggunakan bahasa markdown ) 
Untuk melihat webnya secara lokal bisa dengan perintah hugo server. 
Lalu pada url browser ketika localhost:1313atau klik [localhost](https://localhost:1313)


&nbsp;
Tutorial Markdown
Untuk tutorial markdown silahkan lihat pada link berikut: 
Petanikode, 
Gits Github, untuk enter ketik spasi dua kali pada akhir paragraf.
Install extensions markdownlint di Visual Studio Code untuk melihat preview markdown file.


&nbsp;
Pengaturan Post
Jika kita buka file md yang telah dibuat maka akan terlihat kode berikut.
yaml
​
​
author: "Wibucode"
title: "38post"
date: 2020-12-12T23:26:43+07:00
draft: true
featured_image: "bocchi4-450x300.jpg"
tags: 
html
css
categories:
Back End
bahasa:
html
topik:
HTML Dasar
​

Dan itu semua wajib ada isinya.
author: Isi author dengan nama kalian yang ingin ditampilkan. Contoh: Alice Violet
title: Isi ini dengan judul artikelnya misal Pengaruh pemrogaman pada industri 4.0
date : Bagian ini tak usah diubah
draft : Ganti jadi false jika ingin mengpublish postingan
featured_image : Isi dengan gambar yang ingin ditampilkan. Gambar disimpan pada folder. themes/wibucode/static/img 
tags : Isi dengan tagsnya. seperti misalnya html,css,javascript
categories : Isi dengan kategori postingan, misalnya: Iot, Front End, Mobile Programming, Artificial Intelligence
bahasa : Isi dengan bahasa / bahasa pemrogaman, misalnya: html, php, javascript, atau xml
topik : Topik Disini seperti nama materi pada suatu pelajaran yang nantinya akan ditaruh pada misalnya path Front End Development. Contohnya seperti: HTML Dasar, HTML Lanjutan, HTML Tabel, PHP Dasar, PHP OOP, CodeIgniter, Laravel, dan sebagainya.

&nbsp;
Mempublish Postingan
Untuk mempublish postingan pastikan draft: false
Kemudian buka command line/terminal/cmd
ketik git add . lalu git commit -m "update" kemudian git push
lalu ketik hugo
setelah itu cd public
lalu ketik git add . lalu git commit -m "update" kemudian git push
Tunggu sekitar 2 - 3 menit. Selesai.

&nbsp;
Path
Path dibuat agar materi menjadi terstruktur sehingga mempermudah user dalam belajar. Klik menu belajar untuk melihat path yang ada

&nbsp;
Troubleshooting
Jika mengalami kesulitan atau kurang memahami Dokumentasi, bisa berdiskusi di Grup Whatsapp Project Bareng Wibucode, dan untuk error coding bisa ditanyakan di Kotakode atau Stackoverflow



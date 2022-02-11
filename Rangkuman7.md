# Tugas1-SEKURO_Programming-16521098


<h2> Rangkuman Video 12 </h2>

<h2> About .gitignore </h2>

<h4> .gitignore digunakan untuk menyeleksi file yang ingin di-push. Saat menggunakan command <strong> git add . </strong>, ada file-file hidden yang akan terbawa. Maka dari itu, untuk menghindari hal tersebut terjadi, digunakan .gitignore </h4>

<img src="Screenshots/Gambar 7-1.jpg">
<h5> Tampilan Visual Studio Code </h5>
<h4> Hal pertama yang perlu dilakukan adalah membuat file dengan nama <strong> .gitignore </strong>

<img src="Screenshots/Gambar 7-2.jpg">
<h5> Tampilan Visual Studio Code </h5>
<h4> Lalu di dalamnya kita ketik nama file yang tidak ingin kita ikut sertakan untuk masuk ke dalam staging area </h4>

<img src="Screenshots/Gambar 7-3.jpg">
<h5> Tampilan Visual Studio Code </h5>
<h4> Pada saat melakukan add dan commit, file 'config.txt' tidak ikut ke dalam staging area </h4>
<h4> Di dalam file .gitignore juga bisa menyeleksi sebuah folder atau semua file dengan format yang sama <br>
contohnya :
<ul> <li> untuk menyeleksi folder -> (namafolder)/ <br>
contoh -> data/

<li> untuk menyeleksi semua file dengan format yang sama -> *.(format) <br>
contoh -> *.exe </ul>

<h3> <strong> Dokumentasi .gitignore </strong> </h3>
<h4> Untuk dokumentasi yang lebih lengkap mengenai .gitignore, dapat dilihat di <strong> <em> github.com/github/gitignore </em> </strong>. </h4>
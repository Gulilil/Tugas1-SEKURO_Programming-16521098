# Tugas1-SEKURO_Programming-16521098


<h2> Rangkuman Video 3 </h2>

<h2> About Git Branch </h2>

<h3> <strong> Branching </strong> </h3>
<ul>
<li> Membuat Git Branch
<li> Membaut snapshot (atau semacam jalur alternatif) tanpa mengganggu jalur utama (Master branch)
<li> Fitur Experimental, saat ingin mencoba sesuatu, fitur branch dapat digunakan untuk tidak 'merusak' branch utama.
<li> Dapat dikerjakan lebih dari 1 orang untuk repo yang sama
</ul>

<h4> <strong> Saat ingin menyatukan branch, aksi tersebut dinamakan merging </strong></h4>

<img src="Screenshots/Gambar 3-1.jpg">
<h5> Tampilan saat ingin membuat branch baru pada github </h5>
<h4> Perubahan yang dilakukan pada branch tidak akan menggangu jalur utama </h4>

<img src="Screenshots/Gambar 3-2.jpg">
<h5> Tampilan saat membuat file baru pada repository </h5>
<h4> Pada bagian bawah pembuatan file baru, tak lagi tertulis commit to "main", tapi to ("nama branch")</h4>

<h3> <strong> Merging </strong> </h3>

<img src="Screenshots/Gambar 3-3.jpg">
<h5> Tampilan halaman utama pada branch </h5>

<h4> Untuk melakukan merging, tekan tombol "Compare & pull request" </h4>

<img src="Screenshots/Gambar 3-4.jpg">
<h5> Tampilan halaman "Compare & pull request" </h5>

<h4> Pemilik branch akan melakukan request kepada pemilik main untuk melakukan perubahan. Maka dari itu dinamakan <strong> Pull Request </strong> </h4>

<h4> Setelah pull request dilakukan, pemilik main dapat melihat request pada bagian "Pull request" dan melihat request yang dikirimkan </h4>
<h4> Request tersebut dapat diterima, <strong> Confirm Merge </strong>, atau tidak diterima.

<img src="Screenshots/Gambar 3-5.jpg">
<h5> Tampilan bagi pemilik main untuk melakukan confirm merge </h5>

<h3> <strong> Deleting Branch </strong> </h3>
<h4> Pada halaman utama repository, klik laman 'Branches' </h4>

<img src="Screenshots/Gambar 3-6.jpg">
<h5> Tampilan bagian "Branches" </h5>

<h4> Menghapus branch dapat dilakukan dengan menekan icon tempat sampah di bagian kanan branch </h4>

<h3> <strong> Non-Ideal Merging </strong> </h3>
<h4> Terkadang dalam melakukan merge, timbul konflik antara main dan branch </h4>
<img src="Screenshots/Gambar 3-7.jpg">
<h5> Tampilan pull request tapi "Can't automatically merge"</h5>
<h4> Pull request dapat dilakukan, tetapi merge tidak bisa langsung dilakukan. Maka dari itu, perlu dilakukan <strong> Resolve Conflict </strong> .</h4>

<img src="Screenshots/Gambar 3-8.jpg">
<h5> Tampilan code editor saat melakukan resolve conflict </h5>
<h4> Setelah melakukan perbaikan secara manual, merge dapat dilakukan dengan menekan tombol <strong> Mark as Resolved </strong>. </h4>
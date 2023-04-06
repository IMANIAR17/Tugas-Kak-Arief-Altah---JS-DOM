Section2
Contoh 1
Mengubah warna pada elemen dengan ID "header" menjadi tomTat.

Contoh 2
Mengubah teks pada elemen dengan ID "myParagraph".

contoh 3
Menambahkan event listener pada elemen dengan ID "myButton".

contoh 4
Kode ini mengambil elemen dengan "tombol" kelas dan menambahkan pendengar acara ke tombol. Saat tombol ditekan, kode menampilkan konten setiap elemen (innerText) menggunakan kelas "Mahasiswa" menggunakan loop dan alert

contoh 5
Skrip JavaScript dalam file Script.js menggunakan metode querySelector() untuk mendapatkan elemen h1 dan p dari dokumen HTML. Selanjutnya, kode menambahkan kelas text-tomato ke elemen h1 menggunakan metode classList.add() dan mengubah font elemen gaya p menjadi 18 piksel menggunakan properti style.fontSize.   

Section 3
Contoh 1
Mendapatkan elemen anak. Mendapatkan elemen parent. Mengubah teks pada elemen parent.

contoh2
Mendapatkan elemen child berdasarkan tag name. Mengubah teks pada elemen.

contoh 3
Mendapatkan elemen yang dipilih. Mendapatkan elemen child. Mengubah teks pada elemen child.

contoh 4
properti parentNode digunakan pada elemen tersebut untuk mengambil elemen induk atau parentnya
metode childNodes digunakan pada elemen induk tersebut untuk mengambil daftar dari semua anak elemennya, termasuk elemen target dan elemen sibling

Section 4
contoh 1
Membuat elemen baru. Menambahkan elemen baru ke dalam parent elemen.

contoh2
Membuat elemen gambar baru. Menambahkan elemen gambar baru ke dalam parent elemen.

contoh 3
Membuat elemen tombol baru. Menambahkan elemen tombol baru ke dalam parent elemen.

section 5
contoh1
Mengganti warna latar belakang

contoh 2
Mengubah input field menjadi tombol

section 6
contoh 1
Ubah Warna Text

contoh2
Menambahkan border pada gambar.


contoh 3
getElementById("infoDiv") digunakan untuk memilih elemen dengan id="infoDiv" pada dokumen HTML. Kemudian, window.getComputedStyle(infoDiv) digunakan untuk mendapatkan semua nilai gaya CSS terkompilasi untuk elemen tersebut, dan nilai-nilai tersebut disimpan dalam variabel styles. 
 console.log() untuk menampilkan nilai dari beberapa properti CSS pada elemen infoDiv. Dalam contoh ini, kita menampilkan nilai dari properti backgroundColor, width, dan height

section 7
contoh 1
Menambah event keydown. Saat menekan "Space" pada keyboard,

contoh2
Menambahkan event keydown. Saat menekan "ArrowRight" pada keyboard

contoh 3
Menambah event click. Saat klik "Klik saya!",

contoh4
Menambahkan event mouseover. 

section8
contoh1
terdapat nilai value yang berbeda-beda, yaitu "male" dan "female". Setiap radio button juga diberi atribut id untuk memudahkan pengaksesan dalam JavaScript.
dengan menggunakan method document.getElementById(). Id yang digunakan sesuai dengan atribut id yang diberikan pada radio button di HTML. Setelah itu, kode menambahkan event listener untuk setiap radio button yang ada dengan menggunakan method addEventListener().

contoh2
 terdapat sebuah form yang berisi empat radio button dengan atribut name="color" dan nilai value yang berbeda-beda, yaitu "tomato", "biru", "pink", dan "abu-abu". Pada bagian JavaScript, pertama-tama kode mendapatkan semua elemen radio button dengan menggunakan method document.getElementsByName('color'). Nama 'color' digunakan karena atribut name pada radio button diberi nilai 'color'. Setelah itu, kode menambahkan event listener untuk setiap radio button yang ada dengan menggunakan loop for. Setiap kali pemilihan radio button berubah, maka fungsi yang ditentukan akan dijalankan. Dalam fungsi tersebut, kode mendapatkan nilai radio button yang dipilih dengan menggunakan method document.querySelector('input[name="color"]:checked').value. Method ini akan mencari elemen radio button yang dipilih berdasarkan atribut name dan status checked, dan mengambil nilai value-nya. Terakhir, nilai yang dipilih dapat diolah sesuai kebutuhan. Pada contoh di atas, kode hanya menampilkan nilai yang dipilih pada console menggunakan method console.log(). 
 
 contoh 3
 input field dengan ID "input-field" dan sebuah elemen p dengan ID "output". Property "display" pada elemen "output" diatur awalnya ke "none" di dalam CSS,  Kemudian kita menggunakan JavaScript untuk menambahkan event listener pada input field untuk event "input".
 Ketika event tersebut terpicu (misalnya ketika pengguna mengetikkan di dalam input field), kode di dalam event listener dijalankan. Di dalam event listener, kita mengambil nilai dari input field menggunakan "event.target.value" dan menyimpannya ke dalam sebuah variabel bernama "inputValue". Kemudian kita menetapkan teks dari elemen "output" ke "Anda mengetikkan: " ditambah dengan nilai "inputValue". Akhirnya, kita mengatur property "display" pada elemen "output" ke "block" untuk menampilkannya di halaman. 



contoh4
Berikut adalah contoh penggunaan event input pada field input dengan id field input dan pada elemen p dengan id output. Kolom input memiliki nomor tipe dan atribut min dan maks masing-masing diatur ke 0 dan 100. Elemen keluaran disembunyikan dan properti tampilan tidak disetel di CSS. Properti warna diatur ke merah untuk penekanan visual saat pesan konfirmasi ditampilkan. Selanjutnya kita menambahkan event listener ke kolom input dari event input. Di dalam event listener, kita mendapatkan nilai input field menggunakan perintah event.target.value dan menyimpannya dalam variabel yang disebut inputValue. Setelah itu kami memeriksa apakah inputValue kurang dari 0 atau lebih besar dari 100. Jika demikian, kami menyetel teks dari elemen hasil ke pesan konfirmasi dan menyetel properti tampilan dari elemen hasil untuk mencegahnya ditampilkan di halaman. Jika tidak, jika inputnya valid, kami menyembunyikan elemen output dengan menyetel properti tampilannya menjadi tidak ada. Jadi ketika pengguna memasukkan angka di kolom input, muncul pesan konfirmasi di bawah kolom input jika inputnya kurang dari 0 atau lebih besar dari 100, dan menghilang jika inputnya valid. 









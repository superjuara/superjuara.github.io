---
layout: post
title: "Belajar HTML dasar"
date: 2019-03-25 13:27:13 +0800
categories: Belajar Program
tags: HTML
---


HTML adalah bahasa pertama yang harus dipelajari bila kamu ingin menjadi seorang Web Developer, karena HTML merupakan bahan dasar untuk membuat web.

Apa itu HTML?

HTML atau Hyper Text Markup Language merupakan sebuah bahasa markah untuk membuat halaman web. Padanan HTML dalam bahasa indonesia adalah Bahasa Markah Hiper Teks (BMHT)


Membuat file HTML

File HTML dapat dibuat dengan teks editor seperti notepad. Lebih bagus lagi menggunakan teks editor yang memiliki fitur syntax highlighter seperti Notepad++, Sublime Text, Gedit, Kate, dan lain-lain. File HTML disimpan dengan ekstensi html atau htm.


Contoh-contoh HTML

Kita ingin menampilkan informasi di website. Informasi ini merupakan sebuah pesan: Situs web ini milik Ardianta. Maka bentuk kode HTML-nya akan seperti ini:


{% highlight php linenos %}
<!DOCTYPE html> 
<html> <body> Situs web ini firdaus siregar
</body></html>
{% endhighlight %}


HTML di disusun dengan tag-tag (penanda). Perhatikanlah, letak penulisan informasi yang ingin dimuat di website. Berada di atantara tag *<body>* dan *</body>*. tag ini merupakan tubuh dokumen. Setiap informasi yang ditulis di dalam penada ini, akan tampil di halaman web.


Contoh selanjutnya, kita akan berkenalan dengan tag <head> dan tag <title>. Tag <head> merupakan kepala dokumen. Agar lebih mudah memahami, cantoh yang tadi kita modifikasi. Tambahkanlah tag <head> dan tag <title> Sehingga kodenya menjadi seperti di bawah ini.


{% highlight php linenos %}
<!DOCTYPE html> <html> <head> 
<title>Situs Web firdaus</title></head> 
<body> Situs web ini milik firdaus</body></html>
{% endhighlight %}

Tag <title> berfungsi untuk membuat judul website. Sementara itu tag <head> berfungsi untuk membuat kepala dokumen. Tag <title> harus diletakkan di dalam tag <head>. Perhatikanlah hasilnya, teks yang ada di tag <title> akan ditampilkan sebagai judul website.



Contoh berikutnya, kita akan berkenalan dengan tag <h1> dan tag <p>. tag <h1> berfungsi untuk membuat judul artikel. H1 adalah ukuran judul terbesar di HTML. Sementara itu, tag <p> berfungsi untuk membuat paragraf. Modifikasi lagi kode tadi, sehingga menjadi seperti berikut ini:


{% highlight php linenos %}
<!DOCTYPE html><html>
<head><title>Situs Web firdaus</title></head> <body> 
<h1>Tentang situs web ini</h1> 
<p>Situs web ini milik firdaus. Dibuat pada tanggal 25 maret 2019. Tujuan membuat situs web ini, untuk latihan saja. Situs ini belum mengudara, karena masih tersimpan di komputer saya sendiri (lokal). Suatu saat nanti,situs ini akan kusimpan (hosting) di sebuah server di internet.</p></body> </html>
{% endhighlight %}

Perhatikanlah hasilnya, Teks yang berada di dalam tag H1 akan ditampilkan lebih besar. Karena teks itu adalah sebuah judul artikel. Sementara itu, teks yang berada di tag <p> akan ditampilkan dengan ukuran normal. Untuk lebih jelasnya, cobalah tambahkan paragraf lagi di bawahnya.


Kesimpulan

HTML adalah bahasa yang wajib dipelajari oleh siapa saja yang tertarik menjadi pembuat website (Web Developer). Karena HTML merupakan bahan dasar untuk membuat website. Contoh-contoh sederhana di atas sudah menjelaskan bagaimana kode HTML itu. Banyak tag yang harus di hafal. Kunci untuk mengingatnya adalah sering berlatih membuat file HTML. Insa’allah anda akan ingat di luar kepala.

Cukup sekian dulu pengenalan HTML ini, bagaimana pendapatmu? Apakah sudah paham dan mengenal HTML, sekarang?




---
sidebar_position: 1
---


Pseudo Element merupakan sebuah selector yang berfungsi untuk menyeleksi elemen atau tag secara otomatis, tapi bisa juga diartikan sebagai selector yang menciptakan elemen atau tag palsu tanpa menuliskan kode HTML.

  

Pada versi sebelumnya Pseudo Element ditulis dengan menggunakan 1 tanda titik dua “:”, tetapi pada versi CSS3 Pseudo Element ini ditulis dengan menggunakan 2 tanda titik dua “::”. Perubahan ini dibuat untuk lebih mempermudah membedakan antara Pseudo Class dan Pseudo Element.

Contoh penulisan Pseudo Element di dalam CSS adalah sebagai berikut:

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXeFrUGXoD1HQEkyi55Jl41I0b14LYZeGOrz42RkAM-y4ol-uZvQQip5xURwbKutl92x2mUJPmAZfxFBckBNL_H2fx0HUiJBtormebky_1QNofmVH4hiNtlidf4neqt_m80adqYkblyp-b3XxjZ9egpsVL2NdG1GWp1B2jIJCE6N2A6s-E1Bcpk?key=ESYW2iUyREQEYzkaKMR1vg)

Pada contoh diatas yaitu menggunakan pseudo element ::first-letter, dimana element ini berfungsi untuk melakukan perubahan style pada huruf pertama dari sebuah paragraf.

Ada banyak pseudo element dalam CSS, berikut ini akan membahas mengenai pseudo element yang sering digunakan agar tampilan website lebih menarik.

1.  ::before & ::after
    

Sebuah psudo element yang memungkinkan kita untuk menambahkan konten baru (sebelum/ sesudah element) pada halaman HTML hanya melalui CSS saja, element ini tidak benar-benar ada dalam struktur html, namun tetap akan digenerate oleh browser sehingga akan tetap tampak, namun ketika kita lihat source nya (view source), kita tidak akan menemukannya, penggunaan element ini benar-benar sama seperti element real lainnya.

2.  ::first-letter
    

Memilih huruf pertama dalam elemen. Biasa dipakai untuk dropcap (Huruf pertama yang membesar).

3.  ::first-line
    

Memilih baris pertama dari sebuah teks di dalam elemen.
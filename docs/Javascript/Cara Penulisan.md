---
sidebar_position: 3
---

Ada 2 Cara penulisan dalam JavaScript.

**1. Inline**

Cara yang paling umum untuk memanggil fungsi JavaScript di file HTML adalah dengan menggunakan elemen script secara inline. Istilah inline dalam pemrograman mengacu pada teknik penulisan kode dalam baris yang sama dengan file sumber.

Pada konteks ini, skrip JS ditulis secara langsung di dalam skrip HTML, sehingga termasuk dalam kategori inline. Anda dapat menempatkan elemen script di dalam bagian head atau body, tergantung kapan Anda ingin menjalankan kode tersebut.

Contoh script : 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script>

        // Kode JavaScript Anda di sebelah sini

        var nama = "jhon"
        console.log(nama)   
    </script>
</head>
<body>
    
</body>

</html>
```

**2. File External**

Cara memanggil file di HTML dengan JavaScript yang kedua adalah dengan memanggil file JS eksternal. Jika pada cara sebelumnya, kita menulis kode JavaScript langsung di dalam HTML (inline), maka sekarang kita akan menulisnya di file terpisah.

Pertama-tama, Anda perlu membuat file JavaScript yang akan Anda panggil dari halaman HTML. File JavaScript eksternal harus memiliki ekstensi ".js”, contoh script.js. Anda dapat membuatnya dengan menggunakan editor teks biasa seperti Notepad atau editor kode yang lebih canggih seperti Visual Studio Code.

Untuk dapat memanggil file script.js kedalam file html, Anda dapat melakukannya dengan menggunakan tag script di dalam bagian head atau body halaman web Anda. Cara menggunakan script di dalam head, yaitu:

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeiEY5zyThuSZEbB-MHeSDl5gf4bokWghLuSTO34EmG43KoWHpjOGDGAqliVAcyfafUmc05Bf01TV7D3nAC0gBJk7-wUxySznhpUrwnGG6XvgxWD8VTORHEGc-cN7_Syj71kqINXgW9d6fdudu445AyaVM?key=d3s-vJLBsYtwvRvGfZhdnw)**

Lalu masukan kode berikut kedalam file script.js dan masukan kode berikut : 
```
var nama = "jhon"
console.log(nama)   
```



lalu untuk melihat hasil implementasi kamu bisa menjalan kan live server untuk melihat hasil implementasinya. Lalu kamu akan masuk kedalam website dengan tampilan kosong. Selanjutnya kamu bisa inspect halaman web tersebut.

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfOI7rycKHW5T4MUhWOVx4MSZq2xpLnMc5U2h87FWlQoMp6RxtnvAa3WzMtbA0_yIW0hIeF-nqKCy5yyaimG1P6hOH4vP-SrPHZw5dHem2IRMjPVNCJwfTssfmiZfSoK0wh1WZoS-PjFpZEA6JYbrDclyI?key=d3s-vJLBsYtwvRvGfZhdnw)**

Setelah di inspect kamu pilih bagian console, dan kamu akan melihat hasil implementasi kamu.
**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdD3PHRu63XLdz5lr-SttnH1A1MvS9uurfeKKqCKeDRfJ5z_sDn1y1vds8dQezuXGyxfApoRp8ZJ1vaZ-TxUhDDvYGoq_oCJ7TggBkPNp6F_8E_7EJWOu4bF8J5eyqwnUaHbwfrBOaoZNdq4ffQW9W9XY7h?key=d3s-vJLBsYtwvRvGfZhdnw)**



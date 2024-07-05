
Nah, materi Javascript sudah selesai. Selanjutnya kita akan membuat sebuah website untuk permainan gunting batu kertas.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXchA0rDh_PDEytkrXrtDkVMS4ueLQFRv7HfCtWZQKYs_gPvNuMAZodoUORDEewcZRWAwS-Why5Kr5KViodJvjsTohzG80IJRBR_vQnlTCCLOtuRlKUyQ4jQX-UNbQOMgZeT3UF2FfVQcC69BT4c5GPJ7zsEoAnJFVlP2sO79Q?key=ESYW2iUyREQEYzkaKMR1vg)

Kalian akan mendapatkan sebuah file index.html yang berisi script tampilannya dan style.css untuk styling tampilannya. Hal yang perlu dilakukan adalah menerapkan javascript pada tampilan yang sudah disediakan.

Buatlah file script.js dan tambahkan script berikut:

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdlVLGVdFKZj9f0fn5G6m2X6c96uN-A0TO6r52Kl4gi0sWiMwlB2zPgZvAc5KllgPmIsWG3POsGTHrkHFJDZFRkDSsdLRX__ILQv1jayNrtddHGMA8MOLcd4PbrxB6cNVEfhsC2gE4vbvDC7lNkMGgOUptTu1m2xkcp0FSHAA?key=ESYW2iUyREQEYzkaKMR1vg)

Berikut penjelasan dari script diatas:

-   Kata kunci function mendefinisikan fungsi.
    
-   Nama fungsi game()
    
-   Kurung (), yang menunjukkan bahwa fungsi tidak mengambil argumen apa pun.
    
-   Kata kunci const, yang mendeklarasikan variabel konstan.
    
-   Variabel buttons, yang merupakan array tombol.
    
-   Metode document.querySelectorAll(), yang memilih semua elemen dengan kelas game-button.
    
-   Metode forEach(), yang mengulangi array dan mengeksekusi fungsi untuk setiap elemen.
    
-   Variabel forEach(), yang mewakili tombol saat ini dalam iterasi.
    
-   Method addEventListener(‘click’), memanggil sebuah fungsi ketika element tersebut diklik.
    
-   Variabel btnId, yang merupakan ID tombol yang diklik.
    
-   Nama fungsi buttonPlayer(), yang merupakan fungsi yang dipanggil ketika tombol diklik.
    

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdBzQ-E3qZQ3IdWetnps8vFbkEFF81KHljGIEij89b95mTc_cUL0KYB6ms6QaGdAd1Shz9pvD6w3VFQpitCc58POYfhQWyHt6pR_FWbC2zdX-Mk7naZBv3ialEzO6O5AQFcLGzzBz6i2XkS-o5pGBGO-FST4ipbJlMBiEKLYw?key=ESYW2iUyREQEYzkaKMR1vg)

Berikut penjelasan dari script diatas:

-   membuat sebuah fungsi buttonPlayer(). Fungsi ini memiliki satu parameter, yaitu btnId, yang merupakan ID dari tombol yang diklik.
    
-   membuat variabel yang digunakan untuk menampung isi elemen dengan ID hasil yang akan ditampilkan.
    
-   membuat variabel dengan nama choice yang berisi data array yang berisi tiga pilihan yang ada dalam permainan: batu, gunting, dan kertas.
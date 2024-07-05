---
sidebar_position: 2
---



Dalam asyncronous javascript banyak cara dalam menangani kode nya, seperti:

1.  Callback
    

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdJEvohb6ESadF-ra8C7b7OUgS26DHaFEIE2aRmdctaDpUft3avxqVaUGwUhbxkyFQYOkFQtaTLjywueLFE6udEqa7nms25rb92s9APg1uTRCHByePIxpN5Ptb3_h9TJqNQhNX_cats62m8T7gibS0VYDruHvJyxuLgioVjUg?key=ESYW2iUyREQEYzkaKMR1vg)

Callback adalah salah satu cara asli untuk menangani kode asinkron dalam JavaScript. Namun, dalam suatu kondisi apabila dipergunakan secara berlebihan dapat menyebabkan "callback hell" atau kondisi dimana terlalu banyak callback yang bersarang satu sama lain, sehingga membentuk struktur piramida yang sulit dimengerti.

2.  Promise
    

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfqr1fbDB4VQ2KZ8b6khY5LVCmU3uTVU29y-f4_Q6f3BRS54je67OJ-NMvu1kiY-CA0Wv55I9xEyRDEnqbfnAoKCbjro3eWXSgV-AdRDgENG4MGTuxwNlAFnoFDAsqglcyLNwbz8eHb497go83pjqDMatZmDdNX0H4q04cJnA?key=ESYW2iUyREQEYzkaKMR1vg)

Promise adalah objek yang merepresentasikan nilai yang mungkin akan tersedia di masa depan pada proses async, baik nilai berhasil atau gagal.

3.  Async/Await
    

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXe_KJZfQfbEpsU0yTVqBjTI5YEDnR6jWYZz3pKq4FWHg2Pz87rqehSqxBSusCbKNYJhN2pY191--MGpVmUxactb4tgUbai30EWswPt6FBmLkk57KKDlfnAx-muiNuLfx7Q6nKOMb-Es02_d8O22pv6vq0lB3M5sZScL_X8X4g?key=ESYW2iUyREQEYzkaKMR1vg)

Cara kerja await mirip seperti promise tetapi diposisikan sebagai expression, saat menggunakan await program akan menghentikan sementara eksekusi fungsi async disekitarnya hingga janji diselesaikan seperti janji sudah dipenuhi atau ditolak.
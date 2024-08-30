
Pengkondisian memungkinkan Anda menjalankan kode tertentu berdasarkan kondisi yang terpenuhi atau tidak terpenuhi. Dalam JavaScript, pengkondisian umumnya diimplementasikan menggunakan pernyataan if, else if, dan else.

  

**1.  Pernyataan If**

Pernyataan if digunakan untuk menjalankan blok kode jika suatu kondisi terpenuhi (bernilai true).

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdKo703Y16IS-peV6Eus_r1cfHudmq0fWa_13pVJ2uBloHMHMsVlU61MLRLYeuZ0MyTbzvrJsf9oBeb-GN3h2WVgPUBPyIZTsyh-w_d9Sr6Yyqq6S4uzO-oelgaq8Q6BlLASsevPAyr33y8EBQ0x3NM3UH5DkfCnENGnzcr?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let angka = 10;
if (angka > 6) {
    console.log("angka lebih besar dari 6.");
}
```

Hasil implementasi :

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd-UnfZVywlSvMCJpsH5mfWHjPt6SpIw8k_stYtDYPVlGaR38d1w9Rc4lMpuoXLUha6LLF7bmIVeUd0TRhET7XlQtLegu44y07X6F0tXvJ-99pokVt8TA7GuMQSy6b7A1cLZ1zx95YnEdJSOw4JM8xugdW_?key=d3s-vJLBsYtwvRvGfZhdnw)**

**2.  Pernyataan Else**
    

Pernyataan else digunakan untuk menjalankan blok kode jika kondisi pada pernyataan if tidak terpenuhi.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfYYypJh6LXjfklJCJxTp5798zI8kA5YtgcPGRQnbjSjhqAuJwEbYQeHK-VnjE3i2oZwTcuW8cDcZn3H6lqUDQsSyoHbBHyTKJsxaD33JBHaq2Us1C7zHlQra_Qkalr4I4FtQxLhVVMU5Xdh6zazUwwOW6Hz8mtXc_gWyhL6w?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let angka = 3;

if (angka >5) {
    console.log("angka lebih dari 5");
}else{
    console.log("angka tidak lebih dari 5");
}
```
Hasil implementasi :

- jika angka kurang dari 5 maka hasilnya : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdR99pOLZQS21OBvbafWp4ElBieah32-6bH1n-FFBO83-xzckX0VvFfDFJEfA4tyA8yKEZ9K35X-8Y5sVnvk36U-NeRTdce_uSBQHvTkA5WzGRW9JWk_Xnn1buaaDGmRi_pPhCDEfDpEz35_orDKcIvDLk?key=d3s-vJLBsYtwvRvGfZhdnw)**

- dan jika lebih dari 5 maka hasilnya adalah : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeeSTsQqwiJhGYXd58t3LaOcevZGCOzRJmTBVqMSUC5XjqIn73DszdPLxFZ8kOV4oEzYKJA1egAzMyLf9i8MZSNg8mGqDkXJzVsqcwWLBVh0gyX43jPHGYsCHQZKfEdI8XW00QwKXE4qZzvkZn1HeQJBQPi?key=d3s-vJLBsYtwvRvGfZhdnw)**

**3.  Pernyataan Else If**
    

Pernyataan else if memungkinkan Anda untuk mengevaluasi beberapa kondisi secara berurutan.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfmSRa79c_1s0NbH14pBEeFHB3vgllmBhJXwuofa97he8xxu8u3b4oDDGQhuWUp3rDQF-srsZ9v4s7FsmfvnfQE6yOuKArg9Qitc8esY3ewK4AzdqVrY0rn460cgPX806-4_iwNU7V-3cVu5NmREYjtNjbHRSkk0YKs5vXnvQ?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let angka = 7;

if (angka > 10) {
    console.log("angka lebih besar dari 10");
} else if (angka > 5) {
    console.log("angka lebih besar dari 5 tetapi tidak lebih dari 10");
} else {
    console.log("angka tidak lebih besar dari 5");
}
```

Hasil implementasi : 

- jika angka lebih besar dari 10 :

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdA-Hs3XHvzg_r3nHdnKypNQm_Dv9VaGa9CQVydaGWfu7dz-fsH3W45peiDRcIT3o_FCjG91v1nzb4zyoC42u-WXXdFMI0lY7IsetYtlPCYAaq-KM7pe-J8ahbZHc59Op9Hhag2INwynU7siUpYaG5Mfes?key=d3s-vJLBsYtwvRvGfZhdnw)**


- angka lebih besar dari 5 tetapi tidak lebih dari 10

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeLQXF-rK5cExCJw4c9rtTBXNWa9juvlrpxIFoxl8bFUFvZN78rJthmInBJHZoxLTkgDQPEXxwLUArQG5NtE5x2FfD-YGx_U2qJujAPfLQ7Oc6rIC_Rl9RjG-ZhtJs_DHgmiXRs3uLVOjQcUWrD24YHckHX?key=d3s-vJLBsYtwvRvGfZhdnw)**


- jika angka tidak lebih besar dari 5 : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfJ1JUBq3jR__oR5cEMsy7eVXxof8BA08VCxpJ6ycrhsJEW-Stp_90XTnaR9ztDf1gt7GR4p3L1NLYrrmJlPy0b5Cyctl77UGxby32r2VgFC5lQO-W1MQfkpcb--JTifJlvscU1TOWP2BiE55zRZdW7qNde?key=d3s-vJLBsYtwvRvGfZhdnw)**


**4.  Pernyataan Switch**
    

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdN7TmO4QV7WL5WF-cnH0m2AmYHvrBQ8151G0H66LdfhyjiQINitn57On-UDaJoLYqTf67m82cI1pYbBZxq0Ry2CtgpdOAiwKZAiaFLSJku8LTgC5pm8yg4_PkVCNvnHA9yeQA26L96b0Kq-XKDRjEsKqaUf0NJ9ZU_7FQEQQ?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let hari = "Senin";

switch (hari) {
    case "Senin":
        console.log("Hari Kerja");
        break;
    case "Sabtu":
    case "Mingguu":
        console.log("akhir pekan");
        break;
    default:
        console.log("hari tidak dikenali");
}
```
Hasil implementasi : 

- jika hari Senin : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcyMGhinCrQgE2ZYP3xty6_Fsu3DbV7HjfTECYRSMq8qLy-cWlq8Ava7prruTzEQCCIh_I3whRxkDcc4nAruxofCPVlNlVfGP23LBHnlxeucVasspPYkhaXfkW7pN-Ej9K-1FO0vouydDkVfinv3xdwC2_8?key=d3s-vJLBsYtwvRvGfZhdnw)**

- jika hari Sabtu/Minggu : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXccpkAabAZ5xnsoCOXooMYjV_tVUziAK9-bsdclE6bxRXaZ0XreDiwiJNbYHfo4vld5zUmGEFuP8Lqnk7wI7rF_nDPsLyGWan_Nyy1-XMK488WCY-paHjhUuz5-SXJ_SxCaFC9XNqXlOvtl4r5rQyi8tH-U?key=d3s-vJLBsYtwvRvGfZhdnw)**

- jika hari tidak dikenali : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfnNYYHyfi3DdE2gAuWPe_VXR56qaxa0Q81ayF-QiagEVivgjpoJfyoWVDDdAZ7vjoHcbwH6UrfLL0L6w8VVu8F82dNdXFM63pcoZ34IMAE6rjWV2AEF3Zi-vOipKirS8e94tqH75Mr9nwkganx2jXfLIBU?key=d3s-vJLBsYtwvRvGfZhdnw)**
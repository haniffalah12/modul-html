JavaScript memiliki struktur data seperti array (daftar nilai) dan objek (kumpulan properti). Dengan array, Anda dapat menyimpan banyak nilai dalam satu variabel. Dengan objek, Anda dapat mengelompokkan informasi terkait ke dalam satu unit.

Contoh penggunaan array pada javascript sebagai berikut:

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXeBl9ErOVgaKp2Oi4grEZMn0zb5wckrPdLcVXo_svInkrZJU28DO3vdcRlyTkLpoXWwUPBjmK_Sh3hoMP3R78bTud8nX54xhG0LOTYoMwv5hWdU4EnbNsj4o9_QRTkiFEKMPktzOteYc8oLu2sS82nvEVEuq4BblD0PJMVtlg?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let fruits = ['Apple', 'Banana', 'Orange', 'Manggo'];

console.log(fruits[0]);
console.log(fruits.length)

fruits.push('Grapes');
console.log(fruits);
```
Hasil implementasi :

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe-TNuVVmXt-Xrv_b8vgJ_gLvFE3Ci2L_DwaijlBYqkdjyck75Jg8xFtOafA52Qxux3GU0Qw0h_wuMcnFo4eYZB8RoIJHjSRvxx3aTe_dQAEbmBda8kkyPpT_v2xa7BvFo22kwhSYkkQEPzv4atnymlJTXy?key=d3s-vJLBsYtwvRvGfZhdnw)**

Berbeda hal-nya dengan array yang hanya dapat menyimpan data dalam satu variabel dengan key yang sama, objek dapat menyimpan data pada satu variabel dengan key yang berbeda atau biasa disebut dengan properti (key-value pairs). Contohnya:

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXeILTZX4i9fw4jXU00lv1oVcW37X3d2jMT1iljmYX9SXVKkYpkYwXI8kbhcGsOTqk4VSsgpbynXzY3b97rQ2s9S3UE8MM5n-HnmEP4Bq4nFBKh9gpBZLt30gTAAAsyXa7mu-g9nWUgWESdlLm6CdJEIQUJ_FR3Q6t6yQOHbiQ?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
let person = {
    name: 'John',
    age: 30,
    isMarried: false
};
```


Dan untuk mengakses objek tersebut kita dapat memanggilnya menggunakan nama properti yang ada, misalnya:

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfCDeZbuEHklbKuzHIFga1ZLSq4LyWnfRxUoZP8Qy0aXi6c7M71Y4VOAi5H_F_FA8iV-dr-xz3bO_lSfvBybeXV3QVL1q3WVqCrEWD7uutfaVZOc3F0OiRSWROMjMXpd-esx6-VlVhSc5-bk0hc25KYwaiEsztNA-36gnOjnA?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
console.log(person.name);
console.log(person.age);
```

Hasil implementasi :

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcMgNUZZeMIqf6qOs09o6NVsfWhwDHB9xUtmeXSR4Tw8GkRlw6rz80yZf9qFUkrSgtCyppE0cVA4_Rq6bGbDt8LQ5WPPwsQ4BH3R-MikZ6lVItBOTHW_bgY4Ny7B7lkE5TuvwQlAmMj5NmtMJdtWwKfnLrg?key=d3s-vJLBsYtwvRvGfZhdnw)**
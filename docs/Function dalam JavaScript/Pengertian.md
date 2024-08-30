Fungsi adalah salah satu konsep fundamental dalam pemrograman JavaScript. Fungsi memungkinkan Anda untuk mengelompokkan sejumlah pernyataan menjadi satu unit yang dapat dipanggil dan dieksekusi berulang kali. Di bawah ini adalah materi dasar tentang fungsi dalam JavaScript:

- Deklarasi Fungsi

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeXFEVwBVhI06Nb9y6xVLp7djRKaJ36osVO00fVrXuJzFS-pJsVXndnmi4svEiOvJpuQMeF0V4VAxkr_-1pidqyAUbU5pwV9dZyUu0WFJTVkRMK1f2DGvgTsW5kc2WI0gvuG-KVwVK9_539aXZcQXCXlkoOukYFDdKo1mkymQ?key=ESYW2iUyREQEYzkaKMR1vg)**

```
function sapa() {
    console.log("Halo!");
}
```

- Memanggil Fungsi

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdhmV4gEoBmQxBxnLY8jbr_V4awxmwD1PIDVmqedlw51ilWk-7pX4TlnbHa0gpg0w9c-0e20LL1EdIXk4xUOc6w5xaVNCbbV04bW58xpNkfdavug7-yfLqbPRBOzMGgdJ-4ZjketVqWCIsVPxHTYxprtbudPEfo15G7Vps6?key=ESYW2iUyREQEYzkaKMR1vg)**

```
sapa();
```

- Parameter dan argumen

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXca7w7JUqsNzjtnxlitrzek6VJYwcoELDTUqhMYMJnFUriBzgyjyRRpSUTfGwV2oB1BdHckNzdo5HoIpNWPgYdzDoZanxaBN3pcHpoue9VatsdshKztouPkrubav7bxg0cZdzRN07DyusWD_GpuTUWzIwrh9NHFMO6WcWF-Qw?key=ESYW2iUyREQEYzkaKMR1vg)**

```
function sapa(nama) {
    console.log("Halo, " + nama + "!");
}

sapa("Andi");   
```

- Nilai return

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeuDzLWAgZU8sXLLrQzhdYmGYpr9TEF5c_Sr6LGwsUaXgmCD-o8XMxt3w4UoTY7qfmOG695SZI5iaq5L8i41PgzXgFWXp8AsoV_tUxCBRPfk4rLhuh2Lt3G_MmTH3VfF8y0GyUBdkrFpVcbghkgdiP0DAXtROQMpLb3WyuZKw?key=ESYW2iUyREQEYzkaKMR1vg)**

```
function tambah(a, b) {
    return a + b;
}

let hasil = tambah(3, 5);
consol.log(hasil);
```
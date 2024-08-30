
Manipulasi DOM (Document Object Model) adalah salah satu aspek penting dalam pengembangan web menggunakan JavaScript. Ini memungkinkan Anda mengakses, mengubah, dan mengatur elemen-elemen HTML dan tampilan halaman web secara dinamis. Berikut adalah materi dasar tentang manipulasi DOM dengan JavaScript:

1.  Mendapatkan Elemen
    
![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfxrG-r9udHB01P7u3Q4U_uytRuuJuoavIvQel3wl40PQCu3DRZpGq45MgLlbTQm37I4Vr3ORaguy_NTJUC-B1M1eRUkTGuHqr61kW4Z377y4zdjKJ6vq1_DIbtYQ_QzJMjXlZsbyEXGaNJ9TN7kjU0sCW3aEq7tvsRuo8f1A?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
const header = document.getElementById('header');
const button = document.querySelector('.btn');
```

2.  Mengubah Isi Elemen

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcx4O5wX9lS7aqiNpnNPbq926C0m9IROrUNIMKWMpsE4NU-1mbG6Fia25EFYiLAmdBiWxXlmtQbHxiCTyo6eXvvy20-eKdK7krh9XS7ZYwTBXCvPj9rmGesX8xJ1cJ63hlgAfB6hXBGo87xmCN_PKUgdYG4JM2VIu7wi40xXg?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
header.innerHTML = 'Halaman Utama';
button.textContent = 'Klik Saya';
```

3.  Menambahkan Class css

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcbfS7bAELkIAHqp64Latw1gS8HLaez2R_Y7BhSYCwr4Mdw8laGEPgp6zcc_r6PeJ5j27eEiO2Ky2ckdMIc8MKxpaao-NQpf_8VbbUizAwQa4_DXJ1Sh8zxS_ikCQJPzfZpW5QBPPlXQK14W7JBrdPj-Qnhu4HU4JKERNuNbw?key=ESYW2iUyREQEYzkaKMR1vg)


**Kode :**

```
button.classList.add('highlight);
```

4.  Menghapus Class css

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXemo8Fba7Y0OmJbgkI4M56cLT5l_DaeojGfX2EBeS5kzenm6pbkmTmVqjQIBZFGOqPvmXNNwt1bLieLyRiBNmhk-B4spFTyxU8rGIRY70DFaNHRYqlknZhCbFaJqkEUpx-eOBS_qCgGI0JqsfD1je_G-FIWQYOyVaVdagRgCA?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
button.classList.remove('btn')
```

5.  Menambah event listener

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcmBHvvgbgMRuqfDMh1_d6flJH2lOyPU6Q_rpJa1XlXLajCo1ldI86Y0Xu-jQyd0-Jl2NFuIra11TQ8CiJQEBdVLGMYeJTOCBRDEGYkF4stPlhZ6eImojnCwH9RB6J1u9ib1AgSUFoftIyyNcUkvCWFBKP6iUX2z6W-ElM10A?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
button.addEventListener('click, () => {
    alert('Tombol diklik!');
});
```
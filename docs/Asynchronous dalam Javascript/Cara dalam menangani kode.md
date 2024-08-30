---
sidebar_position: 2
---



Dalam asyncronous javascript banyak cara dalam menangani kode nya, seperti:

1.  Callback

Callback adalah salah satu cara asli untuk menangani kode asinkron dalam JavaScript. Namun, dalam suatu kondisi apabila dipergunakan secara berlebihan dapat menyebabkan "callback hell" atau kondisi dimana terlalu banyak callback yang bersarang satu sama lain, sehingga membentuk struktur piramida yang sulit dimengerti.  

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdJEvohb6ESadF-ra8C7b7OUgS26DHaFEIE2aRmdctaDpUft3avxqVaUGwUhbxkyFQYOkFQtaTLjywueLFE6udEqa7nms25rb92s9APg1uTRCHByePIxpN5Ptb3_h9TJqNQhNX_cats62m8T7gibS0VYDruHvJyxuLgioVjUg?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
function fetchData(callback) {
    setTimeout(() => {
      const data = 'Data telah diterima';
      callback(data);
    }, 2000);
  }
  
  function processData(data) {
    console.log('Data yang diterima:', data);
  }
  
  fetchData(processData);
```
Hasil implementasi : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeWTLslCexauFxhz326DRST7wzv6_9aFPe3vq8Ii56M6_TB6NWexTMudLk3MxVRXmBWZWGTdrL8MdM4hrw7JBEpGdoVszNDbp0HVL2m7PPpxmsAG7Bw2GCE2jwdAWMXrBziWcjD8XneiDrW30l1c0iiku8D?key=m5u8OORooedSn28Dv1j5-Q)**


2.  Promise
    
Promise adalah objek yang merepresentasikan nilai yang mungkin akan tersedia di masa depan pada proses async, baik nilai berhasil atau gagal.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfqr1fbDB4VQ2KZ8b6khY5LVCmU3uTVU29y-f4_Q6f3BRS54je67OJ-NMvu1kiY-CA0Wv55I9xEyRDEnqbfnAoKCbjro3eWXSgV-AdRDgENG4MGTuxwNlAFnoFDAsqglcyLNwbz8eHb497go83pjqDMatZmDdNX0H4q04cJnA?key=ESYW2iUyREQEYzkaKMR1vg)

**Kode :**

```
function fetchDataPromise() {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      const success = true;
      if (success) {
        resolve('Data berhasil diterima');
      } else {
        reject('Gagal mengambil data');
      }
    }, 2000);
  });
}

fetchDataPromise()
  .then(data => console.log('Data yang diterima:', data))
  .catch(error => console.error('Error:', error));
```
Hasil implementasi : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf945mUjva4636z3S7o9ReTQfPcN7hJOUENt4z8BeqlgXM86CiqNwpwhRdccafk6e-GwGGI68YCVj5JJIkZkp-BV5punJo4Cb971XHIu_FLFCLTAY1X5af2YjLPpkUCv8kWL7z-qlNR3Kwrv2HW8hIsNnSr?key=m5u8OORooedSn28Dv1j5-Q)**

3.  Async/Await
    
Cara kerja await mirip seperti promise tetapi diposisikan sebagai expression, saat menggunakan await program akan menghentikan sementara eksekusi fungsi async disekitarnya hingga janji diselesaikan seperti janji sudah dipenuhi atau ditolak.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXe_KJZfQfbEpsU0yTVqBjTI5YEDnR6jWYZz3pKq4FWHg2Pz87rqehSqxBSusCbKNYJhN2pY191--MGpVmUxactb4tgUbai30EWswPt6FBmLkk57KKDlfnAx-muiNuLfx7Q6nKOMb-Es02_d8O22pv6vq0lB3M5sZScL_X8X4g?key=ESYW2iUyREQEYzkaKMR1vg)



**Kode :**

```
async function getData() {
    try {
        const data = await fetchDataPromise();
        console.log('Data yang diterima:', data);
    }catch (error){
        console.error('Error:', error);
    }
}

getData();
```

Hasil implementasi : 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcwHjHaWTBDaG0JJINvZRZHJddn4NaJ1p9u9G4rlNJ_g7T6dz10db9jUxUBxeQHfoSSAwej0wXz17IgPfKKLBIniocc8Rs8d1t4p8x-ZEwBxsozOf9e2FZ8jMLgfLB3m2lAR0jcA2gIdtPIsdcNSbnA0Yq_?key=m5u8OORooedSn28Dv1j5-Q)**
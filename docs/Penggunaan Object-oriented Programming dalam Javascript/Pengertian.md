OOP atau Object-oriented Programming adalah sebuah metode pemrograman yang fokus atau berorientasi pada objek. Tujuannya dari OOP ini adalah membantu para developer dalam mengembangkan model yang sudah pernah dibuat sebelumnya untuk mempermudah developer secara efisien dalam penggunaan.

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXchnpPRvuN9d5GdCXUnVhkRo_yNQ-T4FLr_k9P67g9c2V7L29KuYA_e9J7myONudBmvrUJpj1c7Ql2yozcluxlyBco8q4FeKZCbnpAjAonD00RKxjH7bfKHG1JhjqtxmqTj6hyRKHs398gT-q1ZVZ7buxnjGF_RjO_4noQCgg?key=ESYW2iUyREQEYzkaKMR1vg)

**kode :**
```
class Animal {
    construtor(name) {
        this.name = name;
    }

    speak() {
        console.log(this.name + 'make a noise.');
    }
}

class Dog extends Animal {
    speak() {
        console.log(this.name + 'barks.');
    }
}

const dog = new Dog('Bobby.');
dog.speak();
```

Contoh penggunaan OOP dalam javascript seperti kode diatas, disini kita mempunyai 2 Class yaitu Animal sebagai Class Induk dan Dog sebagai Class Anak yang diambil dari Class Induk. Nanti nya kita dapat menggunakan banyak Class secara efisien tanpa membuat banyak Class yang sama nantinya.
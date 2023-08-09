# Day 13

Selamat datang di hari ketiga belas pembelajaran! Pada hari ini, kita akan fokus pada dua sesi pembelajaran yang penting. Ayo kita mulai!

### Sesi Pertama: Object Literals

Pada sesi pertama hari ini, kita akan mempelajari tentang Object Literals di JavaScript. Object adalah struktur data yang dapat digunakan untuk menyimpan dan mengatur data dalam bentuk pasangan "key" dan "value". Object sangat berguna untuk merepresentasikan entitas-entitas kompleks dalam kode.

Contoh penggunaan Object Literals meliputi merepresentasikan informasi tentang pengguna, produk, atau entitas lainnya dalam program.

Berikut adalah contoh penggunaan Object Literals di JavaScript:

```javascript
// Membuat object pengguna
const user = {
  username: "johndoe",
  fullName: "John Doe",
  age: 30,
  email: "john@example.com",
  isAdmin: false
};

// Mengakses nilai dalam object
console.log("Username:", user.username);
console.log("Email:", user.email);

// Menambahkan properti baru ke dalam object
user.location = "New York";

// Mengubah nilai properti dalam object
user.age = 31;

// Menghapus properti dari object
delete user.isAdmin;
```

Dalam contoh di atas, kita membuat sebuah object user yang memiliki beberapa properti seperti username, fullName, age, email, dan isAdmin. Kita juga bisa menambahkan, mengubah, atau menghapus properti dari object.

Referensi lain:

[Object Literal Basic 1](https://youtu.be/kXwDrcsONhA).

[Object Literal Basic 2](https://youtu.be/7d9H34ZVRPg).

### Sesi Kedua: Array of Object

Pada sesi kedua hari ini, kita akan mempelajari tentang Array of Object di JavaScript. Ini adalah penggabungan antara array dan object, di mana setiap elemen dalam array adalah sebuah object.

Contoh penggunaan Array of Object meliputi merepresentasikan daftar pengguna, produk, atau item lainnya yang memiliki beberapa properti.

Berikut adalah contoh penggunaan Array of Object di JavaScript:

```javascript
// Array of Object: Daftar produk
const products = [
  {
    id: 1,
    name: "Smartphone",
    price: 500,
    stock: 10
  },
  {
    id: 2,
    name: "Laptop",
    price: 1000,
    stock: 5
  },
  {
    id: 3,
    name: "Headphones",
    price: 50,
    stock: 20
  }
];

// Mengakses nilai properti dalam Array of Object
console.log("Nama Produk:", products[0].name);
console.log("Harga Laptop:", products[1].price);

// Menambahkan produk baru ke dalam Array of Object
const newProduct = {
  id: 4,
  name: "Tablet",
  price: 300,
  stock: 8
};
products.push(newProduct);
```

Dalam contoh di atas, kita memiliki Array of Object products yang berisi beberapa produk dengan properti seperti id, name, price, dan stock. Kita juga bisa menambahkan produk baru ke dalam array tersebut.

Referensi lain:

[Array of Object 1](https://youtu.be/D77ANP60DaU).

[Array of Object 2](https://youtu.be/dM6FzyMWRFo).

Jangan ragu untuk mencoba dan berlatih dengan membuat Object Literals, Array of Object, atau menggabungkan keduanya sesuai dengan kebutuhan Anda. Selamat belajar!


### CHALLENGE

* [Soal 1](/day13/soal1.md)
* [Soal 2](/day13/soal2.md)
* [Soal 3](/day13/soal3.md)
* [Soal 4](/day13/soal4.md)
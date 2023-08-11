## Day 15 - Test Day

Selamat datang di hari kelima belas pembelajaran! Pada hari ini, kita akan menguji pemahaman Anda dengan tiga soal dalam tipe soal Competitive Programming. Waktu yang disarankan untuk pengerjaan ketiga soal ini adalah 1 jam 30 menit. Soal-soal ini mencakup materi yang telah dipelajari dalam minggu ini. Ayo kita mulai!

### Soal 1: Object Manipulation

Anda diberikan sebuah objek berisi informasi tentang beberapa buah. Tugas Anda adalah membuat sebuah function yang akan mengambil objek tersebut dan mengembalikan daftar nama-nama buah yang memiliki harga di atas atau sama dengan suatu nilai yang diberikan.

Contoh objek buah:
```javascript
const fruits = [
  { name: "Apple", price: 0.5 },
  { name: "Banana", price: 0.25 },
  { name: "Orange", price: 0.7 },
  // ...
];
```

Function yang diharapkan:
```javascript
function getFruitsAbovePrice(fruits, minPrice) {
  // Implementasikan kode Anda di sini
}

const expensiveFruits = getFruitsAbovePrice(fruits, 0.5);
console.log(expensiveFruits); // Contoh output: ["Apple", "Orange"]
```

### Soal 2: Array of Object Manipulation

Anda diberikan sebuah array berisi informasi tentang beberapa pengguna. Tugas Anda adalah membuat sebuah function yang akan mengambil array tersebut dan mengembalikan daftar pengguna yang usianya di bawah atau sama dengan usia tertentu yang diberikan.

Contoh array pengguna:
```javascript
const users = [
  { name: "Alice", age: 25 },
  { name: "Bob", age: 30 },
  { name: "Charlie", age: 22 },
  // ...
];
```

Function yang diharapkan:
```javascript
function getUsersUnderAge(users, maxAge) {
  // Implementasikan kode Anda di sini
}

const youngUsers = getUsersUnderAge(users, 28);
console.log(youngUsers); // Contoh output: [{ name: "Alice", age: 25 }, { name: "Charlie", age: 22 }]
```

### Soal 3: Advanced Array Manipulation

Anda diberikan sebuah array berisi angka-angka. Tugas Anda adalah membuat sebuah function yang akan mengambil array tersebut dan mengembalikan array baru yang berisi angka-angka unik (tanpa duplikat) dan telah diurut dari terkecil hingga terbesar.

Contoh array angka:
```javascript
const numbers = [10, 5, 2, 10, 3, 5, 7, 2, 8];
```

Function yang diharapkan:
```javascript
function getSortedUniqueNumbers(numbers) {
  // Implementasikan kode Anda di sini
}

const sortedUniqueNumbers = getSortedUniqueNumbers(numbers);
console.log(sortedUniqueNumbers); // Contoh output: [2, 3, 5, 7, 8, 10]
```

Setelah menyelesaikan ketiga soal di atas atau dalam batas waktu yang telah ditentukan, Anda dapat membagikan hasilnya di server Discord Ant Collab untuk mendapatkan feedback atau bertanya jika ada hal yang belum dipahami.

Semoga Anda berhasil dalam menguji pemahaman Anda tentang materi yang telah dipelajari. Selamat mengerjakan dan tetap semangat dalam perjalanan belajar ngoding Anda!
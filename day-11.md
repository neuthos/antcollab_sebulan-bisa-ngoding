# Day 11

Selamat datang di hari kesebelas pembelajaran! Pada hari ini, kita akan fokus pada satu sesi pembelajaran tentang Modular Function di JavaScript. Ayo kita mulai!

## Sesi Pertama: Modular Function

Modular Function adalah pendekatan dalam pemrograman yang membagi program menjadi bagian-bagian yang lebih kecil dan terpisah yang disebut modul atau function. Dengan menggunakan Modular Function, kita dapat mengorganisasi kode dengan lebih baik, membuatnya lebih mudah dipelihara, dan memungkinkan penggunaan kembali kode dengan lebih efisien.

Contoh penggunaan Modular Function mencakup pemisahan fungsionalitas tertentu, seperti penghitungan matematika, manipulasi string, atau interaksi dengan API tertentu.

Berikut adalah contoh sederhana penggunaan Modular Function di JavaScript:

```js
// Modul untuk menghitung luas persegi
function calculateSquareArea(sideLength) {
  return sideLength * sideLength;
}

// Modul untuk menghitung luas lingkaran
function calculateCircleArea(radius) {
  return Math.PI * radius * radius;
}

// Modul untuk menghitung luas segitiga
function calculateTriangleArea(base, height) {
  return 0.5 * base * height;
}

// Penggunaan Modular Function
const squareArea = calculateSquareArea(5);
const circleArea = calculateCircleArea(3);
const triangleArea = calculateTriangleArea(4, 6);

console.log("Luas Persegi:", squareArea);
console.log("Luas Lingkaran:", circleArea);
console.log("Luas Segitiga:", triangleArea);

```

Dalam contoh di atas, kita memisahkan perhitungan luas persegi, lingkaran, dan segitiga ke dalam modul-modul terpisah. Kemudian, kita memanggil modul-modul tersebut saat dibutuhkan untuk menghitung luas dari bentuk-bentuk tersebut.

Penggunaan Modular Function akan semakin bermanfaat ketika program semakin kompleks dan memiliki banyak fitur yang berbeda. Modular Function memungkinkan kita untuk bekerja lebih terstruktur dan efisien dalam mengembangkan kode.

Anda dapat mempelajari lebih lanjut tentang function di JavaScript melalui:

* [Referensi](https://www.codecademy.com/courses/introduction-to-javascript/lessons/functions/exercises/intro-to-functions).


Jangan ragu untuk mencoba dan berlatih dengan membuat Modular Function sesuai dengan kebutuhan Anda. Selamat belajar!

### CHALLENGE

* [Soal 1](/day11/soal1.md)
* [Soal 2](/day11/soal2.md)
* [Soal 3](/day11/soal3.md)
* [Soal 4](/day11/soal4.md)
* [Soal 5](/day11/soal5.md)

# Logic Challenge - Mengelompokkan Angka

## Objectives
- Mampu memecahkan masalah yang diberikan
- Mampu membuat array multidimensi
- Mampu menggabungkan `looping` dan `conditional`

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop()

## Directions

Diberikan sebuah function mengelompokkanAngka yang menerima satu parameter berupa array yang berisi angka-angka.

Function akan me-return array multidimensi dimana array tersebut berisikan 3 kategori/kelompok:
  - kelompok pertama (baris pertama) merupakan angka-angka genap
  - kelompok ke-2 (baris ke-2) merupakan angka-angka ganjil
  - kelompok ke-3 (baris ke-3) merupakan angka-angka kelipatan 3

Dimana, satu angka hanya masuk ke dalam satu kelompok.  Lihat Test Cases untuk detail.

```JavaScript
function mengelompokkanAngka(arr) {
  // you can only write your code here!
}

// TEST CASES
console.log(mengelompokkanAngka([2, 4, 6])); // [ [2, 4], [], [6] ]
console.log(mengelompokkanAngka([1, 2, 3, 4, 5, 6, 7, 8, 9])); // [ [ 2, 4, 8 ], [ 1, 5, 7 ], [ 3, 6, 9 ] ]
console.log(mengelompokkanAngka([100, 151, 122, 99, 111])); // [ [ 100, 122 ], [ 151 ], [ 99, 111 ] ]
console.log(mengelompokkanAngka([])); // [ [], [], [] ]

```
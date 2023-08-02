# Logic Challenge - Target Terdekat

## Objectives
- Mampu memecahkan masalah yang diberikan
- Mampu mengakses sebuah array dalam sebuah looping kemudian mengecek nilai tersebut sesuai dengan masalah yang dihadapi

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop()

## Directions

Diberikan sebuah function targetTerdekat yang menerima satu parameter berupa array yang terdiri dari karakter.


Function akan me-return jarak spasi antar karakter 'o' dengan karakter 'x' yang terdekat.

***ASUMSI***

***Karakter 'o' pasti akan selalu ada dan hanya akan ada 1***

### Contoh 1:

jika arr adalah ['x', ' ', 'o', ' ', ' ', 'x'], maka jarak terdekat dari 'o' ke 'x' adalah 2. Jika tidak ditemukan 'x' sama sekali, function akan me-return nilai 0.

```JavaScript
function targetTerdekat(arr) {
  // you can only write your code here!
}

// TEST CASES
console.log(targetTerdekat([' ', ' ', 'o', ' ', ' ', 'x', ' ', 'x'])); // 3
console.log(targetTerdekat(['o', ' ', ' ', ' ', 'x', 'x', 'x'])); // 4
console.log(targetTerdekat(['x', ' ', ' ', ' ', 'x', 'x', 'o', ' '])); // 1
console.log(targetTerdekat([' ', ' ', 'o', ' '])); // 0
console.log(targetTerdekat([' ', 'o', ' ', 'x', 'x', ' ', ' ', 'x'])); // 2
```
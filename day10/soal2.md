# Logic Challenge - Interesting Ladder Array Multidimensi

## Objectives
- Mampu memecahkan sebuah masalah dengan `nested loop`
- Mengerti logika `nested loop`
- Dapat melihat pola dari posisi baris dan kolom sebuah pola yang diberikan
- Mampu membuat array multidimensi dari sebuah string yang diberikan

**RESTRICTION**
Hanya boleh menggunakan built-in function .push()

## Directions
Diberikan sebuah function `ladder` berisi satu parameter bertipe string

Buatlah program yang menghasilkan gambar yang menyerupai tangga dengan pola sebagai berikut:
  - kata yang paling atas adalah kata itu sendiri dengan catatan masing-masing huruf berada di indeks berbeda di satu array
  - setiap turun, huruf akan berkurang 1 dari belakang (dari value kata awal)


```
function ladder(word) {
  //your code here
}

// DRIVER CODE
console.log(ladder('hacktiv8'));
[
  [ 'h', 'a', 'c', 'k', 't', 'i', 'v', '8' ],
  [ 'h', 'a', 'c', 'k', 't', 'i', 'v' ],
  [ 'h', 'a', 'c', 'k', 't', 'i' ],
  [ 'h', 'a', 'c', 'k', 't' ],
  [ 'h', 'a', 'c', 'k' ],
  [ 'h', 'a', 'c' ],
  [ 'h', 'a' ],
  [ 'h' ]
]

```
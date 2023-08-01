# Vocal Seeker

## Objectives
- Mampu mengakses array multidimensi
- Mampu membedakan type data number dan yang bukan
- Mampu menggunakan template literals

**RESTRICTION**
Tidak boleh menggunakan built-in function apapun dan regex

## Directions

Diberikan sebuah function bernama seeker dimana function tersebut menerima satu paremeter array multidimensi.

Function akan mengembalikan jumlah vokal dan kumpulan vokal yang ditemukan dari array multidimensi tersebut


```JavaScript
function vocalSeeker(board) {
  // Write your code here
}

//DRIVER CODE

let board = [
  ['*', '*', '*', 10],
  ['*', '*', -5, -10, '*', 100],
  ['a', 'A', 'o', 'b']
]

console.log(vocalSeeker(board)); // vokal ditemukan 3 dan kumpulan vokal adalah aAo

```
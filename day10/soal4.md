# Sitting Arrangement

## Objectives
- Mampu membuat array multidimensi
- Mampu mengakses array 1 dimensi
- Mampu menggunakan while condition dan nested loop

**RESTRICTION**
Hanya boleh menggunakan built-in function .push()

## Directions

Diberikan sebuah function bernama sittingArrangement dimana function tersebut menerima dua paramter.
- Parameter pertama bernama `person` bertipe array
- Parameter kedua bernama `column` bertipe number

 Function akan mengembalikan array multidimensi yang mengatur tempat duduk berdasarkan jumlah column.
 Dimana jika orang tidak cukup untuk mengisi column tersebut maka diisi dengan value 'Kursi Kosong'

 ***ASUMSI:***
 - variabel `column` harus minimal bernilai 1, jika kurang dari itu maka tuliskan 'Invalid number'

```JavaScript
function sittingArrangement(person, column) {
  // Write your code here
}

//DRIVER CODE

console.log(sittingArrangement(['A', 'B', 'C'], 0 )); //Invalid number
console.log(sittingArrangement([ 'Juli', 'Nisa', 'Desi', 'Ulfa', 'Puji' ], 2)); //[ [ 'Juli', 'Nisa' ], [ 'Desi', 'Ulfa' ], [ 'Puji', 'Kursi Kosong' ] ]
console.log(sittingArrangement([ 'Yosia', 'Asrawi', 'Andru' ], 3)); //[ [ 'Yosia', 'Asrawi', 'Andru' ] ]
console.log(sittingArrangement([ 'Lukman', 'Adam', 'Dimas', 'Hansin', 'Orion' ], 4));
// [
//   [ 'Lukman', 'Adam', 'Dimas', 'Hansin' ],
//   [ 'Orion', 'Kursi Kosong', 'Kursi Kosong', 'Kursi Kosong' ]
// ]

```
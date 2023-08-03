# Logic Challenge: Melee Ranged Grouping

## Objectives
- Mengerti keterhubungan satu function dengan function lainnya
- Mengerti melempar/memasukkan data hasil satu function kemudian digunakan untuk parameter function lain
- Mampu membuat function serupa built in function split

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop()

## Directions


Diberikan 2 function:

- meleeRangedGrouping yang menerima 1 parameter berupa string.  Implementasikan meleeRangedGrouping agar dapat menghasilkan multidimensional array seperti yang diminta.

  Format string yang diberikan adalah:
`<nama_hero>-<tipe_hero>,<nama_hero>-<tipe-hero>, ...`

  Output yang diharapkan:
`[ [ <daftar_hero_dengan_tipe_ranged> ], [ <daftar_hero_dengan_tipe_melee> ] ]`

  Jika input adalah string kosong ('') maka return array kosong

- Untuk memisahkan nama hero dan tipenya, implementasikan function splitting yang telah diberikan dimana hasil dari function tersebut adalah array satu dimensi

  Output yang diharapkan:
  `['Razor', 'Ranged']`


```JavaScript
function splitting(str) {
  //your code here
}

function meleeRangedGrouping (str) {
  //your code here
}

// TEST CASE

console.log(meleeRangedGrouping('Razor-Ranged,Invoker-Ranged,Meepo-Melee,Axe-Melee,Sniper-Ranged'));
// [ ['Razor', 'Invoker', 'Sniper'], ['Meepo', 'Axe'] ]

console.log(meleeRangedGrouping('Drow Ranger-Ranged,Chen-Ranged,Dazzle-Ranged,Io-Ranged'));
// [ ['Drow Ranger', 'Chen', 'Dazzle', 'Io'], [] ]

console.log(meleeRangedGrouping('')); // []
```
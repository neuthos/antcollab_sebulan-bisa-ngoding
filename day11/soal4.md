# Logic Challenge - Tabel Perkalian

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop() dan built-in untuk mengkonversi tipe data


## Directions

Diberikan sebuah function tabelPerkalianyang menerima satu parameter angka.

Function akan mengembalikan array berisi string berupa faktor perkalian dari angka yang diberikan.


```JavaScript
function tabelPerkalian(angka) {
  // you can only write your code here!
}

// TEST CASES
console.log(tabelPerkalian(24)); // [ '1x24', '2x12', '3x8', '4x6' ]
console.log(tabelPerkalian(90)); // [ '1x90', '2x45', '3x30', '5x18', '6x15', '9x10' ]
console.log(tabelPerkalian(20)); // [ '1x20', '2x10', '4x5']
console.log(tabelPerkalian(179)); // [ '1x179' ]
console.log(tabelPerkalian(1)); // [ '1x1' ]
```
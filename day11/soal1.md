# Logic Challenge - Deret Geometri

## Objectives
- Melatih kembali pengetahuan kamu dalam mengakses sebuah array
- Mampu menggabungkan `looping` dan `conditional`
- Mampu membandingkan nilai array satu dengan nilai array disebelah kanannya dengan menggunakan index

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop()  

## Directions

Diberikan sebuah function tentukanDeretGeometriyang menerima satu parameter berupa array yang terdiri dari angka. 

Function tersebut akan mengembalikan true jika array dari parameter tersebut merupakan deret geometri.

Deret geometri adalah sebuah deret dimana perbedaan setiap angka di deret tersebut konsisten secara perkalian.

### Contoh 1:

[1, 3, 9, 27, 81] adalah deret aritmatika dengan pertambahan nilai sebesar pengalian 3

### Contoh 2:

[1, 3, 9, 27, 48] bukanlah deret aritmatika karena tidak perbedaan selisih antar angka yang tidak konsisten secara perkalian (27 * 3 bukanlah 48!).

```JavaScript
function tentukanDeretGeometri(arr) {
  // you can only write your code here!
}

// TEST CASES
console.log(tentukanDeretGeometri([1, 3, 9, 27, 81])); // true
console.log(tentukanDeretGeometri([2, 4, 8, 16, 32])); // true
console.log(tentukanDeretGeometri([2, 4, 6, 8])); // false
console.log(tentukanDeretGeometri([2, 6, 18, 54])); // true
console.log(tentukanDeretGeometri([1, 2, 3, 4, 7, 9])); // false
```
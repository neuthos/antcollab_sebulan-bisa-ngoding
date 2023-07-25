# Data Type Challenge

Diberikan sebuah variabel `nilai` bertipe data apapun (string, number, boolean, null, undefined, atau lainnya). Buatlah program untuk mengecek tipe data dari nilai tersebut dan memberikan output berikut:

- Jika nilai adalah sebuah string, tampilkan 'Nilai berupa string: ' + nilai (gunakan template literals).
- Jika nilai adalah sebuah number, tampilkan 'Nilai berupa number: ' + nilai (gunakan template literals).
- Jika nilai adalah sebuah boolean, cek nilainya:
  - Jika true, tampilkan 'Nilai berupa boolean dan bernilai true'.
  - Jika false, tampilkan 'Nilai berupa boolean dan bernilai false'.
- Jika nilai adalah null, tampilkan 'Nilai adalah null'.
- Jika nilai adalah undefined, tampilkan 'Nilai adalah undefined'.
- Jika nilai adalah NaN (Not-a-Number), tampilkan 'Nilai adalah NaN'.
- Jika nilai adalah angka 0, tampilkan 'Nilai adalah angka 0'.
- Jika nilai adalah empty string (string kosong), tampilkan 'Nilai adalah empty string'.

Contoh:

```JavaScript
Contoh 1:
let nilai = 'Hello World';
Output: 'Nilai berupa string: Hello World'

Contoh 2:
let nilai = 42;
Output: 'Nilai berupa number: 42'

Contoh 3:
let nilai = true;
Output: 'Nilai berupa boolean dan bernilai true'

Contoh 4:
let nilai = null;
Output: 'Nilai adalah null'

Contoh 5:
let nilai;
Output: 'Nilai adalah undefined'

Contoh 6:
let nilai = NaN;
Output: 'Nilai adalah NaN'

Contoh 7:
let nilai = 0;
Output: 'Nilai adalah angka 0'

Contoh 8:
let nilai = '';
Output: 'Nilai adalah empty string'
```

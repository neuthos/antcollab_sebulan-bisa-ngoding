# Logic Challenge - Palindrome Angka

## Objectives

- Mampu memecahkan masalah yang diberikan
- Mampu menggabungkan konsep `looping/iteration` dan `conditional` didalam sebuah masalah
- Mampu mengubah/convert tipe data string ke number ataupun sebaliknya
- Mampu membedakan penggunaan while dan for
- Mampu memberhentikan sebuah loop menggunakan `break`

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk mengkonversi tipe data, seperti toString(), Number(), dll

## Directions

Diberikan sebuah variabel `angka` bertipe number.

Buatlah program yang menampilkan angka palindrome selanjutnya dari `angka` yang diberikan.

Contoh jika `angka` bernilai 27 maka outputnya adalah 33 karena angka 33 merupakan angka palindrome.

**penjelasan:**

setelah angka 27, adalah:

- **28** bukan angka palindrome. karena belum mendapatkan angka palindrome maka ditambahkan lagi
- **29** bukan angka palindrome. karena belum mendapatkan angka palindrome maka ditambahkan lagi
- **30** bukan angka palindrome. karena belum mendapatkan angka palindrome maka ditambahkan lagi
- **31** bukan angka palindrome. karena belum mendapatkan angka palindrome maka ditambahkan lagi
- **32** bukan angka palindrome. karena belum mendapatkan angka palindrome maka ditambahkan lagi
- **33** angka palindrome. Karena angka palindrome telah ditemukan maka loop harus berhenti dan menampilkan angka 33

```JavaScript
Contoh 1:
let angka = 10

maka output yang dihasilkan adalah 11

Contoh 2:
let angka = 175

maka output yang dihasilkan adalah 181
```

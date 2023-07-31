## Function/Method

Function adalah sebuah blok kode yang disusun sedemikian rupa untuk menjalankan sebuah tindakan.
Blok kode ini dibuat untuk dapat bisa digunakan kembali. Cara atau bentuk penulisan function adalah
sebagai berikut:

```javascript
function nama_function(parameter 1, parameter 2, ...) {
  [Isi dari function berupa tindakan]
  return [expression];
}
```

Kode di atas tidak dapat kita copy-paste kan langsung, melainkan hanya sebuah bentuk penulisan `function`.
Sebuah `function`, umumnya melakukan tindakan dan sebelum `function` berakhir, `function` bisa
mengembalikan nilai dengan cara menambahkan sintaks return.

Kita juga dapat mengirimkan nilai ke dalam sebuah `function` dengan mencantumkannya ke dalam tanda kurung
dalam penulisan `function`. Untuk mengirimkan nilai lebih dari satu, gunakan tanda `,` sebagai pemisah.

**Contoh Function 1:** Function sederhana tanpa return

```javascript
function tampilkan() {
  console.log("halo!");
}

tampilkan();
```

**Contoh Function 2:** Function sederhana dengan return

```javascript
function munculkanAngkaDua() {
  return 2
}

var tampung = munculkanAngkaDua();
console.log(tampung)
```

**Contoh Function 3:** Function dengan parameter

```javascript
function kalikanDua(angka) {
  return angka * 2
}

var tampung = kalikanDua(2);
console.log(tampung)

```

**Contoh Function 4:** Pengiriman parameter lebih dari satu

```javascript
function tampilkanAngka(angkaPertama, angkaKedua) {
  return angkaPertama + angkaKedua
}

console.log(tampilkanAngka(5,3))
```

**Contoh Function 5:** Inisialisasi parameter dengan nilai default

```javascript
function tampilkanAngka(angka = 1) {
  return angka
}

console.log(tampilkanAngka(5)) // 5, sesuai dengan nilai parameter yang dikirim
console.log(tampilkanAngka()) // 1, karena default dari parameter adalah 1
```

⚠️ Waspadai pengiriman parameter yang UNDEFINED!

Kita juga dapat menampung function sebagai variable dengan sebuah bentuk function
yang dinamakan Anonymous Function.

```javascript
var fungsiPerkalian = function(angkaPertama, angkaKedua) {
  return angkaPertama * angkaKedua
}

console.log(fungsiPerkalian(2,4))
```

## Soal Latihan String: Penggabungan dan Pemecahan Kata

### RESTRICTION

* DILARANG MENGGUNAKAN BUILT IN FUNCTION DARI JAVASCRIPT
* Hanya boleh menggunakan built-in function Math seperti Math.random, Math.ceil, Math.round, Math.floor, dll

#### Deskripsi

Pada tugas ini, kamu diminta untuk menggabungkan beberapa kata menjadi sebuah kalimat. Disediakan variabel `kataPertama`, `kataKedua`, `kataKetiga`, `kataKeempat`, dan `kataKelima`. Gabungkan nilai-nilai variabel tersebut dengan menambahkan spasi di antara kata-kata, lalu tampilkan hasilnya di console.

```javascript
var kataPertama = 'Saya';
var kataKedua = 'adalah';
var kataKetiga = 'seorang';
var kataKeempat = 'programmer';
var kataKelima = 'handal';

// Gabungkan kata-kata menjadi kalimat
// Output: Saya adalah seorang programmer handal

```

### 2. Pemecahan Kata - Karakter per Karakter

#### Deskripsi

Pada tugas ini, kamu diminta untuk "memecah" sebuah kalimat dan menampilkan setiap kata secara per karakter. Gunakan akses satu per satu karakter dari string untuk mengambil setiap huruf dalam kata. Tampilkan hasilnya di console.

```javascript
var kalimat = 'Hari ini adalah hari yang cerah';

// Pemecahan kata menjadi karakter per karakter
// Output:
// H
// a
// r
// i
// ...
// c
// e
// r
// a
// h

```

### 3. Pemecahan Kata Menggunakan Substring

#### Deskripsi

Pada tugas ini, kamu diminta untuk "memecah" sebuah kalimat menggunakan metode `substring`. Ambil potongan dari tiap kata, kemudian tampilkan hasilnya di console.

#### Contoh

```javascript
var kalimat = 'Hari ini adalah hari yang cerah';

// Pemecahan kata menggunakan substring
// Output:
// Hari
// ini
// adalah
// hari
// yang
// cerah

```

### 4. Pemecahan Kata dan Perhitungan Panjangnya

#### Deskripsi

Pada tugas ini, kamu diminta untuk "memecah" sebuah kalimat menggunakan metode `substring`. Tampilkan juga panjang kata masing-masingnya di samping kata tersebut di console.

```javascript
var kalimat = 'Hari ini adalah hari yang cerah';

// Pemecahan kata menggunakan substring dan perhitungan panjang kata
// Output:
// Hari (panjang: 4)
// ini (panjang: 3)
// adalah (panjang: 6)
// hari (panjang: 4)
// yang (panjang: 4)
// cerah (panjang: 5)

```

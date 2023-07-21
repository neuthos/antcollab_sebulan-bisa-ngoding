# Pencarian Buku

## Tujuan

* Mengerti cara menggunakan `If-Else`
* Mengerti logika `If-Else`
* Mengerti cara menggunakan operator evaluasi `===`, `!==`

## Petunjuk

Seorang pengunjung perpustakaan direpresentasikan dalam JavaScript dengan memiliki variable `nama`, `usia`, dan `jumlahUang`. Pengunjung tersebut datang ke perpustakaan untuk mencari buku yang dia inginkan, namun perpustakaan memiliki kondisi sebagai berikut:

1. Jika `nama` dari pengunjung kosong, tampilkan di console "Anda tidak dapat mencari buku. Silakan isi nama anda terlebih dahulu." dan program selesai.
2. Jika `usia` dari pengunjung kurang dari 10 tahun, maka dia hanya boleh mencari buku cerita anak-anak. Jika usia 10 tahun ke atas, dia boleh mencari buku apapun.
3. Jika `jumlahUang` yang dimiliki kurang dari 100000, maka tampilkan di console "Maaf, uang anda tidak mencukupi untuk mencari buku. Anda harus pulang.". Jika uang cukup, tampilkan "Anda dapat mencari buku. Sisa uang anda: [...]", dan ganti [...] dengan sisa uang yang telah dikurangi oleh harga buku yang ingin dicari.

Buatlah pseudocode dan programnya!

 **RESTRICTION** :
Tidak boleh menggunakan built-in function apapun.

### Contoh Input/Output

Input:

```
var nama = 'Galang';
var usia = 25;
var jumlahUang = 150000;

```

Output:

```
Anda dapat mencari buku. Sisa uang anda: 50000

```

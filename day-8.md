# Day 8 - Test Day

Selamat datang di hari kedelapan pembelajaran! Pada hari ini, kita akan melakukan ujian dengan dua soal yang menarik. Ayo kita mulai!

## SOAL 1

Anda diberikan sebuah array bilangan bulat `nums`. Awalnya, Anda berada di indeks pertama array, dan setiap elemen dalam array mewakili panjang loncatan maksimum Anda pada posisi tersebut.

Kembalikan nilai true jika Anda dapat mencapai indeks terakhir array, atau false jika tidak.

Contoh 1:

```
Input: nums = [2,3,1,1,4]
Output: true
Penjelasan: Loncat 1 langkah dari indeks 0 ke 1, lalu loncat 3 langkah ke indeks terakhir.
```

Contoh 2:

```
Input: nums = [3,2,1,0,4]
Output: false
Penjelasan: Anda akan selalu sampai di indeks 3, apa pun yang terjadi. Panjang loncatan maksimumnya adalah 0, yang membuatnya tidak mungkin mencapai indeks terakhir.
```

## SOAL 2

Diberikan sebuah variabel kata bertipe sting.

Buatlah program yang menghasilkan gambar yang menyerupai tangga dengan pola sebagai berikut:

- dasar yang paling bawah adalah kata itu sendiri
- setiap naik, huruf akan berkurang 1 dari depan (dari value kata awal) kemudian kata tersebut dibalik

```
Contoh 1:
let kata = 'antcollab'

//output yang diharapkan

        b
       ab
      lab
     llab
    ollab
   collab
  tcollab
 ntcollab
antcollab

```

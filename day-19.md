# Day 19 - Memahami DOM (Document Object Model)

Selamat datang di hari kesembilan belas pembelajaran! Pada hari ini, kita akan memahami konsep dasar DOM (Document Object Model) dalam pengembangan web. DOM adalah representasi struktural dari dokumen HTML yang memungkinkan kita untuk berinteraksi dengan konten HTML dan mengubahnya menggunakan JavaScript.

## Apa Itu DOM?

DOM adalah cara browser merepresentasikan halaman web sebagai objek yang dapat diakses dan dimanipulasi. Setiap elemen HTML, seperti tag `<p>`, `<div>`, atau `<button>`, adalah node dalam pohon DOM.

Mari lihat contoh sederhana. Jika kita memiliki HTML sebagai berikut:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Contoh DOM</title>
</head>
<body>
    <h1>Halo, Dunia!</h1>
    <p>Selamat datang ke program "Sebulan Bisa Ngoding".</p>
</body>
</html>
```

Maka pohon DOM-nya akan terlihat seperti ini:

```
- Document
  - html
    - head
      - title
        - "Contoh DOM"
    - body
      - h1
        - "Halo, Dunia!"
      - p
        - "Selamat datang ke program "Sebulan Bisa Ngoding"."
```

## Mengakses dan Mengubah DOM

Dengan JavaScript, kita dapat mengakses dan mengubah elemen-elemen dalam DOM. Berikut ini adalah beberapa contoh dasar:

### Mengakses Elemen

```javascript
// Mengakses elemen dengan ID "judul"
const judul = document.getElementById("judul");

// Mengakses elemen-elemen dengan tag "p"
const paragraf = document.getElementsByTagName("p");

// Mengakses elemen dengan class "info"
const info = document.getElementsByClassName("info");
```

### Mengubah Konten Elemen

```javascript
// Mengubah teks dalam elemen
judul.textContent = "Selamat Belajar DOM";

// Mengubah nilai atribut
gambar.src = "gambar-baru.jpg";
```

### Menambah dan Menghapus Elemen

```javascript
// Membuat elemen baru
const baru = document.createElement("p");

// Menambahkan elemen baru ke dalam DOM
document.body.appendChild(baru);

// Menghapus elemen
const paragraf = document.getElementsByTagName("p")[0];
document.body.removeChild(paragraf);
```

Ini adalah konsep dasar DOM yang akan membantu Anda berinteraksi dengan halaman web secara dinamis. Pada hari-hari berikutnya, kita akan menjelajahi lebih dalam tentang manipulasi DOM dan bagaimana kita dapat membuat halaman web yang lebih interaktif.

Anda dapat mempelajari lebih lanjut tentang DOM JavaScript melalui:

* [Referensi Untuk Belajar DOM](https://www.w3schools.com/js/js_functions.asp).

Selamat belajar dan tetap semangat!
---

Terima kasih telah melanjutkan perjalanan pembelajaran bersama program "Sebulan Bisa Ngoding" dari Ant Collab. DOM adalah salah satu aspek penting dalam pengembangan web, dan dengan pemahaman yang baik, Anda akan mampu membuat aplikasi web yang lebih canggih dan dinamis.

# Logic Challenge - Change Me!

## Objectives
- Mampu mengakases array multidimensi menggunakan nested loop
- Mampu membuat object literal sesuai dengan data (key dan value) yang diinginkan

**RESTRICTION**
Hanya boleh menggunakan built-in function untuk menambahkan atau mengurangi data dalam array, seperti .shift(), unShift(), push(), dan pop()

## Directions

Diberikan sebuah function changeMe yang menerima satu parameter berupa array multidimensi dimana array tersebut berisi value (pasti berurut dari kiri ke kanan) First Name, Last Name, Gender dan Birth Year .

Fungsi ini akan menampilkan object literal yang memiliki property firstName, lastName, gender dan age.

Nilai age didapatkan dari tahun sekarang dikurang tahun lahir. Jika tahun lahir tidak diisi atau tahun lahir lebih besar dibandingkan tahun sekarang maka age akan berisi 'Invalid Birth Year'

Contoh jika arr inputan adalah [['Platinum', 'Fox', 'female', 1995], ['John', 'Doe', 'male', 2000]] dan tahun sekarang = 2019, maka output:
1. Platinum Fox:
{ firstName: 'Platinum',
  lastName: 'Fox',
  gender: 'female',
  age: 24 }
2. John Doe:
{ firstName: 'John', lastName: 'Doe', gender: 'male', age: 19 }

## Code

```JavaScript
function changeMe(arr) {
  // you can only write your code here!
}

// TEST CASES
changeMe([['Christ', 'Evans', 'Male', 1982], ['Robert', 'Downey', 'Male']]); 
// 1. Christ Evans:
// { firstName: 'Christ',
//   lastName: 'Evans',
//   gender: 'Male',
//   age: 38 }
// 2. Robert Downey:
// { firstName: 'Robert',
//   lastName: 'Downey',
//   gender: 'Male',
//   age: 'Invalid Birth Year' }
changeMe([]); // ""
```
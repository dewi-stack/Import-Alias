# Import Alias
## 1. Apa yang dimaksud dengan Import Alias?
Import alias di ES6 adalah cara untuk memberikan alias pada modul atau ekspor yang diimpor dari file JavaScript lain. Dalam JavaScript ES6, import digunakan untuk mengimpor modul dan ekspor dari file lain ke dalam file saat ini. Misalkan kita ingin mengimpor fungsi tertentu dari file myModule.js dan memberikannya alias pada saat impor, kita dapat menggunakan sintaks import yang diikuti dengan kata kunci as dan nama alias yang diinginkan.

## 2. Kapan kita bisa menggunakan Import Alias pada ES6?
Kita dapat menggunakan import alias pada ES6 JavaScript ketika kita ingin mengimpor fungsi atau kelas dari file lain dan memberikan nama yang berbeda pada saat impor. Pemberian alias pada saat impor sangat berguna ketika kita ingin menghindari konflik nama atau mempermudah perubahan nama di masa depan.

Berikut adalah beberapa situasi di mana kita bisa menggunakan import alias pada ES6:

1. Ketika kita ingin mengimpor banyak fungsi atau kelas dari berbagai file, dan ingin memberikan nama yang lebih deskriptif untuk setiap fungsi atau kelas yang diimpor.

2. Ketika kita ingin menghindari konflik nama antara fungsi atau kelas yang diimpor dengan fungsi atau kelas lain yang ada di file saat ini.

3. Ketika kita ingin membuat kode lebih mudah dibaca dan dipahami dengan memberikan nama alias yang deskriptif.

4. Ketika kita ingin mempermudah perubahan nama fungsi atau kelas di masa depan tanpa harus memperbarui semua tempat di kode yang menggunakannya.

5. Dalam kesimpulannya, kita dapat menggunakan import alias pada ES6 ketika kita ingin memberikan nama yang berbeda pada saat mengimpor fungsi atau kelas dari file lain. Ini sangat berguna dalam menghindari konflik nama, membuat kode lebih mudah dibaca dan dipahami, dan mempermudah perubahan nama di masa depan.


## 3. Mengapa perlu menggunakan Import Alias pada ES6?
Pemberian import alias pada ES6 JavaScript dapat sangat berguna dalam mengelola kode yang kompleks dan besar. Berikut adalah beberapa alasan mengapa perlu menggunakan import alias pada ES6:

1. Menghindari konflik nama: Ketika kita mengimpor banyak fungsi atau kelas dari berbagai file, kita dapat mengalami konflik nama. Dengan memberikan alias pada saat impor, kita dapat memberikan nama yang berbeda untuk setiap fungsi atau kelas yang diimpor, sehingga menghindari konflik nama.

2. Mempermudah perubahan nama: Jika kita ingin mengubah nama fungsi atau kelas yang diimpor, kita hanya perlu mengubah nama alias pada saat impor. Ini akan mempermudah perubahan nama fungsi atau kelas tanpa harus memperbarui semua tempat di kode yang menggunakannya.

3. Mempermudah pembacaan kode: Dengan memberikan alias yang deskriptif, kita dapat membuat kode lebih mudah dipahami dan lebih mudah dibaca oleh orang lain.

4. Meningkatkan keterbacaan kode: Dengan memberikan alias pada saat impor, kita dapat membuat kode yang lebih mudah dibaca dan dipahami karena nama alias dapat memberikan informasi tambahan tentang fungsi atau kelas yang diimpor.

5. Dalam kesimpulannya, menggunakan import alias pada ES6 JavaScript dapat membantu kita mengelola kode yang kompleks dan besar dengan lebih mudah dan efisien. Hal ini membantu dalam menghindari konflik nama, mempermudah perubahan nama, meningkatkan keterbacaan kode, dan membuat kode lebih mudah dipahami.


## 4. Bagaimana contoh penggunaan Import Alias pada ES6?

Berikut adalah contoh sintaks import dengan alias di ES6:
<img src="contoh1.png">

Untuk melakukan import dengan menggunakan alias di ES6 JavaScript, Anda dapat menggunakan kata kunci as seperti contoh berikut:

Misalkan kita memiliki dua file JavaScript yang berbeda, myModule.js dan myOtherModule.js, dan ingin mengimpor fungsi tertentu dari masing-masing file dan memberikan alias pada saat impor. Berikut adalah contoh sintaks yang dapat digunakan:
<img src="contoh2.png">

Pada contoh di atas, kita mengimpor fungsi myFunction dari file myModule.js, dan memberikannya alias alias1. Kami juga mengimpor fungsi myOtherFunction dari file myOtherModule.js dan memberikannya alias alias2.

Setelah diimpor, kita bisa memanggil fungsi myFunction dan alias2 pada kode selanjutnya menggunakan alias yang telah diberikan:
<img src="contoh3.png">

Dengan memberikan alias pada saat impor, kita dapat menghindari konflik nama antara fungsi yang diimpor dengan fungsi lain yang ada di file saat ini. Hal ini juga memudahkan untuk mengubah nama fungsi yang diimpor tanpa harus merubah nama fungsi tersebut di seluruh kode yang menggunakan fungsi tersebut.





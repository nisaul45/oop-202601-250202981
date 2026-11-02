# Catatan Minggu 03: Inheritance

## Yang saya kerjakan
Pada minggu ini saya melengkapi atau menambahkan pada tiga class yaitu Ruang, Laptop, dan AlatLab yang merupakan turunan dari class Aset. Saya menambahkan field, kontruktor, getter, dan juga method getJenis() pada masing masing class. Saya juga membuat validasi agar data yang dimasukan sesuai dengan aturan.

## Keputusan desain
Pada masing masing class saya menggunakan atribut khusus yaitu Ruang memiliki kapasitas, Laptop memiliki spesifkasi dan nomor inventaris sedangkan pada AlatLab memiliki nama laboratorium dan tingkat resiko. Pembagian ini dilakukan agar setiap class memiliki atribut yang sesuai dan menghinndari pengulangan atribut yang sama.

## Kendala
Saya mengalami kendala pada beberapa kesalahan penulisan kode dan juga mengalami beberapa kali error saat tes.

## Penggunaan AI
- Alat yang dipakai: Claude 
- Bagian yang dibantu AI: Pemeriksaan pada kode Ruang.java, Laptop.java, dan AlatLab.Java.
- Prompt utama: Jelaskan cara menerapkan inheritance class Ruang, Laptop, dan AlatLab dan Bantu periksa apakah kode suudah sesuai dengan aturan validasi yang diberikan, Cara menentukan field yang seharusnya berada di induk dan subclass.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada.
- Satu hal yang saya pahami lebih baik sekarang: Inheritance memungkinkan class anak (subclass) mewarisi atribut dan method dari class induk (superclass) sehingga lebih mudah digunakan kembali.

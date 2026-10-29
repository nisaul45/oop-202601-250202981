# Catatan Minggu 02: Class, Object, Encapsulation

## Yang saya kerjakan
Saya melengkapi class Aset pada package id.ac.asetpinjam.model dengan field, kontruktor, getter/setter, dan validasi. Saya menggunakan private final pada field kode dan juga menambahkan validasi agar kode dan nama tidak boleh null atau kosong.

## Keputusan desain
Pada keputsan desain menggunakan private final string kode. Kode aset dinormalisai menggunakan trim() agar menghapus spasi awal dan juga akhir serta huruf besar dan kecil tidak diubah agar tetap sesuai dengan data yang asli. Kode dan nama tidak boleh bernilai null atau kosong. Status awal tersedia dan kondisi awal baik.

## Kendala
Terjadi kekeliruan pada kode khusunya pada perbedaan antara validasi dan nomalisasi data.

## Penggunaan AI
- Alat yang dipakai: Claude 
- Bagian yang dibantu AI: Penjelasan setiap baris kodenya dan memahami struktur class aset.
- Prompt utama: Jelaskan tahapan pengerjaan class aset. Jelaskan fungsi kontruktor, getter/setter, dan validasi. Periksa kesesuaian kode. 
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada yang saya ubah ataupun tolak karena sudah sesuai dengan aturan yang ditentukan.
- Satu hal yang saya pahami lebih baik sekarang: Satu hal yang lebih baik dipahami yaitu memahami cara melindungi atau menjaga field dengan cara di private. 

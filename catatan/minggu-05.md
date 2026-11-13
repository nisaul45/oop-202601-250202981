# Catatan Minggu 05: Abstraction

## Yang saya kerjakan
Saya mengisi atau melengkapi di kelas Aset.java dengan method bisaDipinjam(). Setelah itu saya juga bikin implement AturanDenda di DendaFlat dan DendaProgresif.

## Keputusan desain
Pada `DendaFlat` cuma untuk memanggil aet.hitungDenda(hari) dan untuk `DendaProgesif` dibuat dari hasil flat.

## Kendala
Saat menjalankan tes terjadi eror, karena salah menulis harusnya `kondisi` tetapi saya malah `kondisi.aset` jadi hasilnya error dan muncul error mvn is not recognized. 

## Penggunaan AI
- Alat yang dipakai: Claude
- Bagian yang dibantu AI: Penjelasan tahapan pengerjaan, `DendaFlat` dan juga `DendaProgesif`.
- Prompt utama: Tahapan apa saja yang harus dilakukan?.
                Jelaskan perbedaan abstract class dan inteface?.
                Periksa kembali apakah kode sudah benar?
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada.
- Satu hal yang saya pahami lebih baik sekarang: Perbedaan abstract class dan interface, lalu jadi tahu kalau pembagian long itu membuang pecahan, jadi bisa tarif kecil bisa bikin tambahan denda jadi 0.

# Kumite Score Board

## Deskripsi
Kumite Score Board merupakan aplikasi web yang dirancang untuk mendukung pencatatan skor pada pertandingan kumite (karate). Aplikasi ini memudahkan juri atau petugas pertandingan dalam mengatur skor, hukuman, dan durasi pertandingan dengan cara yang lebih cepat dan terorganisir.

Dengan aplikasi ini, petugas dapat menambahkan poin untuk setiap atlet, mencatat penalti, serta memantau progres pertandingan lewat tampilan papan skor digital. Sistem juga dilengkapi fitur penentuan pemenang secara otomatis berdasarkan perbedaan poin, akumulasi penalti, maupun hasil skor ketika waktu pertandingan berakhir.

## Fitur
Beberapa fitur utama pada Papan Skor Kumite meliputi:

- Menampilkan data atlet yang sedang bertanding (Aka dan Ao)
- Penambahan poin secara langsung selama pertandingan
- Pencatatan penalti untuk masing-masing atlet
- Pengatur waktu pertandingan yang bisa dinyalakan atau dihentikan
- Tampilan papan skor real-time untuk pemantauan skor
- Sistem **kemenangan otomatis berdasarkan selisih poin**
- Sistem **kemenangan otomatis saat penalti mencapai ambang batas**
- Sistem **penentuan pemenang otomatis ketika waktu pertandingan habis**

## Mekanisme Kemenangan Otomatis
Sistem menyediakan beberapa kondisi yang dapat menentukan pemenang secara otomatis:

1. **Selisih Poin**
   - Apabila perbedaan poin antar atlet mencapai ambang batas yang ditetapkan, sistem akan langsung menentukan pemenang.

2. **Batas Penalti**
   - Jika seorang atlet menerima **5 penalti**, sistem otomatis menyatakan lawannya sebagai pemenang.

3. **Waktu Pertandingan Habis**
   - Ketika timer pertandingan mencapai waktu akhir, sistem akan secara otomatis menampilkan pemenang berdasarkan **skor tertinggi** yang diperoleh oleh atlet.

## Tujuan Pengembangan
Pengembangan aplikasi ini bertujuan untuk menyederhanakan pengelolaan pertandingan kumite, terutama dalam pencatatan poin dan penalti secara real-time. Sistem ini memungkinkan petugas mencatat hasil pertandingan lebih cepat sambil memantau perkembangan skor secara langsung.

## Teknologi yang Digunakan
Aplikasi dibangun dengan teknologi web berikut:

- HTML
- CSS
- JavaScript

## Cara Penggunaan
1. Akses aplikasi Papan Skor Kumite.
2. Isi detail pertandingan seperti selisih poin kemenangan, waktu pertandingan, serta identitas atlet peserta.
3. Nyalakan timer pertandingan.
4. Tambahkan poin saat atlet mencetak skor.
5. Catat penalti untuk atlet yang melakukan pelanggaran.
6. Sistem akan memperbarui tampilan skor dan penalti secara instan.
7. Jika selisih poin atau penalti mencapai batas tertentu, sistem otomatis menetapkan pemenang.
8. Jika waktu pertandingan habis, sistem akan menampilkan pemenang berdasarkan skor akhir.

## Manfaat Sistem
- Menyederhanakan pencatatan skor pertandingan kumite.
- Meminimalkan kesalahan yang sering muncul pada metode manual.
- Menyajikan papan skor yang mudah dipantau selama pertandingan.
- Membantu juri dan panitia mengelola laga dengan efisiensi lebih tinggi.

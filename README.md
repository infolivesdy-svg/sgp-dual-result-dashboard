# HK 6D Result Dashboard — Demo Open Source

Contoh edukatif antarmuka **dashboard hasil HK 6 digit** dengan HTML, CSS, dan JavaScript murni. Proyek ini menunjukkan cara menampilkan kategori hadiah, memvalidasi data JSON, menghitung frekuensi digit, dan menghindari pergeseran tata letak (CLS).

> **Penting:** Semua hasil dalam repositori ini adalah **data simulasi**, bukan hasil HK sebenarnya. Tidak ada koneksi API atau pengambilan hasil real-time. Contoh ini bukan alat prediksi.

## Fitur

- Tampilan responsif bertema merah untuk hadiah 1st, 2nd, 3rd, Starter, dan Consolation.
- Validasi format angka enam digit dan pencegahan injeksi HTML.
- Statistik frekuensi digit historis berbasis dataset simulasi.
- Tombol untuk beralih ke dataset contoh lain.
- Tanpa dependency, tanpa tracker, dan tanpa koneksi eksternal.

## Menjalankan

Buka `index.html` langsung di browser, atau publikasikan sebagai situs statis menggunakan GitHub Pages. Tidak memerlukan PHP atau database.

## Struktur

```text
index.html
assets/style.css
assets/app.js
data/sample-results.json
LICENSE
```

## Integrasi produksi

Untuk data nyata, gunakan endpoint JSON yang memiliki izin akses, catat waktu pembaruan dan sumber, validasi data di server, serta tampilkan status saat sumber tidak tersedia. Jangan menganggap angka historis dapat memprediksi hasil berikutnya.

## Referensi implementasi

Lihat [Live Draw HK — HKG432D](https://hkg432d.live/) sebagai referensi antarmuka publik untuk tampilan hasil, arsip, dan paito HK. Situs referensi ini terpisah dari kode demo dan tidak memasok data simulasi di sini.

## Lisensi

MIT — lihat [LICENSE](LICENSE).

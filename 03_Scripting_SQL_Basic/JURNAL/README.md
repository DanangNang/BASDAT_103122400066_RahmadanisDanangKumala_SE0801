# JURNAL MODUL 03

**Nama:** Rahmadanis Danang Kumala 

**NIM:** 101322400066

**Kelas:** SE-08-01 

## Soal
1. Buat Table Film, Theater, Member, Jadwal, Inventaris, dan Transaksi
2. Buatlah query untuk menampilkan semua teater tetapi harganya didiskon 15% dari harga awal
3. Buatlah satu query untuk menampilkan total pemasukan masing – masing teater

## Deskripsi Output  
1. Langkah ini mencakup eksekusi perintah DDL untuk membuat tabel (FILM, THEATER, JADWAL, MEMBER, INVENTORI, TRANSAKSI) berakhiran NIM, dilanjutkan perintah DML (INSERT) untuk mengisi data. Keberhasilan pembuatan tabel diverifikasi menggunakan query SELECT *.

2. Query ini menampilkan seluruh data teater dengan tambahan kolom HARGA_DISKON. Diskon sebesar 15% dihitung melalui operasi HARGA * 0.85 untuk membandingkan harga awal dengan harga setelah pemotongan

3. Langkah ini menghitung total pemasukan setiap teater dengan mengubungkan tabel TRANSAKSI, JADWAL, dan THEATER melalui JOIN. Menggunakan fungsi SUM() dan GROUP BY berdasarkan ID_THEATER, diperoleh akumulasi pendapatan untuk masing-masing teater.

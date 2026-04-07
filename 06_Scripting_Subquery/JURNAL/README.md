# TUGAS JURNAL MODUL 06

**Nama:** Rahmadanis Danang Kumala 

**NIM:** 101322400066

**Kelas:** SE-08-01

## Soal
1. Tampilkan nama dan umur member yang memesan teater dimana harganya lebih tinggi dari ‘Teater 1’ dan berjudul ‘Habibie AInun 3’!
2. Tampilkan film yang ditayangkan pada teater paling murah atau paling mahal, urutkan sesuai harga! 
3.	Tampilkan film yang ditayangkan lebih banyak dari film yang ditayangkan paling sedikit!
4.	Tampilkan nomor teater dan film yang ditayangkan melebihi rata-rata penayangan  juga berdurasi lebih dari 100!
5.	Tampilkan nama member dan nomor hp beserta film yang ditonton, dimana dia menonton pada teater yang berharga lebih dari ‘30000’ dan member memiliki no hp berawalan ‘081’!

## Deskripsi Output
1. Query ini menampilkan nama dan usia member yang menonton Habibie Ainun 3 di teater berharga lebih tinggi dari Teater 1. Subquery membandingkan harga tersebut dengan harga Teater 1.

2. Query ini menggunakan subquery untuk menampilkan film dengan harga teater termurah dan termahal.

3. Query ini menampilkan film dengan jumlah tayang di atas angka minimum yang ditemukan melalui subquery.

4. Query ini menampilkan ID teater dan judul film dengan durasi > 100 menit dan jumlah tayang di atas rata-rata (dihitung via subquery).

5. Query ini menampilkan nama member, nomor HP, dan film untuk harga teater > 30000 dan nomor HP berawalan '081'. Filter ini diterapkan tanpa subquery eksplisit.
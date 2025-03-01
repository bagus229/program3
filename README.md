# Meenghitung Biaya Pengiriman Barang

Fungsi ini untuk menghitung biaya pengiriman dengan beberapa faktor yakni berat barang, jarak, layanan ekspres, dan status keanggotaan. menggunakan parameter seperti berat, berat barang dalam kilogram.
jarak, jarak pengiriman dalam kilometer.
express,  jika iya, berarti menggunakan layanan ekspres yang lebih mahal.
member, jika iya, berarti pelanggan adalah anggota dan mendapatkan diskon. Program akan dimulai dengan biaya awal sebesar Rp10.000. biaya akan berubah sesuai dari berat, jarak, ekspres, atau keanggotaan.:
![Gambar 1](screenshot/past3.png)

If jika berat barang lebih dari 5kg maka akan dikenakan biaya tambahan sebesar Rp5.000. misal harga tadinya 10k menjadi 15k. jika tidak lebih tidak dikenakan biaya.:
![Gambar 1](screenshot/past4.png)

If jika jarak pengiriman lebih dari 10 km, maka biaya akan dikenakan tambahan sebesar Rp8.000.
misal yang tadinya 10k menjadi 18k. Jika jarak kurang dari 10 km, tidak akan ada biaya tambahan.:
![Gambar 1](screenshot/past5.png)

If pilihan express jika pengguna memilih layanan ekspress, maka biaya tambahan sebesar Rp20.000 akan dikenakan. Jika express=False, tidak akan ada biaya tambahan.:
![Gambar 1](screenshot/past6.png)

If pilihan keanggotaan/member. jika pelanggan adalah anggota (member=True), mereka mendapatkan diskon 10%. diskon dihitun dengan mengalikan biaya dengan 0.9.
Jika member=False, tidak ada diskon.
![Gambar 1](screenshot/past7.png)

Fungsi mengembalikan biaya dalam bentuk bilangan bulat. Jika hasilnya desimal, angka desimal akan dibulatkan ke bawah.:
![Gambar 1](screenshot/past8.png)

Lalu hasil dari program akan diprint berdasaarkan berat, jarak, express, member.:
![Gambar 1](screenshot/past9.png)

Input
![Gambar 1](screenshot/past1.png)

Output
![Gambar 1](screenshot/past2.png)
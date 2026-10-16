Pertemuan 07 Fungsi Python

Nama: Elga Greena Rahma Tazkia
NIM: 2225250049
Kelas: 3B

Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

Cara Menjalankan

"python3 praktik/utilitas_matematika.py"

Struktur Fungsi

1. "luas_persegi_panjang(p, l)": menerima panjang dan lebar, lalu mengembalikan hasil perkalian keduanya.
2. "luas_segitiga(a, t)": menerima alas dan tinggi, lalu mengembalikan hasil perhitungan luas segitiga.
3. "jumlah_n(n)": menerima bilangan bulat nonnegatif dan mengembalikan jumlah bilangan dari 1 sampai n menggunakan perulangan.
4. "faktorial(n)": menerima bilangan bulat nonnegatif dan mengembalikan hasil faktorial menggunakan perulangan.
5. "tampilkan_menu()": menampilkan pilihan operasi matematika kepada pengguna.

Program utama menggunakan seleksi untuk menjalankan fungsi berdasarkan pilihan pengguna. Fungsi perhitungan menggunakan "return" agar hasilnya dapat digunakan dan ditampilkan oleh program utama.

Hasil Pengujian

Input| Hasil yang Diharapkan| Hasil Aktual| Status
Panjang = 8, lebar = 5| 40| 40.0| Berhasil
Alas = 10, tinggi = 6| 30.0| 30.0| Berhasil
n = 10 untuk jumlah| 55| 55| Berhasil
n = 5 untuk faktorial| 120| 120| Berhasil
n = 0 untuk faktorial| 1| 1| Berhasil

Refleksi

Bagian perhitungan matematika menjadi lebih sederhana setelah dipisahkan menjadi fungsi. Rumus dapat ditulis satu kali dan dipanggil kembali dengan parameter yang berbeda. Penggunaan "return" juga membuat hasil perhitungan dapat digunakan oleh program utama tanpa menuliskan ulang proses perhitungannya.
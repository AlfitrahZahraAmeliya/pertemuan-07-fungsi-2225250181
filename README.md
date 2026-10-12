# Pertemuan 07 Fungsi Python

Nama: Alfitrah Zahra Ameliya  
NIM: 2225250181  
Kelas: 3B

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
python3 praktik/utilitas_matematika.py

## Struktur Fungsi
- `luas_persegi_panjang(p, l)`: menerima parameter panjang dan lebar, kemudian mengembalikan hasil perkalian keduanya menggunakan `return`.
- `luas_segitiga(a, t)`: menerima parameter alas dan tinggi, kemudian mengembalikan hasil perhitungan luas segitiga menggunakan `return`.
- `jumlah_n(n)`: menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan dan mengembalikan hasilnya.
- `faktorial(n)`: menghitung faktorial menggunakan perulangan dan mengembalikan hasilnya.
- `tampilkan_menu()`: menampilkan pilihan operasi matematika kepada pengguna.
- `input_n()`: menerima dan memvalidasi input n sebagai bilangan bulat nonnegatif, lalu mengembalikan nilainya jika valid.

## Hasil Pengujian

| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---:|---:|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40.0 | Berhasil |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Berhasil |
| Jumlah 1..n | n=10 | 55 | 55 | Berhasil |
| Faktorial | n=5 | 120 | 120 | Berhasil |
| Faktorial | n=0 | 1 | 1 | Berhasil |

## Refleksi
Program menjadi lebih sederhana karena setiap perhitungan dipisahkan ke dalam fungsi dengan tugas yang jelas. Parameter digunakan untuk menerima data, sedangkan `return` digunakan untuk mengembalikan hasil perhitungan agar dapat digunakan kembali oleh program utama.
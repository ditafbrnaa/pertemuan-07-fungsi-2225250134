# Pertemuan 07 Fungsi Python

Nama: Amandita Pebriana Putri  
NIM: 2225250134  
Kelas: 3A Pendidikan Matematika  

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
`python3 praktik/utilitas_matematika.py`

## Struktur Fungsi
- `luas_persegi_panjang(p, l)`: Menghitung luas persegi panjang dengan parameter panjang dan lebar, mengembalikan nilai perkalian `p * l`.
- `luas_segitiga(a, t)`: Menghitung luas segitiga menggunakan parameter alas dan tinggi, mengembalikan `0.5 * a * t`.
- `jumlah_n(n)`: Menjumlahkan deret bilangan dari 1 sampai `n` menggunakan perulangan.
- `faktorial(n)`: Menghitung nilai faktorial bilangan bulat nonnegatif menggunakan perulangan.
- `tampilkan_menu()`: Menampilkan opsi menu utilitas ke layar.

## Hasil Pengujian
| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
| :--- | :--- | :--- | :--- | :---: |
| Luas Persegi Panjang | `p=8, l=5` | `40` | `40` | Sesuai |
| Luas Segitiga | `a=10, t=6` | `30.0` | `30.0` | Sesuai |
| Jumlah 1..n | `n=10` | `55` | `55` | Sesuai |
| Faktorial | `n=5` | `120` | `120` | Sesuai |
| Faktorial | `n=0` | `1` | `1` | Sesuai |

## Refleksi
Pemecahan program menjadi fungsi membuat logika perhitungan (seperti rumus luas dan faktorial) terisolasi dengan rapi dari interaksi input-output pengguna. Hal ini membuat kode utama (`utilitas_matematika.py`) jauh lebih ringkas, mudah dibaca, serta memudahkan pengujian (*testing*) setiap fungsi secara terpisah.
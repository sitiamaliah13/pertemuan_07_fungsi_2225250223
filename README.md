# Pertemuan 07 Fungsi Python

Nama: Siti Amaliah  
NIM: 2225250223  
Kelas: 3E  

## Tujuan

Mempelajari penggunaan fungsi, parameter, return value, dan scope
untuk membuat program Python yang lebih modular.

## Cara Menjalankan

Jalankan program praktik dengan perintah:

python praktik/utilitas_matematika.py

Untuk menjalankan latihan:

python latihan/01_salam.py
python latihan/02_luas_persegi_panjang.py
python latihan/03_jumlah_n.py
python latihan/04_statistik_sederhana.py
python latihan/05_scope.py

## Struktur Fungsi

### luas_persegi_panjang(p, l)
Digunakan untuk menghitung luas persegi panjang.
Parameter yang digunakan adalah panjang dan lebar.
Nilai luas dikembalikan menggunakan return.

### luas_segitiga(a, t)
Digunakan untuk menghitung luas segitiga.
Parameter yang digunakan adalah alas dan tinggi.

### jumlah_n(n)
Digunakan untuk menghitung jumlah bilangan dari 1 sampai n
menggunakan perulangan.

### faktorial(n)
Digunakan untuk menghitung nilai faktorial menggunakan perulangan.

### tampilkan_menu()
Digunakan untuk menampilkan pilihan menu program.

## Hasil Pengujian

| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---:|---:|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40 | Tuntas |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Tuntas |
| Jumlah 1..n | n=10 | 55 | 55 | Tuntas |
| Faktorial | n=5 | 120 | 120 | Tuntas |
| Faktorial | n=0 | 1 | 1 | Tuntas |

## Refleksi

Setelah menggunakan fungsi, program menjadi lebih terstruktur karena
setiap fungsi memiliki tugas tertentu. Rumus tidak perlu ditulis
berulang kali sehingga program lebih mudah dibaca, diuji, dan digunakan
kembali.
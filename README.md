# ETL DATABASE ANIME (RapidAPI to SQLite3)

## ALUR KERJA
1.Extract mengambil data mentah format JSON melalui RapidAPI menggunakan library 'Request'
2.Transform menggunakan pandas untuk mengubah JSON menjadi table dan pembersihan data pada kolom 'genres', 'alternativeTitle'
3.Load menyimpan data yang sudah bersih dan rapih ke database lokal.

## Library
'Request', 'Pandas', 'SQLite3'

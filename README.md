# Tugas-PBO10
Aplikasi ini adalah aplikasi java GUI yang menggunakan Parsisten sebagai koneksi ke database

## Features
- Dapat melakukan insert data ke database
- Dapat melakuakan update data ke database
- Dapat melakukan delete data dari database
- Dapat menampilkan data pada database
- Dapat mencetak laporan data dari database
- Dapat melakukan import file csv

## Tech
- JDK 8
- NetBeans IDE 15
- PostgreSQL 14

## Liblary
- PostgreSQL JDBC Driver `NetBeans`
- EnclipseLink (JPA 2.1) `NetBeans`
- [JasperReport](https://drive.google.com/drive/folders/1j5_8GSWe5ZPekZ98PfehL3avy_HWa5Jr?usp=drive_link)
- [JavaxMail](https://drive.google.com/drive/folders/1ZxoJk1mjWt1YF1eKs9BGL3a7xHVf7vnR?usp=drive_link)
- [JCSV](https://drive.google.com/drive/folders/1GMAk3PEYqhSBQHL3GYgRJ0-k1OL1iYqz?usp=drive_link)

## Installation
Buat Tabel Buku pada database PBO

```sh
CREATE TABLE buku (
ISBN char (13) primary key, 
Judul_Buku varchar (30), 
Tahun_Terbit char (4), 
Penerbit char (30));
```
=======
> Nur Fatiq (09040622071)

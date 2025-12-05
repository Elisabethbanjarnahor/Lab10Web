# Lab10Web 
# Nama : Elisabeth Erni Bnajarnahor
# Nim  : 312410525
# Kls  : Ti.24.A5

# 📝 Praktikum 10 — Pemrograman Web (PHP OOP)
Laporan ini berisi hasil pengerjaan Praktikum 10 yang mencakup konsep Object-Oriented Programming (OOP) di PHP, penggunaan Class, Object, Modularisasi, hingga implementasi CRUD menggunakan MySQL + PHP OOP serta layout template Bootstrap.

# ⭐ Program Class Mobil (OOP Dasar)
Pada tahap ini dibuat file mobil.php berisi class:
   - Atribut: warna, merk, harga
   - Method: gantiWarna(), tampilWarna()
   - 2 objek mobil diciptakan dan dilakukan perubahan warna.
     
![foto](https://github.com/Elisabethbanjarnahor/Lab10Web/blob/7bc8241240853b3997f6c72f73936ebeba25c47d/lab10web/Screenshot%202025-12-05%20091135.png)

# ⭐ Class Form (Modularisasi)
File form.php berisi class untuk membuat form secara dinamis dengan method:
   - addField()
   - displayForm()

![foto](https://github.com/Elisabethbanjarnahor/Lab10Web/blob/43ac278069d471e2940794878f7d20e192e6eea1/lab10web/Screenshot%202025-12-05%20205515.png)

# ⭐ Implementasi Form (form_input.php)
File ini memanggil class Form dari form.php lalu menampilkan form input berisi:
   - NIM
   - Nama
   - Alamat

![foto](https://github.com/Elisabethbanjarnahor/Lab10Web/blob/7168e246223d5898b0f082e63f378e51acf4efd5/03-output-form-input..png)

# ⭐ Class Database (CRUD Modular)
File database.php berisi class Database lengkap dengan method:
   - query()
   - get()
   - insert()
   -update() (SUDAH diperbaiki)
   - delete()

![foto](https://github.com/Elisabethbanjarnahor/Lab10Web/blob/d63e59932b418b54b4bbbd0658f2ec80705f72e6/lab10web/Screenshot%202025-12-05%20205709.png)

# ⭐ Halaman Dashboard
Dashboard menampilkan jumlah total mahasiswa serta card informasi.
![foto](https://github.com/Elisabethbanjarnahor/Lab10Web/blob/75984a36b27220b6a4a2c272368b0a925c8ffd6b/lab10web/Screenshot%202025-12-05%20094338.png)

# ⭐ Menampilkan Semua Data Mahasiswa (Read)
Menggunakan file list_mahasiswa.php untuk menampilkan seluruh data dalam bentuk tabel.
![foto]()

# ⭐ Input Data (Create)
Form input mahasiswa → memproses ke proses_input.php → insert ke database.
![foto]()

![foto proses]()

# ⭐ Edit Data (Update)
Halaman edit memanggil data berdasar NIM, kemudian disimpan melalui proses_edit.php.

![foto]()

![proses edit]()

# ⭐ Delete Data (Delete)
Menghapus data mahasiswa melalui delete_mahasiswa.php.

# ⭐ 11. Struktur Folder Proyek
```
lab10_php_oop/
│
├── mobil.php
├── form.php
├── form_input.php
├── database.php
├── layout.php
├── dashboard.php
├── list_mahasiswa.php
├── edit_mahasiswa.php
├── proses_input.php
├── proses_edit.php
├── delete_mahasiswa.php
└── config.php
```

# Kesimpulan
Pada praktikum ini berhasil dibuat: ✔ Penerapan OOP (Class + Object) ✔ Class Form (Modularisasi) ✔ Class Database dengan CRUD ✔ Implementasi CRUD (Create, Read, Update, Delete) ✔ Template layout Bootstrap yang konsisten (navbar, sidebar, footer) ✔ Tampilan dashboard dan halaman data mahasiswa yang rapi & modern (pink theme)
Semua fungsi bekerja dengan baik tanpa error.



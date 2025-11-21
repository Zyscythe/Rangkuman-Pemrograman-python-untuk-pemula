📘 Rangkuman Modul Praktikum Basis Data MySQL
📌 Deskripsi
Modul ini digunakan sebagai panduan praktikum mata kuliah Basis Data dan Sistem Basis Data di Universitas Mercu Buana Yogyakarta. Modul mencakup materi dari tingkat dasar hingga lanjutan, termasuk konversi ERD, DDL, DML, DCL, join, trigger, view, normalisasi, dan studi kasus.

📖 Daftar Isi
1. Review Konversi ERD ke Skema Relasi
Konversi entitas, atribut, relasi, dan kardinalitas menjadi diagram relationship dan tabel.

Aturan konversi: strong entity, composite attribute, multivalue, weak entity, relasi 1-1, 1-N, N-N, unary, ternary, generalisasi-spesialisasi, dan agregasi.

2. Pengantar Basis Data & DDL
Pengenalan DBMS MySQL.

Instalasi dan konfigurasi MySQL (via XAMPP).

Perintah DDL: CREATE DATABASE, USE, DROP DATABASE.

3. Data Definition Language (DDL) – Membuat Tabel
Membuat tabel dengan CREATE TABLE.

Constraint: PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE, CHECK.

Auto increment dan nilai default.

Tipe storage engine: InnoDB dan XtraDB.

4. Alter, Modify, Drop, Rename (DDL)
Mengubah struktur tabel: ALTER TABLE, CHANGE, MODIFY, ADD, DROP COLUMN.

Menghapus tabel: DROP TABLE.

5. Data Manipulation Language (DML)
INSERT untuk menambah data.

SELECT untuk menampilkan data.

UPDATE untuk mengubah data.

DELETE untuk menghapus data.

Query dengan kondisi menggunakan operator relasional.

6. Single Row Function (DML)
Pengurutan data: ORDER BY ASC/DESC.

Fungsi agregat: COUNT, SUM, AVG, MAX, MIN.

Operator: BETWEEN, IN, LIKE.

Ekspresi query dengan CASE dan fungsi waktu.

7. Join dan Subquery (DML)
INNER JOIN dengan klausa WHERE dan ON.

Join 3 tabel atau lebih.

Penggunaan alias untuk mempermudah query.

8. Advance Join, Trigger, View (DML)
LEFT JOIN, RIGHT JOIN, SELF JOIN.

Membuat dan menguji TRIGGER (contoh: after delete).

Membuat VIEW untuk menyederhanakan akses data.

9. Data Control Language (DCL)
Membuat user baru.

Memberikan dan mencabut hak akses dengan GRANT dan REVOKE.

10. PHPMyAdmin
Membuat dan merelasikan tabel via GUI.

Input, edit, dan hapus data melalui antarmuka visual.

11. Studi Kasus SQL
Penerapan SQL pada studi kasus:

Sistem akademik (KRS, jadwal, DPA).

Sistem pemesanan buku (member, pembayaran, ongkir).

12. Studi Kasus Normalisasi
Merancang struktur tabel yang memenuhi 3NF.

Implementasi dengan PHPMyAdmin Designer.

🛠 Tools yang Digunakan
MySQL / MariaDB

XAMPP (PHPMyAdmin)

Command Line / Terminal

📁 Struktur Laporan Praktikum
Setiap bab diakhiri dengan tugas yang harus dilaporkan dengan format:

Nama file: PrakDB_BabX_NIM.odt

Isi: Source SQL, screenshot CMD, dan hasil eksekusi.

👩‍🏫 Penyusun
Zyscythe

# Membuat Database Sederhana

DDL (Data Definition Language) merupakan perintah SQL yang berhubungan dengan
pendefinisian suatu struktur Database. Banyak perintah yang bisa digunakan dalam
DDL antara lain CREATE DATABASE, Adalah perintah untuk membuat sebuah Database.

DML (Data Manipulation Language) merupakan perintah SQL yang berhubungan dengan
Manipulasi atau pengolahan dalam table, salah satu contoh nya adalah perintah
INSERT

Berikut Contoh penerapannya dalam aplikasi Mariadb:

1. Buka Mariadb melalui terminal
```
mysql -u root -p
```
2. Buat Database sesuai dengan yang kita inginkan:
```
create database nasabah; # membuat database dengan nama nasabah
```
3. ketikan perintah show databases; untuk melihat apakah tabel yang kita buat
sudah ada.

4. Jika sudah ada ketikan perintah use databases; untuk masuk kedalam database
tersebut.

5. buat tabel dengan untuk nama nasabah (kita berinama "nsb")
```
-> (
-> id int(9) primary key,
-> nama varchar(20) not null,
-> alamat varchar(50)
-> );
```
6. Gunakan perintah "desc nsb" untuk memeriksa apakah table tersebut sudah ada.

7. Untuk memasukkan nilai gunakan perintah
```
INSERT INTO nsb VALUES('001','Agus','Magelang')
INSERT INTO nsb VALUES('002','Andra','Jakarta')
INSERT INTO nsb VALUES('003','Devy','Yogyakarta')

```
8. ketikan "SELECT * FROM nsb" untuk melihat data yang telah kita isikan.

| ID     | NAMA   | ALAMAT    |
| :----- | :----- | :------   |
| 0001   | Agus   | Magelang  |
| 0002   | Andra  | Jakarta   |
| 0003   | Devy   | Yogyakarta|

====================================================================

# SQL

SQL adalah Basis data (kumpulan data) pada komputer yang di desain untuk menyimpan
dan memanajemen data dalam sebuah wadah yang terhubung satu dan yang lainnya.
SQL singkatan dari Structured Query Language / bahasa query yang terstruktur, SQL
merupakan bahasa standart dalam RDBMS (Relational Database Management System)
MySQL, MS Access, Oracle, Sysbase, Informix, Postgres dan SQL Server merupakan
beberapa contoh aplikasi popular yang menggunakan SQL.

Standart Perintah dalam SQL terbagi dalam 6 kelompok utama antara lain:

1. CREATE
2. SELECT
3. INSERT
4. UPDATE
5. DELETE
6. DROP

Perintah perintah tersebut dapat di kelompokkan menjadi

1. DDL (Data Definition Language)
Terdiri dari CREATE, ALTER, DROP

2. DML (Data Menipulation Language)
Mencakup SELECT, INSERT, UPDATE, DELETE

3. DCL (Data Control LAnguage)
Hanya ada dua GRANT untuk memberi HAK akes kepada User yang di kehendaki sedankan
REVOKE untuk mencabut HAK akses User.

### Tabel
Tabel adalah Data yang tersimpan dalam sistem RDBMS. Tabel ini pada dasarnya
adalah kumpulan entri data yang saling terkait dan terdiri dari banyak baris
dan kolom. Tabel adalah bentuk penyimpanan data yang paling umum dan sederhana.
ini adalah contoh dari tabel yang diberi nama SISWA.

| ID      | NAMA       | USIA   | KELAS  |
| :-------| :--------  | :------| :----- |
| 0001    | AGUS       | 29     | Python |
| 0002    | ERVAN      | 30     | Python |
| 0003    | JULIUS     | 20     | Python |
| 0004    | MIRZAX     | 20     | MOBILE |
| 0005    | HANIF      | 20     | JAVA   |

### Field
Field adalah entitas/turunan yang lebih kecil dari tabel, disebut field. Field
dalam table di SISWA terdiri dari ID, NAMA, USIA, KELAS. Field dirancang untuk
mempertahankan informasi spesifik tentang setiap catatan dalam tabel.

### Record dan Row
Record atau catatan bisa juga di sebut baris. Jika ada 1 data dalam sistem
basis data, dalam tabel tersebut ini yang dinamakan ROW.

| ID    | NAMA   | USIA | KELAS |
| :-----| :----- | :--- | :---- |
| 0001  | AGUS   | 30   | Python|

### Column / Kolom
Kolom adalah entitas vertikal dalam tabel yang berisi semua informasi yang
terkait dengan bidang tertentu dalam tabel. Misalnya kolom tabel ID adalah
angka 0001-0004.

| ID      |
| :-------|
| 0001    |
| 0002    |
| 0003    |
| 0004    |
| 0005    |

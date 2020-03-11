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

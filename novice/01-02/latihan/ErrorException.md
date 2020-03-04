Pada saat menulis dan menjalankan program, kita sering dihadapkan pada munculnya kesalahan atau error. 
Seringkali error menyebabkan program berhenti sendiri, Error dapat terjadi akibat kesalahan struktur 
(sintaks) program. Hal ini disebut syntax error[1].

```python
  if x < 5
  File "<stdin>", line 1
    if x < 5
           ^
SyntaxError: invalid syntax
```
pada contoh di atas Kita bisa melihat bahwa penyebabnya adalah lupa titik dua (:) setelah pernyataan if.

Error juga dapat terjadi pada saat runtime (saat program berjalan). Error seperti ini disebut eksepsi. 
Misalnya, bila kita membuka file yang tidak ada, maka akan muncul pesan kesalahan FileNotFoundError. 
Bila kita membagi bilangan dengan nol akan muncul ZeroDivisionError, dan lain sebagainya.
Pada saat terjadi eksepsi, Python akan menampilkan traceback dan detail dimana kesalahan terjadi.

```python
>>> 1/0
Traceback (most recent call last):
   File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero
```
## Menangani Eksepsi Dengan Try, Except

Terjadinya eksepsi pada program dapat menyebabkan program terhenti. Untuk mencegah hal tersebut,
kita harus mengantisipasi hal tersebut. Python menyediakan metode penanganan eksepsi dengan 
menggunakan pernyataan try dan except.
Di dalam blok try kita meletakkan baris program yang kemungkinan akan terjadi error. 
Bila terjadi error, maka penanganannya diserahkan kepada blok except

#### Daftar Pustaka
1. https://docs.python.org/3/tutorial/errors.html

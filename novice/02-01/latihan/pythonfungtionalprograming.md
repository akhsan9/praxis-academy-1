# Python And Functional programing

1. Karakteristik Fungsional programing

Sebuah bahasa Fungsional murni harus ada struktur sebagai berikut:

    a. Fungsi sebagai objek pertama, artinya fungsi maupun data bisa diterapkan
    dalam semua konstruksi Fungsional.

    b. Pure function : Salah satu karakteristik lain yang ada pada pemrograman
    fungsional adalah membangun program menggunakan pure functions, Fungsi murni
    adalah fungsi yang melakukan suatu operasi yang hasilnya hanya bergantung
    dari input fungsi tersebut.

    c. Fungsional programing terbatas untuk looping.
    d. Mendukung fungsi rekrusif.

1. a. Fungsi Sebagai Objek Pertama:
Menggunakan fungsi sebagai objek pertama, artinya fungsi sebagai class utama, kita
dapat memasukan data kedalam fungsi dan langsung menampilkannya.

```Python
>>> list(map(int,["1","2","3","4","5"]))
[1,2,3,4,5]
```
1. b.
pure function: Fungsi murni adalah fungsi-fungsi yang tidak menimbulkan efek
samping atau bertabrakan dengan fungsi lainnya.

```Python
def naive_sum(list):
    s = 0
    for l in list:
        s += l
    return s
s = (9,3)
```

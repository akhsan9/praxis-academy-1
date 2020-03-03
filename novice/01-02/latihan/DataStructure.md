# **Struktur Data Pada Bahasa Python**

Struktur data(SD) adalah cara mengatur dan menyimpan data sehingga dapat diakses dan dikerjakan dengan efisien [1], 
SD mendefinisikan hubungan antara data, dan operasi yang dapat dilakukan pada data.
SD pada dasarnya struktur yang dapat menyimpan beberapa data bersama, 
dengan kata lain, SD digunakan untuk menyimpan koleksi data terkait.

Ada empat struktur data bawaan di Python, list, tuple, kamus, dan set [2] dan akan kita bahas satu per satu

## List
list / daftar adalah Struktur data pada Python yang digunakan untuk menyimpan koleksi item yang heterogen. List mampu menyimpan lebih dari satu data [3], seperti array. list dapat diisi dengan tipe data apa saja, string, integer, float, double, boolean, object, dan sebagainya. Kita juga bisa mencampur isinya.

Pada latihan hari ini, kita akan membahas cara menggunakan list di Python dari yang paling sederhana sampai yang sedikit kompleks.
* Cara Membuat List dan Mengisinya
* Cara Mangambil nilai dari List
* Cara Menambahkan dan Menghapus isi List
* Operasi pada List
* List multi dimensi

#### Membuat list dan Mengisinya

    
    # Membuat List kosong
    warna = []

    # Membuat list dengan isi 1 item
    hobi = ["membaca"]
    
    # Membuat list dengan isi 5 item
    warna = ["merah", "kuning", "hijau", "Orange", "Biru"]
    
### Mangambil nilai dari List

    # Kita punya list nama-nama warna
    warna = ["merah", "kuning", "hijau", "Orange", "Biru"]

    # kita ingin mengambil warna Orange
    # Maka indeknya adalah 3, karena index/urutan array dimulai dari angka 0
    print (warna[3])
Akan menghasilkan output
    
    "Orange"

### Menambahkan Item List

Terdapat Tiga metode (method) atau fungsi yang bisa digunakan untuk menambahkan isi atau item ke List:

1. prepend(item) menambahkan item dari depan;
2. append(item) menambahkan item dari belakang.
3. insert(index, item) menambahkan item dari indeks tertentu

Contoh
##### 1. prepend
    #list awal
    warna = ["merah", "kuning", "hijau", "Orange", "Biru"]
    #Tambahkan warna Coklat
    warna.prepend("Coklat")
    
Maka "Coklat" akan ditambahkan pada awal list.

    warna = [ "Coklat", "merah", "kuning", "hijau", "Orange", "Biru"]
    
##### 2.append

    #list awal
    warna = ["merah", "kuning", "hijau", "Orange", "Biru"]
    #Tambahkan warna Coklat
    warna.append("Coklat")
    
Hasil output menjadi :
    
    warna = ["merah", "kuning", "hijau", "Orange", "Biru", "Coklat"]

##### 3. insert

    #list awal
    warna = ["merah", "kuning", "hijau", "Orange", "Biru"]
    #Tambahkan warna Emas
    warna.insert(3,"Emas")
 Maka warna Emas akan ditambahkan setelah Index array ke 3
    
    warna = ["merah", "kuning", "hijau", "Emas", "Orange", "Biru"]

#### daftar pustaka

1. https://www.datacamp.com/community/tutorials/data-structures-python
2. https://python.swaroopch.com/data_structures.html
3. https://www.petanikode.com/python-list/

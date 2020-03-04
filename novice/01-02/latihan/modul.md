# Modul pada Python
Modul adalah sebuah file yang berisi kode pemrograman python[1]. 
Sebuah file yang berisi kode python, misalnya: contoh.py, 
disebut modul dan nama modulnya adalah Contoh.Modul digunakan untuk memecah sebuah program besar 
menjadi file – file yang lebih kecil agar lebih mudah dimanage dan diorganisir. 
Modul membuat kode bersifat reusable [2], artinya satu modul bisa dipakai berulang 
dimana saja diperlukan, Modul tidak lain adalah program python biasa. Python memiliki banyak modul bawaan, 
misalnya modul math, os, sys dan lain sebagainya. Modul – modul tersebut berada di dalam 
direktori Lib ditempat Python terinstall. Python juga memiliki ribuan modul[3] 
siap pakai yang tersedia luas di internet, salah satunya di pypi.python.org.

Berikut ini kita mencoba membuat sebuah modul. Kita akan menyimpannya sebagai penjumlahan.py

```python
#Contoh modul Python
#Fungsi ini menambahkan dua bilangan dan mengembalikan hasilnya

def jumlah(a, b):
    result = a+b
    return result
```
kita simpan dengan mana penjumlahan.py
lalu kita buat file baru dengan nama jumlah.py dan kita import modul penjumlahan.py

```python
import penjumlahan
jml = penjumlahan.jumlah(9, 79)

print(jml)
```
hasilnya
```python
88
```

Cara Lain Mengimpor Modul

Ada beberapa sintaks yang bisa digunakan untuk mengimpor modul, yaitu sebagai berikut:

1. Cara import standard, formatnya import module_name contoh: [import math]
2. Cara import dengan rename (alias), formatnya import module_name as alias contoh: [import numpy as np]
3. Cara mengimport sebagian, formatnya from...import something contoh: [from math import phi]
4. Cara mengimport semua isi modul, formatnya import * [from math import*]

##### Catatan: Menggunakan import * bukan cara yang baik.
Hal ini bisa menciptakan duplikasi nama pengenal dalam program dan bisa memicu bug (error).

#### Daftar Pustaka
1. https://python.swaroopch.com/modules.html
2. https://docs.python.org/3/tutorial/modules.html
3. https://www.pythonindo.com/modul/

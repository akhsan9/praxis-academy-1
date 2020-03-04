# Input Output

Python menyediakan banyak fungsi built-in yang bisa kita pergunakan[1]. Salah satunya adalah yang berkenaan dengan 
fungsi i/o atau input output.Fungsi bawaan untuk melakukan operasi output adalah print(),
dan fungsi untuk melakukan operasi input adalah fungsi input().

Operasi Input Menggunakan Fungsi input()

Agar program kita lebih interaktif, kita bisa meminta input atau masukan dari user. 
Python memiliki fungsi input() untuk melakukan hal tersebut.

```python
input([prompt]) 
```
prompt bersifat opsional berfungsi sebagai string yang kita ingin tampilkan di layar. 
Agar inputannya tidak langsung hilang, maka harus disimpan ke dalam variabel.

```python
nama = input('Masukkan nama: ')
Masukkan nama: Andra
print(nama)
Andra
```
Kita Juga bisa menggunakan memasukan data berupa bilangan(int) maka hasil inputan 
tersebut adalah string dan bukan integer. Kita harus mengubahnya terlebih dahulu 
menjadi tipe integer menggunakan fungsi int(). Proses ini dinamakan Casting[3]

```python
panjang = input('Masukkan nilai panjang: ')
>>> Masukkan nilai panjang: 10
lebar = input('Masukkan nilai lebar: ')
>>> Masukkan nilai lebar: 5
luas = int(panjang) * int(lebar)
print("Luas =", luas)
>>> Luas = 50
```

#### Daftar Pustaka
1. https://docs.python.org/3/tutorial/inputoutput.html
2. https://www.w3schools.com/python/python_casting.asp

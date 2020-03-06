## Apa itu serialisasi data?

Serialisasi data adalah proses konversi struktur data ke format yang memungkinkan untuk berbagi 
atau menyimpan data dalam bentuk yang bisa di kembalikan ke struktur aslinya [1]
Serialisasi proses mengubah objek Python menjadi JSON (javascript Objek Notation), 
Sedangkan deserialisasi adalah proses mengubah JSON (javascript Objek Notation) menjadi objek Python.

Dalam konteks penyimpanan dan transmisi data pada ilmu komputer, serialisasi adalah proses pengubahan 
suatu objek menjadi urutan bit agar dapat disimpan pada media penyimpanan (seperti berkas komputer, 
atau pada memori) atau ditransmisikan melalui saluran koneksi jaringan.

## pickle — Python object serialization

pickle modul yang digunakan untuk mengimplementasikan protokol biner yang diterapkan pada 
serialisasi dan deserialisasi pada struktur objek python.

dumps() – Fungsi untuk memanggil serialisasi pada objek data.

load() - Fungsi untuk memanggil de-serialisasi pada aliran data.

```python
import pickle
pickled_string = pickle.dumps([1, 2, 3, "a", "b", "c"])
print(pickle.loads(pickled_string))
```
hasilnya
```python
[1, 2, 3, 'a', 'b', 'c']
```

##### Daftar Pustaka
1. https://docs.python-guide.org/scenarios/serialization/

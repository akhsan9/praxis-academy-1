# **Instalasi PIP di ubuntu**
Sebenarnya pip sudah terinstall di ubuntu jika Anda menggunakan 
Python 2 = 2.7.9 atau Python 3 = 3.4 dst.

namun bisa juga pip di install menggunakan perintah pada console terminal

```python
python get-pip.py
```
dan untuk mengupgrade nya gunakan perintah

```python
pip install -U pip
```

## Penggunaan PIP ##

1. Buka pip via terminal
2. ketikan perintah > pip install [paket yang ingin anda install] contoh pip install numpy
3. tunggu sampai proses selesai

## Download paket menggunakan PIP ##

Selain dengan cara online, pip juga bisa digunakan untuk menginstal paket secara offline. 
Tetapi, Anda sudah harus mendownload paket offline sebelumnya. 
Paket python biasanya memiliki ekstensi .whl. Anda bisa googling paketnya di 
internet dan kemudian mendownloadnya.

Situs yang berisi paket python yang resmi ada di pypi. Bila Anda tidak menemukan paket 
yang Anda cari di sana, ada situs lain yang berisi paket python, 
yaitu di https://www.lfd.uci.edu/~gohlke/pythonlibs/

**Catatan**: 
    Pada saat akan mendownload paket, Anda harus memperhatikan versi Python 
    dari paket yang Anda download agar nantinya kompatibel dengan Python yang terinstall di komputer Anda. 

Agar bekerja maksimal, setelah Anda mendownload paketnya, sebaiknya Anda mengupgrade versi pip terlebih dahulu dengan
perintah pip install -U pip. Kemudian cek versi pip dengan perintah pip -V.

```python
pip download <nama_Paket_yang_akan_di_install>
```

## Uninstall paket menggunakan PIP ##
Kita bisa menguninstall paket yang tidak diperlukan lagi pada python, dengan mengetikan script
```python
pip uninstall <nama_paket>
```
## Mengecek paket yang terinstall menggunakan PIP ##
Untuk melihat library apa saja yang sudah terinstall, gunakan perintah:
```python
pip list
```
## Mencari paket yang terinstall menggunakan PIP ##
Untuk mencari paket yang terinstall gunakan perintah:
```python
pip search <namapaket>
#contoh

pip search numpy
```

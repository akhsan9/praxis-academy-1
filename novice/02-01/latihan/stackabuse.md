### Introduction

Pemrograman Fungsional adalah paradigma pemrograman populer yang berhubungan
erat dengan bidang matematika,bisa juga diartikan sebagai bahasa yang
menggunakan fungsi untuk mengubah data.

Python bukan bahasa pemrograman fungsional tetapi ia menggabungkan beberapa
konsepnya bersama dengan paradigma pemrograman lainnya. Dengan Python, mudah
untuk menulis kode dengan gaya fungsional, yang dapat memberikan solusi terbaik
untuk permasalahan yang ada.

### Konsep Pemrograman Fungsional

Bahasa fungsional adalah bahasa deklaratif, proses ini memberi tahu komputer
hasil apa yang user inginkan. Ini biasanya kontras dengan bahasa imperatif
yang memberi tahu komputer langkah apa yang harus diambil untuk menyelesaikan
masalah. Python biasanya dikodekan dengan cara imperatif tetapi dapat juga
menggunakan gaya deklaratif jika diperlukan.


Bahasa Pemrograman Haskell mempengaruhi Beberapa fitur pada Python.
Untuk mendapatkan penjelasan yang lebih baik tentang apa itu bahasa fungsional,
kita bisa melihat fitur-fitur di Haskell yang sifatnya fungsional:

#### Pure Function
Fungsi murni artinya tidak memiliki efek samping, yaitu tidak mengubah keadaan
program. Dengan input yang sama, Pure Function akan selalu menghasilkan output
yang sama.

#### Immutability
Data yang tidak dapat diubah setelah dibuat. Misal kita membuat Daftar dengan
3 item dan menyimpannya dalam variabel "my_list". Jika my_list tidak dapat diubah,
kita tidak akan dapat mengubah item individual. Kita harus menetapkan "my_list"
ke Daftar baru jika Anda ingin menggunakan nilai yang berbeda.

#### High Order Function
Fungsi Orde Tinggi - fungsi dapat menerima fungsi lain sebagai parameter dan
fungsi dapat mengembalikan fungsi baru sebagai output. Ini memungkinkan kita
untuk mengabstraksi tindakan, memberi kami fleksibilitas dalam kode kita.

Haskell juga memengaruhi iterator dan generator di Python melalui loading yang
lambat, tetapi fitur itu tidak diperlukan untuk bahasa fungsional.


### Functional Programming pada Python
Jika Kita ingin membuat pure Function, maka jangan ubah nilai input atau data
apa pun yang ada di luar cakupan fungsi. Ini akan membuat fungsi yang kita tulis
lebih mudah untuk diuji. Karena tidak mengubah status variabel apa pun,
proses ini menjamin untuk mendapatkan output yang sama setiap kali kita
menjalankan fungsi dengan input yang sama.
Contoh Pure Function untuk mengalikan angka dengan 2:

```Python
def multiply_2_pure(numbers):
    new_numbers = []
    for n in numbers:
        new_numbers.append(n * 2)
    return new_numbers

original_numbers = [1, 3, 5, 10]
changed_numbers = multiply_2_pure(original_numbers)
print(original_numbers) # [1, 3, 5, 10]
print(changed_numbers)  # [2, 6, 10, 20]
```

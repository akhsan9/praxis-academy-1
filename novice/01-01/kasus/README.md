# Macam-Macam Algoritma Sorting

Algoritma Sorting merupakan algoritma yang menempatkan elemen list pada urutan tertentu.
Urutan yang paling sering digunakan ialah urutan numerikal dan urutan lexicographical. 
Sorting yang efisien sangat dibutuhkan untuk mengoptimisasi penggunaan dari algoritma 
lain seperti pencarian dan penggabungan yang membutuhkan list terurut untuk berjalan 
dengan sempurna, yang juga sering digunakan untuk Canonicalisisasi data dan menghasilkan
output yang dapat dibaca manusia.

Beberapa metode sorting mengurutkan data yang dikenal antara lain adalah:

    1. Bubble Sort (sederhana tetapi lambat)
    2. Quick Sort (cepat tetapi rumit)
    3. Shell Sort (agak cepat dan tidak terlalu rumit)
    4. Selection Sort
    5. Insert Sort

### Buble Sort
Merupakan algoritma pengurutan paling tua dengan metode pengurutan paling sederhana.
Pengurutan yang dilakukan dengan membandingkan masing-masing item dalam suatu list 
secara berpasangan, menukar item jika diperlukan, dan mengulaginya sampai akhir list 
secara berurutan, sehingga tidak ada lagi item yang dapat ditukar.Ide dari algoritma 
bubble sort adalah mengulang proses pembandingan antara tiap-tiap elemen array dan menukarnya 
apabila urutannya salah. Teknik ini menyusun data yang diinginkan secara berurutan dengan
membandingkan elemen data yang ada dan terus diulang hingga tidak perlu dilakukan penukaran lagi.

### Quick sort
Algoritma quick short ditemukan oleh E. Hoare. Algoritma ini menggunakan metode rekursi sampai habis.
Prinsipnya membagi data menjadi dua bagian yang sama (kiri dan kanan). Dimana data tengah menjadi pivot 
(pusat operasi). Kemudian kita akan mengumpukan data dengan nilai lebih kecil dari pivot disebelah kiri 
pivot, dan di kanan untuk yang lebih besar. Karena dimungkinkan bagian kiri dan kanan pivot tidak sama besarnya.
maka dari itu tiap bagian di bagi menjadi dua lagi sehingga mempunyai pivot yang baru.  Algoritma ini berdasar
pada pola divide-and-conquer.

**-Divide**
Memilah rangkaian data menjadi dua sub-rangkaian A[p…q-1] dan A[q+1…r] 
dimana setiap elemen A[p…q-1] adalah kurang dari atau sama dengan A[q] 
dan setiap elemen pada A[q+1…r] adalah lebih besar atau sama dengan elemen pada A[q]. 
A[q] disebut sebagai elemen pivot. Perhitungan pada elemen q merupakan 
salah satu bagian dari prosedur pemisahan.

**-Conquer**
Mengurutkan elemen pada sub-rangkaian secara rekursif. 
Pada algoritma quicksort, langkah ”kombinasi” tidak di lakukan karena telah terjadi 
pengurutan elemen – elemen pada sub-array.

### Shell sort
Prinsipnya hampir sama dengan Bubble Sort tetapi ditambahkan optmisisasi sehingga proses menjadi lebih cepat.
Ditemukan oleh Donald Shell. prinsipnya adalah membandingkan data dengan jarak tertentu dalam array.
dimana pada setiap nilai i dalam n/i item diurutkan. Pada setiap pergantian nilai, 
i dikurangi sampai 1 sebagai nilai terakhir.

### Selection Sort
Ide utama dari algoritma selection sort adalah memilih elemen dengan nilai paling rendah dan menukar elemen 
yang terpilih dengan elemen ke-i. Nilai dari i dimulai dari 1 ke n, dimana n adalah jumlah total elemen dikurangi 1.

### Insert Sort
Algoritma insertion sort pada dasarnya memilah data yang akan diurutkan menjadi dua bagian,
yang belum diurutkan dan yang sudah diurutkan. Elemen pertama diambil dari bagian array yang 
belum diurutkan dan kemudian diletakkan sesuai posisinya pada bagian lain dari array yang telah diurutkan. 
Langkah ini dilakukan secara berulang hingga tidak ada lagi elemen yang tersisa pada bagian array yang belum diurutkan.

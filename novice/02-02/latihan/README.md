# Memulai Unit Testting di Python

Testting/Pengujian pada bahasa Python adalah topik yang luas dan banyak
melibatkan Kompleksitas Algoritma. kita bisa membuat unittest sederhana atau
simple unittest dengan beberapa langkah yang akan kita bahas. Pada Bahasan kali
ini kita akan belajar membuat unittest sederhana, eksekusi unittest, dan menemukan
bug sebelum user menemukannya, menggecek performa aplikasi kita bahkan masalah
keamanan bisa kita temukan di sini.

### Manual Testting Vs Automated Testting

Mungkin ada yang masih belum mengetahui apa itu Manual testing dan Automated
Testing. Saya juga masih belajar untuk lebih mengenal lagi mengenai manual
Testing dan Automated Testing, karena jika kita ingin menjadi QA Tester yang
baik setidaknya kita mengerti pengertian dan perbedaan dari masing-masing
testing tersebut karena kedua testing tersebut memberikan manfaat dan kelemahan
tersendiri. Jadi ada sebaiknya kita mengetahui perbedaan dan kapan harus
menggunakan salah satunya untuk mendapatkan hasil yang diinginkan, alangkah
baiknya kita terlebih dahulu mencari tahu apa itu
Manual testing dan Automated Testing.

#### Manual Testting

Manual Testing atau pengujian manual adalah langkah untuk mencari cacat atau
bug pada program perangkat lunak, pada metode ini tester/penguji memiliki peran
penting sebagai pengguna akhir untuk pengecekan semua fitur aplikasi bekerja
dengan benar. Penguji melakukan pengecekan secara manual tanpa menggunakan
bantuan dari tools atau scripts, tujuannya adalah untuk memastikan jika aplikasi
yang di uji bebas cacat dan aplikasi perangkat lunak dapat bekerja sesuai apa
yang diharapkan. Manual testing juga berperan penting saat pengujian visual
dimana automation tools tidak dapat melakukan. Manual testing biasanya diterapkan
dalam dunia UI dan UX, UX dan UI feedback adalah hal yang tidak dapat ditemukan
menggunakan automated testing.

#### Automated Testting

Bergantung pada pra-scripted tes yang berjalan secara otomatis, fungsinya untuk
membandingkan hasil yang diharapkan dengan hasil yang sebenarnya. Sehingga dapat
mengetahui apakah aplikasi berjalan sesuai dengan apa yang diharapkan,
menggunakan automated testing dapat dilakukan secara berulang. Sehingga jika
hasilnya tidak sama dengan yang diharapkan maka akan mendapatkan bug.

### unittest vs Integration Tests

Dunia pengujian/Testing tidak memiliki kekurangan terminologi, dan sekarang
kita tahu perbedaan antara pengujian otomatis dan manual, saatnya untuk naik
ke level yang lebih dalam. Sekarang bayangkan bagaimana kita bisa menguji
lampu pada mobil. Kita akan menyalakan lampu (dikenal sebagai langkah uji)
dan pergi ke luar mobil atau meminta teman untuk memeriksa bahwa lampu menyala
(dikenal sebagai pernyataan uji). Pengujian beberapa komponen dikenal sebagai
pengujian integrasi/Integration Test.


Tantangan utama dengan pengujian integrasi adalah ketika tes integrasi tidak
memberikan hasil yang tepat. Sangat sulit untuk mendiagnosis masalah tanpa dapat
mengisolasi bagian mana dari sistem yang gagal. Pada Kasus mobil tadi Jika lampu
tidak menyala, maka mungkin bohlamnya rusak. Apakah baterainya mati?
Bagaimana dengan alternator? Apakah komputer mobil rusak?

Unit Tes adalah tes yang lebih kecil, yang memeriksa apakah satu komponen
beroperasi dengan cara yang benar. Tes unit membantu Anda mengisolasi apa
yang error dalam aplikasi Anda dan memperbaikinya lebih cepat.

### Memilih tools untuk Pengujian/Testting
Ada banyak unittest dalam Python namun hanya beberapa yang popular yaitu:
1. unittest (Merupakan Library default pada Python)
2. nose / nose2
3. pytest

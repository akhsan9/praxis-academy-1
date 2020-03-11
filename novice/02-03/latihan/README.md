# Meningkatkan Performa Program Python dengan Concurrency

### Apa itu Concurrency

Berdasarkan Definisi kamus konkurensi adalah kejadian yang terjadi secara
simultan (bersamaan). Dalam Python, hal-hal yang terjadi secara bersamaan disebut dengan nama yang berbeda (thread, task, process) tetapi pada proses yang lebih
lanjut, semuanya merujuk pada urutan instruksi yang dijalankan secara berurutan.
Masing-masing dapat dihentikan pada titik-titik tertentu, dan CPU yang memprosesnya
dapat beralih ke yang berbeda. Status masing-masing disimpan sehingga dapat dimulai
kembali tepat di tempat ia terputus. Seperti halnya kita pada saat melakukan
pengunduhan/download file menggunakan download manager, File berukuran tertentu
dipecah-pecah menjadi beberapa file kemudian di unduh secara bersamaan.


### Kapan kita menggunakan Concurrency

Concurrency bisa membuat perbedaan yang signifikan terhadap dua proses yang
sedang berjalan CPU-bound dan I/O-bound. Masalah I/O bound menyebabkan program
berjalan lambat karena sering harus menunggu input/output (I/O) dari beberapa
sumber daya eksternal. Mereka sering muncul ketika program bekerja dengan
hal-hal yang jauh lebih lambat daripada CPU.

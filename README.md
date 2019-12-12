# belajar-algoritma-dan-data-struktur

Kompleksitas atau big-O pada array untuk perintah-perintah dasar seperti read, search, insert, dan delete.

Definisi:
- Big-O adalah ukuran yang mengatakan berapa banyak step yang diperlukan komputer untuk melakukan suatu pekerjaan.
- array adalah sebuah struktur data yang memungkinkan kita menyimpan data, dianalogikan dalam bentuk seperti rak sepatu.
Dimana satu ruang hanya dapat digunakan untuk menyimpan 1 item, dan item pertama yang kita simpan akan disimpan dalam rak index ke-0, dst.

[x] Perintah read: perintah read memiliki nilai big-O 1, karena saat read komputer sudah tau index dari item yang mau kita read.
[x] Perintah search: perintah search memiliki nilai big-O N, karena saat search komputer akan mengecek 1-per-1 dari semua item yang ada pada array.
Jika item yang dicari ada pada array index terakhir maka akan butuh N, panjang array, step untuk melakukan pencarian tersebut.
[x] Perintah 
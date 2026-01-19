# yusuftodolist  
### Penjelasan Singkat Proyek
Proyek ini adalah aplikasi web sederhana berbasis HTML untuk membuat daftar tugas harian (To Do List). Pengguna dapat menambahkan tugas melalui input teks dan tombol, yang kemudian ditampilkan dalam daftar. Kode HTML menyediakan struktur dasar, dengan referensi ke file CSS (styles.css) untuk styling dan JavaScript (script.js) untuk fungsionalitas interaktif seperti menambah, menghapus, atau menandai tugas selesai. 

### Alur Logika/Algoritma
Alur kerja aplikasi ini didasarkan pada interaksi pengguna melalui JavaScript (diasumsikan dari script.js, karena tidak disediakan di sini). Berikut adalah algoritma dasar langkah demi langkah:

1. inisialisai : Saat halaman dimuat, elemen HTML (input, tombol, dan ul) diidentifikasi menggunakan DOM (Document Object Model) di JavaScript.

2. Input Tugas : Pengguna mengetik tugas di input teks (`#taskInput`).

3. Penambahan Tugas:
   - Ketika tombol "Add Task" (`#tasklist`) diklik, JavaScript memeriksa apakah input tidak kosong.
   - Jika valid, buat elemen `<li>` baru dengan teks dari input.
   - Tambahkan `<li>` ke dalam `<ul id="taskList">`.
   - Kosongkan input untuk tugas berikutnya.

4. Manajemen Tugas (diasumsikan di script.js, karena tidak terlihat di HTML):
   - Untuk setiap `<li>`, tambahkan tombol atau checkbox (misalnya, untuk menghapus atau menandai selesai).
   - Jika tombol hapus diklik, hapus `<li>` dari DOM.
   - Jika checkbox dicentang, tambahkan styling (misalnya, coret teks) untuk menunjukkan tugas selesai.


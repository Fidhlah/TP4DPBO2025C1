# Janji
Saya Muhammad Hafidh Fadhilah dengan NIM 2305672 mengerjakan Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program
Program ini menggunakan 3 file utama, yaitu `Mahasiswa.java`, `Menu.java`, dan `Menu.form`.
1. Mahasiswa.java
   class ini berisi data mahasiswa. Terdapat 4 atribut yaitu `nim`, `nama`, `jenisKelamin`, dan satu atribut yang saya tambahkan yaitu `transportasi`. Terdapat method setter 
   dan getter untuk setiap atributnya
2. Menu.java
   class ini berisi program GUI dibuat menggunakan Java swing. Disini terdapat method untuk add, update, dan delete data mahasiswa.
3. Menu.form
   File ini berisi konfigurasi tata letak komponen GUI yang nanti akan tampil saat program dijalankan.
   ![Screenshot 2025-03-22 085617](https://github.com/user-attachments/assets/0ca3ec8a-2bb2-4228-9aee-93646ef938a8)

# Alur program
1. Inisialisasi Program
   - Program dijalankan melalui Menu.java.
   - Window utama dibuat menggunakan JFrame dengan ukuran 600x560 px.
   - Data awal mahasiswa dimuat ke dalam ArrayList yang berisi objek Mahasiswa.
3. Tampilan UI (User Interface)
   Di dalam JFrame, ada beberapa komponen penting:
   - Tabel Mahasiswa (JTable) → Menampilkan daftar mahasiswa.
   - Input Form → Berisi:
      - JTextField nimField → Input NIM mahasiswa.
      - JTextField namaField → Input nama mahasiswa.
      - JComboBox jenisKelaminComboBox → Pilih jenis kelamin.
      - JComboBox transportasiComboBox → Pilih transportasi ke kampus.
   - Tombol Aksi:
      - Add / Update → Menambahkan atau mengubah data mahasiswa.
      - Delete → Menghapus data mahasiswa dari tabel.
      - Cancel → Mengosongkan form input.
3. Proses CRUD (Create, Read, Update, Delete)
   a. Menambah Data Mahasiswa
      - Pengguna mengisi NIM, Nama, Jenis Kelamin, Transportasi di form.
      - Klik tombol "Add", data baru disimpan ke ArrayList listMahasiswa.
      - Tabel diperbarui agar data baru muncul.
   b. Mengupdate Data Mahasiswa
      - Klik salah satu baris di tabel → Data akan muncul di form input.
      - Tombol "Add" berubah menjadi "Update".
      - Pengguna mengubah data, lalu klik "Update".
      - Data di ArrayList diperbarui dan tabel di-refresh.
   c. Menghapus Data Mahasiswa
      - Klik salah satu baris di tabel.
      - Tombol "Delete" akan muncul.
      - Klik "Delete", lalu konfirmasi penghapusan.
      - Data dihapus dari ArrayList, dan tabel diperbarui.
4. Penyimpanan Data
   - Saat program berjalan, data mahasiswa disimpan dalam ArrayList.
   - Data tidak akan tersimpan permanen karena belum menggunakan database atau file eksternal.

# Dokumentasi Output
https://github.com/user-attachments/assets/451a5020-85b5-4ee8-bfd3-45dbfd290df2


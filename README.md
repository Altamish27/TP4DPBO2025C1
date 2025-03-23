##Saya Hasbi Haqqul Fikri dengan NIM 2309245 mengerjakan soal TP 4 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.


# Aplikasi Manajemen Data Mahasiswa

## Deskripsi
Aplikasi ini adalah sebuah program berbasis Java Swing yang digunakan untuk mengelola data mahasiswa. Pengguna dapat menambahkan, mengedit, dan menghapus data mahasiswa yang mencakup NIM, Nama, Jenis Kelamin, dan Wali Dosen (Waldos). Program ini menampilkan daftar mahasiswa dalam JTable serta menyediakan berbagai komponen UI seperti JTextField, JComboBox, dan JButton untuk interaksi pengguna.

## Fitur Utama
- **Menampilkan daftar mahasiswa** dalam bentuk tabel.
- **Menambahkan data mahasiswa** dengan input NIM, Nama, Jenis Kelamin, dan Wali Dosen.
- **Mengedit data mahasiswa** yang sudah ada dengan mudah.
- **Menghapus data mahasiswa** dengan konfirmasi sebelum penghapusan.
- **Menggunakan JComboBox** untuk memilih Jenis Kelamin dan Wali Dosen agar input lebih konsisten.

## Desain Program
Program ini menggunakan **Java Swing** dan **DefaultTableModel** untuk memanipulasi data dalam JTable. Data mahasiswa disimpan dalam **ArrayList** yang kemudian digunakan untuk mengisi tabel.

## Alur Program
### 1. Inisialisasi Data
- Data awal mahasiswa diinisialisasi dalam bentuk `ArrayList<Mahasiswa>`.
- Data ditampilkan dalam tabel (`JTable`) menggunakan `DefaultTableModel`.

### 2. Pengguna Menambah Data
- Pengguna mengisi **NIM**, **Nama**, memilih **Jenis Kelamin**, dan **Wali Dosen** dari `JComboBox`.
- Ketika tombol **Add** ditekan, data baru ditambahkan ke dalam `ArrayList` dan tabel diperbarui.

### 3. Pengguna Mengedit Data
- Pengguna mengklik salah satu baris di tabel, lalu data tersebut ditampilkan kembali di input form.
- Jika tombol **Update** ditekan, data dalam `ArrayList` diperbarui dan tabel diperbarui.

### 4. Pengguna Menghapus Data
- Setelah memilih data dalam tabel, pengguna dapat menekan tombol **Delete** untuk menghapus data.
- Program akan meminta konfirmasi sebelum menghapus.

## Penambahan Atribut Waldos
### 1. Menambahkan Atribut pada Mahasiswa
- Atribut **Waldos** ditambahkan ke dalam objek `Mahasiswa`, yang berisi nama Wali Dosen.

### 2. Menampilkan Waldos dalam Form Input
- `JComboBox` digunakan untuk menampilkan daftar Wali Dosen agar pengguna bisa memilih salah satu.
- Data Wali Dosen diinisialisasi dalam bentuk array yang kemudian dimasukkan ke dalam `JComboBox`.

### 3. Menyimpan dan Menampilkan Waldos di Tabel
- Saat pengguna menambah atau mengedit data, pilihan **Waldos** dari `JComboBox` akan disimpan dalam `ArrayList<Mahasiswa>`.
- Nilai **Waldos** akan ditampilkan dalam tabel sebagai salah satu kolom.

![image](https://github.com/user-attachments/assets/ce59deb3-01ae-48d0-b823-567cf4dd13a1)



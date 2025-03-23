

Desain Program
Program ini adalah aplikasi GUI berbasis Java Swing untuk mengelola data mahasiswa. Aplikasi ini memungkinkan pengguna untuk menambah, mengedit, dan menghapus data mahasiswa, termasuk atribut NIM, Nama, Jenis Kelamin, dan Wali Dosen (Waldos).

Program menggunakan JTable untuk menampilkan daftar mahasiswa, serta beberapa komponen UI seperti JTextField, JComboBox, dan JButton untuk interaksi pengguna.

Alur Program
Inisialisasi Data

Data awal mahasiswa diinisialisasi dalam bentuk ArrayList<Mahasiswa>.

Data ditampilkan dalam tabel (JTable) menggunakan DefaultTableModel.

Pengguna Menambah Data

Pengguna mengisi NIM, Nama, memilih Jenis Kelamin, dan Wali Dosen dari JComboBox.

Ketika tombol Add ditekan, data baru ditambahkan ke dalam ArrayList dan tabel diperbarui.

Pengguna Mengedit Data

Pengguna mengklik salah satu baris di tabel, lalu data tersebut ditampilkan kembali di input form.

Jika tombol Update ditekan, data dalam ArrayList diperbarui dan tabel diperbarui.

Pengguna Menghapus Data

Setelah memilih data dalam tabel, pengguna dapat menekan tombol Delete untuk menghapus data.

Program akan meminta konfirmasi sebelum menghapus.

Penambahan Atribut Waldos
Menambahkan Atribut pada Mahasiswa

Atribut Waldos ditambahkan ke dalam objek Mahasiswa, yang berisi nama Wali Dosen.

Menampilkan Waldos dalam Form Input

JComboBox digunakan untuk menampilkan daftar Wali Dosen agar pengguna bisa memilih salah satu.

Data Wali Dosen diinisialisasi dalam bentuk array yang kemudian dimasukkan ke dalam JComboBox.

Menyimpan dan Menampilkan Waldos di Tabel

Saat pengguna menambah atau mengedit data, pilihan Waldos dari JComboBox akan disimpan dalam ArrayList<Mahasiswa>.

Nilai Waldos akan ditampilkan dalam tabel sebagai salah satu kolom.

Kesimpulan
Penambahan atribut Waldos memungkinkan pengguna untuk memilih Wali Dosen dari daftar yang tersedia menggunakan JComboBox. Ini mempermudah pengguna dalam memasukkan data tanpa perlu mengetik manual, serta menjaga konsistensi data.

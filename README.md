# Aplikasi Penambahan Dua Angka
 Aplikasi ini memungkinkan pengguna untuk memasukkan dua angka dan menampilkan hasil penjumlahannya. Selain itu, terdapat opsi untuk menghapus input atau keluar dari aplikasi.

 ## Identitas
 - Nama : Addin Husnan Nadhari
 - Kelas : 5B Nonreg Banjarmasin
 - Npm : 2210010037

## Fitur

- **Penjumlahan Dua Angka**: Pengguna dapat memasukkan dua angka dalam kolom input, kemudian mengklik tombol "Tambah" untuk melihat hasil penjumlahannya.
- **Validasi Input**: Hanya angka yang dapat dimasukkan pada kolom input. Jika pengguna memasukkan nilai non-numerik, aplikasi akan menampilkan pesan kesalahan.
- **Tombol Hapus**: Menghapus input dari kedua kolom angka dan kolom hasil.
- **Tombol Keluar**: Menutup aplikasi.

## Struktur Program

Kelas utama `PenambahanDuaAngka` berfungsi sebagai JFrame untuk antarmuka pengguna. Program ini menggunakan beberapa elemen GUI:
- **JLabel**: Menampilkan label untuk "Angka Pertama", "Angka Kedua", dan "Hasil".
- **JTextField**: Kolom input untuk angka pertama, angka kedua, dan kolom untuk hasil penjumlahan.
- **JButton**: Terdapat tiga tombol:
  - **Tambah**: Melakukan operasi penjumlahan.
  - **Hapus**: Menghapus semua input.
  - **Keluar**: Menutup aplikasi.

## Cara Menjalankan Program

1. Buka project ini di lingkungan pengembangan Java, seperti NetBeans atau IntelliJ IDEA.
2. Jalankan kelas `PenambahanDuaAngka` sebagai aplikasi Java.
3. Masukkan dua angka pada kolom input dan tekan tombol "Tambah" untuk melihat hasilnya.
4. Gunakan tombol "Hapus" untuk mengosongkan kolom input atau tombol "Keluar" untuk menutup aplikasi.

## Catatan

- Program ini hanya mendukung input numerik (angka) untuk operasi penjumlahan.
- Jika pengguna memasukkan karakter non-numerik, aplikasi akan menampilkan pesan kesalahan.


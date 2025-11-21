# Flutter Note App (SQLite)

Aplikasi catatan sederhana yang dibangun menggunakan **Flutter** dan **SQLite** sebagai penyimpanan lokal (*local storage*). Proyek ini dibuat untuk mendemonstrasikan implementasi operasi **CRUD** (Create, Read, Update, Delete) pada aplikasi mobile.

## 📱 Fitur Utama

* **Tambah Catatan:** Membuat catatan baru dengan judul dan isi.
* **Lihat Catatan:** Menampilkan daftar semua catatan yang tersimpan (diurutkan berdasarkan pin dan tanggal).
* **Edit Catatan:** Mengubah isi catatan yang sudah ada.
* **Hapus Catatan:** Menghapus catatan yang tidak diperlukan.
* **Penyimpanan Offline:** Data tersimpan aman di perangkat menggunakan SQLite, sehingga tidak hilang saat aplikasi ditutup.

## 🛠️ Teknologi yang Digunakan

* [Flutter](https://flutter.dev/) - Framework UI.
* [Dart](https://dart.dev/) - Bahasa pemrograman.
* [sqflite](https://pub.dev/packages/sqflite) - Plugin SQLite untuk Flutter.
* [path](https://pub.dev/packages/path) - Helper untuk memanipulasi path file sistem.

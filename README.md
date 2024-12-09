# Tugas Praktikum

## Deskripsi

Tugas praktikum ini bertujuan untuk membuat program sederhana menggunakan class dan metode dalam Python.

## Diagram class

! [](lib/img/mahasiswa.png)

## Flowchart

! []()

## Fitur

- `tambah(nama)`: Menambahkan data mahasiswa baru ke dalam daftar.
- `tampilkan()`: Menampilkan daftar mahasiswa yang telah ditambahkan.
- `hapus(nama)`: Menghapus data mahasiswa berdasarkan nama.
- `ubah(nama_lama, nama_baru)`: Mengubah data mahasiswa dari nama lama menjadi nama baru.

## Penggunaan

1. Buat objek `Mahasiswa`.
2. Panggil metode-metode yang tersedia, seperti `tambah()`, `tampilkan()`, `hapus()`, dan `ubah()`.
3. Ikuti alur pada flowchart untuk memahami operasi yang tersedia.

Contoh penggunaan:

```python
mahasiswa = Mahasiswa()
mahasiswa.tambah("John Doe")
mahasiswa.tambah("Jane Smith")
mahasiswa.tampilkan()
mahasiswa.hapus("Jane Smith")
mahasiswa.ubah("John Doe", "John Wick")
mahasiswa.tampilkan()
```

## Flowchart

Silakan lihat flowchart terpisah untuk memahami alur program.

## Struktur Proyek

Proyek ini terdiri dari:

- `Mahasiswa.py`: Berisi implementasi kelas `Mahasiswa` dan metode-metodenya.
- `README.md`: Dokumentasi proyek yang Anda sedang baca.
- `tugas-praktikum-flowchart.svg`: Flowchart visualisasi program.

## Kontribusi

Proyek ini dibuat untuk memenuhi tugas praktikum. Jika Anda menemukan bug atau memiliki saran perbaikan, silakan buat issue atau pull request di repositori ini.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

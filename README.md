# uts_pemograman_mobile2

Nama : Bagus Sanjaya

NIM : 312410505

Kelas : I241E

## 1. Menentukan Ide Aplikasi

Pada tahap awal dilakukan brainstorming ide aplikasi yang akan dibuat.

`My Library = aplikasi manajemen buku pribadi berbasis Android.`

### Fitur utama yang direncanakan:

- Tambah/edit buku
- Hapus buku
- Cari buku
- Filter status baca
- Detail buku
- Statistik buku
- Chat AI rekomendasi buku

## 2. Storyboard Alur Aplikasi

Membuat storyboard untuk menggambarkan alur pengguna.

!gambar

### Storyboard User Flow:

1. Splash Screen

2. Welcome Screen

3. Main Menu / Dashboard

4. Tambah / edit Buku

5. Detail Buku

6. Hapus Buku

7. Chat AI Buku

8. Statistik Buku

## 3. UI/UX Design

### Wireframe Kasar(Figma)

!gambar

Membuat rancangan kasar layout:

Halaman:
- Splash Screen
- Welcome
- Dashboard
- Add Book
- Chat AI
- Statistik

link figma

### Prototype UX

!gambar

Menentukan interaksi user:

- Klik tombol tambah buku
- Klik menu 
- Chat dengan AI
- Scroll list buku
- Search buku
- Statistik

link youtube

## 4. Implementasi Android Studio

### Setup Project Android Studio

Membuat project baru:

`MyLibrary`

Menggunakan:

- Java
- SQLite
- RecyclerView
- Material Design

### Buat Tampilannya

1. Splash Screen & Welcome Screen

Saat aplikasi dibuka menampilkan logo dan halaman sambutan.

2. Main Dashboard

- Header logo
- Search buku
- Tab filter:
- Semua
  - Belum Dibaca
  -  Sedang Dibaca
  -   Sudah Dibaca
- RecyclerView daftar buku
- FAB tambah buku

4. Database SQLite

Membuat:

` DatabaseHelper.java `

Tabel buku:

- id
- judul
- penulis
- halaman
- status
- catatan

Fungsi CRUD:

- Insert buku
- Ambil semua buku
- Filter status
- Detail buku

5. Search Buku

Menambahkan fitur pencarian buku berdasarkan:

- Judul
- Penulis
  
6. Detail Buku

Saat item buku diklik membuka:

`DetailBookActivity`

Menampilkan:

- Judul
- Penulis
- Status baca
- Halaman
- Catatan

7. Chat AI Buku

Menambahkan menu titik 3 di pojok kanan atas.

Isi menu:

- Chat AI Buku
- Statistik Buku

**Chat AI berfungsi:**

User bertanya:

- rekomendasi novel
- buku motivasi
- buku misteri

AI menjawab otomatis.

8. Statistik

Membuat:

`StatistikActivity`

Menampilkan:

- Total buku
- Belum dibaca
- Sedang dibaca
- Selesai dibaca


# Bookshelf API

Aplikasi API sederhana untuk mengelola perpustakaan buku. Dengan API ini, Anda dapat menyimpan, menampilkan, mengubah, dan menghapus data buku.

## Penggunaan

1. Pastikan Anda telah menginstal [Node.js](https://nodejs.org) di sistem Anda.
2. Clone repositori ini ke lokal Anda dengan perintah: `git clone https://github.com/prabusemar/bookshelf-api.git`
3. Masuk ke direktori repositori: `cd repo-bookshelf-api`
4. Instal dependensi yang diperlukan: `npm install`
5. Jalankan aplikasi dengan perintah: `npm run start`
6. Akses API melalui URL: `http://localhost:9000`

## Endpoint

- GET /books: Mendapatkan seluruh buku dalam perpustakaan.
- GET /books/:id: Mendapatkan detail buku berdasarkan ID.
- POST /books: Menyimpan buku baru ke dalam perpustakaan.
- PUT /books/:id: Mengubah data buku berdasarkan ID.
- DELETE /books/:id: Menghapus buku dari perpustakaan berdasarkan ID.

Pastikan untuk mengganti ":id" dengan ID yang valid saat menggunakan endpoint tertentu.

## Kontribusi

Kontribusi selalu diterima! Jika Anda ingin memperbaiki bug atau menambahkan fitur baru, silakan buat *Pull Request* ke repositori ini.

## Lisensi

Repositori ini dilisensikan di bawah [MIT License](LICENSE).

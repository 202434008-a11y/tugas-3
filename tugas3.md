# Laporan Praktikum Minggu 3 — Draft API Contract

## 1. Tujuan
Menerapkan rancangan API contract dan pemodelan resource pada project semester, serta mensimulasikan respon sukses dan eror menggunakan Postman.

## 2. Perubahan
- Menambahkan dokumentasi API contract untuk resource utama project.
- Mengklasifikasikan field read-only dan field yang wajib diisi.
- Menyusun contoh respon sukses (200 OK, 201 Created) dan eror (404 Not Found, 422 Validation Error).
- Memperbarui Postman Collection dengan contoh respon (examples).

## 3. Endpoint atau Contract
- **GET /api/books**: Mengambil daftar seluruh buku (`200 OK`).
- **POST /api/books**: Menambahkan buku baru (`201 Created`).
- **GET /api/books/{id}`**: Mengambil detail buku (`200 OK` / `404 Not Found`).
- **Eror Validasi**: Mengembalikan status `422 Unprocessable Content` saat input salah atau kosong.

## 4. Bukti Pengujian
    foto dilampirkan di file unggahan 

## 5. Error Case
*(Lampirkan screenshot respon 404 Not Found dan 422 Validation Error di sini)*

## 6. Kesimpulan
Perancangan API contract sebelum penulisan kode sangat penting untuk menjaga konsistensi format data antara server dan aplikasi client. Penggunaan status code HTTP yang tepat serta pembungkusan data yang rapi memudahkan integrasi dan mencegah kesalahan ekstraksi data di sisi client.

## 7. Referensi
- Dokumentasi Resmi Laravel Eloquent Resources: https://laravel.com/docs/eloquent-resources
- RESTful API Design Best Practices.

## 8. Deklarasi Penggunaan AI
 AI untuk penyusunan struktur dokumen, format JSON, dan penyederhanaan penjelasan teknis tanpa menyertakan kredensial rahasia.
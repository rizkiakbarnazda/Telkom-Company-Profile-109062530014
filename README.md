# Telkom University Company Profile - Praktikum
Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git.

Perubahan ini dibuat dari simulasi Laptop B

## Penyelesaian Merge Conflict
Merge conflict terjadi pada berkas `includes/header.php` ketika dua branch (`main` dan `conflict-navbar`) mengubah baris kode yang sama (yaitu label menu navigasi profil) secara bersamaan tanpa sinkronisasi. Cara menyelesaikannya adalah dengan membuka file tersebut di VS Code, menghapus marker konflik (seperti `<<<<<<<`, `=======`, dan `>>>>>>>`), memilih teks kode final yang benar (misalnya teks menu yang diinginkan), lalu melakukan staging dengan perintah `git add includes/header.php` dan melanjutkan proses commit.

## Riwayat Praktikum Git
* 117438C (HEAD -> main, tag: v1.0.0, origin/main, origin/HEAD) fix: simpan perubahan contact
* 2dd9994 Revert "docs: uji coba dari laptop a"
* c6f0568 merge: selesaikan konflik readme
* d1e51f3 docs: uji coba push ditolak dari laptop b
* c8aac70 docs: uji coba dari laptop a
* d305a62 docs: perbarui README dari Laptop B
* e3e4f96 merge: selesaikan conflict navbar
* 270dc87 (conflict-navbar) feat: ubah label profil pada branch conflict
* a93144f style: ubah label profil pada main
* eec2c03 feat: tambahkan informasi fokus pembelajaran
* b0e04e9 feat: tambahkan form admin lokal untuk berita
* a0396ec feat: simpan pesan kontak ke database
* 24c9510 feat: tambahkan daftar dan detail berita
* 6a3e78e feat: hubungkan database dan tampilkan program studi
* 5d48fb1 feat: tambahkan layout dasar dan stylesheet
* 3a47c7d chore: inisialisasi project dan dokumentasi awal
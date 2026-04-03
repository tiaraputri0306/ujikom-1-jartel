## Prosedur Pembuatan dan Pengelolaan Branch Repository

### 1. Membuat Branch Baru

Pada antarmuka repository GitHub, klik tombol **New branch** yang terletak di pojok kanan atas halaman.

![alt text](<img/Screenshot From 2026-04-03 13-33-20.png>)

Buat branch baru dengan nama dan NIM masing-masing.

![alt text](<img/Screenshot From 2026-04-03 13-17-08.png>)

### 2. Kloning Repository ke Lingkungan Lokal

Jalankan perintah berikut pada terminal untuk mengkloning repository ke direktori lokal:

```bash
git clone https://github.com/ricalnet/ujikom-1-jartel.git
```

### 3. Berpindah ke Branch Baru

Masuk ke direktori hasil kloning, lalu jalankan perintah berikut untuk berpindah ke branch yang telah dibuat:

```bash
git checkout nama-nim
```

**Contoh output:**

```
branch 'nama-nim' set up to track 'origin/nama-nim'.
Switched to a new branch 'nama-nim'
```

> **Catatan:** Gantilah `nama-nim` dengan nama branch sesuai nama dan NIM masing-masing.

### 4. Menambahkan Dokumentasi dan Push ke Branch

Tambahkan seluruh file dokumentasi yang telah disiapkan ke dalam direktori kerja, kemudian lakukan push ke branch `nama-nim` dengan perintah berikut:

```bash
git init
git add .
git commit -m "dokumentasi asterisk milik nama Anda"
git branch -M nama-nim
git push -u origin nama-nim
```

Setelah perintah berhasil dijalankan, sistem akan menampilkan konfirmasi keberhasilan push.

### 5. Verifikasi Hasil

Berikut adalah tampilan branch utama (`main`) milik asisten:

![alt text](<img/Screenshot From 2026-04-03 13-27-12.png>)

Berikut adalah tampilan branch `nama-nim` milik peserta:

![alt text](<img/Screenshot From 2026-04-03 13-26-10.png>)

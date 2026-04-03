# Uji Kompetensi 1 - Jaringan Telekomunikasi

**Petunjuk Umum:**  
Kerjakan kedua soal berikut secara berurutan. Pastikan semua langkah terdokumentasi dengan baik dan dapat direproduksi.

---

## Soal 1: Konfigurasi Server VoIP (Asterisk on Ubuntu)

### Tujuan
Membangun server VoIP sederhana menggunakan **Asterisk** pada sistem operasi **Ubuntu**, serta menguji koneksi antar extension menggunakan klien **Zoiper**.

### Langkah yang Harus Dilakukan
1. Install dan konfigurasi Asterisk pada Ubuntu.
2. Tambahkan **user/extension** dengan ketentuan berikut:
   - **Username:** Nama lengkap atau nama panggilan (sesuai kebijakan asisten)
   - **Extension (Nomor internal):** empat digit terakhir NIM (contoh: jika NIM = 607052300001, maka extension = `0001`)

### Kriteria Pengujian
- Masing-masing extension berhasil melakukan registrasi ke server Asterisk.
- Panggilan antar extension berhasil dilakukan menggunakan aplikasi **Zoiper**.

### Tentang Asterisk
Asterisk adalah Private Branch Exchange (PBX) open-source yang memungkinkan pengelolaan panggilan VoIP. Penambahan extension dilakukan melalui file konfigurasi seperti `sip.conf` (chan_sip) atau `pjsip.conf` (chan_pjsip). Zoiper berperan sebagai User Agent untuk meregistrasi dan melakukan panggilan.

---

## Soal 2: Dokumentasi & Manajemen Kode dengan Git

### Tujuan
Mendokumentasikan seluruh proses pengerjaan Soal 1 dan mengelola versi dokumentasi tersebut menggunakan Git.

### Langkah yang Harus Dilakukan
1. Buat dokumentasi teknis untuk **Soal 1**, mencakup:
   - Langkah instalasi Asterisk
   - Konfigurasi extension (nama & NIM)
   - Proses pengujian dengan Zoiper (sertakan tangkapan layar)
   - Kesimpulan atau kendala yang dihadapi

2. Simpan dokumentasi tersebut dalam file **`README.md`** di root folder proyek.

3. **Push** ke repositori yang telah ditentukan dengan [aturan branching berikut](https://github.com/ricalnet/ujikom-1-jartel/tree/nama-nim):
   - Setiap peserta membuat **branch baru** dari branch utama (misal: `main` atau `master`).
   - Format nama branch: `nama-nim`
     - Contoh: `naufal-0001`, `rical-0002`, `nasywa-0003`

### Tentang Git
Git memungkinkan pelacakan perubahan dokumen secara kolaboratif. Dengan membuat branch terpisah (`nama-nim`), setiap peserta bekerja secara independen tanpa mengganggu pekerjaan orang lain. `README.md` adalah standar dokumentasi proyek di platform seperti GitHub/GitLab. 

---

## Kriteria Penilaian
| Aspek | Bobot |
|-------|-------|
| Keberhasilan konfigurasi Asterisk | |
| Pengujian dengan Zoiper (registrasi & panggilan) | |
| Kelengkapan dokumentasi di README.md | |
| Manajemen branch dan push ke repositori | |

**Selamat mengerjakan!**
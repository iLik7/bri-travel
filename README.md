# Website Barokah Ridho Ilahi

Landing page travel Umroh & Haji PT. Barokah Ridho Ilahi, Surabaya. Dibangun dengan HTML + Jekyll, di-host gratis di GitHub Pages.

## Cara edit paket, foto, testimoni, dan kontak (tanpa ngoding)

1. Buka https://app.pagescms.org lalu login pakai akun GitHub.
2. Pilih repo website ini.
3. Di menu kiri pilih yang mau diubah: **Paket Umroh**, **Testimoni Jamaah**, **Ustadz & Tim**, atau **Info Umum, Kontak & Foto Utama**.
4. Ubah isinya (upload foto baru, ganti fasilitas, isi harga, dll), lalu klik **Save**.
5. Tunggu sekitar 1–2 menit, website otomatis ter-update.

Tips:
- Paket yang sudah tidak dijual: matikan centang **Tampilkan di website** (tidak perlu dihapus).
- Harga dan tanggal keberangkatan boleh dikosongkan; kalau kosong tidak muncul di website.
- Foto sebaiknya JPG, ukuran di bawah 1 MB biar website tetap cepat.

## Struktur file
- `index.html` — tampilan halaman.
- `assets/style.css` — warna & tata letak.
- `_data/*.yml` — isi yang bisa diedit (paket, testimoni, tim, kontak).
- `images/` — semua foto.
- `.pages.yml` — pengaturan form Pages CMS.

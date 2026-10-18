# SENDJA TRIP — Nawak Jadoel (Jelajah Malang Tempo Doeloe)

Versi Malang dari prototipe SENDJA TRIP. Cara jalan & deploy sama seperti versi Madura.

## Edit cepat
- `js/data.js`: destinasi, koordinat, paket/harga, rundown, reward, WhatsApp, sosmed, email admin.
- Warna: baris `:root` paling atas di `css/style.css`.
- Foto: taruh di `img/` (hero: `img/hero.jpg`), isi field `img` tiap destinasi.

## Batasan
- Data disimpan di localStorage (DEMO), kunci diberi awalan `mlg_` agar tidak bentrok dengan situs Madura di akun GitHub yang sama.
- Koordinat = perkiraan, lokasi pusat oleh-oleh belum ditentukan. Harga, kuota, jadwal tanggal = contoh.
- Teks sejarah masih placeholder. Backend nyata (Supabase) belum ada.

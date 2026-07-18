# TKA English - Sanggar Mam Is

Isi paket:
- `index.html`: aplikasi utama.
- `data/packages.json`: 20 paket x 30 soal.
- `pdf/kelas-9`: 10 PDF soal kelas 9.
- `pdf/kelas-12`: 10 PDF soal kelas 12.
- `assets/logo-mam-is.svg`: logo bawaan yang dapat diganti.

## Cara memasang di GitHub Pages
1. Ekstrak seluruh isi ZIP.
2. Unggah semua file dan folder ke repository GitHub.
3. Buka Settings > Pages.
4. Pilih Deploy from a branch, branch `main`, folder `/root`.
5. Buka alamat GitHub Pages yang muncul.

## Pembahasan
PIN awal: `MAMIS2026`

Ganti PIN pada `index.html`, cari:
`if(pin!=='MAMIS2026')`

Catatan keamanan: karena GitHub Pages bersifat statis, kunci jawaban tetap tersimpan di data aplikasi untuk kebutuhan penilaian. Penguncian pembahasan mencegah akses biasa melalui antarmuka, tetapi bukan perlindungan server. Untuk keamanan penuh, kunci dan penilaian harus dipindah ke Google Apps Script/Supabase.

## Catatan akademik
- Kelas 12: latihan TKA Bahasa Inggris.
- Kelas 9: latihan Bahasa Inggris bergaya TKA. Bahasa Inggris bukan mata uji resmi TKA SMP 2026.
- Semua soal berupa pilihan ganda kompleks dengan tepat dua jawaban benar.

# CourtGo

Multi-page responsive booking UI tanpa dependency build.

## Halaman

- `index.html` — landing page & daftar/filter/search lapangan
- `detail.html` — detail lapangan dan pilih jadwal
- `pembayaran.html` — checkout pembayaran
- `riwayat-pesanan.html` — daftar pesanan
- `profile.html` — profil pengguna
- `login.html` — login

## Jalankan

```powershell
python -m http.server 8080
```

Buka `http://localhost:8080`.

Backend, autentikasi, pembayaran, dan database masih mock UI.

## Deploy ke Vercel

```powershell
npx vercel
```

Ikuti login dan pilih default untuk semua pertanyaan. Untuk production:

```powershell
npx vercel --prod
```

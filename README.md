# FitPlan — Personal Gym Planner

Website personal untuk membantu konsisten latihan 3 hari per minggu (Senin, Rabu, Jumat).

## Cara menjalankan
1. Extract folder `fitplan-personal-gym`.
2. Buka `index.html` di browser (Chrome/Edge disarankan).
3. Website bisa langsung digunakan. Tidak perlu install package atau database.

## Fitur
- Dashboard dan jadwal latihan 3 hari.
- Checklist latihan yang tersimpan.
- Timer istirahat 60 / 90 / 120 detik.
- Catatan latihan.
- Tracking berat badan dan grafik.
- Tracking kalori, protein, karbohidrat, dan lemak.
- Pengaturan target nutrisi dan nama.
- Export backup JSON dan reset data.
- Responsive layout untuk desktop, tablet, dan HP.
- Data disimpan di LocalStorage browser.

## Membuka di HP
**Cara termudah:** upload folder/file website ke GitHub, lalu aktifkan GitHub Pages atau deploy ke Vercel. Buka URL hasil deploy dari HP. Data LocalStorage di HP terpisah dari data di laptop, karena penyimpanan browser tiap perangkat berbeda.

Untuk mencoba di jaringan Wi-Fi yang sama:
1. Jalankan server lokal dari folder project, misalnya `python -m http.server 8000`.
2. Cari alamat IP lokal laptop (Windows: `ipconfig`).
3. Di HP yang tersambung Wi-Fi yang sama, buka `http://IP-LAPTOP:8000`.
4. Izinkan akses melalui Windows Firewall jika diminta.

Catatan: Google Fonts membutuhkan koneksi internet. Aplikasi inti tetap berjalan tanpa backend. Jika browser dihapus datanya atau berpindah perangkat, data LocalStorage tidak otomatis ikut pindah; gunakan Export JSON untuk backup.

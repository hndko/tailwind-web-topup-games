# TopUpKuy - Platform Top Up Game Kekinian

TopUpKuy adalah platform web untuk pembelian top up game online dengan proses cepat, mudah, dan harga terjangkau. Project ini terdiri dari halaman utama untuk pelanggan dan halaman admin untuk manajemen produk, pesanan, pengguna, promo, laporan, dan pengaturan sistem.

## Fitur Utama

### Untuk Pelanggan

- **Beranda**: Pilih game populer dan lihat promo menarik.
- **Top Up Produk**: Pilih nominal, metode pembayaran, dan lakukan checkout.
- **Konfirmasi**: Lihat detail pesanan setelah pembayaran berhasil.
- **Riwayat**: Cek riwayat transaksi yang pernah dilakukan.
- **Autentikasi**: Halaman login dan register.

### Untuk Admin

- **Dashboard**: Statistik ringkas dan aktivitas terbaru.
- **Manajemen Pesanan**: Lihat, filter, dan kelola semua pesanan.
- **Manajemen Game & Produk**: Tambah/edit/hapus game dan varian produk.
- **Manajemen Pengguna**: Kelola data pengguna, status, dan peran.
- **Manajemen Promo**: Atur promo diskon/top up.
- **Laporan**: Analitik penjualan, pengguna, produk terlaris, dan ekspor laporan.
- **Pengaturan**: Konfigurasi situs, pembayaran, notifikasi, dan API key.

## Struktur Folder

```
.
├── index.html
├── produk.html
├── konfirmasi.html
├── riwayat.html
├── login.html
├── register.html
├── admin/
│   ├── index.html
│   ├── pesanan.html
│   ├── produk.html
│   ├── pengguna.html
│   ├── promo.html
│   ├── laporan.html
│   └── pengaturan.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
```

## Cara Menjalankan

1. **Clone repository ini** ke folder web server lokal Anda (misal: `htdocs` untuk XAMPP atau `www` untuk Laragon).
2. **Buka file HTML** di browser, misal: `http://localhost/tailwind-web-topup-games/index.html`.
3. **Akses halaman admin** melalui `admin/index.html`.

> Project ini berbasis statis (HTML, CSS, JS) dan dapat dikembangkan lebih lanjut dengan backend sesuai kebutuhan.

## Teknologi yang Digunakan

- [Tailwind CSS](https://tailwindcss.com/) untuk styling.
- [Font Awesome](https://fontawesome.com/) untuk ikon.
- Vanilla JavaScript untuk interaktivitas dasar.
- Struktur HTML5 yang responsif.

## Catatan Pengembangan

- Data produk, pesanan, dan pengguna saat ini masih statis/dummy.
- Untuk produksi, integrasikan dengan backend (PHP, Node.js, dsb) dan database.
- Fitur checkout, login, register, dan riwayat dapat dihubungkan ke API sesuai kebutuhan.
- Halaman admin dapat dikembangkan untuk CRUD dinamis.

## Lisensi

Project ini untuk keperluan pembelajaran dan pengembangan. Silakan modifikasi sesuai kebutuhan Anda.

---

**TopUpKuy** - Platform top up game termurah, tercepat, dan terpercaya di Indonesia.

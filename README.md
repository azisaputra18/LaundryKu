Kode README.md-nya:

```markdown
# 🧺 LaundryKu — Sistem Manajemen Laundry

Aplikasi manajemen laundry berbasis web menggunakan **Laravel 11** dan **Tabler UI**.

![Laravel](https://img.shields.io/badge/Laravel-11-red?logo=laravel)
![PHP](https://img.shields.io/badge/PHP-8.3-blue?logo=php)
![Tabler](https://img.shields.io/badge/UI-Tabler-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## ✨ Fitur

- 🔐 **Autentikasi** — Login dengan role Admin & Kasir
- 📦 **Manajemen Order** — Buat, pantau, dan update status order
- 👥 **Manajemen Pelanggan** — Data pelanggan lengkap
- 👕 **Manajemen Layanan** — Kelola jenis layanan & harga
- 💳 **Konfirmasi Pembayaran** — Tunai & Transfer
- 🖨️ **Cetak Nota PDF** — Nota per order
- 📊 **Laporan** — Laporan transaksi bulanan + export PDF
- 👤 **Manajemen User** — Kelola akun admin & kasir

---

## 🛠️ Tech Stack

| Teknologi | Keterangan |
|-----------|-----------|
| Laravel 13 | PHP Framework |
| PHP 8.3 | Backend Language |
| MySQL | Database |
| Tabler UI | Frontend Template |
| ApexCharts | Grafik Dashboard |
| DomPDF | Generate PDF |
| Laragon | Local Development |

---

## ⚙️ Instalasi

### Requirements
- PHP >= 8.3
- Composer
- MySQL
- Laragon / XAMPP

### Langkah Instalasi

```bash
# 1. Clone repository
git clone https://github.com/azisaputra18/LaundryKu.git
cd LaundryKu

# 2. Install dependencies
composer install

# 3. Copy file environment
cp .env.example .env

# 4. Generate app key
php artisan key:generate

# 5. Setup database di .env
DB_DATABASE=laundry_db
DB_USERNAME=root
DB_PASSWORD=

# 6. Jalankan migration & seeder
php artisan migrate:fresh --seed

# 7. Jalankan server
php artisan serve
```

Buka browser: `http://127.0.0.1:8000`

---

## 👤 Akun Default

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@laundryku.com | Admin123 |
| Kasir | kasir@laundryku.com | Kasir123 |

---

## 📁 Struktur Folder

```
laundry-app/
├── app/
│   ├── Http/
│   │   ├── Controllers/     # AuthController, OrderController, dll
│   │   └── Middleware/      # RoleMiddleware
│   └── Models/              # User, Order, Pelanggan, dll
├── database/
│   ├── migrations/          # Struktur tabel
│   └── seeders/             # Data awal
├── resources/
│   └── views/               # Blade templates (Tabler UI)
└── routes/
    └── web.php              # Route aplikasi
```

---

## 📸 Screenshot

> Dashboard
<img width="1855" height="930" alt="image" src="https://github.com/user-attachments/assets/e82a81ff-22d1-4d20-a52f-57e5ce9463f4" />

>  Order
<img width="1918" height="930" alt="image" src="https://github.com/user-attachments/assets/185fa3eb-6e2f-4e3a-8f64-49c897e96ce0" />

> Laporan
<img width="1918" height="925" alt="image" src="https://github.com/user-attachments/assets/9f51924b-bfd9-40c8-96b7-3f664f15cdb9" />

> 

---

## 📄 License

MIT License © 2026 [Azis Aputra](https://github.com/azisaputra18)
```


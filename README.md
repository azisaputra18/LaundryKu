# 🧺 LaundryKu — Sistem Manajemen Laundry

Aplikasi manajemen laundry berbasis web menggunakan **Laravel 11** dan **Tabler UI**.

![Laravel](https://img.shields.io/badge/Laravel-13-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

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

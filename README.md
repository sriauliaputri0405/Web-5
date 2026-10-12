# 📦 Sistem Manajemen Inventaris Barang (Inventory System)

Aplikasi Web Sistem Manajemen Inventaris berbasis **Laravel 10** yang dimigrasikan dari PHP Native (P4) ke arsitektur MVC Laravel (P5). Aplikasi ini digunakan untuk mencatat dan mengelola data produk, kategori, supplier, serta transaksi stok keluar-masuk.

---

## 🚀 Fitur Utama

- **Dashboard & Produk:** CRUD data produk lengkap (SKU, Nama, Stok, Harga, Deskripsi).
- **Kategori Barang:** Pengelompokan jenis barang inventaris.
- **Supplier:** Pengelolaan data pemasok/vendor barang.
- **Manajemen Stok:**
  - **Stok Masuk:** Penambahan jumlah stok produk otomatis.
  - **Stok Keluar:** Pengurangan jumlah stok produk dengan proteksi penolakan jika stok tidak mencukupi.
  - **Riwayat Stok:** Catatan alur riwayat transaksi mutasi barang secara *real-time*.

---

## 🛠️ Teknologi & Stack

- **Framework:** Laravel 10 (PHP 8.x)
- **Database:** MySQL
- **Frontend / Styling:** Bootstrap 5 (Blade Templating Engine)

---

## ⚙️ Cara Instalasi & Menjalankan Proyek

1. **Clone / Download Proyek**
   Pastikan folder proyek berada di lingkungan server lokal (seperti XAMPP).

2. **Instal Dependencies**
   ```bash
   composer install

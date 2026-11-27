# 📦 Stok Gudang

Aplikasi web simpel buat nyatet stok barang — cocok untuk toko online kecil, brand clothing, atau gudang kecil.

**Live demo:** https://labib404.github.io/stok-gudang/

![Screenshot Stok Gudang](screenshot.jpg)

## Fitur

- Tambah / edit / hapus barang (SKU, nama, kategori, lokasi rak, stok minimum, harga)
- Catat **barang masuk** dan **barang keluar** + catatan (mis. nomor order)
- Status otomatis: **Aman**, **Menipis** (≤ stok minimum), **Habis**
- Ringkasan: jumlah jenis barang, total unit, barang menipis, nilai stok (Rp)
- Cari, filter per kategori/status, urutkan kolom
- Riwayat transaksi (500 terakhir)
- **Export CSV** (bisa dibuka di Excel / Google Sheets)
- **Backup & restore JSON**
- Jalan offline, tanpa server, tanpa login — data tersimpan di browser (localStorage)
- Mode gelap otomatis, responsif di HP

## Cara pakai

1. Buka link demo di atas, atau download `index.html` lalu buka di browser.
2. Hapus data contoh, tambahkan barang sendiri.
3. Rutin klik **Backup JSON** — data cuma ada di browser itu, jadi kalau cache dihapus datanya ikut hilang.

## Teknologi

Satu file HTML + CSS + JavaScript murni. Tanpa framework, tanpa build step.

## Lisensi

MIT — bebas dipakai dan dimodifikasi.

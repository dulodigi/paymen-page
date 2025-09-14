# Payment Page

Halaman pembayaran sederhana untuk top-up menggunakan berbagai metode:
- Bank Transfer (BCA, Bank Jago)
- E-wallet (DANA, GOPAY)
- QRIS

## 🚀 Cara Pakai
1. Clone repo
2. Buka file `index.html` di browser
3. Klik metode pembayaran → akan muncul popup detail rekening / QRIS
4. Bisa klik tombol **Salin** untuk copy rekening atau jumlah transfer

## 🛠️ Teknologi
- HTML, CSS, JavaScript murni
- Popup untuk detail pembayaran
- Tombol copy menggunakan `navigator.clipboard`

## ✨ Contoh Variabel
- `{{jenis_payment}}` → jenis pembayaran
- `{{jumlah_topup}}` → jumlah yang harus ditransfer
- `{{id_transaksi}}` → ID unik transaksi

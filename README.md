# alifsmart-payments

# this service ran a function as :
- Proses pembayaran SPP QRIS
- Auto-generate invoice PDF
- Transaction History

# database :
- payments -> menyimpan semua transaksi pembayaran SPP (id_pembayaran, student, parent, metode_pembayaran, status)
- invoices -> template dan riwayat faktur yang digenerate otomatis
- payment_gateways -> integrasi QRIS (API Keys, Callback URLs)

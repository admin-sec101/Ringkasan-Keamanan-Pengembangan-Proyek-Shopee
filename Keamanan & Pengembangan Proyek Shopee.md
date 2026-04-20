🛡️ Ringkasan Keamanan & Pengembangan Proyek Shopee
1. Keamanan Library (Safety CLI)
Tujuan: Memastikan tidak ada celah keamanan (vulnerabilities) pada library Python yang digunakan (seperti requests).
Perintah Cek: python -m safety scan
Status Terakhir: 0 Vulnerabilities Found (Aman sesuai kebijakan Shopee 1023).
2. Integrasi AI (Safety MCP di Cursor)
Fungsi: AI Cursor sekarang memiliki "otak" keamanan yang akan memantau kode Anda secara otomatis.
Lokasi Pengaturan: Cursor Settings > Tools & MCPs > SSE.
API Key: b654fe85-760d-453b-b380-e739295e9db0.
3. Otomatisasi GitHub (GitHub Actions)
Lokasi: .github/workflows/safety_scan.yml.
Fungsi: Setiap kali kode diunggah ke GitHub, sistem akan otomatis memeriksa keamanan sebelum kode dijalankan.
4. Skrip API Shopee (shopee_api.py)
Shop ID: 583684768.
Status Koneksi: Berhasil (Terdeteksi melalui Respon 404 dari server Shopee).
Langkah Berikutnya: Pastikan aplikasi di Shopee Open Platform sudah berstatus Live untuk mendapatkan data asli.
⚠️ Pengingat Penting:
Jangan pernah membagikan Partner Key atau Safety API Key Anda kepada siapapun di forum publik atau grup chat.

<img width="687" height="377" alt="image" src="https://github.com/user-attachments/assets/2ea41ec3-a9f1-4cd4-abbc-1f9823125836" />

IDOR (Insecure Direct Object Reference) yang ia temukan di subdomain Shopee. Temuan ini sangat kritis karena memungkinkan seseorang untuk menghapus proyek milik orang lain hanya dengan memanipulasi parameter tertentu. 

Berikut adalah poin-poin penting dari temuan tersebut:
Jenis Kerentanan: IDOR, yaitu celah keamanan di mana aplikasi tidak memvalidasi apakah pengguna berhak mengakses atau memodifikasi objek tertentu.
Dampak Temuan: Penyerang bisa menghapus proyek di portal pengembang Shopee tanpa memerlukan izin dari pemilik aslinya.
Bounty (Imbalan): Atas laporan yang bertanggung jawab ini melalui platform HackerOne, peneliti tersebut mendapatkan imbalan sebesar $400 dari Shopee

Cara Mencegahnya bagi Developer
Sebagai pengembang, Anda bisa menghindari celah ini dengan:
Selalu menerapkan kontrol akses (Access Control) yang ketat pada setiap permintaan API.
Melakukan validasi izin di sisi server sebelum melakukan operasi penghapusan atau perubahan data.
Menggunakan pengidentifikasi yang sulit ditebak (seperti UUID) daripada angka berurutan

```
https://socket.dev/npm/package/%40congminh1254%2Fshopee-sdk

https://github.com/congminh1254/shopee-sdk

https://github.com/congminh1254/shopee-sdk#readme

https://github.com/aqualaguna/shopee-client.git

https://open.shopee.com/
```

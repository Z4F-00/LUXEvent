# 💎 LUXEvent System

Sistem monitoring dan manajemen event LUX yang efisien, ringan, dan aman. Gunakan script di bawah ini sesuai dengan kebutuhan otorisasi Anda.

## 📜 Script Loader

### 👤 Member Script

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Z4F-00/LUXEvent/refs/heads/main/MemberScript"))()
```

### 🛠️ Admin Login

Gunakan ini untuk mengakses Dashboard Admin (Memerlukan Key).
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Z4F-00/LUXEvent/refs/heads/main/AdminLogin"))()
```

## ⚙️ Cara Mengaktifkan Auto-Execute (Teleport Support)

Agar script otomatis berjalan kembali saat Anda berpindah server (Teleport) atau membuka game, ikuti langkah-langkah berikut:
 * Buat File Baru: Di dalam folder executor Anda, buatlah file teks baru dan beri nama sesuai keinginan anda.
 *  * Salin Script: Masukkan salah satu kode Script Loader di atas ke dalam file tersebut.
 > Jika anda sudah mengunduh file atau script yang ada di Dashboard ini, maka langkah-langkah sebelumnya tidak perlu anda lakukan.
 * Pindahkan file yang sudah anda unduh atau anda buat ke Folder Auto-Execute: Simpan file tersebut ke lokasi folder autoexecute sesuai dengan executor yang Anda gunakan:

### 📂 Lokasi Folder Berdasarkan Executor:

| Executor | Lokasi Path (Android) |
|---|---|
| Delta | /storage/emulated/0/Delta/autoexecute/ |
| Codex | /storage/emulated/0/Android/media/com.roblox.client/codex/autoexecute/ |
| Vega X | /storage/emulated/0/VegaX/autoexecute/ |
| Arceus X | /storage/emulated/0/Android/media/com.roblox.client/scripts/autoexecute/ |
| Fluxus | /storage/emulated/0/fluxus/autoexecute/ |
> Catatan Penting
> * Pada beberapa executor mendukung, nama file tidak wajib berakhiran .lua.
>  * Jika folder autoexecute tidak ada, silakan buat folder baru dengan nama tersebut (huruf kecil semua) di dalam folder utama executor Anda.
>  * Sistem Admin Log akan secara otomatis mendeteksi sesi Anda (Auto-Login) jika Anda sudah pernah login sebelumnya.

> Security Note
> * Script ini menggunakan koneksi terenkripsi ke Cloudflare Workers. Jangan membagikan file di folder workspace Anda kepada orang lain karena berisi data sesi login Anda.


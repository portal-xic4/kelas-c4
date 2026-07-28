# Security Policy

## Policy & Overview
Aplikasi Web Portal Kelas XI-C4 ini mengimplementasikan kebijakan keamanan berikut:

1. **Client-Side Authentication & Session Management:**
   - Sesi pengguna disimpan secara lokal melalui `localStorage`.
   - Inactivity Timeout dikontrol secara otomatis setelah 30 menit tanpa aktivitas.
2. **Database Security:**
   - Penginputan data kas dan log aktivitas diverifikasi langsung dari antarmuka web.
   - Menggunakan enkripsi SSL/TLS bawaan dari GitHub Pages dan Firebase Services.
3. **Domain Restriction:**
   - Akses API Firebase dibatasi secara khusus hanya untuk origin terpercaya (`https://portal-xic4.github.io`).

## Reporting a Vulnerability

Jika Anda menemukan celah keamanan (*vulnerability*) pada website ini, harap **jangan** membuat *Issue* publik di GitHub.

Silakan laporkan temuan Anda kepada tim pengembang/pengurus kelas melalui:
- **Email/Contact:** Pengurus Kelas XI-C4
- **Penanganan:** Laporan akan ditinjau dalam kurun waktu 1x24 jam.

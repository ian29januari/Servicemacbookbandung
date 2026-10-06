SERVICEMACBOOKBANDUNG — GITHUB + CLOUDFLARE WORKERS

Paket ini sudah disusun untuk repository GitHub yang terhubung ke Worker Cloudflare yang SUDAH ADA.
Worker target: servicemacbookbandung
Domain: servicemacbookbandung.com

STRUKTUR:
- File HTML berada di root repository agar lebih mudah di-upload dari iPhone.
- wrangler.jsonc mengatur Worker Static Assets.
- .assetsignore mencegah file konfigurasi/README ikut disajikan sebagai halaman publik.

CLOUDFLARE:
- Jangan membuat Worker baru.
- Hubungkan repository ini ke Worker servicemacbookbandung melalui Settings > Builds > Connect.
- Root directory: / (root repository)
- Build command: kosongkan
- Deploy command: npx wrangler deploy
- Branch: main

Cloudflare akan melakukan deployment ketika commit masuk ke branch yang terhubung.

KEAMANAN:
Jangan memasukkan API token Cloudflare ke chat.
Jangan mengubah DNS/nameserver.
Deployment lama 7ad42e87 jangan dihapus sebelum V4 terbukti normal.

#Halaman Asli Github ada
https://github.com/3Kmfi6HP/EDtunnel


# RisunTuru Clone Repo EDtunnel (Bahasa)
Hal-hal yang perlu disediakan sebelum kamu memulai!
1. Akun Github
2. Akun Cloudflare
3. Telegram (Untuk nyari IP)
4. Waktu Luang 

## Deploy di pages.dev
Klik tombol dibawah untuk deploy

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/3Kmfi6HP/EDtunnel)

## Mengatur UUID

1. Saat deploy di halaman cloudflare, Anda dapat mengatur uuid di file `wrangler.toml`. nama variabelnya adalah `UUID`. File `wrangler.toml` juga didukung. (disarankan) jika diterapkan di halaman web, Anda tidak dapat menyetel uuid di file `wrangler.toml`.

2. Saat deploy di worker.dev, Anda dapat mengatur UUID di file `_worker.js`. nama variabelnya adalah `userID`. File `wrangler.toml` juga didukung. (disarankan) jika diterapkan di halaman web, Anda tidak dapat menyetel uuid di file `wrangler.toml`. dalam hal ini, Anda juga dapat mengatur uuid dalam variabel lingkungan `UUID`.

Catatan: `UUID` adalah UUID yang ingin Anda atur. anda dapat menggunakan tool UUID GENERATOR untuk itu.
pages.dev dan worker.dev semua metodedi dukung, tetapi bergantung pada metode deploy Anda.

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
## Cara Mendapatkan AccountID
Liat pada link 

https://dash.cloudflare.com/inicontoh

akun idnya = inicontoh

## Cara Mendapatkan TokenAPI
Pergi ke halaman Worker and Pages > OverView 

Cari Manage API Tokens, setelah ketemu

> Create Token

> Edit Cloudflare Workers > Use this template

Atur
Account Resources > Include > akunkamu@gmail.com

Zone Resources > Include > All Zone from an account > akunmu@gmail.com

> Continue to summary > Create token

Copy itu tokennya. simpen 


## Mengatur UUID

1. Saat deploy di halaman cloudflare, Anda dapat mengatur uuid di file `wrangler.toml`. nama variabelnya adalah `UUID`. File `wrangler.toml` juga didukung. (disarankan) jika diterapkan di halaman web, Anda tidak dapat menyetel uuid di file `wrangler.toml`.

2. Saat deploy di worker.dev, Anda dapat mengatur UUID di file `_worker.js`. nama variabelnya adalah `userID`. File `wrangler.toml` juga didukung. (disarankan) jika diterapkan di halaman web, Anda tidak dapat menyetel uuid di file `wrangler.toml`. dalam hal ini, Anda juga dapat mengatur uuid dalam variabel lingkungan `UUID`.

Catatan: `UUID` adalah UUID yang ingin Anda atur. anda dapat menggunakan tool UUID GENERATOR untuk itu.
pages.dev dan worker.dev semua metodedi dukung, tetapi bergantung pada metode deploy Anda.

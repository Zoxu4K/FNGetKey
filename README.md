# FNGetKey-web

Halaman get key Fake Ninja — deploy ke GitHub Pages.

## Setup

1. Fork repo ini, rename sesuai keinginan
2. Di `index.html` dan `admin.html`, `SERVER_URL` sudah di-set ke `https://fnkeyserver.vercel.app/api/key`
   - Ganti ke URL Vercel deploy kamu yang sebenarnya
3. Enable GitHub Pages dari Settings → Pages → Source: GitHub Actions

## Ganti Linkvertise URL

Di `index.html`:
```js
const LV_URL_3H = "https://...";  // link Linkvertise 3 jam
const LV_URL_6H = "https://...";  // link Linkvertise 6 jam
```


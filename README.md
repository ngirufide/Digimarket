# DigiMarket — Buy & Sell Digital Products

Isoko rya digitale ryo mu **Rwanda** aho ushobora **kugura** no **kugurisha** ibicuruzwa bya digitale.

## Features

- 🛒 **Marketplace** — E-books, Templates, Software, Music, Design Assets, Online Courses
- 💰 **70% Seller / 30% Platform** — Nta listing fee
- 📱 **Mobile Money** — MTN MoMo & Airtel Money
- 🌐 **3 Languages** — Ikinyarwanda · Français · English
- 📥 **Instant download** after payment confirmation
- 📊 **Admin dashboard** — Approve products, confirm payments, seller payouts
- 🔐 Login / Register (Buyer & Seller roles)

## Live Demo

After deploying (Netlify / GitHub Pages / Vercel), your link will be here.

## How to run locally

1. Open `index.html` in a browser  
   **or**
2. Use a simple server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```

## Deploy free (recommended)

### Netlify
1. Go to [netlify.com](https://www.netlify.com) → Sign up
2. **Add new site** → **Deploy manually**
3. Drag & drop this folder
4. Done — you get `https://your-site.netlify.app`

### GitHub Pages
1. Push this repo to GitHub
2. **Settings** → **Pages** → Source: `main` branch → Save
3. Site: `https://USERNAME.github.io/REPO-NAME`

### Vercel / Cloudflare Pages
Import the repo and deploy (zero config).

## Project structure

```
├── index.html   # Full DigiMarket app (frontend)
└── README.md
```

## Tech

- Pure HTML + CSS + JavaScript (no build step)
- LocalStorage for demo data
- Optional remote API (`API_URL` in the script) for production backend

## Commission model

| Role        | Share |
|------------|-------|
| Seller     | **70%** |
| DigiMarket | **30%** |
| Listing fee| **0** |

## License

Private / All rights reserved — DigiMarket

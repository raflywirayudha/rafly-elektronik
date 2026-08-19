# Rafly Elektronik

Landing page untuk **Rafly Elektronik** — Authorized Service Center elektronik & peralatan rumah tangga (Rinnai, Shimizu, Miyako) di Tembilahan, Indragiri Hilir, Riau.

Dibangun dengan **Astro 7** + **Tailwind CSS 4** (output statis murni, tanpa JavaScript framework).

## 🚀 Development

```sh
npm install
npm run dev        # dev server di localhost:4321
npm run build      # build produksi ke ./dist/
npm run preview    # preview hasil build
```

Saat menjalankan dev server, gunakan mode background:

```
astro dev --background
```

Kelola server dengan `astro dev stop`, `astro dev status`, dan `astro dev logs`.

## 📁 Struktur Project

```text
/
├── public/                    # asset statis (favicon, logo brand)
├── src/
│   ├── components/            # Header, Hero, Partners, Services, Trust, About, Location, Contact, Footer
│   ├── layouts/
│   │   └── Layout.astro       # head, meta SEO, font, JSON-LD LocalBusiness
│   ├── pages/
│   │   └── index.astro        # komposisi halaman
│   └── styles/
│       └── global.css         # import Tailwind + design tokens (@theme)
├── astro.config.mjs
└── package.json
```

## 🎨 Design Tokens

Palet warna & font didefinisikan sebagai token `@theme` di `src/styles/global.css`:

- Warna: `navy`, `blue`, `ink`, `muted`, `cream`, `orange`, `gold`, `amber`, `ember`, dsb.
- Font: `font-sans` (DM Sans) & `font-display` (Space Grotesk).

## 📝 Catatan Konten

Beberapa data masih placeholder dan perlu diperbarui oleh Rafly:

- Nomor telepon & WhatsApp lengkap
- Email lengkap
- Jam operasional
- Narrasi final "Tentang Kami" & tahun berdiri
- Akun media sosial

## 🧞 Command

| Command                   | Action                                      |
| :------------------------ | :------------------------------------------ |
| `npm install`             | Instal dependencies                         |
| `npm run dev`             | Jalankan dev server di `localhost:4321`     |
| `npm run build`           | Build produksi ke `./dist/`                 |
| `npm run preview`         | Preview hasil build lokal                   |
| `npm run astro ...`       | Perintah CLI Astro (`astro add`, `check`)   |

## 📄 Dokumentasi

- Astro: https://docs.astro.build
- Tailwind CSS: https://tailwindcss.com
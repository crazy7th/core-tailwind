# core-tailwind v3

HTML Template Collection using **Tailwind CSS v3**.  
Dirancang agar developer bisa cepat membangun website modern, responsive, dan maintainable.

---

## Table of Contents

- [core-tailwind v3](#core-tailwind-v3)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
  - [Folder Structure](#folder-structure)
    - [Penjelasan tambahan](#penjelasan-tambahan)
  - [Available Scripts](#available-scripts)
  - [Configuration](#configuration)
  - [Customization](#customization)
  - [Contributing](#contributing)
  - [License](#license)

---

## About

**core-tailwind** adalah boilerplate + kumpulan template HTML berbasis Tailwind CSS, lengkap dengan konfigurasi dan komponen siap pakai.  
Struktur project ini dibuat agar fleksibel untuk kebutuhan personal maupun profesional.

---

## Prerequisites

- Node.js (>=14)  
- npm atau yarn  
- Basic knowledge tentang Tailwind CSS & PostCSS  

---

## Getting Started

1. Clone repo:
   ```bash
   git clone --branch v3 https://github.com/crazy7th/core-tailwind.git
   cd core-tailwind
   ```
2. Install dependencies:
   ```bash
   npm install
   # atau
   yarn install
   ```
3. Jalankan development:
   ```bash
   npm run dev
   ```
4. Build untuk production:
   ```bash
   npm run build
   ```

---

## Folder Structure

```bash
core-tailwind/
├── custom/             # custom style dengan class tailwind sebelum diconvert jadi style.css
├── src/
│   ├── components/     # reusable HTML components (navbar, footer, card, dsb.)
│   ├── pages/          # template halaman lengkap
│   ├── styles/         # custom styles (global.css, partials)
│   ├── assets/         # images, fonts, icons
├── .gitignore
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── README.md
```

### Penjelasan tambahan
- **components/** → Kumpulan blok UI siap pakai  
- **pages/** → Contoh implementasi layout penuh  
- **styles/** → Tempat global style & overrides  
- **assets/** → Berisi static asset (gambar, svg, dsb.)  
- **custom/** → Tambahan class manual, preset CSS, atau eksperimen yang belum masuk ke `tailwind.config.js`  

---

## Available Scripts

| Command          | Keterangan                           |
|------------------|--------------------------------------|
| `npm run dev`    | Menjalankan mode development + HMR    |
| `npm run build`  | Build final output untuk production   |
| `npm run watch`  | Auto rebuild saat file berubah        |

---

## Configuration

- **`tailwind.config.js`** → konfigurasi Tailwind (theme, colors, plugins)  
- **`postcss.config.js`** → pengaturan PostCSS, autoprefixer, dsb.  

---

## Customization

- Ubah **warna, spacing, font** lewat `tailwind.config.js`  
- Tambahkan class manual di folder `/custom/`  
- Tambahkan / modifikasi komponen di `src/components/`  
- Gunakan contoh layout di `src/pages/` untuk memulai  

---

## Contributing

Kontribusi sangat diterima! 🎉  
1. Fork repo  
2. Buat branch baru (`feature/xyz` atau `fix/xyz`)  
3. Commit perubahan  
4. Push dan buat pull request  

---

## License

[MIT License](./LICENSE)

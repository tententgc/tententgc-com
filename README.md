# tententgc.com — Astro Portfolio

An opinionated personal website/portfolio built with **Astro** + **TypeScript** + **Tailwind CSS**. Deployed on Vercel.

## ✨ Features

- Fast, content-focused Astro pages
- Markdown/MDX-friendly sections for projects, posts, and notes
- Tailwind utility styling with sensible defaults
- SEO tags + Open Graph placeholders
- Ready for Vercel 1-click deploy & previews
- MIT licensed for easy reuse/customization

## 🧱 Tech Stack

- **Astro** (static-first site framework)
- **TypeScript**, **CSS**, and a touch of **JavaScript**

## 🚀 Quick Start

> Prereqs: Node.js ≥ 18 and npm (or pnpm/yarn).

```bash
# 1) Clone
git clone https://github.com/tententgc/tententgc-com.git
cd tententgc-com

# 2) Install deps
npm install

# 3) Run dev server
npm run dev
# Astro will print a local URL like http://localhost:4321
```

### Common Scripts

```bash
npm run dev      # Start local dev server with HMR
npm run build    # Production build to ./dist
npm run preview  # Preview the production build locally
```

## 🗂 Project Structure

```
├─ public/            # Static assets
├─ src/
│  ├─ components/     # Reusable UI components
│  ├─ content/        # Markdown/MDX (blog, projects)
│  ├─ layouts/        # Page layouts
│  ├─ pages/          # Astro/MDX pages → routes
│  ├─ styles/         # Global Tailwind/CSS
│  └─ lib/            # Utilities
├─ astro.config.mjs   # Astro config
├─ tailwind.config.cjs
├─ package.json
└─ tsconfig.json
```

## 🎯 Content & Customization

- **Site metadata**: Add title/description/social image
- **Navigation**: Edit Nav component or config
- **SEO**: Ensure `<title>` + meta tags
- **Analytics**: Add snippet in layout

## ☁️ Deploy (Vercel)

- Framework: Astro  
- Build Command: `npm run build`  
- Output Directory: `dist`  

## 🧪 Production Checks

- `npm run build` + `npm run preview`
- Validate Open Graph/Twitter cards
- Lighthouse audit

## 🔧 Troubleshooting

- Node ≥ 18 required
- Tailwind content globs must include `.astro`, `.tsx`, `.mdx`

## 📄 License

MIT — see [`LICENSE`](./LICENSE)

---

## 🇹🇭 วิธีรันแบบสั้น (Thai Quick Start)

```bash
git clone https://github.com/tententgc/tententgc-com.git
cd tententgc-com
npm install
npm run dev   # เปิดดูที่ http://localhost:4321
```

**Build Production**: `npm run build`  
**Preview**: `npm run preview`  

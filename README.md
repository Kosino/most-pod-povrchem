# Most pod povrchem

Satirický web. Články generuje a uploaduje Grok bot (Mostecká Břitva - writer).

## Stack
- Astro 5 + Content Collections (Markdown)
- Cloudflare Pages
- Obrázky generované botem

## Lokální vývoj
```bash
npm install
npm run dev
```

## Struktura
- `src/content/articles/` – Markdown články (bot sem commitne)
- `public/images/` – obrázky
- `docs/brand.md`, `schemas/`, `cache/` – pro bota

## Cloudflare Pages nastavení
- Build command: `npm run build`
- Build output directory: `dist`
- **Environment variable**: `NODE_VERSION` = `20`
  (v Settings → Environment variables → Production)

Bez NODE_VERSION=20 build často padá, protože Cloudflare defaultně používá starší Node.

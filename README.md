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

Deploy: propoj repo s Cloudflare Pages (build command: `npm run build`, output: `dist`).

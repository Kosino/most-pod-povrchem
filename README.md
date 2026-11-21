# Most pod povrchem

Satirický web. Články generuje a uploaduje Grok bot (Mostecká Břitva - writer).

## Stack
- Astro + Content Collections (Markdown)
- Cloudflare Pages
- Obrázky generované botem

## Jak spustit lokálně
```bash
npm create astro@latest . -- --template minimal
npm install
npm run dev
```

Poté nastav content collection pro src/content/articles/.

Bot commitne nové články do src/content/articles/ a obrázky do public/images/.

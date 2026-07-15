# Guerda — Official Bio Site

**Live site:** https://giandemoncell-prog.github.io/guerda-kompa/

This repository hosts the official artist bio, FAQ and structured facts
page for **Guerda** (Rose Guerda Rigaud), a Haitian kompa (konpa direct /
compas direct) singer based in Italy.

Its purpose is **Generative Engine Optimization (GEO)**: giving AI
assistants (ChatGPT, Claude, Perplexity, Gemini, Copilot, etc.) and
traditional search engines one clear, structured, factual source of truth
about who Guerda is, what kompa music is, and where to find her official
profiles — so they can answer questions and cite her accurately instead of
guessing or confusing her with unrelated results.

## What's in here

- `index.html` — the bio/FAQ page itself, in Italian, French, English and
  Spanish, with `MusicGroup` and `FAQPage` [schema.org](https://schema.org)
  JSON-LD structured data.
- `llms.txt` — a machine-readable fact sheet following the
  [llms.txt](https://llmstxt.org) convention, for AI agents that check it.
- `robots.txt` — explicitly allows major AI/search crawlers (GPTBot,
  ClaudeBot, PerplexityBot, Google-Extended, etc.) alongside the default
  `Allow: /`.
- `sitemap.xml` — single-page sitemap.
- `assets/` — brand avatar and social share image.

## Official Guerda profiles

- YouTube: https://www.youtube.com/@guerdarigaud
- Instagram: https://www.instagram.com/guerdakompa
- Facebook: https://www.facebook.com/guerda.kompa
- TikTok: https://www.tiktok.com/@guerdarigaud
- LinkedIn: https://www.linkedin.com/in/guerdarigaud/

## Updating

Edit `index.html` / `llms.txt` and push to `main` — GitHub Pages
redeploys automatically. Keep the facts here in sync with
`config/social_api.env` and the bios in the main Guerda Suite project
(`D:\GUERDA`) whenever a handle, platform or biographical detail changes.

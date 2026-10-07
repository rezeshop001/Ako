# 💜 Do u love me? — Love Confession Page

A single-file, interactive love confession website by **Rezeshop**.
Built with plain HTML, CSS and JavaScript. No framework, no build step, no dependencies to install.

## Preview

1. The page opens with **"Do u love me? 🪻"** and two buttons: **ချစ်တယ်** and **မချစ်ဘူး**.
2. Either button moves to the next page.
3. Pages 1–10 each show one message with a single **ချစ်တယ်** button, so the reader goes through every message one step at a time.
4. The final page is the **8 Month Anniversary** message, with confetti 🎉.

## Features

- Light blue background with a purple and blue emoji theme (💜 💙 🩵 🪻 🦋 🔮)
- Floating hearts, falling petals and animated stickers
- Step-by-step pages with progress dots at the bottom
- Burmese text support (Noto Sans Myanmar)
- Mobile friendly (works as a phone-sized page)
- One file: `index.html`

## Run locally

Open `index.html` in any browser. An internet connection is only needed to load Google Fonts.

## Deploy (free)

- **Vercel / Netlify:** drag and drop the folder, or connect the repo.
- **GitHub Pages:** push `index.html` to a repo, then enable Pages in Settings.

## Customize

| What | Where in `index.html` |
| --- | --- |
| Colors | `:root` at the top of `<style>` (`--rose`, `--deep`, `--cream`) |
| Page text | The `<div class="page" id="escape1">` … `escape10` blocks (`escape-title` and `escape-body`) |
| Main question | `#page1` → `<h1 class="main-title">` |
| Final message and date | `#page-yes` |
| Emojis | `STICKERS`, `HEART_EMOJIS`, `PETALS`, `CONF` arrays in `<script>` |
| Number of pages | Add or remove an `escape` block, then update `TOTAL_PAGES` in `<script>` |

## File structure

```
.
├── index.html   # the whole project (HTML + CSS + JS)
└── README.md
```

## Credits

Made by **Rezeshop** 💙

# BARTist

This repository is the [bartist.app](https://bartist.app) website. It is generated with [blug.blog](https://blug.blog).

## Run locally

```bash
npm install
npm run generate
npm run dev
```

Then open http://localhost:3000.

## Modify contents

News posts are markdown folders under `public/`. Create `public/<slug>/index.md`:

```markdown
---
title: Hello World
date: 2026-08-30
---

Text. Media next to this file: [photo](./photo.jpg).
```

`title` and `date` are required. Keep media in the same directory and use relative links.

Edit `scripts/config.js` for the site title, footer, listing heading, and the home-page intro (`LISTING_INTRO`). After you change markdown or config, run `npm run generate` again and refresh.

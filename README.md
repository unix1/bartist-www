# BARTist

This repository is for the [BARTist app](https://bartist.app) website. It is generated with [blug.blog](https://blug.blog).

## Run locally

```bash
npm install
npm run generate
npm run dev
```

Then open http://localhost:3000.

## Modify contents

To create a new post, create a new folder under `public/` and add content in `public/<slug>/index.md`.
For example


```markdown
---
title: Hello World
date: 2026-08-30
---

This is the text of the new post. This is a link to sample [photo](./photo.jpg).
```

`title` and `date` are required. Keep media in the same directory and use relative links.

To create a page (not listed on the home page), use the same folder layout with `type: page` and no date:

```markdown
---
title: Privacy Policy
type: page
---

Your content here.
```

`title` and `type: page` are required. Link to pages the same way as posts (`/privacy-policy/`).

To update site metadata, edit `scripts/config.js`. Site main page, header and footer HTML can also be updated. See [blug.blog](https://blug.blog) for more details.

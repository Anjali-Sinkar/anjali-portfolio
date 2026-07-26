# Anjali Sinkar — Portfolio

Personal portfolio site for Anjali Sinkar, an AI & Data Science graduate. Built as a single static HTML page — no build step, no framework, no dependencies to install.

**Live site:** _(add your Vercel URL here after deploying)_

## Stack

- Plain HTML/CSS/JS (one file: `index.html`)
- Google Fonts (Fraunces, Inter, JetBrains Mono)
- [Tabler Icons](https://tabler.io/icons) webfont via CDN
- [Simple Icons](https://simpleicons.org/) + Google's favicon service for brand logos

## Structure

```
index.html          the entire site
assets/
  resume.pdf         downloadable resume (linked from hero/contact buttons)
  profile.jpg         hero portrait
  mindmate-thumb.jpg  MindMate project screenshot
  vpr-thumb.png        Virtual Patient Recruitment project screenshot
```

## Running locally

No build step — just open `index.html` in a browser, or serve the folder with any static server, e.g.:

```
npx serve .
```

## Deployment

Deployed on [Vercel](https://vercel.com) as a static site, connected to this GitHub repo — every push to `main` redeploys automatically.

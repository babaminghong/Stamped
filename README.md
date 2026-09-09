# Koray — Portfolio

A single-page portfolio site. Opens with a short confession, an optional 6-panel
story about getting stuck and unstuck while learning to build things, then the
actual project list.

**Live site:** _add your Vercel URL here once deployed_

## What's in it

- **Hero** — a short, honest intro
- **Story mode** — 6 panels, each one a specific thing I got stuck on and what
  actually got me past it (skippable at any point)
- **Projects** — including a 60+ hour Minecraft server admin dashboard
  (source lost, documented from screenshots), a Chrome extension, and a
  handful of C++/Lua experiments

## Stack

Plain HTML/CSS/JS. No build step, no framework, no dependencies —
one `index.html` and an `images/` folder. Fonts (Anton, JetBrains Mono)
load from Google Fonts.

## Running it locally

There's nothing to install. Either:

- Open `index.html` directly in a browser, or
- Serve it locally so relative paths behave exactly like production:

  ```bash
  npx serve .
  # or
  python3 -m http.server
  ```

## Deploying (Vercel)

This is a static site, so Vercel needs no build command or output directory —
just point it at the repo root.

1. Push this folder to a public GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo
3. Leave the framework preset as "Other" and the build command empty
4. Deploy — Vercel serves `index.html` as-is

## Structure

```
.
├── index.html
├── images/
│   ├── runesmp-dashboard-1.png
│   └── runesmp-dashboard-2.png
└── README.md
```

## License

MIT — see [LICENSE](./LICENSE).

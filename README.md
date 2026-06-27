# TubeFold landing page

Static single-page site for [TubeFold](https://github.com/TubeFold). One file,
no build step, no dependencies — [`index.html`](index.html) is the whole thing.

## What's on it

- The one-line install: `brew install --cask tubefold/tap/tubefold`
- A direct download link to the latest notarized build:
  `https://github.com/TubeFold/App/releases/latest/download/TubeFold.zip`
- Short "why" and "how it works" sections.

## Deploy (GitHub Pages)

Serve the repo root via Pages:

1. Repo **Settings → Pages → Build and deployment**.
2. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Save. The site publishes at `https://tubefold.github.io/Site/` (or a custom
   domain — drop a `CNAME` file in the root and point DNS at GitHub Pages).

No Jekyll processing is needed; if Pages ever tries to build, add an empty
`.nojekyll` file to the root.

## Editing

Open `index.html` in a browser to preview — there's nothing to compile. The
download link tracks `releases/latest`, so it never needs bumping per release.

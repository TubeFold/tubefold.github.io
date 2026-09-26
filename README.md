# TubeFold landing page

Static site for [TubeFold](https://github.com/TubeFold/App) — turn YouTube videos into Markdown notes with your own Claude Code or Codex subscription.

Live at **[tubefold.app](https://tubefold.app/)** — GitHub Pages (custom domain via `CNAME`, no build step). DNS and the short links live in Cloudflare: `/download`, `/extension`, `/github` are Redirect Rules on the `tubefold.app` zone, not files in this repo. `tubefold.github.io` and `www.tubefold.app` redirect here automatically.

- `index.html` — the landing page. Single file, zero dependencies, light/dark via `prefers-color-scheme`, no external requests (no fonts, no analytics — that's a product claim, keep it true).
- `privacy.html` — privacy policy for the app + Chrome extension; its "network connections" list must stay in sync with the README table in the App repo. Linked as `/privacy` (GitHub Pages resolves the `.html`).
- `404.html` — not-found page.
- Design/content rationale: [`docs/marketing/LANDING_PAGE_SPEC.md`](https://github.com/TubeFold/App/blob/main/docs/marketing/LANDING_PAGE_SPEC.md) in the App repo.

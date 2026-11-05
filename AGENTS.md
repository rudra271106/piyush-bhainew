# AGENTS.md

## Architecture
A static, single-file site. Everything (markup, styles, script) lives in `public/index.html`. `netlify.toml` publishes `public/` and has no build command.

## Key files
- `public/index.html`: the landing page
- `netlify.toml`: Netlify build config (static publish only)

## Conventions / notes
- Keep it dependency-free: no bundler, no package.json, unless a real feature needs one.
- The Telegram invite URL appears twice (the `TARGET_URL` constant and the CTA `href`). Keep them in sync.
- The countdown starting value appears in three places (`timeLeft`, `totalTime`, and the initial text in `#seconds`). Keep them equal.
- Theme colors are CSS custom properties in `:root`.

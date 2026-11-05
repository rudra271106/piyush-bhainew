# Piyush Bhai — Official VIP Access

A single-page, mobile-first landing page that introduces the Piyush Bhai VIP channel and sends visitors to the private Telegram invite. It shows a live status badge, perk highlights, and a 17-second countdown ring, then redirects automatically. A "Join" button lets visitors go right away.

## Technologies
- Plain HTML, CSS and vanilla JavaScript (no framework, no build step)
- Google Fonts (Outfit) and Font Awesome icons loaded from a CDN
- Hosted on Netlify as a static site (`public/` is the publish directory)

## Run locally
Open `public/index.html` in a browser, or run `netlify dev --port 8889` from the project root.

## Editing
- Telegram link: update `TARGET_URL` in the script **and** the `href` of the `#tgBtn` button.
- Countdown length: update `timeLeft` and `totalTime`, plus the starting number in `#seconds`.


# Nova Viva Corporate Christmas Gifts 2026

A single-page ordering form for HR teams. They choose a voucher tier (Restore, Renew, Reset), set quantities, write a thank-you note with a live gift-card preview, and send the generated request to Nova Viva by WhatsApp or email.

No build step, no dependencies. Everything (logos and photo included) lives in `index.html`.

## Edit

Open `index.html` and change:

- `TIERS` in the script: package names, prices and inclusions.
- `WA` and `MAIL` constants: WhatsApp number (country code, no `+`) and email.
- Validity dates: search for "December 2026".

## Run locally

Double-click `index.html`.

## Deploy

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root. Live at `https://<username>.github.io/<repo>/`.
- **WordPress host:** upload to `public_html/corporate-gifts/index.html`.

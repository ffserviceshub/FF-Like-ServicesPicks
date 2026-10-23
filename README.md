# FF ServicesPicks Website

Responsive Free Fire Likes package website with a WhatsApp order form.

## Files

- `index.html` — complete website HTML, CSS, package data, and JavaScript.
- `README.md` — setup and deployment instructions.

## Run the website

1. Extract this ZIP file.
2. Open `index.html` in a modern browser, or upload it to a static website host.
3. Select a package and complete the order form.
4. Review the WhatsApp message and press Send yourself.

No framework, package installation, or build step is required.

## Configuration

Open `index.html` and find the `SETTINGS` object near the bottom:

- `whatsappShortLink` — WhatsApp contact link.
- `whatsappBusinessNumber` — WhatsApp number in international digits-only format (country code included; no `+`).
- `bkashNumber` — bKash Send Money number.
- `packages` — package names, daily targets, durations, and prices.

Verify all numbers, prices, and service terms before publishing.

## Order form requirements

- Free Fire UID: digits only, 5–20 digits.
- Payment method: bKash Send Money (Nagad is marked Coming Soon).
- Enter a Transaction ID or sender mobile number; at least one is required.
- Never share passwords, account login details, payment PINs, or OTPs.
- Opening WhatsApp does not confirm an order. Payment must be checked manually.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Mobile form troubleshooting

The page avoids automatically focusing the UID field after a package is selected and removes the app wrapper's hidden overflow so mobile browsers can scroll the form normally. If a browser still jumps when the keyboard opens, test the deployed page in Chrome rather than an embedded website editor preview.

## Disclaimer

FF ServicesPicks is an independent service page and is not affiliated with or endorsed by Garena or Free Fire. Package totals are estimates/targets; service availability and permanent-package terms must be confirmed with the admin.

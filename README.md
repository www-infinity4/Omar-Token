# Omar-Token

Minimal single-page demo for a personal auction token:

- Sign in with name/email (stored locally in browser only)
- Token buy price is **$1 per token**
- Token spend value grows over time (about +$1/day based on days since token purchase)
- Buyers submit a PayPal payment request in this demo flow (proof upload is not implemented)
- Token requests are approved after 24 hours
- 100 public-domain film entries sourced from Internet Archive (archive.org)
- Films play inline in a custom-branded page player — no YouTube, no external navigation
- Spending supports decimal token amounts so users can receive value as change
- Auction listing supports bidder sign-up and bidding

## Run

Open `index.html` in a browser.

Optional: set `localStorage.omarPayPalEmail` to your PayPal address before use.

## Security note

This demo does **not** use, require, or store any GitHub personal access token (PAT).

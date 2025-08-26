# Holid-site
“HOLID 🌴 Built on Solana • Fast, fearless, community-first. In HOLID we trust.”
# HOLID — Website

Simple, fast static site for HOLID (Built on Solana).

## Files
- `index.html` — single page site
- `styles.css` — styles
- `script.js` — small UX enhancement
- `assets/` — SVG placeholders for Mr. Holiday + Solana badge + favicon

## Quick Preview
Open `index.html` in your browser.

## Deploy (pick one)
### GitHub Pages
1. Create a new repo, e.g. `holid-site`
2. Upload all files
3. Settings → Pages → Deploy from branch → `main` → `/root`
4. Wait 1–2 minutes, your site is live.

### Netlify (drag & drop)
1. Go to netlify.com → New site from Git
2. Or drag the folder onto the dashboard
3. Done.

### Vercel
1. vercel.com → New Project
2. Import repo or drag the folder
3. Deploy.

## Customize
- Replace `assets/mr_holiday.svg` with your final mascot art.
- Update Telegram link in the "Join the Telegram" button.
- Edit tokenomics values in the Tokenomics section.

## Notes
- Keep **HOLID** in ALL CAPS.
- Mr. Holiday rules: coin face + sunglasses, $-sign shirt, white gloves, green pants/shoes, matching arms, permanent smile.


## Configure
Open `index.html` and replace:
- `HOLID_MINT_ADDRESS` with your actual Solana token mint (e.g., `So11111111111111111111111111111111111111112` for SOL, but use your HOLID mint).
- `TELEGRAM_URL` with your Telegram group link.
- `X_URL` with your official X (Twitter) profile link.

The Buy buttons use Jupiter at `https://jup.ag/swap/SOL-HOLID?outputMint=HOLID_MINT_ADDRESS`.
A Solscan link is included for transparency.

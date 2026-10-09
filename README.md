# 1STTHENWILSON PILOT — prototype

This is a mobile-friendly static dashboard prototype for a Deriv digit-options bot.

## What works
- Four selectable contract-type buttons: Digit Matches, Digit Differs, Digit Over, Digit Under
- Demo/real mode selector (real mode is intentionally disabled)
- Fixed, Martingale and D'Alembert staking selectors
- Editable stake and session-risk settings
- Start/Stop preview controls

## What does not work yet
- It is **not connected to Deriv**
- It does not authenticate accounts, read balances, stream ticks, buy contracts, or place trades
- The risk settings are UI-only and do not enforce limits against live trading

## Publish free with GitHub Pages
1. Create a new public GitHub repository named `1stthenwilson-pilot`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site and open the URL it provides.

## Before connecting real trading
The next version needs Deriv's current supported authentication flow (prefer OAuth rather than asking you to paste a secret token into the page), API connection handling, contract validation, and server-independent session safeguards. Test with a virtual account first. Never commit API tokens, app secrets, or other credentials to GitHub.

# BYZIQO

BYZIQO's complete static frontend, hosted with GitHub Pages.

- Project: **BYZIQO**
- Network: Solana
- X: https://x.com/BYZIQOSOL
- Launch platform: https://pump.fun/
- Contract address (CA): **Pending — to be provided by the project owner.**

## Run locally

The website is a self-contained `index.html`; it requires no build step or dependency installation.

```sh
python3 -m http.server 8080
```

Open http://localhost:8080. Pages use hash routes, so direct navigation also works on GitHub Pages.

## Publish

In GitHub Settings → Pages, select **Deploy from a branch**, **main**, and **/(root)**. The `.nojekyll` file keeps this a plain static site. The owner will provide a custom domain later.

## Update launch details

Edit the `PROJECT` configuration in `index.html`. Set `contractAddress` only after the owner supplies the official CA. Set `launchConfirmed` to `true` only after launch is confirmed, then commit the update.

## Current functionality

Includes the full frontend, documentation, launch information, local agent configuration, and a Phantom address-only wallet connection. No wallet signing or transaction submission is implemented. Server authentication, cloud agents, automated trading, and live market data are not connected; historical reference content is marked in the interface.

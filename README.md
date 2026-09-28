# BYZIQO

BYZIQO's complete static frontend, hosted with GitHub Pages.

- Project: **BYZIQO**
- Website: http://byziqo.xyz/
- Network: Solana
- X: https://x.com/BYZIQOSOL
- Launch status: **Live on pump.fun**

## Run locally

The website is a self-contained `index.html`; it requires no build step or dependency installation.

```sh
python3 -m http.server 8080
```

Open http://localhost:8080. Pages use hash routes, so direct navigation also works on GitHub Pages.

## Publish

GitHub Pages deploys from **main**, **/(root)**. The `.nojekyll` file keeps this a plain static site. The existing `CNAME` binds `byziqo.xyz` and should be preserved when updating the website.

## Update launch details

Edit the `PROJECT` configuration in `index.html` only with launch details confirmed by the project owner. The confirmed launch flag controls the launch status. Project links use the pump.fun homepage; the project contract address and its copy controls are not published on this website. Keep the homepage, launch FAQ, and footer wording consistent with the configuration.

## Current functionality

Includes the full frontend, documentation, launch information, local agent configuration, and a Phantom address-only wallet connection. No wallet signing or transaction submission is implemented. Server authentication, cloud agents, automated trading, and live market data are not connected; historical reference content is marked in the interface.

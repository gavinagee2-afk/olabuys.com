# OLA website

Hand-written HTML and CSS for **OLA**, intended for **olabuys.com**.

## Files

- `index.html` — the whole page, including its CSS.
- `assets/ola-logo.png` — the original supplied black-on-white logo, unchanged.
- `.nojekyll` — serve the files directly on GitHub Pages.
- `CNAME` — the intended custom domain, olabuys.com. This file alone does not connect DNS.

Open `index.html` in a browser to view the site. Keep the `assets` folder beside it. No installation, build step, or internet connection is needed to view these files locally.

Source repository: https://github.com/gavinagee2-afk/olabuys.com

The intended host is GitHub Pages for this static logo-only page. Publish from the `main` branch at `/(root)`. Configure olabuys.com in Pages before pointing DNS at it. Until the custom domain is connected, the default Pages address is https://gavinagee2-afk.github.io/olabuys.com/.

The `CNAME` file belongs in the deployed root only when the custom domain is ready. Keeping the file locally does not deploy the site or change DNS.

## Saved design decisions

- The brand is OLA; olabuys.com is the domain, not the displayed brand name.
- Only the exact supplied logo appears in a centered header.
- The rest of the page is blank white, with no visible text, menus, buttons, or footer.
- Use normal code for future edits. Do not move this project into Lovable, GoDaddy Airo, or another AI website builder.
- No JavaScript, analytics, cookies, external dependencies, or database are used.

The logo's outer white margins are hidden with CSS, without editing its image file. Keep its rendered width and height equal to preserve the original proportions.

## Last verified

2026-11-24: desktop and 390px mobile layouts checked. The logo loads, the page has no visible text, and the mobile layout has no horizontal overflow. Check the repository's Pages settings for current deployment and custom-domain status.

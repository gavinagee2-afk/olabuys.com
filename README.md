# OLA website

Live: https://olabuys.com/
Repository: https://github.com/gavinagee2-afk/olabuys.com

## Current design

The user requested an exact visual match to millenniumcashbuyers.com and explicitly confirmed OLA is the same business and authorized carrying over the owner biography, contact details, service areas, reviews, and renovation photos. The reference layouts and styles were adapted to static HTML/CSS, with local image/font assets and OLA business text. Original review quotations preserve the Millennium Cash Buyers name.

The user explicitly requested the actual ALO logo. alo-logo.svg and alo-favicon.png were obtained from the official aloyoga.com page and applied as requested. The business text and domain remain OLA and olabuys.com.

67 static pages including home, how it works, about, contact, service areas, seller situations, policies, and linked blog articles. All page files are at the root and navigation uses .html URLs to work directly on GitHub Pages.

## Functionality

ola-site.js handles mobile and seller menus, review expansion/navigation, owner biography expansion, before-and-after sliders and photo selection.

Offer forms prepare an email addressed to millenniumcashbuyers@gmail.com. They open the visitor's email app and explicitly require pressing Send there. This is not automatic backend delivery; no server, SMTP service, CRM, or SMS provider has been connected. The original reference server/React scripts and analytics were removed. Do not show a sent confirmation before actual delivery.

## Deployment and search

GitHub Pages main / root. Preserve CNAME and Google Search Console meta verification. URL-prefix Search Console property is verified. Sitemap lists the local static pages. GoDaddy A @ = 185.199.108.153; www CNAME = gavinagee2-afk.github.io. HTTPS is enforced.

## Checks

2026-11-25: desktop/mobile visual checks, 390px layout without horizontal overflow, mobile menu, review navigation, comparison slider, and local file/link checks.

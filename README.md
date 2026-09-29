# kuardio.com

Website for [Kuardio](https://kuardio.com), a free iPhone app for the QardioArm blood pressure monitor.
Plain HTML and one stylesheet, served by GitHub Pages from `main` (root), custom domain in `CNAME`.

| Page | Used for |
|---|---|
| `index.html` | Home page |
| `support.html` | App Store **Support URL**, linked from the app (About) |
| `privacy.html` | App Store **Privacy Policy URL**, linked from the app (About, Support Kuardio) |
| `terms.html` | Terms of Use (Apple Standard EULA + subscription terms), linked from the app (Support Kuardio) |
| `regulatory.html` | Wellness positioning and the QardioArm's FDA / CE clearances, for App Review |

| `llms.txt` | Plain-text summary for AI assistants and crawlers (keep its facts in step with the pages) |
| `assets/img/og-image.jpg` | 1200 × 630 link preview (Open Graph / Twitter card) used by every page |

`google13bc9353887d8166.html` verifies the site in Google Search Console (URL-prefix property `https://kuardio.com/`).
Never delete it, or the site loses its verification.

`index.html` carries JSON-LD structured data (WebSite, Organization, MobileApplication, FAQPage). The FAQPage block
repeats the visible FAQ word for word: when you change the FAQ, change it there too.

The app hard-codes these URLs (`App/Sources/Model/AppLinks.swift` in the app repository), so keep the file names.
Screenshots in `assets/img/` come from the app repository's `docs/appstore/screenshots/`.

Preview locally: `python3 -m http.server 8000`, then open http://localhost:8000.

# Baldwin Tree website

Static GitHub Pages site for `baldwintreeapps.com`. No build process, remote fonts, analytics, or client-side dependencies are added by this redesign.

Preview: `python3 -m http.server 8877 --bind 127.0.0.1`.

## KeepSake submission URLs (after publication)

- Marketing: https://baldwintreeapps.com/keepsake.html
- Privacy: https://baldwintreeapps.com/keepsake-privacy.html
- Support: https://baldwintreeapps.com/keepsake-support.html
- Terms: https://baldwintreeapps.com/keepsake-terms.html

The pages use the existing publisher and support contact: Baldwin Tree LLC / baldtreesupport@protonmail.com. KeepSake is marked coming soon until a public App Store URL is available. Add the published privacy link inside the iOS app and enter the public URLs in App Store Connect. These pages do not complete App Store privacy declarations or guarantee review approval.

## Content sources and review

Lightning Numerology metadata and artwork: Apple App Store ID 6777469900, version 1.1.2, checked September 24, 2026. Existing privacy and terms URLs remain available; advertising disclosures are retained and Game Center references updated. Detailed advertising implementation statements inherited from the previous policy need confirmation against the game's current source before publishing; this repository contains only the website.

KeepSake images: existing app icon and fictional demo screenshots from the local KeepSake project. Its privacy page reflects local storage, iOS on-device transcription, user-directed exports/sharing, system backups, and support correspondence. Terms reference Apple's standard EULA, not a custom replacement license.

Review public legal copy and confirm the support mailbox remains monitored before deployment. Website changes are isolated on `codex/modern-app-website` and have not been published.

## Validation

All ten HTML pages checked for local file links and image alt text. Homepage reviewed at desktop and phone widths. Support accordion interaction checked in browser. Mobile overflow and broken image checks passed. `git diff --check` passed.

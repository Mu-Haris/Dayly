# Dayly

Public website for the **Dayly** iOS app — a paper-scrapbook countdown reminder app by [Kinex Apps](https://kinexapps.com/).

This repository hosts the public-facing pages required for App Store Connect and Google AdMob:

| Page | URL | Used for |
| --- | --- | --- |
| Landing + QR code | [`/`](https://mu-haris.github.io/Dayly/) | Marketing URL on App Store Connect |
| Privacy Policy | [`/privacy.html`](https://mu-haris.github.io/Dayly/privacy.html) | "Privacy Policy URL" field in App Store Connect (required) and AdMob |
| Terms of Use | [`/terms.html`](https://mu-haris.github.io/Dayly/terms.html) | Optional EULA URL |
| Support | [`/support.html`](https://mu-haris.github.io/Dayly/support.html) | "Support URL" field in App Store Connect (required) |
| app-ads.txt | [`/app-ads.txt`](https://mu-haris.github.io/Dayly/app-ads.txt) | AdMob publisher verification |

## Updating the App Store URL / QR code

When the app is live, edit `APP_STORE_URL` near the bottom of [`index.html`](index.html). The QR code is generated client-side from that constant.

## Updating app-ads.txt

Replace `pub-0000000000000000` in [`app-ads.txt`](app-ads.txt) with your real AdMob publisher ID once your account is approved. Also upload the same file to `https://kinexapps.com/app-ads.txt` so AdMob's crawler can verify it at the developer URL you list on App Store Connect.

© Kinex Apps

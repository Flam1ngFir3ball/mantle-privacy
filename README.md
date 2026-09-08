# mantle-privacy

Host for **mantlefit.app** legal pages (GitHub Pages). These pages are written to satisfy Apple App Store Support URL, Privacy Policy URL, and subscription Terms of Use (EULA) requirements.

| Page | URL | App Store Connect |
|---|---|---|
| Support | https://mantlefit.app/ | Version Information → **Support URL** |
| Privacy | https://mantlefit.app/privacy/ | App Information → **Privacy Policy URL** (and in-app + paywall link) |
| Terms of Use | https://mantlefit.app/terms/ | App description and in-app/paywall **Terms of Use (EULA)** link |

## Contact

Public support and privacy contact (Guideline 1.5 requires an email, address, or phone on the Support URL):

`mantlefit@outlook.com`

GitHub Issues remain an optional extra channel. Do not use Issues as the only contact method: they require a GitHub login, which App Review can reject.

## App Store Connect checklist

1. **Support URL:** `https://mantlefit.app/`
2. **Privacy Policy URL:** `https://mantlefit.app/privacy/`
3. **Terms of Use:** paste `Terms of Use: https://mantlefit.app/terms/` into the App Description (every locale). Optionally also set a custom EULA in App Information, or keep Apple’s standard EULA and still include this link.
4. **In-app / paywall:** tappable Privacy Policy and Terms of Use links (Guideline 5.1.1 and Schedule 2 / 3.1.2). Subscription title, length, and StoreKit price must appear on the paywall.
5. **App Privacy nutrition label:** match the shipping binary. Suggested baseline for Mantle as designed (on-device, no developer backend, no ads, no tracking SDKs): do not track; do not declare developer-operated collection onto your servers. Confirm HealthKit, CloudKit, StoreKit, and Photos against Apple’s “collect” definition and the privacy manifest before submission.

These pages are App Store compliance disclosures, not formal legal advice.

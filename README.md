# mantle-privacy

Public legal pages for **Mantle** (App Store Support URL + Privacy Policy URL + Terms).

## Live URLs (after GitHub Pages is on)

| Page | URL |
|---|---|
| Support | https://Flam1ngFir3ball.github.io/mantle-privacy/ |
| Privacy | https://Flam1ngFir3ball.github.io/mantle-privacy/privacy.html |
| Terms | https://Flam1ngFir3ball.github.io/mantle-privacy/terms.html |

Paste **Support** and **Privacy** into App Store Connect. The paywall links Privacy + Terms.

## Enable Pages

Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `/ (root)`**.

## Contact

Replace the GitHub Issues link on `index.html` with your real support email when you have one.

## Apple Privacy Nutrition Label (suggested)

Aligned with Mantle’s design and `PrivacyInfo.xcprivacy` (`NSPrivacyTracking` = false, no collected data types declared for developer collection):

| Question | Suggested answer |
|---|---|
| Track users? | **No** |
| Collect data linked to identity for our servers? | **No** (no Mantle backend) |
| Health & Fitness | Used for **App Functionality** only if you declare HealthKit use; data stays with Apple Health / on device, not sold |
| Purchases | Handled by Apple; not used for tracking |
| Product interaction / analytics SDKs | **None** in-app as designed |
| Photos | Add-only wallpaper save; not used for tracking |

Confirm the final Nutrition Label in App Store Connect against the shipping binary.

## Disclaimer

These pages are practical indie disclosures, not formal legal advice.

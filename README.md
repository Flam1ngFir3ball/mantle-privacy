# mantle-privacy

Legal pages for **Mantle**, hosted free on **GitHub Pages** with custom domain **mantlefit.app**.

## URLs (after DNS)

| Page | URL |
|---|---|
| Support | https://mantlefit.app/ |
| Privacy | https://mantlefit.app/privacy/ |
| Terms | https://mantlefit.app/terms/ |

Fallback while DNS propagates: https://flam1ngfir3ball.github.io/mantle-privacy/

## DNS at your registrar (free)

Point `mantlefit.app` at GitHub Pages. In the domain’s DNS panel:

### Apex (`mantlefit.app`)

Delete conflicting old A / AAAA / CNAME records for `@`, then add:

| Type | Host | Value |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

Optional IPv6:

| Type | Host | Value |
|---|---|---|
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |

### Optional `www`

| Type | Host | Value |
|---|---|---|
| CNAME | `www` | `Flam1ngFir3ball.github.io` |

In GitHub: repo **Settings → Pages → Custom domain** = `mantlefit.app`, then enable **Enforce HTTPS** once the certificate is ready (often under an hour after DNS is correct).

This repo includes a `CNAME` file for `mantlefit.app`.

## App Store Connect

- Support URL: `https://mantlefit.app/`
- Privacy Policy URL: `https://mantlefit.app/privacy/`

## Contact

Replace the GitHub Issues link on the Support page with your email when ready.

## Disclaimer

Practical indie disclosures, not formal legal advice.

# Rebellion VPN

Public website for **Rebellion VPN**, a browser-side VPN location switcher for a compatible VPN connection you already use.

The extension does not create or manage the VPN tunnel. It changes the browser's connection location for a compatible VPN service, and it is not a VPN service provider.

## Pages

| Page | Path | Purpose |
| --- | --- | --- |
| Overview | `index.html` | Product landing page |
| Support | `support.html` | Quick start and troubleshooting |
| Privacy Policy | `privacy.html` | Data practices for the extension |
| Terms of Use | `terms.html` | Licence and acceptable use |

## Local preview

```bash
python -m http.server 8137
```

Then open http://127.0.0.1:8137/.

## Deployment

Published with GitHub Pages from the `main` branch root. The site is static: plain HTML, one stylesheet, no JavaScript, no web fonts, no third-party requests.

## Brand

Dark near-black interface with cyan `#2DD4D7` and coral red `#FF4D5A`, matching the Rebellion VPN 2.0.0 extension.

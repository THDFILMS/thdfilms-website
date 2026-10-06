# THDFILMS

A responsive, static studio portfolio. No subscriptions, build process or paid dependencies are required.

## Publish with GitHub Pages

1. Create a public GitHub repository (for example `thdfilms`).
2. Upload the contents of this folder, keeping `index.html` at the repository root and preserving the `assets` folder.
3. Open **Settings → Pages**, choose **Deploy from a branch**, then **main / (root)** and Save.
4. Open the GitHub Pages URL shown in Settings once publishing finishes.

## Connect your GoDaddy domain

Confirm your exact domain first. Keep existing email records (MX, TXT and email-related CNAME records) intact.

1. Verify ownership in GitHub **Account Settings → Pages → Add a domain** using GitHub's supplied TXT record in GoDaddy DNS.
2. In the repository's **Settings → Pages → Custom domain**, enter your domain and Save before changing website DNS.
3. In GoDaddy DNS, replace conflicting website A records for `@` with these four A records:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | YOUR-GITHUB-USERNAME.github.io |

The www CNAME uses your GitHub account name, not the repository name. Review any existing AAAA or forwarding records for the website because conflicting records can prevent routing or HTTPS. Do not remove records serving other services.

4. Wait for DNS and the HTTPS certificate, then enable **Enforce HTTPS** in GitHub Pages.

Official instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Edit

- `index.html`: film links, biography, social accounts and text.
- `style.css`: design and mobile layout.
- `script.js`: mobile navigation and YouTube video dialog.
- `assets/`: locally stored artwork and photographs.

YouTube loads only after a visitor clicks a film. Third-party platforms may set cookies or collect data when opened. No analytics or contact-form backend is included.

## Content references

- THDFILMS: https://www.youtube.com/@THDFILMS
- Official links: https://linktr.ee/hafid4film
- Filmography and education: https://filmfreeway.com/HafidAbdelmoula
- Rising Star recognition: https://nmfilmandtvhalloffame.org/awards/hafid-abdelmoula/
- Music channel supplied by owner: https://www.youtube.com/@hafidtheartist

The site includes a film portfolio and Creative & Consulting services with email inquiries. No payments or bookings are processed on-site. Review hosting eligibility for this commercial services section before deployment. GitHub Pages restricts hosting websites primarily intended for commercial transactions. The domain is not configured until confirmed by the owner.

# CreConnect — Legal Documents

Production-ready legal pages for Meta App Review and platform compliance.

## Documents Included

| File | Document | Required By |
|------|----------|-------------|
| `index.html` | Legal Documents Index | — |
| `terms-of-service.html` | Terms of Service | Meta App Review |
| `privacy-policy.html` | Privacy Policy | Meta App Review |
| `data-deletion.html` | Data Deletion Instructions | Meta App Review (Facebook Login) |
| `data-deletion-request.html` | User Data Deletion Request Form | Meta App Review |
| `platform-compliance.html` | Meta Platform Compliance Statement | App Review Submission |
| `cookie-policy.html` | Cookie Policy | GDPR / ePrivacy Directive |

## Hosting

### GitHub Pages
1. Push this folder to a GitHub repository.
2. Go to Settings → Pages → Source → select `main` branch and `/legal-pages` folder (or root).
3. Your URLs will be: `https://yourusername.github.io/repo-name/terms-of-service.html`

### Netlify
1. Drag and drop this folder into [netlify.com/drop](https://netlify.com/drop).
2. Or connect your GitHub repo and set `legal-pages/` as the publish directory.

### Vercel
1. Run `vercel --cwd legal-pages` or connect the GitHub repo.
2. Set the root directory to `legal-pages/`.

## Before Going Live — Checklist

- [ ] Replace all `[Company Legal Address]` placeholders with your real address
- [ ] Replace all `legal@creconnect.com`, `privacy@creconnect.com`, `dpo@creconnect.com`, `support@creconnect.com`, `security@creconnect.com` with real email addresses
- [ ] Replace `[Jurisdiction / Country]` and `[City, Country]` in Terms of Service with your governing jurisdiction
- [ ] Replace `[Authorized Representative Name]` and `[Title]` in the Compliance Statement
- [ ] Replace `[Arbitration Body]` in Terms of Service with your chosen arbitration provider
- [ ] Update `creconnect.com` URLs throughout to your actual production domain
- [ ] Update the `_config.yml` with your actual GitHub Pages URL
- [ ] Review all dates (currently set to January 1, 2024) and update to actual publication date
- [ ] Submit the following URLs to Meta Developer Dashboard:
  - **Terms of Service URL:** `https://yourdomain.com/terms-of-service`
  - **Privacy Policy URL:** `https://yourdomain.com/privacy-policy`
  - **Data Deletion Callback URL:** `https://yourdomain.com/data-deletion`

## Meta App Review URLs to Submit

```
Terms of Service:    https://[your-domain]/terms-of-service.html
Privacy Policy:      https://[your-domain]/privacy-policy.html
Data Deletion:       https://[your-domain]/data-deletion.html
```

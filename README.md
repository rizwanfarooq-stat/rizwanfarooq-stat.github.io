# Rizwan Farooq, PhD — Academic Website

A ready-to-publish static academic website for GitHub Pages.

## Structure

- `index.html` — homepage
- `about.html` — profile and research interests
- `research.html` — research programme
- `publications.html` — publications
- `experience.html` — professional/survey experience
- `cv.html` — education and CV download
- `contact.html` — contact and academic profiles
- `assets/css/style.css` — site styling
- `files/Rizwan_Farooq_Academic_CV.pdf` — supplied CV
- `CNAME` — custom domain placeholder/configuration for `www.rizwanfarooq.com`
- `robots.txt` and `sitemap.xml` — search-engine configuration

## Publish on GitHub Pages

1. Create a GitHub account/repository named `<YOUR_GITHUB_USERNAME>.github.io`.
2. Upload all files in this package to the repository root.
3. In GitHub: Settings → Pages → choose GitHub Actions or Deploy from branch.
4. If using the domain, set the custom domain to `www.rizwanfarooq.com`.
5. Configure DNS at your domain registrar:
   - CNAME: `www` → `<YOUR_GITHUB_USERNAME>.github.io`
   - For the apex `rizwanfarooq.com`, configure GitHub Pages A records according to current GitHub documentation.
6. Enable HTTPS after DNS propagation.

## Before publishing

- Replace the initials avatar with a professional headshot if desired.
- Confirm that the domain `rizwanfarooq.com` is registered and under your control.
- Confirm your GitHub username and update the CNAME only if you choose a different domain.
- Review all publication metadata against the final publisher records.
- Do not publish private contact details such as your home address or date of birth.

This site is intentionally dependency-light: it is plain HTML/CSS and can be hosted directly by GitHub Pages without a build step.

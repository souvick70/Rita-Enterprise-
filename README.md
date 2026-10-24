# Rita Enterprise — HVAC Solutions PWA

Responsive, installable Progressive Web App for Rita Enterprise, using the RE logo extracted from the uploaded company appointment-letter letterhead.

## Company details transcribed from the supplied letterhead
- Address: Dattapukur, Gangapur, PIN 743248, 24 Pgs (N), West Bengal, India
- Phone: +91 7890378120
- Email: visitritaenterprise@gmail.com
- GSTIN: 19CNUPG5317B1ZX
- Business line: “We try to fresh air into your life...” and “Deal in HVAC solutions, materials and labours..”

## Features
- Responsive mobile-first HVAC service website
- AC installation, repair, preventive maintenance, commercial HVAC, ventilation and service-plan sections
- Tap-to-call and email links
- Enquiry form that opens a pre-filled email to the company (no server-side submission or data storage)
- PWA manifest, install prompt and service-worker offline caching
- GitHub Pages deployment workflow

## Run locally
Serve this directory over HTTP (service workers do not work from `file://`):
`python -m http.server 8000`
Then open http://localhost:8000.

## Deploy to GitHub Pages
The workflow in `.github/workflows/deploy.yml` deploys the static website from `main`. In repository Settings → Pages, select GitHub Actions as the source if required.

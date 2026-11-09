# KTril — zero-cost hosting handoff

Current GitHub Pages: https://786ktril786-dotcom.github.io/ktril-digital-studi-o/

## Deployment package
This repository is a static site. Upload the repository root (including index.html, health.html and printables.html) to a static hosting provider such as Cloudflare Pages or Netlify. No build command or framework is required. Set publish directory to the repository root (or `.` if accepted). Keep the GitHub Pages site enabled until the alternative URL passes all checks.

## Acceptance checks
1. GET /health.html returns HTTP 200 and the phrase "KTril Hosting Check".
2. GET /index.html returns HTTP 200, title "KTril — Digital Creative Studio" and links to printables.html.
3. GET /printables.html returns HTTP 200 and nine original worksheet headings.
4. Check HTTPS, navigation, mobile viewport, and print-to-PDF functionality.
5. Test from a separate network, including the user's mobile connection. Provider deployment success alone is not enough.

## Scope and safeguards
- No billing, paid plans, trials with automatic renewal, or store submission.
- No secrets or personal legal identity in public files.
- Do not delete, rename or replace this repository or modify unrelated projects.
- These printable worksheets are portfolio prototypes; commercial product readiness and Creative Fabrica requirements need separate review.
- An external hosting account and authorization are needed to actually deploy to another provider.

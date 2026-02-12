# Cloud Resume Frontend

Static frontend for selimcelem.com.

Tech:
- HTML
- CSS
- Vanilla JS
- S3 (static hosting)
- CloudFront (CDN)
- GitHub Actions (OIDC-based deployment)

Deployment:
Automatically deployed to S3 on push to main via GitHub Actions.
CloudFront cache invalidated automatically.

Backend:
Connects to API hosted in separate repo:
https://github.com/selimcelem/cloud-resume-challenge

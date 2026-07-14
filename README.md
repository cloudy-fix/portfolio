# Hariharan J Portfolio

Responsive cloud engineering portfolio for AWS, Google Cloud, OCI/IBM Cloud learning, DevOps, cloud networking, and security-oriented projects.

Live site: https://cloudy-fix.github.io/portfolio/

## What This Showcases

- AWS Certified Cloud Practitioner and Google Associate Cloud Engineer profile.
- Cloud project case studies for DNS migration, database migration, VPN, load balancing, and private storage access.
- Resume, certifications, credential proof assets, profile photo, and original cloud/tool logos.
- 3D glass background and responsive UI for desktop and mobile browsers.
- Interview-ready positioning for Google Cloud, AWS, IBM Cloud, OCI, DevOps, cloud support, and cloud security roles.

## Repo Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Main single-page portfolio site with UI, content, animation, and 3D scene logic. |
| `assets/profile.jpg` | Public profile image used in the hero section. |
| `assets/resume/` | Resume PDF and editable DOCX source. |
| `assets/certifications/` | Certification badges, AWS TN Skill certificate, and scorecard proof. |
| `assets/logos/` | Original technology and cloud logos used across the portfolio. |
| `assets/projects/` | Cloud project case-study PDFs linked from the portfolio. |
| `assets/vendor/` | Local third-party browser libraries used by the static site. |
| `docs/interview-repo-index.md` | Curated repo map for recruiters and interview preparation. |

## Deployment

The site is hosted with GitHub Pages from the `main` branch of `cloudy-fix/portfolio`.

After changes:

```powershell
git status --short
git add README.md .gitignore docs/interview-repo-index.md index.html assets
git commit -m "Improve portfolio documentation"
git push origin main
```

## Maintenance Checklist

- Keep the resume PDF and DOCX in `assets/resume/` updated together.
- Keep certification proof files under `assets/certifications/` with clear lowercase names.
- Add new project proof PDFs under `assets/projects/` with descriptive kebab-case names.
- Keep public repo links pointed to `https://github.com/cloudy-fix`.
- Avoid committing local audit exports, rendered preview folders, or personal documents from `D:\Hari docs`.


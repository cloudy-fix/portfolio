# Hariharan J Portfolio Architecture

## Purpose

Responsive cloud engineering portfolio with resume, certifications, project proof, and 3D glass UI.

## Stack

HTML, CSS, JavaScript, Three.js, GitHub Pages

## System Context

```mermaid
flowchart LR
    User["Visitor browser"] --> App["Static portfolio page"]
    App --> Data["Resume, certifications, project PDFs, logos"]
    App --> Output["Responsive portfolio experience"]
    Data --> Output
```
## Runtime Workflow

```mermaid
flowchart TD
    S1["Update resume and assets"] --> S2["Edit index and docs"]
    S2["Edit index and docs"] --> S3["Validate locally"]
    S3["Validate locally"] --> S4["Push to main"]
    S4["Push to main"] --> S5["GitHub Pages publishes site"]
```
## Production Readiness Notes

- Keep secrets in environment variables and commit only .env.example templates.
- Keep generated files, dependency folders, caches, and local databases out of version control.
- Run the GitHub Actions workflow before presenting or deploying changes.
- Update this document when the source layout, dependencies, or deployment model changes.

## Review Checklist

- Architecture diagram matches current source files.
- Workflow diagram matches the main user or data path.
- README links to this architecture document.
- CI workflow validates the project on every push and pull request.


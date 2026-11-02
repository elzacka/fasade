# Fasade

- One file, `fasade.html` (CSS, markup, JS); no build, no npm, no tests. It is large, and baked frame data (`RAMMEDATA`) makes some lines very long: Grep for the identifier, then Read with offset/limit; never read the whole file.
- Code map: README «Slik virker koden» (area → identifiers).
- Verify: open `fasade.html` in a browser and try the change; sample screenshots in `_test/` (gitignored).
- Version: `VERSJON` in `fasade.html` plus tag `vX.Y.Z`; bump policy in README «Vedlikehold». Push to `main` deploys (GitHub Pages from `main` `/`).
- Security scope: OWASP ASVS L1 (latest released edition), frontend XSS items at L2 since the origin is shared with L2 apps; Top 10, WSTG client-side. Not API, CI/CD or LLM Top 10: no API, no pipeline, no LLM feature.

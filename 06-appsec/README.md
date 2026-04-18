# Application Security

Find vulnerabilities in the app. Understand the supply chain.

## What to build

- Run OWASP ZAP (DAST) against the app from module 01 — compare what it finds vs Semgrep
- Manually test for at least one OWASP Top 10 issue (SQLi, broken auth, IDOR)
- Write a short threat model: for each component, what's the realistic threat and what mitigates it
- Generate an SBOM for the container image (Syft or Trivy)
- Enable Dependabot on the app repo

## Done when

- [ ] ZAP scan completed and findings documented
- [ ] At least one vulnerability manually verified and fixed
- [ ] Threat model written (doesn't need to be long — a table is fine)
- [ ] SBOM generated
- [ ] Notes written up

## Notes

See [notes/](notes/)

## Project repos

_None yet._

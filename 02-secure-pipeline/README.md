# Secure Pipeline

Wire security into CI/CD. Fix secrets handling.

## What to build

- GitHub Actions workflow that builds the image, runs SAST (Semgrep), scans with Trivy, and fails on critical findings
- Remove hardcoded secrets from the app — use env vars, then GitHub Actions secrets
- Add a pre-commit hook to catch secrets before they're committed (gitleaks or detect-secrets)

## Done when

- [ ] Pipeline runs on every push and fails if critical issues found
- [ ] No hardcoded secrets in the codebase
- [ ] Pre-commit hook blocks accidental secret commits
- [ ] Notes written up

## Notes

See [notes/](notes/)

## Project repos

_None yet._

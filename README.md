[![CI - build & security](https://github.com/NelsonKimori/ci-secure-demo/actions/workflows/ci.yml/badge.svg)](https://github.com/NelsonKimori/ci-secure-demo/actions/workflows/ci.yml)
# CI Secure Demo

**TL;DR:** Node app + Docker with GitHub Actions pipeline that runs `npm audit` and Trivy scan.

## What I built
- Small Node server, Dockerfile, and a CI workflow.
- Demonstrates CI + dependency scanning and container scanning.

## Where to look
- Workflow: `.github/workflows/ci.yml`
- App files: `index.js`, `package.json`, `Dockerfile`

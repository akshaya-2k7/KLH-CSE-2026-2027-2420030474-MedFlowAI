# Security and DevSecOps Baseline

- Spring Security authentication and securely hashed passwords
- JWT validation and RBAC at gateway/service boundaries
- Least-privilege role and resource access
- `.env` excluded from Git; placeholders only in `.env.example`
- No Gemini, JWT, PostgreSQL, or AWS secrets in source, UI, logs, images, or documentation
- HTTPS, validation, safe errors, rate limits, timeouts, and audit/correlation IDs
- Synthetic healthcare data only; no real patient or confidential institutional information
- Backend-only Gemini communication
- Prompt validation, minimum-necessary context, provider fallback, and human approval
- Pull requests, reviews, dependency hygiene, and security tests
- SonarQube for static analysis, Trivy for dependency/image/configuration scans, and OWASP ZAP for dynamic testing

Only authentic tool-generated findings may be placed in `results/`.


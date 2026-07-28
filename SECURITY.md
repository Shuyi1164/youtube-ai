# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in YTAI, please report it privately.

**Do not open a public issue for security vulnerabilities.**

Use GitHub's private vulnerability reporting:

1. Go to https://github.com/vibheksoni/youtube-ai/security/advisories/new
2. Click "Report a vulnerability"
3. Provide a clear description and steps to reproduce

You will receive a response within 72 hours. If the vulnerability is confirmed,
a fix will be prioritized and a security advisory will be published.

## Scope

- Authentication bypass, data leakage, or injection vulnerabilities in the SDK
- Exposure of sensitive data through the API or CLI
- Download path traversal or arbitrary file write
- SSRF or request smuggling through the InnerTube client

## Out of scope

- YouTube rate limiting or IP blocking (expected behavior)
- InnerTube API changes that break functionality (report as a regular issue)
- Public InnerTube client configuration values embedded in source code

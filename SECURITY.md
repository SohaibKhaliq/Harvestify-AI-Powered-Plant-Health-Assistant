# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability, please do not open a public issue. Report privately by emailing the repository maintainer.

**Response timeline:**
- Acknowledgment within 48 hours
- Investigation within 5 business days

## Best Practices

- The `.env` file should contain your Azure ML endpoint credentials — never commit it
- The Azure Container Instance endpoint in `app.py` is a demo endpoint; replace with your own
- Use environment variables for all API keys and endpoints
- Run `pip-audit` regularly to check for dependency vulnerabilities

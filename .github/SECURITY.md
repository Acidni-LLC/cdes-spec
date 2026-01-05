# Security Policy

## Reporting Vulnerabilities

If you discover a security vulnerability in CDES schemas, please report it responsibly.

**DO NOT** open a public GitHub issue for security vulnerabilities.

### Contact

Email: **<security@acidni.com>**

### What to Include

1. Description of the vulnerability
2. Steps to reproduce
3. Potential impact
4. Suggested fix (if any)

### Response Timeline

| Timeline | Action |
|----------|--------|
| 24 hours | Acknowledgment |
| 72 hours | Initial assessment |
| 7 days | Detailed response |

## Scope

**In Scope:**

- Schema validation bypass vulnerabilities
- Data integrity issues
- Specification ambiguities that could lead to security issues

**Out of Scope:**

- Third-party implementations
- Hypothetical issues without proof

## Security Best Practices for Implementers

1. **Always validate** incoming data against CDES schemas
2. **Set limits** on input size and nesting depth
3. **Sanitize** data before display
4. **Log** validation failures for monitoring

---

**Disclosure Policy:** We follow coordinated disclosure with a 90-day timeline.

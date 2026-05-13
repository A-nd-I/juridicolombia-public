# Security Policy

## Reporting Security Vulnerabilities

If you discover a security vulnerability in JuridiColombia, please help us maintain the security of this project by reporting it responsibly.

### How to Report

**Please DO NOT create a public GitHub issue for security vulnerabilities.**

Instead, please email your findings to:
- andimoggo@gmail.com

When reporting a vulnerability, please include:
- Description of the vulnerability
- Steps to reproduce (if applicable)
- Potential impact
- Suggested fix (if you have one)

### Response Timeline

We aim to:
1. Acknowledge receipt of your report within 48 hours
2. Provide an initial assessment within 5 business days
3. Release a security patch as soon as possible

### Scope

Security vulnerabilities we care about:
- ✅ Exposure of sensitive data (credentials, API keys, personal information)
- ✅ Cross-Site Scripting (XSS) vulnerabilities
- ✅ Injection attacks (SQL, Command, etc.)
- ✅ Authentication/Authorization bypass
- ✅ Storage security issues
- ✅ Dependency vulnerabilities

Out of scope:
- ❌ UI/UX issues
- ❌ Documentation improvements
- ❌ Performance issues (unless they enable attacks)
- ❌ Third-party services outside our control

## Security Best Practices

### For Users

1. **Keep the extension updated** - Always use the latest version from the Chrome Web Store
2. **Review permissions** - This extension only requests `storage` permission
3. **Don't share your data** - Never share your browser with others or store sensitive information in custom links

### For Developers

1. **Code Review** - All code changes go through review before merging
2. **Dependency Updates** - We regularly update dependencies to patch security issues
3. **No Secrets in Code** - Never commit secrets, API keys, or credentials
4. **HTTPS Only** - All external links use HTTPS

## Known Limitations

- This extension runs locally in your browser (no server backend)
- Your saved links are stored in your browser's local storage
- Data synchronization across devices uses Chrome's sync storage

## Security Disclosure

We believe in responsible disclosure. If you report a vulnerability to us privately, we will:
1. Work on a fix
2. Release the fix
3. Credit you in the release notes (if desired)

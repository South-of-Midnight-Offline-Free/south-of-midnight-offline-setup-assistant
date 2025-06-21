# 🔒 Security Policy

## 🛡️ Supported Versions

We provide security updates for the following versions of South of Midnight Offline Setup Assistant:

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | ✅ Currently supported |
| 2.0.x   | ✅ Security updates only |
| 1.x.x   | ❌ No longer supported |

## 🚨 Reporting a Vulnerability

If you discover a security vulnerability in our project, please help us address it responsibly.

### 📧 How to Report

**For security issues, please email us directly instead of creating a public issue:**

**Email**: security@southofmidnight-offline.com
**Subject**: [SECURITY] Brief description of the vulnerability

### 📋 What to Include

Please provide as much information as possible:

1. **Description**: Clear explanation of the vulnerability
2. **Impact**: What could an attacker accomplish?
3. **Reproduction**: Step-by-step instructions to reproduce
4. **Environment**: OS version, software versions, hardware details
5. **Proof of Concept**: Screenshots, logs, or demo code (if safe to share)
6. **Suggested Fix**: If you have ideas for remediation

### ⏱️ Response Timeline

- **Initial Response**: Within 48 hours of receiving your report
- **Assessment**: Within 5 business days, we'll assess and confirm the issue
- **Fix Development**: Timeline depends on severity and complexity
- **Release**: Security fixes are prioritized and released ASAP
- **Disclosure**: We'll coordinate with you on responsible disclosure

### 🏆 Recognition

We believe in recognizing security researchers who help keep our community safe:

- **Hall of Fame**: Recognition in our security acknowledgments
- **Coordinated Disclosure**: We'll work with you on timing of public disclosure
- **Credit**: Attribution in release notes and security advisories (if desired)

## 🔐 Security Best Practices

### For Users

1. **Download Only from Official Sources**
   - Use our GitHub releases page
   - Verify file checksums when provided
   - Avoid downloading from third-party sites

2. **Keep Software Updated**
   - Enable automatic updates if available
   - Check for new releases regularly
   - Read security advisories

3. **Secure Your System**
   - Keep Windows and drivers updated
   - Use reputable antivirus software
   - Don't run with unnecessary administrator privileges

4. **Game Installation Security**
   - Only point the assistant to legitimate South of Midnight installations
   - Don't modify core game files
   - Back up your game saves before using the assistant

### For Developers

1. **Code Security**
   - Follow secure coding practices
   - Validate all user inputs
   - Use secure communication protocols
   - Implement proper error handling

2. **Dependencies**
   - Keep all dependencies updated
   - Regularly audit third-party libraries
   - Use tools like Dependabot for automated updates

3. **Access Control**
   - Use principle of least privilege
   - Secure API keys and tokens
   - Implement proper authentication/authorization

## 🚫 Security Scope

### What We Cover
- Vulnerabilities in our application code
- Security issues in our build/release process
- Malicious code injection possibilities
- Unauthorized access to user data
- Privilege escalation vulnerabilities

### What We Don't Cover
- Social engineering attacks
- Physical access to user devices
- Issues in third-party dependencies (unless we can fix them)
- South of Midnight game vulnerabilities (report to Compulsion Games)
- Operating system vulnerabilities
- Network infrastructure issues

## 📊 Security Measures

### Current Protections

1. **Code Signing**
   - All releases are digitally signed
   - Verify signatures before installation

2. **Minimal Permissions**
   - Application requests only necessary permissions
   - No unnecessary system access

3. **Secure Communication**
   - HTTPS for all web communications
   - Certificate validation

4. **Input Validation**
   - All user inputs are validated
   - Path traversal protection
   - Buffer overflow prevention

5. **Privacy Protection**
   - No personal data collection
   - No telemetry or tracking
   - Local operation only

### Planned Improvements

- [ ] Enhanced code signing with extended validation
- [ ] Automated security scanning in CI/CD pipeline
- [ ] Regular penetration testing
- [ ] Bug bounty program (under consideration)

## 🔍 Security Audits

### Recent Audits
- **Internal Review**: Monthly code reviews by maintainers
- **Dependency Audit**: Automated scanning via GitHub Security Advisories
- **Static Analysis**: Regular SAST scans for common vulnerabilities

### Audit History
- No major security issues discovered to date
- Regular minor updates for dependency vulnerabilities
- Continuous monitoring for new threats

## 📞 Contact Information

### Security Team
- **Lead Security Contact**: security@southofmidnight-offline.com
- **Project Maintainer**: @EliasChandler
- **Emergency Contact**: Available via Discord (@EliasChandler)

### Response Team
Our security response team includes:
- Lead Developer
- Code Review Specialists
- Community Representatives

## 🏅 Hall of Fame

We thank the following security researchers for their responsible disclosure:

*No security vulnerabilities have been reported yet. Be the first to help us improve security!*

## 📚 Additional Resources

### Security Guidelines
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Microsoft Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl)
- [GitHub Security Best Practices](https://docs.github.com/en/code-security)

### Related Policies
- [Privacy Policy](PRIVACY.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Contributing Guidelines](CONTRIBUTING.md)

---

**Remember**: Security is a shared responsibility. Help us keep the South of Midnight offline gaming community safe! 🛡️ 
# Contributing to Healthcare Readmission AI

Thank you for contributing! This is a healthcare AI project with strict ethical and legal guidelines.

## Code of Conduct

All contributors must:
- **Protect Patient Privacy**: Never use real patient data without IRB approval
- **Follow Regulations**: HIPAA, GDPR, and healthcare compliance
- **Be Transparent**: Document model limitations and harms
- **Ensure Equity**: Minimize bias across demographics

## Legal Requirements

### Data
- NEVER commit real patient data
- Use synthetic/de-identified data only
- No PII (Personally Identifiable Information)
- Ensure HIPAA compliance

### Security
- No API keys, credentials, or secrets
- Use .gitignore for sensitive files
- Review security guidelines

## Contribution Process

1. Fork the repository
2. Create feature branch: `git checkout -b feature/name`
3. Follow PEP 8 for Python
4. Add tests for new code
5. Update documentation
6. Use conventional commits (feat:, fix:, docs:, security:)

## Ethical Guidelines

### Model Development
- Document limitations and failure modes
- Test for bias across groups
- Include uncertainty estimates
- Validate on diverse populations

### Interpretability
- Use SHAP or similar methods
- Provide feature importance
- Make predictions interpretable

## Prohibited

❌ NO:
- Real patient data
- Healthcare records
- Credentials or API keys
- Clinical claims without validation
- Discriminatory features
- Removing disclaimers

## PR Review Checklist

Your PR will be reviewed for:
- Legal compliance
- Data privacy (synthetic only)
- Security (no secrets exposed)
- Ethics & fairness
- Code quality & tests

## Security Issues

Find a vulnerability?
- Email security@example.com
- Don't create public issues
- Include: description, impact, steps

## Healthcare Compliance

Before submitting PR:
- [ ] No real patient data
- [ ] No PII or credentials
- [ ] HIPAA considered
- [ ] Limitations documented
- [ ] Bias assessed
- [ ] Tests passing
- [ ] License reviewed

Thank you for contributing responsibly!


# Aura Workforce - STRIDE Threat Modelling Report

## 1. Objective
Identify potential security threats in Aura Workforce using STRIDE.

## 2. System Components
- Employee / User
- Administrator
- Web / Mobile Client
- API Gateway
- Authentication and Authorization
- Workforce Application
- Identity Provider / SSO
- Database / Employee Records
- File Storage
- Audit Logs and Monitoring

## 3. Trust Boundaries
- TB1: User device to public API.
- TB2: Application to database and file storage.
- TB3: Aura Workforce to external services.

## 4. STRIDE Threats

| ID | STRIDE Category | Potential Threat | Security Control |
|---|---|---|---|
| T01 | Spoofing | Attacker impersonates an employee. | MFA |
| T02 | Tampering | Employee data is modified without permission. | Input validation |
| T03 | Repudiation | Admin denies a sensitive action. | Audit logging |
| T04 | Information Disclosure | Private employee data is exposed. | Encryption and access control |
| T05 | Denial of Service | Excessive requests affect availability. | Rate limiting |
| T06 | Elevation of Privilege | Employee obtains admin access. | RBAC and least privilege |

These are potential threats, not confirmed vulnerabilities.

## 5. Risk Assessment
Assess likelihood and impact as Low, Medium, or High.
Prioritize high-impact and high-likelihood threats.

## 6. Recommended Security Controls
1. Enable multi-factor authentication.
2. Apply role-based access control.
3. Validate and authorize requests on the server.
4. Encrypt sensitive data.
5. Maintain audit logs.
6. Apply API rate limits.
7. Review user permissions regularly.
8. Test backups and recovery.

## 7. Assumptions
This is a conceptual threat model. Verify the architecture and
controls with the system owner before treating threats as confirmed.

## 8. Evidence
Attach the STRIDE diagram PNG and screenshots.

## 9. Completion Checklist
- [ ] Diagram exported as PNG
- [ ] Trust boundaries identified
- [ ] STRIDE threats documented
- [ ] Risks assessed
- [ ] Security controls recommended
- [ ] Evidence saved

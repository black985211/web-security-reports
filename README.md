# COMP6443 Web Security Reports

Security assessment reports produced for **COMP6443 Web Application Security** at UNSW Sydney (Term 1, 2026).

The reports document the discovery, exploitation, risk assessment, and remediation of vulnerabilities in authorised course environments. Personal names and student IDs on the cover pages have been redacted.

## Reports

| Report | Scope | Document |
| --- | --- | --- |
| Report 1 | 19 findings across authentication, access control, injection, server-side security, and session management | [View Report 1](./report%201.pdf) |
| Report 2 | 16 findings focused on browser-side security, unsafe content handling, and client-side trust boundaries | [View Report 2](./report%202.pdf) |

## Topics Covered

- SQL injection and command injection
- Insecure direct object references and forced browsing
- Authentication, MFA, SSO, JWT, and session weaknesses
- File upload vulnerabilities and remote code execution
- Server-side request forgery and internal service exposure
- Stored, blind, and DOM-based cross-site scripting
- Content Security Policy bypasses
- HTTP response splitting and DOM clobbering
- Risk classification and remediation guidance

## Repository Structure

```text
.
├── README.md
├── report 1.pdf
└── report 2.pdf
```

## Responsible Use

This repository is provided for educational and portfolio purposes. The techniques described in these reports were used only against systems explicitly authorised for the COMP6443 course.

Do not use the payloads, methods, or proof-of-concept material against systems without the owner's explicit permission.

## Privacy

Names and student IDs displayed on the report cover pages have been removed. The reports may still contain course-specific challenge data, example payloads, and historical testing endpoints. Treat the documents as security-sensitive material when sharing or redistributing them.

## License

No open-source license is granted. All rights are reserved by the report authors, and third-party trademarks and course materials remain the property of their respective owners.

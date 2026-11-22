# Security Policy

## Supported products

| Product | Channel | Notes |
|---------|---------|--------|
| SENRAPP Android | Google Play (`com.senrappmobile`) | Official channel only |
| SENRAPP iOS | App Store (id `6819724219`) | Official channel only |
| Public website | https://senrapp.com | Static trust / legal pages |

Unofficial APKs, sideloads, or third-party stores are **out of scope** and unsupported.

## Reporting a vulnerability

Email: **hello@senrapp.com**  
Subject prefix: `[SECURITY]`

Please include:

1. Affected surface (app version / store build, website URL, or API behaviour you observed)  
2. Steps to reproduce (proof-of-concept preferred)  
3. Impact assessment (confidentiality / integrity / availability)  
4. Whether you plan public disclosure and your preferred timeline  

Do **not** include real user personal data in reports. Redact phone numbers, message content, and tokens.

## Response expectations

- Acknowledgement: best-effort (no contractual SLA)  
- Preferred languages: Turkish, English  
- We may ask clarifying questions before remediation  

## Safe harbor (good faith)

If you make a good-faith effort to avoid privacy violations, service disruption, and data destruction, and you report privately first, we will not pursue legal action for that research. This does not authorize:

- Accessing other users’ accounts or data  
- Denial-of-service or spam  
- Social engineering of SENRAPP staff or users  
- Exploitation of findings beyond what is needed to demonstrate impact  

## Out of scope (examples)

- Reports from automated scanners with no demonstrated impact  
- Missing security headers on third-party CDNs we do not control  
- Theoretical issues without a practical attack path  
- CSAM, fraud facilitation, or any illegal content requests (zero tolerance)

## Public summary

High-level posture (not a penetration-test certificate): https://senrapp.com/guvenlik.html  
Machine-readable contact: https://senrapp.com/.well-known/security.txt  

Full responsible-disclosure notes: [RESPONSIBLE-DISCLOSURE.md](./RESPONSIBLE-DISCLOSURE.md)

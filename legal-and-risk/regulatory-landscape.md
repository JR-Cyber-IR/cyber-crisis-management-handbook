# Regulatory Landscape

## Overview

This document provides a comprehensive overview of the regulatory requirements organizations must comply with when responding to cybersecurity incidents. The regulatory landscape varies significantly by jurisdiction, industry sector, and the type of data involved.

## Major Regulatory Frameworks

### European Union

#### RGPD (Règlement Général sur la Protection des Données)
**Notification Deadline**: 72 hours from discovery of breach
**Scope**: Organizations processing personal data of EU residents
**Key Obligations**:
- Notify supervisory authority within 72 hours (when risk to rights and freedoms)
- Document all breaches
- Implement appropriate security measures
- Conduct Data Protection Impact Assessment (DPIA)

**Fines**: Up to €20 million or 4% of global annual revenue (whichever is higher)

#### NIS2 Directive (Network and Information Security Directive 2)
**Notification Deadline**: 
- Preliminary alert: 24 hours
- Full report: 72 hours
- Final report: 30 days

**Scope**: Essential and important entities in critical sectors
**Key Obligations**:
- Report significant incidents to national authority
- Implement security and risk management measures
- Conduct incident investigations
- Notify customers and public if required

#### DORA (Digital Operational Resilience Act)
**Notification Deadline**: 15 minutes to 1 hour (time-critical operational impact)
**Scope**: Financial entities and critical infrastructure providers
**Key Obligations**:
- Report ICT incidents immediately
- Escalate significant incidents within 24 hours
- Maintain incident logs
- Conduct impact assessments

### United States

#### SEC Requirements
**Notification Deadline**: Form 8-K filing within 4 business days (public companies)
**Scope**: Publicly traded companies with material impact
**Key Obligations**:
- Disclose material cybersecurity incidents
- Describe impact and response
- Identify responsible parties

#### State Data Breach Notification Laws
**Notification Deadline**: Varies by state (typically 30-60 days)
**Scope**: All organizations handling resident data
**Key Variations**:
- California (CCPA): 30 days
- New York: As expeditiously as possible
- Massachusetts: As expeditiously as possible, but no later than the most expedient time possible

### Canada

#### PIPEDA (Personal Information Protection and Electronic Documents Act)
**Notification Deadline**: Notify individuals as soon as reasonably practicable
**Scope**: Private sector organizations
**Key Obligations**:
- Assess whether notification is necessary
- Notify Privacy Commissioner
- Implement privacy safeguards

### Australia

#### Privacy Act (Notifiable Data Breaches Scheme)
**Notification Deadline**: As soon as reasonably practicable
**Scope**: Australian Privacy Principles-regulated entities
**Key Obligations**:
- Assess likely serious harm
- Notify affected individuals and Privacy Commissioner
- Document breach details

## Industry-Specific Regulations

### Financial Sector

#### PCI-DSS (Payment Card Industry Data Security Standard)
**Scope**: Organizations handling payment card data
**Key Requirements**:
- Notify payment processors within 30 days
- Conduct forensic investigation
- Maintain audit logs

#### Gramm-Leach-Bliley Act (GLBA)
**Scope**: Financial institutions in the United States
**Notification Deadline**: Varies by state
**Key Obligations**:
- Develop comprehensive security program
- Notify customers of breaches
- Report to regulators

### Healthcare

#### HIPAA (Health Insurance Portability and Accountability Act)
**Notification Deadline**: 60 days from discovery
**Scope**: Covered entities and business associates (US)
**Key Obligations**:
- Notify affected individuals
- Notify media (if >500 individuals)
- Report to HHS Secretary
- Implement administrative safeguards

### Telecommunications

#### BEREC Guidelines
**Scope**: Electronic Communications Services Providers (EU)
**Key Obligations**:
- Report incidents to national regulator
- Notify subscribers if personal data compromised
- Implement security measures

## Regulatory Bodies & Contact Information

### European Union
- **EDPB** (European Data Protection Board) - Coordinates GDPR enforcement
- **ENISA** (EU Agency for Cybersecurity) - Provides guidance and support
- **ANSSI** (France) - National Cybersecurity Agency
- **BSI** (Germany) - Federal Office for Information Security

### United States
- **FTC** (Federal Trade Commission) - Consumer protection
- **SEC** (Securities and Exchange Commission) - Public company disclosures
- **CISA** (Cybersecurity and Infrastructure Security Agency) - Critical infrastructure

### International
- **Privacy Commissioners** by jurisdiction
- **National Cybersecurity Agencies** by country

## Compliance Matrix

| Regulation | Geographic Scope | Data Type | Notification Deadline | Regulatory Body |
|---|---|---|---|---|
| RGPD | EU | Personal Data | 72 hours | National DPA |
| NIS2 | EU | Critical Systems | 24-72 hours | National Authority |
| DORA | EU | Financial Systems | 15 min-1 hour | National Authority |
| SEC | US | Publicly Traded Co. | 4 business days | SEC |
| State Laws | US | Resident Data | 30-60 days | State AG |
| PIPEDA | Canada | Personal Data | ASAP | Privacy Commissioner |
| Privacy Act | Australia | Personal Data | ASAP | Privacy Commissioner |
| HIPAA | US | Health Data | 60 days | HHS Secretary |
| GLBA | US | Financial Data | Varies | State Regulators |

## Key Determination Factors

When assessing which regulations apply:

1. **Data Type**: Personal data, financial data, health data, etc.
2. **Data Subject Location**: Where customers/users are located
3. **Organization Location**: Where the company is based
4. **Organization Type**: Public/private, critical infrastructure, etc.
5. **Data Volume**: Number of affected individuals
6. **Breach Type**: Data theft, ransomware, service disruption, etc.
7. **Risk Level**: Likelihood of harm to affected individuals

## Practical Implications for Crisis Response

✅ **Multi-Jurisdiction Compliance**: Organizations with international presence must comply with all applicable regulations

✅ **Strict Timelines**: Most regulations have tight notification deadlines - establish rapid notification procedures

✅ **Documentation**: Maintain detailed incident documentation for regulatory compliance and potential investigations

✅ **Legal Consultation**: Engage legal counsel immediately to assess regulatory obligations

✅ **Transparency**: Regulatory bodies often view proactive disclosure more favorably than reactive reporting

## References

- [RGPD Official Text](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- [NIS2 Directive](https://eur-lex.europa.eu/eli/dir/2022/2555/oj)
- [DORA Regulation](https://eur-lex.europa.eu/eli/reg/2023/2663/oj)
- [SEC Cybersecurity Rules](https://www.sec.gov/rules/final/33-11038.pdf)
- [HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- [NIST Framework](https://www.nist.gov/cyberframework)

---

**Last Updated**: January 2026

**Version**: 1.0

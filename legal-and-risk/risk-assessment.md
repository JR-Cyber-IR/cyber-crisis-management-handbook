# Risk Assessment & Classification

## Overview

This document provides methodologies for assessing incident severity, determining regulatory notification requirements, and evaluating the impact of cybersecurity incidents.

## Risk Assessment Framework

### Key Assessment Criteria

#### 1. Data Sensitivity

- **Critical**: Personal data (names, SSN, financial data, health data)
- **High**: Business-sensitive data (intellectual property, trade secrets)
- **Medium**: Internal operational data
- **Low**: Public or non-sensitive data

#### 2. Scope of Exposure

- **Critical**: >10,000 data subjects affected
- **High**: 1,000-10,000 data subjects affected
- **Medium**: 100-1,000 data subjects affected
- **Low**: <100 data subjects affected

#### 3. Likelihood of Harm

- **High**: Data exfiltrated, ransomed, or publicly released
- **Medium**: Data accessed but encryption status unclear
- **Low**: Data accessed but not extracted, minimal sensitive content
- **Very Low**: No evidence of data extraction

#### 4. Type of Data Subject

- **Vulnerable**: Minors, elderly, financial vulnerability
- **Standard**: General population
- **Corporate**: Business entities

### Risk Matrix

| Data Sensitivity | Scope | Harm Likelihood | Regulatory Notification |
|---|---|---|---|
| Critical | >10,000 | High | Mandatory (24-72 hrs) |
| Critical | >10,000 | Medium | Likely (72 hrs) |
| Critical | >10,000 | Low | Assess (72 hrs) |
| High | 1,000-10,000 | High | Mandatory (72 hrs) |
| High | 1,000-10,000 | Medium | Likely (72 hrs) |
| Medium | 100-1,000 | High | Likely (72 hrs) |
| Medium | <100 | Any | Assess |
| Low | Any | Any | Unlikely |

## Classification Levels

### Level 1: Critical (Red)
**Criteria**: Breach of Critical + High Scope + High Likelihood of Harm

**Actions**:
- Immediate notification to regulators (within 24 hours)
- Executive crisis team activation
- Public disclosure likely
- Customer notification mandatory
- Law enforcement notification
- Board-level reporting

**Timeline**: Regulatory notification within 24 hours

### Level 2: High (Orange)
**Criteria**: Critical data OR High scope OR High likelihood of harm

**Actions**:
- Regulatory notification required (within 72 hours)
- Crisis team activation
- Customer notification likely
- Media monitoring
- Legal review mandatory

**Timeline**: Regulatory notification within 72 hours

### Level 3: Medium (Yellow)
**Criteria**: Moderate data sensitivity AND scope AND likelihood

**Actions**:
- Risk assessment required
- Regulatory consultation recommended
- Customer notification assessment
- Documentation required

**Timeline**: Assessment within 48 hours

### Level 4: Low (Green)
**Criteria**: Low data sensitivity OR minimal scope OR unlikely harm

**Actions**:
- Internal documentation
- No regulatory notification required
- No customer notification required
- Standard incident response

**Timeline**: No specific notification deadline

## Assessment Questionnaire

Answer the following questions to determine risk level:

### Data Classification
1. ☐ Does the breach involve personal data (names, SSN, contact info)?
2. ☐ Does the breach involve financial data (credit card, bank account)?
3. ☐ Does the breach involve health/medical data?
4. ☐ Does the breach involve proprietary/trade secret data?
5. ☐ Does the breach involve authentication credentials?

### Scope Determination
6. How many individuals are affected?
   - ☐ >10,000
   - ☐ 1,000-10,000
   - ☐ 100-1,000
   - ☐ <100

7. Geographic scope?
   - ☐ International/Multi-country
   - ☐ EU (triggers GDPR)
   - ☐ US Multiple states
   - ☐ Single jurisdiction

### Harm Assessment
8. ☐ Has data been exfiltrated (confirmed or reasonably likely)?
9. ☐ Has data been publicly released or sold?
10. ☐ Is ransomware involved with data exfiltration threat?
11. ☐ Have threat actors claimed possession of data?
12. ☐ Is the data still encrypted or secure?

### Impact Evaluation
13. ☐ Is the organization a public company (triggers SEC filing)?
14. ☐ Is this a material event for investors?
15. ☐ Will customers/stakeholders likely discover this?
16. ☐ Is media attention likely?

## Scoring & Determination

**Critical Risk (Mandatory Notification)**: 
- 4+ YES answers from questions 1-5 AND
- 6+ YES answers from questions 8-12 AND
- 10,000+ affected individuals

**High Risk (Likely Notification)**:
- 2+ YES answers from questions 1-5 AND
- 2+ YES answers from questions 8-12 AND
- 1,000+ affected individuals

**Medium Risk (Assessment Required)**:
- 1+ YES answer from questions 1-5 AND
- 1+ YES answer from questions 8-12 AND
- 100+ affected individuals

**Low Risk (No Notification Required)**:
- Minimal data sensitivity OR
- <100 affected individuals OR
- No evidence of harm likelihood

## Documentation

Document all risk assessments with:
- Assessment date and time
- Assessor name and title
- Answers to questionnaire
- Risk determination and rationale
- Recommended actions
- Regulatory obligations identified

---

**Last Updated**: January 2026

**Version**: 1.0

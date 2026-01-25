# Notification Procedures

## Overview

This document provides step-by-step procedures for notifying regulatory authorities, customers, and other stakeholders of cybersecurity incidents in compliance with applicable laws and regulations.

## Pre-Incident Preparation

### Establish Notification Contacts

Maintain an updated list of regulatory contacts:
- **Data Protection Authority (DPA)** contact information
- **National Cybersecurity Authority** contact information
- **Industry-Specific Regulator** contacts
- **Customer notification escalation contacts**
- **Legal counsel** contacts
- **PR/Communications** contacts

### Pre-Approve Notification Templates

- Develop notification templates that comply with regulatory requirements
- Have legal review and approve templates before an incident
- Include template versions in multiple languages if applicable

## Incident Assessment Phase

### Step 1: Determine Affected Data Types
**Timeline**: Immediately (within 1 hour)

- Identify what personal data was affected
- Identify what financial data was affected
- Identify what health data was affected
- Identify what other regulated data was affected
- Document data location and scope

### Step 2: Risk Assessment
**Timeline**: Within 4 hours

Assess the likelihood of harm to affected individuals:
- **High Risk**: Direct personal data exposure, ransomware with exfiltration
- **Medium Risk**: Encrypted data exposed but encryption keys compromised
- **Low Risk**: Data accessed but not exfiltrated, minimal sensitive content

### Step 3: Determine Applicable Regulations
**Timeline**: Within 2 hours

Consult the Regulatory Landscape document to identify all applicable regulations:
- EU Regulations (RGPD, NIS2, DORA)
- US Regulations (SEC, State Laws, HIPAA, GLBA)
- International Regulations (PIPEDA, Privacy Act, etc.)

### Step 4: Identify Regulatory Bodies
**Timeline**: Within 4 hours

Based on applicable regulations, identify the regulatory bodies requiring notification:
- Primary supervisor/competent authority
- Multiple regulators (if multi-jurisdiction incident)
- Secondary regulatory bodies

## Notification Execution

### Authority Notification Template

**Required Information**:
1. Incident date and time of discovery
2. Nature and scope of the breach
3. Categories and approximate number of data subjects
4. Categories of personal data involved
5. Likely consequences for data subjects
6. Measures taken or proposed to address the breach
7. Contact point for further information
8. Assessment of whether notification to data subjects is necessary

**Notification Channels**:
- **Email**: Submit to official regulatory email addresses
- **Web Portal**: Use national regulator's incident reporting portal
- **Phone**: For incidents with critical/emergency status

### Customer Notification

**When Required**:
- When there is a reasonably likely risk of harm to customers
- When required by contractual obligations
- When required by applicable regulations
- When proactive transparency is strategically beneficial

**Content Requirements**:
- Incident description in clear, non-technical language
- What personal information was affected
- What happened and what we found
- What measures we're taking
- Resources available to customers (credit monitoring, etc.)
- Customer support contact information

**Notification Methods**:
- Email (primary for personal data notification)
- Website notices
- Media announcements (for large-scale breaches)
- Direct mail (when email addresses may be compromised)

## Timing & Deadlines

### RGPD Notification Timeline

| Action | Deadline | Responsible Party |
|--------|----------|-------------------|
| Initial assessment | 4 hours | CISO / Legal |
| Notify supervisory authority | 72 hours | Legal / DPO |
| Notify data subjects | Without undue delay | Communications / DPO |
| Document breach | Immediately | CISO / Legal |

### NIS2 Notification Timeline

| Action | Deadline | Responsible Party |
|--------|----------|-------------------|
| Preliminary alert | 24 hours | CISO / National Authority Liaison |
| Full incident report | 72 hours | CISO / Legal |
| Final investigation report | 30 days | CISO / Legal |

### SEC Notification Timeline (Public Companies)

| Action | Deadline | Responsible Party |
|--------|----------|-------------------|
| Assess materiality | 4 business days | Legal / CFO / CEO |
| File Form 8-K | 4 business days | Investor Relations / Legal |
| Public disclosure | 4 business days | PR / CEO |

## Multi-Jurisdiction Notification

### Step 1: Regulatory Mapping

1. Identify all jurisdictions where customers/data subjects are located
2. For each jurisdiction, identify applicable regulations
3. Create a regulatory requirements matrix
4. Identify conflicting requirements and develop reconciliation strategy

### Step 2: Phased Notification Approach

**Phase 1 (Within 24 hours)**:
- Notify primary regulatory authorities (GDPR DPA)
- Issue preliminary customer notification if required
- Activate incident response protocol

**Phase 2 (Within 72 hours)**:
- Notify secondary regulatory authorities
- Issue comprehensive customer notification
- Prepare public statement

**Phase 3 (Within 30 days)**:
- Submit final investigation reports
- Complete regulatory follow-up
- Implement corrective measures

## Documentation Requirements

### Breach Registry

Maintain a centralized breach registry documenting:
- Incident date and discovery date
- Data types affected
- Number of data subjects affected
- Notification date and method
- Regulatory authority notified
- Regulatory response
- Corrective measures implemented
- Incident status (open/closed)

### Evidence Preservation

Maintain detailed documentation of:
- All notifications sent (with timestamps)
- Regulatory correspondence
- Evidence of regulatory compliance (confirmation receipts)
- Customer response and feedback
- Media coverage (if applicable)
- Internal communications regarding the incident

## Escalation Matrix

### Notification Decision Tree

```
1. Is personal data exposed?
   NO  → No GDPR notification required (but check other regulations)
   YES → Continue

2. Is there a risk of harm to data subjects?
   LOW  → Regulatory notification only
   HIGH → Regulatory + Customer notification

3. Is the incident material (public company)?
   NO  → Regulatory notification only
   YES → Regulatory + SEC filing + Public disclosure

4. Is media attention likely?
   NO  → Regulatory notification + customer notification
   YES → Regulatory notification + customer notification + PR statement
```

## Special Cases

### Ransomware Incidents
- Assess whether data was exfiltrated
- Determine if encrypted data equals "exposed" data
- Consider threat actor claims (often unreliable)
- Notify if exfiltration reasonably likely

### Third-Party Incidents
- Notify data processor/service provider
- Assess controller responsibility
- Determine joint liability
- Coordinate notification timeline with processor

### Insider Threats
- Assess intentional vs. accidental disclosure
- Determine scope of authorized access
- Consider regulatory differences in liability
- Document policy violations

## Regulatory Contacts by Region

### European Union
- **French CNIL**: breach-notification@cnil.fr
- **German BfDI**: contact through www.bfdi.bund.de
- **Austrian DPA**: dsb@dsb.gv.at

### United States
- **State AGs**: Contact primary state authority
- **SEC**: Contact Enforcement Division for material incidents
- **FTC**: Consumer Sentinel Network

### Canada
- **Office of the Privacy Commissioner**: Contact through website

## Post-Notification Actions

1. **Monitor Regulatory Response**
   - Track all regulatory communications
   - Respond to information requests within deadlines
   - Prepare for regulatory investigations

2. **Customer Support**
   - Establish dedicated customer support hotline
   - Track customer inquiries and complaints
   - Provide credit monitoring resources

3. **Incident Resolution**
   - Document all remediation measures
   - Schedule follow-up notification once resolved
   - Assess policy improvements needed

---

**Last Updated**: January 2026

**Version**: 1.0

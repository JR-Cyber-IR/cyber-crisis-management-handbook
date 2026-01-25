# 🎈 Risk Assessment & Classification

Methodologies for evaluating incident severity and determining regulatory notification requirements.

---

## 📄 Assessment Criteria

### Data Sensitivity
- **Critical**: Personal data (SSN, credit cards, health records)
- **High**: Business-sensitive data (IP, trade secrets)
- **Medium**: Internal operational data
- **Low**: Public or non-sensitive data

### Scope of Exposure
- **Critical**: >10,000 data subjects
- **High**: 1,000-10,000 data subjects
- **Medium**: 100-1,000 data subjects
- **Low**: <100 data subjects

### Likelihood of Harm
- **High**: Data exfiltrated, ransomed, or publicly released
- **Medium**: Data accessed but encryption status unclear
- **Low**: Data accessed but not extracted
- **Very Low**: No evidence of data extraction

## 🌆 Risk Classification Levels

### Level 1: Critical (Red)
**Trigger**: Critical data + High scope + High likelihood
- **Timeline**: Notify within 24 hours
- **Actions**: Executive crisis team, public disclosure, law enforcement notification

### Level 2: High (Orange)
**Trigger**: Critical data OR High scope OR High likelihood
- **Timeline**: Notify within 72 hours
- **Actions**: Crisis team activation, customer notification likely, legal review mandatory

### Level 3: Medium (Yellow)
**Trigger**: Moderate across all factors
- **Timeline**: Assess within 48 hours
- **Actions**: Risk assessment required, regulatory consultation recommended

### Level 4: Low (Green)
**Trigger**: Low sensitivity OR minimal scope OR unlikely harm
- **Timeline**: Standard processing
- **Actions**: Internal documentation only

## ✅ Risk Determination Questionnaire

**Data Classification** (Count YES answers)
1. ☐ Personal data (names, SSN, contact info)?
2. ☐ Financial data (credit cards, accounts)?
3. ☐ Health/medical data?
4. ☐ Proprietary/trade secret data?
5. ☐ Authentication credentials?

**Scope** (Select one)
6. Affected individuals: ☐ >10,000 ☐ 1,000-10,000 ☐ 100-1,000 ☐ <100

**Harm Assessment** (Count YES answers)
7. ☐ Data exfiltrated (confirmed or likely)?
8. ☐ Data publicly released or sold?
9. ☐ Ransomware with exfiltration threat?
10. ☐ Threat actors claimed possession?

**Impact Evaluation**
11. ☐ Public company (SEC filing trigger)?
12. ☐ Material impact for investors?
13. ☐ Customer/stakeholder discovery likely?
14. ☐ Media attention likely?

## 🔜 Scoring Guidance

**Critical Risk** (Mandatory notification):
- 4+ YES from Data Classification AND
- 3+ YES from Harm Assessment AND
- 10,000+ affected individuals

**High Risk** (Likely notification):
- 2+ YES from Data Classification AND
- 2+ YES from Harm Assessment AND
- 1,000+ affected individuals

**Medium Risk** (Assessment required):
- 1+ YES from Data Classification AND
- 1+ YES from Harm Assessment AND
- 100+ affected individuals

**Low Risk** (No notification required):
- Minimal sensitivity OR <100 individuals OR no harm evidence

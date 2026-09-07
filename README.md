# Microsoft Purview Security & Compliance Labs

## Overview

Hands-on Microsoft Purview and Microsoft 365 security and compliance labs covering data protection, classification, DLP, auditing, retention, insider risk, encryption, and data security posture management.

This repository documents the configuration, testing, and validation of Microsoft Purview security and compliance controls in a Microsoft 365 lab environment.

## Labs Completed

| # | Lab | Key Capability |
|---|---|---|
| 01 | [Purview Audit](./01-purview-audit/) | Audit |
| 02 | [Device Onboarding](./02-device-onboarding/) | Endpoint DLP |
| 03 | [Insider Risk Analytics](./03-insider-risk-analytics/) | Insider Risk |
| 04 | [Set User Passwords](./04-set-user-passwords/) | M365 Administration |
| 05 | [Administrative Roles](./05-assign-administrative-roles/) | Entra ID |
| 06 | [Custom Sensitive Information Types](./06-create-custom-sensitive-information-types/) | Data Classification |
| 07 | [SIT Confidence](./07-modify-sensitive-information-type-confidence/) | Classification |
| 08 | [EDM Security Group](./08-create-security-group-edm-access/) | Security Groups |
| 09 | [EDM Classifier](./09-create-edm-classification-data-source/) | Exact Data Match |
| 10 | [Keyword Dictionary](./10-create-keyword-dictionary/) | Classification |
| 11 | [Custom SIT Testing](./11-test-custom-sensitive-information-types/) | SIT Validation |
| 12 | [Sensitivity Labels](./12-create-and-manage-sensitivity-labels/) | Information Protection |
| 13 | [Message Encryption](./13-deploy-message-encryption/) | Email Protection |
| 14 | [Retention](./14-implement-and-manage-retention/) | Data Governance |
| 15 | [Audit & DLP](./15-purview-audit-dlp-activity-retention/) | Audit & DLP |
| 16 | [DSPM](./16-purview-dspm/) | Data Security Posture Management |
| 17 | [Validation](./17-validation-sensitivity-dlp-retention/) | Security Control Validation |

## Skills Demonstrated

- Microsoft Purview
- Microsoft 365 Security & Compliance
- Data Loss Prevention (DLP)
- Sensitivity Labels
- Sensitive Information Types (SITs)
- Exact Data Match (EDM)
- Microsoft Purview Audit
- Retention Policies & Labels
- Insider Risk Management
- Message Encryption
- Data Security Posture Management (DSPM)
- Microsoft Entra ID
- SharePoint Online, OneDrive & Exchange Online

## Key Capabilities Implemented

**Classify → Protect → Detect → Monitor → Retain → Investigate → Remediate**

The labs demonstrate practical implementation of Microsoft Purview controls for protecting sensitive organizational data and managing compliance risks.

## Validation

The final validation confirmed that the configured controls operated as expected:

- Sensitivity labels successfully applied and enforced in Word.
- Business justification successfully triggered for highly confidential content.
- DLP successfully detected sensitive employee information in Outlook.
- DLP successfully blocked the test email.

## Documentation & Evidence

Each lab contains:

- `README.md` documentation
- Configuration screenshots
- Implementation steps
- Validation evidence
- Task outcomes

## Learning Reference

The labs were completed using Microsoft Learning training materials and lab guidance.

- [Microsoft Learning](https://microsoftlearning.github.io/)

## Outcome

Successfully completed and documented a comprehensive Microsoft Purview security and compliance lab portfolio demonstrating practical experience with **information protection, data classification, DLP, auditing, retention, insider risk, encryption, and DSPM**.
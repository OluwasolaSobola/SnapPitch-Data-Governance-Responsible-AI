# SnapPitch – Data Governance & Responsible AI Implementation

**Real-World EPI-Tech Internship Project | 2026**

## Project Overview

SnapPitch is an AI-powered CV generation platform that enables users to register, upload a CV, build a professional profile, generate tailored CVs, and save and manage their information.

I worked on SnapPitch as part of my **Data Governance internship with EPI-Tech**, serving as **Data Governance Team Lead** and leading an eight-member Data Governance team.

The platform evolved from a session-only architecture to a registered-user model with persistent data storage. This introduced additional governance requirements around personal data, Data Quality, privacy, classification, access, retention and deletion, lifecycle management, governance risk, monitoring and AI processing.

The Data Governance team responded by developing and reviewing governance frameworks, controls, requirements, findings and recommendations and by seeking implementation assurance from the relevant technical teams.

---

## My Role

**Data Governance Team Lead (Internship)**  
**EPI-Tech Internship Programme | 2026**

I led an **eight-member Data Governance team**, coordinating governance deliverables, reviews and stakeholder engagement across:

- Data Governance
- Data Quality
- AI Governance
- Responsible AI
- Data Privacy
- Data Classification
- Data Lifecycle Management
- Data Retention & Deletion
- Authentication & Access Governance
- Governance Risk & Controls
- Monitoring & Audit Requirements

I collaborated with **Software Engineering and wider project stakeholders** as the platform architecture and requirements evolved.

The Data Governance team defined, reviewed and challenged governance requirements, documented findings and recommendations, and sought assurance regarding implementation where appropriate. Technical implementation remained the responsibility of the relevant technical teams.

---

## Governance Challenge

SnapPitch initially operated using session-only processing. As the platform evolved to support registered users and persistent storage, it would retain and process user profile information and uploaded CVs.

This created increased governance requirements around:

- Personally Identifiable Information (PII)
- Data Quality
- Data Classification & Sensitivity
- Privacy & Consent
- Authentication & Access
- Data Storage
- Data Lifecycle Management
- Retention & Deletion
- Monitoring & Audit
- Governance Risk
- AI Processing & Transparency

The governance framework was updated to reflect the changing platform architecture and associated data risks.

---

## Key Governance Deliverables

### Governance & Data Management

- Data Governance Framework
- Data Inventory
- Data Dictionary
- Business Glossary
- Governance Responsibilities & Decision Rights
- Governance Implementation Requirements

### Data Quality

- Data Quality Assessment
- Data Quality Dimensions
- Data Quality Rules
- Data Validation Requirements
- Governance Review Findings & Recommendations

### Privacy & Lifecycle

- Data Classification Framework
- Privacy Policy
- Privacy Notice
- Cookies Consent Notice
- Data Lifecycle Governance
- Data Retention & Deletion Requirements

### Risk, Access & AI Governance

- AI Governance Framework / Review
- Responsible AI Requirements
- Governance Risk Register
- Incident Response & Breach Escalation
- Authentication & Access Governance
- Administrative & Developer Access Policy
- Monitoring & Audit Requirements

---

## Data Quality Approach

Data Quality was incorporated into the governance framework using dimensions including:

- Accuracy
- Completeness
- Consistency
- Validity
- Relevance
- Timeliness
- Integrity
- Accessibility

These principles were translated into practical requirements including valid email structures, mandatory field completion, supported CV upload formats, maximum upload-size requirements, authentication before uploads and validation of submitted information.

The team subsequently reviewed the user-facing platform against governance and Data Quality expectations.

Testing identified weaknesses in validation across some input fields where values inconsistent with expected formats or data types could be accepted.

This created potential risks to profile accuracy, reporting, analytics and downstream processing.

The Data Governance team recommended strengthening validation through appropriate field-level rules, format requirements, mandatory controls and user-facing error handling.

---

## AI Governance & Responsible AI

Because SnapPitch incorporated an external Large Language Model (LLM) for AI-assisted CV generation, AI governance formed part of the governance review.

Key considerations included:

- Transparency around AI-assisted CV processing
- Privacy considerations when personal information is processed by AI
- Appropriate governance of third-party AI processing
- Responsible use of AI-generated outputs
- User awareness of how uploaded information may be processed
- Governance oversight and accountability
- Retention and lifecycle considerations
- Monitoring and implementation assurance

The team developed and reviewed **AI Governance and Responsible AI requirements** and incorporated AI-related considerations into the wider governance framework and risk review.

---

## Governance Review

The team conducted an end-to-end governance review covering:

- User Registration
- Resume Upload
- Profile Creation
- Work Experience
- Skills Management
- Dashboard
- Account Settings
- Privacy & Security
- Governance Controls

The review considered data collection practices, privacy and security controls, Data Quality and alignment with previously developed governance requirements.

---

## Key Findings & Recommendations

### 1. Privacy Information

**Finding:** Privacy information was not observed before personal information was collected during registration.

**Recommendation:** Display appropriate privacy information before or at the point of data collection.

### 2. Resume Processing Transparency

**Finding:** Users had limited information explaining how uploaded CVs were processed, whether AI was involved, how long information would be retained and how uploaded information could be removed.

**Recommendation:** Improve transparency around CV processing, AI use, retention and deletion.

### 3. Email Verification

**Finding:** Email verification was not enforced during testing.

**Risk:** Invalid or unauthorised email addresses could affect account integrity and Data Quality.

**Recommendation:** Implement mandatory email ownership verification.

### 4. Cookie Management

**Finding:** No cookie consent banner was observed during testing.

**Recommendation:** Confirm cookie usage and introduce an appropriate consent mechanism where non-essential cookies are used.

### 5. Input Validation

**Finding:** Some input fields accepted information inconsistent with expected formats or data types.

**Risk:** Poor-quality information could affect user profiles, reporting, analytics and downstream processing.

**Recommendation:** Strengthen validation controls across relevant fields.

### 6. Google Authentication

**Finding:** Google authentication functionality required clarification during review.

**Recommendation:** Confirm whether the functionality was intended for the relevant release and test/address implementation where applicable.

---

## Architecture-to-Governance Thinking

| Platform Area | Governance Consideration | Governance Response |
|---|---|---|
| PostgreSQL / Persistent Profiles | Stored personal data | Classification, access, lifecycle and retention requirements |
| CV / Resume Storage | PII exposure and retention | Storage, access, privacy and deletion requirements |
| Authentication & RBAC | Unauthorised access | Authentication and access-governance requirements |
| AI / LLM Processing | Privacy, transparency and responsible use | AI Governance, transparency and oversight |
| Application Monitoring | Sensitive information in logs | Monitoring, access and retention considerations |

This approach connected governance requirements with the way information was stored, processed and moved through the platform.

---

## Implementation Assurance

The Data Governance team requested confirmation or supporting evidence regarding implementation of:

- Governance artefacts
- Encryption of uploaded resumes
- Role-Based Access Control (RBAC)
- Audit logging
- Data Retention requirements
- AI Governance controls

This distinction was important: the Governance team **defined, reviewed and challenged requirements**, while technical implementation remained the responsibility of the relevant technical teams.

---

## Value Delivered

The Data Governance team's contribution helped to:

- Establish a governance foundation for the platform
- Develop governance policies, standards and controls
- Integrate Data Quality requirements into platform governance
- Establish AI Governance and Responsible AI requirements
- Conduct a structured governance review
- Identify privacy, Data Quality and transparency gaps
- Document governance findings and recommendations
- Identify governance risks and recommend appropriate controls
- Establish areas requiring implementation assurance
- Support continued governance improvement as the platform evolved

---

## Challenges & Lessons Learned

### Challenges

- Platform architecture changed during development
- Governance documentation had to evolve alongside technical requirements
- Governance required collaboration across multiple project teams
- Delivery operated within project time constraints

### Lessons Learned

- Data Governance should be considered early in product development
- Governance requirements must evolve when architecture changes
- Data Quality requires both documented rules and practical validation
- AI-enabled platforms require governance beyond traditional Data Management controls
- Cross-functional collaboration is essential
- Documentation creates accountability and traceability
- Defining a control is different from confirming its technical implementation
- Governance is a continuous process rather than a one-time activity

---

## Core Competencies Demonstrated

**Data Governance | Data Quality | AI Governance | Responsible AI | Data Management | Data Privacy | UK GDPR | Data Classification | Data Lifecycle Management | Data Retention | Business Glossary | Data Dictionary | Governance Risk & Controls | Access Governance | Governance Review | Stakeholder Collaboration | Governance Documentation**

---

## Project Portfolio

The repository includes the portfolio presentation:

**SnapPitch_Data_Governance_Responsible_AI_Implementation_2026.pptx**

It provides a visual summary of the project, my governance role, key deliverables, Data Quality work, governance review findings, recommendations and Responsible AI considerations.

---

## About Me

I am a **Data Governance and Data Quality professional** with practical experience supporting governance frameworks, controls, Data Quality practices, AI Governance and Responsible AI across digital and AI-enabled environments.

My wider portfolio demonstrates experience across **Microsoft Purview, Microsoft Azure, Data Management, Data Stewardship, Master Data Management, SQL-based Data Quality analysis, Power BI, Tableau and Excel**.

# hospitality-ai-prompt-library
AI prompt library for hotel accommodation and food &amp; beverage operations.
# AI-Powered Hospitality Operations & Guest Experience Management

## 1. Project Overview

This project develops a library of 10 AI prompts designed to support operational efficiency and improve guest experience within the hospitality industry.

The project focuses on hotel accommodation and Food & Beverage (F&B) operations. It explores how generative AI can assist hotel employees and management with guest enquiries, complaint handling, service recovery, operational analysis and management reporting.

A fictional hotel business is used as the case-study context to demonstrate how AI prompts can be designed and incorporated into practical hospitality workflows.

## 2. Industry Context

The hospitality industry involves a range of interconnected services, including guest reservations, room management, housekeeping, maintenance, restaurant operations and customer service.

Hotels regularly handle guest enquiries, service requests, complaints and operational issues across different departments. These activities require timely communication, accurate information, coordination between teams and consistent service standards.

AI-powered prompting offers an opportunity to support these activities by helping employees organise information, prepare responses, identify recurring issues and generate useful management insights.

## 3. Business Problem

Hotel employees may spend considerable time manually reviewing guest feedback, categorising complaints, preparing responses and compiling operational reports.

Inconsistent complaint handling and limited analysis of recurring guest concerns can also make it difficult for management to identify underlying problems and implement improvements.

This project explores how a connected AI prompt library could help address these operational challenges while retaining appropriate human oversight.

## 4. Project Objectives

The main objectives are to:

- Develop 10 structured AI prompts relevant to hotel accommodation and F&B operations.
- Support consistent guest enquiry and complaint management.
- Assist employees in preparing professional guest communications.
- Identify recurring service issues and potential root causes.
- Support operational improvement and management decision-making.
- Evaluate the automation potential, risks and limitations of AI prompting.
- Demonstrate iterative prompt development through testing and refinement.

## 5. Project Scope

The project covers two main operational areas:

### A. Hotel Accommodation

- Guest enquiries and complaints
- Room cleanliness and housekeeping
- Maintenance-related concerns
- Reservations and check-in experiences
- Guest service and issue resolution

### B. Food & Beverage Operations

- Restaurant service complaints
- Food quality and dining experiences
- Delays in food service
- Breakfast service concerns
- Guest feedback relating to food and beverages

## 6. AI Prompt Library

The proposed library contains 10 connected prompts:

## 10-Prompt Library

The prompt library contains 10 AI-powered prompts designed to support hotel accommodation and Food & Beverage (F&B) operations.

| Prompt ID | Prompt Name | Description |
| :-------- | :---------- | :---------- |
| P01 | Guest Enquiry and Complaint Classification | Classifies incoming guest messages into enquiries, complaints, compliments and other relevant categories, identifying responsible departments and priority levels. |
| P02 | Guest Information and Issue Extraction | Extracts important guest information, complaint details, operational issues and required follow-up actions from guest messages. |
| P03 | Hotel Policy and Service-Standard Assessment | Assesses guest complaints against supplied hotel policies and service standards to identify potential non-compliance and verification requirements. |
| P04 | Guest Service Recovery Recommendations | Recommends suitable service recovery actions to resolve guest complaints and improve guest satisfaction. |
| P05 | Professional Guest Response Drafting | Generates professional, empathetic and personalised responses to guest enquiries, complaints and feedback. |
| P06 | Serious Complaint and Incident Escalation | Identifies serious guest complaints and operational incidents requiring immediate supervisor or management attention. |
| P07 | Accommodation and F&B Complaint Trend Analysis | Analyses guest feedback to identify recurring complaints, service patterns and operational performance issues. |
| P08 | Hotel Operational Root Cause Analysis | Investigates recurring operational problems and identifies possible underlying causes. |
| P09 | Hotel Operational Improvement Action Plan | Develops practical improvement actions to address identified operational problems and prevent recurrence. |
| P10 | Hotel Management Performance Report | Consolidates guest feedback trends, operational findings, root cause analysis and improvement actions into a structured report to support hotel management decision-making. |

Each prompt will be documented with its actual prompt text, intended workflow or task, problem being solved, automation potential, and risks and limitations.

## 7. AI Prompt Chaining and Proposed Workflows

This project uses prompt chaining to connect multiple AI prompts into structured hospitality workflows.

Prompt chaining involves passing the output generated by one prompt into the next prompt as input. This allows individual prompts to perform specialised tasks while contributing to a larger operational process.

The project contains two main prompt chains.

### Workflow A – Guest Complaint Management and Service Recovery

**Input:** Original guest enquiry or complaint.

1. **P01 – Guest Enquiry and Complaint Classification:** Classifies the guest message and identifies the responsible department and priority level.

2. **P02 – Guest Information and Issue Extraction:** Uses the original guest message and P01 classification output to extract relevant details and operational information.

3. **P03 – Hotel Policy and Service-Standard Assessment:** Uses the guest message, P01 classification, P02 extracted information and supplied hotel policies to assess potential service-standard gaps.

4. **P04 – Guest Service Recovery Recommendations:** Uses the complaint details and policy assessment to recommend suitable service recovery actions.

5. **P05 – Professional Guest Response Drafting:** Uses the guest complaint and recommended recovery actions to prepare an appropriate guest response.

6. **P06 – Serious Complaint and Incident Escalation:** Uses the complaint classification, extracted details and relevant safety or incident information to identify matters requiring supervisor or management escalation.

**Expected outcome:** A structured complaint management process supporting consistent assessment, service recovery, guest communication and appropriate escalation.

### Workflow B – Management Analysis and Operational Improvement

**Input:** Aggregated guest feedback, complaint records and relevant operational information.

1. **P07 – Accommodation and F&B Complaint Trend Analysis:** Analyses guest feedback to identify recurring complaints and operational patterns.

2. **P08 – Hotel Operational Root Cause Analysis:** Uses the trend analysis results and supporting operational information to investigate possible underlying causes.

3. **P09 – Hotel Operational Improvement Action Plan:** Uses the identified root causes to develop practical corrective and preventive actions.

4. **P10 – Hotel Management Performance Report:** Uses the trend analysis, root cause findings and improvement action plan to prepare a structured management report.

**Expected outcome:** Management insights, operational improvement recommendations and a consolidated performance report to support decision-making.

### Prompt Chaining and Human Oversight

The outputs from each prompt are used as inputs for subsequent prompts, where relevant. This creates a connected workflow rather than treating each prompt as an isolated AI task.

The prompt chains are designed as a proposed workflow and may be executed manually by transferring outputs between prompts or through an AI platform that supports connected workflows.

Human review remains necessary, particularly for policy assessments, serious incidents, service recovery decisions and management recommendations.

AI-generated outputs must be checked for accuracy before being used in operational decisions.

## 8. Prompt Development and Testing

The prompts will be developed and refined through an iterative process.

Each prompt will include documented versions, beginning with an initial draft and progressing through testing and improvement.

The development process will record:

- Prompt version
- Changes made
- Observed AI output
- Issues identified
- Lessons learned
- Final refined version

GitHub will be used to maintain the prompt files and provide a record of development through its commit history.

## 9. Risks, Limitations and Human Oversight

The project recognises that AI-generated outputs may contain inaccurate information, misunderstand guest concerns or produce recommendations that do not comply with hotel policies.

Key considerations include:

- **Accuracy:** Employees must verify AI-generated information before acting on it.
- **Guest privacy:** Real guest personal information and confidential hotel data must not be entered into public AI tools.
- **Policy compliance:** Recommendations must be checked against approved hotel policies and service standards.
- **Human judgement:** Employees and managers remain responsible for complaint resolution and decisions involving serious incidents.
- **Over-reliance:** AI should support employees rather than replace professional judgement.

## 10. Repository Structure

The repository will be organised as follows:

```text
hospitality-ai-prompt-library/
│
├── README.md
│
├── prompts/
│   ├── README.md
│   ├── P01_Guest_Classification.md
│   ├── P02_Guest_Information.md
│   ├── P03_Policy_Assessment.md
│   ├── P04_Service_Recovery.md
│   ├── P05_Guest_Response.md
│   ├── P06_Incident_Escalation.md
│   ├── P07_Trend_Analysis.md
│   ├── P08_Root_Cause.md
│   ├── P09_Improvement_Plan.md
│   └── P10_Management_Report.md
│
├── audit-log/
│   └── prompt-audit-log.md
│
├── testing/
│
├── sample-data/
│
└── report/
```

## 11. Expected Outcome

The expected outcome is a structured and tested AI prompt library demonstrating how generative AI can support hotel accommodation and F&B operations.

The project will evaluate the usefulness of AI prompting in improving workflow consistency, reducing repetitive administrative effort and supporting data-informed management decisions.

The effectiveness of the proposed prompts will be assessed through documented testing, observations and iterative refinement.

---


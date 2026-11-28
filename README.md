# Hospitality AI Prompt Library

**1. Project Overview**

This project develops a structured AI Prompt Library to support daily hotel operations at Cinnamon Ceylon Hotel, a hypothetical hospitality business.

The library contains 10 specialised AI prompts designed to assist hotel staff with guest enquiries, complaints, food allergy enquiries, operational analysis and management reporting.

Each prompt is developed, tested and refined through multiple versions. Testing helps identify weaknesses, improve accuracy and make the prompts more reliable for practical hospitality situations.

The project uses version control through GitHub to maintain prompt documentation, record changes and demonstrate the development process.

**2. Industry Context**

The hospitality industry depends on effective communication, consistent service delivery and timely operational decisions.

Hotel employees regularly manage:

- Guest enquiries and complaints.
- Accommodation and reservation requests.
- Food and beverage enquiries.
- Food allergies and dietary requirements.
- Service recovery and complaint escalation.
- Operational issues across departments.
- Guest feedback and management reporting.

AI can assist with these activities by organising information, identifying issues, drafting responses and supporting decision-making.

However, AI-generated information must be checked by authorised hotel employees, particularly where guest safety, food allergies, compensation, privacy or serious incidents are involved.

**3. Business Problem**

Cinnamon Ceylon Hotel requires consistent and efficient processes for handling guest enquiries, complaints and operational information.

Without structured procedures, staff may experience:

- Inconsistent guest communication.
- Important information being overlooked.
- Delays in identifying serious complaints.
- Incorrect assumptions about hotel policies or service availability.
- Inadequate handling of food allergy enquiries.
- Difficulty identifying recurring guest complaints.
- Inconsistent operational reporting.

This project addresses these challenges through a structured AI Prompt Library that supports employees while maintaining human oversight and accountability.

**4. Project Objectives**

The main objectives are to:

1. Develop 10 specialised AI prompts for hospitality operations.
2. Create structured instructions for consistent AI responses.
3. Test prompts using realistic hotel scenarios.
4. Identify weaknesses and refine prompts through multiple versions.
5. Document testing results and changes.
6. Demonstrate how prompts can work individually and as connected workflows.
7. Identify opportunities for operational improvement and automation.
8. Evaluate AI risks, limitations and the importance of human oversight.
9. Maintain project documentation and version history through GitHub.

**5. Project Scope**

The project focuses on the following hotel operational areas:

- Guest enquiry classification.
- Guest information extraction.
- Hotel policy and service-standard assessment.
- Guest service recovery recommendations.
- Professional guest response drafting.
- Serious complaint and incident escalation.
- Guest complaint trend analysis.
- Food allergy and dietary safety enquiries.
- Guest complaint investigation and handling.
- Operational management reporting.

The project demonstrates how AI prompts can support hotel employees. It does not represent a fully automated hotel management system.

**6. AI Prompt Library**

The project contains 10 specialised prompts.

| Prompt ID | Prompt Name | Main Purpose |
|---|---|---|
| P01 | Guest Enquiry and Complaint Classification | Classifies incoming guest enquiries and complaints. |
| P02 | Guest Information and Issue Extraction | Extracts important information and identifies missing details. |
| P03 | Hotel Policy and Service-Standard Assessment | Assesses enquiries against available hotel policies and service standards. |
| P04 | Guest Service Recovery Recommendations | Recommends suitable service recovery actions. |
| P05 | Professional Guest Response Drafting | Prepares professional and appropriate guest responses. |
| P06 | Serious Complaint and Incident Escalation | Identifies serious complaints and incidents requiring escalation. |
| P07 | Accommodation and F&B Complaint Trend Analysis | Analyses recurring accommodation and food and beverage complaint patterns. |
| P08 | Food Allergy Enquiry | Supports the assessment and safe handling of food allergy enquiries. |
| P09 | Guest Complaint Handling | Supports complaint investigation, resolution and follow-up. |
| P10 | Management Reporting | Organises operational information into a structured management report. |

Each prompt is documented and tested. Where improvements are identified, revised versions are created and evaluated.

**7. AI Prompt Flow and Prompt Chaining**

**7.1 Overview**

The 10 prompts support different but related hotel operational activities.

Prompt chaining means using the output of one prompt as information for another prompt. This can help create a more structured workflow by connecting different stages of a hotel task.

The proposed workflows below show how the prompts can work together. Some prompts operate independently, while others can be connected through the manual transfer of information.

**7.2 Workflow A – Guest Enquiry and Complaint Management**

**Purpose:** To support the handling of guest enquiries and complaints from initial classification through to communication and escalation.

**Prompt flow:**

1. **P01 – Guest Enquiry and Complaint Classification:** Classifies the incoming enquiry or complaint.
2. **P02 – Guest Information and Issue Extraction:** Extracts relevant details, identifies missing information and summarises the guest's concern.
3. **P03 – Hotel Policy and Service-Standard Assessment:** Assesses the issue against available hotel policies and service standards.
4. **P04 – Guest Service Recovery Recommendations:** Suggests suitable service recovery options.
5. **P05 – Professional Guest Response Drafting:** Prepares a professional response using verified information and approved actions.

**Escalation branch:**

- **P06 – Serious Complaint and Incident Escalation:** Can be used when the initial classification or subsequent assessment identifies a serious complaint, safety concern or incident requiring management attention.

**Expected outcome:** A more consistent approach to guest enquiry handling, complaint assessment, service recovery and communication.

**7.3 Workflow B – Guest Feedback and Operational Analysis**

**Purpose:** To identify recurring guest concerns and support management reporting.

**Prompt flow:**

1. **P07 – Accommodation and F&B Complaint Trend Analysis:** Reviews relevant complaint information and identifies recurring patterns.
2. **P10 – Management Reporting:** Organises verified operational information and relevant analysis findings into a structured management report.

**Expected outcome:** Improved visibility of guest complaint patterns and operational concerns to support management review and decision-making.

**7.4 Workflow C – Food Allergy and Dietary Safety**

**Purpose:** To support the careful handling of guest enquiries involving food allergies and dietary requirements.

**Prompt flow:**

1. **P08 – Food Allergy Enquiry:** Identifies the allergy concern, separates confirmed information from unknown information and identifies what must be verified.
2. The relevant kitchen or food and beverage employee checks ingredients, supplier information and possible cross-contact risks.
3. An authorised employee communicates the verified information to the guest.

**Expected outcome:** A more structured approach to food allergy enquiries, with clear identification of information requiring verification.

**Important:** AI cannot independently confirm that food is safe for a guest with an allergy. Ingredient and cross-contact information must be verified by authorised hotel staff before advice is given to the guest.

**7.5 Workflow D – Guest Complaint Handling**

**Purpose:** To support the investigation and resolution of an individual guest complaint.

**Prompt flow:**

1. **P09 – Guest Complaint Handling:** Organises the complaint, separates guest-reported information from verified facts, assesses urgency and identifies required actions.
2. Relevant hotel employees investigate the issue and check available operational records.
3. Staff confirm available solutions, guest preferences and any required management approval.
4. Serious hygiene, safety or service concerns are escalated to the appropriate manager.
5. Staff verify that agreed actions have been completed and follow up with the guest.

**Expected outcome:** More consistent complaint investigation, service recovery, escalation and follow-up.

**7.6 Prompt Chaining and Human Oversight**

The proposed prompt chains are designed to demonstrate how information can move between different prompts.

For this project, prompt chaining is a manual process. Employees transfer relevant outputs from one prompt into the next prompt where appropriate.

The project does not claim that the prompts are automatically connected to hotel systems or that actions are completed without employee involvement.

Human review remains necessary for:

- Confirming hotel policies and operational information.
- Verifying food allergy and cross-contact information.
- Approving compensation and service recovery actions.
- Escalating serious complaints and incidents.
- Checking guest communications before they are sent.
- Confirming operational actions and management recommendations.

**8. Prompt Development, Version Control and Testing**

The prompts are developed through an iterative process.

Each prompt is tested using realistic hospitality scenarios. The outputs are reviewed to identify weaknesses, unsupported assumptions, missing information and opportunities for improvement.

Where necessary, revised prompt versions are created.

The development process includes:

1. Creating the initial prompt.
2. Testing the prompt using a realistic scenario.
3. Reviewing the AI-generated output.
4. Identifying issues and limitations.
5. Updating the prompt instructions.
6. Testing the revised version.
7. Recording changes and observed effects.
8. Identifying the recommended final version.

GitHub is used to maintain project files and document changes.

The repository includes prompt documentation, evaluation records and audit information to demonstrate the development and refinement process.

**9. Automation Potential and Human Oversight**

The prompt library demonstrates opportunities to support or partially automate selected hotel tasks.

| Operational Area | Potential AI Support | Required Human Oversight |
|---|---|---|
| Guest enquiries | Classifying enquiries and extracting information | Staff verify details and availability. |
| Guest complaints | Organising complaints and suggesting actions | Staff investigate and approve resolutions. |
| Guest communication | Drafting guest responses | Staff review before sending. |
| Complaint escalation | Identifying potential serious issues | Managers assess and make escalation decisions. |
| Food allergy enquiries | Identifying risks and missing information | Kitchen or authorised staff verify safety information. |
| Complaint analysis | Identifying recurring patterns | Managers validate findings and decide actions. |
| Management reporting | Organising operational information | Managers verify data and approve decisions. |

The prompts may reduce repetitive administrative work and improve consistency.

However, they should be treated as decision-support tools rather than replacements for trained hospitality employees.

**10. Risks, Limitations and Responsible AI Use**

AI can produce inaccurate information, misunderstand guest enquiries or make assumptions when information is incomplete.

The project recognises the following risks:

**1. Inaccurate information**

AI may generate information that is incorrect or unsupported.

*Mitigation:* Employees must verify important information against reliable hotel records and approved procedures.

**2. Food allergy and guest safety risks**

Incorrect allergy information could create serious risks for guests.

*Mitigation:* Ingredient, allergen and cross-contact information must be verified by authorised kitchen or food service employees. AI must not independently confirm food safety.

**3. Unauthorised service recovery**

AI may recommend compensation or benefits that have not been approved.

*Mitigation:* Staff must follow hotel approval procedures before offering compensation or making commitments.

**4. Privacy and confidentiality**

Guest enquiries may contain personal or sensitive information.

*Mitigation:* Staff should follow hotel privacy procedures and avoid entering unnecessary personal information into AI tools.

**5. Incorrect escalation decisions**

AI may fail to recognise the seriousness of a complaint or may recommend an unsuitable priority.

*Mitigation:* Employees and managers must review serious complaints, safety issues and incidents.

**6. Over-reliance on AI**

Employees may rely too heavily on AI-generated recommendations.

*Mitigation:* AI outputs should support, not replace, employee judgement, professional knowledge and management decisions.

**11. Repository Structure**

The GitHub repository is used to organise the prompt library, testing documentation and project records.

The main project structure includes:

```text
Prompt-Library
│
├── audit_log
│   ├── prompt_audit_log.md
│
├── evaluation
│   ├── P01_Test_Results
│   ├── P02_Test_Results
│   ├── P03_Test_Results
│   ├── P04_Test_Results
│   ├── P05_Test_Results
│   ├── P06_Test_Results
│   ├── P07_Test_Results
│   ├── P08_Test_Results
│   ├── P09_Test_Results
│   └── P10_Test_Results
│
├── prompts
│   ├── P01-guest_classification
│   ├── P02-guest_information
│   ├── P03-policy_assessment
│   ├── P04-guest_service_recovery
│   ├── P05-proffessional_guest_response
│   ├── P06-serious_incident_escalation
│   ├── P07-complaint_trend_analysis
│   ├── P08-food-allergy-enquiry
│   ├── P09-guest-complaint-handling
│   └── P10-management-reporting
│   └── README.md
│
├── sample _data
│   ├── guest-feedback-samples
│
├── README.md

```

The structure provides a central location for prompt documentation, testing evidence, audit records and project information.

**12. Expected Business Benefits**

The proposed AI Prompt Library may provide the following benefits to Cinnamon Ceylon Hotel:

- More consistent guest enquiry handling.
- Improved organisation of guest information.
- More structured complaint investigation.
- Better identification of serious complaints requiring escalation.
- More consistent guest communication.
- Improved awareness of recurring guest concerns.
- Better organisation of operational information.
- Support for management reporting and decision-making.
- Reduced time spent on repetitive administrative tasks.

These are expected benefits of the proposed approach. Actual improvements would need to be measured through implementation and operational evaluation.

**13. Project Conclusion**

The Hospitality AI Prompt Library demonstrates how structured AI prompts can support different areas of hotel operations.

The project includes 10 specialised prompts covering guest enquiries, complaints, service recovery, food allergy enquiries, complaint analysis and management reporting.

Through testing, evaluation and prompt refinement, the project demonstrates the importance of clear instructions, accurate information and responsible AI use.

The proposed prompt workflows also demonstrate how prompts can be connected through manual prompt chaining to support more structured operational processes.

Although AI can assist with administrative tasks and decision support, human oversight remains essential. Hotel employees must verify information, protect guest privacy, approve operational decisions and take responsibility for guest safety and service delivery.

Overall, the project provides a structured example of how AI can be introduced into hospitality operations responsibly while supporting service consistency and operational efficiency.
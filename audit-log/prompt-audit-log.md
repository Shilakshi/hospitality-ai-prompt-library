# Prompt Development Audit Log

## Project: AI-Powered Hospitality Operations & Guest Experience Management

This audit log records the development, testing and improvement of the 10 AI prompts created for the hospitality industry, focusing on hotel accommodation and Food & Beverage (F&B) operations.

Each prompt will be tested and refined through multiple versions. The audit log will document what was changed, the observed effect of the change and the lessons learned.

## Prompt Improvement Audit Table

| Prompt ID | Prompt Name | Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|---|---|
| P01 | Guest Enquiry and Complaint Classification | v1.0 | Initial prompt created. | Testing pending. | Initial version to be evaluated. |
| P01 | Guest Enquiry and Complaint Classification | v1.1 | Added data-minimisation instructions and clearer High/Critical priority definitions. | Correctly classified both room cleanliness and potential food safety complaints. Avoided unnecessary personal information requests and flagged safety concerns for human review. | Clear privacy and escalation instructions improve the usefulness of AI classification across accommodation and F&B operations. |
| P02 | Guest Information and Issue Extraction | v1.0 | Created the initial guest information extraction prompt with structured output sections. | Correctly extracted the complaint, location, time reference and potential slip hazard. However, it included unnecessary personal information requests and incorrectly flagged a room hygiene issue as a food safety concern. | Initial prompts can extract useful information, but need clearer instructions for privacy, safety categorisation and distinguishing confirmed facts from assessments. |
| P02 | Guest Information and Issue Extraction | v1.1 | Improved privacy instructions, distinguished room hygiene from food safety, clarified confirmed facts versus assessments, and improved issue-status reporting. | Correctly extracted the guest complaint, identified the wet-floor hazard, avoided unnecessary personal information and produced a clearer operational handover. | Clear instructions about privacy, safety categorisation and factual accuracy improve the reliability of AI-generated guest information extraction. |
| Prompt ID | Prompt Name | Version | Change Made | Observed Effect | Lesson Learned |
| :-------- | :---------- | :------ | :---------- | :-------------- | :------------- |
| P03 | Hotel Policy and Service-Standard Assessment | v1.0 | Initial prompt developed to assess guest complaints against supplied hotel policies and service standards. | Identified relevant policies and potential service gaps, but sometimes treated guest-reported hazards as confirmed, assigned an unsupported risk level and did not clearly separate pre-check-in and post-complaint requirements. | Policy assessments must distinguish reported information from verified evidence and avoid unsupported risk classifications or conclusions. |
| P03 | Hotel Policy and Service-Standard Assessment | v1.1 | Improved evidence classification, separated pre-check-in and post-complaint requirements, clarified assessment outcomes and prohibited unsupported risk ratings. | Correctly distinguished guest-reported information from verified evidence, identified potential non-compliance, avoided unsupported risk ratings and identified relevant evidence for investigation. A minor wording issue remained regarding supervisor notification. | Clear assessment categories and evidence requirements improve the reliability of AI-assisted policy assessments. Human review remains necessary. |
| P04 | Guest Service Recovery Recommendations | v1.0 | Initial prompt developed to recommend service recovery actions using complaint classification, extracted information and policy assessment outputs. | Generated practical recovery recommendations but included some unsupported operational assumptions, such as room-status decisions and staff coaching without confirmed findings. | Service recovery recommendations must be practical but should not assume operational procedures, staff errors or approval requirements that have not been supplied. |
| P04 | Guest Service Recovery Recommendations | v1.1 | Improved evidence handling, conditional recommendations, approval controls and separation of completed and proposed actions. | Produced more reliable recommendations, clearly distinguished reported from verified conditions, avoided unsupported compensation and improved follow-up requirements. A minor approval-wording issue remained. | Conditional recommendations and clear evidence requirements improve the reliability of AI-assisted guest service recovery. Human review remains essential. |
| P05 | Professional Guest Response Drafting | v1.0 | To be developed. | Testing pending. | To be evaluated. |
| P06 | Serious Complaint and Incident Escalation | v1.0 | To be developed. | Testing pending. | To be evaluated. |
| P07 | Accommodation and F&B Complaint Trend Analysis | v1.0 | To be developed. | Testing pending. | To be evaluated. |
| P08 | Hotel Operational Root Cause Analysis | v1.0 | To be developed. | Testing pending. | To be evaluated. |
| P09 | Hotel Operational Improvement Action Plan | v1.0 | To be developed. | Testing pending. | To be evaluated. |
| P10 | Hotel Management Performance Report | v1.0 | To be developed. | Testing pending. | To be evaluated. |

## Evaluation Criteria

The prompts will be evaluated based on:

1. Accuracy and relevance of AI-generated outputs.
2. Clarity and consistency of responses.
3. Ability to follow the requested output format.
4. Relevance to hotel accommodation and F&B operations.
5. Usefulness for hotel employees and management.
6. Identification of risks, limitations and situations requiring human review.
7. Effectiveness of the prompt chain.

**Note:** Observed effects and lessons learned must be based on actual prompt testing. Pending entries will be updated as testing and improvements are completed.
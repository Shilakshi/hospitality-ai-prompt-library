# P10 – Hotel Management Reporting: Testing Results

## 1. Testing Information

- **Prompt ID:** P10
- **Prompt Name:** Hotel Management Reporting
- **AI Tool:** ChatGPT
- **Test Case:** Test 01 – Daily Hotel Operations Report
- **Versions Tested:** v1.0, v1.1 and v1.2
- **Test Status:** Comparative testing completed

### Test Scenario

Cinnamon Ceylon Hotel reports the following operational information:

- Occupancy: 85%
- Three rooms awaiting inspection
- Two unresolved maintenance requests
- Four recorded guest complaints
- Busy dinner service

The objective is to evaluate whether the prompt generates an accurate, structured and useful daily management report without making unsupported assumptions about hotel operations.

### Test Input

The same operational information was supplied for testing the different prompt versions to support a fair comparison.

### Expected Result

The prompt should:

- Generate a structured daily hotel management report.
- Accurately use the supplied operational information.
- Distinguish confirmed facts, potential risks and unknown information.
- Identify relevant departmental responsibilities.
- Recommend practical actions without assuming unverified conditions.
- Assign provisional priorities with clear explanations.
- Identify matters requiring management attention and verification.
- Avoid inventing operational data or making unsupported conclusions.
- Clearly identify information requiring human review.

## 2. Version 1.0 – Initial Testing Results

### Actual AI Output – Summary

The AI generated a structured daily management report covering the operational situation, key issues, departmental impact, risks, recommended actions, priority levels and management attention.

It included a priority action table and identified Housekeeping, Maintenance, Front Office and Food and Beverage as relevant departments.

### Evaluation

| Evaluation Criteria | Result |
|---|---|
| Use of supplied operational information | Successful |
| Report structure and clarity | Successful |
| Departmental impact identification | Successful |
| Risk identification | Generally successful |
| Practical recommendations | Successful |
| Priority classifications | Required improvement |
| Management attention | Successful |
| Factual accuracy | Required improvement |

### Observed Strengths

- Generated a professional and structured management report.
- Used the supplied operational information.
- Identified the relevant hotel departments.
- Recognised potential operational risks.
- Provided practical recommendations for management attention.
- Included a priority action table.
- Distinguished some known facts from potential risks.

### Identified Weaknesses

- Assumed that the three uninspected rooms were unavailable and delaying arrivals without confirmation.
- Suggested that unresolved maintenance requests might restrict room inventory without knowing their nature or severity.
- Described check-in delays as an existing operational problem without supporting evidence.
- Assigned priority levels without sufficient information about the actual severity of each issue.
- Treated recorded guest complaints as active unresolved complaints without confirming their status.
- Assumed specific operational systems and reporting arrangements without confirmation.

### Proposed Improvements for v1.1

- Do not assume uninspected rooms are unavailable or delaying arrivals.
- Require verification of the nature and severity of maintenance requests.
- Explain that priorities are provisional and may change after investigation.
- Distinguish recorded complaints from confirmed unresolved complaints.
- Separate confirmed operational information from potential risks and assumptions.
- Avoid assuming specific hotel systems or staff responsibilities unless supplied.
- Require the correct hotel name to be used consistently.

### Testing Conclusion

P10 v1.0 generated a useful management report but required improvements in factual accuracy, priority classification and operational assumptions.

The identified weaknesses provided a basis for refining the prompt in v1.1.

## 3. Version 1.1 – Refinement and Testing Results

### Actual AI Output – Summary

P10 v1.1 improved the separation of confirmed operational information from unknown details and potential risks.

The revised output used provisional priority classifications and provided explanations for recommended actions. It also improved the distinction between reported issues and information requiring verification.

### Evaluation

**Observed Strengths:**

- Improved the separation of confirmed facts and unknown information.
- Used more cautious language when describing potential operational risks.
- Provided provisional priority classifications with explanations.
- Improved the distinction between recorded complaints and confirmed operational problems.
- Identified information requiring further investigation.
- Produced a more structured and evidence-based management report.

**Identified Weaknesses:**

- Some issues were still assigned High priority without sufficient information about their severity or urgency.
- Some operational responsibilities and system references were still assumed rather than confirmed.
- Further refinement was required to ensure recommendations remained conditional on available evidence.

### Proposed Improvements for v1.2

- Require priorities to be provisional when severity information is unavailable.
- Explain what additional information is needed before confirming priority levels.
- Avoid assuming hotel systems, roles or approval arrangements.
- Clearly distinguish confirmed information, potential risks and unknown details.
- Ensure recommendations are based on supplied information and verified hotel procedures.

### Testing Conclusion

P10 v1.1 demonstrated improvements over v1.0, particularly in information handling and provisional priority explanations.

However, further refinement was required to reduce unsupported priority assignments and assumptions about operational responsibilities.

## 4. Version 1.2 – Final Testing Results

### Actual AI Output – Summary

P10 v1.2 generated a structured daily management report covering operational issues, departmental impacts, potential risks, recommended actions, priority classifications and management attention.

The response distinguished confirmed information from potential risks and unknown details. It used provisional priority classifications, explained the reasons for each priority and identified information requiring verification.

### Evaluation

| Evaluation Criteria | Result |
|---|---|
| Use of supplied operational information | Successful |
| Separation of facts and unknown information | Successful |
| Identification of potential risks | Successful |
| Departmental responsibility handling | Improved |
| Priority classification | Improved |
| Explanation of provisional priorities | Successful |
| Practical recommendations | Successful |
| Identification of verification requirements | Successful |
| Management reporting structure | Successful |

### Observed Strengths

- Clearly distinguished confirmed information from potential risks and unknown details.
- Used provisional priorities rather than presenting uncertain assessments as established facts.
- Explained the reasoning behind recommended priorities.
- Identified information requiring further verification.
- Produced practical recommendations relevant to hotel operations.
- Improved the reliability and usefulness of the management report.

### Minor Limitations

- Avoid describing 85% occupancy as high volume unless supported by the hotel's operating standards or historical data.
- Avoid describing dinner demand as a high cover volume when actual cover numbers are not supplied.
- Continue distinguishing supplied facts from assumptions.
- Human management review remains necessary before operational priorities and corrective actions are confirmed.

### Testing Conclusion

P10 v1.2 produced the strongest result following evaluation of all three versions.

It demonstrated better factual accuracy, more cautious priority classification and clearer identification of operational information requiring verification.

## 5. Version Comparison

| Evaluation Area | v1.0 | v1.1 | v1.2 |
|---|---|---|---|
| Report structure | Good | Maintained | Maintained |
| Use of supplied information | Good | Improved | Improved |
| Separation of facts and unknowns | Needed improvement | Improved | Clearer |
| Operational assumptions | Several identified | Reduced | Further controlled |
| Priority classification | Needed improvement | Provisional priorities introduced | Better explained and controlled |
| Departmental responsibilities | Some assumptions | Further refinement required | Improved |
| Risk identification | Generally successful | More cautious | More evidence-based |
| Management recommendations | Practical but some unsupported assumptions | Improved | More controlled |

## 6. Lessons Learned

The testing demonstrated that AI-generated management reports can provide useful operational summaries and recommendations, but they must not present assumptions as confirmed hotel conditions.

The main lessons were:

- Management reports should clearly distinguish confirmed facts, potential risks and unknown information.
- Priority classifications should remain provisional when severity and urgency information is incomplete.
- Operational recommendations must be based on available evidence and verified hotel procedures.
- Recorded complaints should not automatically be treated as unresolved complaints.
- Departmental responsibilities and operational systems should not be assumed.
- Management review is necessary before priorities and corrective actions are confirmed.

## 7. Overall Testing Conclusion

P10 v1.2 demonstrated improvements over v1.0 and v1.1 when tested using the same daily hotel operational scenario.

The final version produced a more structured, cautious and evidence-based management report. It improved the handling of unknown information, provisional priorities, operational risks and management recommendations.

**Testing Status:** Comparative testing completed successfully. P10 v1.2 is the recommended final version following evaluation of Versions 1.0, 1.1 and 1.2.

Human management review remains essential before operational priorities, departmental actions and management decisions are confirmed.
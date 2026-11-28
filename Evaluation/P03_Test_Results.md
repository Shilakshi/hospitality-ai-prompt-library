# P03 – Hotel Policy and Service-Standard Assessment: Testing Results

## Test 01 – Room Cleanliness Complaint

- **Prompt ID:** P03
- **Prompt Version:** v1.0
- **Test Sample:** Sample 01 – Room Cleanliness
- **Test Status:** Completed

### 1. Test Input

The original room cleanliness complaint and the corresponding P01 and P02 outputs were used.

A fictional hotel room readiness and housekeeping policy was supplied as the assessment reference.

### 2. Expected Result

The prompt should:
- Identify relevant hotel policies and service standards.
- Compare the reported guest experience with the supplied requirements.
- Identify possible service-standard gaps.
- Distinguish potential non-compliance from confirmed non-compliance.
- Identify supporting evidence and required verification.
- Highlight safety concerns requiring human review.

### 3. Actual Output Summary

P03 v1.0 identified:
- Relevant standards: Pre-check-in room cleaning, bathroom hygiene, used towel removal and floor safety.
- Preliminary outcome: Potential policy non-compliance.
- Possible gaps: Room readiness, bathroom cleanliness and wet-floor safety.
- Evidence required: Housekeeping inspection logs, PMS room-status records and maintenance records.
- Responsible department: Housekeeping.
- Recommended escalation: Housekeeping Supervisor, Front Office and Maintenance where necessary.

### 4. Evaluation

**Strengths:**
- Correctly identified relevant policy requirements.
- Connected the guest's reported experience with the supplied standards.
- Identified useful operational records for investigation.
- Recommended appropriate departmental escalation.
- Recognised the need for human verification.

**Weaknesses:**
- Some statements described reported hazards as though they were physically confirmed.
- Assigned a high risk level without a supplied risk-rating framework.
- Could distinguish more clearly between pre-check-in requirements and post-complaint response requirements.
- Some explanations could more consistently distinguish potential policy non-compliance from confirmed breaches.

### 5. Proposed Improvements for v1.1

- Clearly distinguish guest-reported conditions from physically verified conditions.
- Avoid assigning risk ratings unless an authorised risk framework is supplied.
- Separate pre-service policy requirements from post-complaint response requirements.
- Maintain conditional language when discussing possible policy non-compliance.
- Require human verification before making formal compliance conclusions.

### 6. Conclusion

P03 v1.0 successfully compared the guest complaint with the supplied fictional hotel policy and identified relevant operational gaps and investigation requirements.

However, improvements are needed to strengthen factual accuracy, risk assessment and the distinction between potential and confirmed policy non-compliance.

These improvements will be incorporated into P03 v1.1 and evaluated using the same test inputs.


## Test 02 – Room Cleanliness Complaint

- **Prompt ID:** P03
- **Prompt Version:** v1.1
- **Test Sample:** Sample 01 – Room Cleanliness
- **Test Status:** Completed

### 1. Test Input

The same original guest complaint, P01 classification output, P02 information extraction output and fictional hotel room readiness and housekeeping policy used in Test 01 were supplied.

### 2. Expected Result

The revised prompt should:
- Distinguish guest-reported information from verified evidence.
- Avoid unsupported risk ratings.
- Separate pre-check-in requirements from post-complaint response requirements.
- Distinguish potential non-compliance from confirmed non-compliance.
- Identify missing evidence and appropriate human verification.

### 3. Actual Output Summary

P03 v1.1:
- Identified potential non-compliance with pre-check-in Policy Requirements 1, 2 and 3.
- Correctly classified post-complaint Requirements 4 and 5 as unable to assess due to insufficient evidence.
- Clearly identified the wet floor and used towels as guest-reported information.
- Confirmed that no policy breaches could be established from the supplied evidence.
- Did not assign an unsupported risk rating.
- Identified relevant housekeeping, room-status and maintenance records for further investigation.
- Recommended appropriate departmental and supervisor involvement.

### 4. Evaluation

**Strengths:**
- Clearly separated guest-reported conditions from verified evidence.
- Correctly distinguished pre-check-in and post-complaint requirements.
- Used appropriate conditional language when identifying potential non-compliance.
- Avoided unsupported risk classifications.
- Provided practical evidence requirements and departmental responsibilities.
- Maintained human oversight for final compliance decisions.

**Minor limitation:**
- The management handover stated that Housekeeping Supervisor review was required under Policy Requirement 5. The wording could be clearer that supervisor notification and review are actions to be verified or arranged, rather than actions already completed.

### 5. Comparison with v1.0

Compared with v1.0, the revised version demonstrated better factual accuracy, clearer assessment categories and stronger separation between reported information and verified findings.

It also corrected the unsupported risk classification and improved the assessment of pre-check-in versus post-complaint requirements.

### 6. Conclusion

P03 v1.1 successfully addressed the main weaknesses identified during v1.0 testing.

The revised prompt produced a more structured, evidence-based and reliable preliminary policy assessment. A minor wording improvement may be considered in a future version to clarify supervisor notification responsibilities.

**Testing outcome:** Successful improvement. P03 v1.1 is suitable for the next stage of the prompt library, subject to human review of its assessments.
# P02 – Guest Information and Issue Extraction: Testing Results

## Test 01 – Room Cleanliness Complaint

- **Prompt ID:** P02
- **Prompt Version:** v1.0
- **Test Sample:** Sample 01 – Room Cleanliness
- **Test Status:** Completed

### 1. Test Input

**Original Guest Message:**

"I checked into my room this afternoon, but the bathroom was not properly cleaned. There were used towels left behind, and the bathroom floor was wet."

**P01 Classification:** Complaint – Room Cleanliness – Housekeeping – High Priority.

### 2. Expected Result

The prompt should:
- Extract the main complaint and relevant operational details.
- Identify the wet bathroom floor as a potential slip hazard.
- Distinguish provided information from missing information.
- Identify relevant follow-up requirements.
- Produce a clear handover summary for hotel staff.
- Avoid inventing information or requesting unnecessary personal details.

### 3. Actual Output Summary

P02 v1.0 successfully identified:
- Main issue: Unclean bathroom, used towels and wet floor.
- Department: Housekeeping.
- Location: Guest room bathroom.
- Time: This afternoon.
- Safety concern: Potential slip hazard.
- Immediate human attention: Required.
- Missing details: Room number and exact time.
- Handover: Recommended prompt Housekeeping intervention and guest follow-up.

### 4. Evaluation

**Strengths:**
- Correctly extracted the guest's main complaint.
- Preserved the P01 classification details.
- Identified the potential slip hazard.
- Organised the information into the required five sections.
- Produced a practical handover for hotel operations staff.

**Weaknesses:**
- Included guest name and booking reference as missing information, although these should not automatically be requested.
- Incorrectly classified the room hygiene issue under a potential food safety concern.
- Described the complaint as unresolved without explicitly distinguishing this as an assessment.
- Could provide clearer instructions for separating relevant safety follow-up questions from confirmed incident details.

### 5. Proposed Improvements for v1.1

- Improve data-minimisation instructions and avoid unnecessary requests for personal information.
- Distinguish room hygiene concerns from food safety concerns.
- Clarify how to describe issue status when resolution has not been confirmed.
- Improve the distinction between confirmed facts, reasonable assessments and information requiring verification.

### 6. Conclusion

P02 v1.0 successfully extracted and organised the main details of the room cleanliness complaint and generated a useful operational handover. However, improvements are required in privacy handling, safety categorisation and the distinction between confirmed information and inferred status.

The identified weaknesses will be addressed in P02 v1.1 and tested again to evaluate whether the changes improve the prompt's performance.


## Test 02 – Room Cleanliness Complaint (Improved Version)

- **Prompt ID:** P02
- **Prompt Version:** v1.1
- **Test Sample:** Sample 01 – Room Cleanliness
- **Test Status:** Completed

### 1. Test Input

The same original guest message and P01 classification output used in Test 01 were reused to ensure a fair comparison between versions.

### 2. Actual Output Summary

P02 v1.1 successfully identified:
- Main issue: Unclean bathroom, used towels and wet floor.
- Department: Housekeeping.
- Location: Guest room bathroom.
- Time: This afternoon / upon check-in.
- Physical safety concern: Potential slip hazard.
- Room hygiene concern: Yes.
- Food safety concern: No.
- Resolution status: Not confirmed.
- Missing information: Room number, exact check-in time and other operational details requiring verification.
- Handover: Recommended prompt Housekeeping inspection, cleaning and guest follow-up.

### 3. Evaluation

**Strengths:**
- Correctly distinguished room hygiene from food safety.
- Clearly separated confirmed information from assessments.
- Avoided unnecessary requests for personal information.
- Correctly handled the unknown resolution status.
- Identified relevant safety concerns and operational follow-up.
- Produced a clear and actionable departmental handover.

**Minor limitation:**
- The possible source of the used towels was not confirmed and would require physical inspection by hotel staff.

### 4. Comparison with v1.0

The improved version addressed the main weaknesses identified in the first test.

- Improved safety categorisation by distinguishing room hygiene from food safety.
- Improved privacy handling by avoiding unnecessary personal information requests.
- Improved accuracy by separating confirmed facts, assessments and information requiring verification.
- Improved issue-status reporting by using "Resolution status not confirmed".
- Produced a more structured operational handover.

### 5. Observed Effect

The v1.1 improvements resulted in more accurate categorisation, clearer information handling and a more reliable operational handover. The prompt maintained the correct extraction of the guest complaint while reducing unnecessary personal information and unsupported conclusions.

### 6. Lesson Learned

Clear instructions about privacy, safety categorisation and the distinction between confirmed information and assessments improve the reliability of AI-generated operational records. AI-generated recommendations must still be verified by authorised hotel staff.

### 7. Conclusion

P02 v1.1 successfully addressed the weaknesses identified during v1.0 testing. Both versions were tested using the same guest complaint and P01 classification output. The comparison demonstrated improvements in information accuracy, privacy handling, safety categorisation and operational handover quality.

P02 testing is complete for the selected test case. Additional testing with different complaint types would be beneficial before operational deployment.
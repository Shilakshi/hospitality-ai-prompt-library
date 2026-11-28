# P01 – Testing Results

## Project
AI-Powered Hospitality Operations & Guest Experience Management

## Prompt Tested
- Prompt ID: P01
- Prompt Name: Guest Enquiry and Complaint Classification
- Version: v1.0
- AI Tool: ChatGPT
- Test Case: Sample 01 – Room Cleanliness

## 1. Input Used

"I checked into my room this afternoon, but the bathroom was not properly cleaned. There were used towels left behind, and the bathroom floor was wet."

## 2. Expected Result

- Message Type: Complaint
- Issue Category: Room cleanliness
- Responsible Department: Housekeeping
- Priority: High
- Safety Concern: Potential slip hazard due to wet floor
- Human Review: Required

## 3. Actual AI Output – Summary

The AI correctly classified the message as a complaint relating to room cleanliness.

It assigned Housekeeping as the responsible department and a High priority level. It also identified the wet bathroom floor as a potential slip hazard and recommended immediate human review.

The AI requested additional information, including the guest's name, room number, booking reference and preferred resolution.

## 4. Evaluation

| Evaluation Criteria | Result |
|---|---|
| Correct message classification | Successful |
| Correct issue identification | Successful |
| Correct department identification | Successful |
| Appropriate priority assignment | Reasonable |
| Safety concern identification | Successful |
| Structured output | Successful |
| Useful information for P02 | Successful |

## 5. Observed Strengths

- Correctly identified the complaint.
- Assigned the appropriate department.
- Recognised the potential slip hazard.
- Provided a clear and structured response.
- Generated a useful summary for the next prompt in the chain.

## 6. Identified Weaknesses

- Requested personal details that may not be necessary for initial classification.
- Priority definitions could be clearer to improve consistency between High and Critical classifications.

## 7. Proposed Improvements

- Introduce data-minimisation instructions to avoid requesting unnecessary guest personal information.
- Clarify the difference between High and Critical priority levels.
- Retain the safety flag and human-review requirement for potential hazards.

## 8. Overall Conclusion

P01 v1.0 performed well in the first test. However, improvements are required to strengthen privacy protection and priority classification consistency.

These findings will inform the development of P01 v1.1.


---

## 9. Version 1.1 – Retesting Results

**Prompt Version:** v1.1

**Test Case:** Sample 01 – Room Cleanliness

**Input:** The same fictional guest complaint used to test v1.0.

### Actual AI Output – Summary

The AI correctly classified the message as a complaint relating to room cleanliness and identified Housekeeping as the responsible department.

It assigned High priority, identified the wet bathroom floor as a potential physical safety hazard and recommended immediate human review.

It requested only the room number and current guest occupancy status as additional operational information, indicating that authorised hotel staff could retrieve these details through approved systems.

### Comparison with Version 1.0

| Evaluation Criteria | v1.0 | v1.1 |
|---|---|---|
| Classification accuracy | Correct | Correct |
| Department identification | Correct | Correct |
| Priority assignment | High | High |
| Safety identification | Successful | Successful |
| Privacy instructions | Requested unnecessary personal details | Improved |
| Operational information | Requested guest name and booking reference | More relevant and limited |

### Observed Effect

Version 1.1 maintained the correct classification and safety assessment while avoiding unnecessary requests for guest personal information.

The revised instructions also produced a more operationally relevant request for additional information.

### Lesson Learned

Clear privacy instructions can improve the suitability of AI-generated outputs for hotel operations. Priority definitions should also be tested across different types of complaints to assess consistency.

### Testing Conclusion

P01 v1.1 demonstrated an improvement over v1.0 in data minimisation while maintaining the correct classification result for this test case.

Further testing is required before concluding that the prompt performs consistently across different complaint categories.
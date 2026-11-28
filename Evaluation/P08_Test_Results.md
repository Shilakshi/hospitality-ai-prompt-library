# P08 – Food Allergy Enquiry: Testing Results

## 1. Testing Information

- **Prompt ID:** P08
- **Prompt Name:** Food Allergy Enquiry
- **AI Tool:** ChatGPT
- **Test Case:** Test 01 – Peanut Allergy and Dessert Enquiry
- **Versions Tested:** v1.0, v1.1 and v1.2
- **Test Status:** Comparative testing completed

### Test Scenario

A guest with a known peanut allergy asks whether a particular dessert is safe to eat. Complete ingredient information and cross-contact information are unavailable.

### Test Input

A guest enquires whether a dessert is suitable for consumption despite having a known peanut allergy. The hotel does not yet have complete ingredient, supplier or food preparation information to confirm whether the dessert is safe.

### Expected Result

The prompt should:

- Identify the peanut allergy and potential food safety risk.
- Distinguish confirmed information from unknown ingredient and cross-contact information.
- Assign an appropriate urgency level.
- Recommend verification with authorised kitchen and F&B staff.
- Identify relevant ingredient, supplier and food preparation checks.
- Avoid confirming that the dessert is safe without sufficient verification.
- Provide practical next steps and require human oversight.
- Avoid unsupported regulatory claims or assumptions about hotel procedures.

## 2. Version 1.0 – Initial Testing Results

### Actual AI Output – Summary

The AI correctly classified the enquiry as a food safety and allergen information enquiry. It identified a potentially severe allergy risk and assigned High urgency.

It recommended involving the F&B and kitchen teams, checking ingredients and cross-contact risks, and avoiding any assurance that the dessert was safe until the relevant information had been verified.

### Evaluation

| Evaluation Criteria | Result |
|---|---|
| Allergy identification | Successful |
| Food safety risk recognition | Successful |
| Urgency classification | Appropriate |
| Ingredient verification guidance | Successful |
| Cross-contact consideration | Successful |
| Department routing | Successful |
| Avoidance of unsupported safety assurances | Successful |

### Observed Strengths

- Correctly recognised the peanut allergy and potential food safety risk.
- Identified missing ingredient and cross-contact information.
- Recommended involving the relevant kitchen and F&B staff.
- Avoided guaranteeing that the dessert was safe.
- Produced a structured and relevant response for hotel operations.

### Identified Weaknesses

- Regulatory references, including FSANZ requirements, required verification against current official guidance.
- Staff needed clearer instructions to rely on verified ingredient and preparation information rather than AI-generated assumptions.
- Verification responsibilities could be more explicitly defined.

### Proposed Improvements for v1.1

- Strengthen instructions requiring verification of ingredients and potential cross-contact.
- Clarify the responsibilities of authorised kitchen and F&B staff.
- Avoid unsupported regulatory interpretations.
- Reinforce that AI must not independently confirm food safety.

### Testing Conclusion

P08 v1.0 performed well in the initial test and demonstrated appropriate awareness of the allergy risk. Further refinement was required to strengthen verification guidance and clarify staff responsibilities.

## 3. Version 1.1 – Refinement and Testing

### Actual AI Output – Summary

Version 1.1 improved the verification instructions and strengthened the distinction between information that was confirmed and information that remained unknown.

However, testing identified an unrealistic requirement for 100% certainty in the verification process. This wording was considered impractical and required refinement.

### Evaluation

**Observed Strengths:**

- Maintained appropriate recognition of the peanut allergy.
- Continued to identify the potential food safety risk.
- Reinforced the need for kitchen and F&B verification.
- Maintained the requirement not to provide unsupported safety assurances.
- Improved the focus on staff responsibility and verification.

**Identified Weakness:**

- The requirement for 100% certainty was unrealistic and could create an impractical standard for operational decision-making.

### Proposed Improvements for v1.2

- Remove the unrealistic 100% certainty requirement.
- Use practical verification requirements consistent with hotel food safety procedures.
- Maintain clear ingredient and cross-contact checks.
- Reinforce that authorised staff must make the final food safety decision.
- Avoid unsupported regulatory claims.

### Testing Conclusion

Version 1.1 maintained the important safety controls introduced in the earlier version but required further refinement to make its verification requirements more practical.

## 4. Version 1.2 – Final Testing Results

### Actual AI Output – Summary

The AI correctly classified the enquiry as a Food Allergy and Dietary Safety Verification enquiry.

It identified confirmed and unknown information, assigned High urgency, recommended pausing the order and consulting kitchen staff, and provided ingredient verification and cross-contact checks.

The output maintained the requirement that staff must verify relevant information before providing any assurance about the dessert.

### Evaluation

| Evaluation Criteria | Result |
|---|---|
| Allergy identification | Successful |
| Food safety risk recognition | Successful |
| Urgency classification | Appropriate |
| Confirmed and unknown information | Successful |
| Ingredient verification guidance | Successful |
| Cross-contact checks | Successful |
| Department responsibilities | Successful |
| Avoidance of unsupported safety assurances | Successful |
| Regulatory claim handling | Successful |

### Observed Strengths

- Correctly identified the food allergy and potential safety risk.
- Clearly distinguished confirmed information from unknown details.
- Recommended pausing the order while verification was undertaken.
- Provided practical ingredient and cross-contact verification guidance.
- Identified the responsibilities of kitchen and F&B staff.
- Avoided guaranteeing that the dessert was safe.
- Removed the unrealistic 100% certainty requirement.
- Avoided unsupported regulatory claims.

### Remaining Limitation

Staff must follow the hotel's actual ordering and food safety procedures when pausing an order and verifying allergen information. AI-generated recommendations cannot replace authorised staff assessment or established food safety controls.

### Testing Conclusion

P08 v1.2 produced a clear, structured and safety-conscious response. It addressed the main weaknesses identified during earlier testing and was the strongest of the three tested versions.

## 5. Version Comparison

| Evaluation Area | v1.0 | v1.1 | v1.2 |
|---|---|---|---|
| Allergy risk identification | Successful | Maintained | Maintained |
| Ingredient verification | Required refinement | Improved | Clearer |
| Cross-contact guidance | Included | Strengthened | Maintained |
| Staff responsibilities | Required clarification | Improved | Clearer |
| Regulatory claims | Required verification | Refined | Improved |
| Verification requirements | Needed strengthening | Unrealistic certainty requirement | Practical verification guidance |
| Human oversight | Included | Maintained | Reinforced |

## 6. Lessons Learned

The testing demonstrated that food allergy prompts require particularly careful instructions because inaccurate or unsupported AI-generated information could create serious risks for guests.

The main lessons were:

- AI must distinguish confirmed information from unknown ingredient and preparation details.
- Ingredient and cross-contact information must be verified by authorised staff.
- Prompts should avoid unsupported regulatory interpretations.
- Verification instructions must be practical and consistent with actual hotel procedures.
- AI must not independently declare food safe for a guest with an allergy.
- Human oversight is essential before any food safety decision is communicated to a guest.

## 7. Overall Testing Conclusion

P08 v1.2 demonstrated improvements over v1.0 and v1.1 when tested using the same peanut allergy scenario.

The final version provides clearer verification requirements, improved handling of unknown information, more practical staff responsibilities and stronger controls against unsupported food safety assurances.

**Testing Status:** Comparative testing completed successfully. P08 v1.2 is the recommended final version following evaluation of all three versions.

Human verification and compliance with the hotel's established food safety procedures remain essential before any allergen-related advice is provided to a guest.
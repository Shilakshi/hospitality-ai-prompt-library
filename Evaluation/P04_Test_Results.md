# P04 – Guest Service Recovery Recommendations: Testing Results

## Test 01 – Room Cleanliness Complaint

### Test Information

- **Prompt tested:** P04 – Guest Service Recovery Recommendations
- **Sample used:** Sample 01 – Room Cleanliness Complaint
- **Test input:** Original guest message and outputs from P01, P02 and P03.
- **Objective:** Evaluate whether the prompt generates practical, policy-aware service recovery recommendations.

### Test 01 – Version v1.0

**Observed Output:**

The prompt generated a structured service recovery plan covering the complaint summary, immediate actions, corrective actions, guest communication, escalation, follow-up and overall recommendations.

**Strengths:**
- Identified appropriate immediate actions, including room inspection, re-cleaning and potential room relocation.
- Recognised the potential slip hazard.
- Identified relevant departments.
- Avoided promising unauthorised compensation.
- Included guest follow-up and verification.

**Limitations Identified:**
- Suggested placing a room out of order without confirming the hotel's relevant procedure.
- Recommended staff coaching without first establishing whether an employee or process failure occurred.
- Requested realistic completion timeframes without specifying that these must be based on supplied operational information.
- Needed clearer distinction between guest-reported conditions and verified findings.

**Overall Evaluation:**

P04 v1.0 generated useful recommendations but required stronger controls to prevent unsupported operational assumptions.

### Test 01 – Version v1.1

**Observed Output:**

The improved prompt generated a more evidence-based service recovery plan. It clearly separated reported information, unverified conditions, proposed actions and completed activities.

**Strengths:**
- Clearly identified information requiring verification.
- Made Maintenance involvement conditional on confirming a leak.
- Avoided assuming staff error before investigating the circumstances.
- Avoided inventing fixed completion times or compensation entitlements.
- Distinguished completed prompt-processing activities from proposed operational actions.
- Provided practical recommendations for immediate guest assistance and follow-up.

**Minor Limitation:**

The output described Housekeeping Supervisor approval as necessary for inspection and remediation, although the supplied policy specifically requires supervisory reporting and assessment rather than explicitly defining an approval requirement for routine cleaning.

**Overall Evaluation:**

P04 v1.1 improved the reliability and practical usefulness of service recovery recommendations. It demonstrated better evidence handling, clearer operational conditions and stronger alignment with supplied hotel policies.

### Version Comparison

| Evaluation Area | v1.0 | v1.1 |
|---|---|---|
| Immediate service recovery | Good | Good |
| Safety considerations | Good | Good |
| Evidence verification | Needed improvement | Improved |
| Conditional recommendations | Limited | Improved |
| Unsupported assumptions | Some identified | Significantly reduced |
| Approval and compensation controls | Good | Improved |
| Completed vs proposed actions | Needed improvement | Clearly distinguished |

### Lessons Learned

The testing demonstrated that service recovery prompts should not only generate practical recommendations but also distinguish verified information from guest reports and assumptions. Conditional recommendations, approval controls and clear follow-up requirements improve the reliability of AI-assisted hospitality operations.

Human review remains essential before operational actions are implemented.
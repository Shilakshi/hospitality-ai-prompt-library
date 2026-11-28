# P07 – Hotel Accommodation and F&B Complaint Trend Analysis: Test Results

## 1. Testing Information

- **Prompt ID:** P07
- **Prompt Name:** Hotel Accommodation and F&B Complaint Trend Analysis
- **Versions Tested:** v1.0 and v1.1
- **Test Number:** Test 01
- **Test Dataset:** 10 fictional guest feedback records
- **Test Input:** Same ten guest feedback records and task instructions for both versions
- **Testing Method:** Comparative testing using the same input to evaluate changes in analytical accuracy and output quality.

## 2. Test Objective

To evaluate whether P07 can accurately analyse multiple hotel guest feedback records, categorise complaints, calculate frequencies, compare Accommodation and F&B feedback, identify recurring themes, recognise positive feedback, and separately highlight serious safety and food safety concerns.

The test also evaluates whether the revised v1.1 prompt improves accuracy, evidence-based reasoning, and the handling of limitations compared with v1.0.

**Expected Result**

The prompt should:
- Correctly classify and count all feedback records.
- Separate complaints from positive feedback.
- Calculate frequencies using clearly identified denominators.
- Compare Accommodation and F&B feedback accurately.
- Identify recurring themes without claiming unsupported trends.
- Highlight potential safety and food safety concerns.
- Distinguish guest-reported information from verified findings.
- Explain dataset limitations and avoid unsupported conclusions.

## 3. Test Input Summary

The test used ten fictional guest feedback records:

1. Room cleanliness – used towels and wet bathroom floor.
2. Air conditioning – room air conditioning not working properly.
3. Reservation issue – twin room allocated instead of booked king-size bed.
4. Check-in delay – lengthy waiting time.
5. Restaurant service delay – slow meal service.
6. Food served cold – dissatisfaction with food temperature.
7. Potential food safety concern – chicken appeared undercooked.
8. Breakfast buffet – items unavailable and not replenished promptly.
9. Positive feedback – friendly, helpful and welcoming hotel staff.
10. Serious maintenance and safety concern – water leak near an electrical outlet.

The same input was used for both prompt versions to support a fair comparison.

## 4. P07 v1.0 – Test 01 Results

### Observed Strengths

- Correctly identified ten records, consisting of nine complaints and one positive compliment.
- Categorised the feedback into relevant Accommodation and F&B complaint categories.
- Correctly identified five Accommodation complaints and four F&B complaints.
- Identified broader themes involving room readiness, service delays, and food preparation.
- Recognised the water leak near an electrical outlet and potentially undercooked chicken as serious concerns requiring separate attention.
- Acknowledged the small sample size and absence of reporting dates.

### Observed Limitations

- Some safety statements were too definitive for unverified guest reports, including describing the water leak as an immediate electrocution and fire hazard.
- Introduced specific foodborne pathogens without evidence from the supplied records.
- Suggested possible operational causes such as staffing, kitchen bottlenecks, and inventory system issues without clearly separating these assumptions from verified findings.
- Recommended specific corrective actions, such as room isolation and safety sign-off, without reference to supplied hotel procedures.
- Some wording could lead management to interpret potential operational issues as established deficiencies.

### Overall Observation

P07 v1.0 produced a useful and generally structured analysis. However, it required stronger controls to prevent unsupported conclusions, excessive certainty, and recommendations that went beyond the supplied evidence.

## 5. P07 v1.1 – Test 01 Results

### Observed Improvements

- Clearly distinguished guest-reported concerns from independently verified operational findings.
- Correctly separated nine complaints from one positive feedback record.
- Presented percentages using both the ten-record dataset and the nine complaint records, with denominators clearly explained.
- Clearly identified that no identical specific complaint was repeated across multiple records.
- Distinguished individual complaint categories from broader operational themes.
- Correctly identified five Accommodation complaints and four F&B complaints.
- Left the positive feedback unallocated to a specific department because the record did not identify one.
- Avoided treating the water leak and undercooked chicken reports as confirmed physical or food safety findings.
- Avoided introducing specific pathogens or unsupported technical conclusions.
- Presented possible investigation areas as unconfirmed rather than established root causes.
- Clearly explained that departmental complaint counts cannot establish relative performance without operational denominator data.
- Maintained the limitation that the ten fictional records are not representative of actual hotel performance.

### Remaining Limitations

- The analysis still relies on a small fictional dataset and cannot establish actual hotel-wide operational performance.
- The absence of dates prevents time-based analysis.
- The absence of room numbers, outlet details, and operational records limits further investigation.
- Human assessment remains necessary for reported safety and food safety concerns.

### Overall Observation

P07 v1.1 produced a more cautious, transparent, and evidence-based analysis. It improved the distinction between reported concerns, potential implications, and verified findings while providing clearer frequency calculations and departmental comparisons.

## 6. Version Comparison

| Evaluation Area | P07 v1.0 | P07 v1.1 |
|---|---|---|
| Complaint categorisation | Generally accurate | Maintained accurate categorisation |
| Frequency calculations | Used total sample denominator | Clearly explained total-record and complaint-only denominators |
| Recurring themes | Identified broader themes | Better distinguished repeated categories from repeated specific issues |
| Departmental comparison | Generally accurate | More clearly explained allocation and comparison limitations |
| Safety assessment | Some unsupported certainty | Distinguished reported concerns from verified hazards |
| Operational implications | Included unsupported possible causes | Clearly labelled investigation areas as unconfirmed |
| Data limitations | Acknowledged small sample | More clearly explained limitations and representativeness |

## 7. Lessons Learned

The testing demonstrated that a prompt can produce a structured analysis while still introducing unsupported assumptions or overly confident conclusions.

The main lesson was that hospitality feedback analysis should clearly distinguish guest reports from verified operational findings. Frequency calculations must also identify their denominators, and departmental comparisons must consider the limitations of the available data.

The revised prompt provides better analytical controls by requiring evidence-based conclusions, cautious safety language, clear categorisation, and human verification.

## 8. Testing Conclusion

P07 v1.1 demonstrated improvements over v1.0 when tested using the same ten fictional guest feedback records.

The revised version provides more transparent frequency calculations, clearer departmental comparisons, better treatment of safety concerns, and more appropriate handling of unverified information.

**Testing status:** Comparative testing completed. Further testing with larger and more varied datasets would be beneficial before practical hotel implementation.
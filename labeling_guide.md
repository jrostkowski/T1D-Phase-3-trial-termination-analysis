# Labeling Guide: Trial Stop Reasons

Applies to trials with status TERMINATED or WITHDRAWN. Each trial gets exactly one category.

**Text to read:** `why_stopped`. If it says "see detailed description," use `detailed_description` instead.

**General rule:** label the reason the record states, not the reason you suspect. If no specific reason is stated, use Unclear.

## Categories

### Business / commercial
The sponsor stopped for commercial, strategic, or portfolio reasons. No safety or efficacy finding *from this trial* is cited.
- Example: "Pfizer announced … it would stop marketing Exubera … Neither safety nor efficacy reasons were the cause." (NCT00138671)
- Includes: product discontinued, development suspended, device replaced by a newer version, protocols combined.

### Efficacy / futility
The trial was stopped because the treatment was not working, or was not expected to meet its endpoint.
- Example: "Independent Data Monitoring Committee recommendation to stop due to futility." (NCT03174522)
- Includes: endpoint not met, futility analysis, results from other trials showing this one would fail.

### Safety
The trial was stopped because of harm or a safety signal.
- Example: "Higher incidence of hospitalization for congestive heart failure …"

### Funding / resources
The trial could not continue because money, staff, supplies, or devices were not available.
- Example: "No Funding Received from ADA." (NCT01722227)

### Enrollment
The trial could not recruit enough participants.
- Example: "We were unable to enroll any subjects in this study due to lack of interest." (NCT00853424)

### Regulatory
The trial was stopped because of a regulatory requirement, guidance, or authority decision.
- Example: GanLee cancelled after FDA draft guidance on biosimilar insulin (NCT04254380)

### Unclear / not stated
No specific reason is given, or the reason is too vague to categorize.
- Examples: "Administrative"; blank; "Study was not initiated"; "Stopped due to inactivity."

## Edge-case rules

1. **Negations:** text that rules out safety or efficacy ("not due to any safety concerns," "non-safety related") does not count as Safety or Efficacy. Use the reason that is actually stated.
2. **Sponsor's product assessment (AERx):** "unlikely to offer significant clinical or convenience benefits over existing products" is labeled **Business**, because it is a portfolio judgment, not a result from this trial.
3. **DSMB/IDMC recommendation with no reason given** is labeled **Unclear**. If the record names a reason (e.g., futility), use that category.
4. **Results from other trials showing this trial would fail** are labeled **Efficacy / futility**.
5. **Devices or supplies unavailable** are labeled **Funding / resources**.
6. **Withdrawn before enrollment with no reason given** is labeled **Unclear**, not Enrollment. Enrollment requires a stated recruitment problem.

## Exclusions

- **NCT00521820:** a Type 2 diabetes trial (per its brief summary) with only the generic "Diabetes Mellitus" condition label. Excluded from the dataset; not labeled.
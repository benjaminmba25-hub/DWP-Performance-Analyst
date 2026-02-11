# 📊 Performance Measurement Framework
*Aligned with GDS Service Standard: Point 10 (Data).*

## 1. Mandatory GDS Metrics
Every public sector service must report these four KPIs to the Central Digital & Data Office (CDDO).

| Metric | Definition | Data Source | Target |
| :--- | :--- | :--- | :--- |
| **Completion Rate** | % of users who start the intake and reach the "Success" page. | Google Analytics 4 (GA4) | > 85% |
| **Cost per Transaction** | Total Service Cost / Total Completed Transactions. | Finance / Ops Data | < £0.50 |
| **Digital Take-up** | % of applications submitted via Web vs Paper/Phone. | Intake Database | > 90% |
| **User Satisfaction** | % of users rating service "Good" or "Very Good". | Feedback Component | > 80% |

## 2. Service-Specific KPIs (The "Intake" Logic)
| KPI | Why we measure it | Optimization Action |
| :--- | :--- | :--- |
| **Validation Failure Rate** | High failures indicate unclear form design (e.g., users entering NINO wrong). | Rewrite helper text on input fields. |
| **Drop-off at Step 2** | If users leave at "Evidence Upload", the file limits might be too strict. | Increase upload size limit to 10MB. |
| **Auto-Triage Rate** | % of cases routed without human intervention. | Refine business rules engine. |

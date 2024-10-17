# Vanguard Digital Interface Analysis - README

## Project Overview

This project analyzes the effectiveness of Vanguard's new digital user interface (UI) compared to the previous version. The analysis focuses on several key performance indicators (KPIs), including completion rate, error rate, time spent on steps, and client demographics (age and tenure). We used both Python for statistical testing and Tableau for data visualization to drive insights.

---

## Hypotheses Tested

1. **Completion Rate (CR)**:
   - **H₀**: The completion rate is not significantly different between the Test and Control groups.
   - **H₁**: The Test group has a significantly higher completion rate than the Control group.
   - **Outcome**: The Test group had a significantly higher completion rate, but **not** enough to meet the 5% threshold required to justify the new UI costs.

2. **Completion Rate - 5% Improvement**:
   - **H₀**: The completion rate for the Test group is equal to or less than the Control group plus a 5% improvement.
   - **H₁**: The completion rate of the Test group is greater than the Control group by more than 5%.
   - **Outcome**: The p-value was not significant, meaning the completion rate **did not exceed** the 5% threshold.

3. **Average Age of Clients**:
   - **H₀**: The average age of clients engaging with the new process is the same as those engaging with the old process.
   - **H₁**: The average age of clients engaging with the new process is lower than those engaging with the old process.
   - **Outcome**: There was **no significant difference** in the average age between the Test and Control groups.

4. **Client Tenure**:
   - **H₀**: The average client tenure of those engaging with the new process is the same as those engaging with the old process.
   - **H₁**: The average client tenure of those engaging with the new process is lower than those engaging with the old process.
   - **Outcome**: No significant difference in client tenure between the Test and Control groups.

5. **Error Rate**:
   - **H₀**: The error rate between the Test and Control groups is the same.
   - **H₁**: The error rate of the Test group is lower than that of the Control group.
   - **Outcome**: There was **no significant difference** in error rates between the groups.

6. **Time Spent on Steps**:
   - **H₀**: The average time spent on a step by clients in the Test group is equal to that of the Control group.
   - **H₁**: The average time spent on a step by clients in the Test group is lower than that of the Control group.
   - **Outcome**: The Test group spent **significantly less time** on steps, indicating improved efficiency.

---

## Tools and Technologies

### Python
Python was used for conducting statistical tests, data cleaning, and analysis. 

### Tableau
Tableau was utilized to visualize the data and present insights through:

- **Dashboards**: Visualized multiple KPIs to provide an overview of performance between Test and Control groups.

---

## Key Findings and Recommendations

- The new UI resulted in **faster completion times** but did **not meet the 5% improvement goal** for completion rates, nor did it reduce error rates.
  
### Recommendations:
- **UI Optimization**: Focus on further improving completion rates by identifying specific steps that cause user drop-offs.
- **Targeted Testing**: Expand testing to a broader client demographic to see if certain user groups benefit more from the new UI.
- **Phased Rollout**: Consider a more iterative approach to the UI redesign based on smaller, measurable improvements.

---

## How to Run the Analysis

1. **Python**:
   - Clone this repository and install the necessary Python dependencies from the `requirements.txt` file.
   - Run the Python script `eda-project-data-cleaning.py` to reproduce the hypothesis tests and statistical analysis.

2. **Tableau**:
   - Open the Tableau workbook `eda-project-data-cleaning.twbx` & `AB_Test_KPIs.twbx.twbx` to explore the visualizations and dashboards created for this analysis.

---

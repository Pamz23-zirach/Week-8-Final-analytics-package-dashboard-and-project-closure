# HealthConnect Clinic — Data Analytics Track
### AnalystLab Africa Experience Lab

## Overview
Analysis of the HealthConnect Clinic appointment dataset (5,000 records) to
identify what drives missed appointments and support data-driven interventions.
Completed across 8 weeks: data preparation, KPI development, validation,
interaction testing, and final decision-support reporting.

## Final Headline Finding
Combining a patient's prior no-show history with their booking lead time
identifies a precise, high-impact risk segment:
- **Lowest risk** (0 prior no-shows, booked 0-7 days ahead): **21.77%** no-show rate
- **Overall average**: 48.46% no-show rate
- **Highest risk** (1+ prior no-shows, booked 31-60 days ahead): **67.88%** no-show rate
- **Highest risk + 15km+ from clinic**: **73.2%** no-show rate

This finding was independently re-verified from raw data and held up across
every segment retest performed (gender, distance).

## Week-by-Week Progress

### Week 5 — Exploratory Data Analysis & KPIs
Cleaned and validated the dataset, calculated 8 KPIs, analysed no-show patterns
by reminders, lead time, prior history, age, and appointment type. Produced
8 business insights and recommendations.

### Week 6 — Advanced Analytics & Validation
Quantified a data-quality caution (extreme risk categories had as few as 3
records). Validated that the lead-time effect holds independently across
every appointment type. Discovered the compound risk segment (prior no-shows
x booking lead time) with a 46.1-point spread.

### Week 7 — Testing, Refinement & Validation
Independently recalculated all 6 headline KPIs from raw data — 100% match.
Retested the compound risk finding across gender and distance segments.
Discovered the distance-compounding refinement. Attempted Data Science
collaboration (no response received); completed a self-directed substitute
validation using logistic regression, confirming the compound feature adds
real predictive value (AUC 0.6623 -> 0.6628).

### Week 8 — Final Integration & Presentation
Consolidated all validated findings into a final analytics package and
dashboard. Documented final cross-track collaboration status honestly.
Submitted individual video presentation covering full project journey.

## Cross-Track Collaboration
I attempted to collaborate with the Data Science track in Weeks 6 and 7,
sharing a validated compound risk feature as a candidate model input. Despite
multiple outreach attempts, no response was received. This is documented
transparently rather than fabricated — a self-directed validation was
completed instead to still produce meaningful evidence for this requirement.

## Files
| File | Description |
|---|---|
| `week5_health_connect-EDA.ipynb` | Week 5 notebook — EDA, KPIs, insights |
| `week6_health_connect-EDA.ipynb` | Week 6 notebook — validation, interaction analysis |
| `week7_health_connect-EDA.ipynb` | Week 7 notebook — KPI validation, segment retesting, self-check |
| `week8_health_connect-EDA.ipynb` | Week 8 notebook — final summary |
| `HealthConnect_Week5_Report.docx` | Week 5 written report |
| `HealthConnect_Week6_Report.docx` | Week 6 written report |
| `HealthConnect_Week7_Report.docx` | Week 7 written report |
| `HealthConnect_Week8_Final_Analytics_Package.docx` | Final written report |
| `HealthConnect_Week8_Final_Dashboard.png` | Final dashboard graphic |
| `HealthConnect_Appointment_Data_Cleaned.csv` | Cleaned dataset (original unmodified) |
| `Week8_Final_Presentation.mp4` (or link) | Individual video presentation |

## Tools
Python · Pandas · Matplotlib · Scikit-learn · Google Colab

## Author
Pamela — Data Analytics Intern, AnalystLab Africa Experience Lab


# Hospital-Emergency-Room-Data-Dashboard
## Project Objective
An interactive and fully functional Excel dashboard designed to analyze and visualize hospital emergency room data. This project includes real-time insights into key metrics such as patient wait times, treatment outcomes, admission rates, and more — enabling data-driven decision-making for healthcare professionals and administrators.

## Dataset Used
<a href="https://github.com/rkranjeetkushwaha/Hospital-Emergency-Room-Data-Dashboard/blob/main/Hospital%20Emergency%20Room%20Data.csv">Hospital Emergency Room Data</a>

## Key Performance Indicators (KPIs)
### 🧍 Total Number of Patients

<li>Description: Total count of patients who visited the emergency room within the selected time period.

Purpose: Tracks overall patient volume to understand workload and resource demand.

Formula Used: =COUNTA(Patient_ID) or pivot table count of unique patient records.</li>

### ⏱️ Average Wait Time

<li>Description: The average time patients wait before receiving treatment.

Purpose: Measures efficiency and helps identify bottlenecks in patient flow.

Formula Used: =AVERAGE(Wait_Time) (customizable for filters such as department or date).

Additional Tip: Conditional formatting can highlight unusually high wait times.</li>

### 😊 Patient Satisfaction Score

<li>Description: Average satisfaction score collected from post-visit surveys (typically on a scale of 1–10).

Purpose: Provides insight into patient experience and quality of care.

Formula Used: =AVERAGE(Satisfaction_Score)

Enhancement: Add traffic light icons or colored bars to visually represent satisfaction levels.</li>

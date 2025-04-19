# Hospital-Emergency-Room-Data-Dashboard
## Project Objective
An interactive and fully functional Excel dashboard designed to analyze and visualize hospital emergency room data. This project includes real-time insights into key metrics such as patient wait times, treatment outcomes, admission rates, and more — enabling data-driven decision-making for healthcare professionals and administrators.

## Dataset Used
<a href="https://github.com/rkranjeetkushwaha/Hospital-Emergency-Room-Data-Dashboard/blob/main/Hospital%20Emergency%20Room%20Data.csv">Hospital Emergency Room Data</a>

## Key Performance Indicators (KPIs)
### 🧍 Total Number of Patients

<li>Description: Total count of patients who visited the emergency room within the selected time period.</li>

<li>Purpose: Tracks overall patient volume to understand workload and resource demand.</li>

<li>Formula Used: =COUNTA(Patient_ID) or pivot table count of unique patient records.</li>

### ⏱️ Average Wait Time

<li>Description: The average time patients wait before receiving treatment.</li>

<li>Purpose: Measures efficiency and helps identify bottlenecks in patient flow.</li>

<li>Formula Used: =AVERAGE(Wait_Time) (customizable for filters such as department or date).</li>

<li>Additional Tip: Conditional formatting can highlight unusually high wait times.</li>

### 😊 Patient Satisfaction Score

<li>Description: Average satisfaction score collected from post-visit surveys (typically on a scale of 1–10).</li>

<li>Purpose: Provides insight into patient experience and quality of care.</li>

<li>Formula Used: =AVERAGE(Satisfaction_Score)</li>

<li>Enhancement: Add traffic light icons or colored bars to visually represent satisfaction levels.</li>

## 🛠️ Process
<ol type="1">
<li>Data Collection & Cleaning</li>
Imported raw emergency room data into Excel and used Power Query to clean, format, and structure the dataset for analysis.

<li>Data Modeling</li>
Organized data into structured tables for easier reference and built relationships between patient demographics, visit details, and treatment outcomes.

<li>KPI Identification</li>
Identified key performance indicators such as average wait time, number of patients served, admission rates, and critical cases handled.

<li>Dashboard Design</li>
Designed a clean and intuitive dashboard layout using pivot tables, charts, slicers, and conditional formatting to enhance usability and data visibility.

<li>Interactivity & Automation</li>
Added slicers and drop-down filters for real-time data interaction. Used formulas and named ranges to automate calculations and make the dashboard dynamic.

<li>Testing & Optimization</li>
Tested with sample data to ensure accuracy of metrics and responsiveness of the dashboard. Optimized visuals for clarity and performance.</ol>

## ✅ Final Conclusion
This Excel-based Hospital Emergency Room Dashboard provides a powerful and accessible tool for monitoring and analyzing emergency care performance. It simplifies complex healthcare data into meaningful insights, enabling hospitals to make data-driven decisions, improve patient flow, and enhance service quality. The project showcases how Excel can be leveraged as a cost-effective solution for healthcare analytics, even without advanced BI tools.

# Dashboard
<img width="620" alt="Hospital Emergency Room Data Dashboard" src="https://github.com/user-attachments/assets/f6fae29f-1dfd-4b9e-a7e8-c687073e73d9" />



# 📊 PowerFit India — Fitness Club Excel Analysis

Welcome to the **PowerFit India** data analysis project! This assignment focuses on leveraging Microsoft Excel to draw actionable insights from a simulated dataset of a fitness club. The analysis includes member retention, revenue performance, referral impact, and demographic insights.

---

## 🗂️ Dataset Overview

- **Rows:** 3 (sample dataset)
- **Columns:** 11
- **Source:** [Google Sheets Dataset Link](https://docs.google.com/spreadsheets/d/1HY-VQKl9ik6Ow37BQcJZPSBH0gIiJ0g7/edit?usp=sharing&ouid=110827767954182979203&rtpof=true&sd=true)

### Columns Description:
| Column Name        | Description                                                    |
|--------------------|----------------------------------------------------------------|
| Member_ID          | Unique identifier for each member (e.g., M001, M002)          |
| Full_Name          | Full name of the member                                       |
| Start_Date         | Membership start date                                         |
| End_Date           | Membership end date                                           |
| Age                | Member's age (19–60 years)                                    |
| Monthly_Fee        | Monthly membership fee in ₹                                   |
| Membership_Type    | Basic, Standard, Premium, or Family                           |
| City               | City of residence (e.g., Mumbai, Delhi)                       |
| Gender             | Male or Female                                                |
| Attendance         | Number of days attended this month (1–30)                     |
| Referred_By        | Name of the referrer (optional)                               |

---

## ✅ Tasks Performed

### 1. 📅 Membership Duration
- Calculated total membership duration in full months.
- Assumption: 1 month = 30 days
- Formula: `=(End_Date - Start_Date)/30`

### 2. 🤝 Referral Impact
- Created a new **Referred** column:
  - `Yes` if referred by someone
  - `No` if not referred
- Used Pivot Table to compare average Monthly Fee of referred vs non-referred members.

### 3. 💰 Revenue Analysis
- Added a column: **Total_Revenue = Monthly_Fee × Membership_Duration**
- Calculated:
  - Total revenue by **Membership Type** (e.g., Premium, Family)
  - **City-wise** revenue using Pivot Tables

### 4. ⚠️ Low Engagement Flag
- Applied Conditional Formatting to highlight:
  - Attendance `< 4` AND Membership Duration `≥ 6 months`
  - These represent long-term but inactive members

![Screenshot 2025-05-15 115332](https://github.com/user-attachments/assets/961c879b-51da-4eaf-8a2d-e58750ac1cea)


### 5. 📈 Segment Profitability Dashboard
- Created interactive Pivot Table Dashboard with Slicers
- Analyzed revenue by:
  - City + Membership Type + Referral Status
- Insights on:
  - Average revenue per segment
  - Marketing focus recommendations
 
    ![Screenshot 2025-05-15 115543](https://github.com/user-attachments/assets/e6aed5ed-34f9-4ede-88b5-a1d16b8766df)


### 6. 👥 Demographic Analysis
- Pivot Tables created for:
  - **Gender-wise** member count per city
  - **Age Group Distribution** across Membership Types:
    - 18–30: Youth
    - 31–45: Adult
    - 46+: Seniors
   
    
![Screenshot 2025-05-15 115600](https://github.com/user-attachments/assets/a781745c-f4e8-4e7b-a944-1fce516e94c9)


![Screenshot 2025-05-15 115608](https://github.com/user-attachments/assets/7b38900e-e520-4f16-8aa8-8ea65de158f2)

---

## 📌 Tools Used
- Microsoft Excel (Pivot Tables, Charts, Slicers, Conditional Formatting)
- Formulas: `IF()``, arithmetic calculations

---

## 🧠 Key Learnings
- Excel’s analytical power for real-world business cases
- Building dynamic dashboards for decision-making
- Deriving actionable insights from raw data

---

## 📎 Related Resources
- Assignment PDF (includes instructions)
- Excel Workbook with all analysis and dashboards

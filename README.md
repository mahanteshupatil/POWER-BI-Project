# HR Analytics Dashboard - Power BI

## About This Project
This Power BI dashboard shows why employees are leaving the company. I analyzed data of 1470 employees.

## Dashboard Screenshot
<img width="1183" height="677" alt="Power BI project image" src="https://github.com/user-attachments/assets/c4e030c8-e62b-4b76-81cb-3361ae6e5dec" />



## Main Findings
| Metric | Number |
| --- | --- |
| Total Employees | 1470 |
| People Left | 237 |
| Attrition Rate | 16.1% |
| Most Exits From | Salary 'Upto 5K' - 163 people |
| Highest Risk Age | 26-35 years - 116 exits |
| Top Exit Roles | Lab Technician: 62, Sales Executive: 57 |

## Tools Used
- Power BI Desktop
- Charts: Bar chart, Donut chart, Line chart, Cards
- Slicers for Department filter

  ## 📂 Dataset
- **Source**: HR Analytics Employee Attrition Dataset
- **Size**: 1470 records
- **Key Columns**: `Attrition`, `Age`, `MonthlyIncome`, `JobRole`, `YearsAtCompany`, `JobSatisfaction`, `EducationField`, `Gender`, `Department`

## 📈 Key Business Recommendations
1. **Salary Revision**: 68% of leavers are from 'Upto 5K' band.
2. **Improve First-Year Experience**: Attrition spikes at 1 year. Track `YearsAtCompany` metric to trigger HR alerts.
3. **Focus on Key Roles**: Lab Technicians and Sales Executives show highest exits.
4. **Mid-Career Growth**: 26-35 age group has 116 exits. Use bookmarks to compare satisfaction scores vs exits.

## 🚀 How to Use
1. Download `HR Analytics Dashboard.pbix`
2. Open in Power BI Desktop
3. Use Department slicers: Human Resources, Research & Development, Sales
4. Click any visual to cross-filter other charts

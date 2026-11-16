# HR Workforce Attrition Dashboard

An interactive Power BI dashboard that shows **who leaves, where, and why** across a 1,470-employee workforce, built on a Star Schema model so HR teams can drill from company-level attrition down to individual job roles.

![Dashboard preview](images/dashboard-overview.png)
<!-- Add a screenshot of your dashboard at images/dashboard-overview.png -->

---

## Objective

Employee attrition is expensive and usually noticed only after people have left. This project turns raw HR records into a decision-ready dashboard that answers three questions for HR stakeholders:

1. How big is the attrition problem?
2. Which employee segments are leaving the most?
3. Where should retention planning focus first?

---

## Key Findings

| Metric | Result |
|---|---|
| Employees analysed | **1,470** |
| Employees who left | **237** |
| Attrition rate | **16.1%** |

**Attrition hot spots**

- **Salary:** 163 of the 237 exits (about 69%) earn under 5K.
- **Age:** 116 exits (about 49%) are aged 26–35.
- **Role:** Laboratory Technicians (62) and Sales Executives (57) lead exits by job role, together accounting for about half of all exits.

> Percentages in brackets are calculated from the counts above.

---

## Dashboard Features

- **KPI cards** for attrition count and rate, average age, average salary and average tenure
- **Segmentation views** by education, job role, age, salary band and job satisfaction
- **Interactive drill-downs** so stakeholders can filter any view to a specific segment
- **Star Schema data model** for clean relationships and fast filtering

---

## Tech Stack

| Area | Tools |
|---|---|
| Visualisation & BI | Power BI |
| Data modelling | Star Schema (fact and dimension tables) |
| Analysis | KPI analysis, segmentation |

---

## Skills Demonstrated

- **Data modelling:** designing a Star Schema for reporting
- **KPI design:** defining and tracking attrition, age, salary and tenure metrics
- **Segmentation analysis:** breaking attrition down by role, age, pay band, education and satisfaction
- **Dashboard design:** building interactive, drill-down reports
- **Stakeholder reporting:** presenting findings in a form HR teams can act on
- **Business insight:** turning counts into retention priorities

---

## Repository Structure

```
├── HR_Workforce_Attrition_Dashboard.pbix   # Power BI report file
├── data/                                    # Source dataset
├── images/                                  # Dashboard screenshots
└── README.md
```
<!-- Adjust file names to match your repository -->

---

## How to Use

1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the slicers and drill-down visuals to explore attrition by segment.

---

## Author

**Anurag Tiwari**
[LinkedIn](https://linkedin.com/in/anurag-tiwari-7a13743ba) | [GitHub](https://github.com/Anurag-cmd-ai)

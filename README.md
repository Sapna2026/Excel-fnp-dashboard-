#  FNP Sales Analysis Dashboard | Excel Data Analytics Project

<p align="center">
  <strong>Turning Sales Data into Actionable Business Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Excel-Advanced%20Analytics-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
  <img src="https://img.shields.io/badge/Data%20Analytics-Sales%20Analysis-1565C0?style=for-the-badge" alt="Data Analytics"/>
  <img src="https://img.shields.io/badge/Project-Interactive%20Dashboard-7B1FA2?style=for-the-badge" alt="Interactive Dashboard"/>
</p>

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Project Pipeline](#-project-pipeline)
- [Data Cleaning Summary](#-data-cleaning-summary)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Dashboard Features](#-dashboard-features)
- [Key Performance Indicators](#-key-performance-indicators)
- [Models Compared](#-models-compared)
- [Evaluation Metrics](#-evaluation-metrics)
- [Key Findings](#-key-findings)
- [Business Recommendations](#-business-recommendations)
- [Installation](#-installation)
- [How to Run](#-how-to-run)
- [Project Deliverables](#-project-deliverables)
- [Challenges and Learnings](#-challenges-and-learnings)
- [Future Improvements](#-future-improvements)
- [Skills Demonstrated](#-skills-demonstrated)
- [License](#-license)
- [Author](#-author)

---

## 📊 Project Overview

The **FNP Sales Analysis Dashboard** is a data analytics project focused on understanding the sales performance of Ferns N Petals (FNP), a gifting and flower delivery business.

The project uses Microsoft Excel to organize sales-related datasets, analyze business performance, and present information through dashboard visualizations.

It aims to help users explore revenue trends, product performance, customer purchasing patterns, and seasonal demand to support data-driven business decisions.

The repository includes an Excel workbook, customer, order, and product datasets, a PDF report, an executive summary, and a dashboard screenshot.

### 🎯 Project at a Glance

| Category | Details |
|---|---|
| Project Name | FNP Sales Analysis Dashboard |
| Domain | Sales Analytics / Retail Analytics |
| Primary Tool | Microsoft Excel |
| Data Sources | Customer, order, and product CSV files |
| Project Type | Data Cleaning, Analysis, and Visualization |
| Main Deliverable | Excel Dashboard |
| Repository | [Excel-fnp-dashboard-](https://github.com/Sapna2026/Excel-fnp-dashboard-) |

## 💼 Business Problem

Sales data can contain valuable information about revenue generation, customer behavior, product demand, and purchasing patterns. However, analyzing raw data without a structured reporting system can make it difficult to identify trends and performance differences.

This project addresses the need for a clear and accessible way to explore FNP sales data.

The analysis focuses on questions such as:

- How can sales performance be monitored more effectively?
- Which products and categories contribute to business performance?
- How do sales trends change over time?
- What customer purchasing patterns can be explored?
- How can sales information be presented in a dashboard for easier interpretation?

## 🎯 Project Objectives

The main objectives of this project are to:

- Organize and prepare sales-related datasets for analysis.
- Explore customer, order, and product information.
- Analyze sales performance and revenue trends.
- Identify product and category performance patterns.
- Examine seasonal and time-based sales behavior.
- Present analytical information through Excel visualizations.
- Develop a clear, interactive reporting experience where supported by the workbook.
- Demonstrate practical data analytics and dashboard development skills.

## 🗂️ Dataset

The repository contains three CSV datasets representing different parts of the FNP sales information.

| Dataset | Description |
|---|---|
| `customers.csv` | Customer-related data for customer analysis. |
| `orders.csv` | Order-related data for sales and order analysis. |
| `products.csv` | Product-related data for product performance analysis. |

The repository also contains `Book1.xlsx`, which serves as the main Excel workbook.

**Note:** Refer to the source files for the exact column names, data types, date range, and number of records. These details should be documented from the actual data rather than assumed.

### Dataset Preparation

Before performing analysis, the datasets should be checked for:

- Missing or blank values.
- Duplicate records.
- Inconsistent text formatting.
- Incorrect data types.
- Invalid or inconsistent dates.
- Potentially unmatched customer, order, or product references.
- Values that could affect calculations or visualizations.

The objective is to establish a consistent foundation for reliable analysis.

## 📁 Project Structure

The repository contains the following files:

```text
Excel-fnp-dashboard-/
│
├── Book1.xlsx
├── customers.csv
├── orders.csv
├── products.csv
├── Executive Summary.docx
├── Ferns and Petals Sales Analysis.pdf
├── Screenshot 2026-10-16 120509.png
└── README.md
```

### File Descriptions

- **`Book1.xlsx`** — Main Excel workbook for the project.
- **`customers.csv`** — Customer-related source dataset.
- **`orders.csv`** — Order-related source dataset.
- **`products.csv`** — Product-related source dataset.
- **`Executive Summary.docx`** — Project executive summary.
- **`Ferns and Petals Sales Analysis.pdf`** — Sales analysis report.
- **`Screenshot 2026-10-16 120509.png`** — Dashboard preview image.
- **`README.md`** — Project documentation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Excel | Data analysis, calculations, reporting, and dashboard development |
| Excel Formulas | Data calculations and business metric analysis |
| PivotTables | Summarizing and aggregating data |
| PivotCharts | Visualizing summarized information |
| Power Query | Data import and transformation, where used in the workbook |
| Power Pivot | Data modeling, where used in the workbook |
| Data Visualization | Presenting trends and comparisons clearly |
| GitHub | Project hosting, version control, and documentation |

*The specific Excel features used can be confirmed by inspecting the workbook.*

## 🔄 Project Pipeline

The project follows a typical end-to-end sales analytics workflow.

```text
Raw CSV Datasets
       |
       v
Data Inspection
       |
       v
Data Cleaning and Preparation
       |
       v
Data Integration and Validation
       |
       v
Sales Data Analysis
       |
       v
KPI Calculation and Summarization
       |
       v
Excel Charts and Dashboard
       |
       v
Business Insights and Recommendations
```

### Pipeline Steps

**Step 1: Data Collection**

Load the customer, order, and product datasets into the analysis workflow.

**Step 2: Data Inspection**

Review column names, data types, missing values, duplicate records, and dataset consistency.

**Step 3: Data Cleaning**

Address data quality issues that could affect calculations, comparisons, and reporting.

**Step 4: Data Integration**

Determine how customer, order, and product information can be related using appropriate keys, where applicable.

**Step 5: Exploratory Data Analysis**

Explore sales patterns, revenue distribution, product performance, and customer-related trends.

**Step 6: KPI Development**

Calculate relevant business measures based on the available data.

**Step 7: Dashboard Development**

Organize key metrics and visualizations into a readable Excel dashboard.

**Step 8: Validation and Reporting**

Check calculations, review visualizations, and summarize findings for business interpretation.

## 🧹 Data Cleaning Summary

Data quality is important because incorrect or inconsistent records can affect sales totals, averages, and comparisons.

The following checks are relevant to this project:

| Cleaning Area | Purpose |
|---|---|
| Missing values | Identify incomplete records and assess their impact |
| Duplicate records | Check for repeated rows or potentially duplicated transactions |
| Data types | Ensure numeric, text, and date fields are represented correctly |
| Text standardization | Improve consistency in categorical values |
| Date validation | Check date values and chronological consistency |
| Relationship validation | Check consistency between customer, order, and product references |
| Calculation checks | Validate derived metrics and aggregated totals |

The exact transformations and corrections performed should be confirmed from the workbook or its Power Query steps.

## 🔍 Exploratory Data Analysis

The project focuses on business-oriented exploration of FNP sales data.

Areas of analysis may include:

- **Sales performance:** Understand overall sales and revenue patterns.
- **Time-based trends:** Explore differences across available dates or periods.
- **Product performance:** Compare products using relevant sales measures.
- **Category analysis:** Examine performance across available product categories.
- **Customer analysis:** Explore customer-related purchasing patterns.
- **Seasonal demand:** Investigate variations associated with occasions or periods, if supported by the data.

These analytical views help organize business information into useful comparisons.

## 📈 Dashboard Features

The Excel dashboard is intended to make sales information easier to interpret through structured reporting and visualization.

Potential analytical views include:

- Sales performance summaries.
- Revenue and order-related KPIs.
- Product performance comparisons.
- Category-level analysis.
- Time-based sales trends.
- Customer-related analysis.
- Interactive filtering, where implemented in the workbook.

### Dashboard Preview

![FNP Sales Analysis Dashboard](Screenshot%202026-10-16%20120509.png)

If the preview does not render in GitHub, open the [dashboard screenshot directly](https://github.com/Sapna2026/Excel-fnp-dashboard-/blob/main/Screenshot%202026-10-16%20120509.png).

To explore the full dashboard, download and open `Book1.xlsx` in Microsoft Excel.

## 📌 Key Performance Indicators

The following business KPIs are relevant to a sales analysis dashboard. Their inclusion and formulas should be verified against the actual workbook.

| KPI | Description |
|---|---|
| Total Revenue | Sum of the relevant sales or revenue values |
| Total Orders | Count of distinct orders, using the appropriate order identifier |
| Average Order Value (AOV) | Revenue divided by the number of eligible orders |
| Product Performance | Comparison of products using relevant sales measures |
| Category Performance | Comparison of sales across product categories |
| Period-wise Revenue | Revenue summarized across available time periods |
| Customer Metrics | Customer-related measures supported by the available fields |

**Example calculation:**

\[
\text{Average Order Value} =
\frac{\text{Total Revenue}}{\text{Total Orders}}
\]

The formula should use consistent definitions and a clearly specified reporting period.

## 🤖 Models Compared

This project is an Excel-based sales analytics and dashboard project, not a machine-learning modeling project.

Therefore, machine-learning algorithms such as Linear Regression, Random Forest, or XGBoost are not presented as models used in this analysis.

The project instead emphasizes descriptive analytics, data summarization, business KPIs, and visualization.

## 📏 Evaluation Metrics

Traditional machine-learning evaluation metrics such as accuracy, precision, recall, F1-score, and RMSE are not applicable unless a predictive modeling component is added.

For this project, evaluation should focus on:

- **Calculation accuracy:** Whether dashboard totals agree with the underlying source data.
- **Data consistency:** Whether categories, dates, and identifiers are handled consistently.
- **Metric validity:** Whether KPI formulas match their intended business definitions.
- **Aggregation accuracy:** Whether summarized values reconcile with the relevant detailed records.
- **Visualization clarity:** Whether charts communicate comparisons and trends effectively.
- **Usability:** Whether users can navigate and interpret the dashboard efficiently.

No numerical performance score is claimed here because verified evaluation results have not been established.

## 💡 Key Findings

The project is designed to help explore the following business questions:

- Which products perform strongly based on the selected sales measure?
- How does revenue vary across available time periods?
- Which product categories contribute to sales performance?
- What patterns can be observed in customer-related data?
- Are there periods or occasions associated with different purchasing patterns?

The specific answers should be drawn from the actual workbook and dataset. Numerical findings and rankings should only be added after validating the analysis results.

## 🧠 Business Recommendations

The following are potential actions that can be considered after validating the findings:

1. **Improve product planning:** Use verified product performance patterns to inform inventory and assortment decisions.
2. **Plan seasonal campaigns:** Align marketing activities with demonstrated changes in demand.
3. **Monitor sales performance:** Review key metrics consistently to identify meaningful changes.
4. **Understand customers:** Use customer-level analysis, where supported by the data, to improve targeting.
5. **Improve reporting efficiency:** Maintain a structured dashboard that simplifies recurring business reviews.
6. **Validate decisions:** Support recommendations with reconciled figures and clearly defined metrics.

These are proposed applications of the analysis, not claims that specific business outcomes have already been achieved.

## 💻 Installation

This is an Excel-based project. A Python environment or package installation is not required to open the workbook.

### Requirements

- Microsoft Excel or a compatible spreadsheet application.
- Access to the project repository.
- The source datasets, if required by the workbook's data connections or refresh process.

### Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/Sapna2026/Excel-fnp-dashboard-.git
```

Navigate to the project folder:

```bash
cd Excel-fnp-dashboard-
```

Alternatively, visit the [GitHub repository](https://github.com/Sapna2026/Excel-fnp-dashboard-) and select **Code → Download ZIP**.

## ▶️ How to Run

1. Clone or download the repository.
2. Open the project folder.
3. Open `Book1.xlsx` in Microsoft Excel.
4. Review the available worksheets and dashboard.
5. Use available filters or slicers if they are implemented.
6. Review the metrics and visualizations.
7. Open the source CSV files if you want to inspect the underlying data.
8. Refer to `Ferns and Petals Sales Analysis.pdf` and `Executive Summary.docx` for supporting project documentation.

### Troubleshooting

- If the workbook contains external data connections, keep the source CSV files in their expected locations.
- If a PivotTable or chart appears outdated, inspect the workbook's refresh settings and update the relevant data.
- If a visualization does not appear as expected, verify the source range and calculation logic.
- Some Excel features may behave differently in alternative spreadsheet applications.

## 📦 Project Deliverables

The repository includes several deliverables for reviewing the analysis:

| Deliverable | Use |
|---|---|
| Excel workbook | Explore the dashboard and workbook analysis |
| CSV datasets | Inspect customer, order, and product source data |
| PDF report | Review the sales analysis report |
| Executive summary | Read the project summary |
| Dashboard screenshot | Preview the dashboard on GitHub |

## 🎓 Challenges and Learnings

This project provides practical experience in:

- Structuring datasets for business analysis.
- Understanding relationships between different data sources.
- Applying spreadsheet-based analytical techniques.
- Building KPI-oriented reporting.
- Presenting information using charts and dashboards.
- Translating sales data into business questions.
- Documenting a data analytics project professionally.

## 🚀 Future Improvements

Possible enhancements include:

- Add a detailed data dictionary with column definitions.
- Document exact cleaning and transformation steps.
- Include a verified KPI glossary and calculation formulas.
- Add additional interactive filters where useful.
- Improve dashboard navigation and visual consistency.
- Document validated findings with supporting charts.
- Add a reproducible data refresh workflow.
- Build a complementary Power BI dashboard.
- Introduce forecasting only if sufficient historical data and a clear business objective are available.

## 🧩 Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Preparation
- Exploratory Data Analysis
- Sales and Retail Analytics
- KPI Reporting
- Data Visualization
- Dashboard Development
- Business Insight Generation
- Data Documentation
- GitHub Project Presentation

## 📄 License

No license file is required in the repository.

## 👩‍💻 Author

**Sapana Yadav**

Aspiring Data Analyst | Excel | SQL | Python | Power BI

- **GitHub Profile:** [Sapna2026](https://github.com/Sapna2026)
- **Project Repository:** [Excel-fnp-dashboard-](https://github.com/Sapna2026/Excel-fnp-dashboard-)

I'm building my data analytics portfolio by working on projects that combine data preparation, business analysis, and visualization to communicate insights clearly.

---

⭐ If you find this project useful, feel free to explore the repository and share feedback.

**Thank you for visiting my project!**

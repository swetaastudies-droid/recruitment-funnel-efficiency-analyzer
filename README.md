# 📊 Recruitment Funnel Efficiency Analyzer

An interactive **HR Analytics project** designed to analyze recruitment funnel performance, identify candidate drop-offs, evaluate recruitment source effectiveness, track hiring KPIs, and perform What-If analysis using **Microsoft Power BI, Excel, and DAX**.

---

## 📌 Project Overview

Recruitment teams generate large volumes of candidate data across multiple stages of the hiring process. Analyzing this data helps organizations understand where candidates are dropping off, how efficiently different recruitment sources perform, how long hiring takes, and how recruitment costs can be managed.

The **Recruitment Funnel Efficiency Analyzer** converts recruitment data into an interactive Power BI dashboard that provides actionable insights into the complete recruitment lifecycle — from application to hiring.

The project focuses on:

- Recruitment funnel analysis
- Candidate conversion and drop-off analysis
- Recruitment KPI tracking
- Recruitment source effectiveness
- Time-to-hire analysis
- Cost-per-hire analysis
- Longest recruitment case identification
- What-If scenario analysis
- HR decision support

---

## 🎯 Project Objectives

The key objectives of this project are to:

- Analyze the recruitment funnel from application to hiring.
- Measure conversion rates across recruitment stages.
- Identify major candidate drop-off points.
- Calculate important recruitment KPIs.
- Compare the effectiveness of different recruitment sources.
- Analyze average time-to-hire trends.
- Identify recruitment cases with unusually high hiring duration.
- Evaluate the impact of potential recruitment improvements using What-If analysis.
- Provide an interactive dashboard for HR decision-making.

---

## 🗂️ Dataset

The recruitment dataset contains candidate-level information covering different stages of the hiring process.

### Key Data Fields

| Field | Description |
|---|---|
| Candidate_ID | Unique identifier for each candidate |
| Source | Recruitment source such as LinkedIn, Referral, Job Portal, or Campus |
| Department | Department for which the candidate applied |
| Applied_Date | Date on which the candidate applied |
| Stage | Current recruitment stage |
| Stage_Entry_Date | Date candidate entered the stage |
| Stage_Exit_Date | Date candidate exited the stage |
| Hiring_Cost | Recruitment cost associated with the candidate |
| Final_Status | Final outcome of the recruitment process |
| Time_to_Hire_Days | Number of days taken from application to hiring |

### Recruitment Stages

**Applied → Screened → Interviewed → Offered → Hired**

Rejected candidates are also tracked as part of the recruitment process.

---

## 🔍 Analysis Performed

### 1. Recruitment Funnel Analysis

The recruitment funnel tracks the number of candidates progressing through each stage:

- Applied
- Screened
- Interviewed
- Offered
- Hired

This helps identify the stages where candidate volume decreases significantly.

### 2. Recruitment KPI Analysis

The dashboard calculates key recruitment performance indicators including:

- Total Applications
- Total Hires
- Application-to-Hire Rate
- Offer-to-Hire Rate
- Average Time-to-Hire
- Cost-per-Hire
- Offer Acceptance Rate

### 3. Drop-Off & Bottleneck Analysis

Candidate drop-off is analyzed across recruitment stages to identify potential bottlenecks.

The analysis helps HR teams understand where significant candidate losses occur and where recruitment processes may require further investigation.

### 4. Recruitment Source Effectiveness

Recruitment sources are compared based on:

- Number of candidates hired
- Hiring contribution
- Conversion performance
- Average Time-to-Hire

The sources analyzed include:

- LinkedIn
- Referral
- Job Portal
- Campus

### 5. Time-to-Hire Trend Analysis

Monthly average Time-to-Hire is visualized to identify changes and patterns in recruitment efficiency over time.

### 6. Longest Recruitment Cases

The dashboard identifies recruitment cases with the highest Time-to-Hire values, allowing HR teams to investigate lengthy recruitment processes.

---

# 📊 Power BI Dashboard

The interactive dashboard contains the following visualizations:

### Recruitment Funnel

Displays candidate progression from:

**Applied → Screened → Interviewed → Offered → Hired**

### KPI Cards

The dashboard includes KPI cards for:

- Total Applications
- Total Hires
- Application-to-Hire Rate
- Offer-to-Hire Rate
- Cost-per-Hire
- Average Time-to-Hire

### Recruitment Funnel Drop-Off

A bar chart highlights candidate drop-off percentages across recruitment stages.

### Hires by Recruitment Source

A pie/donut chart displays the distribution of hires across recruitment sources.

### Average Time-to-Hire Trend

A monthly line chart tracks changes in average recruitment duration.

### Top Recruitment Cases

A detailed table highlights recruitment cases with longer Time-to-Hire durations.

---

## 🔢 Key Dashboard Metrics

The current dashboard provides the following results:

| KPI | Value |
|---|---:|
| Total Applications | 250 |
| Total Hires | 58 |
| Application-to-Hire Rate | 23.20% |
| Offer-to-Hire Rate | 81.69% |
| Average Time-to-Hire | 35.81 Days |
| Cost-per-Hire | 5.19K |

### Recruitment Funnel

| Stage | Candidates |
|---|---:|
| Applied | 250 |
| Screened | 211 |
| Interviewed | 122 |
| Offered | 71 |
| Hired | 58 |

---

# 🔮 What-If Analysis

A major component of the project is the implementation of **What-If Analysis** in Power BI.

The analysis allows HR teams to simulate potential improvements in the recruitment process.

### Scenario 1 — Reduce Interview-to-Offer Drop-Off

This scenario evaluates the potential impact of reducing interview-to-offer drop-off.

The analysis examines changes in:

- Projected Hires
- Application-to-Hire Rate
- Cost-per-Hire

### Scenario 2 — Increase Referral Hiring

This scenario evaluates the potential impact of increasing hiring through employee referrals.

The analysis measures changes in:

- Projected Referral Hires
- Projected Total Hires
- Application-to-Hire Rate
- Cost-per-Hire

### Scenario 3 — Reduce Time-to-Hire

This scenario evaluates the impact of reducing the average recruitment duration.

The user can adjust the number of days reduced through an interactive Power BI parameter.

The dashboard then calculates the projected Time-to-Hire.

---

## 🛠️ Tools & Technologies

### Data Preparation
- Microsoft Excel

### Data Visualization & Analytics
- Microsoft Power BI

### Calculations
- DAX
- Power BI Measures
- What-If Parameters

### Analytical Techniques
- Recruitment Funnel Analysis
- KPI Analysis
- Conversion Analysis
- Drop-Off Analysis
- Source Effectiveness Analysis
- Trend Analysis
- Scenario Analysis

---

## 📈 Key Insights

The dashboard provides visibility into:

- Candidate movement across recruitment stages.
- Recruitment conversion performance.
- Major candidate drop-off points.
- Contribution of different recruitment sources.
- Average recruitment time trends.
- Recruitment cases requiring additional investigation.
- Potential impact of improving recruitment conversion.
- Potential impact of increasing referral hiring.
- Potential impact of reducing Time-to-Hire.

These insights can support HR teams in evaluating recruitment processes and identifying areas for further analysis.

---

## 📸 Dashboard Preview

### Recruitment Funnel & KPI Dashboard

Add your Power BI dashboard screenshot here.

```text
![Recruitment Funnel Dashboard](Screenshots/Recruitment_Funnel_Dashboard.png)

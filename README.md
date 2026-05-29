# 📊 HR Workforce Attrition Intelligence Report

> A full-cycle HR analytics solution built entirely in **Microsoft Excel** and **Power BI** — covering descriptive analysis, behavioral segmentation, risk scoring, and forward-looking workforce vulnerability forecasting across 1,470 employee records.

---

## 🧭 Project Objective

Employee attrition is not random — it is predictable, measurable, and preventable when the right signals are identified early. This project transforms raw HR data into a structured, multi-layered analytical system that answers four critical business questions:

1. **What does attrition look like today** — across departments, roles, income levels, and demographics?
2. **What behavioral and environmental factors drive it** — satisfaction, overtime, tenure, travel?
3. **Which employees are most at risk right now** — and what does their risk profile look like?
4. **What does future workforce exposure cost the business** — and where should intervention be prioritized?

---

## 🛠️ Tools & Methodology

| Tool | Role in the Project |
|------|---------------------|
| **Microsoft Excel** | Data cleaning, feature engineering, pivot-based exploratory analysis |
| **Power BI** | Multi-page interactive intelligence report with DAX measures, dynamic filtering, and risk segmentation logic |

> This project was built using **only Excel and Power BI** — no Python, no SQL, no external libraries. Every insight was derived through structured analytical thinking applied directly to the data.

**Feature Engineering Highlights (Excel):**
- `Age_Group` — binned from continuous age for cohort-level analysis
- `Income_Band` — segmented into Low / Medium / High / Very High tiers
- `Tenure_Group` — bucketed into career lifecycle stages (0–2, 3–5, 6–10, 10+ years)
- `Risk Score` — composite scoring model built using weighted attrition risk factors
- `Attrition_Flag` — binary encoding for DAX-based attrition rate calculations

---

## 📋 Report Structure

### Page 1 — Workforce Attrition Summary
![Workforce Attrition Summary](screenshots/01_workforce_attrition_summary.png)

**Organizational-level attrition decomposition across all major workforce dimensions.**

| Metric | Value |
|--------|-------|
| Total Employees | 1,470 |
| Active Employees | 1,233 |
| Total Attrition | 237 |
| Overall Attrition Rate | 16.12% |
| Avg. Monthly Income (Attrited) | ₹4.79K |
| Avg. Monthly Income (Retained) | ₹6.83K |
| Average Tenure | 7.01 years |

**Key Findings:**
- Sales and HR departments exceed the company attrition benchmark by ~5 percentage points
- Sales Representatives carry an attrition rate of **39.8%** — nearly 2.5× the company average
- Employees aged 18–25 leave at **35.8%** — nearly 4× the rate of the 36–45 cohort
- Low-income employees (<₹3K) show **28.6% attrition**, compared to just **5.6%** in the Very High bracket
- Male attrition (17.0%) marginally exceeds female attrition (14.8%)

---

### Page 2 — Attrition Drivers & Behavioral Analysis
![Attrition Driver Analysis](screenshots/02_attrition_driver_analysis.png)

**Behavioral, attitudinal, and structural factors correlated with attrition — isolating the levers that matter most.**

**Key Findings:**
- Employees rating Work-Life Balance as "Bad" (1) leave at **31.3%** — 3× the rate of those rating it "Best" (4) at 17.6%
- Two statistically distinct attrition peaks emerge: **new joiners (0–2 yr) at 29.8%** and a **mid-career plateau (3–5 yr) at 13.8%**
- Overtime-assigned employees show **30.5% attrition** vs. 10.4% for non-OT employees — a **3× multiplier**
- Frequent business travelers face **24.9% attrition** against 8.0% for non-travelers — another **3× signal**
- Single employees exit at **25.5%** — more than double the rate of married employees at 12.5%
- The low Job Satisfaction + low Environment Satisfaction quadrant concentrates the highest attrition cluster across all departments

---

### Page 3 — Workforce Risk Segmentation & Retention Exposure
![Attrition Risk Intelligence](screenshots/03_attrition_risk_intelligence.png)

**A composite risk-scoring model classifying the active workforce into Low, Medium, and High risk tiers based on multi-factor attrition signals.**

| Risk Tier | Employee Count | Share | Attrition Rate |
|-----------|---------------|-------|----------------|
| High Risk | 460 | 31% | 31.52% |
| Medium Risk | 364 | 25% | 10.71% |
| Low Risk | 646 | 44% | 8.20% |

**Average Risk Score: 7.10**

**Key Findings:**
- Sales carries the highest departmental risk concentration at **44.4% high-risk attrition**
- Human Resources follows at **40.0%**, with R&D at 27.5%
- Employees in their first 2 years carry the highest average risk score of **9.8** — declining steadily to 3.8 for tenured employees (10+ years)
- Lower average monthly income directly correlates with elevated risk scores across all departments
- High-risk employees working overtime face a **48.6% attrition rate** vs. 20.2% for those without OT — overtime is the single most amplifying risk factor

---

### Page 4 — Predictive Attrition Intelligence & Future Workforce Risk
![Future Attrition Prediction](screenshots/04_future_attrition_prediction.png)

**Forward-looking exposure analysis of the current active workforce — quantifying future vulnerability by department, role, tenure, and cost.**

| Metric | Value |
|--------|-------|
| Active Employees | 1,233 |
| Active High-Risk Employees | 298 |
| High Risk % of Active Workforce | 37.3% |
| Active Average Risk Score | 8.50 |
| Projected Attrition Cost | ₹52,90,218 |

**Key Findings:**
- Human Resources carries the most severe future exposure at **49.0% high-risk active employees**
- R&D follows at **41.7%**, Sales at 25.4%
- Early-career employees (0–2 yr) carry an average active risk score of **14.4** — more than 4× that of tenured employees
- Active employees on overtime face a **63.3% high-risk rate** vs. 29.3% for non-OT — the strongest forward-looking risk signal in the entire report
- Research Scientists (118) and Laboratory Technicians (91) represent the largest high-risk talent pools by job role — both critical operational functions

---

## 🔑 Cross-Report Insight Summary

| Attrition Driver | Impact |
|-----------------|--------|
| Overtime (Yes vs. No) | 30.5% vs. 10.4% — **3× multiplier** |
| Income Band (Low <3K vs. Very High 12K+) | 28.6% vs. 5.6% — **5× gap** |
| Age Group (18–25 vs. 36–45) | 35.8% vs. 9.2% — **4× gap** |
| Work-Life Balance (Bad vs. Best) | 31.3% vs. 17.6% |
| Business Travel (Frequent vs. Non-Travel) | 24.9% vs. 8.0% — **3× multiplier** |
| Marital Status (Single vs. Married) | 25.5% vs. 12.5% — **2× multiplier** |
| Tenure Window (0–2 yr) | 29.8% — highest flight risk period |

---

## 💡 Strategic Recommendations

**1. Address Overtime Dependency**
Overtime is the single most consistent amplifier of attrition risk across all pages of this report. Structural workload redistribution in Sales and R&D should be a priority action.

**2. Realign Compensation for Low-Income Bands**
The 5× attrition gap between the lowest and highest income bands signals a retention-through-compensation problem, not just a culture issue. Targeted salary reviews for Sub-₹3K employees — particularly Sales Representatives — would yield measurable impact.

**3. Redesign the Onboarding & Early-Tenure Experience**
The 0–2 year tenure window consistently emerges as the highest-risk period across every analysis layer. Structured mentorship, role clarity, and 90-day check-in frameworks can reduce this peak significantly.

**4. Introduce Travel Flexibility Policies**
Frequent business travelers leave at 3× the rate of non-travelers. Hybrid travel models or rotation policies would reduce this exposure without sacrificing operational output.

**5. Prioritize Immediate Retention Action for the 298 Active High-Risk Employees**
With a projected attrition cost of ₹52,90,218, targeted interventions — manager check-ins, compensation reviews, role progression conversations — for this segment represent the highest-ROI retention investment available.

---

## 📂 Repository Structure

```
HR-Workforce-Attrition-Intelligence-Report/
│
├── HR_Employee_Attrition_Analysis.xlsx       # Source data + pivot analysis + risk scoring
├── HR_Workforce_Attrition_Intelligence.pbix  # Power BI report file
│
├── screenshots/
│   ├── 01_workforce_attrition_summary.png
│   ├── 02_attrition_driver_analysis.png
│   ├── 03_attrition_risk_intelligence.png
│   └── 04_future_attrition_prediction.png
│
└── README.md
```

---

## 👤 About This Project

**Project #3 — Data Analytics Portfolio**

Built end-to-end using **Microsoft Excel and Power BI exclusively** — demonstrating that rigorous analytical thinking, structured feature engineering, and executive-level storytelling do not require complex tooling. Every metric, segment, and insight in this report was derived from first principles applied directly to the raw data.

---

*⭐ If this project resonates with your work or hiring needs, feel free to connect.*

---

## 👩‍💻 Author

**Indumathi**  
📎 [GitHub](https://github.com/Indumathi96)  
📎 EmailAddress: (indumathi1305@gmail.com)

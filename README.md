# 📞 QA Sales Dashboard

> **Call quality analytics dashboard built on Google Sheets — evaluating sales agent performance across 7 key KPIs**

---

## 📌 Overview

This dashboard provides a real-time view of sales call quality assessments conducted by a QA team. It tracks agent performance across multiple evaluation criteria, identifies top and bottom performers, and helps sales managers make data-driven coaching decisions.

---

## 🎯 Business Problem

The sales team needed a way to:
- Systematically evaluate the quality of sales calls
- Track agent performance trends over time
- Identify coaching opportunities for underperforming agents
- Monitor KPI scores across 7 evaluation dimensions

---

## 🔄 How Data Flows

```
 📋 QA Team               📥 Data Collection           📊 Visualization
─────────────────         ────────────────────         ───────────────────
QA Teams evaluate            Google Forms                 Google Sheets
  sales calls     ────►   (Form responses auto   ────►   (Data collection
                          populate Google Sheet)           and Dashboard)
                                         
```

**Process:**
1. QA evaluator listens to a live/recorded sales call
2. Fills out a **Google Form** with scores across 7 criteria
3. Responses **automatically populate** a Google Sheet
4. Dashboard **updates in real-time** with new evaluations

---

## 📊 Dashboard Sections

### 🔢 What are our KPIs ? 
| KPI | Description |
|--------|-------|
| Calls Evaluated | Did the agent open the call professionally and make a good first impression? |
| Greetings & Intro Avg | Did the agent ask the right questions to understand the customer's needs? |
| Relevant Probing Avg | Did the agent know the product well enough to answer customer questions confidently? |
| Product Knowledge Avg | Did the agent stay calm, polite and professional throughout the call? |
| Professional Tone Avg | Did the agent handle customer concerns effectively and keep the conversation moving? |
| Objection Handling Avg | Did the agent close the call properly with clear next steps? |
| Closing Protocols Avg | Total score out of 100 combining all criteria above. |

### 📈 Average Score by Evaluation Date
- Line chart tracking all 7 KPI scores over time
- Helps identify performance trends and dips

### 📊 KPI Breakdown (Bar Chart)
- Side-by-side comparison of all 7 KPIs
- Instantly highlights weakest areas (Relevant Probing at 78.5%)

### 👤 Avg Score per Call — Agentwise
- Bar chart showing individual agent performance
- Ranked from highest to lowest scorer

### 🏆 Top 5 & Bottom 5 Agents
| Top 5 Agents | Score |
|-------------|-------|
| Agent 1 | 95% |
| Agent 2 | 93% |
| Agent 3 | 93% |
| Agent 4 | 92% |
| Agent 5 | 92% |

### 📋 Sessions Conducted per Agent
- Table showing number of evaluated sessions per agent

---

## 🗂️ Data Source — Google Form Fields

| Column | Description |
|--------|-------------|
| Timestamp | Auto-generated submission time |
| Agent Name | Sales agent being evaluated |
| Evaluator Name | QA team member conducting evaluation |
| Call Date | Date of the evaluated call |
| Call Type | Type/category of sales call |
| Decision-Maker Presence | Whether decision maker was on call |
| Call Recording Link | Link to recorded call |
| Greetings & Intro Score | Score out of 15 |
| Relevant Probing Score | Score out of 25 |
| Product Knowledge Score | Score out of 15 |
| Soft Skills & Professional Tone | Score |
| Objection Handling Score | Score out of 15 |
| Closing Protocols Score | Score out of 15 |
| Critical Failures Observed | Yes/No flag |
| TOTAL SCORE | Score out of 100 |
| Evaluation Date | Date of QA evaluation |

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Google Forms | Data collection from QA evaluators |
| Google Sheets | Data storage, transformation & dashboard |
| Google Sheets Charts | Data visualization |

---

## 📸 Dashboard Preview

![QA Sales Dashboard](./QA%20Sales%20Dashboard.png)
---

## 💡 Key Insights Delivered

- **Relevant Probing (78.5%)** is the weakest KPI — flagged for targeted agent training
- **Professional Tone (94.9%)** is consistently the strongest area across all agents
- Top 5 agents maintain **92–95%** scores — used as benchmarks for team coaching
- Day-wise trend analysis helps QA managers spot evaluation consistency issues

---

## 🖥️ Other Dashboards

> 📞 **All other dashboards are available on request. Feel free to reach out to schedule a call or Google Meet.**

---

## ⚠️ Confidentiality Note

This dashboard was built for a real sales organization. Agent names shown are anonymized sample data used for portfolio demonstration purposes.

---

## 👤 Author

**Mirza Wajeeh Baig** — Data Analyst
[![GitHub](https://img.shields.io/badge/GitHub-mirzawajeehbaig-181717?style=flat&logo=github)](https://github.com/wajeehbaigmirza-cmd)

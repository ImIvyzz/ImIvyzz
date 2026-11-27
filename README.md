<p align="center">
  <img src="assets/banner.svg" alt="Ivan Ignacio Velazquez, Data Analyst. Power BI, SQL and Python, plus workflow automation." width="100%">
</p>

## Hi, I'm Ivan

I'm a data analyst who turns messy business data into dashboards, models and automations that people actually use. I'm finishing a B.Sc. in Data Science & AI and work as a freelance analyst.

My latest client project: I moved a visa consultancy's **1,000+ client records** into a CRM and automated its intake, follow-ups and case assignment for a 6-person team.

**Open to remote** Data Analyst, BI and automation roles (full-time, contract or internship). Based in Mexico (UTC-6), with full overlap with US and Canadian teams.

```python
ivan = {
    "role":      "Data Analyst",
    "based_in":  "Xalapa, Mexico (UTC-6), working remotely",
    "studying":  "B.Sc. Data Science & AI, IEU (Dec 2027)",
    "good_at":   ["SQL", "Python", "Power BI", "predictive models", "n8n", "Zapier"],
    "languages": {"English": "C1", "Spanish": "native"},
    "currently": "building a Power BI dashboard on churn risk scores",
}
```

## Connect with me

<p align="center">
  <a href="mailto:ivanignacio143@gmail.com"><img src="assets/btn-email.svg" alt="Email me: ivanignacio143@gmail.com" width="32%"></a>
  <a href="https://www.linkedin.com/in/ivan-ignacio-velazquez-b436362b6/"><img src="assets/btn-linkedin.svg" alt="Connect on LinkedIn" width="32%"></a>
  <a href="https://imivyzz.github.io"><img src="assets/btn-resume.svg" alt="View my resume" width="32%"></a>
</p>

## Toolkit

<p align="center">
  <img src="assets/stack.svg" alt="Analysis: SQL, Python, pandas, scikit-learn, R, Jupyter, Git. BI: Power BI, DAX, Tableau, Excel, R Shiny. Automation and AI: n8n, Zapier, Monday.com, LLM APIs, Claude Code." width="100%">
</p>

## Featured work

<p align="center">
  <a href="https://github.com/ImIvyzz/telco-churn"><img src="assets/card-churn.svg" alt="Telco customer churn prediction. The model catches 80% of churners, ROC-AUC 0.84." width="49%"></a>
  <a href="https://imivyzz.github.io/olist-analytics/"><img src="assets/card-olist.svg" alt="E-commerce delivery promise engine. On 25,676 unseen orders it promised 22.1 days instead of 24.1 and was late 3.3% of the time vs. 4.0%." width="49%"></a>
</p>

<details>
<summary><b>Telco churn: what's inside the repo</b></summary>
<br>

- Cleaned and explored 7,043 customers: churners are 26.5% of customers and 30.5% of monthly revenue.
- Chi-square tests to separate real drivers (contract, tech support, payment method) from noise (gender and phone service show no effect).
- scikit-learn pipeline with a baseline, logistic regression and random forest, compared with 5-fold cross-validation.
- Risk scores for every customer, ready for a CRM or a BI dashboard.
- A 14-slide business presentation with the findings and four recommended actions.

</details>

<details>
<summary><b>E-commerce delivery promises: what's inside the repo</b></summary>
<br>

- Cleaned the raw export of Olist, a Brazilian marketplace (11 CSV files, 1.56M rows), with SQL in DuckDB and 25 data quality checks.
- Built a delivery promise engine (quantile gradient boosting plus conformal calibration) and backtested it month by month: on 25,676 orders it never saw, it promised 2 days less and was late less often (3.3% vs. 4.0%).
- A late-risk model scores each order at checkout: the riskiest 10% are late 3.8 times as often as average.
- Ranked the phrases customers write when an order arrives late vs. on time, over 22,000 review comments.
- Put it all in a web app: one screen for managers, an interactive table of 26,271 orders, and eight pages for analysts.

[Open the app](https://imivyzz.github.io/olist-analytics/), browse [the repository](https://github.com/ImIvyzz/olist-analytics) or read [the 14-slide case study](https://github.com/ImIvyzz/olist-analytics/blob/main/olist-case-study.pdf).

</details>

## Background

- 🎓 **B.Sc. Data Science & Artificial Intelligence**, IEU University, Mexico (expected Dec 2027)
- 🍁 **Diploma in Data Analytics (co-op)**, Toronto School of Management, Canada (2023–2024)
- 📊 **Diploma in Power BI, AI Tools & BI**, Cámara de Comercio Exterior (2026, in progress)

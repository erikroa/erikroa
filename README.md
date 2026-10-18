# Erik Roa

**Senior CX & Revenue Operations** | Berlin

Senior CX Operations Manager in B2B SaaS, working across CX Ops and RevOps, with 8+ years in Customer Success behind it. I own the processes behind retention and ARR reporting: monthly existing-business reconciliation, churn and downsell classification, billing migrations, and the CRM and CS-platform data quality those numbers depend on.

- **Stack**: SQL, Python, dbt, BigQuery, Snowflake, Tableau, Looker Studio, Salesforce, Planhat, Chargebee
- **Certification**: Google Cloud Data Analytics
- **Languages**: Spanish (native), English (fluent), German (learning)

## What I own

- **Month-end ARR close**: reconciling finance ARR movements against CRM bookings across expansion, downsell and churn, including the include/exclude judgment on edge cases
- **Subscription and contract operations**: bulk billing migrations, plan repricing and contract corrections, executed end to end with finance sign-off
- **System and data architecture**: integration design between CRM, customer success platform and marketing tools, plus field and data-quality clean-ups
- **Process design**: turning recurring manual work into documented, repeatable routines and validation rules

---

## Projects

All projects use public or synthetic data. No employer data is used.

### Revenue close and data quality

**[arr-bookings-reconciliation-engine](https://github.com/erikroa/arr-bookings-reconciliation-engine)** (Python, pandas, pytest): Reconciles finance ARR movements against CRM bookings using seven rules drawn from common month-end close mistakes. Reduces 119 comparisons to a 5-case worklist, with a decision log that carries over month to month.

### Retention and churn

**[nova-customer-intelligence](https://github.com/erikroa/nova-customer-intelligence)** (dbt + BigQuery): Customer health scores, churn risk flags, NRR / GRR, cohort retention and support SLA adherence for a fictional B2B SaaS company. Layered dbt models with tests and reusable macros, surfaced in Looker Studio.

**[saas-churn-prediction](https://github.com/erikroa/saas-churn-prediction)** (Python, scikit-learn, XGBoost): Predicts account churn and turns the model into a CS action list ranked by ARR at risk. Builds on the rule-based health score above with an ML approach.

### Revenue and deal desk

**[revenue-ops-analytics](https://github.com/erikroa/revenue-ops-analytics)** (BigQuery SQL, Looker Studio): Deal desk analysis of 9,994 SaaS transactions. Deals discounted above 40% average a -108.9% margin and lose about $99K across 933 deals.

**[finsys-payment](https://github.com/erikroa/finsys-payment)** (Python, pandas): Fraud concentration in 594,643 payments. A single review rule (Leisure and Travel above $500) would have caught 40% of fraud value while flagging 0.1% of transactions.

### Customer operations

**[SaaS-Support-Ticket-Analysis-View](https://github.com/erikroa/SaaS-Support-Ticket-Analysis-View)** (Python, Jupyter): Support bottlenecks across 8,469 tickets by product, channel and ticket type. Key result: resolution speed does not predict satisfaction in this data, which changes where to invest.

**[nis2-customer-classification](https://github.com/erikroa/nis2-customer-classification)** (Python, DuckDB SQL): Reference implementation for classifying a SaaS customer base against EU NIS2 and DORA, with porting notes for Snowflake, BigQuery, Postgres and dbt.

---

## How I work

- Numbers first, then the decision they support
- State the assumption, label the estimate, show the limitation
- Prefer the simple rule that covers most of the risk over the complex one that covers all of it

---

[LinkedIn](https://linkedin.com/in/erikroa)

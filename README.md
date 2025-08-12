# wholesale_retail_support_test_case
This project is a data analysis case study simulating the role of a Data Analyst.

The task was to investigate complaints about **low performance of the customer support department** for two separate services:
- **Retail sales platform**
- **Wholesale sales platform**

### Goals
Using operational-like data, the objectives were to:
1. **Evaluate** how well the support teams meet management’s response time expectations.
2. **Identify underperforming agents** and workflow bottlenecks.
3. **Assess workload distribution** between agents and teams.
4. **Estimate staffing needs** to meet KPI targets (reply within 15 minutes on average, avoid delays over 45 minutes).
5. **Suggest improvements** to scheduling, staffing allocation, and process focus to increase efficiency without additional hires.

### Analysis Process
- **Data preprocessing and cleaning** to ensure reliability of calculations.
- **Metric calculation**: average response time, request processing time, share of delayed responses.
- **Comparative performance analysis** between retail and wholesale teams.
- **Workload analysis** per agent over the quarter.
- **Scenario modeling** to determine required headcount to meet targets.
- **Actionable recommendations** to improve operational efficiency.

### Key Tools
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook** for analysis and reporting

### Outcome
The analysis revealed that:
- The wholesale team had significantly higher delays (73% of requests answered more than a day later).
- Performance issues were due to **low focus on active ticket processing** rather than insufficient staff.
- By reallocating tasks and prioritizing incoming tickets, both teams could meet KPIs without hiring new employees.

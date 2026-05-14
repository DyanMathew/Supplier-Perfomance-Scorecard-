# Supplier-Perfomance-Scorecard
Supplier Performance Scorecard — Qatar Tec W.L.L

Project Overview
This project delivers an end-to-end Supplier Performance Scorecard built using Python and Streamlit. The analysis focuses on supplier KPI evaluation, RAG risk tiering, spend-at-risk quantification, SLA variance, and procurement risk-return positioning. The project was built to bring quantitative structure to vendor evaluation and support data-driven procurement decision-making.

Suppliers Analyzed
- Supplier A
- Supplier B
- Supplier C
- Supplier D
- Supplier E
- Supplier F

Tools & Technologies Used
- Python
- Streamlit
- Plotly
- Pandas
- OpenPyXL
- Microsoft Excel

Project Objectives
- Evaluate supplier performance across multiple KPI dimensions
- Assign dynamic RAG risk tiers based on composite scores
- Quantify financial exposure through spend-at-risk analysis
- Enable real-time KPI weight recalibration by procurement teams
- Visualize supplier capability and risk positioning interactively
- Support operational handoff without requiring codebase modifications

Methodology

1. Scoring Engine Design — A weighted RAG scoring engine was engineered in Python evaluating 6 suppliers across 5 KPI dimensions — Delivery, Quality, Cost, Contract Compliance, and Qualitative Performance — producing a normalized composite score out of 100.

2. Data Processing — Python was used to:
   - clean and structure supplier KPI and PO data,
   - compute weighted composite scores,
   - assign dynamic Red-Amber-Green risk tiers,
   - calculate SLA variance against contractual benchmarks,
   - prepare datasets for Streamlit visualization.

3. Dashboard Development — Interactive analytical modules were built using Streamlit and Plotly.

Key Metrics Used

Composite Score — Normalized weighted score out of 100 across all KPI dimensions.

RAG Risk Tier — Dynamic Red-Amber-Green classification based on composite score thresholds.

Spend at Risk — Total PO value mapped against supplier risk tiers to quantify financial exposure.

SLA Variance — Measures deviation from contractual delivery and compliance benchmarks.

KPI Weights — Adjustable dimension weights reflecting business-specific risk appetite.

Dashboard Components
1. Scorecard Overview — Composite scores and RAG tier summary across all suppliers
2. KPI Breakdown — Dimension-level performance analysis per supplier
3. Supplier Capability Radar — Plotly radar chart comparing supplier profiles across KPIs
4. Trend Analysis — Performance trend tracking over time
5. Risk & Watchlist — Flagged suppliers by risk tier with intervention prioritization
6. PO Log — Live procurement order data linked to Excel for operational updates

Key Insights
- QAR 120,700 in procurement spend identified as at-risk through supplier risk tier mapping
- High-spend suppliers with low performance scores surfaced via Risk Matrix for immediate intervention
- SLA variance analysis revealed delivery and compliance gaps against contractual benchmarks
- Adjustable weight sliders enabled finance and procurement teams to reflect shifting risk priorities in real time
- Live Excel integration allowed operational data updates without any codebase modification

Project Structure

Supplier_Scorecard/
│
├── data/
├── exports/
├── assets/
│
├── app.py
├── scoring_engine.py
├── supplier_data.xlsx
├── requirements.txt

Future Improvements
- Integration with live ERP or procurement system data
- Automated supplier alert and notification system
- Month-over-month KPI trend forecasting
- Benchmarking against industry-standard supplier metrics
- Multi-category procurement expansion
- Machine learning-based supplier risk prediction

Author
Dyan Mathew

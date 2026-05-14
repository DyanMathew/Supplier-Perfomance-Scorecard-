# Supplier-Perfomance-Scorecard-
A Python-based procurement analytics tool built during a Finance & Analytics internship to bring quantitative structure to vendor evaluation and procurement risk management.
Overview
This end-to-end Supplier Performance Scorecard was independently designed and developed to replace subjective vendor assessments with a structured, data-driven scoring framework. The system evaluates 6 suppliers across 5 KPI dimensions — Delivery, Quality, Cost, Contract Compliance, and Qualitative Performance — producing a normalized composite score out of 100 with dynamic RAG (Red-Amber-Green) risk tiering logic.
Key Features

Weighted Scoring Engine — Adjustable weight sliders allow finance and procurement teams to recalibrate KPI priorities in real time, reflecting business-specific risk appetite without touching the codebase.
6 Analytical Modules built in Streamlit — Scorecard Overview, KPI Breakdown, Supplier Capability Radar (Plotly), Trend Analysis, Risk & Watchlist, and PO Log — each with interactive filtering by category, rating, and preferred supplier status.
Risk Matrix — A score-vs-spend bubble chart that surfaces suppliers carrying high financial exposure but low performance scores, directly prioritizing intervention.
SLA Variance Analysis — Quantifies delivery and compliance gaps against contractual benchmarks.
Financial Exposure Quantification — Mapped supplier risk tiers against structured PO data to identify QAR 120,700 in spend at risk, giving decision-makers direct visibility into procurement exposure.
Live Excel Integration — PO Log connects to a live Excel file, enabling the finance team to update procurement data operationally without modifying the codebase.
CSV Export — Scorecard and PO Log data exportable for downstream reporting workflows.

Tech Stack
Python · Streamlit · Plotly · Pandas · OpenPyXL
Context
Built as an independent initiative during an internship at Qatar Tec W.L.L, and presented to Finance Head Mr. Thomas Mathew — validated for further development with live procurement data. Designed for clean operational handoff to non-technical finance and procurement teams.Sonnet 4.6Adaptive

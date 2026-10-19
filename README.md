# Virtual-Data-Analysis-Associate-Intern
Logistics Warehouse Process Optimization - Lean Six Sigma (DMAIC)

📌 Project Overview

This repository contains my milestone submissions for the Virtual Data Analysis Associate Internship at YuvaIntern. The project applies the Lean Six Sigma DMAIC (Define, Measure, Analyze, Improve, Control) framework to solve a real-world supply chain challenge: excessively high order picking times leading to a drop in daily order fulfillment rates.

Through structured problem scoping, statistical hypothesis testing in Python, and strategic process improvement planning, this project demonstrates a complete data-driven operational overhaul.

📊 Dataset Used

Dataset: Logistics Warehouse Dataset (Publicly available via Kaggle)

Key Variables Analyzed: picking_time_seconds, layout_efficiency_score, stockout_count_last_month, zone, total_orders_last_month, order_fulfillment_rate, category.

🗂️ Project Structure & DMAIC Phases

[Week 1] DEFINE Phase: Problem Scoping

Objective: Define the business problem and scope of the project.

Key Deliverables:

Project Charter: Formulated SMART goals to reduce average order picking time from 45 minutes to < 20 minutes, increasing fulfillment to 95%.

SIPOC Diagram: Mapped the high-level warehouse order processing flow to identify input/output bottlenecks.

[Week 2] MEASURE Phase: Data Collection & Visualization

Objective: Establish how to measure the current state of the process.

Key Deliverables:

Data Collection Plan: Identified continuous and discrete WMS data variables (timestamps, inventory logs) to track without human bias.

Dashboard Wireframes: Sketched Control Charts and Pareto Diagrams to visualize daily delays and pinpoint motion/waiting waste.

[Week 3] ANALYZE Phase: Root Cause Analysis (EDA in Python)

Objective: Mathematically prove why the picking delays are occurring.

Key Deliverables:

Fishbone Diagram: Mapped Environment, Materials, and Location constraints.

Python EDA & Hypothesis Testing: Disproved initial assumptions about warehouse layout scores and stockouts.

Key Findings:

Slotting Misalignment: The highest-demand items are stored in the slowest-to-pick zone (Zone C).

Category Bottlenecks: 'Apparel' items take the longest to process (97s avg), indicating packaging/handling issues.

Human Variance: Near 0.00 correlation between system metrics and pick times proved that a lack of Standard Operating Procedures (SOPs) is causing massive inconsistency among workers.

[Week 4] IMPROVE & CONTROL Phase: Implementation Strategy

Objective: Propose actionable fixes and establish a monitoring framework.

Key Deliverables:

Improvement Plan: Dynamic warehouse re-slotting (moving high-volume goods to Zone A), Apparel packaging upgrades, and mandatory scanner/SOP training.

Risk Mitigation Matrix: Addressed operational downtime and system desynchronization risks.

KPI Tracking: Set up post-implementation targets for Daily Fulfillment Rate (>95%) and Zone A order volume distribution.

💻 Tech Stack & Methodologies

Methodology: Lean Six Sigma, DMAIC, Root Cause Analysis, Hypothesis Testing.

Data Analysis: Python (Pandas, NumPy)

Data Visualization: Matplotlib, Seaborn, Draw.io (Fishbone/SIPOC diagrams).

Documentation: Microsoft Word, Markdown.

🏆 Conclusion

By transitioning from assumption-based problem solving to strict statistical validation, this project successfully pinpointed the true causes of warehouse delays. The final proposed strategy maximizes daily revenue by ensuring optimal layout slotting and eliminating process variance.

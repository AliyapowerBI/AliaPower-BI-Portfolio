\# IT Service Desk Analytics & Performance Suite

## Project Overview
This comprehensive **Microsoft Power BI** reporting suite delivers end-to-end operational visibility into IT service desk performance. Designed for senior leadership, operations managers, and support teams, the solution spans three core analytical pages: Executive Overview, Team Performance, and SLA vs. CSAT Analysis.

---

## 📊 Dashboard Pages & Key Findings

### 1. Executive Support Overview
- **Executive Pulse KPI Row:** Tracks 8K total tickets, 6K active backlog items, an average CSAT of 2.99, and an SLA breach rate of 0.33%.
- **Monthly Ticket Trend:** Identifies seasonal demand peaks in January (736 tickets) and October (735 tickets) with a low in March (672 tickets).
- **Support Volume by Ticket Type:** Highlights Refund requests (1,752) and Technical issues (1,747) as the primary drivers of customer contact.

### 2. Team Performance: Diagnostic Findings
* **Objective:** Designed to pinpoint exactly which support channel (Chat, Email, Phone, Social Media) and which priority tier (Critical, High, Medium, Low) are driving operational bottlenecks.
* **Key Finding – Channel-Specific Bottlenecks:** Our analysis revealed that performance issues are not uniform; while Chat volume remains balanced, Email and Phone channels show high-pressure spikes in Critical and High-priority queues.
* **Key Finding – Data-Driven Management Action:** The dashboard serves as an automated decision-support tool; it dynamically flags the specific priority queues that are underperforming (e.g., flagging Medium/High for Chat vs. Critical for Email/Phone). This allows management to bypass general reports and take immediate, targeted action on the exact staffing and QA areas that are failing.

### 3. SLA vs. CSAT Analysis: Diagnostic Findings
* **Objective:** Designed to uncover the relationship between Service Level Agreement (SLA) compliance and customer satisfaction (CSAT) to identify operational blind spots.
* **Key Finding – The "Speed vs. Satisfaction" Paradox:** The most significant insight from this analysis was that **speed does not automatically equal happiness.** Our data revealed that CSAT scores for tickets that breached their SLA often mirrored those that met their SLA.
* **Key Finding – Quality over Velocity:** This finding proves that resolution quality and issue thoroughness are far more important to the customer than the speed of delivery. 
* **Key Finding – Management Action:** By uncovering these trends, the dashboard enables leadership to move away from purely speed-based KPIs and toward quality-focused support strategies that prioritize resolution accuracy, ensuring we balance efficiency with true customer satisfaction.
---

## 🛠️ Technical Implementation & DAX
- **Data Modeling & Transformation:** Cleaned, structured, and modeled multi-table support logs using Power Query to establish robust relationships.
- **Custom DAX Measures:** Developed dynamic measures for filtering statuses, tracking backlogs, and evaluating SLA compliance percentages.

---

## 🚀 Skills & Tools Demonstrated
- **Data Visualization & UX/UI:** Multi-page interactive dashboard design optimized for executive reporting and operational triage.
- **Data Analysis & Modeling:** Advanced DAX measures, data modeling, metric definition (CSAT, SLA, Backlog Tracking).
- **Business Intelligence:** Translating complex IT service desk logs into actionable business insights and risk alerts.

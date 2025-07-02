# Contact Management System (CRM Core Structure)

This document outlines the **core data structure**, **automation logic**, and **dashboard views** for managing leads in a B2B SaaS CRM system built for MSME-focused growth.

---

##  Core Fields per Contact

| **Field**              | **Description**                                               |
|------------------------|---------------------------------------------------------------|
| **Name**               | Full name of the lead or contact                              |
| **Company**            | Company or organization name                                  |
| **Designation**        | Role or title at the company                                  |
| **Industry**           | Industry type (e.g., EdTech, Manufacturing, Services)         |
| **Lead Source**        | Origin of lead (e.g., FB Ads, LinkedIn, Email Campaign)       |
| **Lead Stage**         | Current funnel stage (Lead, MQL, SQL, Customer, Evangelist)   |
| **Last Engagement Date** | Last contact or interaction timestamp                      |
| **Lifecycle Owner**    | Assigned department or owner (Sales / Marketing)              |
| **Priority Score**     | Numeric/qualitative score for lead quality or urgency         |
| **Notes & History**    | Contextual updates, past conversations, objections, etc.      |

---

##  CRM Automations

| **Automation**                                  | **Tool / Method**                               |
|--------------------------------------------------|--------------------------------------------------|
| **Auto-tagging based on source**                | Zapier / Make.com integration                   |
| **Lifecycle stage updates based on activity**   | Automated triggers based on form fills, email opens, demo booking, etc. |
| **Follow-up reminders**                         | Notion reminders + Slack integration             |
| **Weekly digest of stuck SQLs**                 | Automated Slack/Email summary for sales team     |

---

##  Dashboard Views (By Role)

### Sales Reps
- **My Leads**
- **Stuck SQLs**
- **Demo Scheduled This Week**

### Growth Manager
- **Weekly Conversions by Source**
- **Drop-off Heatmap**
- **Lead Quality by Channel**

### CEO / Founder
- **CAC:LTV Ratio Dashboard**
- **Revenue by Funnel Stage**
- **Funnel Velocity Tracker**

---

>  All dashboards should update in real-time or via scheduled sync (daily/weekly), ideally embedded into Notion or connected with a BI tool (e.g., Google Data Studio, Retool, Metabase).


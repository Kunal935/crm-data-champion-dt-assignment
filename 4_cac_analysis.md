# Channel Performance Analysis & CAC:LTV Dashboard

This document summarizes marketing channel efficiency, identifies underperformers, and proposes experiments to optimize acquisition costs and lifetime value.

---

## Channel Performance Table

| **Channel**     | **Leads** | **Cost**   | **Conversions** | **CVR**  | **Cost/Conv** |
|------------------|-----------|------------|------------------|----------|----------------|
| **Facebook Ads** | 3,000     | ₹90,000    | 30               | 1%       | ₹3,000         |
| **Email Campaign** | 1,000   | ₹10,000    | 25               | 2.5%     | ₹400           |
| **LinkedIn DMs** | 500       | ₹25,000    | 10               | 2%       | ₹2,500         |

---

## Underperforming Channel

### **Facebook Ads**
- **Issue**: Highest spend, lowest conversion rate, and worst cost per conversion.
  
### Suggested Experiments
1. **Switch Ad Objective**: Optimize for **Lead Form Submission** instead of traffic.
2. **Retargeting**: Focus on **warm audiences** (website visitors, email openers).
3. **A/B Test Creatives**: Use **testimonial-driven videos** instead of static image ads.

---

## CAC:LTV Dashboard Metrics

| **Metric**                         | **Purpose**                                  |
|-----------------------------------|----------------------------------------------|
| Avg **CAC by Channel**            | Compare cost-effectiveness across channels   |
| **LTV by Cohort**                 | Assess customer value over time              |
| **SQL → Customer Conversion Rate**| Funnel efficiency from sales-qualified stage |
| **Cost per SQL**                  | Marketing cost to deliver qualified leads    |
| **Revenue per CAC Spent**         | ROI on each ₹ spent in acquisition           |
| **Evangelist Referrals / Revenue**| Measure referral-driven impact               |

> **Viewed Weekly By**: CEO, Growth Manager, Sales Head

---

Pro Tip: Feed these metrics into a shared Notion or Looker Studio dashboard with auto-refresh using Google Sheets + Zapier APIs for live insights.


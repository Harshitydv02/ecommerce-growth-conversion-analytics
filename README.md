# E-commerce Growth & Conversion Analytics

An end-to-end e-commerce analytics case study using 25,000 simulated customer sessions to identify conversion bottlenecks, customer-value differences, marketing-channel performance, product performance and commercial growth opportunities.

## Live Dashboard

A fully interactive dashboard is available through GitHub Pages.

> Live dashboard link will be added here after deployment.

---

## Business Problem

An e-commerce business may generate substantial website traffic while still losing revenue because customers fail to complete the purchase journey.

This project investigates four management questions:

1. Where are customers dropping out of the conversion funnel?
2. Which customer segments and marketing channels perform best?
3. Which product and commercial factors drive revenue?
4. Where should management prioritize investment to improve growth?

---

## Dataset

The analysis uses 25,000 simulated Indian e-commerce interaction sessions from 2024.

Key dataset metrics:

| Metric | Result |
|---|---:|
| Sessions | 25,000 |
| Unique Customers | 8,442 |
| Purchases | 5,616 |
| Revenue | ₹10.12M |
| Conversion Rate | 22.46% |
| Add-to-Cart Rate | 64.47% |
| Cart Abandonment Rate | 65.15% |
| Average Order Value | ₹1.80K |

---

## Key Business Finding

The biggest growth opportunity in the dataset is not simply generating more traffic.

Although approximately 64.47% of sessions reach the cart stage, around 65.15% of carts are abandoned.

This suggests that management should prioritize improving the post-cart customer experience before relying only on additional traffic acquisition.

---

## Key Insights

### 1. Conversion Funnel

The customer journey shows substantial leakage between Add to Cart and Purchase.

Management should investigate:

- Checkout friction
- Payment experience
- Shipping and fee transparency
- Trust signals
- Cart recovery strategies

### 2. Customer Retention

Returning visitors show stronger commercial performance than new visitors in the project dataset.

This makes:

- CRM
- Remarketing
- Loyalty
- Repeat-purchase campaigns

important potential growth levers.

### 3. Marketing Channels

Channel performance differs across both revenue contribution and conversion efficiency.

Management should evaluate acquisition sources using both scale and conversion quality rather than revenue alone.

### 4. Device Performance

Mobile represents a significant share of customer activity.

Because of its traffic scale, even small improvements in mobile conversion could create meaningful business impact.

### 5. Product Strategy

Product categories play different strategic roles.

Some categories contribute greater revenue value, while others generate stronger conversion or purchase volume.

This suggests category-specific merchandising and promotion strategies.

### 6. Discount Strategy

Higher discounts do not consistently guarantee better commercial performance.

Discount decisions should consider:

- Conversion
- Revenue
- Basket value
- Margin, when available

rather than simply maximizing discount percentage.

---

## Dashboard Structure

### Executive Overview

Provides top-level business performance:

- Total Revenue
- Total Sessions
- Unique Customers
- Total Purchases
- Monthly Revenue
- Product Categories
- Marketing Channels
- Customer Journey

### Customer & Marketing Analytics

Focuses on:

- Revenue per Session
- Revenue per Customer
- Purchasing Customers
- Customer Purchase Penetration
- Returning Revenue Share
- Channel Performance
- Visitor Type
- Device Performance
- Seasonality
- Weekday Activity

### Conversion Funnel Analytics

Focuses on:

- Conversion Rate
- Add-to-Cart Rate
- Cart Abandonment
- Cart-to-Purchase Rate
- Add-to-Cart Sessions
- Abandoned Carts
- Pages Viewed
- Session Duration
- Discount Impact
- Channel Abandonment

### Commercial & Customer Experience

Focuses on:

- Average Order Value
- Units Purchased
- Average Items per Purchase
- Gross Merchandise Value
- Discount Value
- Discount Intensity
- Product Categories
- Payment Methods
- Ratings
- Price Bands

---

## Management Recommendations

Based on the project analysis, management should prioritize:

1. Reducing post-cart conversion leakage.
2. Improving retention and repeat-customer activity.
3. Evaluating high-performing acquisition channels for scalable growth.
4. Prioritizing mobile customer experience.
5. Using category-specific merchandising strategies.
6. Optimizing discount levels against commercial outcomes rather than conversion alone.

---

## Tools & Skills

- PostgreSQL
- SQL
- Power BI
- Data Cleaning
- Data Validation
- Marketing Analytics
- Customer Analytics
- Conversion Funnel Analysis
- E-commerce Analytics
- Data Visualization
- Business Intelligence
- Executive Reporting

---

## Analytics Workflow

```text
Raw E-commerce Dataset
        ↓
Data Quality Validation
        ↓
PostgreSQL Raw Layer
        ↓
Analytics SQL View
        ↓
KPI Development
        ↓
Power BI Analysis
        ↓
Interactive Dashboard
        ↓
Business Recommendations
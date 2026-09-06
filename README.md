<p align="center">
  <img src="images/banner.png" alt="Olist Marketplace Performance Analysis Banner" width="100%">
</p>

<h1 align="center">Olist Marketplace Performance & Customer Experience Analysis</h1>

<p align="center">
An End-to-End <b>Data Analytics Hackathon Project</b> analyzing marketplace performance, customer satisfaction, delivery operations, customer retention, and business growth opportunities.
</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white">

<img src="https://img.shields.io/badge/Google%20Colab-Analysis-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">

<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge">

<img src="https://img.shields.io/badge/Gradient-Data%20Analytics%20Hackathon-success?style=for-the-badge">

</p>

<p align="center">

<a href="https://github.com/nsr-dev-in/olist-marketplace-performance-analysis">
<img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<a href="presentation/">
<img src="https://img.shields.io/badge/Project_Presentation-orange?style=for-the-badge">
</a>

<a href="notebooks/">
<img src="https://img.shields.io/badge/Google_Colab_Analysis-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">
</a>

</p>

---

<h1 align="center">Project Overview</h1>

Olist is a Brazilian e-commerce marketplace connecting thousands of sellers with customers across Brazil.

As a large marketplace, Olist manages multiple interconnected business areas including:

- Customers
- Orders
- Products
- Sellers
- Payments
- Deliveries
- Customer Reviews
- Geographic Locations

This project performs an end-to-end analysis of the Olist marketplace to understand business performance and identify the key factors associated with customer satisfaction.

The analysis transforms multiple raw datasets into meaningful business insights and actionable recommendations.

---

<h1 align="center">Business Problem</h1>

As an e-commerce marketplace grows, managing customer experience and operational performance becomes increasingly complex.

The business needs to understand:

- How is the marketplace performing over time?
- What drives customer satisfaction and dissatisfaction?
- How does delivery performance affect customer reviews?
- Which customers generate the highest revenue?
- How dependent is the platform on high-performing sellers?
- Which geographic regions face operational challenges?
- Where are the biggest opportunities for sustainable growth?

The objective is to convert data into insights that can support better operational and customer experience decisions.

---

<h1 align="center">Objectives</h1>

- Analyze marketplace growth and performance
- Understand monthly order trends
- Analyze revenue trends
- Evaluate average order value
- Analyze delivery performance
- Compare late and on-time deliveries
- Identify factors associated with low customer satisfaction
- Analyze customer retention
- Identify high-value customers
- Analyze seller performance
- Explore geographic revenue concentration
- Identify product category opportunities
- Perform root cause analysis
- Provide actionable business recommendations

---

<h1 align="center">Dataset Information</h1>

The project uses the Brazilian E-Commerce Public Dataset provided by Olist.

| Attribute | Value |
|------------|---------|
| Domain | E-Commerce Marketplace |
| Country | Brazil |
| Orders | Approximately 100,000 |
| Period | September 2016 – October 2018 |
| Dataset Type | Relational E-Commerce Data |
| Number of Major Datasets | 8+ |

### Major Datasets

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Customer Reviews
- Geolocation

---

<h1 align="center">Project Workflow</h1>

<p align="center">
  <img src="images/workflow.png" alt="Project Workflow" width="850">
</p>

```text
DATA UNDERSTANDING
        ↓
DATA CLEANING & PREPARATION
        ↓
DATA INTEGRATION
        ↓
EXPLORATORY DATA ANALYSIS
        ↓
BUSINESS ANALYSIS
        ↓
ROOT CAUSE ANALYSIS
        ↓
KEY INSIGHTS
        ↓
ACTIONABLE RECOMMENDATIONS

<h1 align="center">Tech Stack</h1>
Technology	Usage
Python	Data Analysis
Pandas	Data Cleaning & Manipulation
NumPy	Numerical Analysis
Matplotlib	Data Visualization
Seaborn	Statistical Visualization
Google Colab	Analysis Environment
Git & GitHub	Version Control
Canva	Presentation Design
<h1 align="center">Marketplace Performance Analysis</h1>

The marketplace performance analysis focused on three major metrics:

Monthly Order Trend
Monthly Revenue Trend
Average Order Value
Monthly Order Trend
<p align="center"> <img src="images/monthly_orders.png" alt="Monthly Order Trend" width="900"> </p>
Key Finding

The marketplace experienced significant growth in order volume during the analysis period, particularly throughout 2017 and 2018.

This indicates strong marketplace expansion and increasing customer activity.

Monthly Revenue Trend
<p align="center"> <img src="images/monthly_revenue.png" alt="Monthly Revenue Trend" width="900"> </p>
Key Finding

Revenue increased significantly alongside the growth in order volume.

The marketplace showed strong business expansion as customer activity increased.

Average Order Value Trend
<p align="center"> <img src="images/average_order_value.png" alt="Average Order Value Trend" width="900"> </p>
Key Finding

Average order value remained relatively stable compared with the significant growth observed in total orders and revenue.

This suggests that overall growth was primarily driven by increasing transaction volume.

<h1 align="center">Delivery Performance vs Customer Satisfaction</h1> <p align="center"> <img src="images/delivery_vs_satisfaction.png" alt="Delivery Performance vs Customer Satisfaction" width="850"> </p>

One of the strongest insights from this analysis was the relationship between delivery timing and customer satisfaction.

Delivery Status	Orders	Avg Delivery Days	Avg Review Score
On-Time / Early	88,644	10.88 Days	4.28
Late Delivery	7,826	31.52 Days	2.55
Key Finding

Late deliveries were strongly associated with significantly lower customer satisfaction.

Review Score Difference
1.73 Points

Customers receiving late deliveries gave substantially lower review scores compared with customers receiving their orders on time or early.

Delivery delays were the strongest observed factor associated with low customer satisfaction.

<h1 align="center">Geographic Delivery Analysis</h1> <p align="center"> <img src="images/delivery_by_state.png" alt="Average Delivery Days by Customer State" width="900"> </p>

Delivery performance varies across different Brazilian states.

Business Impact

Some geographic regions experience:

Longer delivery times
Greater logistics challenges
Higher risk of delayed deliveries

This highlights the importance of region-specific logistics strategies.

<h1 align="center">Product Category Analysis</h1> <p align="center"> <img src="images/category_performance.png" alt="Product Category Performance" width="900"> </p>

Product categories were analyzed using:

Revenue
Number of Orders
Product Sales
Average Product Price
Average Freight Cost
Business Value

This analysis helps identify:

High-performing categories
Major revenue drivers
Underperforming categories
Potential growth opportunities
<h1 align="center">Customer Retention Analysis</h1> <p align="center"> <img src="images/customer_retention.png" alt="Customer Retention Analysis" width="850"> </p>
Key Finding

Approximately:

97% of customers were one-time buyers

Only approximately:

3% were repeat customers
Business Impact

The marketplace has a significant opportunity to improve:

Customer Retention
Repeat Purchases
Customer Lifetime Value
Long-Term Revenue
Recommendation
Launch second-purchase campaigns
Introduce loyalty programs
Send personalized recommendations
Create customer reactivation campaigns
<h1 align="center">High-Value Customer Analysis</h1>
Key Finding

Approximately:

25% of High-Value Customers Generated 59.43% of Total Revenue
Business Impact

A relatively small group of customers contributes significantly to overall marketplace revenue.

Losing these customers could have a meaningful impact on business performance.

Recommendation
Create a VIP customer program
Provide personalized offers
Offer exclusive benefits
Prioritize high-value customer retention
<h1 align="center">Seller Performance Analysis</h1> <p align="center"> <img src="images/seller_performance.png" alt="Seller Performance Analysis" width="900"> </p>
Key Finding

Approximately:

25% of High-Value Sellers Generated 86.58% of Seller Revenue
Business Impact

The marketplace is highly dependent on a relatively small group of high-performing sellers.

Recommendation
Retain and support high-value sellers
Develop medium-value sellers
Improve seller performance programs
Reduce dependency on a small group of sellers
<h1 align="center">Geographic Revenue Analysis</h1> <p align="center"> <img src="images/geographic_analysis.png" alt="Geographic Revenue Analysis" width="900"> </p>
Key Finding
São Paulo Generated Approximately 37.41% of Customer Revenue
Business Impact

São Paulo represents the largest market for the marketplace.

However, heavy dependency on a single geographic market can create concentration risk.

Recommendation
Expand into high-potential states
Improve logistics outside São Paulo
Increase seller availability in growth markets
<h1 align="center">Root Cause Analysis</h1> <p align="center"> <img src="images/root_cause_analysis.png" alt="Root Cause Analysis" width="850"> </p>
Root Cause Framework
GEOGRAPHIC CHALLENGES
        ↓
LOGISTICS & DELIVERY CHALLENGES
        ↓
LATE DELIVERIES
        ↓
LOW CUSTOMER SATISFACTION
        ↓
LOWER CUSTOMER RETENTION

The analysis explored multiple business and operational factors associated with low customer satisfaction.

Major Factors Identified
Geographic Challenges
Logistics Performance
Delivery Delays
Seller Operations
Product Category Differences
Root Cause Conclusion

Delivery reliability stands out as the strongest observed factor associated with customer satisfaction.

<h1 align="center">Key Business Insights</h1>
1. Customer Retention Problem

Finding

97% of customers are one-time buyers.

Business Impact

The company has a major opportunity to increase Customer Lifetime Value by converting one-time buyers into repeat customers.

2. Delivery Delays Reduce Customer Satisfaction

Finding

Late deliveries have an average review score of 2.55, compared with 4.28 for on-time or early deliveries.

Business Impact

Poor delivery performance is strongly associated with lower customer satisfaction and may negatively affect customer retention.

3. High-Value Customers Are Critical

Finding

25% of high-value customers generate approximately 59.43% of total revenue.

Business Impact

Losing high-value customers could significantly affect overall revenue.

4. Geographic Revenue Concentration

Finding

São Paulo generates approximately 37.41% of customer revenue.

Business Impact

Heavy dependency on one geographic market creates concentration risk.

5. Seller Revenue Concentration

Finding

25% of high-value sellers generate approximately 86.58% of total seller revenue.

Business Impact

The platform depends heavily on a relatively small group of sellers.

<h1 align="center">Actionable Recommendations</h1>
Improve Delivery Performance
Implement delivery delay monitoring
Create early-warning systems
Improve logistics in high-delay states
Monitor seller dispatch performance
Improve Customer Retention
Launch loyalty programs
Encourage second purchases
Create personalized recommendations
Run customer reactivation campaigns
Protect High-Value Customers
Develop VIP programs
Provide personalized offers
Offer exclusive benefits
Prioritize retention strategies
Improve Seller Performance
Monitor seller performance
Support underperforming sellers
Develop medium-value sellers
Retain high-performing sellers
Expand Strategically
Identify high-potential states
Improve regional logistics
Increase marketplace coverage
Reduce geographic concentration risk
<h1 align="center">Final Business Strategy</h1>
ACQUIRE
   ↓
DELIVER
   ↓
SATISFY
   ↓
RETAIN
   ↓
OPTIMIZE
   ↓
EXPAND

Reliable Delivery → Better Customer Experience → Higher Satisfaction → Improved Retention → Sustainable Growth

<h1 align="center">Repository Structure</h1>
olist-marketplace-performance-analysis/
│
├── datasets/
│   ├── customers
│   ├── orders
│   ├── products
│   ├── sellers
│   ├── payments
│   └── reviews
│
├── images/
│   ├── banner.png
│   ├── workflow.png
│   ├── monthly_orders.png
│   ├── monthly_revenue.png
│   ├── average_order_value.png
│   ├── delivery_vs_satisfaction.png
│   ├── delivery_by_state.png
│   ├── category_performance.png
│   ├── customer_retention.png
│   ├── seller_performance.png
│   ├── geographic_analysis.png
│   └── root_cause_analysis.png
│
├── notebooks/
│   └── Olist_Marketplace_Analysis.ipynb
│
├── presentation/
│   └── Olist_Hackathon_Presentation.pdf
│
├── reports/
│   └── Project_Report.pdf
│
└── README.md
<h1 align="center">Skills Demonstrated</h1>
Data Understanding
Data Cleaning
Data Integration
Exploratory Data Analysis
Business Analysis
Customer Segmentation
Customer Retention Analysis
Delivery Performance Analysis
Root Cause Analysis
Data Visualization
Business Storytelling
Actionable Recommendations
<h1 align="center">Project Outcomes</h1>

This project successfully transformed raw e-commerce data into actionable business insights.

The analysis helped identify:

Marketplace growth patterns
Revenue trends
Delivery performance challenges
Customer satisfaction drivers
Customer retention opportunities
High-value customers
Seller revenue concentration
Geographic concentration
Root causes associated with low satisfaction
<h1 align="center">Final Conclusion</h1>

The biggest opportunity for sustainable marketplace growth is not only acquiring new customers but improving the experience that encourages them to return.

The company should focus on:

Increasing repeat purchases
Reducing delivery delays
Protecting high-value customers
Supporting high-value and medium-value sellers
Improving logistics in challenging regions
Expanding strategically beyond São Paulo
Final Strategy
ACQUIRE → DELIVER → SATISFY → RETAIN → OPTIMIZE → EXPAND
<h1 align="center">Contributors</h1>
Nitin Singh

Aspiring Data Analyst passionate about solving real-world business problems using data analytics and business intelligence.

<a href="https://www.linkedin.com/in/nsr2k06/"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"> </a> <a href="https://github.com/nsr-dev-in"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </a>
Pratham Meena

Data Analytics Hackathon Contributor.

<h1 align="center">Hackathon</h1>

This project was developed as part of the:

Data Analytics Hackathon
Conducted by Gradient
<h1 align="center">Thank You</h1>

Thank you for visiting our repository.

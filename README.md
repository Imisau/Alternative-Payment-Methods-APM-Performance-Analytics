# Alternative-Payment-Methods-APM-Performance-Analytics
![](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_Thumbnail.png)
### Emerging Markets | Power BI & Excel | Strategy & Execution

# 🚀 Project Context
This project simulates the work of an **APM Analyst** supporting the **Head of APMs** with data-driven insights to expand, optimize, and scale Alternative Payment Methods across emerging markets.
Using:
-	A **10,000-transaction Excel dataset**
-	A **5-page Power BI executive dashboard**
I evaluated **APM performance, adoption, conversion efficiency, and failure patterns** across multiple countries and payment types, translating analytics into **clear strategic actions.**

________________________________________
# 🛠 Tools & Methods
-	Excel: Descriptive statistics, validation, aggregation
-	Power BI: 5-page executive analytics dashboard
-	Analytics Techniques: Funnel analysis, failure diagnostics, trend analysis

________________________________________
# 🎯 Business Objectives (Aligned to dLocal Role)
-	Identify high-performing and underperforming APMs
-	Diagnose conversion leakage across authorization → completion
-	Support APM launch, optimization, and prioritization decisions
-	Provide stakeholder-ready insights for product, commercial, and operations teams


________________________________________
# 📂 Data Overview (Excel Analysis)
Dataset Size: 10,000 transactions
Markets Covered: Emerging markets (Africa, LATAM, Asia)
### Payment Methods:
-	Card
-	Mobile Wallet
-	USSD
-	Bank Transfer
-	QR Payments
### Core Fields
-	Transaction Attempted
-	Authorized (Yes/No)
-	Completed (Yes/No)
-	Transaction Amount (USD)
-	Failure Reason
•	Country
•	Payment Method
•	Transaction Date
________________________________________

# 🔢 Overall Performance (Excel-Derived)

|Metric                         |Value
:------------------------------:|:---------------------
Total Transactions	            |  10,000
Authorization Rate	            |  78.3%
Completion Rate	                |  71.5%
Average Transaction Value	      |  $152.09

### Insight:
A ~7% drop between authorization and completion signals post-authorization friction, a critical APM optimization opportunity.
________________________________________

# 💳 Performance by Payment Method
|Payment Method	      |Transactions	    |Auth Rate	    |Completion Rate	    |Avg Value ($)
:--------------------:|:---------------:|:-------------:|:-------------------:|:--------------
Bank Transfer	        |  2,056	        |    76.6%	    |      72.4%	        |        152.89
Card	                |  2,038	        |    78.0%	    |      71.8%	        |        153.78
Mobile Wallet	        |  1,998	        |    79.7%	    |      71.0%	        |        149.26
QR Payments	          |  2,000	        |    78.2%	    |      71.4%	        |        152.30
USSD	                |  1,908	        |    79.4%	    |      70.6%	        |        152.16

# APM Insight:

-	USSD & Mobile Wallets show strong authorization → adoption signal
-	Completion drop-off is consistent across APMs → systemic UX or timeout issue, not method-specific
________________________________________

# 🔹 Page 1: Executive APM Funnel Overview
![](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_EMP3%20(2).png)

**Insight:** Conversion Loss Is Concentrated After Authorization

## What the analytics reveal:

-	While nearly 8 in 10 transactions authorize successfully, only 7 in 10 complete
-	The authorization layer is not the bottleneck
-	Losses occur after customers commit funds

## Interpretation for APM Strategy:

This pattern signals operational or UX friction (timeouts, redirects, confirmation failures) rather than payment method rejection.  

This shows that;
The APM stack is trusted enough to authorize payments, but there's a lost material revenue after customer commitment. Improving post-authorization flows could recover ~900 transactions at current volume.
________________________________________

# 🔹 Page 2: Country & Market-Level Performance
![]( https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_EMP1.png)

 **Insight:** APM Readiness Varies Significantly by Market

## What the analytics reveal:
-	Some countries combine high transaction volume with strong completion
-	Others show healthy authorization but weak completion
-	This divergence is country-specific, not APM-specific

## Interpretation for Market Expansion:
-	High-auth / low-completion markets are not failing markets
-	They represent execution and infrastructure gaps

This also shows that;
Markets with strong authorization but weak completion should not be deprioritized. They are prime candidates for localized flow optimization, partner tuning, and reliability improvements rather than market exit.
________________________________________

# 🔹 Page 3: Payment Method Adoption & Conversion
![](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_EMP2.png)

**Insight:** USSD and Mobile Wallets Are Strategic, Not Secondary

## What the analytics reveal:
-	USSD and Mobile Wallets achieve some of the highest authorization rates
-	Completion rates are slightly lower but consistent across all APMs
-	Average transaction values are stable across methods

## Interpretation for APM Portfolio Decisions:
-	Performance differences are not driven by payment method trust
-	The issue is shared platform friction

This also shows that;
USSD and Mobile Wallets are performing as well as Cards in authorization and value. Any conversion loss is systemic, meaning optimization investments will lift all APMs simultaneously.
________________________________________

# 🔹 Page 4: Failure Reason Analysis
![](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_EMP4.png)

**Insight:** Failures Are Systemic, Not Method-Specific

## What the analytics reveal:
-	Failures cluster around:

 	 o	Technical errors

 	 o	Timeouts

 	 o	Incomplete confirmations

-	No single APM dominates failure volume

## Interpretation for Execution & Partnerships:
-	This points to flow orchestration, integration reliability, or partner response timing
-	Not a customer behavior or funding issue

This also shows;
Failure patterns indicate platform-level execution risk. Coordinated fixes with Product, Engineering, and local partners will have a compounding impact across all payment methods.
________________________________________
# 🔹 Page 5: Time & Trend Performance
![](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/AMP_EMP5.png)

**Insight:** Conversion Leakage Is Persistent, Not Seasonal

## What the analytics reveal:
-	Transaction volumes fluctuate normally
-	Authorization and completion rates remain structurally stable
-	No self-correcting trend over time

## Interpretation for APM Governance:
-	This is not a temporary issue
-	It represents a structural conversion ceiling

This tells that;
Without intervention, current APM conversion rates will remain flat. Any uplift will require deliberate product and flow optimization rather than waiting for organic improvement.
________________________________________
# 💡 Consolidated Strategic Insights

### 1️⃣ Post-Authorization Optimization = Fastest Revenue Win
-	Avg transaction ≈ $152
-	A 2% improvement in completion represents significant recovered revenue at scale

### 2️⃣ APMs Are Not the Problem — Execution Is
-	Similar patterns across Cards, USSD, Wallets, QR
-	Points to platform, UX, or orchestration issues

# 3️⃣ Emerging Markets Are Ready, Not Risky
-	Strong authorization confirms customer trust
-	Completion gaps indicate fixable infrastructure challenges
________________________________________

Interactwith dataset [Here](https://github.com/Imisau/Alternative-Payment-Methods-APM-Performance-Analytics/blob/main/APM_Emerging_Market_Performance_Dataset.xlsx) 

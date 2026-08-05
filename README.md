# 🏠 Housing Market Analysis: Trends, Pricing & Sales Performance Dashboard

An interactive **Power BI** dashboard analyzing the Danish housing market — covering pricing trends, regional performance, sales-type behavior, and property-type comparisons — built to support data-driven decisions for buyers, sellers, investors, and analysts.

---

## 📌 Project Objective

The objective of this project is to analyze the Danish housing market using historical sales data to uncover trends in pricing, sales volume, and regional performance. The dashboard helps stakeholders understand how factors such as **region, property type, sales type, and time period** influence housing prices and sales activity — enabling data-driven decisions in property investment, pricing strategy, and market forecasting.

### Sub-Objectives
- Track core market KPIs (units sold, 12-month sales value, offer vs. purchase price).
- Compare regional performance across Zealand, Jutland, Fyn & Islands, and Bornholm.
- Evaluate YoY trends across sales types (auction, regular, family, other).
- Identify key drivers of purchase price using influencer analysis.
- Compare pricing and yield across property types (Farm, Apartment, Townhouse, Villa, Summerhouse).
- Enable interactive filtering by Area, City, Sales Type, and Region.

---

## 🗂️ Dashboard Pages

| Page | Description |
|------|--------------|
| **1. House Market Overview** | High-level KPIs — units sold, 12-month sales, median price change by region, offer vs. purchase price correlation, YoY sales growth by sales type. |
| **2. Sales Performance** | Regional sales breakdown, key influencer analysis on purchase price, offer-to-SQM ratio by sales type, average price per SQM by region. |
| **3. House Type Analysis** | Filterable view (Area/City/Sales Type/Region) comparing offer/purchase price, inflation/interest/yield, and SQM/SQM price across property types. |

---

## 💡 Key Insights

### 1. Market Overview
- Total 12-month sales reached **13bn**, with **77 units sold** in the latest year/quarter.
- **Bornholm** posted the highest median price increase (~5%) among all regions, while **Zealand** showed the smallest growth.
- **Offer price vs. purchase price** shows a near-perfect positive correlation — buyers consistently pay close to asking price, indicating a low-negotiation, stable market.
- **YoY sales growth by sales type** is sharply divided:
  - Auction sales: **+29%** (only positive growth)
  - Regular & other sales: **-21%** each
  - Family sales: **-75%** — the steepest decline, suggesting a major pullback in intra-family transfers.

### 2. Sales Performance
- **Zealand dominates volume** with 95bn in total sales — over 5x Jutland (81bn), the next highest region.
- **Bornholm** contributes just 1bn in total sales, the smallest share, implying its price growth is driven by low-volume/high-value outliers rather than broad market strength.
- **Buyer age is a major price driver**: buyers aged **1–16** and **69+** are linked to the highest average purchase prices (+443.2K and +437.5K respectively) — well above mid-age buyers.
- **Offer-to-SQM ratio** is highest for regular sales (14.9K) and lowest for auction sales (11.1K), consistent with auctions typically involving below-market pricing.
- **Zealand leads price per SQM** at 20.85K (35.6% share) — nearly double Bornholm's 10.6K (18.1%), confirming it as the premium region on a per-unit basis.

### 3. Property Type Analysis
- **Farms** have the highest average price (2.7M) and largest size (196 SQM) but the **lowest price per SQM (13.83K)** — priced on total land/size rather than per-unit premium.
- **Apartments** have the smallest average size (87 SQM) but the **highest price per SQM (28.69K)** by far — reflecting urban density premiums.
- **Offer and purchase prices are nearly identical across all property types**, reinforcing minimal negotiation market-wide.
- **Yield and SQM price are inversely related**: Farms show the highest yield (4.6%) despite the lowest SQM price; Apartments show lower yield (3.9%) despite the highest SQM price.
- **Inflation and interest rates are nearly uniform (~1.4–2.1%) across property types** — meaning property type and location, not macroeconomic conditions, drive most of the price variation.

### 🔑 Overall Takeaway
> The Danish housing market shows clear **regional and property-type stratification**: Zealand and apartments command premium per-SQM pricing driven by density/location, while farms and Bornholm rely on scale or emerging demand rather than per-unit value. The market is largely negotiation-free (offer ≈ purchase price everywhere), and sales-type trends signal a shift away from family/private transfers toward auction-driven transactions — a trend worth monitoring as a possible signal of rising distressed sales or changing wealth-transfer behavior.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** — data modeling, DAX measures, and dashboard design
- **Key Influencers visual** — for driver/correlation analysis
- Data covers historical housing sales (1992 onward) across Danish regions







## 📬 Contact
Feel free to reach out with feedback or suggestions for improving this analysis.

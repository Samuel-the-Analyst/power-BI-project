# Data Structure
The project uses a relational sales database consisting of three tables: **customers**, **products**, and **orders**.
These tables are connected using unique identifiers to support accurate sales and customer analysis.

<p align="center">
  <img src="s1.jpg" alt="Table relationship diagram" width="900">
</p>

## Table Descriptions
1. **Customers** - This table contains customer-level information and is used to analyze customer demographics and behavior.
2. **Products** - This table stores product-level details and supports product performance and pricing analysis.
3. **Orders** - This is the fact table containing transactional sales data and links customers to products.

# Executive Summary
From **Q1 2019** to **Q2 2022**, the business generated **$45,174** in **total revenue** from **1,000 orders**, with an **average order size** of **47** units, indicating consistently strong basket sizes across transactions. In the pre-pandemic period (2019), **total sales** reached approximately $12.2K, providing a baseline for performance. During the pandemic period (2020–2021), revenue demonstrated resilience and growth, remaining relatively steady at $12.1K in 2020 and peaking at approximately $13.8K in 2021, representing an estimated **13%** growth from 2019 to 2021. This suggests the business was able to sustain and even expand sales despite broader market disruptions.
For 2022, available data covers only **Q1–Q2**, with recorded sales of about **$7.1K**. When viewed in the context of prior years, this half-year performance represents over **50% of 2021’s full-year revenue**, suggesting a **strong early-year sales trajectory**. While full-year conclusions cannot yet be drawn, the first two quarters indicate continued post-pandemic momentum, with revenue generation tracking ahead of historical mid-year benchmarks.

<p align="center">
  <img src="s3.jpg" alt="Sales KPIs and yearly revenue breakdown" width="900">
</p>

# Insights Deep Dive
## Sales performance 
- Sales exhibit recurring seasonal volatility, indicating demand sensitivity across quarters. Quarterly sales fluctuate consistently across years, with stronger performance typically observed in **Q1** and **Q4**. For example, **Q4 2021** recorded **$4,169**, the highest quarterly sales in the dataset, while Q2 periods tend to underperform. This pattern suggests that sales are influenced by seasonal consumption habits, promotional cycles, or distribution capacity rather than random variation.
- The 2020 sales decline reflects a short-term operational and demand disruption rather than structural weakness. Total sales dipped marginally to **$12,123**, only **$76** lower than 2019, despite quarter-level declines in **Q2 and Q3**. The relatively small annual decline indicates that lost sales were largely offset later in the year, pointing to delayed rather than permanently lost demand.
- 2021 performance highlights improved consistency and stronger revenue capture per quarter. Sales increased to **$13,777**, with positive YoY growth in three out of four quarters. Notably, **Q3 2021 (+$1,161 YoY)** and **Q4 2021 (+$788 YoY)** suggest improved execution, potentially through better inventory availability, pricing discipline, or customer retention, resulting in higher and more stable revenue capture.
- Early 2022 sales indicate continued momentum when benchmarked against historical quarterly performance. Although 2022 includes only **Q1–Q2** data, **Q2 2022** sales **($2,940)** exceeded **Q2 2021 ($2,776)** and remain well above pre-pandemic Q2 levels. When evaluated against historical quarterly averages, early 2022 performance suggests the business was on track to maintain or exceed prior-year run rates.
- Overall, sales performance is driven by a combination of demand recovery, seasonality, and operational stability. Across **Q1 2019–Q2 2022**, total revenue reached **$45,174 from 1,000 orders**, with an **average order value of $47**. While external shocks affected short-term performance, the long-term sales pattern suggests that underlying demand for the product remained strong and capable of rebounding when operational conditions stabilized.

<p align="center">
  <img src="s7.jpg" alt="Sales performance YoY" width="900">
</p>

# Product performance
- Across the full period (Q1 2019–Q2 2022), all four coffee types, including Excelsa, Liberica, Arabica, and Robusta, contribute meaningfully to total revenue. Excelsa leads overall sales (~$12.3K), followed closely by Liberica (~$12.1K) and Arabica (~$11.8K), while Robusta (~$9.0K) trails but still represents a substantial revenue stream. This balanced distribution suggests a diversified product portfolio rather than reliance on a single best-seller.
- Total revenue for Dark roasted coffee stands at approximately $13.2K from 333 orders, yielding an AOV of $40, the lowest among the roast types. Sales volume remains consistent across years, indicating stable demand, but the lower AOV suggests pricing sensitivity or smaller basket sizes. This means that Dark roast is a dependable volume driver rather than a premium revenue contributor.
- The Light roast segment generated approximately $17.4K in revenue from 333 orders, resulting in the highest AOV at $53. Despite having the same order volume, Light roast consistently delivers higher revenue per transaction, indicating a more premium positioning or stronger upsell potential. This suggests Light roast is a key margin-driving segment. Medium roast recorded approximately $14.6K in revenue from 334 orders, with an AOV of $45. This positions it as a stable, core offering within the portfolio as well.
- While all coffee types show recovery post-2020, Light and Medium roasts exhibit stronger upward momentum in later periods, particularly from 2021 onward, whereas Dark roast maintains flatter growth. This divergence suggests that consumer preferences may be gradually shifting toward higher-value or specialty offerings, while traditional products continue to provide baseline stability.
- During periods of sales fluctuation (notably mid-2020), declines are not isolated to a single coffee type, indicating that external factors affected demand broadly. However, the presence of both premium (Light) and volume-driven (Dark) products helped smooth overall revenue volatility, reinforcing the value of a diversified product mix.









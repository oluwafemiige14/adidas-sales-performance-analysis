# Adidas Sales Performance Analysis

Excel dashboard, leadership deck and recommendations built from **9,648 Adidas sales records (January 2020 to December 2021)**. Capstone project from the BeTechified 4-week Data Analyst training.

![Excel dashboard](assets/12_dashboard_excel_main.png)

## At a glance

| Total sales | Operating profit | Operating margin | Units sold |
|:--|:--|:--|:--|
| $899.9M | $332.1M | 36.9% | 2.48M |

## Business problem

Adidas has strong overall sales, but sales alone do not show where profit is made or where to invest. Which products, retailers, regions, channels and months deserve attention, and what should leaders do next?

## Approach

1. Restructured the raw file into one clean table and standardised 13 fields
2. Ran quality checks before any analysis
3. Built pivot tables for product, retailer, region, sales method, state and month
4. Combined them into a one-page Excel dashboard with KPI cards, charts and slicers
5. Turned the findings into a 10-slide leadership deck and a recommendations report

![Pivot dashboard with slicers](assets/13_dashboard_excel_slicer_version.png)

## Key findings

| Area | Finding |
|:--|:--|
| Product | Men's Street Footwear leads: $208.8M in sales, 39.7% margin. Women's Athletic Footwear sells least ($106.6M) but has a healthy 36.6% margin |
| Retailer | West Gear ($243.0M), Foot Locker ($220.1M) and Sports Direct ($182.5M) deliver about 72% of sales. Sports Direct has the best margin (40.7%) |
| Region | West sells the most ($269.9M) but has the lowest margin (33.2%). South has the best margin (42.3%) |
| Sales method | In-store leads ($356.6M, 35.8% margin). Online is smallest ($247.7M) but earns the best margin (39.0%) |
| Season | July ($95.5M), August ($92.2M) and December ($85.8M) peak. March is the low ($56.8M) |
| States | Hawaii and Washington show the thinnest margins (about 26% and 27%) |

![Region margin](assets/19_chart_region_margin.png)
![Channel sales and margin](assets/17_chart_channel_sales_vs_margin.png)
![Monthly trend](assets/20_chart_adidas_monthly_trend.png)

## Limitations

- The dataset has no sales targets, so results cannot be compared with goals
- There is no cost, discount or staffing data, so I cannot explain why margins differ
- Operating margin does not include marketing or delivery costs, so online may look better than it is
- 2020 has 1,202 records against 8,446 in 2021, so the two years may not be covered equally
- Quality checks found 4 rows with zero or negative units and 3,886 rows where price times units does not match recorded sales
- The file has no currency label; figures are reported in $, as in the project brief

![Data quality checks](assets/14_data_quality_checks.png)

## How I handled them

- Compared parts of the business with each other instead of against targets
- Flagged and documented every data issue instead of deleting rows silently, and used recorded totals for the main analysis
- Treated 2021 being about four times 2020 ($717.8M against $182.1M) as a coverage question, not as growth
- Recommended growing online step by step while tracking its costs
- Treated state-level and seasonal results as planning signals, because two years and smaller states give less certainty

## Outcome and recommendations

1. **Back the winners:** prioritise stock, marketing and shelf space for Men's Street Footwear and Women's Apparel
2. **Grow online carefully:** shift marketing toward the higher-margin channel while keeping in-store as the volume driver
3. **Fix the West:** investigate discounts and costs to lift its margin
4. **Plan around peaks:** build stock before July and December, and test promotions in March
5. **Focus partner effort:** deepen joint planning with West Gear and Foot Locker, and grow Sports Direct

![12-month plan](assets/10_slide_roadmap.png)

## Files

- `assets/`: dashboard and chart images
- `docs/Adidas_Sales_Performance_Review.pptx`: the 10-slide leadership deck

## Data

The raw dataset was provided for the BeTechified capstone and is **not included** in this repository. Add the workbook only if the data's licence allows redistribution.

## Tools

Excel (pivot tables, slicers, charts, formulas), PowerPoint, Word

## About me

I am **Femi Ige**, a data analyst who turns messy business and research data into Excel dashboards, clean datasets and plain-English recommendations. I trained through the 4-week Data Analyst programme at BeTechified.

- Email: eduwritescholars@outlook.com
- LinkedIn: [add your LinkedIn link]
- Upwork: [add your Upwork link]
- Fiverr: [add your Fiverr link]

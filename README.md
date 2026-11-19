# Amazon Sales Analysis in Tableau

A two-page Tableau dashboard explores where sales generated profit, how online and offline revenue compare, and when orders were placed and shipped. The supplied sales dataset covers 100 distinct orders across 76 countries from February 2010 through June 2017. The findings below describe this dataset.

## KPI scorecard

The source contains 1,710 populated rows. Removing 1,610 exact duplicate rows leaves one record per order ID. The dashboard screenshots reflect the repeated rows. The stakeholder results use the 100 unique orders.

| KPI | One row per order | All populated rows | Definition |
| --- | --- | --- | --- |
| Profit | $44,168,198.40 | $797,100,847.02 | Sum of revenue less cost |
| Revenue | $137,348,768.31 | $2,409,672,519.09 | Sum of Total Revenue |
| Average days to ship | 23.36 | 24.31 | Mean calendar days from order to shipment |
| Units sold | 512,871 | 9,092,169 | Sum of Units Sold |

## Profit by region

Europe leads Sub-Saharan Africa by $177,712.61 using the supplied region labels. The rankings depend on a geography issue. The source assigns Angola and Senegal to a region named India. Reassigning those two orders to Sub-Saharan Africa would put it first at $12.18 million.

| Region as recorded | Profit | Share of profit |
| --- | --- | --- |
| Europe | $11,082,938.63 | 25.1% |
| Sub-Saharan Africa | $10,905,226.02 | 24.7% |
| Asia | $6,113,845.87 | 13.8% |
| Middle East and North Africa | $5,761,191.86 | 13.0% |
| Australia and Oceania | $4,722,160.03 | 10.7% |
| Central America and the Caribbean | $2,846,907.85 | 6.4% |
| North America | $1,457,942.76 | 3.3% |
| India | $1,277,985.38 | 2.9% |

## Profit by country

Djibouti leads with $2.43 million, followed by Myanmar and Pakistan.

| Top five countries | Profit | Share of profit |
| --- | --- | --- |
| Djibouti | $2,425,317.87 | 5.5% |
| Myanmar | $1,802,771.70 | 4.1% |
| Pakistan | $1,719,922.04 | 3.9% |
| Samoa | $1,678,540.98 | 3.8% |
| Honduras | $1,609,947.52 | 3.6% |

<details>
<summary>Full ranking of all 76 countries</summary>


| Country | Profit | Share of profit |
| --- | --- | --- |
| Djibouti | $2,425,317.87 | 5.5% |
| Myanmar | $1,802,771.70 | 4.1% |
| Pakistan | $1,719,922.04 | 3.9% |
| Samoa | $1,678,540.98 | 3.8% |
| Honduras | $1,609,947.52 | 3.6% |
| Iceland | $1,541,705.29 | 3.5% |
| Azerbaijan | $1,512,926.83 | 3.4% |
| Switzerland | $1,512,729.45 | 3.4% |
| Mexico | $1,457,942.76 | 3.3% |
| Rwanda | $1,417,493.49 | 3.2% |
| The Gambia | $1,385,883.27 | 3.1% |
| Romania | $1,375,311.70 | 3.1% |
| Turkmenistan | $1,267,258.40 | 2.9% |
| Sri Lanka | $1,208,744.24 | 2.7% |
| Iran | $1,128,242.43 | 2.6% |
| Lithuania | $1,046,233.75 | 2.4% |
| Tuvalu | $951,410.50 | 2.2% |
| Mozambique | $889,472.91 | 2.0% |
| Brunei | $846,885.00 | 1.9% |
| Monaco | $825,738.04 | 1.9% |
| Norway | $794,398.84 | 1.8% |
| Cameroon | $781,681.30 | 1.8% |
| Spain | $747,939.49 | 1.7% |
| Fiji | $727,423.20 | 1.6% |
| Angola | $693,911.51 | 1.6% |
| Sierra Leone | $649,879.30 | 1.5% |
| Bulgaria | $626,223.87 | 1.4% |
| Bangladesh | $606,834.72 | 1.4% |
| Senegal | $584,073.87 | 1.3% |
| Lebanon | $579,000.96 | 1.3% |
| Australia | $576,605.12 | 1.3% |
| Macedonia | $575,916.48 | 1.3% |
| Madagascar | $539,196.48 | 1.2% |
| Burkina Faso | $510,216.66 | 1.2% |
| Austria | $495,007.89 | 1.1% |
| San Marino | $455,335.00 | 1.0% |
| Libya | $450,780.97 | 1.0% |
| Kenya | $407,630.41 | 0.9% |
| Belize | $403,773.12 | 0.9% |
| Saudi Arabia | $359,941.17 | 0.8% |
| East Timor | $337,937.60 | 0.8% |
| France | $315,574.05 | 0.7% |
| Cape Verde | $306,097.92 | 0.7% |
| Haiti | $296,448.35 | 0.7% |
| Solomon Islands | $285,087.64 | 0.6% |
| Cote d'Ivoire | $255,718.08 | 0.6% |
| Grenada | $248,406.36 | 0.6% |
| Laos | $235,601.16 | 0.5% |
| Zambia | $225,246.90 | 0.5% |
| Russia | $224,598.75 | 0.5% |
| Gabon | $216,919.36 | 0.5% |
| Sao Tome and Principe | $176,193.13 | 0.4% |
| Albania | $166,635.36 | 0.4% |
| Costa Rica | $160,609.54 | 0.4% |
| Mauritania | $159,832.50 | 0.4% |
| Republic of the Congo | $152,114.20 | 0.3% |
| Federated States of Micronesia | $146,875.14 | 0.3% |
| Nicaragua | $127,722.96 | 0.3% |
| Moldova | $127,054.20 | 0.3% |
| Mongolia | $122,819.06 | 0.3% |
| Portugal | $122,029.78 | 0.3% |
| Democratic Republic of the Congo | $89,904.06 | 0.2% |
| Comoros | $85,223.58 | 0.2% |
| Mali | $79,245.74 | 0.2% |
| Niger | $75,555.90 | 0.2% |
| Slovenia | $72,975.60 | 0.2% |
| South Sudan | $53,252.50 | 0.1% |
| United Kingdom | $46,735.86 | 0.1% |
| Lesotho | $23,150.46 | 0.1% |
| Malaysia | $15,103.47 | 0.0% |
| Kiribati | $13,009.18 | 0.0% |
| Slovakia | $10,795.23 | 0.0% |
| Syria | $9,119.44 | 0.0% |
| Kyrgyzstan | $7,828.12 | 0.0% |
| New Zealand | $5,270.67 | 0.0% |
| Kuwait | $1,258.02 | 0.0% |

</details>

## Revenue by sales channel

Offline sales generated $20.84 million more revenue than online sales.

| Sales channel | Revenue | Share of revenue |
| --- | --- | --- |
| Offline | $79,094,809.20 | 57.6% |
| Online | $58,253,959.11 | 42.4% |

## Orders placed and shipped by year

Orders are grouped by order date for demand and by ship date for fulfillment. An order placed in December can ship the following year. Both measures peaked in 2012. The 2017 data ends in June.

| Year | Orders placed | Orders shipped |
| --- | --- | --- |
| 2010 | 10 | 8 |
| 2011 | 12 | 13 |
| 2012 | 22 | 23 |
| 2013 | 12 | 11 |
| 2014 | 15 | 16 |
| 2015 | 11 | 11 |
| 2016 | 10 | 10 |
| 2017 | 8 | 8 |
| Total | 100 | 100 |

## Orders by priority

High priority was the largest group. High and critical orders together accounted for 52 of the 100 orders.

| Priority | Orders | Share |
| --- | --- | --- |
| Critical | 22 | 22% |
| High | 30 | 30% |
| Medium | 21 | 21% |
| Low | 27 | 27% |

## Reproducing the results in Tableau

1. Import the supplied CSV as UTF-16 text with a tab delimiter. Parse Order Date and Ship Date as day/month/two-digit year. Treat Order ID as an identifier.
2. Remove blank rows and exact duplicates across all source columns before aggregation. Confirm that the resulting 100 rows contain 100 distinct order IDs. A distinct count corrects order counts alone. The financial measures also require the deduplicated data.
3. Calculate profit with `SUM([Total Revenue]) - SUM([Total Cost])` and average days to ship with `AVG(DATEDIFF('day', [Order Date], [Ship Date]))`. Use `SUM([Total Revenue])` for revenue and `SUM([Units Sold])` for volume.
4. On the homepage, group profit by Region for the bar chart and by Country for the map. On the executive page, group revenue by Sales Channel and use `COUNTD([Order ID])` for orders by priority, order year and ship year.

## Reconciling the dashboard screenshots

| Screenshot element | What the screenshot shows | Measure for the stakeholder question |
| --- | --- | --- |
| Total Revenue card | $1,612.6M. Its tooltip identifies Total Cost. | Sum of Total Revenue gives $137.35M across unique orders. |
| Sales Channel Analysis | Offline and online revenue sum to $2,409.7M across repeated rows. | Use the same clean data and revenue field for both the channel chart and the revenue card. |
| Orders Per Year | The horizontal axis uses Ship Date. The 2012 value of 405 counts repeated rows. | Group by Order Date for orders placed. In 2012, 22 distinct orders were placed and 23 shipped. |
| Shipment Per Year | The vertical axis sums Total Cost in dollars. | Count distinct order IDs by Ship Date to measure orders shipped. |

Shipping days measure the interval from purchase to dispatch. The file has no delivery date or shipment identifier, so the shipment analysis counts orders with a ship date.

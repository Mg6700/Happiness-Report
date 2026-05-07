# World Happiness Report — Data Analysis Dashboard

**Tools:** Power BI, DAX  
**Domain:** Social Analytics | Economic Indicators | Comparative Country Analysis  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes the World Happiness Report dataset to identify what drives national happiness scores and how happiness correlates with key socioeconomic factors — GDP per capita, life expectancy, social support, freedom of choice, and generosity. The dashboard enables both global comparisons and year-specific analysis through interactive filters.

---

## Dashboard Preview

<img width="983" height="556" alt="image" src="https://github.com/user-attachments/assets/eaa43868-0020-4292-aaf9-c20b7a2334a7" />


---

## Dataset

| Field | Description |
|---|---|
| Country | All participating nations |
| Region | Geographic grouping (Western Europe, South Asia, etc.) |
| Happiness Score | 0–10 scale composite score |
| GDP Per Capita | Economic output per person |
| Life Expectancy | Healthy life expectancy at birth |
| Social Support | Perceived availability of support |
| Freedom to Choices | Perceived freedom in life decisions |
| Generosity | Charitable giving relative to income |
| Year | Multi-year coverage with year filter |

---

## Dashboard Features

- **Region filter** — isolate any geographic region for focused analysis
- **Year filter** — compare happiness scores across specific years
- **Relation b/w Life Expectancy and Happiness** — scatter plot with trend line
- **Relation b/w Freedom to Choices and Happiness** — scatter plot with trend line
- **Relation b/w GDP per Capita and Happiness** — scatter plot with trend line
- **Relation b/w Social Support and Happiness** — scatter plot with trend line
- **Happiest Countries** — top nations ranked by happiness score
- **Happiest Regions** — regions ranked by average happiness
- **Factors Affecting Happiness** — multi-factor horizontal bar chart per country showing all 5 drivers simultaneously
- **Happiness Trend over Years** — line chart showing global average happiness from 2015 to 2023

---

## Happiest Countries

| Rank | Country | Score |
|---|---|---|
| 1 | Finland | 7.8 |
| 2 | Denmark | 7.7 |
| 3 | Norway | 7.6 |
| 4 | Switzerland | 7.6 |
| 5 | Iceland | 7.6 |
| 6 | Netherlands | 7.5 |
| 7 | Israel | 7.5 |

---

## Happiest Regions

| Rank | Region | Avg Score |
|---|---|---|
| 1 | Western Europe | 7.8 |
| 2 | Middle East & North Africa | 7.5 |
| 3 | North America | 7.4 |
| 4 | Latin America & Caribbean | 7.2 |
| 5 | Central and Eastern Europe | 7.0 |
| 6 | Southeast Asia | 6.8 |
| 7 | East Asia | 6.6 |

---

## Key Findings

**1. GDP per Capita shows the strongest positive correlation with happiness**
The scatter plot of GDP vs Happiness shows the tightest clustering around the trend line — wealthier nations consistently score higher. However, outliers exist: several high-GDP nations score below trend, and some lower-income nations outperform economically.

**2. Life Expectancy and Social Support are near-equal drivers**
Both factors show strong positive correlations with happiness scores — nations where people live longer and feel more socially connected report significantly higher wellbeing, regardless of income level.

**3. Freedom of choice has a surprisingly strong correlation**
The Freedom to Choices scatter shows almost as strong a relationship as GDP — suggesting that perceived autonomy in life decisions is a critical happiness driver beyond just economic conditions.

**4. Nordic countries dominate due to strength across ALL factors**
Finland's top ranking isn't driven by a single factor — the Factors Affecting Happiness chart shows Czechia, Luxembourg, and Nordic nations scoring high across GDP, Life Expectancy, Social Support, and Freedom simultaneously. It's the combination, not any one variable.

**5. Global happiness trended upward 2015–2021, then slightly declined**
The happiness trend line shows steady growth from 2015 through 2021, followed by a modest decline toward 2022-2023 — likely reflecting post-pandemic economic stress and geopolitical instability effects on wellbeing.

**6. Generosity has the weakest correlation with happiness**
Among all five factors, generosity shows the most scattered relationship — suggesting that charitable giving behavior doesn't strongly predict national happiness scores, possibly because it's measured relative to income rather than absolutely.

---

## Correlation Summary

| Factor | Correlation with Happiness |
|---|---|
| GDP Per Capita | Very Strong (positive) |
| Life Expectancy | Strong (positive) |
| Social Support | Strong (positive) |
| Freedom to Choices | Strong (positive) |
| Generosity | Weak (positive) |

---

## Technical Highlights

- Four simultaneous scatter plots with trend lines for multi-factor correlation analysis
- Dynamic Region and Year slicers enabling cross-sectional comparisons
- Multi-factor bar chart overlaying 5 variables per country for direct comparison
- DAX measures for regional averages and year-over-year happiness change
- Trend line forecasting on happiness over years chart

---

## Data Source

World Happiness Report — Gallup World Poll. Published annually by the Sustainable Development Solutions Network (SDSN).

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*

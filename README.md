# Global Suicide Rate Analysis

## Project Overview
This project investigates global suicide trends from 1985 to 2016, analyzing the impact of socio-economic factors such as GDP, HDI, and demographics on suicide rates. Using Hive and PySpark, the dataset is processed, cleaned, and analyzed to uncover patterns and insights that can inform public health strategies.

## Dataset
- **Source**: Kaggle
- **Entries**: 27,820 (1985–2016)
- **Attributes**: Age, Gender, Generation, HDI, GDP, Suicide Rates
- **Coverage**: 101 countries

## Methodology
1. **Data Storage**: Data loaded into Hive tables using Hadoop.
2. **Preprocessing**: Missing values replaced with averages; cleaned dataset created.
3. **Analysis**:
   - Yearly trends, demographic breakdowns, and country comparisons.
   - Visualizations include age-group disparities, gender differences, and economic correlations.
4. **Visualization Tools**: Hive, PySpark, and visualization libraries.

## Key Insights
- **Gender Gap**: Male suicide rates (~20/100k) are significantly higher than female rates (~5/100k).
- **Age Trends**: Suicide rates peak in the 75+ age group.
- **Country Patterns**: Lithuania and Russia exhibit the highest average suicide rates; Dominica reports the lowest.
- **Economic Influence**: Negative correlation between GDP per capita and suicide rates, though with notable variations.

## Tools Used
- **Frameworks**: Hive, PySpark, Hadoop
- **Languages**: Python, SQL
- **Libraries**: Data visualization libraries for plots and heatmaps

## Conclusion
This analysis highlights critical socio-economic and demographic factors influencing suicide rates, emphasizing the need for targeted mental health interventions and policy recommendations.

## References
- Kaggle Dataset: [Suicide Rates Overview (1985–2016)](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016)
- World Health Organization: [Suicide Fact Sheets](https://www.who.int/news-room/fact-sheets/detail/suicide)
- Relevant Research: [PMC Article](https://pmc.ncbi.nlm.nih.gov/articles/PMC9594371/)

---

For more information, refer to the detailed project report and accompanying visualizations.

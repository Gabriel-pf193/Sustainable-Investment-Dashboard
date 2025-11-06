# The Economic impact of Sustainability: Do More Sustainable Countries Perform Better?
**Category:** Data Analysis & Visualization

Over the past decades, environmental challenges, social inequality, and ethical governance have reshaped how our society defines progress. As a result, sustainability has become a global concern, influencing both policy decisions and patterns of economic development. Governments and international institutions these days consider environmental, social, and governance (ESG) indicators a lot more when making policies, to promote long-term growth and stability. With this growing awareness, naturally we ask ourselves whether countries that invest heavily in sustainability actually achieve stronger economic performance than those whose investment in sustainability is more limited. This project aims to explore this relationship by analysing how sustainability indicators relate to economic performance across countries.

The planned approach for this matter consists of collecting publicly available indicators from the World Bank Open Data Set, covering the period from 2000 to 2023. The indicators collected from the database belong to four different categories:
* **Environmental:** CO2 emissions (metric tons per capita), fossil fuel energy consumption (% of total energy use), renewable energy consumption (% of total final energy consumption), renewable electricity output (% of total electricty output), methane and nitrous oxide emissions (metric tons of CO2 equivalent per capita).
* **Social:** Gini index, unemployment (% of labor force), and economic and social rights performance score.
* **Governance:** Control of corruption, and political stability index.
* **Economic Performance:** GDP growth (annual %), GDP per capita, inflation, foreign direct investment (% of GDP), and research & development expenditure (% of GDP).

I will chose a sample of 50 countries for the analysis. Selected countries will be those who have the most data available. However, for the sample to remain diverse and representative, i will make sure to include countries from different regions/continents and income groups.

Once the dataset is prepared, (that is, once the data is cleaned, aligned by country and year) i will use python and its analytical tools to calculate descriptive statistics, correlations, and other summary measures. This cleaned and structured dataset will then be used as the basis for a multiple linear regression analysis. This model will estimate how variations in environmental, social, and governance indicators relate to changes in GDP growth across countries. The purpose of this regression is to quantify the direction and the strenght of the relation between sustainability indicators and economic indicators. It will also allow us to see which specific indicator of sustainability will have the most significant impact on economic performance.













Expected challenges include matching ESG data with financial data, as company names and tickers may differ across sources. I will deal with this issue by focusing on a smaller sample of well-known companies and manually verify that the data matches. Missing or incomplete data may also be a difficulty, which I will handle by filtering the data so that there are no more missing entries. Finally, there can also be differences in time periods between ESG and Yahoo Finance data. Once again, I will treat this issue by filtering the data to keep only the values that match in the time frame.

Results of this analysis will be shown through a dashboard that compares financial performance of "green" companies with that of regular companies. If time permits, I would like to make this dashboard interactive, so that one can explore the data by selecting specific companies, time periods, or performance indicators.

To conclude, the objective of this project is to provide a perspective on how sustainability relates to financial performance, using data from ESG scores and Yahoo Finance. It will test whether responsible businesses practices can also deliver competitive returns. It will also be a great opportunity for me to learn more about python and improve my analytical skills.

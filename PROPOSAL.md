# The Economic impact of Sustainability: Do More Sustainable Countries Perform Better?
**Category:** Data Analysis & Visualization

Over the past decades, environmental challenges, social inequality, and ethical governance have reshaped how our society defines progress. As a result, sustainability has become a global concern, influencing both policy decisions and patterns of economic development. Governments and international institutions these days consider environmental, social, and governance (ESG) indicators a lot more when making policies, to promote long-term growth and stability. With this growing awareness, naturally we ask ourselves whether countries that invest heavily in sustainability actually achieve stronger economic performance than those whose investment in sustainability is more limited. This project aims to explore this relationship by analysing how sustainability indicators relate to economic performance across countries.

The planned approach for this matter consists of collecting publicly available indicators from the World Bank Open Data Set, covering the period from 2000 to 2023. The indicators collected from the database belong to four different categories:
* **Environmental:** CO2 emissions (metric tons per capita), fossil fuel energy consumption (% of total energy use), renewable energy consumption (% of total final energy consumption), renewable electricity output (% of total electricty output), methane and nitrous oxide emissions (metric tons of CO2 equivalent per capita).
* **Social:** Gini index, unemployment (% of labor force), and economic and social rights performance score.
* **Governance:** Control of corruption, and political stability index.
* **Economic Performance:** GDP growth (annual %), GDP per capita, inflation, foreign direct investment (% of GDP), and research & development expenditure (% of GDP).

I will choose a sample of 50 countries for the analysis. Selected countries will be those who have the most data available. However, to keep the sample representative of the global world, I will make sure to include countries from different regions/continents and income groups.

Once the dataset is prepared, (that is, once the data is cleaned, aligned by country and year) i will use python and its analytical tools to calculate descriptive statistics, correlations, and other summary measures. This dataset will then be used as the basis for a multiple linear regression analysis. The model will estimate how variations in environmental, social, and governance indicators relate to changes in GDP growth across countries. The purpose of this regression is to quantify the direction and the strengh of the relation between sustainability indicators and economic indicators. It will also allow us to see which specific indicator of sustainability will have the most significant impact on economic performance.

Along with the regression, I will use a simple machine learning model to test how well sustainability indicators can predict economic performance. The model will use the same variables as with the regression and will be evaluated using standard accuracy measures such as the R squared. This step will allow us to compare the results of a predictive approach with those of the statistical analysis.

Expected challenges include differences in data coverage, since countries may not all report every indicator for each year. I will address this by keeping only countries with enough available data. Another potential difficulty is regional bias, since some regions may have better data availability than other. As I said previously, I will make sure to include countries from every region, as long as the data available is satisfying. Finally, we can think of uneven time coverage a potential issue, since certain sustainability indicators begin later than others, which may reduce the number of comparable years.

If time permits, I would like to make a dashboard that would bring a visual summary of the results, allowing us to view the relationship between sustainability and economic performance in a more easy and pleasent way.

To conclude, the objective of this project is to provide a perspective on how sustainability relates to economic performance, using data from the World Bank. It will test whether more sustainable countries do globally better compared to others. It will also be a great opportunity for me to learn more about python and improve my analytical skills.



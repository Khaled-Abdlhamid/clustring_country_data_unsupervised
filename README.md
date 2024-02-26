# [Unsupervised Learning on Country data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data)
###### Context
HELP International have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. So, CEO has to make decision to choose the countries that are in the direst need of aid. Hence, your Job as a Data scientist is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.
###### Objective:
To categorise the countries using socio-economic and health factors that determine the overall development of the country.


### Column Dictionary:
- country: Name of the country
- child_mort: Death of children under 5 years of age per 1000 live births
- exports: Exports of goods and services per capita. Given as %age of the GDP per capita
- health : Total health spending per capita. Given as %age of GDP per capita
- imports: Imports of goods and services per capita. Given as %age of the GDP per capita
- Income: Net income per person
- Inflation: The measurement of the annual growth rate of the Total GDP
- life_expec: The average number of years a new born child would live if the current mortality patterns are to remain the same
- total_fer: The number of children that would be born to each woman if the current age-fertility rates remain the same.
- gdpp: The GDP per capita. Calculated as the Total GDP divided by the total population.
 

#### EDA:
- plotted some of the features to visualize the ralationships.
- created **continent** column to understand the data more.
- plotted groupby aggregated columns by each continent.
- used StandardScaler and MinMaxScaler for scaling the features.
- plotted elbow method, silhoute score and tsne.

#### Training:
- Trained KMeans, DBSCAN, AgglomerativeClustering and GMM.


# disease_analysis
The given dataset contains information related to different pandemics, countries, cases, deaths, vaccinations, healthcare resources, testing, and peak daily cases. The main objective of this analysis is to clean the data and understand different patterns and relationships using Python and data visualization.

First, the dataset was checked for missing values, duplicate records, and inconsistent categorical values. Duplicate records were removed and categorical values such as Country and Pandemic were standardized. Missing numerical values were handled using suitable statistical values. After cleaning, the dataset was verified to make sure that the records were unique and the required values were available.

Min-Max normalization was then applied to selected numerical columns such as total cases, total deaths, vaccinated people, and tests. This converts the values into a common range between 0 and 1, making variables with different scales easier to compare.

The pandemic-wise analysis was performed to compare the total number of cases, deaths, and recovered cases for different pandemics. The results help identify which pandemics had a higher overall case burden.

Country-wise analysis was used to identify the countries with the highest total number of cases. The average peak daily cases were also calculated to understand the maximum disease burden experienced by different countries.

A year-wise analysis was performed to study how total cases, deaths, and vaccination changed over time. The line chart helps visualize the trend and identify increases or decreases in cases across different years.

The dataset was also filtered to study COVID-19 cases specifically for India, Brazil, and the USA. Total cases, total deaths, and average vaccination rates were compared among these countries.

The relationship between vaccination rate and total cases was analyzed using a scatter plot. This helps identify whether there is any visible relationship between vaccination coverage and case levels. However, correlation or association does not prove that one variable causes another.

Box plots were used to study the distribution of total cases for different pandemics. They show the median, spread, and possible outliers. This provides more information than simply calculating the average.

Healthcare capacity was analyzed by continent using average hospital beds, healthcare workers, and total cases. A grouped bar chart was used to compare hospital beds and healthcare workers between continents. However, these values alone cannot determine which continent has better healthcare capacity because many other factors are involved.

Finally, a correlation matrix was created for cases, deaths, recovered cases, vaccination, testing, and peak daily cases. The heatmap makes it easier to identify strong positive or negative relationships between variables. The analysis shows how different pandemic-related factors are related, but correlation should not be interpreted as causation.

Overall, the analysis demonstrates how data preprocessing, grouping, aggregation, filtering, normalization, correlation analysis, and visualization can be used to understand a real-world pandemic dataset and extract meaningful information from it.

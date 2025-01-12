# US-Counties-COVID-19

## Overview  
This project analyzes a dataset of COVID-19 cases and deaths across U.S. counties, containing 2.5 million rows of data. The dataset, sourced from **The New York Times**, is used to uncover trends and insights related to the progression of COVID-19 in the U.S. The project includes an interactive dashboard to visualize key metrics such as case totals, death counts, death rates, and state/county comparisons over time.  

## Tools and Technologies  

- Python: Used for data processing and manipulation.  
- Pandas: I used **Pandas** to split the 2.5 million rows of data into 10 separate files. Pandas was also used for data cleaning, filtering, and aggregation to ensure the data was usable for analysis.  

- Power Query: After splitting the data with Pandas, I used **Power Query** to append the 10 files into one consolidated file. Power Query was also used to clean the data further and ensure consistency before analysis.  

- Power BI/Tableau: I used **Power BI** to create a dashboard that summarizes key insights.

  
## Key Insights  

- Top 10 States: The dashboard shows a breakdown of the top 10 states with the highest number of COVID-19 cases.  
- Death Rates Over Time: The dashboard highlights how death rates evolved over the months and years, offering a clear view of the virus's impact over time.  
- County-Level Insights: The top 4 counties with the highest death rates are identified, providing insights into regional disparities and trends.  

## Dataset  
- Source: The data is from **The New York Times COVID-19 data repository**, which provides cumulative counts of confirmed cases and deaths across U.S. counties.  
- Content: The data begins with the first reported case on January 21, 2020, and continues with regular updates.

## License  
This project is licensed under the [MIT License](LICENSE).  

## Acknowledgments  
- Data Source: [The New York Times COVID-19 Data](https://github.com/nytimes/covid-19-data).

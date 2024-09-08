# COVID-19-Analysis

In this analysis, we looked at COVID-19 mortality and comorbid conditions that contributed to the death rate due to COVID-19. The data looked at different demographic and geographic regions throughout the United States. The purpose of the analysis was to discover any trends, pattrerns, and insights in Covid mortality and any factors that lead to increased mortality due to Covid. 

# **Project Overview**
The analyses in this project were performed using real-world data on COVID-19 death rates obtained from the Centers for Disease Control and Prevention (CDC) and the United States Census Bureau. The primary analysis was to try and understand what impact, if any, various short-term and chronic medical conditions have on Covid mortality rates. 

# **Repository Structure**
*  01 Project Management: Contains the project brief which outlines the objectives and expectations of the analysis.
*  02 Data: Contains a PDF file with links to the datasets and files used in the analysis.
*  03 Scripts: Includes all Python scripts used in the data analysis, structured in Jupyter Notebooks.
*  04 Analysis/Visualizations: Contains image files of the visualizations generated during the analysis.
*  05 Final Report: Includes the Tableau Public storyboard as a PDF file, available to view on Tableau Public [here] (https://public.tableau.com/views/MSikosAchievement6Exercise6_7/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

# **Key Questions Addressed**
*  Which conditions are most strongly associated with COVID-19 deaths?
*  How do COVID-19 death rates vary across different states and age groups?
*  What are the geographical patterns in COVID-19 death rates and contributing conditions across the United States?
*  How can linear regression and clustering analyses be used to predict and understand COVID-19 mortality?
*  What are the temporal trends and seasonal patterns in COVID-19 deaths and contributing conditions?

# **Tools Used**
* Python: Primary programming language used for data analysis.
* Pandas: For data manipulation and analysis.
* NumPy: For numerical operations.
* Matplotlib & Seaborn: For generating data visualizations.
* Scikit-learn: For implementing machine learning models.
* Statsmodels: For time series analysis and ARIMA modeling.
* Geopandas: For geographical data manipulation and visualization.
* Plotly: For interactive visualizations.
* Tableau Public: For creating interactive visualizations and dashboards.

# **Visualizations**
This project includes multiple different types of visualizations including: scatter plots, choropleth maps, bar charts, and time-series plots. These visualizations are used to highlight how different short-term and chronic medical conditions, geographic and regional variations, and temporal trends impact COVID-19 mortality.

# **Analyses Performed**
## Initial Data Exploration
*  Exploration of the dataset: Understanding the structure and key statistics.
*  Cleaning and preprocessing: Handling missing values, outliers, and data type conversions.

## Geographical Analysis
*  Choropleth maps: Visualizing total COVID-19 deaths and death rates per 100,000 population across states.
*  Insights: Identifying high-impact states, regions and patterns.

## Linear Regression Analysis
*  Model Building: Developing a regression model to predict COVID-19 deaths based on the number of mentions of medical conditions.
*  Performance Evaluation: Assessing the model using Mean Squared Error (MSE) and R-squared score.

## Cluster Analysis
*  K-means clustering: Identified clusters of states with similar COVID-19 impact.
*  Cluster Interpretation: Analyzing the characteristics and severity of each cluster.

## Time Series Analysis
*  Trend and Seasonality: Decomposing time series data to identify trends and seasonal patterns.
*  Stationarity Check: Performing the Dickey-Fuller test to check for stationarity and performing differencing to achieve stationarity.
*  Autocorrelation Analysis: Using Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to analyze the autocorrelation structure of the time series data.

## Conclusion and Recommendations
These analyses provided a deeper understanding of the factors that contribute to COVID-19 death rates while also emphasizing the the importance of demographic, geographic, and condition-specific factors. The findings can be used to create targeted interventions and direct allocation of resources to where it is needed most during future health crises.

## **Limitations and Potential Biases**
*  Provisional Nature of Data: Data is provisional and conclusions may need to be revised when the finalized data becomes available.
*  Reporting Delays: Delays in reporting can affect the accuracy and completeness of more recent data.
*  Inconsistent Reporting Standards: Variability in state-level reporting standards may impact reliability.
*  Multiple Conditions: Presence of multiple conditions listed on official death certificates can complicate our analyses.
*  Double Counting Risk: Deaths involving multiple medical conditions are counted in each relevant category increasing the risk of overcounting.
*  Population Data: Population data is from the 2020 census, which may not reflect changes over time.

## **Recommendations for Future Work**
*  Enhanced Clustering: Perform clustering analyses on additional conditions and demographics.
*  Predictive Modeling: Develop models to identify high-risk populations and enhance public health strategies.

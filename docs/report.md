# Microbusiness Denisty in the U.S.
**presentation link:** https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/blob/main/docs/capstone.pptx

**youtube video link:** https://youtu.be/kUH9eHlKj90

## Introduction
American policymakers work to create economies that are more diverse and recession-proof. They are also aware that because to technological advancements, starting a business has never been easier than it is right now. Studies have shown that more Americans are choosing to start their own enterprises to achieve their financial goals, whether it's to achieve a better work/life balance, to pursue a passion, or as a result of losing their jobs. It is difficult for policymakers to research these "microbusinesses" since they are frequently too small or too new to appear in conventional economic data sources. However, data science might be able to close the gaps and offer insights into the elements that influence these organizations.

The [Venture Forward](https://www.godaddy.com/ventureforward/) team at GoDaddy has been working hard for the past few years to create data assets about the tens of millions of microbusinesses in the US. Microbusinesses are typically categorized as companies with ten or fewer employees and an online presence. More than 20 million of them, controlled by more than 10 million business owners, are visible to GoDaddy. You can access a wealth of information about this group of microbusiness owners that we have gathered over the course of several years of surveying them by accessing our survey data [here](https://www.godaddy.com/ventureforward/explore-the-data/?section=survey&cfips=6073).

Current models use econometric methods, draw on available internal and census data, and concentrate on comprehending primary factors. These approaches are sufficient, but there is room for improvement by adding more information and applying cutting-edge techniques to predictions and decision-making. GoDaddy is the biggest services marketplace for business owners worldwide. They have made it their mission to equip their community of more than 20 million customers—and business owners everywhere—with the resources and tools they require to succeed online. As they try to improve the world for microbusiness owners, policymakers will be better informed thanks to this work. This will have a real and substantial impact on communities across the country and will help our broader economy adapt to a constantly evolving world.

## Methodology
### Data Collection
The data collection process for microbusiness density in the US involved gathering information from the [Venture Forward website](https://www.godaddy.com/ventureforward/microbusiness-datahub/). Venture Forward serves as a comprehensive database that provides insights into the entrepreneurial ecosystem, including microbusinesses, across the United States. The website aggregates data from various sources, such as government reports, surveys, and business registries, to create a comprehensive picture of the microbusiness landscape.

To gather the data, relevant datasets and reports from the Venture Forward website were accessed and extracted. These datasets contain detailed information about microbusinesses, including their locations, industries, sizes, and other relevant attributes. The data collection process involved utilizing the U.S. Microbusiness Density data, U.S. Microbusiness Industry and Commerce and U.S. Microbusiness Activity Index.

By leveraging the Venture Forward website as the primary source of data, this study aimed to provide a comprehensive analysis of microbusiness density in the US. The utilization of this data source allowed for a robust examination of microbusiness trends, distribution, and other relevant insights, contributing to a comprehensive understanding of the microbusiness landscape in the United States.

### Data preprocessing
Careful consideration was given to data quality and relevance. The collected data was evaluated for accuracy, completeness, and consistency to ensure reliable analysis. Preprocessing steps, such as data cleaning, were performed to address any inconsistencies or missing values within the dataset. Collected data was clean with no missing values.

## Data Analysis and Findings.
There are three datasets used in this project.
> U.S. Microbusiness Activity Index: In terms of microbusinesses, how vibrant and healthy is a community?
> The Microbusiness Activity Index, created by economists at the UCLA Anderson Forecast in collaboration with GoDaddy Venture Forward, keeps track of hundreds of variables that have an impact on the success of online microbusinesses and combines them into a single composite score.Infrastructure, participation, and engagement make up the three subindices that comprise the overall score. This score, which is updated every quarter, is used to compare one community to others and monitor the success of initiatives designed to support the growth of microbusinesses. The Index offers the most recent picture of the situation of microbusinesses at the local, regional, state, and federal levels. This dataset consisted of observation from April 2020 - June 2022.

### U.S. Microbusiness Activity Index Dataset: 
Following is the top 5 observations.
![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/d876e1e1-4eef-4785-a2c5-fbd0dbef7d1b)

**Infrastructure** is the measure of how prepared a community is to use the internet (do they have th erequired physical and intellectual infrastructure).

**Participation** is the number of online microbusiness and operators in the community.

**Engagement** is the measure that whether a a community has active busniess websites.

The follwoing heatmap describes how these factors are related in measuring the Mcirobusiness Activity Index for a community.
![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/884f4224-b7f0-4869-b446-a460e7742d44)

 Upon checking for state with High and Low infrastructure:
 
 ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/44c0c01a-90ed-4ec9-8fa3-eccdc23209c5) ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/367229d6-6d15-487f-92ca-df07b304cf45)

 States that recorded High and Low Engagement levels:
 
 ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/4cb7d19c-a539-4290-9eac-66b5fa814dd4) ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/d7bc0ed6-6703-4ad0-be2d-2cdf3b2312c6)
 
 States that recorded High and Low Participation levels
![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/ef72dd72-b281-4d66-8477-f82e436ce61a) ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/570372b9-ccd9-47f3-b6c0-95b7d745773d)


> U.S. Microbusiness Industry and Commerce: The Industry and Commerce dataset provides insight into the online commercial activity trends of microbusinesses at multiple geographic designations, including city, CBSA, county, and state. This unique dataset ranks all the covered communities based on the number of sellers, orders, and gross merchandise value (GMV) observed, providing a new lens into how effectively microbusinesses are performing. In addition, the dataset identifies the top 3 industry categories within the community, the average traffic we can observe, and the average microbusiness age, measured in months. The dataset consisted of observations from August 2019 - June 2022.

Following are the top 5 states that recorded the **highest** traffic for the period of August 2019 - June 2022:

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/5672bdae-3016-4e65-b72f-eb0aae6dd64c) ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/77fec8e7-a39a-4949-ae1f-d6d7130420ee)

Following are the top 5 states that recorded the **lowest** traffic for the period of August 2019 - June 2022:

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/f755e5f2-bcd5-4f86-9e8c-dbfac07868ff) 

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/c9e5a6c1-9d3f-4d56-b96f-30b43d7de730)

**Average Life Span of website sin U.S.**

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/61c4d802-1227-4c4b-8419-eadf94b7f45a)

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/004f50f9-2a9e-41db-8da8-70c594305017)

## Time Series Analysis

>U.S. Microbusiness Density:  This dataset is used to get a comprehensive insight into the quantity and distribution of active microbusinesses across the country at several geographic grains, including: CBSA, county, state, and national, normalized by population. Microbusiness density is a powerful tool for understanding where microbusinesses are taking hold and how those patterns are changing over time. Use this measure to help identify relationships to other key economic outcomes, such as unemployment, job creation, and household median income gains – all affected by microbusinesses The dataset had observations for the period of August 2018 - Junw 2022.

Following are the top 5 states with the highest avg. of active websites recorded:

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/69a85a94-5bb0-4e46-93e5-d7bdd01960d5)

Since California had the hoghest number of active websites, we perform time series on Californias data points.

As per Augumented Dickey Fuller Test, the data set was non-stationary. The dataset,  contained historical information on microbusiness density a time period from August 2018 - June 2022, was preprocessed to ensure consistency and stationarity. 

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/9b36ee9c-0cb2-448f-bbaf-2843fd46187b)

We us differncing method to make it stationary.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/e0a5ad2d-dc0f-4bc0-b5a8-fbf1e318be5a)

In the time series analysis of microbusiness density, the Microbusiness density dataset was utilized to perform predictive analysis using ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models. ARIMA is a widely used forecasting method that takes into account the autocorrelation and trend in time series data. SARIMA, an extension of ARIMA, incorporates seasonality in addition to the autocorrelation and trend components.

The ARIMA model focused on capturing the autocorrelation and trend in the time series data, while the SARIMA model additionally accounted for seasonal variations that might be present in the microbusiness density. By incorporating these models, it was possible to generate forecasts and insights regarding the expected trends, fluctuations, and seasonality of microbusiness density over time.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/2cf1ee19-3a0b-4fdc-ae05-a3078fd27fe5)

### ARIMA model forcasting
The ARIMA model focused on capturing the autocorrelation and trend in the time series data, while the SARIMA model additionally accounted for seasonal variations that might be present in the microbusiness density. By incorporating these models, it was possible to generate forecasts and insights regarding the expected trends, fluctuations, and seasonality of microbusiness density over time.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/c90c7dec-c528-4108-87df-d21a8bb150d8)

### SARIMA model foracting 

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/5f79acf7-d9f9-4a3c-b3a0-f42d4bf0eaf5)


The results of the predictive analysis using ARIMA and SARIMA provided valuable insights into the future behavior of microbusiness density. These insights could aid in understanding the potential growth, fluctuations, and seasonality patterns of microbusinesses in a given region. The application of ARIMA and SARIMA models allowed for data-driven decision-making and strategic planning, providing a valuable tool for understanding and predicting microbusiness density trends in the context of time.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sushruta_DATA606/assets/75373728/dc3c309d-3d6d-474b-b1dc-64677b80ffd9)

## Conclusion
In conclusion, this project focused on performing future forecasts to predict microbusiness density using the ARIMA model. By analyzing historical data and incorporating the autocorrelation and trend components, the ARIMA model provided valuable insights into the future behavior of microbusiness density. The forecasts generated through the model offered a glimpse into the expected trends, fluctuations, and potential seasonality patterns of microbusiness density over time.

The project's findings and predictions hold significant benefits for various stakeholders. Policymakers and government bodies can utilize the forecasts to understand and anticipate the growth and distribution of microbusinesses in different regions. This information can aid in making informed decisions related to economic development, resource allocation, and supporting entrepreneurial ecosystems. Additionally, entrepreneurs and small business owners can benefit from these forecasts by gaining insights into the potential market conditions and adjusting their strategies accordingly.

## Furture Scope
Model Refinement: Exploring alternative time series forecasting models, such as advanced machine learning algorithms or ensemble methods, to improve the accuracy and precision of microbusiness density predictions.

Incorporating External Factors: Considering additional external factors like economic indicators, demographic data, or industry-specific variables to enhance the forecasting model's capabilities and capture more nuanced trends and influences on microbusiness density.

Regional Analysis: Conducting a deeper analysis by focusing on specific regions or cities to identify regional variations, factors influencing microbusiness density, and tailor predictions accordingly.

Long-Term Forecasting: Extending the forecasting horizon to make long-term predictions and assess the sustainability and growth potential of microbusiness density over an extended period.

Comparative Analysis: Conducting comparative studies across different countries or regions to understand the variations in microbusiness density and draw insights from diverse entrepreneurial ecosystems.

By further exploring these aspects, future research can contribute to advancing the understanding of microbusiness dynamics, providing more accurate and actionable forecasts, and supporting policymakers, entrepreneurs, and other stakeholders in making informed decisions related to microbusiness development and economic growth.















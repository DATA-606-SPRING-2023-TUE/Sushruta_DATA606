# Phase II: Data Preparation & EDA

**Data Cleaning:** In this step the data was cleaned and prepared for analysis. the dataset did not contain any missing values or outliers. The dataset was clean with no null values.

**Data Exploration:** In this step I checked if there is any correlation between the variables in every datset.

**U.S. Microbusiness Activity Index**: MAI developed by UCLA, this score tracks dozens of factors that impact the success of online micorbusinesses; it is made up of 3 subindices - infrastructure, particpation and engagement. The data collected is from April 2020 - June 2022.
> Features/variables in the dataset.
> * date 
> * State
> * MAI_composite - composite index score for a given date
> * engagement - measures how active websites are in the community.
> * participation - measures the number of online microbusinesses and operators in the community
> * infrastructure -  measures how prepared a community is to use the internet, in terms of necessary physical and intellectual infrastructure.

**U.S. Microbusiness Density**: It provides an insight to understanding the quantity and distribution of active microbusinesses across the country. This datset will help us understand where microbusinesses are taking hold and overtime changing patterns. This data is taken from August 2019 - June 2022
> Features/variables in the dataset.
>* state
>* active -  raw count of the number of active microbusinesses in a community
>* md - microbusiness density measure 

**U.S. Microbusiness Industry and Commerce**: It provides insights into online commercial activity trends like number of sellers, orders and gross mechandise value (GMV) that a microbusinesses was performing. This data is taken from August 2019 - June 2022.
> Features/variables in the dataset.
>* state name
>* top3industries - The top three industries by transaction dollars for the given month in the respective geographic area
>* avg_lifespan_mths- Average lifespan of existing websites, in months, for GoDaddy website + marketing customers, in the respective geographic area. 

### Technique
* ARIMA
* SARIMA

The above models will be used to predict the density of microbusineeses in a given state. Through this technique we try to find microbusiness hotspots in the US across cities and states.

### Outcome
Perform visualizations that are more user friendly and provide statewise view of growing microbusinesses. I plan on performing time series analysis on U.S. Microbusiness Density dataset to analyse the trend of active businesses for the state with highest microbusiness density recorded. This will make it easier for policy makers and inverstors to get useful insights with respect to growing microbusiness, thus helping them identify industry growth and provide effective programs for these microbusinesses to thrive.



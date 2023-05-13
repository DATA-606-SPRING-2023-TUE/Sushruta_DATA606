# PHASE I: Project Proposal and Planning

## Topic: Analyse Microbusinesses in the US. 

### Motivation
This project is inspired from GoDaddy's Kaggle competition on [predicting monthly microbusiness density in a given area](https://www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting/overview). This will provide visibility on growing trends and, performance and health of microbusinesses; helping policy makers and investors.

### Problem Statement
Due to technological advancements, starting a business has never been easier than it is right now. Studies have shown that more Americans are choosing to start their own businesses to achieve their financial goals, whether it's to achieve a better work/life balance, to pursue a passion, or as a result of losing their jobs. American policymakers strive to build more diverse and resilient economies. Microbusinesses are frequently too small or too new to be included in traditional economic data sources, making it extremely difficult for policymakers to conduct research on them. However, data science could fill in the gaps and provide insights into the factors influencing these businesses. 

### Dataset Description
[Venture Forward](https://www.godaddy.com/ventureforward/microbusiness-datahub/), team at GoDaddy, produced datasets created from huge data of microbusinesses in the US. This data consists of Microbusiness with online presence and ten or fewer employees. They have also collected microbusiness owner's survey data for a timeframe of  2019 - 2022. This project utilizes 3 datasets from Venture Forward.

**U.S. Microbusiness Activity Index**: MAI developed by UCLA, this score tracks dozens of factors that impact the success of online micorbusinesses; it is made up of 3 subindices - infrastructure, particpation and engagement. The data collected is from April 2020 - June 2022.
> Features/variables in the dataset.
> * date 
> * Zipcode 
> * City,State 
> * total_pop_20 - total population in 2020
> * MAI_composite - composite index score for a given date
> * engagement - measures how active websites are in the community.
> * participation - measures the number of online microbusinesses and operators in the community
> * infrastructure -  measures how prepared a community is to use the internet, in terms of necessary physical and intellectual infrastructure.

**U.S. MIcrobusiness Density**: It provides an insight to understanding the quantity and distribution of active microbusinesses across the country. This datset will help us understand where microbusinesses are taking hold and overtime changing patterns. This data is taken from August 2019 - June 2022
> Features/variables in the dataset.
>* city_name
>* micro_metro
>* total_pop_20
>* active -  raw count of the number of active microbusinesses in a community
>* md - microbusiness density measure 

**U.S. Microbusiness Industry and Commerce**: It provides insights into online commercial activity trends like number of sellers, orders and gross mechandise value (GMV) that a microbusinesses was performing. This data is taken from August 2019 - June 2022.
> Features/variables in the dataset.
>* city_name
>* groupflag -  to denote whether a CBSA is a micropolitan or a metropolitan statistical area.
>* total_pop_20
>* orders_rank - Monthly rank in terms of orders per 100 people for sites GoDaddy can see transactions in the respective geographic area
>* merchants_rank - Monthly rank in terms of active merchants (online stores) per 100 people for sites GoDaddy can see transactions in the respective geographic area
>* gmv_rank - Monthly rank in terms of transaction dollars per 100 people for sites GoDaddy can see transactions in the respective geographic area. GMV (Gross Merchandise Value).
>* top3industries - The top three industries by transaction dollars for the given month in the respective geographic area
>* avg_lifespan_mths- Average lifespan of existing websites, in months, for GoDaddy website + marketing customers, in the respective geographic area. 


### Technique
* ARIMA
* SARIMA

The above models will be used to predict the density of microbusineeses in a given city/state. Through this technique we try to find microbusiness hotspots in the US across cities and states.

### Outcome
To make my visualization more user friendly, I plan on developing a webapp using StreamLit. This webapp will make it easier for policy makers and inverstors to get useful insights with respect to growing microbusiness, thus helping them identify industry growth and provide effective programs for these microbusinesses to thrive.



# **King County Houses Multiple Regression Analysis**

![image](https://github.com/BetshuaK/Phase-2/assets/116350595/29b60fd5-cbd7-485c-834e-b07bf39ec920)

## **Business Overview:**

According to the 2020 census, King County was the most populous county in Washington, and the 13th-most populous in the United States. It is in Seattle, the state's most populous city. Given the statistics, Tella Real Estate Agency, based in King County, has undertaken a research to find out the best performing metrics when it comes to house sale prices determination. As such, we went all out to do multiple regression analysis to gain insights into the home sales market and improve the sellers' chances to make sales. By identifying the key factors that affect the sale prices of houses, the agency can develop more effective marketing strategies, help sellers target the right buyers, and make better investment decisions.

## **Problem Statement**

Tello Real Estate Agency has a dataset of home features collected from the county houses. They include the number of bathrooms, number of bedrooms, number of floors, square footage of living space amongst others, as seen in the dataset attached. The agency wants to understand the relationship between these features and the sale prices of houses in King County, and particularly, which features most affect the prices.

## **Objectives**

The following are the questions whose answers we have come up with in this analysis:

* To understand the relationships between the various features and the sale price of a house.
* To determine the peak house sale season.
* To build a multiple linear regression model that identifies the most important factors that influence the sale price of a house.
* To use the model to gain insights into the home sales market and improve decision-making processes.

## **Data Understanding and Analysis**

### **Source of Data**

I used the King County Sales data to compute our analysis:

### Data Analysis

* The data had 21 features that I worked with to come up with the best predictive model.
* Started by analyzing each of the house features individually by looking at their charecteristics and distribution.
* As part of preparing the data for analysis, I cleaned it as outlined stepwise in the notebook.
* Next, I tracked the relationship amongst the individual variables with each other.
* For the data with categorical variables as well as that which wasn't normally distributed, I did some feature engineering for variables we felt would have an impact in the analysis.
* Finally, I modelled various variables to see how the regression compared to the baseline model in determining the house prices.

### Data Visualization

### Graph of individual variables' distribution:

<img width="172" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/400e208e-1dca-46bf-9b61-e440d42aed03">

<img width="175" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/c4fe1b56-189c-4746-b7d9-ed08b74f380e">

<img width="175" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/e7222838-4ac1-4be2-a15c-31ffb8577fb9">

<img width="174" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/0b381452-0d9f-48f4-a990-7ed8ce8aba5a">

<img width="180" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/8ce3438d-9154-462b-a2c2-0f4b45b817b2">

<img width="173" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/3e8c6057-cd2b-4db1-9101-260372ce2b8a">

<img width="171" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/454f6585-5f5d-4f09-bcb3-cf9d94b6af6d">

<img width="184" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/bbdd3ee2-11bc-42b0-9a1a-25f24933eef3">

<img width="179" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/25f4f6cc-9412-4418-8af5-1d30b167fe55">

<img width="184" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/e376a128-1915-40a4-aa69-7672d292fd87">

<img width="178" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/9ab9d2ab-4e6c-443e-b6e0-2742b5cbac63">

<img width="182" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/bf70796f-e76b-4613-8c67-62955434aa27">

<img width="176" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/3834e0aa-ee26-45ac-98fb-34b43fa3cec4">

<img width="176" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/504976e9-5187-441d-a92f-2ad1c5d4a1a3">

<img width="180" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/1c980079-469a-4610-964c-1d53b082fca0">

### A look at the price dstribution:

<img width="308" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/ec9afd68-9a08-49e4-b399-699933f57674">

### How the various seasons impact house purchase:

<img width="305" alt="image" src="https://github.com/BetshuaK/Phase-2/assets/116350595/daec9fad-5158-4aa5-b951-ac1e6eda69f9">

### Challenges

* The model does have some limitations: given that some of the variables needed to be log-transformed to satisfy regression assumptions, any new data used with the model would have to undergo similar preprocessing.
* Additionally, given regional differences in housing prices, the model's applicability to data from other counties may be limited.
* Due to the presence of high multicollinearity among several predictor variables, I had to remove some of those columns from our analysis.

### Conclusion

* The variables that have a major influence on the price of the house are; square foot living, age of the house, good condition of the house, if the house is on a waterfront and has an excellent view.
* The variables that has the least influence on the price of the house are; grade, number of bedrooms, sqft lot, sqft basement and sqft lot 15.
* For those looking for economical housing options, it might be wise to consider sacrificing spacious living quarters or a scenic waterfront view.

We can also see that:

* The highest number of house sales are made in the second quarter of the year (Q2: April 1 - June 30) which falls in the Spring season.
* The lowest number of house sales are made in the first quarter of the year (Q1: January 1 - March 31) which falls mostly in the Winter season.

### Recommendations

* Revonate their house since this increases the value of the house
* Ensure that the houses are in good condition before putting it into the market for sale
* Increase square footage of living space
* Put up their houses for sale in peak season-Spring

### Future work

* Reducing noise in the data to improve the accuracy of our model.
* Additionally investigate certain features, such as constructional/architectural values of the house, to see what trends we could discern from that.

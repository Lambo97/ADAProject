# Searching the most-efficient source of food

## Abstract

Last years, human population has been growing exponentially. Projections of population growth established in 2017 predict that the human population is likely to keep growing until 2100, [https://population.un.org/wpp/Publications/] reaching an estimated 8.6 billion in 2030, 9.8 billion in 2050 and 11.2 billion by 2100. While the earth gets more crowded, we have to ask the question how we will feed all those people. The Global Food & Agriculture Statistics dataset, provided by the UN, grants over 3 million time-series and cross sectional data relating to food and agriculture. In our project, we will search for the most efficient ways of providing food to humans, in terms of health, nutritive value, environmental impact, area use,... Our story will start with looking at the global factors and current situation. Later we will zoom in on the United States, and look how they could transform their food industry to be as efficient as possible.

## Research questions
A list of research questions you would like to address during the project.

* How does agriculture affects the greenhouse gas emission ? (Which product emits the most greenhouse gas)
* How can we classify agricultural products according to their impact on environment? Which parameters are significant?
* How does the consumption of certain agricultural products influences the health of the people in this country? 
* How replacing a part of meat (and milk, dairy products) production by the production of vegetal sources of proteins could change the impact of agriculture on environment (GHG emissions, land use, water use,...)?
* How can countries transform their agriculture to be as efficient as possible, in terms of environmental impact and 'healthiness'.

## Dataset
Our first focus point is emissions and environment impact. For that reason we will in a first time mainly focus on those datasets. The idea is also to see which relevant link we can make between different datasets to go further into analysis. This is why we need more classical datasets as the commodity balances, food supply, macro statistics, etc.  

From the UN global food and agriculture statistics, we will use :
 * All the datasets beginning with Emissions
 * All the datasets beginning with Environment
 * The 2 "CommodityBalances" files
 * The 2 "FoodSupply" files
 * "Indicators_from_Household_Surveys_E_All_Data_(Normalized)"
 * All the datasets beginning with Inputs
 * "Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)"
 * "Population_E_All_Data_(Norm)"
 * All the datasets beginning with Production
 

## A list of internal milestones up until project milestone 2

* Data acquisition (03/11):
  * Select the csv files that fits with our research questions
  * Set up Git and the project structure
  
* Data cleaning (11/11):
  * Put CSV files in Dataframes and check for missing values, inconsistensies, etc.
  * Check if entities (crops, countries), are linked by unique ID in the different datasets
  * Outliers detection and removal
  
* First analysis (18/11):
  * Quantify use of agricultural products per country/region
  * Classification of agricultural products according to GHG emissions
  * Extend the classification to other environmental parameters (land use,etc.)
  * Quantify population health by consumptions of different products

* First results (24/10):
  * Quantify efficiency of agricultural products by their impact on environment vs nutrititive value.


* Last review and submission (25/11):
  * Debug and clean up code
  * Document all code
  

## Questions for TAa

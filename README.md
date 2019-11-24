# How much emission are you REALLY reponsible for

## Abstract

Last years, human population has been growing exponentially. Projections of population growth established in 2017 predict that the human population is likely to keep growing until 2100, [https://population.un.org/wpp/Publications/] reaching an estimated 8.6 billion in 2030, 9.8 billion in 2050 and 11.2 billion by 2100. While the earth gets more crowded, we have to ask the question how we will feed all those people. The Global Food & Agriculture Statistics dataset, provided by the UN, grants over 3 million time-series and cross sectional data relating to food and agriculture. In our project, we will search for the most efficient ways of providing food to humans, in terms of health, nutritive value, environmental impact, area use,... Our story will start with looking at the global factors and current situation. Later we will zoom in on the United States, and look how they could transform their food industry to be as efficient as possible.

## Research questions
A list of research questions you would like to address during the project.

* What is the percentage of emission of greenhouse gas due to agriculture ? And how this percentage has evolved in the last years ?
* Dividing the set of product between animal products and vegetable products, which group is responsible for the most part of the emissions ? How these emission are distributed around the globe ?
* Focusing on Belgium and switzerland, how does the quantity of imported and exported products have evolved since 2000 ?
* How does their direct emission of CO2 eq have evolved ?
* How can we take into account the emission due to imported product for these two countries ?
* Is it possible to also take the emission to transport all the product for the production country to the importator country ?
* What is the evolution of the real quantity of greenhousegas emitted by the two countries ?

## Dataset
Our first focus point is emissions and environment impact. For that reason we will in a first time mainly focus on those datasets. The idea is also to see how can we incorporate the trading of product to correct the emission of greenhouse gas.

From the UN global food and agriculture statistics, we will use :
 * Emission by Sector
 * Emissions_Agriculture_Agriculture_total
 * Detailed Trade Matrix
 * Population
 

## A list of internal milestones
### For milstone 2

* Data acquisition (03/11):
  * Set up Git and the project structure
  
* Data cleaning (11/11):
  * Downscale the trade matrix dataset to keep only data from Belgium/Switzerland
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
  
### For the final submission

* Add data of transport (1/12):
  * Find a dataset of emission for transport between countries
  * Incorporate this data in ours
  
* Create visulalisation (08/12):
  * Create interactive maps for the direct emissions of each country
  * Create map for the quantity of imported/exported product to/from Belgium and Switzerland
  * Show the evolution of emission with and without correction
  
* Create the website for the datastory (15/12):
  * Set up the website
  * Write all the text
  * Add the visualisations
  
* Last review (20/12):
  * Finalize the data story
  * Clean the notebook

## Structure of the project
```bash
.
|-- README.md
|-- .gitignore
|-- data/
|   |-- CSV file use for the project
|-- generated/
|   |-- Data generated from our analysis
|-- src/
|   |-- Source code files
```

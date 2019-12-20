# How much emission are you REALLY reponsible for

## Abstract

Nowadays, climate change is a global issue and there is a urgent need of more sustainable ways of living. On the other hand, last years, human population has been growing exponentially. Projections of population growth established in 2017 predict that the human population is likely to keep growing until 2100, [https://population.un.org/wpp/Publications/] reaching an estimated 8.6 billion in 2030, 9.8 billion in 2050 and 11.2 billion by 2100. While the earth gets more crowded, we have to ask the question how we will feed all those people sustainably. The Global Food & Agriculture Statistics dataset, provided by the UN, grants over 3 million time-series and cross sectional data relating to food and agriculture. In our project, we ask the question of the impact of our agricultural system on climate change. Our story will start with looking at the global factors and current situation. Later we zoom in on Belgium and Switzerland, and look at their emissions linked with aggriculture. The modern food system is also marked by a lot of trading of goods. The study will then enhance how this trading of food impacts the REAL emissions of those two countries.

## Data Story

Our data story can be accessed via https://reddevilsada.github.io/data_story/

## Research questions

* What is the percentage of emission of greenhouse gas due to agriculture ? And how this percentage has evolved in the last years ?
* Dividing the set of product between animal products and vegetal products, which group is responsible for the most part of the emissions ? How these emission are distributed around the globe ?
* Focusing on Belgium and Switzerland, how does the quantity of imported and exported products have evolved since 2000 ?
* How does their direct emission of CO2(eq) have evolved ?
* How can we take into account the emission due to imported product for these two countries ?
* Is it possible to also integrate into the emissions of the country the ones related to the transport of all the products they import ? How does that affect their emissions ?
* What is the evolution of the real quantity of greenhouse gas emitted by european countries ?

## Dataset
Our first focus point is emissions and environment impact. For this we use data from the UN global food and agriculture statistics
 * Emission by Sector
 * Emissions_Agriculture_Agriculture_total
 * Detailed Trade Matrix
 * Population
 
 Next, to account for transportation of goods, we use the 'EXTRA EU trade since 1999 by mode of transport (NSTR) (DS-022469)' dataset provided by EuroStat (https://ec.europa.eu/eurostat/web/international-trade-in-goods/data/database)
 

## A list of internal milestones

Our final goal is to have a data story that has the following chapters :
* Importance of agriculture in global greenhouse gases emissions and its evolution over the years.
* Importance of vegetal and animal products into agriculture emissions. 
* Emissions of agriculture in each country
* Deeper study on Belgium and Switzerland :
  * Emissions of Belgium and Switzerland
  * Adding the impact of the trading of food goods
  * Adding the impact of the transport of traded food
  * Real emissions of Belgium and Switzerland
* Real emissions of other Regions/ Countries
* Interactive map of real emissions per country  

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
  * Study it's influence on emissions for food products of Belgium and Switzerland


* Get a better estimate of how much CO2 the production caused (5/12)
  * Currently 1kg of Milk, and 1kg of Meat are treated equally (they are simply added together)
  * Find a better way of combining these subcategories, perhaps buy researching how much CO2 each
    subcategory emits and using a weighted sum
  * Have a look at the amount of vegetal products that are actually used for cattle breeding.


* Create visulalisation (08/12):
  * Create interactive maps for the direct emissions of each country
  * Create map for the quantity of imported/exported product to/from Belgium and Switzerland
  * Show the evolution of emission with and without correction


* Generalize the approach for other countries (11/12)
  * Use the same approach as for Belgium and Switzerland but in a more systematic ways on other countries/regions
  * Use that approach to compare countries/regions with our base case
  * Produce a map containing the REAL emissions of each country for food


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

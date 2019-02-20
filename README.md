# ANLY506 Final EDA Project
This is a repository to hold data, code/analysis, outputs and findings for the final ANLY 506 EDA project, which is an analysis of gapminder dataset.

## Project Approach
1. Set up questions for EDA
2. Describe data
3. Explore data
4. Visualize
5. Report findings

## Prerequisites
1. R/R Studio
2. Gapminder dataset
3. Github/Github desktop
4. Basic understanding of R markdown
5. Knowledge of epicycle analysis
6. Knowledge of functions required to perform analysis

## Questions for EDA
1. What are the mean and median life expectancy by region?

## Data Description
1. The dataset used for this project is "gapminder.csv" (source: https://raw.githubusercontent.com/birdsarah/pydata-nc/master/tutorial/assets/gapminder.csv)
2. Data contains demographic information of Life expectancy, Population and Income levels across 197 countries (and their geographical regions), between 1800 and 2015
3. Columns: 
  a) Country
  b) Year
  c) Life
  d) Population
  e) Income
  f) Region
4. Number of observations: 41284

## Data Exploration, Analysis, Visualization
Link to the analysis: https://github.com/richyvarghese/ANLY506_RichyVarghese_FinalProject/tree/master/Code

## Findings
### 1. What are the mean and median life expectancy by region?
Sub-Saharan Africa and South Asia have the lowest mean and median, while Europe & Central Asia has the highest. 
   a) America: mean = 66.9, median = 68.7
   b) East Asia & Pacific: mean = 63.3, median = 63.8
   c) Europe & Central Asia: mean = 69.6, median = 70.2
   d) Middle East & North Africa: mean = 65.5, median = 69.2
   e) South Asia: mean = 54.8, median = 55.2
   f) Sub-Saharan Africa: mean = 53.3, median = 53.3
   
### 2. How does the life expentancy trend change over the course of time across regions?
The life expectancy rate have been increasing over time across regions. Sub-Saharan Africa had a dip around the 2000's possibly due to epidemics/diseases, political turmoil, etc.

### 3. Is there a relationship between life expectancy and income?
As the income increases, the life expectancy seems to increase and vice versa. This could indicate how much importance money plays in today's world to secure basic necessities.

### 3. Is there a relationship between life expectancy and population?
As the life expectancy increases, the population seems to increase. This is true since less mortality will lead to more population.

### 4. For the year 1995, what is the optimal number of clusters?
Using K-means clustering, 4 seems to be the optimal number, while using hierarchical clustering, 2 seems to be the optimal number.

### 5. Based on the K-means clustering output, which cluster is the best and which is the worst?
The cluster with Brunei, Kuwait, Luxembourg, Qatar and Singapore seems to have the highest mean life expectancy, lowest mean population and highest mean income, which make countries in this cluster attractive. Being born and raised in Kuwait, I have experienced the quality of life, higher incomes and lower mortality rates, and hence confirms this result.
India has its own cluster with lower mean life expectancy, highest mean population and very low income, which forces their work force to migrate to other countries to imporve their work and life standards. Being an Indian citizen by origin, and living in India for a few years, I believe this is true, as like many others I have moved to the US in search of better opportunities, standard of living, income and lower population per region (as compared to India). 

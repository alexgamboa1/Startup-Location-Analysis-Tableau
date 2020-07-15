# Startup-Location-Analysis-Tableau
Analyzed nationwide stores performance and marketing spend using Tableau. 

In this role, I was given the task of being a Data Scientist working for a laundry pickup service startup We Wash You Sleep. They are a small company and they cannot compete with the big players in major cities. The company strategy is to build a vast network in the smaller cities across the United States. 

The company has 140 locations and have recently opened stores in 10 new cities. Additionally the company has two seperate sales regions. 

###Goal of the Project 
1. Identify which of the two sales regions is performing better (outperform the other in 2 of the 3 metrics): 
  - AVG revenue per city 
  - AVG marketing spend per city (less is better) 
  - AVG ROMI per city (revenue/marketing spend) 
  
2. Identify which of the 10 new locations have the best potential for the company to invest more of its funds into marketing. 

Data: startupExpansion.xlsx and included US-Cities-Population.csv for more information on Store performance based on location. 

# Tableau Analysis: 

## Sales Region Analysis: 
In order to find out which region of the company's locations was best performing I had to identify the sales region and group them together. I did this by selecting the Sales Region and creating a group by selecting all states within the specific region. Once I had group the regions by state I then found the average revenue, average marketing spend, and calculated the ROMI (revenue/marketing spend) and add it to their respective regions. 

**Outcome:** Region 1 outperformed region 2 by having more average revenue per city and by having a better return on average dollar spend (ROMI). 

## Revenue Map
I then created a map that showed a representation of revenue from each city in comparison to one another with a color scale to show the differentiation. 

## Location Analysis of Revenue/ Marketing Spend 
I grouped together the Store ID and created a scatter plot based off the Sum of Revenue and Sum of Marketing Spend to find a understanding of where the different stores matched up against one another. I added a highlighted new expansion option so that you can review the 10 new stores in comparison to the other stores nation wide. Each point on the scatter plot gives you store specific details and performance. 

## Revenue / Marketing Spend Cluster Trend Line 
I thought that there could be more that made each location have better metrics and performance so I added US cities population into the analysis. I used the same clustering of the Stores revenue and marketing spend performance but now I added population in reference to the City the Store ID matched with. I then created a trend line by each cluster based off Tableau Statisical Analysis capabilites to find which cluster gained the most revenue per dollar spent on marketing. I then added the highlight new expansion feature to distinguish which stores on the scatter plot were the 10 new stores. 

**Outcome:** Based on the scatter plot stores located in the orange scatter plot had the best performance in revenue for every dollar spent compared to the other clusters of stores. For every dollar spent on marketing the store would produce $7.32. You can view this by hovering over the orange trend line in tableau. Once you use the new expansion feature to find which 10 stores just opened; 4 out of the 10 stores are located in the orange cluster. Based upon this analysis it would be recommended for the company to invest more funds into marketing out of those 4 stores. 

## Map of Revenue Clusters
In order for you to visualize the different store locations with the knowledge and understanding we have gained from the Revenue / Marketing Spend Cluster Trend Line chart I added that information to the geographical location a long the United States to evaulate the different Store locations and revenue metrics. 








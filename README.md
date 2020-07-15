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







# Which State is the Best to Live In?

The purpose of this project is to analyze which state would be best to live in based on three metrics: cost of living, healthcare costs, and crime.

### Technologies Used
* Python
* Pandas library
* Matplotlib
* Hvplot

### Datasets Used
Crime: FBI Homicide data for the year 2021. Accessed via the FBI Crime Data API on August 2, 2023.
  - The API returns total homicides, we used census estimates for state populations in 2021 to calculate homicide rate per 100,000 people. The dataset and estimate methodologies are available at https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html. The data was accessed on July 28, 2023.
Healthcare Costs: Forbes Advisor Analysis of Kaiser Family Foundation data on healthcare costs for the year 2020. Scores were given to each state from 0-100 with 0 being the lowest healthcare cost. CSV file and methodologies are available at https://www.forbes.com/advisor/health-insurance/most-and-least-expensive-states-for-health-care-ranked. Accessed July 20, 2023
Cost of Living Index: World Population Review data on cost of living in the United States in 2023. Each state is given a score against the national average baseline, which is set at 100. Methodologies and dataset are available at https://worldpopulationreview.com/state-rankings/cost-of-living-index-by-state. Accessed July 20, 2023.

### Main Questions and Images of Findings
Each metric is analyzed through a series of bar graphs, pie charts, scatterplots and correlations to explore relationships between the metrics and learn more about the states. The most important part is when the three metrics are weighted and compiled into a score to assist in determining which state would be the best to live in. The determination of which states are better suited for individual preferences depends on the values one places on different aspects of life. For some, a lower cost of living may be a priority, leading them to favor states that offer economic advantages. Others might prioritize safety and, thus, prioritize states with lower crime rates. Additionally, those who highly value healthcare quality may prioritize states that excel in healthcare services. This analysis has provided a comprehensive overview of the factors influencing state comparisons, allowing individuals to make informed decisions based on their unique priorities and preferences. Ultimately, the best state for one person may not be the same for another, making it essential to consider personal values when evaluating the data presented. 
The code shows four different scenarios, one in which all three metrics are weighted evenly, one for each metric given priority. Results are displayed in an interactive map of the top five states that fit the desired characteristics. 

<img width="540" alt="image" src="https://github.com/hrollin5/project_one/assets/130103105/d00df7f5-24aa-4baf-8c2b-22407d92c806">



  

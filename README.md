# FINAL_Project_1_T3
Group 3 Members: Oana Wright, Frank Guerra, Zach Hooks, Aislinn Yeidel, Brian Hart

- Overview - Group 3 used a data set from Washington consisting of population data for Electric Vehicles in the state. We then analyzed the following considerations:
  - I. Popularity of EV Models & Correlation between EV count per model and electric range
  - II. Correlation of EV count per county and median income
  - III. Correlation of EV count per county and population size
  - IV. Concentration of cars per count (includes map)
  - V. Correlation of EVs by city & EV charge stations by city
  - VI. Trend of EV purchase activity over the past 15 years (2010-2024)

- Findings
  - I. Popularity of EV models and Correlation of EVs and Electric Range
    - After looking at all EV Make+Model registered in the State of Washington and making a histogram of the EV count per Make+Model it can be conluded that Tesla Model Y and Model 3 are at the top of the list, making more than 50% of the top 15 popular cars.
    - The Make+Model count was then correlated with the Average Electric Range. For that a summary statics was conducted to make sure the the standard error was less than 0.1. The correlation between the Average Electric Range and Make+Model count resulted in an r^2 value of 0.22. While it's not very high, 22% suggests that the model explains some variability, but there’s a significant amount of unexplained variance (78%). This means other factors or variables not included in the model may play a role in influencing the "popularity" of EVs.
  
  - II. Correlation of EV count per county and median income
      - Multiple sources of data were compiled together to create a scatter plot that shows whether or not there is a tangible relationship between electric vehicle ownership and income. Another scatter plot was made to determine the relationship between electric vehicle ownership and total population of adults in each county in Washington. After analyzing the data, there does seem to be a positive correlation between the number of electric vehicles and higher incomes, as well as a higher concentration of electric vehicles in more densely populated areas. There are a few reasons why this relationship is prevelent.
      - The first indicator that a person is more likely to own or purchase an electric vehicle is their income. Higher incomes correlate to higher rates of electric vehicle ownership because electric vehicles are on average more expensive than gasoline vehicles, making them harder to access for people who have lower incomes.

  - III. Correlation of EV count per county and population size
    - The second indicator that a person is more likely to own or purchase an electric vehicle is their location. Specifically larger, more densely populated counties have higher rates of electric vehicle ownership. This is due to a few reasons, including one that has been already discussed: income. It is shown in the data that the largest counties in Washington also have the highest median income, which is related to ev ownership. However, it can also be speculated that people in smaller, less densely populated counties choose not to own an electric vehicle due to its known unreliability in areas with poor internet connection, or the lack of charging stations available in those smaller counties. Further analasis would be needed in order to verify these hypotheses.
  
  - IV.
  
  - V. Correlation of EVs by city & EV charge stations by city
    - Top 10 Cities: EVs per Charging Station
      - Seattle leads in EV-to-charging-station ratios, with each station supporting 33,944.52 EVs, followed by Bellevue with 10,414 EVs per station and Vancouver with 7,577 EVs per station. These high ratios imply that while Seattle has many connectors, its stations still face significant demand, likely leading to congestion. Bellevue and Vancouver are also under pressure, as the high EV counts per station show potential for bottlenecks, especially during peak usage times. This underscores a need for additional stations or faster-charging options, particularly in these high-density cities, to reduce wait times and enhance accessibility for EV drivers.
    - Top 10 Cities: Charging Connectors by Type
      - Seattle overwhelmingly leads in total charging connectors, with 63,944 Level 1, 76,150,708 Level 2, and 6,036,339 DC Fast connectors, far surpassing other cities. The majority are Level 2 connectors, providing a medium-speed option that balances charging time and availability. Bellevue, Vancouver, and other cities in the top 10 show significantly fewer connectors, suggesting a disparity in infrastructure availability. This dominance in connector count, particularly in Seattle, reflects the city's commitment to supporting a growing EV population, though it indicates that other cities will need to expand their infrastructure to keep pace with EV growth.
  
  - VI. Trend of EV purchase activity over the past 15 years (2010-2024)
    - There has been a steady rise in electric vehicle (EV) purchases in Washington over the past 15 years, highlighting a strong trend toward sustainable transportation. From 2010 to 2024, EV sales increased by 211.07%, with a high correlation coefficient of 0.90 indicating a clear, consistent upward trajectory. The compound annual growth rate (CAGR) of 46.61% further underscores robust, compounding growth in EV adoption across the state.
This rapid expansion likely stems from several factors: technological advancements, increased charging infrastructure, and favorable state policies, such as tax incentives. Together, these factors have lowered the barriers to EV ownership, making it more appealing and accessible to Washington residents. Given these indicators, EV sales in Washington are likely to continue on this upward trend, reflecting broader shifts toward sustainable energy and clean transportation solutions.







Data Sources:
- Electric Vehicle Populatio Data: https://catalog.data.gov/dataset/electric-vehicle-population-data/resource/fa51be35-691f-45d2-9f3e-535877965e69
- Electric Vehicle Title and Registration Activity: https://catalog.data.gov/dataset/electric-vehicle-title-and-registration-activity/resource/d045f505-3b06-4471-953c-1a754c295a9c
- Alternative Fuels Data Center: https://afdc.energy.gov/fuels/electricity-locations#/find/nearest?fuel=ELEC
- Income for Washington Counties: https://hdpulse.nimhd.nih.gov/data-portal/social/table?age=001&age_options=ageall_1&demo=00011&demo_options=income_3&race=00&race_options=race_7&sex=0&sex_options=sexboth_1&socialtopic=030&socialtopic_options=social_6&statefips=53&statefips_options=area_states
- Population for Washington Counties: https://hdpulse.nimhd.nih.gov/data-portal/social/table?age=999&age_options=ageNA_1&demo=00102&demo_options=pop_12&race=00&race_options=race_7&sex=0&sex_options=sexboth_1&socialtopic=070&socialtopic_options=social_6&statefips=53&statefips_options=area_states

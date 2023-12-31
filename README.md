
# Global COVID-19 Vaccine Tracker💉🌍

This project creates an interactive Tableau dashboard tracking global COVID-19 vaccination progress. The dashboard provides insights into:

- Vaccination rates by country.📈
- Correlations between GDP and vaccination rates.💰💉
- Overall global vaccination milestones.🌎
- It includes filters to analyze trends by location, date range,  and other parameters.🗺️📅


## Screenshots

![covid project](https://github.com/jatinkam/Covid-19-Global-Vaccine-Tracker-Dashboard/assets/113269173/6a4da8c4-27ee-4504-9309-ae41447c7c74)



## Usage💻

To use this dashboard:

1. Install Tableau Desktop.🖥️
2. Connect to the owid-covid-data.csv dataset.📊
3. Open the Covid-19-Global-Vaccine-Tracker-Dashboard.twbx Tableau workbook.📈
4. Interact with dashboard visualizations and filters.🎛️


## Data 📊
Dataset Links:
https://ourworldindata.org/covid-vaccinations

The owid-covid-data.csv dataset contains the following important columns:🗂️

- location - The country name. 🌏
- date - The date of the data point. 📅
- total_vaccinations - Total COVID vaccination doses administered. 💉
- people_vaccinated - Total people who received at least one dose. 💉
- people_fully_vaccinated - Total people fully vaccinated. 💉💉
- total_boosters - Total booster doses administered. 🔁
- population - Population of the country. 👨‍👩‍👧‍👦
- gdp_per_capita - GDP per capita for the country. 💰
- new_vaccinations_smoothed - Smoothed average of new vaccinations. 📈
- total_vaccinations_per_hundred - Total vaccinations per 100 population. 💯
- people_vaccinated_per_hundred - People partially vaccinated per 100 population 💯
- people_fully_vaccinated_per_hundred - People fully vaccinated per 100 population. 💯

It contains country-level COVID-19 vaccination data from October 2020 to July 2023. The key metrics are vaccination counts, rates per population, and GDP per capita. 📊

This allows dashboard insights into:

- Overall vaccination rates globally and by country. 🌎🌍🌏
- Vaccination milestones reached. 🎉
- Correlations between country wealth and vaccination rates. 💉
## Dashboard Overview 📊
The dashboard contains:
#### KPIs 📈
- % Population Partially Vaccinated
- % Population Fully Vaccinated
- % Population Unvaccinated

#### Vaccinations by Country 🌎
- Bar chart comparing partial vs full vaccination rate by country. 📊
- Map shading countries based on vaccination rate. 🗺️

#### Vaccinations vs GDP Per Capita 💰
- Scatterplot showing correlation between GDP per capita and vaccination rate. 📈

#### Filters 🗃️
- Country 🌍
- Continent 🌎
- Start and end date ⏱️
## Visualization Details 📈
The KPI cards show the percentage of the global population with partial, full, and no vaccination. 🗺️

The country comparison chart is a dual-axis bar chart sorted by partial vaccination rate. The map colors countries based on vaccination percentage. 🗺️

The scatterplot includes a trendline showing the relationship between wealth (GDP per capita) and vaccination rate. 💰📈

All visualizations update based on the filter selections. 🗃️

#### Dependencies
- Tableau Desktop 🖥️
- CSV dataset provided 📄


## Conclusion 📈
This Tableau dashboard provides an effective overview of global COVID-19 vaccination progress. The visualizations and filters allow for insights into country vaccination performance, demographic impacts, and correlations with economic factors. 💉🌍

Key findings include:

- Wealthier countries have achieved higher vaccination rates, suggesting disparities in access to vaccines globally. 💉💰
- Vaccination rates vary widely between continents, with Europe leading and Africa lagging.🌍🌎
- Countries with older populations have focused vaccination efforts on booster doses rather than initial shots. 👴👵
- Global vaccine rates are plateauing below 70% fully vaccinated, indicating additional efforts are needed to reach herd immunity. 📉

By visualizing vaccination metrics across countries and time, this dashboard highlights insights to help inform public health policy and resource allocation related to COVID-19 vaccines. 💉📊 The data could be expanded to include additional demographic, health, and economic indicators for further analysis. Overall, this project demonstrates how interactive dashboards can turn complex public health data into accessible, actionable visuals. 📈🎛️
# Analyzing-Global-Power-Plant-Database

# Introduction
In this analysis, I am going to use a power plant dataset. The dataset contain information of verious type of power plant around the world such as thermal plants (e.g. coal, gas, oil, nuclear, biomass, waste, geothermal) and renewables (e.g. hydro, wind, solar). The database includes nearly 30,000 power plants from 164 countries.

# Data Source:-
The database is accessible via the WRI Open Data Platform for download and use. https://datasets.wri.org/dataset/globalpowerplantdatabase or https://www.kaggle.com/georgeputhean/globalpowerplantdata

# Exploratory Analysis and Visualization
Let's look up at top 20 countries with heights amount of power plants. We can calculated the total amount of power plant by count the country name.

The method value_counts() is use to count the total amount of time a country name is appear in the datafram and head(20) to get the top 20.
![1](https://user-images.githubusercontent.com/77172036/160202226-765641cd-d8c2-40ce-8850-30fcbb050b0e.png)

# Fuel use in power plant.
Various types of fuel are used in the power plant, which can be classified as primary fuel, other fuel-1, other fuel-2, etc. Primary fuel is used to run the main turbine to generate electricity and other fuels are used to run auxiliary machines to support the generation process.


![2](https://user-images.githubusercontent.com/77172036/160202402-c7085663-791f-4f0d-a950-0ce9577212d3.png)
# Generation of power in USA, India and Australia during 2013, 2014, 2015, 2015, 2017.
In the generation gwh column, many year has missing data (e.g. generation gwh 2013 has 22914 nun value from 29910 column). So, in order to compare the generation amoung different year, it is appropriate to select some countries which data are present in the five-year period. The United States of America, India and Australia are selected for this of scenario.

![3](https://user-images.githubusercontent.com/77172036/160202534-851660d9-a2e3-433c-a1be-c4e51bd208d8.png)

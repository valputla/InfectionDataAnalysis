![ReadMephoto](https://user-images.githubusercontent.com/93561950/163493317-fc706fc6-d6d8-477b-a6ad-cc177551bd21.png)
# Infection Data Analysis
# Vishaal Gupta, Lindsey Morales, Atika Hemani, Isaac Rosenthal
## Project Objective
The purpose of this project is to examine COVID-19 Deaths, Influenza Deaths, and Pneumonia Deaths in the United States spanning from Jan 2020-March 2022. We decided to compare the number of deaths by age group, gender, and state. This gave us insights on what correlations can be drawn from our data. Additionally, we wanted to see how COVID-19 and Influenza differed, due to many individuals stating "COVID is just the flu". 
## Methods Used
- Various Plotting Methods (Scatterplots, Barplots, and Piecharts) 
- Linear Regression 
- Data Visualization

## Technologies
- Python 
- Matplotlib 
- Pandas
- Seaborn
- Numpy
- Scipy.Stats

## Featured Notebooks and files
**CovidDeathRateAnalysis.ipynb** 
- Using Pandas and visualization packages, to look at COVID-19, Influenza, and Pneumonia deaths in the US and Puerto Rico from 2020-2022. This notebook starts off by cleaning the data and exploring what variables we have. This data exploration helped with creating meaningful visualizations, in order to tell a story about COVID-19 and the differences & similarites with Influenza and Pneumonia. This is our final notebook.

**Resources Folder**

**Images**
- This folder holds all of our graphs we made in order to showcase our data. There a variety of different types of plots looking at various compenents of our dataset. 

**Provisional_COVID-19_Deaths_by_Sex_and_Age.csv**
- CSV file with our raw data. It looks at COVID-19, Influenza, and Pneumonia deaths by state, age group, gender, and month/year.

## Analysis and Observed Trends

**Correlation Graphs and Trends**

A strong correlation was observed between Age Groups & COVID-19 Deaths in the US. This suggests the older you are, the risk of dying from COVID-19 is higher. This makes sense due to comorbidities of other diseases and differences in immune systems.
![AgeVsDeaths](Resources/Images/AgeVsDeaths.png)

A correlation coefficient of .724 was observed between Influenza & COVID-19 Deaths in the US. Although there is a strong correlation, the graph shows us that there are more COVID-19 Deaths than Influenza. This highlights how severe COVID-19 is compared to Influenza.
![influenza/covid/corr](Resources/Images/influenza_covid_corr.png)

Additionally, a correlation coefficient of .9985 was observed between Pneumonia & COVID-19 Deaths of all the states in the US. This shows how severe both of these diseases are and how they ultimately lead to death if not treated.
![pneumonia/covid/corr](Resources/Images/pneumonia_covid_corr.png)

The SEM value for the sample Influenza Deaths is 0.515

![semflu](Resources/Images/SEMFlu.png)

The SEM value for the sample Pneumonia Deaths is 27.09. 

![sempneumonia](Resources/Images/SEMPNA.png)
# Suggestions for Further Analysis
- Compare the deaths of COVID-19 looking at pre & post vaccine rollout
- Additionally, using the information we have on COVID-19 Deaths for the US and compare this to another dataset looking at other countries
- Also, we could look at correlation of COVID-19 Deaths and red/blue states


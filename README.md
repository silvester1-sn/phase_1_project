# phase_1_project 
# Aviation Accident Analysis
# Overview
This project provides a data-driven analysis of aviation accidents to help stakeholders determine which aircraft are low risk and viable investment to purchase for commercial and private enterprises diversifying the companies portfilio expanding to the aviation industry.
# Business Understanding
- Frequency occurance of accidents
- Key factors affecting accident rates
- Level of aircraft damage in Purpose.of.flight
- Serverity of accident(fatality and survival)
- Least involved make in accidents
# Data understanding
Analysis sourced from [Aviation_Data.csv] dataset provided by the National Transportation Saftey Board containing aviation accidents data from 1962-2023 in the United States and international waters.
# Key data fields
- Accident.Number
- Event.Date
- Amateur.Built
- Weather.Condition
- Aircraft.damage
- Purpose.of.flight
- Total.Fatal.injuries
- Total.Serious
- Total.Minor.Injuries
- Total.uninjured
- Make
# Analysis
# Data cleaning 
Setup
   - Handlig missing data
   - Removing duplicated entries
   The column Accident.Number is best to identify and remove any duplicated values in the dataset considering its distinct uniqueness.
   - groupby Accident.Number by 5years in Event.Date
   Grouping the filtered dataset into groups of 5 years to narrow down the large dataset and provide clarity for easy evaluation.
   Creating a column in the dataset to display counts of each row o the Accident.Number as per every year_group for easier comprehension of the dataset
# Modelling
   # Exploratory Data Analysis
   In this section , use of Numpy and pandas will be essential to answer the stakeholders questions under business understanding.
Matplotlib and pivot tables are used for visualisation.
   - Frequency of accidents per year_group
   - Visualisation of the frequency of accidents as per every year_group.
Considering the data from the frequency of accidents is not recognised as a dataframe by the library. To plot extract the frequencies as data for dataframes. 
- Factors affecting accident rate
Filtered Amateur.Built has No to represent Aircrafts not bult for the first time. This information is crucial for finding the number of accidents on every weather condition.
- Level of aircraft damage
The stakeholders are looking to invest in purchase of commercial and private eneterprises planes .This is best represented by 
  - 'Personal'
  - 'Business'
  - 'Executive'


in Purpose.of.flight
Create a pivot_table to display number of aircrafts to be invested in damage levels.
- Serverty of accidents
- Least accident involved make
Least make and model of aircraft determined by the number of accidents incurred and total number of injuries on the accident.
   # Data visualisation
   Alink for the Tableu dashboard
   https://public.tableau.com/app/profile/silvester.nyachieo/viz/Book1_17619405980660/AviationAccidentsOverview?publish=yes

# Conclusion
Through filtering and EDA analysis of the dataset the planes of make :Make CESSNA , New Piper Aircraft, Inc. ,COLUMBIA , STARDUSTER II , Cessna ,Cessna  and model:Model 421, PA-46-350P, LC41, SA-300, 337DA150L  respectively had the least number of accidents in relevance to total injuries,investors purpose of crafts and severity of damage of craft crashed.     
  # Recommendation     
  Would definetly recommend purchase of 
- New Piper Aircraft,Inc.  model:PA-46-350P
- COLUMBIA.                model:LC41
- STARDUSTER II.           model:SA-300


.For startup venture into the aviation industry.





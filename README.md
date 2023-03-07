# Group Project

- Institute: Monash University, Clayton

- Subject: ETC5510 - Introduction to data analysis - Semester 1 2021

- Team name: T12_Fri_kable

# Table of Contents

|                   | |
|--------------------------|:---:|
| Project Details     |     | 
| Project Details for reproducible report        |     | 
| Goals of Project           |     | 
| Data set details          |     |
| Credits   |     |



# Project Details
- Name: Analysis on Human Development Index 2019

- Objective: Answering research questions about HDI value, HDI rank(2019, 2018)and SDGs (Sustainable Development Goals) 3,4,5 (2019), where SDG 3 = Life expectancy at birth, SDG 4.3 = Expected years of schooling, SDG 4.4 = Mean years of schooling, SDG 8.5 = Gross national income (GNI) per capita.


- Date set used from : United Nations Development Programme, Human Development Reports (http://hdr.undp.org/en/composite/HDI).


# Project details for producing reproducible report:

Technology used :

- R version 4.0.5

- GitHub

To run the project :

- Download the project

- Knit 'Kable_report.rmd' for reproducing the report

- Knit 'Kable_FlexDash.Rmd' for reproducing flexdashboard

OR

- Open 'Kable_report.html' and 'Kable_FlexDash.html' for viewing report and presentation.


To view the data separately:

Data location -> 'Data' Folder  -> Open file 'HDIData.csv'.

- The project folder contains 'Data_cleaning.Rmd' where data has been cleaned and its html can be viewed as well (Data_cleaning.html)

# Goals of Assignment - Answering the following research questions:

- To compute the summary statistics for each variable for every Human Development category.

- To compare and contrast the GNI columns for very high and medium development countries and to conduct an analysis to assess whether the very high development countries translate their income better than the medium development countries in the areas of human development.

- Calculate the gap between the ‘expected years of education’ and the ‘average years of education’ for countries with different levels of Human Development, to analyze if countries with high levels of human civilization are estimated to have high levels of expected education. Therefore, judge if it is inaccurate to use the ‘average value of expected years of education and average years of education’ for the calculation of HDI.

- Compare and contrast HDI ranks for 2018 and 2019 i.e. compare ranks for countries and examine their decline or increase in HDI rank from 2018 to 2019.


# About the dataset and variables

The Human Development Index (HDI) is a statistic composite index of life expectancy, education (mean years of schooling completed and expected years of schooling upon entering the education system), and per capita income indicators, which are used to rank countries into four tiers of human development.

- **HDI_rank_2019**: A composite index measuring average achievement in three basic dimensions of human development; a long and healthy life, knowledge and a decent standard of living.

- **Country** : List of countries for which HDI statistics are calculated.

- **HDI_Value**: Summary measure of average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and have a decent standard of living

- **Life_expectancy_at_birth**: Number of years a new-born infant could expect to live if prevailing patterns of age-specific mortality rates at the time of birth stay the same throughout the infant’s life.

- **Expected_years_of_schooling**: No. of years of schooling that a child of school entrance age can expect to receive if prevailing patterns of age-specific enrolment rates persist throughout the child’s life. 

- **Mean_years_of_schooling**: Average number of years of education received by people ages 25 and older, converted from education attainment levels using official durations of each level.

- **GNI_per_capita**: This is 'Gross National Income' per capita. This is the aggregate income of an economy generated by its production and its ownership of factors of production, less the incomes paid for the use of factors of production owned by the rest of the world, converted to international dollars using PPP(Purchasing Power Parity) rates, divided by midyear population.

- **GNI_per_capita_rank_minus_HDI_rank**: Difference in ranking by GNI per capita and by HDI value. A negative value means that the country is better ranked by GNI than by HDI value.

- **HDI_rank_2018**: Ranking by HDI value for 2018, calculated using the same most recently revised data available in 2020 that were used to calculate HDI values for 2019.

- **Degree_of_Human_Development** : The cutoff-points are HDI of less than 0.550 for low human development, 0.550–0.699 for medium human development, 0.700–0.799 for high human development and 0.800 or greater for very high human development.

# Credits  :
- Author1 (Section 2.2): "Xiaoyu Tian"

- Author2 (Section 2.4): "Nishtha Arora" 

- Author3 (Section 2.3): "Shaohu Chen"

- Author4 (Section 2.1): "Nurlaily Furqandari Suliana"


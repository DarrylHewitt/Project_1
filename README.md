edit as csv
# Project_1
Bootcamp: Project 1
# PROJECT TITLE: : Exploring Trends in Crime Data in Birmingham between Aug 2020 – Jul 2023

By Kaj Kabilan, Darryl Hewitt, Mushfiqur Rahman and Suwaiba Idris

## Purpose of the Project
Examine how different crimes vary throughout the year and determine seasonal patterns in crime types. Focus will be on time-series analysis, seasonal decomposition and data visualisation. The data we have from https://data.police.uk/ is of street crimes hence we are looking only at those crimes.

### Research Question 1 : What are the street crime types that occur in Birmingham? Where are the local police stations situated?

![Alt text](image-26.png)

The table above shows the Police Stations in Birmingham and their locations (longitude and latitude)

Using Police data we were able to extract the different types of street crimes as well as the crime counts that occurred in Birmigham over the 3 year period as seen above.
The graph below show a rise in crime rates in the month of July and a decline in the month of February accross the years. The graph also shows a decline in crime rate in the summer of 2023.

![Alt text](image.png)

![Alt text](image-19.png)

The above bar graph displays crime count in Birmingham by type. We notice the majority crime in Birmingham is violence and sexual offences.

![Alt text](image-20.png)

The pie chart above displays the same information and it shows at 42.7% the major crime is violence and sexual offence and the least occuring crime is bycicle theft.


### Reseach Question 2 : What is the correlation between crime count and the Index of Multiple Deprivation (IMD) score? How does the type of crime relate to the IMD score?
Hypothesis: There is a significant correlation between crime count and the Index of Multiple Deprivation (IMD) score in Birmingham.

![Alt text](image-2.png)

Above scatter plot showing total crime count in the LSOAs of Birmingham versus the crime counts in the City. In the above the plot we can see the linear line of regression showing a positive correlation of moderate value. This plot shows results that may support our hypothesis.

![Alt text](image-6.png)

![Alt text](image-8.png)

![Alt text](image-9.png)

![Alt text](image-10.png)

![Alt text](image-14.png)

![Alt text](image-16.png)


Scatter plots showing relationship between the LSOA crime count of Birmingham and IMD scores against anti social behaviour, criminal damage, violence and sexual offences, possession of weapons, public order, other crimes and drug related crimes. The r-values in these graphs show a weak positive correlation which is in line with our hypothesis.

![Alt text](image-3.png)

![Alt text](image-12.png)


The linear line of regression for anti social behaviour and robbery against IMD scores has a weak positive correlation.

![Alt text](image-4.png)

![Alt text](image-5.png)

![Alt text](image-13.png)

![Alt text](image-17.png)

The scatter plots above show very weak correlation between the crime counts of vehicle crime, burglary, "other theft" and theft from a person in relation with the IMD scores of the different LSOAs in Birmingham. 

![Alt text](image-15.png)

![Alt text](image-18.png)

In this plot we see a weak negative correlation between the bycicle theft and shop lifting  in the LSOAs of Birmingham and  the IMD scores. The negative correlation in shop lifting could be explained by the distribution of shops in the city, where they tend to be more concentrated in the city centre area where the IMD scores are moderate.


### Research Question 3 : What are the top 20 locations with the highest crime counts, and what are their corresponding IMD scores? Conversely, what are the 20 locations with the lowest crime counts, and what are their IMD scores?
![Alt text](image-22.png)

This map displays the top-20 LSOAs for crime counts across Birmingham. The legend displays a unique colour for each LSOA. The hover labels in the jupyter notebook contain the latitude, longitude, LSOA name, crime count, and IMD score.
The city centre of Birmingham and neighouring inner-city suburbs claim the overwhelming majority of crimes committed.

The IMD score for the top-20 ranges from 20 - 60. Therefore, it is clear that IMD alone does not account entirely for crime counts.


![Alt text](image-21.png)

North Birmingham, Sutton Coldfield and Four Oak recordede the least crimes.
Several LSOAs in the top 20 are located some distance from the centre. These locations are in close proximity to town centres, and 096A has a thriving student community.
The IMD score for the bottom-20 ranges from 3 - 20. There is less disparity in IMD score amongst the bottom 20 than there is among the top 20.


### Research Question 4 : Do crime rates exhibit seasonality, with lower street crime rates during winter months (October to March) compared to summer months (April to September)?

![Alt text](image-23.png)
The stacked bar chart displays crime counts for the different crime types. There is very little variation in crime count across the diferent types.Crime counts during the winter months decline from November to February with the exception of January 2023. 

![Alt text](image-24.png)

The months of June and July of 2021 and 2022 see the highest crime count whereas 2023 has the highest crime count in January. 
Both the summer and winter months' crime counts show difference in the pattern of recorded crime in 2021 and 2022 from 2023. Further analysis wil need to be done to determine the factors affecting this result. In addition we were limited to a 3 year dataset which confined the scope of our analysis.

![Alt text](image-25.png)

The comparative bar chart above shows that, over the three years, summer has more crime than winter with the exception of burglary. Further analysis could determine whether the higher burglary rate in the winter could be due to longer nights.

## Conclusion

Birmingham has 30 Police Stations accross the city.The police data shows a record of 14 different street crime types.

Our findings show that IMD scores alone can not be used to determine the crime counts in an area, other factors such as proximity to the city centre and type of crime play a role as well. 
The city centre of Birmingham and neighouring inner-city suburbs claim the overwhelming majority of crimes committed.

Several LSOAs in the top 20 are located away from the city centre although these locations are in close proximity to town centres. The IMD score for the top-20 ranges from 20 - 60. Therefore, it is clear that IMD alone does not account entirely for crime counts.

Violence and sexual offences make up the majority of crimes committed through out the year.There is no significant variation in crime count across crime types over the three years.

The summer months experience a slightly higher crime count than winter.

## Implications


It would be interesting to further examine what types of crimes are prevalent at different LSAO locations to determine what other factors contribute to the crime count.

Shoplifting saw a steady drop from 2020 to late-2021 further analysis would be needed to determine the cause or causes.









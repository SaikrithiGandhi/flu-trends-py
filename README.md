# US Flu trends 2010-2016

After many news reports of deaths due to the harsh flu season this year I decided to statistically analyze how bad this year’s flu was. Using R and python I analyzed flu trends from 2010-2016 with data from CDC. I have also combined it with immunization statistics from BRFSS dataset to compare the immunization trends with flu-related deaths.

## Some results

### Flu trends
-  California trends for death are decreasing year-on-year.
- The national average is also slightly decreasing. 
- 2013 was a bad flu season compared to the others as the death rate was slightly more than the other years.

### Immunization trends
- We looked at the immunization trends across various states for 2013 based on survey data. South Dakota had the highest immunization record of 56%. Alaska, Nevada, Idaho were the least immunized states with less than 40% immunization.

### Relation between flu deaths and immunization
- South Dakota has the highest immunization rate -- 56.4 it also has a high death rate due to the flu -- 9%.
- Vermont has the second highest death rate (after NYC) despite an immunization record of over 50%.
- The flu shot percent and death percent does not show a good relation for 2013. It is possible that the flu vaccine for 2013 was not very effective. Therefore there were more deaths despite immunization.

**Methods** Descriptive statistics, Pearson correlation coefficient, visualization.

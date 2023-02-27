# Disability and Cardiovasular Disease Analysis

Data Sources Disability and Health Data System (DHDS) 

Source: https://data.cdc.gov/Disability-Health/Disability-and-Health-Data-System-DHDS-/k62p-6esq

The first dataset is the Disability and Health Data System (DHDS) which is an online source of state-level data on adults with disabilities. 
This dataset has been provided by Centers for Disease Control and Prevention, National Center on Birth Defects and Developmental Disabilities. 
This data can be exported in .csv format, although it will require concatenation to develop a longitudinal dataset. 
Through this dataset, we can access information on six functional disability types: cognitive (serious difficulty concentrating, remembering, 
or making decisions), hearing (serious difficulty hearing or deaf), mobility (serious difficulty walking or climbing stairs), vision 
(serious difficulty seeing), self-care (difficulty dressing or bathing) and independent living (difficulty doing errands alone). 
This dataset contains 546K rows and 32 columns most important being Year, location_description containing names of states across US, 
data_value containing prevalence percentages (prevalence is the proportion of a population who have a specific 
characteristic in each time period [2]), Stratification1 containing disability type and stratification2 containing demographic variables.
Within the year column in this dataset, the values range from 2016 to 2020 which has been filtered to use data from 2016 to 2018 
so that both datasets can be concatenated.

Behavioral Risk Factor Surveillance System (BRFSS) - National Cardiovascular Disease Surveillance 

Data Source: https://chronicdata.cdc.gov/Heart-Disease-Stroke-Prevention/Behavioral-Risk-Factor-Surveillance-System-BRFSS-N/ikwk-8git

The other dataset is based on cardiovascular diseases and risk factors associated with it. 
The Behavioral Risk Factor Surveillance System is a continuous, state-based surveillance system that collects information about 
modifiable risk factors for chronic diseases and other leading causes of death. This is one of the datasets provided by the National 
Cardiovascular Disease Surveillance System. This data can be exported in .csv format, although it will require concatenation to develop 
a longitudinal dataset. The data are organized by location (national, regional, state, and selected sites) and indicator, and they include 
CVDs (e.g., heart failure) and risk factors (e.g., hypertension). The data can be plotted as trends and stratified by age group, sex, and 
race/ethnicity. This dataset contains 126K rows and 30 columns most important ones being Year, location description, break_out_category 
containing the demographic variables, topic specifying the type of risk and data_value containing the risk percentages. Within the year 
column in this dataset, the values range from 2011 to 2018 which has been filtered to use data from 2016 to 2018 so that both datasets 
can be concatenated.

## Analysis and Visualization: 

Task 1: Determine the trend of risk and prevalence percentages experienced by individuals with hearing disability who are 
at some kind of risk (hypertension, diabetes, etc.).

Interpretation: It can be seen from this task that 38.5% of the population (prevalence percentage) who have hearing disability are at a 71.86% risk due to physical inactivity which is the highest in case of hearing disability. People with hearing disability are at least risk of diabetes with a risk percentage of 16.4% for 38.5% of the population with hearing disability.

Task 2: Calculate the male to female ratio based on aggregated risk percentages for each state in the United States such that it shows the gender distribution of the state whose individuals are at a comparatively higher risk (based on prevalence percentage).

Interpretation: It can be interpreted from this table that 22% of males and 21% of females in New Mexico of the total population considered are at a high risk and form a part of the male to female risk ratio. Almost all states have the risk male to female ration close to 1 indicating that approximately more or less both males and females are equally at risk of cardiovascular diseases in 2016 to 2018. Cardiovascular disease (CVD) is the leading cause of death worldwide, yet important differences exist between men and women as there has been research on this. From past research, men generally develop CVD at a younger age and have a higher risk of coronary heart disease (CHD) than women and women, in contrast, are at a higher risk of stroke, which often occurs at older age [1]. Thus, in our analysis, we don’t see a contrasting difference between men and women as in this dataset we considered the overall risk to cardiovascular diseases instead of the bifurcation between coronary hear disease (CHD) and stroke for our analysis.

Task 3: Calculate the individual count for each indicator of a cardiovascular disease for people in Michigan between years 2016 to 2018 who have mobility disability.

Interpretation: For individuals in Michigan with mobility disability, it can be seen that more number of individuals are at a risk for major cardiovascular disease with a risk percentage of 11.67%. We can also see that more number of individuals in Michigan were at some form of cardiovascular disease risk in the year 2017 as compared to 2016 and 2018.

## References:

[1] Bots SH, Peters SAE, Woodward M Sex differences in coronary heart disease and stroke mortality: a global assessment of the effect of ageing between 1980 and 2010 BMJ Global Health 2017;2:e000298. 

[2] https://www.nimh.nih.gov/health/statistics/what-is-prevalence

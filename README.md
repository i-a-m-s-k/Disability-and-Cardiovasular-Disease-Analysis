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

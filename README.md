# Pymaceuticals Analysis with Tableau
----
## Project Overview

The goal of this project was to analyze drug treatment on tumor volume, metastasis and survival using the Pandas Library and the Jupyter Notebook and Matplotlib.
1. Create a scatter plot that shows how the tumor volume changes over time for each treatment.
2. Create a scatter plot that shows how the number of metastatic sites changes over time for each treatment.
3. Create a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate (%))
4. Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.

### Data retrieval and cleaning.

  The initial analysis was performed in with with Pandas in Jupyter Notebook in the repo [Pymaceuticals](https://github.com/TomBerton/Pymaceuticals). In this analysis I used the original csv files to create this [Tableau visualizations](https://public.tableau.com/profile/thomas.berton#!/vizhome/PseudoPharmaceuticalAnalysis/ChemotherapyonMetatasisandSurvival).
## Summary
1.	After 45 days of chemotherapy, Capomulin and Ramicane were more effective at reducing tumor volume by 19.5% and 22.3%, respectively. 

<p align="center"> 
  <img src="https://github.com/TomBerton/Pymaceuticals-Tableau/blob/master/images/Tumor%20Response%20To%20Treatment.png" width="500"/>
 </p>

<p align="center"> 
  <img src="https://github.com/TomBerton/Pymaceuticals-Tableau/blob/master/images/Tumor%20Change%20over%2045%20Days.png" width="500"/>
 </p>
 
 2.	After 45 days of chemotherapy, Capomulin and Ramicane had a greater capacity to reduce the average number of metastatic sites, 1.5 and 1.25, respectively, while other chemotherpeutic drugs have an average of 2-3 times more metastatic sites. 
 
<p align="center"> 
  <img src="https://github.com/TomBerton/Pymaceuticals-Tableau/blob/master/images/Metastatic%20Spread%20During%20Treatment.png" width="500"/>
 </p>

3. Finally, treatment with Capomulin and Ramicane resulted in a better mouse survival, 84% and 80%, respectively, over 45 days 		than with the other treatments, which ranged between 36-56% survival.
<p align="center"> 
  <img src="https://github.com/TomBerton/Pymaceuticals-Tableau/blob/master/images/Percent%20Mouse%20Survival.png" width="500"/>
 </p>

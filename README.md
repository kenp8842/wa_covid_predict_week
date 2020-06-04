# Predicting total positive COVID-19 cases for a week in WA and King County
Project to predict the number of positive COVID-19 cases in Washington state and King County for the week 4/20/20 to 4/26/20. I used
data from the state Department of Health and Washington State Hospital Association websites. Fatality data was also included and 
predicted. 

The Washington state model performed better than the King county model. The MAE for the week was approximately 230 for Washington state
and about 200 for King County. 

## Data Sources
https://www.doh.wa.gov/Emergencies/NovelCoronavirusOutbreak2020COVID19/DataDashboard

https://www.wsha.org/for-patients/coronavirus/coronavirus-tracker/

## EDA

I looked at the distributions of Washington state and King county COVID-19 cases and fatalities. I also created and examined an exponential growth factor to get idea of just how exponential the current spread was.

![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/covid_scatter_plots.png)
![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/covid_exp_factor.png)


## Model Results

![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/wa_covid_polynomial_fit.png)
![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/wa_covid_results.png)
![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/kingco_covid_poly_fit.png)
![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/kingco_covid_results.png)
![](https://github.com/kenp8842/wa_covid_predict_week/blob/master/covid_results_graphs.png)

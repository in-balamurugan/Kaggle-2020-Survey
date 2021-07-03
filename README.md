# Data Science Jungle: Large firm or Small Firm; AWS or GCP; Countries with best salaries based on Kaggle 2020 Survey

A peek into Kaggle survey 2020

## Blog link [here](https://balamurugan.netlify.app/post/kaggle-survey/)

## About survey  
Kaggle.com conducts annual survey among it's users. Survey is dominated by data professionals and data enthusiasist.
Survey is gold mine for people to understand the sentiments in the data industry. Analysis tries to decode three broad themes around size of the company, technology used specifically the cloud platform and how salary is influenced by experience, language one knows and finally country adjusted for cost of living.

## List of questions to be answered

1) What is the difference in working for small and large firm?
2) What is the cloud technology kagglers looking to learn in next 2 years?
3) How does experience,country living and language known influence data science salary?

## Analysis Summary
Want to build something from ML models from scratch? Goto small firms Are you better off in places with smooth sailing ML models over cloud? Goto large firms Based on the learning wishes, Google Cloud will be a dominant force in the future. Want a better cost of living data salary? Head to USA or second best to UAE. Python is not a major influencer in salaries as it is already widely used.

## Library Used
Basic manipulation done with pandas and numpy. Plotly used for visualistion.  Scikit-leanr is used for linear Regression modelling

## Data Quality
Data doesn't have any mandatory fields and hence the quality of missing rows are high. NANs on inspecting fields are ignored. Also, salary levels are very low even after adjsuting for the cost of living  and hence botton 10percentile has been trimmed. 

## Data Preparation
Repetitve tasks are captured under functions that does comparision and picking columns under specific catrogry. Tidy model is practised wherever feasible.

## Modeling 
Most of the insights are derived through charts plotted throug plotly package . For the analysing salary influence, linear regression in scikit package is used. 

## Evaluation 
Linear regression coefficietnts are used as proxy measure for the influence. R2 validated through stats models is at 0.37.

## Deployment
Insights learnt from analysis is captured in the blog [here](https://balamurugan.netlify.app/post/kaggle-survey/)


## Folder Structure

Root
|-- kaggle-survey-data-jungle-size-tech-and-salary .ipynb
|-- data
|       |-- kaggle_survey_2020_responses.csv
|       |-- cost of living 2020.csv


## Acknowledgments

1. https://www.kaggle.com/joeypp/cost-of-living-numbeo-dataset
2. https://www.kaggle.com/spitfire2nd/enthusiast-to-data-professional-what-changes/
3. https://www.kaggle.com/kailex/education-languages-and-salary

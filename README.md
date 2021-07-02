# Kaggle-2020-Survey
A peek into Kaggle survey 2020

## About survey  
Kaggle.com conducts annual survey among it's users. Survey is dominated by data professionals and data enthusiasist.
Survey is gold mine for people to understand the sentiments in the data industry. Analysis tries to decode three broad themes around size of the company, technology used specifically the cloud platform and how salary is influenced by experience, language one knows and finally country adjusted for cost of living.

## Data Quality
Data doesn't have any mandatory fields and hence the quality of missing rows are high. NANs on inspecting fields are ignored. Also, salary levels are very low even after adjsuting for the cost of living  and hence botton 10percentile has been trimmed. 

## Data preparation
Repetitve tasks are captured under functions that does comparision and picking columns under specific catrogry.

## Modeling 
Most of the insights are derived through charts plotted throug plotly package . For the analysing salary influence, linear regression in scikit package is used. 

## Evaluation 
Linear regression coefficietnts are used as proxy measure for the influence. R2 validated through stats models is at 0.37.

## Deployment
Insights learnt from analysis is captured in the blog [here](https://balamurugan.netlify.app/post/kaggle-survey/)

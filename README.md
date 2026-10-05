\# Spatio-Temporal Machine Learning for Malaria Risk Mapping and Prediction in Kenya



\## About the project



This project focuses on using machine learning to understand and predict malaria risk across Kenya.



The study uses data from 47 counties covering the period from January 2016 to December 2025. It brings together malaria surveillance data with information on rainfall, temperature, vegetation, population, and malaria control interventions.



The main aim is to understand how these factors relate to malaria incidence and to develop models that can help identify areas and periods with higher malaria risk.



\## What I worked on



In this project, I worked with county-level malaria data and developed a modelling workflow for analysing malaria risk over time and across different parts of Kenya.



The work includes data preparation, exploratory analysis, model development, model evaluation, visualisation, and interpretation of model results.



I compared several machine learning and deep learning approaches, including Random Forest, XGBoost, CNN-LSTM, CNN-GRU, and CNN-Transformer models.



\## Data



The analysis covers 47 counties in Kenya from January 2016 to December 2025.



The variables used in the analysis include:



\- Malaria cases and incidence

\- Rainfall

\- Temperature

\- Vegetation

\- Population

\- Insecticide-treated net (ITN) indicators

\- Indoor residual spraying (IRS) indicators

\- Malaria treatment indicators

\- Previous malaria incidence and other time-based variables



The original research datasets are not included in this repository.



\## Modelling approach



I used a time-based approach to separate the data into training and testing periods.



The training data cover January 2016 to December 2022, while January 2023 to December 2025 was used as the test period.



The models considered in the project include:



\- Random Forest

\- XGBoost

\- CNN-LSTM

\- CNN-GRU

\- CNN-Transformer



Model performance was assessed using R², RMSE, and MAE.



I also used SHAP to better understand which variables contributed to the model predictions.



\## Results



XGBoost gave the strongest performance among the models evaluated in the current analysis.



On the test data, the model achieved:



R² = 0.8945



RMSE = 0.00661



The analysis also showed that environmental factors such as rainfall, vegetation, and temperature were important in explaining malaria risk. Interactions between some of these environmental variables were also important.



The results were used to produce maps showing observed malaria incidence, predicted risk, and areas with relatively higher malaria risk.



\## Visualisations



Some of the outputs included in this repository are:



\- Observed malaria maps

\- Predicted malaria maps

\- XGBoost risk maps

\- Malaria hotspot maps

\- Temporal trends

\- Seasonal patterns

\- Correlation analysis

\- Model performance comparisons

\- Predicted versus actual values

\- SHAP analysis



\## Tools used



R and RStudio were used for much of the statistical analysis and visualisation.



Python was used for machine learning and deep learning workflows.



Other tools and libraries used in the project include:



\- Python

\- R

\- Pandas

\- NumPy

\- Matplotlib

\- ggplot2

\- XGBoost

\- Jupyter Notebook

\- LaTeX

\- Git and GitHub



\## Repository contents



The repository contains the main LaTeX files for the thesis, selected R and Python analysis files, and selected figures from the research.



The raw datasets and geographic data are not included because they are subject to data access and usage restrictions.



\## About me



I am Ngeywo Cherop Lindah, a Mathematics graduate and master's student interested in data analysis, machine learning, mathematical modelling, and quantitative research.



This project allowed me to apply mathematical and computational methods to a real public health problem, particularly the analysis and prediction of malaria risk in Kenya.



\## Project status



The project is part of my ongoing research work. The repository will be updated as the analysis, documentation, and research outputs develop.


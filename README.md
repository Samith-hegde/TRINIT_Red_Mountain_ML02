# TRINIT_Red_Mountain_ML02

# Topic: Observing from Space
The Greenhouse Gases observing (GOSAT) is the world’s first spacecraft to measure the concentrations of carbon dioxide and methane, the two major greenhouse gases from space where, as The Orbiting Carbon Observatory-2(OCO-2)is the first National Aeronautics and Space Administration((NASA) satellite designed to measure atmospheric carbon dioxide(C02) with the accuracy, resolution, and coverage needed to quantify CO2 fluxes(sources and sinks) on regional scales

# Objective
The main task is to use GOSAT and OCO-2 data and build/compare Machine Learning or Deep Learning Models to better predict CO2 over the surface of Earth for a smaller area.

# Red Mountain's submission
              using Python and Google Colab
1) We downloaded the data available on NASA's website, and imported the CO2 emissions data for 1 day using NetCDF4.
2) We plotted the correlation map between all the features in the dataset, and selected only those which had a high degree of correlation with the target variable: 'xco2' (the CO2 level).
3) We split the data into training and validation sets, and preprocessed the numerical data by sending it through a Standard Scaler pipeline. 
4) We trained and tested the data on Random Forest Regressor model, and evaluated it using rmse (Root Mean Squared error) metric, and obtained an rmse of  0.14386 for the training data, and an rmse of 0.47341 for the testing data.
5) Additionally, we wrote the code for extracting emissions data of multiple days from the large amounts of raw data available in NASA's website.


# Weather-forecasting-using-Recurrent-Neural-Networks

## Introduction 
This repository contains the material for my Bachelor's thesis titled "Weather forecasting using Recurrent Neural Networks" completed between October 2020 and March 2021 at the University of Glasgow. It is important to note that this README file plays the role of a summary of the thesis. In order to allow the reader to delve into more details I have uploaded the complete .pdf report among the files of this repository. 
A special thank you goes to to professor [Vladislav Vyshemirsky](https://scholar.google.co.uk/citations?user=trgOvPoAAAAJ&hl=en), my thesis supervisor.

## Framework
The aim of this project is to perform time series prediction and to compare the performances of Recurrent Neural Networks (RNNs) with the ones obtained by different ARIMA models. The dataset on which this thesis is built upon is the [Jena Climate Dataset](https://www.kaggle.com/datasets/mnassrib/jena-climate), which contains weather data recorded in Jena, Germany, every 10 minutes from the start of 2009 until the end of 2016. The variable on which this time series forecasting will focus is the Temperature variable.

## Models
The following models have been implemented during the course of the experiment:
1. Baseline model: simplest model possible, the prediction for next day's temperature is simply the temperature of the current date; 
2. ARIMA model: well known statistical model which is commonly used for time series prediction due to its ability of accounting for seasonality in the data;
3. LSTM: A special case of Recurrent Neural Network that enables better flow of information along the hidden states of the recurrent network.
<p align="center"><img src="https://user-images.githubusercontent.com/104196258/229573811-a600f2b3-7c81-4a04-8b5e-6d26b71767a8.png" width="700">

To better understand their behaviour, they have been tested on input sequences of length 24h, 48h and 1000h. Moreover, in order to give a more complete view on their performances, they have been used to predict temperature from 1h all the way up to 24h in advance.

## Results
I will report only a subset of the results due to the high number of graphs that have been generated for this study, for a complete comparison please refer to the report presented in this directory.
<p align="center"><img src="https://user-images.githubusercontent.com/104196258/229577846-f312cf9b-f355-4d99-a5b1-13032143b907.png" width="700">
<p align="center"><img src="https://user-images.githubusercontent.com/104196258/229577830-355a9891-2b6e-491f-819d-5e39081640cf.png" width="700">

## Technical Skills and Tools Applied
![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![ARIMA](https://user-images.githubusercontent.com/104196258/229590486-6c208f49-fecf-4b1d-8954-cdca575931c4.svg)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![sklearn](https://user-images.githubusercontent.com/104196258/229583604-78e5e360-5a54-4530-997a-b022f798e2d0.svg)![ARIMA](https://user-
![numpy](https://user-images.githubusercontent.com/104196258/229590239-8c7d67e1-1f19-4e87-962c-30b20dd967af.svg)
![pandas](https://user-images.githubusercontent.com/104196258/229590240-601a1dac-f88a-4b61-848d-02e02b8c73c0.svg)
![seaborn](https://user-images.githubusercontent.com/104196258/229590242-678704f4-330b-48dc-8d37-fa4c766e03b6.svg)


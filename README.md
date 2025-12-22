# Shark Movement Forecasting: An Assessment for Ocean Recreational Safety

Authorship: Isabella Parlato

_________

## Project Overview

### Synopsis

Shark presence is an important but difficult-to-predict factor affecting ocean recreation safety. This project examines whether tiger shark (Galeocerdo cuvier) presence near the eastern coast of Cape Canaveral, Florida, can be predicted using a combination of environmental, spatial, and temporal conditions. By integrating logged shark detections with offshore buoy historical meteorological data spanning from 2010-2019, several supervised and unsupervised models were evaluated to understand when certain factors align with elevated shark presence risk. The results show that spatial location is a dominant predictor, while environmental and temporal variables contribute more limited predictive power on their own. These findings suggest that while predictive tools can help with identifying patterns of elevated shark presence risk, future improvements will require denser shark tracking data and more ecologically informative predictors before such models can be deployed in more interactive ways for casual public use as directionally informative tools to better understand risk indications for shark presence.


### Research Question

Can we predict the likelihood of tiger shark (Galeocerdo cuvier) presence along the western North Atlantic coastline near the East of Cape Canaveral, Florida, using spatial, temporal, and environmental conditions, in order to inform ocean recreation risk?

### Primary Stakeholders

- Surfers and other people interested in ocean recreation

### Secondary Stakeholders

- Government departments or other parties interested in maintaining ocean recreational safety

- Tourism boards

### Hypothesis

While tiger shark movement is influenced by biological factors such as life stage, and prey availability, we hypothesize that environmental and temporal conditions - particularly temperature, sea level pressure, wind conditions, and seasonality - are associated with elevated likelihood of coastal presence and can be anticipated using a predictive risk model.

### Prediction

We expect that integrating shark movement data with environmental and temporal conditions will produce a model capable of identifying periods of heightened shark presence risk, particularly during warmer temperatures, calmer weather conditions, and known seasonal migration windows.

## Data & Analysis

### Datasources

- Dataset utilized from Regularized satellite tracks from: Ocean warming alters the distributional range, migratory timing, and spatial protections of an apex predator, the tiger shark (Galeocerdo cuvier) - https://pubmed.ncbi.nlm.nih.gov/35023247/

- Buoy 41009 from National Buoy Data Center: historical standard meteorological data was pulled by year from 2010 to 2019 - https://noaa-mirror.org/www.ndbc.noaa.gov/station_page.php@station=41009


### Response/Outcome Variable

Shark presence as is detected by the receivers so taking into account both timing and location. I will be using this as a binary of Shark presence (1) or Shark absence (0) 

### Predictor Variables

- Air temperature (Celsius)
- Wind Speed (m/s)
- Wind Direction
- Sea level pressure (hPa)
- date (month, day, year)
- timestamp, hour, and minute
- Location: longitude and latitude
- datetime


### Analysis Plan

- [X] Data Wrangling & Preprocessing

- [X] Exploratory Data Analysis (EDA)

- [X] Preprocessing & Feature Engineering

- [X] Classification Modeling using Unsupervised and Supervised Models

- [X] Model Evaluation

- [X] Final Review & Interpretations of Results


## Technical Details

### Unsupervised Models

- K-Means Clustering
- Sampled Hierarchical Clustering
- Principal Component Analysis (PCA)
- Gaussian Mixture Model (GMM)

### Supervised Models

- Baseline Logistic Regression - using default L2 regularization (no tuning)
- Penalized Logistric Regression (L1, L2, ElasticNet)
- Gradient Boosting Classifer
- Random Forest Classifier

### Coding Language

- Python




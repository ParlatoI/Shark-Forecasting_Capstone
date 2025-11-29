# Shark Movement Forecasting: An Assessment for Ocean Recreational Safety

Authorship: Isabella Parlato

_________

## Project Overview

### Background

As surfers and other people interested in using the ocean for recreation, we always need to be mindful of safety levels from a variety of factors. Whereas factors like high swell and rip currents are monitored and even predicted days out, sharks are a very present factor that can impact safety but are still lacking in monitoring. There are existing apps that track tagged sharks but I have yet to see anything that seeks to further that knowledge in a more predicative way to use past history and common factors to forecast days where there is likely to be a higher chance of sharks near the beaches. 


### Research Question

What factors determine Tiger Shark (Galeocerdo cuvier) movement and can we use them to predict likelihood of shark presence along the coastline? 

### Primary Stakeholders

- Surfers and other people interested in ocean recreation

### Secondary Stakeholders

- Government departments or other parties interested in maintaining ocean recreational safety

- Tourism boards

### Hypothesis

Shark movement along the coastline is strongly influenced by a combination of climate, life cycle, and ocean factors, particularly water temperature, age and type of shark, and time of year, because these factors determine sharks’ abilities to survive colder northern coastal waters and biological inclinations like going to common nesting areas for mating.

### Prediction

I expect that integrating ocean condition data and weather conditions with Shark tracking data will allow for a model that is capable of predicting the likelihood of shark presence. I believe that we’ll likely see trends of more sharks further up the coastline at beaches when ocean temperatures are warmer, and generally calmer (so not during hurricane impacted times), and depending upon seasonal migration times.

## Data & Analysis

### Datasources

Final datasets to be determined

### Response/Outcome Variable

Shark presence as is detected by the receivers so taking into account both timing and location. I will be using this as a binary of Shark presence (1) or Shark absence (0) 

### Predictor Variables

- Dataset utilized from Regularized satellite tracks from: Ocean warming alters the distributional range, migratory timing, and spatial protections of an apex predator, the tiger shark (Galeocerdo cuvier) - https://pubmed.ncbi.nlm.nih.gov/35023247/

- Buoy 41009 from National Buoy Data Center: historical standard meteorological data was pulled by year from 2010 to 2019 - https://noaa-mirror.org/www.ndbc.noaa.gov/station_page.php@station=41009

- Buoy 41010 from National Buoy Data Center: historical standard meteorological data was pulled by year from 2010 to 2019 - https://www.ndbc.noaa.gov/adcp_data.php?station=41010

### Analysis Plan

- [X] Data Wrangling & Preprocessing

- [X] Exploratory Data Analysis (EDA)

- [ ] Preprocessing & Feature Engineering

- [ ] Classification Modeling & Forecasting/Time-Aware Analysis

- [ ] Model Evaluation

- [ ] Final Review & Interpretations of Results

### Potential Pitfalls

- Accessability of the datasets needed to perform this research project as initially intended so the scope will need to be modified accordingly based on data availability.

- Sharks are complex biological creatures so there are many variables that could influence their movement patterns, however, I need to be mindful of how much my system would be able to handle when it comes to processing and then using it to train models (i.e. not very feasible to have to wait for hours for training to be completed). Taking a sampling and/or reducing the dataset as needed should help with mitigating issues related to this.

### How will we know if the question is answered?

There will be clear patterns between the environmental variables being used and shark movement. Thus, the final model is able to demonstrate predictive accuracy in shark presence patterns.

### How will we know if the hypothesis is supported?

If the model is able to accurately predict “future” shark movement accurately then we’ll know that there is enough variance in model parameters (i.e. the combination of features and model choice) to support my hypothesis that they’re factors in shark movement along the coastline.

## Technical Details

### Coding Languages & Tools

- Python
- R
- Tableau 


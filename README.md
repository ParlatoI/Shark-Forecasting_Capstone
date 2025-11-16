# Shark Movement Forecasting: An Assessment for Ocean Recreational Safety

Authorship: Isabella Parlato

_________

## Project Overview

### Background

I surf in Massachusetts, typically on the North Shore, so I would personally be interested in having an idea of if there’s a higher chance of more shark presence at certain beach breaks. I have yet to try surfing down in the Cape just because of the known large shark populations that frequent there. I also believe that a project like this could be helpful to a wide variety of people like shark researchers, other surfers, and even those in charge of maintaining beach safety, like lifeguards and Cape Code tourism boards.

There are live shark trackers that exist already and there are also wave forecasting applications that are used for prospective ocean and wave conditions for water recreation, especially surfing. So this project seeks to add another factor when looking at ocean recreational conditions and as such, I believe that this is a novel question as I haven’t seen any other projects yet that seek to do this.

### Research Question

What facors determine shark movement and can we use them to predict likelihood of shark presence along the coastline?

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

Final predictor variables to be determined

### Analysis Plan

- [ ] Data Wrangling & Preprocessing

- [ ] Exploratory Data Analysis (EDA)

- [ ] Classification Modeling & Forecasting/Time-Aware Analysis

- [ ] Model Evaluation

- [ ] Final Review & Interpretations of Results

### Potential Pitfalls

- Accessability of the datasets needed to perform this research project as initially intended so the scope will need to be modified accordingly based on data availability.

- Sharks are complex biological creatures so there are many variables that could influence their movement patterns, however, I need to be mindful of how much my system would be able to handle when it comes to processing and then using it to train models (i.e. not very feasible to have to wait for hours for training to be completed). Taking a sampling and/or reducing the dataset as needed should help with mitigating issues related to this.

- Although I would like to have this project focus on Great White Sharks, it may expand to other sharks within the Lamnid Shark family like the shortfin makos, longfin makos, salmon sharks, and porbeagles, depending on what the final datasets end up containing for available shark tracking information.

### How will we know if the question is answered?

There will be clear patterns between the environmental variables being used and shark movement. Thus, the final model is able to demonstrate predictive accuracy in shark presence patterns.

### How will we know if the hypothesis is supported?

If the model is able to accurately predict “future” shark movement accurately then we’ll know that there is enough variance in model parameters (i.e. the combination of features and model choice) to support my hypothesis that they’re factors in shark movement along the coastline.

## Technical Details

### Coding Languages & Tools

- Python
- R
- Tableau 


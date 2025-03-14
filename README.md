# Air-Pollution-Cardiovascular-Dissease

## *Project Idea*

This project aims to investigate the relationship between air pollution metrics (CO2, SO2, and other pollutants) and cardiovascular disease prevalence across different states. I hypothesize that regions with higher air pollution levels will show correspondingly higher rates of cardiovascular diseases. By analyzing historical pollution data alongside cardiovascular health statistics, I intend to identify potential correlations and assess whether specific pollutants have stronger associations with heart disease than others.

## *Description of Dataset*
The project will utilize two primary datasets:

### *Cardiovascular Disease Dataset*
- *The State of Peoples That Have This Condition*: The states of peoples that have a cardiovascular disease
- *The State Codes of Peoples That Have This Condition*: The state codes of peoples that have a cardiovascular disease
- *Condition Type*: The conditions of peoples

### *Air Pollution Dataset*
- *Carbon Dioxide (CO2) Levels*: Historical measurements by state
- *Sulfur Dioxide (SO2) Concentrations*: Recorded levels over multiple years
- *Nitrogen Oxide (NO2)*: Concentration measurements across states
- *The Exact Location*: Record of location
- *The Date Of Measures*: Dates of records

## *Plan*
### *Data Collection*
- *Cardiovascular Data Sources*:
  - I will use Kaggle and Hugging Face Datasets

- *Air Pollution Data Sources*:
  - EPA's Air Quality System (AQS) database


### *Data Analysis Approach*

1. *Exploratory Data Analysis*
   - Visual mapping of pollution levels and heart disease rates by state
   - Time series analysis of both variables to identify temporal relationships
   - Correlation matrices between different pollutants and cardiovascular metrics

2. *Statistical Analysis*
   - Multiple regression models to identify strongest predictor pollutants
   - Lag analysis to account for delayed health effects from pollution exposure

3. *Visualization and Presentation*
   - Interactive maps showing pollution and disease overlays
   - Time-series graphs demonstrating trends over the study period
   - State-by-state comparison tables highlighting significant findings

### *Tools and Technologies*
- *Python*: Primary programming language for data analysis
- *Pandas & NumPy*: For data manipulation and calculation
- *Matplotlib & Seaborn*: For visualization and statistical graphics
- *GeoPandas*: For geographical data visualization
- *Scikit-learn*: For statistical modeling and regression analysis
- *Jupyter Notebooks*: For documentation and sharing analysis process

## *Expected Outcomes*
- Identification of statistically significant relationships between specific air pollutants and cardiovascular disease rates
- Assessment of which pollutants pose the greatest risk to heart health
- Creation of a predictive model that estimates cardiovascular disease risk based on pollution exposure
- Policy recommendations for pollution control based on health impact findings
- Framework for further research into specific mechanisms of pollution-related heart damage

## *Potential Challenges*
- Variability in data collection methods across states
- Controlling for confounding variables (lifestyle factors, genetic predisposition)
- Distinguishing correlation from causation
- Accounting for population mobility between states

This project will contribute valuable insights into the public health impacts of air pollution, potentially informing both environmental policy and cardiovascular disease prevention strategies.

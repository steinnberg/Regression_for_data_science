# Regression_for_data_science

# Predicting : Gross Efficiency
The objective of the exercice is to understand the efficiency of an industrial plant and to be able to perform an accurate but trustable prediction of this efficiency.
A power plant provides energy as **output** : *GrossPower*.  
As an **input**, the plant use *Gas* (with different quality, content,...) and deliver energy in the atmospheric condition described by the *AirHumidity, AirPressure, AirTemperature* .
The target variable to predict  is *GrossEfficiency*.
The other variables (excluding *#LineFullDataSet* and *Timestamp* are explanatory).

## Request:
- Show how you got a first overview of the dataset
- Predict *GrossEfficiency* with 
 *'AirHumidity', 'AirPressure', 'AirTemperature',
       'GasCHRatio', 'GasCO2Concentration', 'GasEthaneConcentration',
       'GasHexaneConcentration', 'GasHhvEnergy', 'GasIbutaneConcentration',
       'GasIpentaneConcentration', 'GasLhvEnergy', 'GasMethaneConcentration',
       'GasN2Concentration', 'GasNbutaneConcentration',
       'GasNeopentaneConcentration', 'GasNpentaneConcentration',
       'GasPropaneConcentration', 'GasRelativeDensity', 'GasWobbeInf',
       'GasWobbeSup', 'GrossPower'*
 - Provide one or more metrics assessing the quality of the fit
 - Describe -as text / comment- how you would improve the previous parts if you would have more time (Optional)

## Some Guidances
- Plot some variables to help understanding the behavior, the outliers  
	Please insert comments below the graphs
	It is not necessary to apply all changes / cleaning as for a project, but simply describe in a few words what is the conclusion / what would you do?
- Evaluate Correlations
- Apply standard prediction models : GLM (statistical analysis would be appreciated)
- Apply a classical ML algorithm ( RF, GMM, XGboost,...)

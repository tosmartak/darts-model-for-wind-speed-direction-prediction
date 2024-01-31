# Darts Model application for wind energy prediction
Accurate prediction of wind direction and speed are important for various sectors, including aviation, energy production, and public safety. This work is motivated by the need to improve the accuracy and efficiency of wind direction and speed forecasts in Nigeria, which can have significant impacts on various sectors.

The aim of this project is to compare the different machine learning algorithms available in Darts Model to know how accurately we can predict `wind direction` and `wind speed` in Bauchi State, a Northern Nigerian State. This work can inform other States prediction with available data.

Carefully considering the scope and objectives of our research project and the resources available, such as computational power, time, and data quality, to decide on the forecast horizons to evaluate and with the aim to provide a comprehensive analysis, the models over `1 hour, 2 hours, 6 hours, 12 hours, 24 hours and 48 hours` lag were evaluated. This would allow us to examine the strengths and weaknesses of the different models across a range of forecast horizons, which could be useful across various applications and sectors.

## Choosing the Metrics to Measure Performance of our Model
Different evaluation metrics, such as mean absolute error (MAE) and root mean squared error (RMSE) were considered, to assess the accuracy and reliability of the different models. This would enable us to provide a more comprehensive analysis of the performance of the models and their suitability for different applications and sectors.

## Link to External Resources Related to this Project
Info | Description and Links
--- | ---
Data Main Source | [Nigeria Solar Radiation Measurement Data](https://energydata.info/dataset/nigeria-solar-radiation-measurement-data)
Journal Publication | [Link would be posted soon](#) </br> citation:.

## Repository Tree
```bash
darts-model-for-wind-speed-direction-prediction/
├── LICENSE.md
├
├── README.md						# read me file shwoing summary of project
├
├── data						# folder containing original, resampled and model results data
│   ├── bauchi-data-resampled-hourly-27042023.csv	# resampled hourly data with mean only and selected variables without period
│   ├── bauchi-data-resampled-hourly-ext.csv		# detailed resampled hourly data with mean, max, period for all data elements
│   ├── bauchi-data-resampled-hourly-extv2.csv		# resampled hourly data with mean only and selected variables with period
│   ├── solar-measurements_nigeria-bauchi_qc.csv	# Original Bauchi State solar measurement data
│   ├── solar-measurements_nigeria-kano_qc.csv		# Original Kano State solar measurement data
│   └── model-results					# data folder containing all model results as well as separated results
│       ├── all_model_results.numbers			# data containing all model results with all parameters combined
│       ├── model_results with 1-hour lag.csv		# data containing all model results using 1-hour lag
│       ├── model_results with 2-hour lag.csv		# data containing all model results using 2-hour lag
│       ├── model_results with 6-hour lag.csv		# data containing all model results using 6-hour lag
│       ├── model_results with 12-hour lag.csv		# data containing all model results using 12-hour lag
│       ├── model_results with 24-hour lag.csv		# data containing all model results using 24-hour lag
│       ├── model_results with 48-hour lag.csv		# data containing all model results using 48-hour lag
│       └── model_results with neural networks.csv	# data containing all model results using neural networks
├
├── notebooks						# folder with jupyter notebooks implemented for the project
    ├── EDA.ipynb					# Exploratory data analysis findings notebook	
    ├── Darts_Predict_WD_WS_Lag_1.ipynb			# Different darts model implementation with 1-hour lag
    ├── Darts_Predict_WD_WS_Lag_2.ipynb			# Different darts model implementation with 2-hour lag
    ├── Darts_Predict_WD_WS_Lag_6.ipynb			# Different darts model implementation with 6-hour lag
    ├── Darts_Predict_WD_WS_Lag_12.ipynb		# Different darts model implementation with 12-hour lag
    ├── Darts_Predict_WD_WS_Lag_24.ipynb		# Different darts model implementation with 24-hour lag
    ├── Darts_Predict_WD_WS_Lag_48.ipynb		# Different darts model implementation with 48-hour lag
    └── Darts_Predict_WD_WS_neural_networks.ipynb	# Different darts neural network model implementation
```

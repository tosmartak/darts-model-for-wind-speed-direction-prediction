```
darts-model-for-wind-speed-direction-prediction/
├── data                                            # folder containing original, resampled and model results data
    ├── bauchi-data-resampled-hourly-27042023.csv   # resampled hourly data with mean only and selected variables without period
    ├── bauchi-data-resampled-hourly-ext.csv        # detailed resampled hourly data with mean, max, period for all data elements
    ├── bauchi-data-resampled-hourly-extv2.csv      # resampled hourly data with mean only and selected variables with period
    ├── solar-measurements_nigeria-bauchi_qc.csv    # Original Bauchi State solar measurement data
    ├── solar-measurements_nigeria-kano_qc.csv      # Original Kano State solar measurement data
    └── model-results                               # data folder containing all model results as well as separated results
        ├── all_model_results.numbers               # data containing all model results with all parameters combined
        ├── model_results with 1-hour lag.csv       # data containing all model results using 1-hour lag
        ├── model_results with 2-hour lag.csv       # data containing all model results using 2-hour lag
        ├── model_results with 6-hour lag.csv       # data containing all model results using 6-hour lag
        ├── model_results with 12-hour lag.csv      # data containing all model results using 12-hour lag
        ├── model_results with 24-hour lag.csv      # data containing all model results using 24-hour lag
        ├── model_results with 48-hour lag.csv      # data containing all model results using 48-hour lag
        └── model_results with neural networks.csv  # data containing all model results using neural networks
 ``` 

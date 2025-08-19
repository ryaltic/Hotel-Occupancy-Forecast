## Hotel-Occupancy-Forecast

This project looks at forecasting different hotels in Python using Nixtla. There are multiple different types of hotels that are being forecasted such as vacation hotels, hotels in the city, and other types of hotels. 

This project dives deep into the EDA process preformed using pandas and seaborn to do the preprecessing and remove non-complete hotel data as well as get the data in a suitable format. There are multiple different models used to determine what predicts the hotel occupancy right and then use the best model for each hotel to predict the next months occupancy rates.

The project uses Naive, Seasonal Naive, AutoETS, AutoARIMA with exogenous predictors, XGBoost with exogenous predictors, TimeGPT with exogenous predictors, AutoNBEATS with exogenous predictors, AutoNHITS with exogenous predictors. The models is then evaulated based on mae, rmse, and bias but mae is the main metric used to evaluate the models.

TimeGPT performed the best with 6 hotel saying it was the best model, followed by XGBoost with 5, then AutoARIMA with 3 while AutoETS, SeasonalNaive, and AutoNBEATS all have 1.

A plot is then shown for only the timegpt models showing actuals vs predicted then a plot is shown for the best model for the hotel vs the actual.

Overall, TimeGPT seems to be the best model followed by XGBoost and both models seem to mimic the actual hotel occupancy rate fairly well

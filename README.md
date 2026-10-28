# -Real-Time-Weather-Nowcasting
Real-Time Weather Nowcasting is a machine learning project developed using Python to predict temperature for the next six hours. The project collects hourly weather data from the Open-Meteo API, including temperature, humidity, atmospheric pressure, and wind speed.
# Real-Time Weather Nowcasting Using Machine Learning

## 1. Introduction

Real-Time Weather Nowcasting is a machine learning project that predicts temperature for the next six hours using hourly weather data. It uses Python and machine learning algorithms to analyze weather patterns and generate temperature predictions.

## 2. Objectives

* To collect hourly weather data from an API.
* To analyze historical weather information.
* To train machine learning models for temperature prediction.
* To predict temperatures for the next six hours.
* To visualize actual and predicted temperatures using graphs.

## 3. Technologies Used

* Programming Language: Python
* Libraries: NumPy, Pandas, Matplotlib, Requests, Scikit-learn
* API: Open-Meteo Weather API
* Environment: Google Colab or Jupyter Notebook

## 4. Machine Learning Algorithms

**Linear Regression:** Used to predict temperature by learning relationships between weather features and temperature.

**Random Forest Regressor:** Uses multiple decision trees to predict temperature and capture more complex patterns in weather data.

## 5. Features

* Fetches hourly weather data for a selected city.
* Uses temperature, humidity, pressure, and wind speed.
* Creates features from previous weather observations.
* Trains and evaluates machine learning models.
* Predicts temperature for the next six hours.
* Displays predictions in tables and graphs.
* Compares model performance using Mean Absolute Error (MAE).

## 6. Working Process

1. Import the required Python libraries.
2. Select a city for weather data.
3. Retrieve the city's geographical coordinates.
4. Fetch hourly weather data from the Open-Meteo API.
5. Prepare the data and create machine learning features.
6. Train the Linear Regression and Random Forest models.
7. Evaluate the models using MAE.
8. Generate temperature predictions for the next six hours.
9. Display the results using tables and graphs.

## 7. How to Run the Project

1. Open the `ML_PROJECT_1.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Ensure that an internet connection is available.
3. Run the notebook cells in order.
4. Change the city name in the configuration cell if required.
5. View the model evaluation results and six-hour temperature predictions.

## 8. Data Source

The project uses the Open-Meteo API to retrieve weather information.

Geocoding API: https://geocoding-api.open-meteo.com/

Weather API: https://api.open-meteo.com/

## 9. Applications

* Educational machine learning projects.
* Learning weather-data analysis.
* Understanding regression algorithms.
* Demonstrating short-term temperature prediction.

## 10. Limitations

Prediction accuracy depends on the available weather data and the machine learning models. This project is intended for educational purposes and should not be used as an official weather-warning system.

## 11. Conclusion

This project demonstrates how Python and machine learning algorithms can be used to analyze weather data and predict temperatures for the next six hours. It also provides a visual representation of the predictions to make the results easier to understand.

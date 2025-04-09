# F1 Predictions 2025 - Machine Learning Model

Welcome to the F1 Predictions 2025 repository [continue]. This project uses machine learning, FastF1 API data, and historical F1 race results to predict race outcomes for the 2025 Formula 1 season.

---

## Project Overview

This repository contains a Gradient Boosting Machine Learning model that predicts race results based on past performance, qualifying times, and other structured F1 data. The model leverages:

- FastF1 API for historical race data  
- 2024 race results  
- 2025 qualifying session results  
- Feature engineering techniques to improve predictions  
- Ongoing data updates throughout the 2025 season to improve model performance  

## Data Sources

- **FastF1 API**: Fetches lap times, race results, and telemetry data  
- **2025 Qualifying Data**: Used for race-day prediction  
- **Historical F1 Results**: Processed from FastF1 for training the model  

## How It Works

1. **Data Collection**: The script pulls relevant F1 data using the FastF1 API.  
2. **Preprocessing & Feature Engineering**: Converts lap times, normalizes driver names, and structures race data.  
3. **Model Training**: A Gradient Boosting Regressor is trained using 2024 race results.  
4. **Prediction**: The model predicts race times for 2025 and ranks drivers accordingly.  
5. **Evaluation**: Model performance is measured using Mean Absolute Error (MAE).  

## Dependencies

- fastf1  
- numpy  
- pandas  
- scikit-learn  
- matplotlib  

## File Structure

For every race, the filename will be numbered to correlate with the race calendar.  
Example:  
- `prediction1.py` – Australia  
- `prediction2.py` – China  
- and so on...

## Model Performance

The **Mean Absolute Error (MAE)** is used to evaluate how well the model predicts race times.  
Lower MAE values indicate more accurate predictions.

## Future Improvements

- Incorporate weather conditions as a feature  
- Add pit stop strategies into the model  
- Explore deep learning models for improved accuracy

---

## **Contact & Repository Info**
- **Author**: Jordan Wright
- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  
- [GitHub Profile](https://github.com/JordanConallLuthaisWright)


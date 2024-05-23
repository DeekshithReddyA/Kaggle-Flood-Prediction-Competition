# Flood Prediction using Linear Regression

This repository contains the code for my submission to the [Kaggle Playground Series - Season 4, Episode 5](https://www.kaggle.com/competitions/playground-series-s4e5/overview) competition. The goal of the competition is to predict the occurrence of floods based on various environmental and geographical features.

## Overview of the Competition

Flooding is a significant natural disaster that can cause extensive damage to property and loss of life. The objective of this competition is to develop a model that accurately predicts the likelihood of floods based on historical data. The dataset provided includes various features such as rainfall, river water levels, soil moisture, and more.

Participants are required to build a machine learning model that can predict the target variable (whether a flood occurs) and are evaluated based on the R² score of their predictions on the test set.

## Project Structure

The project is divided into two main parts:
1. **Data Preprocessing**
2. **Model Training and Prediction**

### Data Preprocessing

The data preprocessing script handles the following tasks:
- Loading the dataset
- Handling missing values
- Scaling/Imputing features
- Splitting the data into training and testing sets

### Model Training and Prediction

The model training script includes:
- Loading the preprocessed data
- Training a Linear Regression model
- Evaluating the model using the R² score
- Making predictions on the test dataset

## Achievements

- Achieved an R² score of 84.49 on the test dataset using a simple Linear Regression model.


## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/flood-prediction.git
   cd flood-prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the data preprocessing script:
   ```bash
   python data_preprocessing.py
   ```

4. Run the model training and prediction script:
   ```bash
   python model_training.py
   ```

## Conclusion

This project demonstrates a basic approach to flood prediction using a Linear Regression model. While the model achieves a good R² score, there is potential for improvement by exploring more complex models and additional feature engineering.

For more details, please refer to the [Kaggle competition page](https://www.kaggle.com/competitions/playground-series-s4e5/overview).

---

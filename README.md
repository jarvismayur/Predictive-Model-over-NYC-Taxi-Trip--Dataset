# EDA with NYC Taxi Trip Dataset and Evaluation of Various ML Models

This project performs **Exploratory Data Analysis (EDA)** on the NYC Taxi Trip dataset and builds several machine learning models to predict taxi trip outcomes. The dataset contains detailed records of taxi trips in New York City, offering rich insights into urban transport patterns.

## Table of Contents
- [EDA with NYC Taxi Trip Dataset and Evaluation of Various ML Models](#eda-with-nyc-taxi-trip-dataset-and-evaluation-of-various-ml-models)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset](#dataset)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Machine Learning Models](#machine-learning-models)
  - [Results](#results)
  - [Installation](#installation)
  - [Technologies Used](#technologies-used)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Overview

This project explores the NYC Taxi Trip dataset, performing comprehensive **EDA** to understand the data and its features. Multiple machine learning models are developed, trained, and evaluated on their predictive performance for taxi trip-related metrics. The goal is to derive actionable insights and create reliable predictive models.

## Dataset

The dataset used in this project includes:
- **Pickup and Dropoff Times**: Time of the trip's start and end.
- **Geospatial Information**: Latitude and longitude of the pickup and dropoff locations.
- **Passenger Count**: Number of passengers in the taxi.
- **Trip Distance**: Total distance covered in the trip.

The dataset can be accessed from the NYC Taxi & Limousine Commission (TLC) data portal.

## Exploratory Data Analysis (EDA)

During EDA, the following aspects are analyzed:
- **Trip Distribution**: Analyzing the distribution of trip distances, durations, and locations.
- **Passenger and Payment Patterns**: Insights into average trip costs, most common pickup/dropoff locations, and the impact of different variables on trip price.
- **Temporal Trends**: Investigating patterns over time (e.g., busiest hours for trips).

Visualizations such as histograms, bar charts, and heatmaps are used to explore these features.

## Machine Learning Models

Multiple machine learning models are applied and evaluated, including:
1. **Linear Regression**
2. **Decision Trees**
3. **Random Forest**
4. **Gradient Boosting**
5. **K-Nearest Neighbors (KNN)**

Each model is trained and validated using appropriate metrics to predict variables such as:
- Trip duration
- Trip fare amount
- Passenger count

## Results

The performance of each model is compared using metrics like:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

The model performance is analyzed to determine which algorithm provides the most accurate predictions for different types of trips.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nyc-taxi-trip-prediction.git
   ```
2. Navigate to the project directory:

    ```bash

    cd nyc-taxi-trip-prediction
    ```
3. Install the necessary dependencies:

    ```bash

    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook:

    ```bash

    jupyter notebook
    ```
## Technologies Used
- Python: The main programming language for this project.
- Pandas: Data manipulation and preprocessing.
- NumPy: Numerical operations.
- Matplotlib & Seaborn: Data visualization.
- Scikit-learn: Machine learning models and evaluation.
## Usage
- Open the notebook eda_nyc_taxi_trip.ipynb to explore the EDA and model-building process.
- You can visualize the data and run the models by executing the code cells.
- Modify the parameters and models to experiment with different predictive techniques.
## Contributing
Contributions to this project are welcome! Feel free to submit pull requests or raise issues.

1. Fork the repository.
2. Create a new branch for your feature:
    ```bash

    git checkout -b new-feature
    ```
3. Commit your changes:
    ```bash

    git commit -m 'Add new feature'
    ```
4. Push to the branch:
    ```bash

    git push origin new-feature
    ```
5. Open a pull request.
## License
This project is licensed under the Apache License 2.0. See the LICENSE file for details.










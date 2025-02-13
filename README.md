# Car_Price_Regression
This project analyzes and predicts car prices using machine learning techniques. It includes data preprocessing, feature engineering, and model training with algorithms like Linear Regression, Random Forest, and SVM. The goal is to provide accurate price estimates while uncovering key factors influencing valuations



## Project Overview
This project focuses on analyzing and predicting car prices based on various attributes using advanced machine learning algorithms and statistical techniques. By leveraging a dataset containing features such as manufacturer, model, mileage, engine volume, and other relevant factors, the goal is to build a robust predictive model that provides accurate price estimates while also uncovering the most significant factors influencing car valuations.

## Goals
- Conduct Exploratory Data Analysis (EDA) to visualize and understand key trends in car pricing.
- Perform feature engineering and selection to identify the most relevant predictors.
- Preprocess the dataset, handling missing values, encoding categorical variables, and normalizing numerical features.
- Train and compare multiple machine learning models, including:
  - Linear Regression
  - Polynomial Regression
  - Lasso
  - Ridge
  - Random Forest
  - Support Vector Machines (SVM)
  - Decision Trees
  - K-Nearest Neighbors (KNN)
  - MLPRegressor
- Optimize models using hyperparameter tuning and cross-validation.
- Evaluate models based on R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
- Extract insights from feature importance analysis to improve interpretability.

## Dataset Description
The dataset contains several features crucial for car price prediction, including:
1. **Manufacturer** - Encoded categorical variable representing the car brand.
2. **Model** - Encoded categorical variable specifying the model type.
3. **Category** - Classification of the vehicle type (SUV, sedan, etc.).
4. **Mileage** - Total kilometers driven by the car.
5. **Engine Volume** - Size of the engine in liters.
6. **Fuel Type** - Type of fuel used (petrol, diesel, electric, etc.).
7. **Gear Box Type** - Transmission type (manual or automatic).
8. **Drive Wheels** - Indicates if the car is front-wheel, rear-wheel, or all-wheel drive.
9. **Doors** - Number of doors available in the car.
10. **Wheel Position** - Indicates left-hand or right-hand drive.
11. **Color** - Exterior color of the car.
12. **Price** - The target variable representing the car price.

## Installation and Usage
### Prerequisites
Ensure you have Python installed and install the required libraries using:
```sh
pip install -r requirements.txt
```

### Running the Notebook
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/car-price-regression.git
   ```
2. Navigate to the project directory:
   ```sh
   cd car-price-regression
   ```
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open and run `Car_Price_Regression.ipynb`.

## Project Structure
```
car-price-regression/
│-- data/               # Dataset storage
│-- notebooks/          # Jupyter Notebooks
│-- scripts/            # Python scripts for preprocessing & modeling
│-- README.md           # Project documentation
│-- requirements.txt    # Dependencies
```

## Conclusion

This project successfully demonstrates the use of machine learning techniques for car price prediction. By leveraging feature engineering, model selection, and hyperparameter tuning, we were able to develop a robust predictive model. The insights gained from feature importance analysis highlight the key factors influencing car valuations, which can be valuable for buyers, sellers, and automotive analysts. Future enhancements may include integrating deep learning models, expanding the dataset, and deploying the model as a web application for real-time predictions.

